<div align="center">

# 🏦 Java ATM Simulation System
### *Secure State Management • Transaction Logic • Console-Based Banking*

<p>
  <img src="https://img.shields.io/badge/Java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Interface-CLI-lightgrey?style=for-the-badge&logo=gnumetadata&logoColor=white" />
  <img src="https://img.shields.io/badge/Logic-Conditional%20Flow-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Security-Input%20Validation-success?style=for-the-badge" />
</p>

---

**[ 💻 Usage ](#-system-workflow) • [ ✨ Features ](#-core-capabilities) • [ ⚙️ Logic Architecture ](#-software-architecture) • [ 📬 Contact ](#-author)**

</div>

---

## 🏛️ System Workflow
The program simulates a real-world ATM experience through a continuous loop, ensuring the user can perform multiple transactions in a single session.

[Image of ATM transaction flow chart showing deposit withdraw and balance check]

| Step | Action | Description |
| :--- | :--- | :--- |
| **1** | **Authentication** | Program initializes with a secure default state. |
| **2** | **Menu Selection** | User chooses from 4 core banking operations. |
| **3** | **Validation** | System checks for sufficient funds or negative inputs. |
| **4** | **Execution** | State is updated and a confirmation is displayed. |

---

## 🚀 Core Capabilities

### 💰 Financial Operations
* **Balance Inquiry:** Real-time retrieval of the current account standing.
* **Smart Deposits:** Seamlessly add funds with immediate balance synchronization.
* **Secure Withdrawals:** Logic-gate protected withdrawals to prevent overdrafts.

### 🛠️ Technical Highlights
* **Scanner Integration:** Robust handling of user input via the `java.util.Scanner` class.
* **Persistent Loop:** A `while(true)` or `do-while` implementation that keeps the session alive until the user chooses to exit.
* **Error Handling:** Graceful management of invalid menu choices or non-numeric entries.

---
