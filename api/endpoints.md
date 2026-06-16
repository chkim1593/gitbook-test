# 엔드포인트

## 사용자 조회

{% code title="요청" %}
```http
GET /v1/users/{id}
```
{% endcode %}

{% code title="응답" %}
```json
{
  "data": {
    "id": "1",
    "name": "홍길동",
    "email": "hong@example.com"
  }
}
```
{% endcode %}

## 사용자 생성

```http
POST /v1/users
Content-Type: application/json

{
  "name": "홍길동",
  "email": "hong@example.com"
}
```
