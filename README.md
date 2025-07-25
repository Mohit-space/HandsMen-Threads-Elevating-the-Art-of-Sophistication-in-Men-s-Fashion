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
<img width="1918" height="866" alt="Screenshot 2025-07-20 000314" src="https://github.com/user-attachments/assets/a6e8e33c-80c2-4c7a-98c5-34a64ad536f4" />
🔄 Custom Objects: HandsMen Order
<img width="1919" height="873" alt="Screenshot 2025-07-20 000332" src="https://github.com/user-attachments/assets/ce0126df-b40e-4299-af92-54a0a6caf659" />
🔄 Custom Objects: HandsMen Product
<img width="1917" height="866" alt="Screenshot 2025-07-20 000353" src="https://github.com/user-attachments/assets/b763cc44-efbf-49bd-992b-3c3500ed5520" />
🔄 Custom Objects: Inventory
<img width="1919" height="873" alt="Screenshot 2025-07-20 000409" src="https://github.com/user-attachments/assets/381bd659-39ab-4adf-8596-3f6d95757fe9" />
🔄 Custom Objects: Marketing Campaign
<img width="1919" height="872" alt="Screenshot 2025-07-20 000526" src="https://github.com/user-attachments/assets/69ad606c-db2a-445c-b297-0645c5ad86c2" />
🔄 Flow: Loyalty Program
<img width="1919" height="867" alt="Screenshot 2025-07-20 000629" src="https://github.com/user-attachments/assets/22efadaf-b91b-48c9-9855-030d6679b830" />
🔄 Flow: Loyalty Program Recieved Email
<img width="1918" height="870" alt="Screenshot 2025-07-20 000901" src="https://github.com/user-attachments/assets/26c57bd9-57e4-4a7e-9d83-201bc2b8756f" />
🔄 Flow: Order Confirmation
<img width="1919" height="929" alt="Screenshot 2025-07-20 000712" src="https://github.com/user-attachments/assets/5b008cd5-3fb1-4200-9976-c769c7bd2c42" />
🔄 Flow: Order Confirmation Recieved Email
<img width="1919" height="875" alt="Screenshot 2025-07-20 000831" src="https://github.com/user-attachments/assets/c63341d1-a09f-4d30-b816-73a70c0eefd9" />
🔄 Flow: Stock Alert
<img width="1919" height="924" alt="Screenshot 2025-07-20 000745" src="https://github.com/user-attachments/assets/36520403-7e5f-4b7c-905a-a836cf7d73f9" />
🔄 Flow: Stock Alert Recieved Email
<img width="1919" height="857" alt="Screenshot 2025-07-20 000847" src="https://github.com/user-attachments/assets/4b479645-6c7c-44eb-b241-956b0c0a4068" />
🔄 Classic Email Template
<img width="1919" height="935" alt="Screenshot 2025-07-20 000945" src="https://github.com/user-attachments/assets/760d57fa-0446-48f3-8cca-4323873790e9" />
🔄 Developer Console
<img width="1919" height="917" alt="Screenshot 2025-07-20 001455" src="https://github.com/user-attachments/assets/81e80a01-2911-48fd-becd-87682df0f6a6" />

📄 License This project is for academic and showcase purposes. Please feel free to fork or reference for learning purposes.

💬 Feedback Have suggestions or want to collaborate? Feel free to open an issue or drop me a message!


