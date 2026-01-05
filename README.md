# AI 股票分析師 V33.0

一個使用 Streamlit 和 Google Gemini AI 打造的智能股票分析 Web App。

## 功能特色

- 🤖 整合 Google Gemini 1.5 Pro 模型
- 🔍 自動透過 Google Search 獲取最新股價資訊
- 📊 多維度股票分析（基本面、技術面、籌碼面）
- 🎯 個人化投資建議（依據操作週期、投資風格）
- 📈 估值模型與劇本推演

## 安裝步驟

1. 安裝所需套件：
```bash
pip install -r requirements.txt
```

2. 執行應用程式：
```bash
streamlit run app.py
```

3. 在瀏覽器中開啟顯示的網址（通常是 http://localhost:8501）

## 使用方式

1. 在左側欄位輸入股票資訊：
   - 股票代號（必填）
   - 持有成本
   - 持有股數
   - 操作週期
   - 分析目的
   - 投資風格

2. 點擊「開始分析」按鈕

3. 等待 AI 分析完成（會自動搜尋最新資料）

4. 查看完整的分析報告

## 技術架構

- **前端框架**：Streamlit
- **AI 模型**：Google Gemini 1.5 Pro
- **資料來源**：Google Search Retrieval (Grounding)

