# Photo Gallery Viewer

## 💻 Overview
A lightweight and intuitive desktop application designed for seamless image browsing. Built with **C# Windows Forms**, this gallery viewer provides an elegant interface for organizing and navigating through image collections. It emphasizes user experience through fluid navigation controls, automated directory scanning, and real-time indexing.

---

## 🤍 Tech Stack
* **Language:** C#
* **Framework:** .NET Framework / Windows Forms (WinForms)
* **Design Pattern:** Event-Driven Programming
* **IO:** System.IO (File System manipulation)

![C#](https://img.shields.io/badge/C%23-Language-%23FF69B4.svg?style=for-the-badge&logo=csharp&logoColor=white) ![.NET](https://img.shields.io/badge/.NET-WinForms-%23FF69B4.svg?style=for-the-badge&logo=dotnet&logoColor=white)

![System.IO](https://img.shields.io/badge/IO-File_Handling-%234F4F4F.svg?style=for-the-badge&logo=databricks&logoColor=white) ![UI/UX](https://img.shields.io/badge/UI-WinForms-%23333333.svg?style=for-the-badge)

---

## 🎀 Core Functionality
* **Dynamic Loading:** Automatically scans the local `/Foto` directory for `.jpg` files upon application launch.
* **Navigation Engine:**
    * **Sequential Browsing:** Forward and backward navigation between images.
    * **Jump Controls:** Dedicated buttons to skip directly to the first or last image in the collection.
* **State Management:**
    * **Index Tracking:** Real-time display of the current image index relative to the total collection count.
    * **Boundary Awareness:** Intelligent button activation/deactivation to prevent navigation out of bounds.
* **Responsive UI:** Clean, minimalist design featuring integrated status indicators for a professional user experience.

---

## 📂 Project Structure
* **`Form1.cs`**: Contains the core logic for the application, including directory traversal, event handling, and UI state synchronization.
* **`/Foto`**: Local directory for storing image assets.
* **`LoadImages()`**: Initialization method for file system verification and image caching into memory.
* **`EnableDisable()`**: Logic controller for managing button state based on the current navigation index.

---

### Visual Documentation

| 1 | 2 | 3 |
| :---: | :---: | :---: |
| <img width="300" src="https://github.com/user-attachments/assets/e31fe717-0b8f-480b-8fcb-24ddaea8358b" /> | <img width="300" src="https://github.com/user-attachments/assets/5767450e-c02d-481c-b2ea-1715989648c3" /> | <img width="300" src="https://github.com/user-attachments/assets/f32be469-75ed-4b00-84bf-54d0eb1aa68a" /> |
| 4 | 5 | 6 |
| <img width="300" src="https://github.com/user-attachments/assets/565c1515-7805-441a-aeae-cfc9c1cbbaa6" /> | <img width="300" src="https://github.com/user-attachments/assets/5c5342d8-3fd7-4f93-a51d-4b14c8dc4684" /> | <img width="300" src="https://github.com/user-attachments/assets/0831b3d4-dc79-4ece-a3c1-fa70bf770c3c" /> |

---

## How to Run
1. **Prepare Assets:** Place your images inside a folder named `Foto` located in the same directory as the executable.
2. **Launch:** Run the application.
3. **Navigate:** Use the `<<`, `<`, `>`, `>>` buttons to browse the gallery.

---

© 2023 Photo Gallery Viewer | Developed by [**𝐋𝐞𝐨𝐧𝐭𝐞 𝐏𝐚𝐭𝐫𝐢𝐜𝐢𝐚-𝐌𝐢𝐫𝐚𝐛𝐞𝐥ā**](https://patrrrrrrricia.github.io/glowing-button/)
