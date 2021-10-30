<div align=center>

![GitHub last commit](https://img.shields.io/github/last-commit/nulLeeKH/RESUME.svg)

# nulLeeKH
I believe in the value of failure, constantly challenging and learning anytime, anywhere. 

</div>

## 소개

- 이름 : **이경하**

다양한 분야에 대한 **폭넓은 경험**을 바탕으로 **세상에 없던 것들**을 만들어내는 개발자, 이경하입니다.

```python
#!/usr/bin/env lkh

from nulLeeKH import about_me, get_goal, achieve_goal, check_result

if __name__ == '__main__':
	result = 'I can do anything!'

	while True:
		goal = get_goal(about_me('Kyung-ha Lee'))
		hint = []

		while not check_result(goal, result) :
		    hint.append(result)	

		    try:
		        result = achieve_goal(goal, hint)
		    except Exception as ex:
		        result = ex
```

```
실패의 가치를 믿고,
언제 어디서나 끊임없이 도전하며 배우고 있습니다.
```

- Hobby : 🏹, 📚
- Email : i_am@nulleekh.com
- Github : https://github.com/nulLeeKH

## 경력

### [edutosel.co.ltd.](http://www.tosel.org/) 개발팀 업무 총괄 담당 (2021.05 ~ 2021.10)

### [bettercode Co., Ltd.](https://www.bettercode.kr/) QR 및 개발자 (2021.04 ~ 2021.08)

### [Team Crescendo](https://team-crescendo.me/) Xsi 챗봇 개발자 (2020.10 ~ 2021.10)

### <img src="http://korea.ac.kr/mbshome/mbs/university/images/img/img_1_5_1_1_1.jpg" width="50" height="50"/>[Korea Univ.](https://korea.ac.kr) 정보대학 컴퓨터학과 학부생 (2021 ~ )

### <img src="https://scontent-gmp1-1.xx.fbcdn.net/v/t31.18172-8/11537624_131761307155762_3925225302984064110_o.png?_nc_cat=103&ccb=1-5&_nc_sid=09cbfe&_nc_ohc=Gv1e93HtRYUAX-lbm5l&_nc_ht=scontent-gmp1-1.xx&oh=717ef6e7fd72df35b348b465d2169ba3&oe=61A30D90" width="50" height="50"/>[KITRI BoB7대 총동문회](https://www.facebook.com/bobalumni/) 부회장 (2021.05 ~ )

### <img src="https://www.kitribob.kr/static/front/images/about/bob-logo.png" width="50" height="50"/>[KITRI BoB](https://www.kitribob.kr) 9기 보안제품개발트랙 교육생 (2020.07 ~ 2021.05)

## 사용 기술

### Data

**이미지, 문자열 등 다양한 데이터**를 처리할 수 있는 스킬을 가지고 있습니다.

- Python
	- NumPy
	- SciPy
	- Pandas
	- Matplotlib
	- Scikit-Learn
	- TensorFlow
	- Keras
	- PyTorch
- C++
	- Caffe

### Server

**서버를 전반적으로 구축하고 관리**할 수 있는 스킬을 가지고 있습니다.

- Javascript
	- Node.js
	- Socket.io
- Python
	- Django
	- Flask
	- Celery
- C++
	- TCP/UDP Socket
	- CGSF
- Jenkins
- Docker

### Web

**정적 웹 페이지를 퍼블리싱**할 수 있는 스킬을 가지고 있습니다.

- HTML/CSS/JS
	- Bootstrap
	- React.js
	- Vue.js
	- Svelte

### Process

- Monitoring - Google Analytics
- Communication - Slack, TeamCity, Dooray, JANDI
- Issue - Github, YouTrack, Jira, Trello, Notion
- Version - Git

### TODO

**더 나은 사람**이 되기 위해 지금 아래의 것들에 도전하여 실패를 통해 배우고 있습니다.

- Web
	- D3.js
- Android/IOS
	- React Native
	- Kotlin
	- Swift
- Clean Architecture
- Development methodology
	- Agile
	- DevOps
- Development Approach
	- DDD
- IEEE
	- 802.11

## 오픈소스 기여 및 프로젝트 이력

<img src="https://avatars3.githubusercontent.com/u/12589084?s=200&v=4" width="150" height="150"/>

### Notepad++
- 소개 : 오픈소스로 개발된 무료 소스코드 에디터
- 기간 : 2019.02
- 역할 : 소프트웨어의 한글 번역 개선 프로젝트 진행
- 관련 기술 : Korean, English, Communication

<img src="https://avatars0.githubusercontent.com/u/59673308?s=200&v=4" width="150" height="150"/>

### ABCD (Acid Base Calculation Wizard)
- 소개 : 산/염기 중화적정반응의 결과를 계산하는 소프트웨어
- 기간 : 2019.06 ~
- 역할 : 수식 연산 알고리즘 고안 및 구현, GUI 구성 등 개발 전반
- 관련 기술 : C, Python, NumPy, PyQt

<img src="https://avatars2.githubusercontent.com/u/62950482?s=200&v=4" width="150" height="150"/>

### 66-day
- 소개 : macOS용 66일 습관 달력 앱
- 기간 : 2020.03 ~
- 역할 : 기획 및 개발 등 전 과정
- 관련 기술 : Swift, macOS

### KVE-2018-2449
- 소개 : SKT/CGV 0teen 기기 강제종료 취약점
- 기간 : 2018.12
- 역할 : 로직 버그 발견 및 취약점 확인
- 관련 기술 : Windows IoT

<img src="https://avatars0.githubusercontent.com/u/58934908?s=200&v=4" width="150" height="150"/>

### Dropper API
- 소개 : 다양한 데이터를 제공하는 API 서비스
- 기간 : 2020.02 ~
- 역할 : 데이터 크롤러 및 서버 관리 유틸리티 개발
- 관련 기술 : Python

### 기타 개인 프로젝트

- 교보문고 r-XSS 취약점 제보
	- 소개 : 교보문고 검색 폼 내부에 존재하였던 r-XSS 취약점
- [korean-national-id-checksum-calculator-library](https://github.com/nulLeeKH/korean-national-id-checksum-calculator-library)(2019)
	- 소개 : 대한민국 주민등록번호 체크섬 계산 라이브러리
- [arduino-optical-dust-sensor-library](https://github.com/nulLeeKH/arduino-optical-dust-sensor-library)(2019)
	- 소개 : 아두이노를 이용해 광학식 먼지 농도 센서를 작동시키기 위한 라이브러리
- [arduino-pid-control-library](https://github.com/nulLeeKH/arduino-pid-control-library)(2019)
	- 소개 : 아두이노를 이용해 PID 제어를 구현하기 위한 라이브러리

## 수상 경력

#### 과학전람회 (2019)

- 제22회 울산 과학 전람회 - 특상(1위)
	- 소개 : 울산광역시 교육청 울산과학관이 개최한 초/중/고 학생의 과학 탐구와 연구 활동을 장려하기 위하 전람회
	- 수상 기관 : 울산광역시 교육감 노옥희
	- 관련 저장소 : [ph-calculator](https://github.com/acid-base-calculation-wizard/ph-calculator)
- 제65회 전국과학전람회 - 대통령상(1위)
	- 소개 : 과학기술정보통신부 국립중앙과학관이 개최한 전국 17개 시/도 초/중/고 학생과 교원/일반인들의 과학 탐구와 연구 활동을 장려하기 위한 전람회
	- 수상 기관 : 대한민국 대통령 문재인
	- 관련 저장소 : [ph-calculator](https://github.com/acid-base-calculation-wizard/ph-calculator)

#### 자율주행자동차 경진대회 (2019)

- 2019 울산과학기술제전 자율주행자동차 경진대회 - 금상(1위)
	- 소개 : 울산과학기술제전의 부대행사로 열린 자작 자율주행자동차 경진대회
	- 수상 기관 : 울산광역시 교육감 노옥희
	- 관련 저장소 : [arduino-autonomous-car](https://github.com/nulLeeKH/arduino-autonomous-car)
- 제3회 판교 자율주행모터쇼 고등학생 자작자율주행자동차 경진대회 - 준우숭(2위)/The Fastest Car Award(1위)
	- 소개 : 제3회 판교 자율주행모터쇼의 부대행사로 열린 자작 자율주행자동차 경진대회
	- 수상 기관 (준우승) : 성균관대학교 공과대학 학장 이준영
	- 수상 기관 (The Fastest Car Award) : 성균관대학교 공과교육혁신센터장 이준영
	- 관련 저장소 : [arduino-autonomous-car](https://github.com/nulLeeKH/arduino-autonomous-car)

#### 제19회 앱잼 (2019)

- 생활정보부문 - 최우수상(1위)
	- 소개 : APPJAM이란 중소벤처기업부, SK텔레콤, SK플래닛이 공동으로 주최하는 고등학생 앱 및 융합 서비스 개발 경진대회.
	- 수상 기관 : SK플래닛(주) 대표이사 이한상
	- 관련 저장소 : [danim](https://github.com/easy-prize/danim)

##### 본 문서에는 분량 관계로 우수 수상 경력만 작성되었으며, 기타 수상 경력은 [이 문서](https://github.com/nulLeeKH/RESUME/blob/master/AWARD.md)에서 확인 가능합니다.

## 기타 경력

### 강연 활동

#### 2019년 5월, 소프트웨어에 물들다 강연

- 울산 남목작은도서관
	- 제목 : 인공신경망과 소프트웨어
	
### 봉사 활동

#### 울산환경운동협회 구 웹사이트 데이터 백업 기술지원

---

여기까지 읽어 주셔서 굉장히 감사합니다.

궁금하신 점은 이 Repository에 [Issue](https://github.com/nulLeeKH/RESUME/issues)를 올려주시거나 [i_am@nulleekh.com](i_am@nulleekh.com)으로 메일 남겨주시기 바랍니다.

다시한번 감사드립니다.
