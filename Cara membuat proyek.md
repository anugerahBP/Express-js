Membuat Proyek:
Buat folder proyek dan masuk ke dalamnya melalui terminal.

bash

mkdir nodejs-auth-api
cd nodejs-auth-api

Inisialisasi Proyek:
Inisialisasi proyek Node.js dan instal beberapa dependensi yang diperlukan.

bash

npm init -y
npm install express mongoose bcrypt jsonwebtoken

Membuat Struktur File:
Buat struktur file seperti berikut: 
├── controllers
│   └── authController.js
├── models
│   └── User.js
├── routes
│   └── authRoutes.js
├── app.js
└── .env
