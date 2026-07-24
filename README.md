<div align="center">

[🇰🇷 **한국어**](README.md) · [🇺🇸 English](README.en.md)

# Hi, I'm Chiyeon 👋

**AI Engineer**를 꿈꾸는 세종대학교 지능기전공학과 2학년입니다.

</div>

<br/>

## 👋 About Me

데이터로 문제를 정의하고, 모델로 답을 찾고, 서비스로 완성하는 AI 엔지니어를 꿈꾸고 있습니다.
촛불처럼 잔잔하게 끝까지 타오르는 사람입니다. 저만의 기술과 아이디어로 세상을 좋은 방향으로 바꾸길 소망합니다.😀

- 🎓 세종대학교 지능기전공학과 (Intelligent Mechatronics Engineering) 2학년
- 🔍 DACON 경진대회를 통해 정형·비전 데이터를 다루는 실전 감각을 키우는 중입니다
- 🤖 최근에는 Function Calling, LLM Agent 등 실제 서비스에 붙일 수 있는 AI에 관심이 많습니다
- 📱 모델을 모바일 앱·웹 서비스처럼 "쓸 수 있는 형태"로 완성하는 걸 좋아합니다
- 🧮 알고리즘 수학에 관심이 많아 틈틈이 공부 중입니다.

---

## 🏆 Competitions & Awards

