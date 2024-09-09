# MySQL 이미지 사용
FROM mysql:latest

# 환경 변수 설정
ENV MYSQL_ROOT_PASSWORD=1234
ENV MYSQL_DATABASE=test
ENV MYSQL_USER=test_user
ENV MYSQL_PASSWORD=1234

# 초기 SQL 스크립트 복사
COPY ./init.sql /docker-entrypoint-initdb.d/

# 포트 공개
EXPOSE 3306