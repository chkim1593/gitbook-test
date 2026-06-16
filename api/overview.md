# API 개요

REST API는 JSON 기반 요청/응답을 사용합니다.

## 기본 URL

```
https://api.example.com/v1
```

## 공통 응답 형식

```json
{
  "data": {},
  "error": null,
  "meta": { "requestId": "abc-123" }
}
```

| 상태 코드 | 의미 |
| ----- | --------- |
| 200   | 성공     |
| 401   | 인증 실패  |
| 404   | 리소스 없음 |
| 500   | 서버 오류  |
