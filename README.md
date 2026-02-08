🚀 dhquanganhTechWeb

dhquanganhTechWeb là một dự án website backend + frontend xây dựng bằng Node.js & Express, sử dụng EJS làm template engine và MongoDB làm cơ sở dữ liệu.
Dự án hướng tới một website công nghệ / web quản trị với đầy đủ các chức năng xác thực người dùng, quản lý dữ liệu và hiển thị biểu đồ.

🌐 Demo (Render):
https://technodejsweb.onrender.com/
 (nếu còn hoạt động)

✨ Tính năng chính

🔐 Đăng ký / đăng nhập người dùng

🔑 Xác thực bằng:

Email & mật khẩu (JWT, Session)

Google OAuth

Facebook OAuth

📧 Gửi email (xác nhận, thông báo, reset mật khẩu…)

🧑‍💼 Quản lý người dùng

📊 Hiển thị biểu đồ thống kê bằng Chart.js

🖼 Upload hình ảnh (Multer + Cloudinary)

🗃 Lưu trữ dữ liệu với MongoDB (Mongoose)

🍪 Session, Cookie, phân quyền người dùng

🧩 Template layout với EJS Layouts

🧰 Công nghệ sử dụng
Backend

Node.js

Express.js

MongoDB + Mongoose

JWT (jsonwebtoken)

Express-session

Frontend

EJS

CSS / JavaScript

Chart.js

Xác thực & tiện ích

Passport.js

Google OAuth 2.0

Facebook Strategy

BcryptJS (mã hoá mật khẩu)

Multer (upload file)

Cloudinary (lưu ảnh)

Nodemailer / Resend (gửi email)

dotenv (biến môi trường)

📁 Cấu trúc thư mục (tham khảo)
dhquanganhTechWeb/
│
├── src/
│   ├── index.js            # File khởi động server
│   ├── routes/             # Định nghĩa các route
│   ├── controllers/        # Xử lý logic
│   ├── models/             # Schema MongoDB
│   ├── views/              # Giao diện EJS
│   ├── public/             # CSS, JS, image
│   ├── config/             # Cấu hình DB, passport, cloudinary
│
├── .env                    # Biến môi trường
├── package.json
├── package-lock.json
├── .gitignore
└── README.md

⚙️ Cài đặt & chạy dự án
1️⃣ Clone repository
git clone https://github.com/dhquanganh/dhquanganhTechWeb.git
cd dhquanganhTechWeb

2️⃣ Cài đặt dependencies
npm install

3️⃣ Tạo file .env

Ví dụ:

PORT=3000
MONGODB_URI=mongodb+srv://<username>:<password>@cluster.mongodb.net/dbname

SESSION_SECRET=your_secret_key
JWT_SECRET=your_jwt_secret

GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret

FACEBOOK_CLIENT_ID=your_facebook_client_id
FACEBOOK_CLIENT_SECRET=your_facebook_client_secret

CLOUDINARY_CLOUD_NAME=xxxx
CLOUDINARY_API_KEY=xxxx
CLOUDINARY_API_SECRET=xxxx

EMAIL_USER=your_email
EMAIL_PASS=your_password

4️⃣ Chạy server
npm start


➡ Truy cập:
http://localhost:3000

🧪 Script có sẵn
"scripts": {
  "start": "nodemon src/index.js"
}


Server tự reload khi thay đổi code nhờ nodemon

📌 Ghi chú

Dự án sử dụng Express 5

Phù hợp để:

Học Node.js + Express

Làm đồ án môn Web / Backend

Phát triển dashboard / website quản trị

Có thể mở rộng:

Role Admin / User

REST API

React/Vue frontend
