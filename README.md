# C-IDE-Project

<!-- README.md -->

<img width="844" height="571" alt="Screenshot 2025-11-06 at 7 14 47 AM" src="https://github.com/user-attachments/assets/7b1b2293-19a0-4d7c-a5df-40b1ff640711" />


# 🚀 AI CodeSandbox (C++)

**C++ Execution Environment for the NYCTA Developer Community**

This project is a **single-file**, **zero-backend**, **web-based Integrated Development Environment (IDE)** designed specifically for testing and executing **C++ code** using a **Generative AI model** as the virtual compiler and runtime environment.

Developed by **Sahil (NYCTA Developer Community)** for quick testing, sharing, and demonstration of C++ concepts without needing a local compiler setup.

---

## ✨ Key Features

- **Single-File Simplicity:**  
  The entire application (HTML, CSS, and JavaScript) is contained within one file, making deployment and sharing trivial.

- **Sleek Dark Theme:**  
  Features a modern, high-contrast dark mode using Tailwind CSS for a professional coding experience.

- **AI-Powered Execution:**  
  Leverages the Gemini API to remotely compile and execute C++ code, returning the standard output (stdout) or detailed compilation/runtime errors directly to the console.

- **Responsive Layout:**  
  The interface adapts gracefully from large desktop screens down to mobile devices.

- **Zero Local Dependencies:**  
  Requires no installation of Node.js, Python, or a C++ compiler on the user's local machine.

---

## 🛠️ Technology Stack

| **Component**      | **Technology**        | **Role**                                                                 |
|--------------------|----------------------|--------------------------------------------------------------------------|
| **User Interface** | HTML5, Tailwind CSS  | Structure and presentation, providing a responsive and modern dark theme. |
| **Client Logic**   | JavaScript (ES6)     | Handles all front-end interactivity, form management, and request/response cycle. |
| **Execution Engine** | Gemini API (via fetch) | Acts as the dedicated, remote C++ compiler and runtime, returning results or errors. |

---

## 🏃 How to Run Locally

Since this application uses the **fetch API** to communicate with the execution service, it must be run from a **local web server** to bypass browser security restrictions (CORS).

### Steps

1. **Save the File:**  
   Save the provided `index.html` file into an empty folder.

2. **Start a Local Server (Recommended):**
   - Open your terminal or command prompt.  
   - Navigate to the folder containing `index.html`.  
   - If you have Python 3 installed, run:
     ```bash
     python -m http.server
     ```

3. **Access the IDE:**  
   Open your web browser and navigate to:  
   👉 [http://localhost:8000/](http://localhost:8000/) *(or the port displayed in your terminal)*  

You can now **write and execute C++ code immediately** with no additional setup!

---

> 🧠 *"AI CodeSandbox (C++) is built to empower developers to learn, test, and innovate — all in the browser."*
