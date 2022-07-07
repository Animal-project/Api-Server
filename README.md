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

## 프로젝트 설치
