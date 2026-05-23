# Cinema Database Manager

## 💻 Overview
A robust desktop application developed in **C# Windows Forms** for managing cinematic data. This project bridges the gap between a user-friendly interface and a back-end SQL database, enabling seamless CRUD operations (Create, Read) for film records. It serves as a practical implementation of **ADO.NET** for database connectivity and dynamic information retrieval.

---

## 🤍 Tech Stack
* **Language:** C#
* **Framework:** .NET Framework / Windows Forms (WinForms)
* **Database:** Microsoft SQL Server (`cinema.mdf`)
* **Data Access:** ADO.NET (`System.Data.SqlClient`)

![C#](https://img.shields.io/badge/C%23-Language-%23FF69B4.svg?style=for-the-badge&logo=csharp&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-Database-%23FF69B4.svg?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)

![Backend](https://img.shields.io/badge/ADO.NET-Data_Access-%234F4F4F.svg?style=for-the-badge) ![UI/UX](https://img.shields.io/badge/UI-WinForms-%23333333.svg?style=for-the-badge)

---

## 🎀 Core Functionality
* **Database Integration:** Utilizes `SqlConnection` and `SqlCommand` to perform live insertions into the `filme` table.
* **Structured Data Entry:** Enables users to catalog movies by Title, Category, Lead Actor, and Revenue (Incasari).
* **Dynamic Querying:** Supports search and filter operations based on specific criteria (Category/Actor), providing real-time data views.
* **Secure Termination:** Includes robust event-driven exit controls for safe session management.

---

## 📂 Project Structure
* **`Form1.cs`**: Orchestrates the interaction between the GUI and the SQL database.
* **`buttonAdauga_Click`**: The primary method that parses input data and executes the `INSERT` SQL command.
* **`connString`**: Manages the connection to the local database instance (`cinema.mdf`).
* **`Search & Display Logic`**: Manages data retrieval and visualization in the UI list control.

---

## Visual Demonstration
| Cinema Database Manager |
| :---: |
| <img width="600" src="https://github.com/user-attachments/assets/1eb04172-5865-4be9-8dd2-128d9af718bc" /> |

---

## How to Run
1. **Prerequisites:** Ensure the SQL Server LocalDB component is installed.
2. **Setup:** Verify that the `connString` path points correctly to your `cinema.mdf` file on your machine.
3. **Launch:** Run the compiled application.
4. **Manage:** Add new records or search existing ones via the dedicated control panels.

---

© 2023 Cinema Database System | Developed by [**𝐋𝐞𝐨𝐧𝐭𝐞 𝐏𝐚𝐭𝐫𝐢𝐜𝐢𝐚-𝐌𝐢𝐫𝐚𝐛𝐞𝐥ā**](https://patrrrrrrricia.github.io/glowing-button/)
