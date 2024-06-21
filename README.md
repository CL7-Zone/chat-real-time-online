# TÊN DỰ ÁN CHAT REAL-TIME - WEBCHAT

https://webchat-react-app1.vercel.app/

### Những chức năng chính - Main functions

```js
Đăng nhập - Login 
Đăng xuất - Logout
Đăng ký - Sign-up
Nhắn tin thời gian thực - Chat real-time
Nhắn tin với rô bốt tự động nhắn tin trên facebook - Chatbot on Facebook
```

### Hướng dẫn cài đặt dự án - Setting project tutorial

```js
Tải môi trường node js về link tải: https://nodejs.org/en
Bước 1: tải dự án trên github về
Bước 2: vào thư mục Backend bật công cụ code lên vào thư mục dự án
(Web-chat)
Bước 3: gõ npm install dưới terminal và cài đặt các 
phụ thuộc này để chạy dự án: npm install
    "axios": "^1.4.0",
    "bcryptjs": "^2.4.3",
    "cookie-parser": "^1.4.6",
    "cors": "^2.8.5",
    "delay": "^6.0.0",
    "dotenv": "^16.0.3",
    "express": "^4.18.2",
    "express-flash": "github:RGBboy/express-flash",
    "express-handlebars": "^7.0.7",
    "express-session": "^1.17.3",
    "google-tts-api": "^2.0.2",
    "joi": "^17.11.0",
    "joi-password-complexity": "^5.2.0",
    "jsonwebtoken": "^9.0.2",
    "moment": "^2.29.4",
    "mongoose": "^7.0.5",
    "netlify-cli": "^16.6.1",
    "netlify-lambda": "^2.0.16",
    "node-google-tts-api": "^1.1.1",
    "nodemon": "^2.0.22",
    "play-sound": "^1.1.6",
    "request": "^2.88.2",
    "say": "^0.16.0",
    "socket.io": "^4.6.1"
Bước 4: npm start để chạy phần máy chủ
Bước 5: Vào thư mục Frontend bật công cụ code tab thứ 2 lên vào thư mục dự án
(my-react-app)
Bước 6: gõ npm install dưới terminal và cài đặt các 
phụ thuộc này để chạy dự án: npm install
    "js-cookie": "^3.0.5",
    "jsonwebtoken": "^9.0.2",
    "mdb-react-ui-kit": "^7.0.0",
    "react": "^18.2.0",
    "react-dom": "^18.2.0",
    "react-redux": "^9.0.4",
    "react-router-dom": "^6.21.0",
    "react-scripts": "5.0.1",
    "react-scroll-to-bottom": "^4.2.0",
    "react-scroll-to-top": "^3.0.0",
    "react-toastify": "^9.1.3",
    "redux": "^5.0.1",
    "socket.io-client": "^4.7.2",
Bước 7: npm start để chạy phần giao diện

END SUB(Download the Node.js environment from the download link: https://nodejs.org/en
Step 1: Download the project from GitHub.
Step 2: Open the code editor in the Backend 
folder of the project (Web-chat).
Step 3: Type npm install in the terminal and install the 
following dependencies to run the project: 
    "axios": "^1.4.0",
    "bcryptjs": "^2.4.3",
    "cookie-parser": "^1.4.6",
    "cors": "^2.8.5",
    "delay": "^6.0.0",
    "dotenv": "^16.0.3",
    "express": "^4.18.2",
    "express-flash": "github:RGBboy/express-flash",
    "express-handlebars": "^7.0.7",
    "express-session": "^1.17.3",
    "google-tts-api": "^2.0.2",
    "joi": "^17.11.0",
    "joi-password-complexity": "^5.2.0",
    "jsonwebtoken": "^9.0.2",
    "moment": "^2.29.4",
    "mongoose": "^7.0.5",
    "netlify-cli": "^16.6.1",
    "netlify-lambda": "^2.0.16",
    "node-google-tts-api": "^1.1.1",
    "nodemon": "^2.0.22",
    "play-sound": "^1.1.6",
    "request": "^2.88.2",
    "say": "^0.16.0",
    "socket.io": "^4.6.1"
Step 4: Run npm start to start the server.
Step 5: Open the code editor in the Frontend 
folder of the project (my-react-app).
Step 6: Type npm install in the terminal and install
the following dependencies to run the project:
    "js-cookie": "^3.0.5",
    "jsonwebtoken": "^9.0.2",
    "mdb-react-ui-kit": "^7.0.0",
    "react": "^18.2.0",
    "react-dom": "^18.2.0",
    "react-redux": "^9.0.4",
    "react-router-dom": "^6.21.0",
    "react-scripts": "5.0.1",
    "react-scroll-to-bottom": "^4.2.0",
    "react-scroll-to-top": "^3.0.0",
    "react-toastify": "^9.1.3",
    "redux": "^5.0.1",
    "socket.io-client": "^4.7.2"
Step 7: Run npm start to start the frontend.)
```

