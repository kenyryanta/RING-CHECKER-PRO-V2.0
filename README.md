# 💍 Ring Checker Pro

[![Python Version](https://img.shields.io/badge/Python-3.x-blue.svg)](https://python.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![made-with-tkinter](https://img.shields.io/badge/Made%20with-Tkinter-red)](https://docs.python.org/3/library/tkinter.html)

**Ring Checker Pro** is an interactive Python desktop application designed to analyze algebraic structures known as *rings*. This application is especially useful for students, educators, and researchers in mathematics to validate and explore the properties of rings.


*The Ring Checker Pro interface with the Forest-dark theme.*

---

## ✨ Key Features

-   🎨 **Modern & Responsive GUI**: Comes with dark (Forest) and light (Azure) themes for visual comfort.
-   🔢 **Interactive Operation Tables**: Easily input the addition and multiplication operation tables.
-   🔬 **In-depth Property Analysis**:
    -   Associativity, Commutativity, Distributivity
    -   Unity Element & Inverses
    -   Zero Divisors
-   🏷️ **Ring Classification**: Automatically determines if the ring is a **Field**, **Integral Domain**, **Division Ring**, and more.
-   💾 **Data Management**:
    -   Save and load calculations to/from an **SQLite** database.
    -   Import and export data in **JSON** format.
-   ⚡ **Multi-threaded Analysis**: Analyzes the ring in a background thread to keep the GUI responsive.
-   📚 **Built-in Samples**: Includes sample rings like $Z_3$, Boolean Ring, and others to get you started.

---

## 🚀 Installation and Usage

Make sure you have **Python 3** installed on your system.

1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/your-username/ring-checker-pro.git](https://github.com/your-username/ring-checker-pro.git)
    cd ring-checker-pro
    ```

2.  **Install Dependencies**
    This application uses `customtkinter`, `ttkthemes`, and `sv-ttk`. Install all dependencies from the `requirements.txt` file.
    ```bash
    pip install -r requirements.txt
    ```

3.  **Run the Application**
    To run the application, execute the `final.py` script:
    ```bash
    python final.py
    ```

---

## 📖 How to Use

1.  **Launch the App**: Run the script as instructed above.
2.  **Set Ring Size**: Choose the desired ring size (e.g., 3 for a ring with 3 elements: A, B, C).
3.  **Generate Tables**: Click the **'Generate Table'** button.
4.  **Fill in the Operation Tables**: Complete the addition and multiplication tables. Ensure each entry is a valid ring element (e.g., A, B, C).
5.  **Analyze**: Click **'Analyze Ring'** to see the property analysis and ring classification in the right-hand panel.
6.  **Use Samples**: Explore the pre-built ring examples in the **'Samples'** tab.
7.  **Save & Load**: Use the `File` menu to save, load, import, or export your work.

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action                 |
| :------- | :--------------------- |
| `Ctrl+N` | New Calculation        |
| `Ctrl+S` | Save Calculation       |
| `F11`    | Toggle Fullscreen Mode |

> **📝 Important Note**
> Ensure that all cells in the operation tables are filled correctly. Each entry must be a valid, defined ring element (A, B, C, etc.). Invalid input will cause the analysis to fail.
