# AI 提示詞三版優化器

Firebase Hosting 靜態網站。使用者輸入一句原始提示詞後，網站會立即產生三個不同風格、可直接複製使用的優化版本，適合 ChatGPT、DeepSeek、Gemini 等語言模型。

## 功能

- 一句提示詞生成三個版本：專業精準版、創意發散版、結構化執行版
- 支援 ChatGPT、DeepSeek、Gemini、Claude、通用 AI 模型
- 可選用途、輸出語言與必須包含的內容
- 每個版本都有獨立複製按鈕
- 完全前端執行，不需要後端或 API 金鑰

## 本機預覽

直接開啟 `public/index.html`，或使用任意靜態伺服器預覽。

## Firebase 佈署

```powershell
npx firebase-tools deploy --only hosting
```
