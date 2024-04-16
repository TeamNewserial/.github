![뉴시리얼 썸네일](https://github.com/TeamNewserial/.github/assets/71147610/b341caaa-2d84-4150-a1bb-0f313443accf)
### 프로젝트 소개
---
간단하게 시리얼을 먹듯, 경제 뉴스를 간편하게 챙겨주는 반응형 웹 **경제 뉴스 요약 플랫폼**  입니다.

경제 뉴스의 어려운 문장을 페러프레이징해 쉬운 문장으로 바꿔주고 다양한 퀴즈를 풀며 경제 상식을 쌓을 수 있습니다. 퀴즈를 풀며 귀여운 강아지 펫 ‘우유’를 성장시켜보세요!

📌 **배포 링크** : https://teamnewserial.github.io/

### 개발 기간
---
2023.11.10~2024.03.18

### 기술 스택 & 개발 환경
---
**프론트엔드** : Typescript, React, javascript, @emotion/styled, redux

**개발환경**: MySQL, VSCode, InteliJ, Redis, Git

**백엔드** : Spring Boot 3.1.5, Java JDK 17, Spring Security 6.1.5, JPA Hibernate

**배포환경** : Github pages, CLOUDTYPE

### 화면 디자인
---
<img src="https://github.com/TeamNewserial/.github/assets/71147610/6aebda2c-4dce-4782-88eb-7010c81f8ac7" width=160> 
<img src="https://github.com/TeamNewserial/.github/assets/71147610/df2c5484-1bd4-4912-a469-2eb681beef5c" width=160> 
<img src="https://github.com/TeamNewserial/.github/assets/71147610/1b68a4bd-fb53-4907-861c-52a4c4fff5d9" width=160> 
<img src="https://github.com/TeamNewserial/.github/assets/71147610/3a1efbad-e7d7-4477-a0c1-d0dfb966ae8f" width=160> 
<img src="https://github.com/TeamNewserial/.github/assets/71147610/845bb680-a023-416d-b376-1ab0278d81b4" width=160> 
<img src="https://github.com/TeamNewserial/.github/assets/71147610/40f4ce7e-816a-43a5-888d-b742701e60a1" width=160> 

### 주요 기능 + 상세 기능
---
- 로그인/회원가입/임시 비밀번호 발급
    - 소셜로그인(네이버)
    - accessToken은 **redux store**에 저장, refresh Token은 **쿠키**에 저장
    - **privateRoute**, **publiceRoute**, **HomeRoute**로 페이지 접근 관리
    - 이메일 인증
- 메인페이지
    - 한입 퀴즈 : **Open AI**를 이용하여 경제 용어에 대한 O,X 퀴즈 풀기
    - 맞춤 기사 : 한입 퀴즈 기록에서 단어를 추출해  관련 기사 한 개를 보여줌
    - 뉴시리얼 : **네이버 뉴스를 크롤링**하여 전체 그리고 카테고리 별로 보여줌
- 뉴스 상세
    - 내용 : **클로바 API**로 요약한 내용을 보여줌
    - TTS : **Web Speech API**를 사용하여 기사 내용을 읽어주는 기능
    - 북마크
    - 퀴즈 : **OpenAI를** 이용하여 뉴스기사에 대한 O,X 퀴즈 풀기
    - 쉬운 설명 : **Open AI**를 이용하여 선택한 문장을 쉽게 **paraphrasing**해서 보여줌
- 뉴스 검색
    - 뉴스 제목 검색
- 마이페이지
    - 우유 돌보기 : 우유의 상태 확인. **우유는 뉴시리얼의 마스코트**로 퀴즈의 정답을 맞히면 성장 (노숙견→흥부견→평민견→양반견→임금견)
    - 퀴즈 기록
    - 북마크 기사 목록
    - 비밀번호 재설정 / 로그아웃
    - 
### 프로젝트 아키텍쳐
---
![아키텍쳐](https://github.com/TeamNewserial/.github/assets/71147610/b93bb3d6-5ce3-4c71-bac8-e2b92a2d41f6)

### 개발자
---
 |<img src="https://github.com/VanesaK.png" width="200">|<img src="https://github.com/JEONGEUN0204.png" width="200">|<img src="https://github.com/aaa67.png" width="200">|<img src="https://github.com/Elenaljh.png" width="200">|
 |:-:|:-:|:-:|:-:|
 |[김민지](https://github.com/VanesaK)|[신정은](https://github.com/JEONGEUN0204)|[신정인](https://github.com/aaa67)|[이지혜](https://github.com/Elenaljh)|
 |Frontend Developer|Frontend Developer|Backend Developer|Backend Developer|
  
