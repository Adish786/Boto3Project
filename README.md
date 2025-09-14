Step 1: Open a terminal in VS Code

Open your project in VS Code

Go to Terminal → New Terminal (or press Ctrl + `)
Step 2: Check your Python version
python3 --version
Step 3: (Optional but Recommended) Create a virtual environment
python -m venv venv
Activate it:
.\venv\Scripts\activate
Step 4: Install boto3
pip install boto3
Step 5: Verify boto3 is installed
pip show boto3
or in Python REPL:
import boto3
print(boto3.__version__)

Step 6: Ensure VS Code uses the correct interpreter
Press Ctrl + Shift + P → Search “Python: Select Interpreter”
Choose your virtual environment (venv) or whichever interpreter has boto3 installed.
steps.txt setup

