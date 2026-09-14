# 🔐 帳密 Quick QR Code 生成器 (Account & Password QR Generator)

一個專為條碼掃描槍 / Barcode Scanner 設計的純前端 QR Code 工具。輸入帳號與密碼後，會自動生成帶有 `[ID][TAB][Password][ENTER]` 控制碼的 QR Code，方便透過掃描器快速自動帶入與登入系統。

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Pure Frontend](https://img.shields.io/badge/backend-None%20(Pure%20JS)-brightgreen)

## ✨ 特點說明

- ⚡ **即時生成**：輸入字元立即自動更新 QR Code，無需手動點擊生成。
- ⌨️ **控制鍵支援**：自動插入 `\t` (Tab) 與 `\n` (Enter)，條碼槍掃描後可自動跳格與送出。
- 👁️ **密碼隱私保護**：密碼欄位預設隱藏，提供一鍵切換顯示/隱藏功能，防止旁邊的人側目。
- 🔒 **100% 安全隱私**：**純前端運算**，所有輸入的帳號密碼完全在瀏覽器本地處理，**絕不上傳任何伺服器或紀錄**。
- 📥 **一鍵功能**：支援複製原始轉義字串與高畫質下載 PNG 圖片。

## 🚀 快速使用

1. 開啟 [線上工具頁面](https://swjw15.github.io/Auto-login-QR-code-generator/)
2. 在欄位中輸入你的 **帳號/ID** 與 **密碼**。
3. 畫面將自動產生對應的 QR Code。
4. 使用條碼掃描器（已開啟鍵盤模擬模式）掃描 QR Code，即可自動填入並按下 Enter！

## 🛠️ 技術棧

- **HTML5 & Pure JavaScript**
- **Tailwind CSS** (透過 CDN 引入現代化 UI 樣式)
- **QRCode.js** (前端即時 QR Code 渲染)
- **Lucide Icons** (極簡風格圖示)

## 🛡️ 資安與隱私聲明 (Privacy & Security)

本工具為 **100% 無後端 (Serverless / Static)** 的開源網頁應用。
- 沒有任何 Analytics 追蹤碼。
- 沒有任何 API 請求會發送到第三方伺服器。
- 歡迎直接檢視原始碼 (`index.html`) 進行安全性審核。

## 📄 授權條款

MIT License. 歡迎自由修改、散佈與使用。
