<h1 align="center">🚀 Postman API Campus Project</h1>

<p align="center">
  <img src="https://img.shields.io/badge/status-active-success" />
  <img src="https://img.shields.io/badge/tech-stack-Postman-orange" />
  <img src="https://img.shields.io/badge/level-internship-blue" />
</p>

<p align="center">
  <i>Comprehensive API testing framework designed using Postman for the Campus Education Platform</i>
</p>

---

## 🌐 API Environment

> 🧩 Base URL: [https://test.mersys.io](https://test.mersys.io)

All test cases are executed against this staging environment. Auth tokens and environments are configured accordingly.

---

## 📌 Project Goals

✅ Ensure backend APIs are functioning correctly  
✅ Validate workflows via chained requests  
✅ Automate and organize test cases via collections  
✅ Practice real-world API analysis methods (DevTools, Proxies, Swagger Docs)

---

## 📊 Test Categories

| ✅ Feature                         | 🔍 Description                                      |
|-----------------------------------|-----------------------------------------------------|
| Authentication                   | Login / Token flow                                 |
| User Management                  | Create, Edit, Delete Students & Teachers           |
| School Setup                     | Grades, Sections, Parameters                       |
| Lesson & Schedule Management     | Lesson Program, Fields                             |
| Notification & Messaging         | Send / View messages                               |
| Configuration Settings           | Discounts, Attestations, Nationalities             |

---

## 📁 Project Structure

Postman_API_Campus_Project/
├── 📂 Collections/
│ └── Campus_API_Testing.postman_collection.json
├── 📂 Environments/
│ └── Campus_Environment.postman_environment.json
├── 📂 Documentation/
│ ├── 📄 API_Testing_Yontemler.pdf
│ └── 📄 APITesting_UserStories.xlsx
└── 📄 README.md

yaml
Kopyala
Düzenle

---

## 🧪 Testing Techniques Used

### 🛠️ Developer Tools (F12)
- Analyze API calls directly from browser (Network tab)
- View headers, response bodies, and endpoints

### 📚 Swagger & API Docs
- Review endpoint documentation to understand expected behavior

### 🔁 Proxy & Interceptors
- Use Postman Interceptor or tools like Fiddler to trace network traffic

### ⚙️ Test Scripting in Postman
- Use **Pre-request** and **Test** tabs to validate:
  - Status codes
  - JSON schema
  - Token handling
  - Dynamic chaining of requests

---

## 🧩 Sample Workflow

```bash
1️⃣ Login → Save token as environment variable
2️⃣ Use token in headers for next requests
3️⃣ Validate response status = 200
4️⃣ Check response body contains expected fields
5️⃣ Use data from one request in next (chaining)
📌 Tools & Technologies
Tool	Purpose
🟧 Postman	Main testing tool
🌐 Swagger	API documentation source
🧭 DevTools	Network traffic analysis
🟢 Excel	Test scenario planning
💡 Newman (opt.)	CLI-based automation for CI/CD

📜 License
This repository is created for educational purposes under internship scope. Not intended for production usage.
