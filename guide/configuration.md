# 설정

`config.yaml` 파일로 동작을 제어합니다.

```yaml
server:
  host: 0.0.0.0
  port: 3000
logging:
  level: info
  format: json
```

## 주요 옵션

* **host** - 바인딩할 호스트 주소
* **port** - 수신 포트 번호
* **logging.level** - `debug`, `info`, `warn`, `error`

{% hint style="warning" %}
프로덕션 환경에서는 `logging.level`을 `debug`로 두지 마세요.
{% endhint %}
