# Interactive Image Switcher

## 💻 Overview
A lightweight C# Windows Forms application that brings static UI elements to life. This project implements an **event-driven interactive interface** where a button dynamically toggles between distinct floral compositions based on mouse focus. It serves as a study in real-time GUI manipulation and event handling.

---

## 🤍 Tech Stack
* **Language:** C#
* **Framework:** .NET Framework / Windows Forms (WinForms)
* **Core Concepts:** Event-Driven Programming, Mouse Hover Logic, Image Streaming

![C#](https://img.shields.io/badge/C%23-Language-%23FF69B4.svg?style=for-the-badge&logo=csharp&logoColor=white) ![.NET](https://img.shields.io/badge/.NET-WinForms-%23FF69B4.svg?style=for-the-badge&logo=dotnet&logoColor=white)

![UI/UX](https://img.shields.io/badge/UI-Interactive-%234F4F4F.svg?style=for-the-badge) ![Event-Driven](https://img.shields.io/badge/Event-Driven-%23333333.svg?style=for-the-badge)

---

## 🎀 Core Functionality
* **Dynamic Hover Effects:** Utilizes `MouseEnter` and `MouseLeave` event triggers to swap background imagery in real-time.
* **Layout Optimization:** Implements `ImageLayout.Stretch` to ensure high-fidelity image rendering within the button's bounds, regardless of aspect ratio.
* **Intuitive Navigation:** Features an integrated "Exit" control for seamless application termination.
* **Responsive State:** Immediate visual feedback upon user interaction, creating a polished, engaging user experience.

---

## 📂 Project Structure
* **`Form1.cs`**: Orchestrates the UI logic and mouse event handlers.
* **`ButtonImagine_MouseEnter`**: Triggers the transition to image `1.jpg` when the cursor enters the button area.
* **`ButtonImagine_MouseLeave`**: Reverts the display to image `2.jpg` upon mouse exit.
* **`ButtonIesire_Click`**: Dedicated utility for terminating the process safely.

---

## Visual Demonstration
| Idle State | Hover State |
| :---: | :---: |
| <img width="791" height="918" alt="image" src="https://github.com/user-attachments/assets/d05b7937-2331-499d-a53c-e3aaaa4539a0" /> | <img width="787" height="918" alt="image" src="https://github.com/user-attachments/assets/225aeb3b-3b13-4ba0-832b-9f6c83f26eee" />|

---

## How to Run
1. **Prepare:** Ensure the executable is in the same folder as `1.jpg` and `2.jpg`.
2. **Launch:** Run the compiled application.
3. **Interact:** Simply move your mouse over the floral button to witness the visual transformation.

---

© 2023 Interactive Switcher | Developed by [**𝐋𝐞𝐨𝐧𝐭𝐞 𝐏𝐚𝐭𝐫𝐢𝐜𝐢𝐚-𝐌𝐢𝐫𝐚𝐛𝐞𝐥𝐚**](https://patrrrrrrricia.github.io/glowing-button/)
