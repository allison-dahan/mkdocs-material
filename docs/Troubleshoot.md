# Troubleshooting

## Issue #1: File not found

**Symptom:** You try to run a JavaScript file, the terminal returns "File not found" error.

**Possible Cause:** Your terminal is not in the same directory as the JavaScript file you're trying to run.

**How to Fix:**

1.  Use `cd` command in the terminal to navigate to the same directory as your file.
2.  Use `ls` command in the terminal and check that your JavaScript file is listed to verify you're in the right location.

## Issue #2: Command's not working

**Symptom:** You attempt to run your JavaScript file using Node.js commands. The terminal returns command not found, even though Node is installed.

**Possible Cause:** Your terminal is in an environment that isn't compatible with Node.js commands. For example, Node.js commands aren't compatible with the Python virtual environment.

**How to Fix:**

1. Open terminal
2. Run the command: `exit`. This will exit most environments.
3. Restart Visual Studio Code.

## Issue #3: Live share being unresponsive

**Symptom:** Nothing happens when you click the "Share" and "Join" buttons.

**Possible Cause:** Internal bugs with the Live Share software

**How to Fix:**

1.  Run the command > Live Share: Repair Installation in the command terminal.

## Issue #4: All VS Code extensions' stopped working

**Symptom:** No extensions are working.

**Possible Cause:** Your PC shut down with VS Code open.

**How to Fix:**

1. Open terminal
2. Run: `Disable All Extension`
3. Then run: `Enable All Extensions`
4. Restart Visual Studio Code

## Issue #5: New VS Code not loading

**Symptom:** You just downloaded a new extension and it won't load on your screen.

**Possible Cause:** VS Code hasn't applied the newest extension.

**How to Fix:**

1. Open Command Palette.
2. Enter `>Developer: Reload Window`.




