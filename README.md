## 데이터 베이스 설치
1. Sql 검색
   1. `docker search mssql`
   2. `docker pull liaisonintl/mssql-server-linux`
2. docker images 설치 확인 
   1. `docker images`
3. 이미지 실행
   1. `docker run -e 'ACCEPT_EULA=Y' -e 'SA_PASSWORD=test1234!' -p 1433:1433 --name testMsSql -d liaisonintl/mssql-server-linux`
4. 이미지 실행 확인
   1. `docker ps`
5. db커넥트 테스트
   1. `데이터 그립으로 테스트`
6. 간의 테이블 제작
   1. 팻샵
      1. https://www.edrawsoft.com/template-pet-store-erdiagram.html
   2. 이커머스
      1. https://www.google.com/search?q=ecomus+erd&tbm=isch&ved=2ahUKEwjIgMu0-uX4AhVORvUHHdB[…]img&ei=KWPGYojICc6M1e8P0JGBmA4&bih=860&biw=1324&client=safari
   3. sqlDocs 폴더안에 쿼리문 삽입 + 더미데이터 쿼리삽입

## 프로젝트 설치

## 코드 컨벤션

## docker build
1. 도커 프로잭트 빌드
   1. 도커 파일 생성 Dockerfile
      1. 도커 파일 빌드
         1. docker build -t docker-java-project :0.0.1 .
   2. 환경 테스팅