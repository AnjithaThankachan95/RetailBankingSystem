# Retail Banking System (Open Source)

## 🚀 Project Overview
This is an **open-source Retail Banking System** that allows users to:
✅ Apply for **credit cards**  
✅ View **transaction history**  
✅ Make **bill payments**  
✅ Set up **spending limits & alerts**  
✅ Manage **rewards & cashback**  

## 🛠 Tech Stack
- **Frontend:** React + TypeScript
- **Backend:** ASP.NET Core Web API
- **Database:** Azure SQL
- **Authentication:** Azure AD B2C
- **Payments:** Stripe API
- **Hosting:** Azure App Service & Azure Static Web Apps

## 📂 Project Structure
```
/RetailBankingSystem
│── /backend (ASP.NET Core API)
│   ├── Controllers (CreditCard, Transactions API)
│   ├── Models (User, CreditCard, Transaction)
│   ├── Data (Entity Framework, Azure SQL)
│── /frontend (React + TypeScript)
│   ├── src/components (CreditCardList, TransactionHistory)
│   ├── src/pages (Dashboard, Payments)
│── README.md
│── .gitignore
```

## 🏗 Setup Instructions
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/AnjithaThankachan95/RetailBankingSystem.git
cd RetailBankingSystem
```

### 2️⃣ Backend Setup (ASP.NET Core)
```sh
cd backend
 dotnet restore
 dotnet run
```
Backend runs at: `http://localhost:5000`

### 3️⃣ Frontend Setup (React)
```sh
cd frontend
npm install
npm start
```
Frontend runs at: `http://localhost:3000`

## 🏆 Features
- **Secure authentication with Azure AD B2C**
- **Transaction management** (view, filter, export)
- **Credit card spending limit alerts**
- **Bill payments using Stripe API**

## 🌍 Contributing
1. Fork the repo and create a new branch (`feature-branch`)
2. Make your changes and commit (`git commit -m "Added new feature"`)
3. Push your changes (`git push origin feature-branch`)
4. Create a Pull Request

## 📜 License
This project is licensed under the **MIT License**.

---

## 📄 .gitignore for .NET & React
```
# ASP.NET Core specific
bin/
obj/
appsettings.json
appsettings.Development.json

# React specific
node_modules/
dist/
build/
.env

# IDE settings
.vscode/
.idea/
.DS_Store
```

🚀 Ready to contribute? Start coding now! 😃
