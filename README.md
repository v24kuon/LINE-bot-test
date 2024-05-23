#Cloudflare Worker + D1 + Hono + OpenAIでLINE Bot
LINE botを作成しました使用するには
* 以下の2つが必要です
    * Messaging APIのチャネルアクセストークン
    * OpenAIのAPI Key
それぞれを

```
wrangler secret put CHANNEL_ACCESS_TOKEN
```
```
wrangler secret put OPENAI_API_KEY
```

してください
