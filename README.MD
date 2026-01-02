# Full-Stack Chat App

![Chat App Screenshot 1](/floo-network/main/frontend/public/screenshot-for-readme.png)
![Chat App Screenshot 2](/floo-network/main/frontend/public/screenshot-for-readme-1.png)
## Key Features
...

##  **Key Features**

### **User Experience**
- Secure registration and login with custom JWT tokens
- Real-time online/offline status indicators
- Modern, clean interface with customizable themes

### **Real-time Communication**
- Instant messaging with Socket.io
- Live typing indicators
- User presence tracking
- Real-time notifications

### **Security & Performance**
- API rate-limiting with Arcjet
- Protected routes and endpoints

---

##  **Technical Stack**

| Category       | Technologies Used                          |
|----------------|--------------------------------------------|
| **Frontend**   | React, Tailwind CSS, DaisyUI, Zustand     |
| **Backend**    | Node.js, Express, Socket.io, JWT          |
| **Database**   | MongoDB                                    |
| **Services**   | Cloudinary, Resend, Arcjet                |
| **DevOps**     | Git, GitHub, Environment Variables        |

---

## **Setup & Installation**

### **Prerequisites**
- Node.js (v18 or higher)
- MongoDB instance
- Accounts for Cloudinary, Resend, and Arcjet (free tiers available)

### **Backend Configuration**
Create `.env` file in `/backend`:

```env
PORT=3000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secure_jwt_secret
NODE_ENV=development
RESEND_API_KEY=your_resend_api_key
EMAIL_FROM=your_verified_email@domain.com
EMAIL_FROM_NAME="Chat App Team"
CLIENT_URL=http://localhost:5173
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
ARCJET_KEY=your_arcjet_key
ARCJET_ENV=development
```

### **Installation Steps**

1. **Clone and Setup Backend:**
```bash
cd backend
npm install
npm run dev
```

2. **Clone and Setup Frontend:**
```bash
cd frontend
npm install
npm run dev
```

3. **Access Application:**
- Frontend: `http://localhost:5173`
- Backend API: `http://localhost:3000`

---
