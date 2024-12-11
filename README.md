# 享。閱讀

## 專案簡介
「享。閱讀」是一個結合書籍推薦心得分享與互動留言的綜合平台，涵蓋了 Web 與行動應用 (APP) 兩個版本。使用者可以自由撰寫心得、上傳圖片、設定書籍封面，並在每篇推薦心得中與其他使用者互動留言。此外，APP 還提供即時通知功能，讓使用者不錯過任何互動。

## 功能特色
- **心得分享**：使用者可發表書籍推薦心得，並上傳圖片設定書籍封面。
- **互動留言**：支援每篇心得的使用者互動留言功能。
- **APP 即時通知**：當心得被回覆時，通過 Firebase Cloud Messaging (FCM) 向曾經登入的手機裝置發送通知。

## 技術背景與架設環境
### 享。閱讀 Web
- **後端框架**：Django (Python)
- **前端技術**：jQuery
- **伺服器環境**：Apache 部署於 Hostinger VPS
- **資料庫**：MySQL

### 享。閱讀 APP
- **APP 開發**：Android Studio (Java)
- **後端框架**：Django REST API
- **伺服器環境**：Apache 部署於 AWS EC2
- **資料庫**：MySQL

## 部署架構
1. **Web 平台**：提供穩定的書籍心得發表與留言互動功能，適合桌面與行動端瀏覽。
2. **APP 平台**：以行動裝置為主，支援即時通知與跨設備互動。


## 系統截圖 (APP)
| ![image (20)](https://github.com/user-attachments/assets/99847631-52f0-40d8-a7ca-cd42e1268cdd) | ![image (15)](https://github.com/user-attachments/assets/a7227af3-23f3-4584-a02f-4574f6d25701) |
|-------------------------|------------------------|
| ![image (16)](https://github.com/user-attachments/assets/526d12ed-d904-4ec6-a13a-b288abf491cc) | ![image (21)](https://github.com/user-attachments/assets/b87e223c-62b4-49b0-8aae-d09ce35d71ce) |
| ![image (18)](https://github.com/user-attachments/assets/38883c44-9396-47f1-8027-d449ea5aa19a) | ![image (19)](https://github.com/user-attachments/assets/d9fccd80-2007-4941-9672-5492d1f0e2e8) |


## 系統截圖 (WEB)
![screencapture-nkustbooksharing-online-2024-12-11-08_34_05](https://github.com/user-attachments/assets/9fbeb595-503e-44df-8870-eefa34ab3311)