### Mô tả dự án - Description project

```js
An intelligent chatbot can be used on Facebook 
and the website for real-time conversations.
```


### Học NodeJS cùng tôi - Learn NodeJS with me

```js
Node js là gì?

-> Node js là 1 nền tảng được thiết kế bằng mã javascript
Chạy trên môi trường engine v8 của google

I/O là gì?

-> I/O (input/output) là mô hình xử lý không đồng bộ, 
sẽ truy cập mọi thứ bên ngoài ứng dụng, 
cho phép xử lý nhiều yêu cầu HTTP cùng lúc. 
I/O sẽ được tải vào bộ nhớ máy để chạy 
chương trình sau khi khởi động ứng dụng.

Ưu điểm của Node.js là gì?

-> Khả năng mở rộng lớn bằng cách sử dụng module và thư viện, 
đáp ứng yêu cầu của các ứng dụng web lớn.
Tốc độ xử lý nhanh với event loop.
Phù hợp với những ứng dụng chạy thời gian thực vì code chạy bất đồng bộ
Có thể sử dụng cùng một ngôn ngữ JavaScript cho cả phía máy chủ và khách hàng.
Cộng đồng lớn với nhiều thư viện mã nguồn.
```
```js
Lập trình hướng sự kiện (event-driven) có nghĩa là gì?

-> lập trình hướng sự kiện có nghĩa là thiết kế những 
hành động nào đó trên giao diện của ứng dụng 
(ví dụ như: xây dựng ứng dụng nhắn tin cho người dùng
vào nhắn tin khi đó chúng ta sẽ phải lập trình nên những
sự kiến để người dùng gõ vào và bấm nút gửi tin nhắn và
hiển thị tin nhắn thì đây gọi là những sự kiện).
- Và lập trình hướng sự kiện thường được sử dụng cho các
ứng dụng chạy thời gian thực vd như: ứng dụng nhắn tin, ứng
dụng chơi game...
```
```js
NPM là gì?

-> NPM là (Node Package Manager) là 1 module quản lý các thư viện của node js

REPL trong NodeJS là gì?

-> REPL là viết tắt của Read, Eval, Print và Loop là một đặc tính của 
NodeJS cho phép lập trình viên viết code và chạy trực tiếp trên 
màn hình shell/console/terminal để debug, kiểm tra code mà không
cần tạo ra bất cứ file hay folder nào.

Các framework nổi tiếng chạy trên NodeJS

-> NestJS, ExpressJS, KoaJS, ...
```

-   https://quantrimang.com/cong-nghe/nhung-dieu-can-biet-ve-lap-trinh-huong-su-kien-trong-node-js-199629#google_vignette

-   https://topdev.vn/blog/list-cau-hoi-phong-van-nodejs-developer-hay-va-kho/?utm_source=google&utm_medium=cpc&utm_campaign=topdev&utm_content=performance&gad_source=1&gclid=CjwKCAjwydSzBhBOEiwAj0XN4PhQR1OcIAbz2PQCL8OlTzOmGby_n0FTZywX_iJhTgNTTV__9w-K0BoC9lQQAvD_BwE

-   https://itnavi.com.vn/blog/cau-hoi-phong-van-nodejs