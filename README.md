# 🚀 Python Setup Guide for VS Code

If you're setting up **Python in VS Code** for the first time or facing issues with `input()` not working, follow this **step-by-step** guide to ensure a smooth experience.

---

## ✅ 1. Install Python & VS Code

🔹 Download and install **Python** from: [python.org](https://www.python.org/downloads/)
🔹 Download and install **VS Code** from: [code.visualstudio.com](https://code.visualstudio.com/)

🛑 **During Python installation, check the box** ✅ **"Add Python to PATH"** to avoid manual setup.

---

## ✅ 2. Set Up Python in Environment Variables (If Needed)

If Python isn't recognized in Command Prompt (`cmd`), set it up manually:

1. Open **Start Menu** → Search **"Environment Variables"**
2. Click **"Edit the system environment variables"**
3. In **System Properties**, click **"Environment Variables"**
4. Under **System Variables**, find **Path** → Click **Edit**
5. Click **New** → Add these two paths:
   ```
   C:\Users\YourUsername\AppData\Local\Programs\Python\PythonXX\
   C:\Users\YourUsername\AppData\Local\Programs\Python\PythonXX\Scripts\
   ```
6. Click **OK** → Restart your PC

---

## ✅ 3. Verify Python Installation

Open **Command Prompt (****`cmd`****)** and type:

```sh
python --version
```

✅ If Python is installed correctly, you’ll see something like:

```
Python 3.X.X
```

---

## ✅ 4. Set Up Python in VS Code

🔹 Open **VS Code**\
🔹 Press **`Ctrl + Shift + P`** → Search **"Python: Select Interpreter"**\
🔹 Select the **latest installed version** of Python

---

## ✅ 5. Create & Run a Python Script in VS Code

1. Open **VS Code**
2. Create a new file: **`script.py`**
3. Add this code:
   ```python
   print("Hello, World!")
   name = input("Enter your name: ")
   print("Hello,", name)
   ```
4. **Run the script** by clicking the **▶ Run button**

---

## ✅ 6. Fix Input Issues (`input()` Not Working in VS Code)

📌 **Problem:** If input doesn’t work in the **Output** section, do this:

🔹 Open **VS Code Settings (****`Ctrl + ,`****)**\
🔹 Search for **"Code-runner: Run In Terminal"**\
🔹 ✅ **Enable it** (check the box)\
🔹 Restart VS Code

Now, your Python scripts will always run in the **Terminal**, where input works properly.

---

## ✅ 7. Running Python in Terminal & Command Prompt

🔹 **In Command Prompt (****`cmd`****):**

```sh
python "C:\path\to\your\script.py"
```

🔹 **In VS Code Terminal (****`Ctrl + ~`****):**

```sh
python script.py
```

---

## 🎯 Final Summary (Quick Steps)

1️⃣ Install **Python** and **VS Code**\
2️⃣ Add Python to **Environment Variables (PATH)** (if needed)\
3️⃣ Select **the correct Python interpreter in VS Code**\
4️⃣ Run Python code in **Terminal (****`Ctrl + ~`****)** (not in Output)\
5️⃣ **Enable "Run In Terminal" in VS Code settings**\
6️⃣ Test Python in **Command Prompt & VS Code Terminal**

💡 **Now, Python is fully set up in VS Code with all issues fixed!** 🚀

PS:
## ❗ Common Errors & Fixes
- `'python' is not recognized as an internal or external command` → Add Python to PATH
- `input() not working` → Make sure "Run in Terminal" is enabled in Code Runner

