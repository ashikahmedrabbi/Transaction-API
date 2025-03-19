
### **📌 dmoney API Testing with Postman & Newman**  

![Postman](https://img.shields.io/badge/Postman-API%20Testing-orange?logo=postman)  
![Newman](https://img.shields.io/badge/Newman-CLI%20Runner-brightgreen)  
![GitHub](https://img.shields.io/badge/GitHub-README-blue?logo=github)  

---

## **📖 Overview**  
This repository contains API test cases for the **dmoney API**, executed using **Postman** and automated using **Newman**. The test cases include **positive and negative scenarios**, covering user transactions such as deposits, withdrawals, payments, and balance checks.  

---

## **🚀 Collection Details**  
 
✅ **API Documentation:** [View on Postman](https://documenter.getpostman.com/view/35150579/2sAYkEqf2s)  
✅ **Test Case(Google Sheet):** [View Test case](https://docs.google.com/spreadsheets/d/1UCIiJQstDOM2JnPFtW_6ZilzOdoKf5pSWwYTChA6QEs/edit?usp=sharing)                            
✅ **Bug Report (Google Sheet):** [View Bugs](https://docs.google.com/spreadsheets/d/1kmEWiuRll3JnPXNaORihMcefPwxfDTqbRZmPTJE0wgU/edit?usp=sharing)  

---

## **📂 Test Cases Covered**  
| Test Scenario | Status | Notes |
|--------------|--------|-------|
| ✅ Admin creates an Agent, Customers, and Merchant | ✅ Passed | - |
| ✅ Deposit money from SYSTEM to Agent | ✅ Passed | - |
| ✅ Agent deposits money to Customer | ✅ Passed | - |
| ✅ Check Agent's balance | ✅ Passed | - |
| ✅ Send money between Customers | ✅ Passed | - |
| ✅ Customer withdraws money via Agent | ✅ Passed | - |
| ✅ Check Customer's balance & transaction history | ✅ Passed | - |
| ✅ Customer makes a payment to Merchant | ✅ Passed | - |
| ✅ Merchant checks balance | ✅ Passed | - |
| ❌ Negative Case: Deposit negative amount | ❌ Failed | Expected error handling |
| ❌ Negative Case: Withdraw more than balance | ❌ Failed | Expected insufficient balance error |

---

## **⚡ Running Tests with Newman**  
To run the test collection using **Newman**, follow these steps:  

### **1️⃣ Install Newman (if not installed)**
```bash
npm install -g newman
```

### **2️⃣ Run Tests from Terminal**
```bash
newman run ... -r html,cli --reporter-html-export newman_report.html
```

### **3️⃣ View the HTML Report**
After execution, open **`newman_report.html`** in your browser to check the detailed test results.

---

## **🐞 Bug Reports & Improvements**
A detailed **bug report** is maintained in a **Google Sheet**, listing API issues and improvement suggestions.  

📌 **Bug Report:** [Click Here](#) *(Replace with actual link to Google Sheet)*  

### **Example Bug Report Entry**  
| Issue Type | Title | Description | Steps to Reproduce | Actual Result | Expected Result | Priority | Severity |
|------------|-------|-------------|---------------------|---------------|-----------------|---------|---------|
| Bug | Insufficient Balance Handling | API allows withdrawal exceeding balance | 1. Create a Customer <br> 2. Withdraw more than available balance | Transaction success | Error: Insufficient Balance | High | Critical |

---

## **📸 Screenshots**  
### **Newman Report Screenshot**


![screencapture-127-0-0-1-5500-newman-Transaction-API-2025-03-19-12-12-02-035-0-html-2025-03-19-19_32_32](https://github.com/user-attachments/assets/a6b610cc-62d1-4224-a518-87d6179838d2)

---

## **📌 Contribution & Feedback**
- If you find issues, feel free to **raise an issue** or **submit a pull request**.  
- For feedback, contact via **GitHub Discussions** or **email**.  

---

## **📜 License**
This project is licensed under **MIT License**. Feel free to use and contribute!  

---

