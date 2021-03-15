<h1 align="center"> LoveLine <img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="48px"></h1>
<p>
</p>




<center>
    <img src="./logo_row.png" alt="MODU" style="zoom:76%;" align="center"/>
</center>




> MODU's Health / 모두의 헬스 (SSAFY 3rd 자율프로젝트)

### 🏠 [Github](https://github.com/jesuisjavert/MODU) :clapper:[Demo 시연영상](https://www.youtube.com/watch?v=JnYyQUX-lPw&feature=youtu.be) :page_with_curl:[프로젝트 명세서](https://drive.google.com/file/d/1fWqLAJYHXRDeOOPT6kzg8ESiNVkAZr1h/view?usp=sharing) :microphone:[Presentation](https://drive.google.com/file/d/1LEiyBAhnahO3JV_hn3iLqF7BJafw2TFf/view?usp=sharing)

<br>

## ✨ Description

```sh
모두의 헬스는 Health Trainer 와 Client 간의 온-오프라인 Personal Training 상품을
판매하고, 이용할 수 있게 도와주는 O2O 플랫폼 서비스 입니다.
```



## :pushpin: Project Goal

```sh
 코로나 사태 이후, 우리의 삶은 ‘뉴 노말(New normal)’시대로의 전환을 맞이했습니다.
전염병의 확산을 막기 위한 ‘비대면/언택트(Untact)’의 시대에, 오프라인 대면 만남을 최소한으로 줄이려는 노력과,
그만큼 줄어든 활동량에 따라, 개인의 건강과 운동을 집에서 해결할 수 있는 ‘홈트레이닝’에 대한 수요가 급격하게
늘어나게 되었습니다. 
 그 결과, 2020년 업종별 폐업률 1위가 오프라인 피트니스 시장이 될 정도로, 피트니스 시장의 많은 자영업자들이
심각한 경제적 타격을 입은 것으로 보입니다. 이를 해결하기 위해, 온라인 홈트레이닝족과 오프라인 헬스트레이너를
연결하는 플랫폼 서비스를 만들어 국민건강증진과 트레이너 자영업자들의 경영난을 해소하기 위해 이 프로젝트를 기획했습니다.
 기존의 오프라인 피트니스 시장을 온라인 플랫폼에 안착시키고, 기존의 전문 기술력을 가진 헬스 트레이너들을
온라인 홈트레이닝 시장과 연결시켜 새로운 가치를 창출해내는 것은 유의미한 시도가 될 것입니다.
```



## :mag: 서비스 기능

<center>
    <img src="./README.assets/requirements.png" alt="MODU"  align="center"/>
</center>


## :mag: Overview

### 1. 유저 로그인 페이지 (User Login Page) (소셜로그인)

<center>
    <img src="./README.assets/1.png" alt="MODU"/>
</center>


<br>

### 2. 트레이너-고객 실시간채팅 Trainer - Client Chatting 

<center>
    <img src="./README.assets/2.png" alt="MODU"/>
</center>


<br>

### 3. 트레이너-프로그램 추천 시스템 (Best Trainer/Program Carousel)

<center>
    <img src="./README.assets/3.png" alt="MODU"/>
</center>

<br>

### 4. 다중 화상통화 기능활용 온라인 홈트레이닝 세션 (Multiple User WebRTC(Realtime Camera) Online Personal Training)

<center>
    <img src="./README.assets/4.png" alt="MODU"/>
</center>

<br>

### 5. 달력 기능과 연동한 스케쥴 관리(Schedule managment)

<center>
    <img src="./README.assets/5.png" alt="MODU"/>
</center>


<br>

### 6. 트레이너의 PT관리 CRUD(PT Program & Client management)

<center>
    <img src="./README.assets/6.png" alt="MODU"/>
</center>


<br>

### 7. PT프로그램 디테일 CRUD(PT Program CRUD)

<center>
    <img src="./README.assets/7.png" alt="MODU"/>
</center>


<br>

### 8. 결제시스템 (카카오 페이 결제) Client Payment System

<center>
    <img src="./README.assets/8.png" alt="MODU"/>
</center>


<br>

### 9. 실시간 알림 & 프로그램 리뷰 & 예약 시스템

### Realtime Notification & Review & Reservation System

<center>
    <img src="./README.assets/9.png" alt="MODU"/>
</center>


<br>



## :wrench: Tech Stack

### Tech Stack

<center>
    <img src="./README.assets/stack.png" alt="MODU"/>
</center>




### System Architecture

<center>
    <img src="./README.assets/arch.png" alt="MODU"/>
</center>


<br>

## :pencil2: ERD

<center>
    <img src="./README.assets/erd.png" alt="MODU"/>
</center>

<br>

## :runner: Steps to run

### Backend

```bash
$ cd modeling
$ python -m venv venv
$ source venv/Scripts/activate
$ python install -r requirements.txt
$ python manage.py runserver
```

### Frontend

```bash
$ cd frontend
$ npm install
$ npm run serve
```

<br>

## 🤼‍♂️Author

Team Leader : 🐯**Kang Donghoon**

Backend : 🐶 **Lee Changwan**

Backend: 🐺 **Bae Yongkyun**

Frontend : 🐱 **Kang Byungkook**

Frontend : 🦁 **Roh Hyunsuk**

<hr>


## :trophy: Awards

- SSAFY 자율 프로젝트 우수팀 선정 및 부상 100만원 수상

![Award](C:\Users\DonghoonKang\Desktop\modu\MODU\README.assets\MODU.jpg)

- SSAFY  Best Member 선정 & 50000 마일리지 수여

  ![bestmember](C:\Users\DonghoonKang\Desktop\modu\MODU\README.assets\bestmember.png)




## 📝 License

Copyright © 2020  MODU's Health  <br>

























**Backend**

```sh
cd sub2/backend
pip install -r requirements.txt
# requirements.txt가 안되는 경우엔 개별적으로 설치를 해줘야한다 보통 pandas,scipy,scikit-learn 패키지가 문제를 일으키는경우가 많다.
# 패키지 설치시 동반설치되는 패키지가 지원되지않는 확장자를 가져오는경우가 있어서 그럴때에는 개별설치를 추천한다.
python manage.py makemigrations
python manage.py migrate
python manage.py initialize
python manage.py runserver
```

**Frontend**

```sh
cd sub2/frontend
npm install
npm run serve

```
