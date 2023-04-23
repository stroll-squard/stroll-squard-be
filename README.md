# 산책 특공대

---

## ♻️ 애플리케이션 실행 방법

---

다음과 같이 환경 변수 처리되어 있는 부분을 `.env`을 만들어 설정해줍니다.
```dotenv
# 예시 (.env)
DB_DRIVER=org.postgresql.Driver
DB_URL=jdbc:postgresql://localhost:55000/stroll_squard
DB_USER=postgres
DB_PASSWORD=postgrespw
```

테스트 용도로 사용할 설정 파일은 test.env로 파일로 만들어 위와 같은 형식으로 작성합니다.