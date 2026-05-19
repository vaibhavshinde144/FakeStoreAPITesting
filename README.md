# 🧪 API Testing Project – FakeStoreAPI

## 📌 Project Overview
This repository contains an **API Testing project** built using **Postman** with the **FakeStoreAPI**.  
It includes Postman collections, environment variables, test cases, defect reports, and execution results for validating multiple endpoints.

---

## 📂 Modules Covered
- **Products API**  
  `/products`, `/products/{id}`, `/products/categories`, `/products/category/{categoryName}`  
- **Carts API**  
  `/carts`, `/carts/{id}`  
- **Users API**  
  `/users`, `/users/{id}`  
- **Auth API**  
  `/auth/login`

---

## 📁 Repository Contents
- `FakeStoreAPI.postman_collection.json` → Postman collection with all requests  
- `Test Cases.xlsx` → Designed test cases (positive & negative)  
- `Defect Report.xlsx` → Logged defects with severity, priority, and linked test cases  
- `Test Execution Report.docx` → Execution summary with pass/fail results  
- `Result/` → Folder containing screenshots and supporting evidence  

---

## 🛠 Tools & Environment
- **Postman v10** for API testing  
- **Windows 11** execution environment  
- **FakeStoreAPI** (public mock API)  

---

## ✅ Test Execution Summary
- **Total Test Cases:** 18  
- **Passed:** 12  
- **Failed:** 6  
- **Defects Raised:** 4 (error handling, cart ID, retrieval issues)

---

## 🐞 Defects Logged
- **BUG‑001** – API returns `200 OK` for non‑existing product/user/category  
- **BUG‑002** – API returns `404` instead of `405` for invalid HTTP method  
- **BUG‑003** – Cart ID not generated dynamically (always defaults to 11)  
- **BUG‑004** – Get Cart returns `null` instead of cart details  

---

## 🚀 How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/vaibhavshinde144/API-Project.git