| 대회 | 결과 | 주제 |
|:---|:---:|:---|
| [2024 생명연구자원 AI활용 경진대회 : 인공지능 활용 부문](https://dacon.io/competitions/official/236355/overview/description) | 61/940<br/>(상위 6.48%) | 암환자 유전체 변이 정보 기반 암종 분류 |
| [건설용 자갈 암석 종류 분류 AI 경진대회](https://dacon.io/competitions/official/236471/overview/description) | 32/342<br/>(상위 9.35%) | 건설용 자갈 이미지 기반 암석 종류 분류 (Vision) |
| [HAI(하이)! - Hecto AI Challenge](https://dacon.io/competitions/official/236493/overview/description) | 70/748<br/>(상위 9.35%) | 중고차 이미지 기반 차종 분류 (Vision) |
| [데이콘 x BDA 학습자 수료 예측 AI 경진대회](https://dacon.io/competitions/official/236519/overview/description) | 27/275<br/>(상위 9.81%) | 학습자 설문 데이터 기반 수료 여부 예측 |
| [26년 ALOM DEMO (@alomsejong)](https://www.instagram.com/alomsejong/) | 우수상(3등)🥉 | 특정 사진작가의 스타일을 학습해 실시간으로 촬영 구도 가이드 |
| [[SW중심대학사업단] 2026-1학기 AI·SW중심대학 디지털 경진대회 교내 선발](https://do.sejong.ac.kr/ko/program/all/view/4147) | 최우수상(2등)🥈 | Agent Navigation 예측 성능 극대화 (Kaggle 형식의 대회) |

---

## 💡 Projects

<table>
<thead>
<tr>
<th align="center">기간</th>
<th align="left">프로젝트</th>
</tr>
</thead>
<tbody>

<tr>
<td align="center" valign="top" width="150">

🔵<br>
**2025.05 ~ 2025.06**

</td>
<td valign="top">

### 🎯 [Catridge Case Detect](https://github.com/chiyeon01/Catridge_case-detect-project)
`Python` `Jupyter Notebook` `Object Detection`

군 복무 중 사격 훈련에서 겪은 탄피 회수 문제를 직접 풀어보고자 기획한 **실시간 객체 탐지** 프로젝트입니다.

- 흙먼지가 날리고 화질이 좋지 않은 환경에서도, 사람 눈으로 찾기 어려운 탄피를 실시간으로 탐지
- 빠르게 낙하하는 탄피도 실시간 프레임 속도로 정확히 추적
- 탄피가 겹치는 상황 등 한계를 직접 분석하고, augmentation · 열화상 카메라 결합 등 **개선 방향까지 문서화**

</td>
</tr>

<tr>
<td align="center">┃</td>
<td></td>
</tr>

<tr>
<td align="center" valign="top" width="150">

🔵<br>
**2025.07 ~ 2025.09**

</td>
<td valign="top">

### 💸 [ETF Service](https://github.com/chiyeon01/ETF-Service)
`Python` `Streamlit` `OpenAI Function Calling` `yfinance` `Sentence-Transformers`

적립식(DCA) ETF 투자자를 위한 **금융 AI Agent** 서비스입니다. *(AI 학습 및 파이프라인 설계 담당)*

- 실시간 뉴스, 한국은행 발간자료, 시장 데이터를 종합해 투자 비중 조절을 조언하는 챗봇
- Function Calling으로 주가 · 재무제표 · 뉴스 등 외부 데이터를 실시간 조회
- 코사인 유사도(Sentence-Transformers)로 직전 분석과 비교해 **중복 알림을 걸러내는 로직** 설계

</td>
</tr>

<tr>
<td align="center">┃</td>
<td></td>
</tr>

<tr>
<td align="center" valign="top" width="150">

🔵<br>
**2025.09 ~ 2025.12**

</td>
<td valign="top">

### 🛜 [Routing Network System](https://github.com/chiyeon01/Routing_Network_System)
`Streamlit` `Function Calling` `KT 믿:음 2.0 Mini`

**K intelligence 해커톤 2025 (Track1: AI Agent 개발)** 참가작으로, 기업마다 고유한 페르소나를 가진 AI Agent가 서로의 네트워크를 구성해 소통하는 프로토타입입니다.

- 기업 간 소통의 시간·공간적 제약을 줄이는 **Agent-to-Agent 네트워크** 설계
- 각 Agent가 자사 데이터베이스만 참조하도록 해 **정보 보안 문제를 구조적으로 해결**
- Function Calling을 도입해 **환각(hallucination) 현상을 줄이고** 응답 신뢰도 확보

📽️ [발표자료](https://www.canva.com/design/DAGxmiVe42Y/EvFHh2YEhw-YAZhYEEYcdg/edit?utm_content=DAGxmiVe42Y&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

</td>
</tr>

<tr>
<td align="center">┃</td>
<td></td>
</tr>

<tr>
<td align="center" valign="top" width="150">

🔵<br>
**2025.10 ~ 2026.02**

</td>
<td valign="top">

### 📸 [Retouch Your Photo](https://github.com/chiyeon01/Retouch_Your_Photo)
`Flutter` `Dart` `PyTorch Lite` `YOLO` `MobileNet`

특정 사진작가의 스타일을 학습해 실시간으로 촬영 구도를 가이드해주는 **Flutter 앱**입니다.

- YOLO(객체 탐지) · Depth Estimator(원근감 추정) · MobileNet(특징 추출) · Embedding(작가 스타일 추출) · Regression Layer를 결합한 **커스텀 모델을 직접 설계**
- 좌우 / 상하 / 앞뒤 / 기울기 / 회전 / Good까지 **6축 실시간 가이드** 제공
- PyTorch Lite로 온디바이스 추론을 구현해 카메라 화면에서 바로 피드백

📽️ [발표자료](https://www.canva.com/design/DAHAiN_OG68/3itKJNmlflSALfVwwKLIfw/edit?utm_content=DAHAiN_OG68&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton) · ✍️ [프로젝트 후기](https://velog.io/@chiyeon01/Project-Retouching-Your-Photo)

</td>
</tr>

<tr>
<td align="center">┃</td>
<td></td>
</tr>

<tr>
<td align="center" valign="top" width="150">

🟠<br>
2026.06 ~

</td>
<td valign="top">

### 🛣️ [Crack Detection System](https://github.com/chiyeon01/Crack_Detection_System)
`Arduino` `IOT COSS` `FastAPI` `PyTorch` `YOLO` 

도로의 미세한 균열을 센서를 통해 충격량을 1차적으로 파악하고, GPS와 Segmentation Model을 통해 최종적으로 균열의 상태를 파악해 지도에 표시하여 **도로 상태를 관리하는 시스템**입니다.

- 가속도 센서에서 0.1초간 정보를 받아 충격량 계산 후 임계값에 따라 처리
- 이후, 일정량 이상의 충격이 감지되면 IOT COSS로 GPS 정보와 함께 충격량도 저장 후, FastAPI서버에 전달
- FastAPI에서는 이 충격이 정말 균열에 의한 것인지 실시간 Camera를 통해 Segmentation Model로 분석 후 판단하여 UI에 띄우고 저장.

📽️ [발표자료](https://canva.link/z05u8pkmogeuden)

</td>
</tr>

</tbody>
</table>

## 🛠 Tech Stack

**Language**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Dart](https://img.shields.io/badge/dart-%230175C2.svg?style=for-the-badge&logo=dart&logoColor=white)

**Frontend**

![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white)

**Server**

![FastAPI](https://img.shields.io/badge/FastAPI-009485?style=for-the-badge&logo=fastapi&logoColor=white)

**Machine Learning / Deep Learning**

![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)

<br/>

## 📚 Currently Learning

모델을 더 다양한 형태의 서비스로 배포하고, 대용량 데이터까지 다룰 수 있는 엔지니어가 되기 위해 공부하고 있습니다.

![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)
![Spark](https://img.shields.io/badge/Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)

---

## 📚 Algorithm
[![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=jcy4023)](https://solved.ac/jcy4023/)

## 📊 GitHub Stats

<div align="center">

[![GitHub followers](https://img.shields.io/github/followers/chiyeon01?style=for-the-badge&logo=github&logoColor=white&label=Followers&color=181717)](https://github.com/chiyeon01?tab=followers)
[![View Repositories](https://img.shields.io/badge/GitHub-Repositories-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/chiyeon01?tab=repositories)

</div>

---

## ✉ Contact

[![Velog](https://velog-readme-stats.vercel.app/api/badge?name=03_is_good)](https://velog.io/@chiyeon01/series)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/chiyeon01)
