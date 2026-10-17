# Awaken AI

Windows 個人 AI 助理。自行替助理取名字、輸入自己的 OpenRouter API Key，使用語音對話、搜尋、提醒與選用 YouTube Music 播放。

**公開測試版 0.3.2／C145** · Windows 10／11 x64

[下載安裝包](https://github.com/littleblackmann/awaken-ai-releases/releases/latest) · [線上更新測試](UPDATE.md)

安裝包隨附 Python 與 CPU 語音套件，可選位置、閱讀資料使用說明、選捷徑；首次本機喚醒模型及選用播放器需另下載。雲端功能使用自己帳號的額度，電腦與助理開啟時才會運作。

已安裝 C142：先從系統匣結束助理，開啟 Release 內的 `AwakenAI-Update-Bridge.exe`，檢查並下載更新，再自行啟動原本捷徑。此後從設定 → 系統與重設更新，不需要 GitHub 帳號。C144 起可勾選下載完成後自動更新並重啟；舊版第一次載入新啟動器仍需自行重開。

C145 完整安裝包使用 `app` 資料夾；舊安裝請先結束助理與 Pear，再選原位置覆蓋安裝，Key、記憶與音樂登入會一起保留。一般線上更新可升至 C145 並沿用原資料夾；需要改名時執行完整安裝包。

此庫只存放乾淨的發行資產與使用說明，不匯入舊私人程式庫的 Git 歷史。source ZIP 是程式快照；未宣告開源授權。第三方元件依安裝包內授權使用。

程式更新以 Ed25519 及 SHA256 驗證；Windows EXE 尚未申請發行者簽章，可能顯示未知發行者。完整實機驗收持續進行，請勿作為緊急通知服務。
