# AI 提示詞優化器

Firebase Hosting 靜態網站，協助使用者把初稿提示詞改寫成更清楚、可執行、適合 ChatGPT、DeepSeek、Gemini 等語言模型理解的版本。

## 功能

- 支援不同 AI 模型取向：ChatGPT、DeepSeek、Gemini、Claude、通用模式
- 可選任務類型、輸出語言、語氣與詳細程度
- 自動產生結構化優化提示詞
- 提供問題診斷、缺失提醒與一鍵複製
- 完全前端執行，不需要後端或 API 金鑰

## 本機預覽

直接開啟 `public/index.html`，或使用任意靜態伺服器預覽。

## Firebase 佈署

```powershell
npx firebase-tools deploy --only hosting
```
