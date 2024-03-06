# FT-08-Reading-Python-Error-Message
Python Error Debugging Practice
This project contains Python code and tests that are meant to trigger errors. The goal is to practice debugging skills by systematically fixing test failures.

Getting Started
Clone this repository.

Install pytest: pip install pytest

Open the project folder in VS Code.

Running Tests
Open a terminal in VS Code (Terminal > New Terminal).

Run pytest -x to execute the first test.

View any errors/failures in the terminal output. VS Code may also underline issues.

Debugging Failures
Open the file pointed to in the stack trace and navigate to the failing line.

Analyze the code to understand the cause of failure.

Make necessary fixes to resolve the error.

Save the file and rerun pytest -x to check if the test passes.

Repeat steps 3-4 until all errors are fixed.

Committing Changes
Once all tests pass, stage changes with git add .

Commit with git commit -m "Fix test failures"

Push to remote with git push

Tips
Errors will be underlined in the editor
Navigate between tests and code easily
Use debugging tools as needed
Fix failures one by one systematically