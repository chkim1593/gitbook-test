# 인증

API 키를 `Authorization` 헤더에 담아 전송합니다.

```bash
curl https://api.example.com/v1/users \
  -H "Authorization: Bearer YOUR_API_KEY"
```

{% hint style="danger" %}
API 키는 절대 클라이언트 코드나 공개 저장소에 노출하지 마세요.
{% endhint %}

## 토큰 수명

* 액세스 토큰: 1시간
* 리프레시 토큰: 30일
