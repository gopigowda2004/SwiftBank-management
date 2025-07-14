# SwiftBank – Online Banking System 💳🏦

A full-stack online banking and e-wallet management system with user-friendly features for both customers and administrators.

---

## 🚀 Features

### 👤 User Features
- **User Registration & Login** – Secure JWT authentication system.
- **Multiple Bank Accounts** – Create, manage, and monitor multiple accounts.
- **Fund Transfer** – Transfer funds between accounts.
- **Deposit & Withdraw** – Add or remove funds securely.
- **Profile Management** – Update personal details.
- **Account Deletion** – Users can delete their own account.
- **File Upload** – Upload supporting documents securely.
- **Comments Section** – Users can leave feedback or notes.

### 🛠️ Admin Features
- **User Management** – View and delete any user account.
- **Revoke Access** – Temporarily disable user access without deleting data.
- **File Access** – Download files uploaded by users.

---

## 🧰 Tech Stack

| Layer      | Technology                        |
|------------|-----------------------------------|
| Frontend   | React.js, Redux, JavaScript       |
| Backend    | Spring Boot, Spring Security      |
| Auth       | JWT (JSON Web Tokens)             |
| Build Tool | Maven                             |
| DevOps     | Docker, Docker Compose            |

---

## 🏁 Running the Project

### ✅ Prerequisites
- Java JDK 17+
- Node.js & npm
- Maven
- Docker (optional)

---

### 🔧 Run Without Docker

#### Backend (Spring Boot):
```bash
cd backend
./mvnw spring-boot:run
# For Windows:
mvnw.cmd spring-boot:run



git clone https://github.com/gopigowda2004/SwiftBank-management.git
cd SwiftBank-management
docker-compose up --build




Frontend (React):
cd frontend
npm install
npm start



