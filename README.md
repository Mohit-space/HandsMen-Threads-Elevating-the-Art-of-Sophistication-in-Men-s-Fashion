# 🧵 HandsMen Threads - Salesforce Project

**Elevating the Art of Sophistication in Men's Fashion**

This project represents a Salesforce-based digital transformation initiative for *HandsMen Threads*, a forward-thinking fashion brand. The goal is to streamline internal operations and enhance customer engagement through intelligent automation, robust data models, and personalized user experiences.

---

## 🚀 Project Overview

HandsMen Threads is implementing Salesforce to centralize data, automate core workflows, and boost operational efficiency. The application is designed for use by sales, customer service, and inventory management teams to ensure seamless communication and real-time insights across departments.

---

## 🛠️ Key Features

- ✅ **Automated Order Confirmations**  
  Customers receive order confirmation emails instantly after placing an order.

- 🏆 **Dynamic Loyalty Program**  
  Customers' loyalty statuses update automatically based on their purchase history.

- 📦 **Proactive Stock Alerts**  
  Inventory alerts are sent when stock drops below 5 units, ensuring proactive replenishment.

- 🕛 **Scheduled Bulk Order Updates**  
  Nightly batch jobs process bulk orders, update financial records, and adjust inventory automatically.

---

## 📐 Data Model Highlights

- Custom Objects:
  - `Customer`
  - `Order`
  - `Product`
  - `LoyaltyTier`
  - `Inventory`

- Relationships:
  - One-to-many between Customers and Orders
  - Many-to-one between Orders and Products
  - One-to-one between Customer and LoyaltyTier

---

## ⚙️ Technologies & Tools Used

| Tool | Purpose |
|------|---------|
| **Salesforce Lightning App Builder** | Custom UI and layout creation |
| **Record-Triggered Flows** | Automate real-time operations |
| **Apex Triggers** | Execute logic like updating loyalty status |
| **Batch Apex** | Process bulk records (e.g., orders) asynchronously |
| **Validation Rules** | Ensure data integrity from UI |
| **Scheduled Apex** | Run nightly inventory & order updates |

---

## 📚 What I Learned

- Designing scalable **Salesforce Data Models**
- Implementing **automation with Flows and Apex**
- Maintaining **data integrity** using validation rules and Flow error handling
- Building **custom apps** with Lightning App Builder
- Writing **Apex and Asynchronous Apex** for complex operations


🔗 Project Links 🎥 Demo Video:https://drive.google.com/file/d/1K9giCr1mE7cJpYiYXGdcWeMAqHMv4CGF/view?usp=drive_link

💻 GitHub Repository: https://github.com/yashbhamare-lab/HandsMen-Threads-Elevating-the-Art-of-Sophistication-in-Men-s-Fashion

---
🔄 Custom Objects: HandsMen Customer
<img width="1898" height="924" alt="Screenshot 2025-07-25 003649" src="https://github.com/user-attachments/assets/cdec8441-7890-48ee-a0d5-9a1af9d6f70c" />
🔄 Custom Objects: HandsMen Order
<img width="1911" height="926" alt="Screenshot 2025-07-25 003739" src="https://github.com/user-attachments/assets/91fc501f-7bc0-4129-b9f6-b7098e73de5b" />
🔄 Custom Objects: HandsMen Product
<img width="1911" height="925" alt="Screenshot 2025-07-25 003852" src="https://github.com/user-attachments/assets/c936e5f0-b7e5-4d25-b6d4-f1f0ee1bfd8a" />
🔄 Custom Objects: Inventory
<img width="1914" height="911" alt="Screenshot 2025-07-25 004018" src="https://github.com/user-attachments/assets/9191a857-ceb1-4dac-bbbf-0c9d3d66844e" />
🔄 Custom Objects: Marketing Campaign
<img width="1911" height="921" alt="Screenshot 2025-07-25 004137" src="https://github.com/user-attachments/assets/fc938f86-688f-4b2b-badf-09683d8d3063" />
🔄 Flow: Loyalty Program Recieved Email
<img width="1010" height="489" alt="image" src="https://github.com/user-attachments/assets/67a44edb-b4a6-423b-8852-4099b6e24a05" />
🔄 Flow: Order Confirmation
<img width="989" height="485" alt="image" src="https://github.com/user-attachments/assets/9a73b60e-650c-435a-bc1b-6d14f10c3017" />
🔄 Flow: Order Confirmation Recieved Email
<img width="1919" height="875" alt="Screenshot 2025-07-20 000831" src="https://github.com/user-attachments/assets/c63341d1-a09f-4d30-b816-73a70c0eefd9" />
🔄 Flow: Stock Alert
<img width="1401" height="781" alt="Screenshot 2025-07-25 004300" src="https://github.com/user-attachments/assets/ef72f342-c677-4508-aece-39d2688f27e2" />
🔄 Developer Console
<img width="1915" height="958" alt="Screenshot 2025-07-25 004408" src="https://github.com/user-attachments/assets/1ac56775-3d83-4ac9-8f2b-c956d75c37f1" />


📄 License This project is for academic and showcase purposes. Please feel free to fork or reference for learning purposes.

💬 Feedback Have suggestions or want to collaborate? Feel free to open an issue or drop me a message!


