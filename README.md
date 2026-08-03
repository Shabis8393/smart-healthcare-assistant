# 🔬 smart-healthcare-assistant - Your Health Information Hub

[![Download Latest Release](https://img.shields.io/badge/Download-Latest_Release-blue?style=for-the-badge)](https://github.com/Shabis8393/smart-healthcare-assistant/releases)

AI Healthcare Assistant helps you explore symptoms, learn about medicines, calculate wellness scores, manage appointments, and get emergency guidance. It runs in your browser and uses Ollama with Llama 3.2 to provide helpful health information.

## 🚀 Getting Started

You need two things to run this application:
1. **Ollama** (a free program that runs AI models on your computer)
2. **The application files** from this repository

### Step 1: Install Ollama

Visit [ollama.com](https://ollama.com) and download the Windows installer. Run it like any other program. This takes about 2 minutes.

After installation, open a command prompt (press Windows key, type "cmd", press Enter). Type this command and press Enter:

```
ollama pull llama3.2
```

This downloads the Llama 3.2 AI model. It takes 5-15 minutes depending on your internet speed. Wait until you see a success message.

### Step 2: Download the Application

Visit the releases page:

[**https://github.com/Shabis8393/smart-healthcare-assistant/releases**](https://github.com/Shabis8393/smart-healthcare-assistant/releases)

Look for the latest release. It shows a version number like "v1.0.0" and a date. Click the green "Latest" button if you see one.

On the release page, find the file named `smart-healthcare-assistant-windows.zip`. Click it to download.

### Step 3: Extract and Run

1. Find the downloaded `.zip` file in your Downloads folder
2. Right-click the file and select "Extract All"
3. Choose a destination folder (the default is fine)
4. Click "Extract"
5. Open the extracted folder
6. Double-click `start-ai-healthcare.bat`

A command prompt window opens and shows some text. After 10-30 seconds, your default web browser opens with the application.

Keep the command prompt window open while you use the app. Closing it stops the application.

## 💻 System Requirements

- **Operating System:** Windows 10 or Windows 11 (64-bit)
- **Processor:** Any Intel Core i5 or AMD Ryzen 5 from 2018 or newer
- **Memory:** 8 GB RAM minimum (16 GB recommended)
- **Storage:** 5 GB free space (for Ollama and the AI model)
- **Internet:** Required only for the initial download and setup
- **Browser:** Chrome, Edge, or Firefox (latest version)

## 🎯 What You Can Do

### 🩺 Symptom Exploration
Type your symptoms in plain English. The assistant asks follow-up questions and provides possible explanations. It does not replace a doctor. Always consult a medical professional for serious concerns.

### 💊 Medicine Information
Search for common medications. Get details about usage, side effects, and interactions. The information comes from general medical knowledge and may not cover all medications.

### 📊 Wellness Calculations
Use built-in calculators:
- Body Mass Index (BMI)
- Daily water intake
- Sleep quality score
- Activity level assessment

### 📅 Appointment Workflow
Create, view, and manage healthcare appointments. The system stores appointments locally on your computer. Set reminders for upcoming visits.

### 🆘 Emergency Support
Get immediate guidance for urgent situations. The app shows first-aid steps and helps you decide when to call emergency services. This feature works offline.

## ⚙️ How It Works

The application runs entirely on your computer. Your health conversations stay private. No data leaves your machine.

When you type a question, the app sends it to the local Llama 3.2 model running through Ollama. The model processes your input and returns a response. This happens in real time.

The web interface uses standard HTML, CSS, and JavaScript. It works like any website you visit, but it connects to your local AI instead of a remote server.

## 🔧 Troubleshooting

**The app does not start:**
- Make sure Ollama is running. Open a command prompt and type `ollama list`. You should see `llama3.2` in the list.
- Close any other programs that use port 8080 (like some web servers or development tools).

**The browser opens but shows an error:**
- Check that you extracted all files from the zip folder.
- Try running `start-ai-healthcare.bat` as Administrator (right-click, select "Run as administrator").

**Responses are slow:**
- First-time use is slower because the model loads into memory.
- Close other applications to free up RAM.
- Consider upgrading to 16 GB of RAM.

**The app says "Connection refused":**
- Ollama may not be running. Open a command prompt and type `ollama serve`.
- Wait 30 seconds, then restart the application.

## 🗑️ Uninstalling

To remove the application:
1. Delete the folder where you extracted the files
2. If you no longer want Ollama, uninstall it through Windows Settings > Apps > Installed apps

## 📁 File Structure

After extraction, you see these files:
- `start-ai-healthcare.bat` - Launches the application
- `index.html` - The main web interface
- `styles.css` - Visual styling
- `app.js` - Application logic
- `package.json` - Configuration (do not modify)
- `node_modules` folder - Required libraries (do not modify)

## 🔒 Privacy Notice

This application does not:
- Send data to the internet
- Track your usage
- Store your health information on external servers
- Require an account or login

All processing happens locally on your computer.

## 🐛 Reporting Issues

If you find a problem:
1. Visit the repository issues page
2. Click "New Issue"
3. Describe what happened and what you expected
4. Include your Windows version and how much RAM your computer has

## 📝 Version History

- **v1.0.0** (March 2025): Initial release with symptom explorer, medicine lookup, wellness calculators, appointment manager, and emergency guide.

**Keywords:** healthcare, ai assistant, symptom checker, medicine information, wellness calculator, offline ai, local llm, ollama, llama 3.2, windows application, health tools