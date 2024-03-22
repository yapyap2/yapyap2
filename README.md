![header](https://capsule-render.vercel.app/api?type=waving&text=hello_world!)
# 안녕하세요! 개발자 정원우입니다.


<div align=center><h1>📚 STACKS</h1></div>

<div align=center> 
  <img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white"> 
  <img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white"> 
  <br>
  
  <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white"> 
  <img src="https://img.shields.io/badge/mariaDB-003545?style=for-the-badge&logo=mariaDB&logoColor=white"> 
  <br>
  
  <img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white"> 
  
  <img src="https://img.shields.io/badge/amazonaws-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"> 
  <br>
</div>


# 🏗️Project

## [Milestone](https://milestone-1.firebaseapp.com/)  (2022.07 ~ 2023.07)

[https://milestone-1.firebaseapp.com/](https://milestone-1.firebaseapp.com/)     https://github.com/yapyap2/StravaRefactoring
운동 SNS ‘Strava’의 API를 활용한 스포츠 데이터 시각화 서비스입니다.

- 외부 API(Strava, Kako Local) 호출
- 사용자의 GPS 경로 데이터를 위도, 경도 좌표로 디코딩
- 좌표에 대한 주소 검색시 ExecutorService를 사용한 멀티 스레드 병렬처리를 도입하여 싱글 스레드 대비 처리속도 1/3 수준으로 경감
- Bulk insert 구현을 통해 데이터베이스 통신 횟수 절약
- 프론트 엔드 개발자 1명과의 협업 프로젝트입니다.

## The grid   (2023.07~진행중)

https://github.com/yapyap2/TheGrid

위치 정보 기반 실시간 텍스트 SNS 서비스입니다.

- Redis를 이용한 Pub-Sub 구조 메세지 전달 구현
- 프론트엔드 React 서버와의 소켓 통신
