# 251111_FHIR-Questionnaire-SkipLogic-Demo
運動問卷｜FHIR 跳題邏輯 

---

## 🌐 Demo 網址
👉 [開啟網站](https://kueikui.github.io/251111_FHIR-Questionnaire-SkipLogic-Demo/)

---

## 📖 專案簡介
這是一個基於 **FHIR Questionnaire / QuestionnaireResponse** 的前端網頁示範，  
用於展示「**跳題邏輯（Skip Logic）**」在問卷填答中的實作方式。  

---

## ⚙️ 專案結構
├── index.html # 首頁（導覽頁）
├── 跳題問卷/
│ ├── Questionnaire.html # 上傳問卷CSV檔
│ ├── QuestionnaireResponse.html # 填寫問卷
│ ├── postPatinet.html # 建立patient資訊
│ ├── getBundle2.html # 查詢特定病患的問卷回應
│ ├── HTTP2024.js # 通訊與 FHIR API 讀取函式
│ ├── setting.js # 伺服器設定
│ ├── dateTime.js / Cookie.js # 其他工具模組
│ └── 運動問卷轉換_UTF8new3.csv # 問卷內容資料
└── README.md # 專案說明文件

---

## 主要功能
- 上傳問卷CSV檔
- 建立patient資訊  
- 顯示問卷題目進行填答
- 查詢特定病患的問卷回應 
- 依據使用者回答動態顯示下一題（跳題邏輯）  
- 支援 FHIR Questionnaire / QuestionnaireResponse 結構  

---

## 使用方式
1. 開啟首頁  
 [https://kueikui.github.io/251111_FHIR-Questionnaire-SkipLogic-Demo/](https://kueikui.github.io/251111_FHIR-Questionnaire-SkipLogic-Demo/)
2. 選擇想要查看的頁面：
   - 下載csv範例檔
   - 上傳問卷CSV檔（Questionnaire.html）
   - 建立patient資訊(Patient.html)
   - 填寫問卷（QuestionnaireResponse.html）  
   - 查詢特定病患的問卷回應 （getBundle2.html）
