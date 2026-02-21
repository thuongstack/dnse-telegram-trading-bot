# 📌 DNSE Telegram Trading Bot

Telegram bot tích hợp DNSE API để:

Xem danh mục

Đặt lệnh mua/bán

Thông báo lãi/lỗ

Cảnh báo theo giờ giao dịch VN (09:00–15:00)

Restart bot từ xa

Giải mã API bằng OpenSSL

## 🔐 Bảo mật

Không lưu API key plaintext trên GitHub

Dùng file .env

Có controller riêng để restart

Giới hạn AUTHORIZED_CHAT_ID

Hỗ trợ giải mã bằng OpenSSL

## 🚀 Cài đặt

### 1. Clone repo
#### git clone https://github.com/yourname/dnse-telegram-bot.git
#### cd dnse-telegram-bot

### 2. Cài thư viện

#### pip install -r requirements.txt

### 3. Tạo file .env

#### cp .env.example .env
#### nano .env

### ▶️ Chạy bot
#### python3 bot_dnse.py




