# Media Calculator

## 💻 Overview
A precise academic tool designed to streamline the calculation of grade point averages. Built with **C# Windows Forms**, this application performs real-time parsing and statistical analysis of input grades. It ensures data integrity through strict input validation, providing an efficient experience for students and educators alike.

---

## 🤍 Tech Stack
* **Language:** C#
* **Framework:** .NET Framework / Windows Forms (WinForms)
* **Core Concepts:** String Parsing, Algorithmic Validation, Real-time Event Handling

![C#](https://img.shields.io/badge/C%23-Language-%23FF69B4.svg?style=for-the-badge&logo=csharp&logoColor=white) ![.NET](https://img.shields.io/badge/.NET-WinForms-%23FF69B4.svg?style=for-the-badge&logo=dotnet&logoColor=white)

![Data Processing](https://img.shields.io/badge/Data-Processing-%234F4F4F.svg?style=for-the-badge) ![Logic](https://img.shields.io/badge/Algorithm-Validation-%23333333.svg?style=for-the-badge)

---

## 🎀 Core Functionality
* **Real-time Processing:** Automatically calculates the average as the user inputs grades, thanks to the `TextChanged` event trigger.
* **Intelligent Validation:** * **Character Filtering:** Rejects non-numeric input to maintain data accuracy.
    * **Grade Logic:** Implements specific rules to recognize "10" correctly while preventing erroneous grade entries.
* **Precision Math:** Computes the arithmetic mean with controlled rounding, ensuring the result is formatted to three decimal places.
* **Error Handling:** Provides immediate feedback via message boxes for invalid data entry, ensuring a robust user experience.

---

## 📂 Project Structure
* **`Form1.cs`**: Contains the core UI interaction logic and event listeners.
* **`textBoxNote_TextChanged`**: The primary event handler that triggers validation and calculation whenever data is updated.
* **`EvalMedia()`**: The core algorithmic method responsible for parsing the grade sequence and calculating the statistical mean.
* **`buttonIesire_Click`**: Dedicated control for application termination.

---

## Visual Demonstration
| Input Field | Calculated Result |
| :---: | :---: |
| <img width="1013" height="644" alt="image" src="https://github.com/user-attachments/assets/bea0dfbe-8bb5-4a15-a087-9ff11062b780" /> | <img width="1018" height="643" alt="image" src="https://github.com/user-attachments/assets/e9a5482f-1002-4feb-a52c-e279f59f4061" /> |

---

## How to Run
1. **Launch:** Run the compiled application.
2. **Input:** Type the grades sequentially in the text box (e.g., `10910` for a 10, a 9, and a 10).
3. **Analyze:** View the calculated average instantly reflected on the screen.

---

© 2023 Media la Info | Developed by [**𝐋𝐞𝐨𝐧𝐭𝐞 𝐏𝐚𝐭𝐫𝐢𝐜𝐢𝐚-𝐌𝐢𝐫𝐚𝐛𝐞𝐥a**](https://patrrrrrrricia.github.io/glowing-button/)
