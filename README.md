# Final Project — Class Industry Basic
> 
> *"Logos (Reason) is the governing principle of the universe. Let your code be an extension of that rational order."*

---

## 📝 Project Overview

a robust Point of Sale (POS) system designed as the **Final Capstone Project** for the Class Industry program. Built with **PHP Native** and **MySQL**, this project focuses on high-performance transaction handling, and logical state management.

Inspired by Stoic philosophy, the system emphasizes **resilience** and **determinism**—ensuring that every calculation, from tax to inventory, follows a strict rational order.

### Key Features:
- **Dynamic Product Catalog:** Filterable menu items synced directly with a MySQL database.
- **Rational Cart Logic:** A session-based shopping cart that handles discounts and quantity updates in real-time.
- **Automated Taxation:** Hardcoded `TAX_RATE` (11%) implementation ensuring financial consistency.
- **Responsive Interface:** A sleek, mobile-ready dashboard built with Tailwind CSS.

---

## 🏗️ Architecture & The Logos (Logic)

This project follows a **Decoupled Logic** structure to ensure system stability (Ataraxia):

1.  **System Layer (`/system`):** The "Rational Faculty" of the app. It handles database connections and core helper functions like `useQuery()`.
2.  **Action Layer (`/actions`):** The "Source of Truth." Contains pure business logic for products, categories, and cart manipulation.
3.  **Presentation Layer (`index.php`):** The "Interface with the World." It renders the UI based on data provided by the underlying logic layers.

---

## 🚀 Tech Stack

| Component | Technology | Role |
| :--- | :--- | :--- |
| **Back-End** | PHP 8.x | Server-side processing & Session management |
| **Database** | MySQL | Persistent data storage (The Source of Truth) |
| **Front-End** | Tailwind CSS | Orderly, utility-first UI design |

---

## ⚙️ Stoic Principles in Development

- **Amor Fati (Love of Fate):** We embrace bugs not as failures, but as necessary data points to improve the system's integrity.
- **Logical Determinism:** Given the same inputs (Price, Discount, Tax), the system will always produce the same rational output.

---

## 🛠️ Installation & Setup

To deploy this project in your local environment, follow these steps:

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/fawwazgoreng/project_akhir_cls_industry_basic.git](https://github.com/fawwazgoreng/project_akhir_cls_industry_basic.git)
    ```
2.  **Database Configuration:**
3.  **Deploy to Server:**
    - Move the project folder to your local server directory (e.g., `htdocs` or `www`).
    - Open your browser and navigate to `http://localhost/your-folder-name/index.php`.
4.  **Execute:** Start processing transactions and experience the order of the system.

---

## 🤝 Contributing

This project is built for learning. If you wish to contribute:
1. Fork the repository.
2. Create a feature branch: `git checkout -b feat/YourLogicalFeature`.
3. Commit your changes: `git commit -m 'feat: add resilient payment logic'`.
4. Push to the branch: `git push origin feat/YourLogicalFeature`.
5. Open a Pull Request.

---

## 📄 License
This project is part of the **Class Industry Final Homework**. It is intended for educational purposes.
