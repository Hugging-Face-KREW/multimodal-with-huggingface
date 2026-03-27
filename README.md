# 허깅페이스로 배우는 멀티모달 모델: 이미지 이해부터 생성, 파인튜닝까지

<!-- 책 표지 이미지 -->
<!-- <p align="center"><img src="cover.png" width="300"></p> -->
<p align="center"><img src="https://github.com/user-attachments/assets/e0676620-547b-403c-94bb-827a531f6631" width="350"></p>

이 저장소는 『허깅페이스로 배우는 멀티모달 모델: 이미지 이해부터 생성, 파인튜닝까지』(디지털북스) 도서의 실습 코드를 담고 있습니다.

---

## 책 소개

멀티모달 AI의 핵심 개념부터 실전 활용까지, 허깅페이스 생태계를 중심으로 체계적으로 안내합니다. CLIP, 비전 언어 모델(VLM), 디퓨전 기반 이미지 생성 모델 등 주요 멀티모달 모델의 원리를 이해하고, 직접 코드를 실행하며 파인튜닝과 최적화까지 경험할 수 있습니다.

---

## 목차

### Part 01. 허깅페이스 살펴보기

> 허깅페이스 생태계와 멀티모달 모델 활용을 위한 핵심 라이브러리를 소개합니다.

| 챕터 | 노트북 |
|:---|:---:|
| Chapter 01. 왜 허깅페이스인가? | - |
| Chapter 02. 허깅페이스 가입하기 | - |
| Chapter 03. 멀티모달 모델을 위한 허깅페이스 라이브러리 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](part01/ch03.ipynb) |

### Part 02. 멀티모달 모델 이해하기

> 멀티모달 모델의 기본 개념과 CLIP을 통해 이미지-텍스트 연결 원리를 알아봅니다.

| 챕터 | 노트북 |
|:---|:---:|
| Chapter 01. 멀티모달 모델에 대해서 알아보기 | - |
| Chapter 02. 이미지와 텍스트를 이해하는 CLIP | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](part02/ch02.ipynb) |

### Part 03. 멀티모달 모델을 활용한 이미지 이해

> 비전 언어 모델(VLM)의 구조를 이해하고, 실전 활용부터 파인튜닝까지 다룹니다.

| 챕터 | 노트북 |
|:---|:---:|
| Chapter 01. 비전 언어 모델 알아보기 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](part03/ch01.ipynb) |
| Chapter 02. 주요 비전 언어 모델 실전 활용 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](part03/ch02.ipynb) |
| Chapter 03. 특정 작업을 잘하도록 비전 언어 모델 파인튜닝하기 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](part03/ch03.ipynb) |

### Part 04. 멀티모달 모델을 활용한 이미지 생성

> 디퓨전 모델 기반 이미지 생성의 원리, ControlNet, DreamBooth/LoRA, 양자화 최적화를 실습합니다.

| 챕터 | 노트북 |
|:---|:---:|
| Chapter 01. 이미지 생성 모델 이해하기 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](part04/ch01.ipynb) |
| Chapter 02. 이미지 생성 모델을 더 효과적으로 제어하는 방법 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](part04/ch02.ipynb) |
| Chapter 03. 나만의 멀티모달 이미지 생성 모델을 학습하는 방법 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](part04/ch03.ipynb) |
| Chapter 04. 더 효율적으로 이미지 생성 모델을 사용하는 방법 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](part04/ch04.ipynb) |

### Part 05. 멀티모달 모델 더 알아보기

> 멀티모달 이해와 생성의 최신 트렌드와 심화 주제를 탐구합니다.

| 챕터 | 노트북 |
|:---|:---:|
| Chapter 01. 멀티모달 이해 더 알아보기 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](part05/ch01.ipynb) |
| Chapter 02. 멀티모달 생성 더 알아보기 | - |

<!--
---

## 실행 환경

- **Python**: 3.10+
- **주요 라이브러리**: `transformers`, `diffusers`, `datasets`, `accelerate`, `torch`, `Pillow`
- **GPU**: 일부 실습(파인튜닝, 이미지 생성 등)은 GPU 환경을 권장합니다. Google Colab의 무료 GPU를 활용할 수 있습니다.

```bash
pip install transformers diffusers datasets accelerate torch pillow
```

---
 
## 실행 방법

### Google Colab에서 실행하기

각 챕터의 Colab 배지를 클릭하면 Google Colab에서 바로 노트북을 열 수 있습니다.

### 로컬에서 실행하기

```bash
# 1. 저장소 클론
git clone https://github.com/[사용자명]/[저장소명].git
cd [저장소명]

# 2. 의존성 설치
pip install -r requirements.txt

# 3. 노트북 실행
jupyter notebook
```

---
-->

## 관련 링크

- 📖 [디지털북스 도서 페이지](https://www.digitalbooks.co.kr/326c0948-8461-8028-9fda-d1521e8d6cfe)
- 🛒 [예스24](https://www.yes24.com/product/goods/177059661) | [교보문고](https://product.kyobobook.co.kr/detail/S000219182705) | [알라딘](https://www.aladin.co.kr/shop/wproduct.aspx?ItemId=385518173)

---

## 정오표

도서의 오탈자나 코드 오류를 발견하시면 [Issues](../../issues) 탭에 등록해 주세요. 확인 후 반영하겠습니다.

---

## 라이선스

이 저장소의 소스 코드는 [MIT 라이선스](LICENSE)를 따릅니다.
