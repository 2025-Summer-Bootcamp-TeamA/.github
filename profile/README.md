<h1 align="center">


🏛️ 당신의 눈 앞에서 살아나는 예술, "MUSAÏQUE" 🏛️


</h1>

<div align="center" style="font-size:18px">
<br>
<b>

</b><br>
<br><br>
<b>Art comes alive before your eyes, MUSAÏQUE! </b> </div>
<p align="center">

</p>

<p align="center">
  <img width="800" alt="LMUSAÏQUE 스플래시" src="https://github.com/user-attachments/assets/b18ec4af-b253-48f5-96e6-e82950970f5b">
</p>

## 📣 Introduction

<table width="1200px">
    <thead>
    </thead>
    <tbody>
    <tr>
         <td width="600" align="center">
            <img src="./assets/모나리자 시작 최종.mp4" width="280"/>
        </td>
        <td width="600" align="center">
            <div align="left">
<br/>
<br><br>박물관을 방문하면 멋진 작품들은 많지만, 긴 설명문과 어려운 용어, 혹은 외국어로 된 안내 때문에 작품의 의미와 이야기를 제대로 이해하기 어렵다는 한계가 있었습니다. 이로 인해 많은 관람객들이 작품을 그냥 흘려보거나, 진짜 이야기를 놓치고 돌아가는 경우가 많았습니다.
<br><br>MUSAÏQUE는 이런 문제를 해결하기 위해 기획되었습니다. 관람객이 작품 사진과 설명 사진을 스마트폰으로 촬영하면, AI가 작품 속 주인공을 인식해 실제로 작품이 말을 거는 것처럼 직접 자신의 역사와 제작 배경을 흥미진진한 쇼츠 영상으로 들려주는 새로운 형태의 AI 박물관 가이드 서비스입니다.
<br><br>복잡하고 지루하게 느껴졌던 박물관 관람 경험을 쉽고, 재미있고, 기억에 남는 특별한 순간으로 바꿔주는 것이 MUSAÏQUE의 목표입니다.
<br/><br/>

</br>
</div>
</tr>
</tbody>
</thead>
</table>

<br>
<br>


## Demo

### 메인 페이지 & 영상 생성
- 위치 기반으로 박물관을 선택하고, 온보딩과 함께 주변 박물관 정보를 확인할 수 있습니다.
- 작품 사진과 설명을 찍어 업로드하면, AI가 주인공을 인식해 맞춤형 아바타 영상을 만들어줍니다.

<p align="center">
  <img src="./assets/presentation_1.gif" width="280"/>
  &nbsp;&nbsp;&nbsp;
</p>



### 영상 재생
- 생성된 쇼츠 영상을 바로 감상할 수 있습니다. 작품 인물이 직접 이야기를 들려줍니다.
<p align="center">
  <img src="./assets/gold_3x.gif" width="280"/>
  &nbsp;&nbsp;&nbsp;
</p>

<br>

### 라이브러리
- 모든 영상이 박물관별로 정리되어 저장되며, 원하는 영상을 쉽게 찾아볼 수 있습니다.
<p align="center">
  <img src="./assets/liv_3x.gif" width="280"/>
  &nbsp;&nbsp;&nbsp;
</p>


<br>

## System Architecture


<p align="center">
   <img src="https://github.com/user-attachments/assets/9e222e3f-c147-49df-b833-3b8cc9f17ea2" width="850" height="600"/>
</p>
<p align="center">
   <img src="https://github.com/user-attachments/assets/233bb378-8567-4e2a-8b0e-755ecdcdf1f0" width="850" height="600"/>
</p>
</br>
</br>

## API

<p align="center">
 <img src="https://github.com/user-attachments/assets/f7810832-3a7c-4279-a276-e0f3e26d3c16"/>
</p>

</br>
</br>

## ERD
<p align="center">
 <img src="https://github.com/user-attachments/assets/db3eacd2-cfd3-4ce3-af0f-705188ae48f3" width="850" height="600" />
</p>

</br>
</br>

## Monitoring


<table>
  <tr>
    <td colspan="2" align="center"><b>Redis</b></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/577b08b7-4c0d-42e9-b33a-6b93bbe2d88f" width="100%"></td>
    <td><img src="https://github.com/user-attachments/assets/5e76c8f4-707e-45f4-bc44-eba4012182a2" width="100%"></td>
  </tr>

  <tr>
    <td colspan="2" align="center"><b>cAdvisor</b></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/d80b63e7-8e65-4f0c-8ed9-68abcaa88706" width="100%"></td>
    <td><img src="https://github.com/user-attachments/assets/6727d7d4-609b-4104-895e-add7ff90fb0b" width="100%"></td>
  </tr>

  <tr>
    <td colspan="2" align="center"><b>Node Exporter</b></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/5cc08d54-d1ea-43fc-b4eb-11b4ff3ade58" width="100%"></td>
    <td><img src="https://github.com/user-attachments/assets/acf9f44a-f049-4759-8443-661ba8308d38" width="100%"></td>
  </tr>
