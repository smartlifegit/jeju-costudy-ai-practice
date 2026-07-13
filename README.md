# 딥러닝 기초와 생성형 AI 기초 — 실습 자료

제주대학교 공과대학 · 사물인터넷과 소프트웨어, 인공지능 공동학습프로그램
담당 : 박미애 교수 (경북대학교 AICOSS)

대학 학부생 대상 실습형 강의(1~4차시)의 강의자료(PPT)와 Colab 실습 노트북을 모아 둔 저장소입니다.

---

## 실습 노트북 — Colab에서 바로 열기

아래 **[Colab에서 열기]** 를 누르면 각자 사본으로 실행됩니다. 파일을 내려받을 필요가 없습니다.
실행 전 **런타임 → 런타임 유형 변경 → T4 GPU** 로 바꾼 뒤, 위에서부터 순서대로 실행하세요.

| 순서 | 노트북 | 내용 | 열기 |
| --- | --- | --- | --- |
| 1부 실습 | `lab1_cnn.ipynb` | CNN으로 컬러 숫자(colorMNIST) 분류 | [Colab에서 열기](https://colab.research.google.com/github/smartlifegit/jeju-costudy-ai-practice/blob/main/lab1_cnn.ipynb) |
| 2부 실습 ① | `lab2_autoencoder_vae.ipynb` | 오토인코더 · VAE (MNIST) | [Colab에서 열기](https://colab.research.google.com/github/smartlifegit/jeju-costudy-ai-practice/blob/main/lab2_autoencoder_vae.ipynb) |
| 2부 실습 ② | `lab2_cdcgan.ipynb` | 조건부 DCGAN (MNIST) | [Colab에서 열기](https://colab.research.google.com/github/smartlifegit/jeju-costudy-ai-practice/blob/main/lab2_cdcgan.ipynb) |
| 2부 실습 ③ | `lab2_sdxl_turbo.ipynb` | SDXL-Turbo 텍스트→이미지 생성 | [Colab에서 열기](https://colab.research.google.com/github/smartlifegit/jeju-costudy-ai-practice/blob/main/lab2_sdxl_turbo.ipynb) |

> 2부 실습 세 개는 개념 순서(오토인코더/VAE → GAN → 디퓨전)대로 진행합니다.

## 강의자료 (PPT)

| 차시 | 파일 | 내용 |
| --- | --- | --- |
| 1부 | [`deck1_dl_basics.pptx`](https://github.com/smartlifegit/jeju-costudy-ai-practice/blob/main/deck1_dl_basics.pptx) | 딥러닝 모델 기초 (퍼셉트론 → DNN → CNN → ResNet) |
| 2부 | [`deck2_genai_basics.pptx`](https://github.com/smartlifegit/jeju-costudy-ai-practice/blob/main/deck2_genai_basics.pptx) | 생성형 AI 기초 (생성 모델 · Transformer · GAN · 디퓨전) |

---

## 파일을 직접 내려받으려면

노트북 파일 화면에서 오른쪽 위 **다운로드 아이콘(⬇ Download raw file)** 을 누르면 `.ipynb` 파일이 저장됩니다.
그 파일을 [Google Colab](https://colab.research.google.com/) → **업로드** 탭에서 열 수 있습니다.
(화면에 코드가 그대로 보이는 상태에서 `Ctrl+S` 로 저장하면 `.txt` 로 잘못 저장될 수 있으니, 반드시 다운로드 아이콘을 사용하세요.)

## 실습 환경 안내

- 실습은 설치가 필요 없는 **Google Colab** 에서 진행합니다. (개인 노트북 + Google 계정)
- 딥러닝 학습과 이미지 생성에는 **GPU(T4)** 가 필요합니다.
- 무료 계정은 GPU 배정이 안 될 수 있어 **2인 1조** 진행을 권장합니다.
- `lab2_sdxl_turbo.ipynb` 는 첫 실행 시 모델(약 7GB)을 내려받으므로 시간이 걸립니다.

---

## 이 실습이 지향하는 것 : 개념 → 구현 → 해석

코드는 AI(생성형 AI 도구)에게 맡기고, 학생은 **정확히 지시(프롬프트)하고, 결과를 확인하고, 해석**합니다.
코드를 외우는 것이 아니라 **원리를 이해하고, AI를 부리고, 결과를 해석하는 힘**을 기르는 것이 목표입니다.
