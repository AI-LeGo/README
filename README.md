<div align="center">
<img width="100%" alt="image" src="https://github.com/AI-LeGo/README/assets/108510929/3095e676-8a5a-44ea-a07c-4268dbd58a0a">
</div>
<br>

# 목차
1. [프로젝트 소개](#프로젝트-소개)
2. [프로젝트 목표](#프로젝트-목표)
3. [팀원 구성](#팀원-구성)
4. [개발 환경](#개발-환경)
5. [아키텍처 구조](#아키텍처-구조)
6. [역할 분담](#역할-분담)
7. [개발 기간 및 작업 관리](#개발-기간-및-작업-관리)
8. [프로젝트 사용 모델](#프로젝트-사용-모델)
9. [시연 과정](#시연-과정)
10. [시연 영상](#시연-영상)
11. [개선 목표](#개선-목표)
12. [프로젝트 후기](#프로젝트-후기)
<br>
<br>




## 프로젝트 소개

- Cartoon TTS는 만화/웹툰 이미지의 시각 정보를 청각 정보로 변환하는 서비스입니다.
- 사용자가 웹페이지에 이미지를 업로드하면 Emotional TTS를 통해 변환되며 감정이 담긴 생생한 오디오를 경험할 수 있습니다.

<br>

## 프로젝트 목표

|**1.웹 페이지 접속**|**2.Emotion TTS 변환할 이미지 업로드**|**3.텍스트를 Emotional Speech로 변환**|
| :---: | :---: | :---: |
| <img width="327" height="auto" alt="그림1" src="https://github.com/AI-LeGo/README/assets/108510929/ebbb6250-c354-451f-9b4c-3cec57cee1aa"> | <img width="327" height="auto" alt="22" src="https://github.com/AI-LeGo/README/assets/108510929/991c5b77-0d62-4280-b695-059f7b668825"> | <img width="327" height="auto" alt="3" src="https://github.com/AI-LeGo/README/assets/108510929/703d8aa1-299d-4b07-9b0b-128ab3657c02"> |

## 팀원 구성

<div align="center">

| **김규리** |**김나훈**| **김현우** | **심준석** |**이하준** | 
| :------: | :------:| :------: | :------: |:------: |  
| [<img src="https://avatars.githubusercontent.com/u/97076152?v=4" height=150 width=150> <br/> @GyuRiiii](https://github.com/GyuRiiii) | [<img src="https://avatars.githubusercontent.com/u/68880867?v=4" height=150 width=150> <br/> @hunnxx](https://github.com/hunnxx) | [<img src="https://avatars.githubusercontent.com/u/96505696?v=4" height=150 width=150> <br/> @NK590](https://github.com/NK590) | [<img src="https://avatars.githubusercontent.com/u/120085361?s=70&v=4" height=150 width=150> <br/> @LukeJS0326](https://github.com/LukeJS0326) | [<img src="https://avatars.githubusercontent.com/u/108510929?s=96&v=4" height=150 width=150> <br/> @ha789ha](https://github.com/ha789ha) |

</div>

<br>

## 개발 환경
- Deeplearning Model : [StyleTTS2](https://github.com/yl4579/StyleTTS2), [GPT-4 Vision](https://platform.openai.com/docs/guides/vision)
- Front : HTML, Bootstrap
- Back-end : Fastapi
- 버전 및 이슈관리 : Github, Github Issues, Github Project
- 협업 툴 : [Notion](https://www.notion.so/prgrms/1-362c4eb4c5b040a0aee8d683ac161ea7)
- 서비스 배포 환경 : AWS
<br>

## 아키텍처 구조
![아키텍쳐1](https://github.com/AI-LeGo/README/assets/108510929/873c5f99-77db-4ae1-90a5-07c389560102)

<br>

## 역할 분담

| 이름    | 분야                   | 주요 업무                             |
|---------|------------------------|---------------------------------------|
| 김규리 | Modeling               | Object/Emotion Detection, Prompt Engineering |
| 김나훈 | Modeling/MLOps         | Emotional TTS, 서비스 파이프라인 구축        |
| 김현우 | Front/Back-end          | 프론트/백엔드 시스템 설계, 서비스 파이프라인 구축 |
| 심준석 | Modeling               | Prompt Engineering, Image Captioning  |
| 이하준 | Modeling/Server         | Image Captioning, 데이터 수집 및 처리   |


## 개발 기간 및 작업 관리

### 개발 기간

- 전체 개발 기간 : 2023-12-09 ~ 2024-01-24
<br>

## 프로젝트 사용 모델

- [Image Captiong & Prompt Enginerring](https://github.com/AI-LeGo/Service-Backend/tree/main/tools)
- [Emotional-TTS](https://github.com/AI-LeGo/Emotional-TTS)
  
## 시연 과정
|1. 웹 페이지 접속|2. Emotion TTS로 변환할 이미지 업로드|
|:---:|:---:|
|![이미지1](https://github.com/AI-LeGo/README/assets/108510929/42e78607-3ba9-4705-8ec8-6a2f42a93ad2)|![이미지2](https://github.com/AI-LeGo/README/assets/108510929/ad3b3932-e91c-4dc5-a7e9-d773070c422f)|
|3. 알림창이 뜨며 음원 생성 완료|4. 음원 스크립트 전문과 오디오 파일 다운로드|
|![설명1](https://github.com/AI-LeGo/README/assets/108510929/111bc2e3-d9c3-4c4e-a00e-c2e974f7da5e)|![설명2](https://github.com/AI-LeGo/README/assets/108510929/82dcb284-e974-4959-b30f-984f6c981ac1)|


## 시연 영상

<br>

## 개선 목표
   - 한국어 Emotional-TTS 구현
   - 웹 페이지 기능 추가
<br>

## 프로젝트 후기
한정된 시간으로 웹 페이지에서 성우의 선택이나 발화 묘사 수준의 조절 등을 구현하지 못해 아쉬웠습니다. 또한, 한국어 감정 발화 데이터셋 및 한국어 Emotional-TTS 모델의 부재로 인해 영어 기반의 서비스를 개발하게 되었습니다. 따라서 향후 한국어 발화 데이터셋을 구축하고 이를 기반으로 한 학습이 진행된다면 국내 상용화 서비스를 제공할 수 있을 것으로 기대하고 있습니다.

