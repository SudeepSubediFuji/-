# API仕様書

## 基本情報
- **API名**: [API名]
- **バージョン**: 1.0
- **ベースURL**: https://api.example.com/v1

---

## API一覧

| API ID | API名 | メソッド | エンドポイント | 概要 | 認証 |
|--------|-------|----------|----------------|------|------|
| A001 | [API名1] | GET | /[endpoint] | [概要] | [要/不要] |
| A002 | [API名2] | POST | /[endpoint] | [概要] | [要/不要] |
| A003 | [API名3] | PUT | /[endpoint] | [概要] | [要/不要] |
| A004 | [API名4] | DELETE | /[endpoint] | [概要] | [要/不要] |

---

## API詳細仕様

### A001: [API名]

#### 概要
[APIの概要・目的]

#### リクエスト
```http
GET /[endpoint]?param1=value1&param2=value2
Host: api.example.com
Authorization: Bearer [token]
Content-Type: application/json
