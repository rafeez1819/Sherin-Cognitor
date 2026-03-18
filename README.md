# Sherin-Cognitor

#1. Repository Structure
<img width="902" height="857" alt="image" src="https://github.com/user-attachments/assets/dbbf1240-2711-403a-94a8-8a163ef13da6" />
<img width="900" height="386" alt="image" src="https://github.com/user-attachments/assets/5b249220-272f-40ab-a935-a4178295e287" />


#README>MD
```
# <img src="assets/images/logo.png" alt="Sherin Cognitor Logo" width="40"/> Sherin Cognitor

**Autonomous AI Agent for Human-Like Interaction**

[![Version](https://img.shields.io/badge/version-1.0.0-blue)](https://github.com/yourusername/Sherin-Cognitor/releases)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)
[![Build Status](https://github.com/yourusername/Sherin-Cognitor/actions/workflows/python-app.yml/badge.svg)](https://github.com/yourusername/Sherin-Cognitor/actions)
[![Python](https://img.shields.io/badge/python-3.8+-brightgreen)](https://www.python.org/downloads/)
[![Dependencies](https://img.shields.io/badge/dependencies-up%20to%20date-brightgreen)](requirements.txt)

---

## **🌟 Features**

| Feature                     | Description                                                                 |
|-----------------------------|-----------------------------------------------------------------------------|
| **Voice Commands**          | Control the agent with natural voice commands.                              |
| **Screen Reading**          | Read and interpret screen content using OCR.                                |
| **Human-Like Typing**       | Type and interact with documents like a human.                              |
| **Custom Cursor Overlay**   | Visual feedback with a custom cursor (circle for user, dot for agent).      |
| **Real-Time Action Display**| See what the agent is doing in real-time.                                   |
| **Chat Interface**          | Communicate with the agent via a web-based chat interface.                  |
| **Transparency & Logging**  | All actions are logged and visible to the user.                             |

---

## **📊 Architecture Overview**

### **System Architecture**
![Architecture Diagram](assets/diagrams/architecture.png)

### **Workflow**
![Workflow Diagram](assets/diagrams/workflow.png)

### **Data Flow**
![Data Flow Diagram](assets/diagrams/data_flow.png)

---

## **🚀 Getting Started**

### **Prerequisites**
- Python 3.8+
- Pip
- Tesseract OCR (for screen reading)

### **Installation**

#### **1. Clone the Repository**
```bash
git clone https://github.com/yourusername/Sherin-Cognitor.git
cd Sherin-Cognitor
```

2. Install Dependencies
Windows:
start.bat
Linux/macOS:
chmod +x start.sh
./start.sh
3. Configure Environment Variables
Copy .env.example to .env and update the values:

MODEL_NAME=llama3
LOG_LEVEL=INFO
STT_ENGINE=whisper
TTS_ENGINE=pyttsx3
🎬 Demo
Voice Command
[Image blocked: Voice Command Demo]

Screen Reading
[Image blocked: Screen Reading Demo]

Document Creation
[Image blocked: Document Creation Demo]

Cursor Overlay
[Image blocked: Cursor Overlay Demo]

🛠️ Usage
Start the Agent
python src/scripts/start_agent.py
Voice Commands
"Open Notepad"
"Type Hello World"
"Click the OK button"
"Read the screen"
Chat Interface
Access the chat interface at http://localhost:5000.

<img width="939" height="443" alt="image" src="https://github.com/user-attachments/assets/7b8e89d5-c521-4d2b-8d90-e86b7d722d83" />

🤝 Contributing
Contributions are welcome! Please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Commit your changes (git commit -m "Add new feature").
Push to the branch (git push origin feature-branch).
Open a Pull Request.
📜 License
This project is licensed under the MIT License. See the LICENSE [blocked] file for details.

📧 Contact
For questions or support, contact: your.email@example.com

Happy Coding! 🚀


---

## **3. Visual Assets**

### **Logo and Banner**
- **Logo**: A modern, minimalist logo for Sherin Cognitor (e.g., a brain with a cursor).
- **Banner**: A visually appealing banner for the repository header.

### **Diagrams**
- **Architecture Diagram**: Visualize the system architecture.
- **Workflow Diagram**: Show the agent's workflow.
- **Data Flow Diagram**: Illustrate how data flows through the system.

### **Animated GIFs**
- **Voice Command**: Show the agent responding to voice commands.
- **Screen Reading**: Demonstrate OCR in action.
- **Document Creation**: Show the agent typing and creating documents.
- **Cursor Overlay**: Highlight the custom cursor overlay.

### **Screenshots**
- **Main Window**: Screenshot of the main UI.
- **Chat Interface**: Screenshot of the chat interface.

---

## **4. GitHub Actions Workflow**

### **`.github/workflows/python-app.yml`**
```yaml
name: Python Application

on: [push, pull_request]

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
    - uses: actions/checkout@v2
    - name: Set up Python
      uses: actions/setup-python@v2
      with:
        python-version: '3.8'
    - name: Install dependencies
      run: |
        python -m pip install --upgrade pip
        pip install -r requirements.txt
    - name: Run tests
      run: |
        python -m unittest discover src/tests
5. Documentation
docs/installation.md
Step-by-step visual guide for installation.
Screenshots for each step.
docs/usage.md
Guide on how to use the agent with screenshots.
docs/architecture.md
Detailed architecture overview with diagrams.
6. Branding
Color Palette
Use a modern color scheme (e.g., dark blue, teal, and white).
Typography
Use a clean, readable font (e.g., Roboto or Open Sans).
7. Live Demo Section
Add a live demo section to your README.md with screenshots or a video walkthrough.

## **🎥 Live Demo**

Watch a video walkthrough of Sherin Cognitor in action:

[![Sherin Cognitor Demo](https://img.youtube.com/vi/YOUR_VIDEO_ID/0.jpg)](https://www.youtube.com/watch?v=YOUR_VIDEO_ID)