</table>

<br><br>



## Tech Stack

|**분야**|**사용기술**|
|:-------------------:|:---------:|
|<b>Frontend</b>|<img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"> <img src="https://img.shields.io/badge/Expo-1C2024?style=for-the-badge&logo=expo&logoColor=white"> <img src="https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white"> <img src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white">|
|<b>Backend</b>|<img src="https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white"> <img src="https://img.shields.io/badge/MySql-4479A1?style=for-the-badge&logo=MySql&logoColor=white"/> <img src="https://img.shields.io/badge/Rabbitmq-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white"> <img src="https://img.shields.io/badge/celery-%23a9cc54.svg?style=for-the-badge&logo=celery&logoColor=ddf4a4"> <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=Redis&logoColor=white"> <img src="https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=modelcontextprotocol&logoColor=white">|
|<b>DevOps</b>| <img src="https://img.shields.io/badge/docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"> <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white">|
|<b>AI</b>| <img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white"> <img src="https://img.shields.io/badge/Dalle3-412991?style=for-the-badge&logo=openai&logoColor=white"> <img src="https://img.shields.io/badge/gpt4o-412991?style=for-the-badge&logo=openai&logoColor=white"> <img src="https://img.shields.io/badge/google vision api-4285F4?style=for-the-badge&logo=google&logoColor=white">|
|<b>Monitoring</b>|<img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white"> <img src="https://img.shields.io/badge/grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white"> <img src="https://img.shields.io/badge/cadvisor-2196F3?style=for-the-badge&logo=cadvisor&logoColor=white">|
|<b>etc</b>|<img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white"> <img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white"> <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white"> <img src="https://img.shields.io/badge/-Swagger-%23Clojure?style=for-the-badge&logo=swagger&logoColor=white"> <img src="https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white"> <img src="https://img.shields.io/badge/Zoom-0B5CFF?style=for-the-badge&logo=zoom&logoColor=white"> <br> <img src="https://img.shields.io/badge/visualstudiocode-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" alt="icon" /> |

</br>
</br>

## How to start
```sh
# clone our project
git clone https://github.com/2025-Summer-Bootcamp-TeamA
```
```sh
# Create the .env file in the /.env path
VISIONSTORY_USE_MOCK=
DISABLE_AUTH=

DJANGO_SETTINGS_MODULE=
SECRET_KEY=
DEBUG=

# MySQL
DB_TYPE=
DB_HOST=
DB_PORT=
DB_USER=
DB_PASSWORD=
DB_NAME=

# Smithery
SMITHERY_API_KEY=
SMITHERY_PROFILE=

# Brave Search MCP
BRAVE_MCP_BASE_URL=
BRAVE_API_KEY=
BRAVE_MCP_PROFILE=

# Fetch MCP
FETCH_MCP_BASE_URL=
FETCH_API_KEY=
FETCH_MCP_PROFILE=

# VisionStory
VISIONSTORY_API_KEY=

# Google
DEFAULT_FILE_STORAGE=
GS_BUCKET_NAME=
GOOGLE_APPLICATION_CREDENTIALS=
GOOGLE_MAPS_API_KEY=

# OpenAI
OPENAI_API_KEY=

# TRAEFIK
TRAEFIK_DASHBOARD_USERS=

# RabbitMQ
RABBITMQ_DEFAULT_USER=
RABBITMQ_DEFAULT_PASS=

# Redis
REDIS_PASSWORD=

# celery
CELERY_BROKER_URL=
```
```sh
# build docker
docker compose up --build -d
```
<br></br>


## 🧑‍💻 팀원 소개

| 항목 | 권유리 | 허준영 | 장영균 | 권혁찬 | 조성환 |
|------|--------|--------|--------|--------|--------|
| **Profile** | <img src="https://github.com/user-attachments/assets/19792a35-da75-4b84-bc5a-5bec6b081485" width="80"/> | <img src="https://github.com/user-attachments/assets/15bbcb58-23cc-4dcf-8d8e-32da234a5c9a" width="80"/> | <img src="https://github.com/user-attachments/assets/c0786a26-aafb-4f45-a72e-9877c7a9cf41" width="80"/> | <img src="https://github.com/user-attachments/assets/f2d16237-d629-45bd-93df-34653c10bdbd" width="80"/> | <img src="https://github.com/user-attachments/assets/b26c50c1-86b4-413a-a535-7e700a8fb116" width="80"/> |
| **Role** | Team Leader<br>Backend<br>DevOps | Frontend<br>UI/UX | Backend | Backend | Backend |
| **GitHub** | [@yuripbong](https://github.com/yuripbong) | [@gjwnsdud2083](https://github.com/gjwnsdud2083) | [@Gro-J](https://github.com/Gro-J) | [@Chanhyeok-creator](https://github.com/Chanhyeok-creator) | [@llsung1111](https://github.com/llsung1111) |

