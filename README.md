# 1. 프로젝트 개요
---
### 💡그림 생성과 음악 및 코멘트를 곁들인 AI 일기 통합 서비스
> AI 그림생성 기술을 통해 사용자의 자기 표현을 돕고 그 과정에서의 감정에 대해 인지재구조화를 경험하게 하는 웹개발
> - 일기 작성 시 AI를 활용하여 작성한 일기 텍스트 분석
> - 일기의 내용에 맞는 그림 생성 및 감정 분석, 음악 추천 및 코멘트 제공
> - \(해당하는 그림\)
---

## 🔹 1. 기획배경 및 필요성
정신건강 관리에 대한 관심도가 증가하는 것에 비해 전문 상담 서비스의 높은 비용과 부정적 시선에 대한 장벽 때문에 제대로된 케어를 받지 못하는 MZ세대 증가

이를 예방적 관점에서 바라보고 접근성을 높이면서 사용자가 스스로를 치유하고 스트레스를 관리할 수 있게 도와줄 수 있는 서비스가 필요하다는 점 도출

자기 표현을 통해 부정적 감정을 환기하고 감정을 공감각적으로 파악하도록 도움을 주는 AI 통합형 일기 서비스 개발하고자 결정

## 🔹 2. 대상
- 상시 자기 치유와 힐링을 필요로 하는 사람
- 현실적 장벽으로 케어를 망설이는 사람

---

# 2. 목차
---
# 3.웹 화면 구성
## 🔹 1. 메인 페이지

![image](https://github.com/Three-Park/frontend_server/assets/128453499/8aa5a19c-59ec-4c23-aa80-e1db47f3efbd)

📖 화면 설명
1\)

2\) 나를 위한 AI : 

3\) 달력 보기 : 클릭 시 달력 페이지로 이동

## 🔹 2. 로그인 페이지

![image](https://github.com/Three-Park/frontend_server/assets/128453499/22b038df-5dce-41e7-a22f-2c5d55efe132)

📖 화면 설명

1\) 로그인 : 아이디, 패스워드 입력 후 클릭 시 일기 기록 페이지(3)로 이동

2\) 회원가입 : 클릭 시, 회원가입 페이지로 이동

## 🔹 2-2. 회원가입 페이지

📖 화면 설명

1\) 

2\) 

## 🔹 3. 일기 기록 페이지

![image](https://github.com/Three-Park/frontend_server/assets/128453499/05a650fb-b113-455f-a1b5-2d8f397d1923)

📖 화면 설명

1\) 이웃 추가 기능 : 클릭 시 이웃추가(5) 페이지로 이동

2\) 커뮤니티 기능 : 클릭 시 커뮤니티 페이지(6)로 이동

3\) 일기 작성 기능 : 클릭 시 일기 작성 페이지(4)로 이동

4\) 사용자 프로필

5\) 일기 모아보기 : 작성한 일기 한 번에 조회 가능. 카드 형식

## 🔹 4. 일기 작성 페이지

![image](https://github.com/Three-Park/frontend_server/assets/128453499/11bc3976-7039-4aec-8498-220ccfab58dc)


📖 화면 설명

1\) 제목 작성

2\) 일기 내용 작성

## 🔹 4-1. 일기 상세 페이지

![image](https://github.com/Three-Park/frontend_server/assets/128453499/4d22f4e2-dcb5-4655-a3da-0c818aa21e3f)

📖 화면 설명

1\) 음악 추천 기능

2\) 감정 분석 기능 : AI 기능을 통한 감정 분석 및 감정에 맞는 이모지 노출

3\) 코멘트 텍스트 : AI 기능을 통한 자동 코멘트 생성

4\) 자동 생성 그림 : 일기 내용 기반 자동 AI 그림 생성

5\) 삭제 기능 : 해당 일기 삭제 가능

6\) 돌아가기 : 클릭 시 메인 일기 기록 페이지(3)로 이동

## 🔹 5. 이웃 추가 페이지

![image](https://github.com/Three-Park/frontend_server/assets/128453499/4e279754-606c-4cbd-afbd-63194e9fb8c1)

📖 화면 설명

1\) 친구 추가 창 : 사용자 이름으로 친구 추가 의사 전송

2\) 친구 목록 : 친구 목록 한 번에 조회 가능

3\) 친구 추가, 거절, 삭제 가능

## 🔹 6. 커뮤니티 페이지

![image](https://github.com/Three-Park/frontend_server/assets/128453499/db956ff8-4e7e-4ad5-be4d-602e99dc2dad)

📖 화면 설명

1\) 일기 모아보기 : 친구 등록된 사용자와 자신의 일기 모두 모아보기

---

# 4. 개발 환경 및 구성

## 🔹 1. 감정-
