# 문제 해결

## 자주 발생하는 오류

### 연결 시간 초과

```
Error: ETIMEDOUT
```

방화벽 규칙과 포트 개방 여부를 확인하세요.

### 인증 실패 (401)

* API 키 유효성 확인
* 토큰 만료 여부 확인
* 헤더 형식(`Bearer`) 확인

<details>

<summary>디버그 로그 활성화 방법</summary>

환경 변수를 설정하면 상세 로그가 출력됩니다.

```bash
DEBUG=app:* npm start
```

</details>
