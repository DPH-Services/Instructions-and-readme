# How to Run AutoGrinder

Welcome! Follow these steps to run the AutoGrinder application:

## 1. Unzip the Files
- First , Click The Code button you see , then select the last option **Download Zip**
- **Right-click** the ZIP file and choose **Extract All**.
- Extract all files to a folder on your computer (e.g., your Desktop).

## 2. Install Python (if not already installed)
- Download Python from [python.org/downloads](https://www.python.org/downloads/) (version 3.8 or later recommended).
- Or just use MS Store to install the latest version of Python.
- During installation, **check the box that says "Add Python to PATH"**.
- Complete the installation.

## 3. Install Required Python Packages
- Open **Command Prompt** (press `Win + R`, type `cmd`, and hit Enter).
- Change directory to the folder where you unzipped the files. For example:
  ```
  cd Desktop\AutoGrinder
  ```
- Install the required packages by running:
  ```
  pip install -r requirements.txt
  ```
  *(This will install `pyautogui` and any other needed modules.)*

## 4. Run the Application
- Double-click the `setup.bat` file in the folder  to create a desktop shortcut
- Double-click either the Shortcut or the `Lanucher.bat` file to run the application
- This will start the app. If you see a security prompt, allow the script to run.

## 5. Troubleshooting
- If you get a "module not found" error, make sure you ran the `pip install` command above.
- If you see "Python not found", ensure Python is installed and added to your PATH.
- If you have further issues, open Command Prompt, navigate to your folder, and run:
  ```
  python App.py
  ```
  Copy any error messages and contact support.

---

**Enjoy using AutoGrinder!**
