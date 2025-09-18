# Electricity Billing System  

A desktop-based **Electricity Billing System** built using **Java Swing** and **MySQL**, designed to automate and manage electricity billing operations such as customer management,
bill generation, payment integration, and user authentication.  

---

## 🚀 Features  

- **Login System** – Separate modules for Admin and Customer  
- **Customer Management** – Add, update, and view customer details  
- **Bill Generation** – Generate electricity bills based on meter number and usage  
- **Bill Payment** – Redirect to **Paytm** payment gateway  
- **Utility Tools** – Built-in Notepad and Calculator access  
- **Reports** – View and print generated bills  
- **Database Integration** – Persistent data storage using MySQL  

---

## 🛠️ Tech Stack  

- **Language:** Java (Swing for GUI, AWT for components)  
- **Database:** MySQL  
- **Tools:** JDBC, NetBeans / IntelliJ / Eclipse  
- **Other:** Paytm integration (via JEditorPane)  

---

## 📂 Project Structure  

```
ElectricityBillingSystem/
│
├── src/electricity/billing/system/
│   ├── Project.java              # Main dashboard
│   ├── Login.java                # Login window
│   ├── NewCustomer.java          # Add new customer
│   ├── CustomerDetails.java      # Manage customers
│   ├── GenerateBill.java         # Bill generation & print
│   ├── Paytm.java                # Payment gateway window
│   ├── UpdateInformation.java    # Update customer details
│   ├── Conn.java                 # Database connection helper
│   └── ... (other modules)
│
├── database.sql                  # MySQL database schema
└── README.md                     # Project documentation
```
  
