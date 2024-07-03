# MAKABOOM
Makaboom hybrid app
Apps Managing Projects
https://github.com/shdurud96/MAKABOOM
App Developer : Yeogyeong Noh 
Development Period : 2019.01.14-2019.02.22 
Description
개발 환경으로는 Ionic과 Firebase를 사용하여 프론트엔드는 Single Code base로 안드로이드, iOS, 웹으로 배포 가능하도록 하였고, 백엔드는 Firebase를 사용하여 Auth와 DB를 구성하였음
Cordova Camera로 Native 기능을 사용함.
lazy loading 방식을 적용하여 페이지 별로 관리함. 

Firebase 계정
firebase.console에서 관리

Test Account 
-yeogyeong@makaboom.com	password : maka0210
-developer@makaboom.com 	password : maka1234

Database 구성 
(Firebase NoSQL firestore collection-document형식 / firebase console에서 확인 가능)
Notice – document filed에 바로 정보추가
Share – document 이름을 project name으로 설정하고 field에 정보 추가
User – document를 uid로 설정하고 바로 밑 filed에 사용자 정보 추가 
		-DoneProject Collection 밑 -document이름 project name으로 설정
		-On_project Collection 밑 – document 이름 project name으로 설정
Storage
바탕의 사진은 앱 css에 사용된 파일들
폴더 repair-item/은 project 메인 사진들
폴더 repair_log/는 timeline에 추가한 사진들

Page Location
Main Page src/pages/main
Login Page src/pages/auth/login
Home Page src/pages/home
	-Project OnGoing src/pages/repair/maintenance-log
		-Add Project src/pages/repair/addrepair
	-Project Completed src/pages/repair/on-maintenance
	-Show and Tell src/pages/repair/all
		-Detail Information src/pages/repair/repairitemdetail
			-Add timeline src/pages/repair/addlog
My Profile src/pages/profile



