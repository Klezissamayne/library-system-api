# library-system-api
School Library System REST API (Node.js + MongoDB)
repository https://github.com/Klezissamayne/library-system-api
//
project structure
library-system/
│
├── config/
│   └── db.js
│
├── models/
│   ├── Author.js
│   ├── Book.js
│   ├── Student.js
│   └── Attendant.js
│
├── controllers/
│   ├── authorController.js
│   ├── bookController.js
│   ├── studentController.js
│   └── attendantController.js
│
├── routes/
│   ├── authorRoutes.js
│   ├── bookRoutes.js
│   ├── studentRoutes.js
│   └── attendantRoutes.js
│
├── middleware/
│   ├── validate.js
│   └── auth.js (JWT optional)
│
├── server.js
├── package.json
└── README.md
