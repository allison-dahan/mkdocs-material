# Troubleshooting 

## Issue #1: File Not Found

**Symptom:** You try to run a JavaScript file, the terminal returns "File not found" error.

**Possible Cause:** Your terminal is not in the same directory as the JavaScript file you're trying to run.

**How to Fix:**
1.  Use `cd` command in the terminal to navigate to the same directory as your file.
2.  Use `ls` command in the terminal and check that your JavaScript file is listed to verify you're in the right location.

## Issue #2: Command's Not Working
![Checking the Environment in VSCode's Terminal](assets/images/environment.png)
Fig 1. Checking the Environment in VSCode's Terminal

VSCode's terminal can use different shells (e.g., Bash, Zsh, PowerShell). Ensure you're using one compatible with the commands provided (Bash, Zsh, or PowerShell are recommended). You can switch the shell by clicking on the dropdown menu in the terminal's toolbar and selecting your preferred shell.

**Symptom:** You attempt to run your JavaScript file using Node.js commands. The terminal says "Command not found", even though Node is installed.

**Possible Cause:** Your terminal is in an environment that isn't compatible with Node.js commands. For example, Node.js commands aren't compatible with the Python virtual environment.

**How to Fix:**

1. Open Terminal
2. Run the command: `exit`. This will exit most environments.
3. Restart Visual Studio Code. 



