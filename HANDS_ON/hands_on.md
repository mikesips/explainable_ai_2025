# 🎯 VISA System - Getting Started
The **VISA** system (Visual analytics app for exploring machine learning classifications) is a XAI system built using Streamlit. It enables users to interactively explore and visualize the data, classification errors and the importance of features for the classification result. This guide will walk you through the steps to run the application locally.

## 🔧 Prerequisites
> 💡 **Note:** The VISA system runs in a web browser.  
> Make sure you have a modern browser (such as **Google Chrome**, **Mozilla Firefox**, or **Microsoft Edge**) installed on your system.

## 🚀 Running VISA
You start the application using Streamlit.

```sh
# Linux/macOS

# Navigate into the visa directory
cd HANDS_ON/visa/

# Start VISA by running the following command
streamlit run visa.py 
```
After running the command, Streamlit will start the web server and open the VISA application in your default web browser. If it doesn't open automatically, you can manually navigate to: http://localhost:8501 in your default web browser.

⚠️ Troubleshooting
Streamlit not installed: If you see an error saying that Streamlit is not installed, ensure that you installed the dependencies. Go to [Installation Instruction](./../SETUP/local-install-instructions.md)

Port already in use: If the default port 8501 is already in use, you can specify a different port by running:

```sh
# Linux/macOS

# Specify a different port by running:
streamlit run app.py --server.port <port-number>
```
