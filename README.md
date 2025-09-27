# 🔐 Simple Auth

## 🚀 Cách chạy

### 1. Vào thư mục chứa dự án

cd src/simple_auth
2. Cài đặt dependencies
bash
Copy code
npm install express
Basic Auth
Chạy server
bash
Copy code
node basic_auth.js
Kiểm tra API
GET: http://localhost:3000/
<img width="960" height="540" alt="3000" src="https://github.com/VoVanTuTai/simple_auth/blob/main/Images_report/3000.png" />
GET: http://localhost:3000/public
<img width="960" height="540" alt="3000" src="https://github.com/VoVanTuTai/simple_auth/blob/main/Images_report/3000_public.png" />
Cookie Auth
Chạy server
bash
Copy code
node cookie_auth.js
Kiểm tra API
POST: http://localhost:3001/login
<img width="960" height="540" alt="3000" src="https://github.com/VoVanTuTai/simple_auth/blob/main/Images_report/3001_login.png" />
<img width="960" height="540" alt="3000" src="https://github.com/VoVanTuTai/simple_auth/blob/main/Images_report/data_in_mongo.png" />
GET: http://localhost:3001/profile
<img width="960" height="540" alt="3000" src="https://github.com/VoVanTuTai/simple_auth/blob/main/Images_report/3001_profile.png" />
GET: http://localhost:3001/logout
<img width="960" height="540" alt="3000" src="https://github.com/VoVanTuTai/simple_auth/blob/main/Images_report/3001_logout.png" />
<img width="960" height="540" alt="3000" src="https://github.com/VoVanTuTai/simple_auth/blob/main/Images_report/data_in_mongo_logout.png" />
