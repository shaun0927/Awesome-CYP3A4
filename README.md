# Awesome-P450  
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

🔥 **Boost up AI 2025 – CYP3A4 Inhibition Prediction** 경진대회와 CYP450-AI 연구를 위한 논문·데이터·코드·튜토리얼 큐레이션.

<p align="center">
  <img src="docs/banner_cyp3a4.png" width="65%">
</p>

---

## 목차
- [배경](#배경)
- [대회 개요](#대회-개요)
- [평가 지표](#평가-지표)
- [데이터셋](#데이터셋)
- [Milestone Papers](#milestone-papers)
  - [1. Biochemistry & Structural](#1-biochemistry--structural)
  - [2. Assay & HTS](#2-assay--hts)
  - [3. QSAR / ML](#3-qsar--ml)
  - [4. GNN / DL](#4-gnn--dl)
  - [5. Benchmark Datasets](#5-benchmark-datasets)
- [Starter Kits & 베이스라인](#starter-kits--베이스라인)
- [Training / Inference 툴](#training / inference-툴)
- [평가·유틸리티](#평가·유틸리티)
- [강의 & 튜토리얼](#강의--튜토리얼)
- [기여 방법](#기여-방법)
- [라이선스](#라이선스)

---

## 배경
- **CYP3A4**: 인간 간‧소장에 가장 풍부한 P450 이소효소 → 허가 의약품의 30 ~ 50 % 대사  
- **목표**: 화합물 1,681종의 **SMILES + 저해율(%)** 데이터로 IC₅₀ 대신 %inhibition 회귀 모델을 만들고 **Normalized RMSE + Pearson r** 혼합 점수로 경쟁  
- **주최**: 국가생명연구자원정보센터 (NBRIC)  
- **기간**: 2025-05-01 ~ 2025-07-31  

## 대회 개요
| 항목 | 내용 |
|------|------|
| 주제 | **CYP3A4 저해율(%) 예측 회귀 모델** |
| 제출 파일 | `sample_submission.csv` → `ID, Inhibition` |
| 제출 횟수 | 1일 최대 3회 |
| 공식 페이지 | 🔗 (추가 예정) |
| 커뮤니티 | Discussions / Slack 채널 |

## 평가 지표
| 기호 | 정의 | 식 |
|------|------|---|
| **A** | Normalized RMSE |  ![nRMSE](docs/img/nrmse_formula.svg) |
| **B** | Pearson Correlation | ρ(ŷ, y) |
| **Score** | 최종 점수 | `0.5 × (1 − min(A, 1)) + 0.5 × B` |

## 데이터셋
| 파일 | 크기 | 컬럼 |
|------|------|------|
| `train.csv` | 1,681 × 3 | `ID`, `Canonical_SMILES`, `Inhibition`(%) |
| `test.csv` | — × 2 | `ID`, `Canonical_SMILES` |
| `sample_submission.csv` | — × 2 | 제출 예시 |

EDA 노트북: [`notebooks/eda.ipynb`](notebooks/eda.ipynb)

---

## Milestone Papers

### 1. Biochemistry & Structural
| 연도 | 논문 | 기여 |
|------|------|------|
| 1986 | Beaune *et al.* **PNAS** | 인간 CYP3A4 cDNA 최초 규명 |
| 2004 | Williams *et al.* **Science** | 첫 X-ray 구조 → 다중 기질 포켓 제시 |
| 2025 | Li *et al.* **Nat Commun** | Cryo-EM + AI로 선택적 억제제 결합 모티프 해석 |

### 2. Assay & HTS
| 연도 | 논문 | 기여 |
|------|------|------|
| 1998 | Ito & Houston **Clin Pharmacokinet** | 케토코나졸 기전-기반 불가역 억제 실험계 확립 |
| 2021 | Veith dataset 발표 (TDC) | 12 k 화합물 HTS IC₅₀ 공개 |

### 3. QSAR / ML
| 연도 | 논문 | 기여 |
|------|------|------|
| 2006 | Ekins *et al.* **JCIM** | 다중-프로브 QSAR, multitask 아이디어 |
| 2023 | Zhang *et al.* **J Appl Toxicol** | RF/GBDT vs GCN 성능 비교 |

### 4. GNN / DL
| 연도 | 논문 | 기여 |
|------|------|------|
| 2021 | Nguyen-Vo **Front Pharmacol** | **DeepCYPs** FP-GNN, AUC 0.90+ |
| 2022 | Liu *et al.* **JAFC** | DL-가상 스크리닝으로 식이성 억제제 발굴 |
| 2024 | Wang *et al.* **ICLR** | SMILES-Transformer 대규모 사전학습·회귀 SOTA |

### 5. Benchmark Datasets
| 데이터셋 | 크기 | Split | 출처 |
|----------|------|-------|------|
| **CYP3A4_Veith** | 12 k | Scaffold | Huang 2021 |
| **DeepCYPs-71k** | 71 k | Random/Scaffold | Nguyen-Vo 2021 |
| **MolData-CYP3A4** | 8 k | Time | Wang 2024 |

---

## Starter Kits & 베이스라인
| 폴더 | 모델 | 특징 |
|------|------|------|
| `starter/xgb_fp` | **XGBoost + ECFP4** | 간단·고속 CPU baseline |
| `starter/attentivefp` | **AttentiveFP** | 5-fold CV, scaffold split |
| `starter/mpnn` | **D-MPNN (PyG)** | AMP + OneCycleLR, GPU |

> `conda env create -f environment.yml` 후 바로 실행 가능.

## Training / Inference 툴
- **PyTorch Geometric / DGL** – GNN 구현  
- **DeepChem / MolNet** – QSAR 데이터 로더  
- **Optuna / W&B Sweeps** – HPO & 실험 추적  
- **vLLM / TensorRT-LLM** – 대용량 모델 추론 최적화

## 평가·유틸리티
- `utils/metric.py` – Normalized RMSE & Pearson r  
- `utils/scaffold_split.py` – Bemis-Murcko scaffold split  
- `utils/visualize_error.ipynb` – 실제 vs 예측 시각화

## 강의 & 튜토리얼
- **DeepChem Drug Discovery** MOOC  
- **Graph ML for Molecules (Stanford CS 273)**  
- **ACoP CYP 워크숍** – PBPK 시뮬레이션 입문

---

## 기여 방법
1. PR 전에 `pre-commit run --all-files` 실행  
2. **논문·데이터·코드** 추가 → 관련 섹션 표 갱신  
3. 이슈 / Discussion 탭에서 질문·아이디어 공유

## 라이선스
- 코드·문서: **MIT License**  
- 대회 데이터: 주최 측 비상업적 연구용 라이선스

