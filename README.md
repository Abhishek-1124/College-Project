## 2025_IITM_Winter_School_HandsOn


#### link for Progress Sheet - https://docs.google.com/spreadsheets/d/1bI2ES-S_MbXLSfbs08ovolQEzTkQHPOt_6HqEJ82mSY/edit?usp=sharing


## Install Node.js and Run Your First Program

This guide will help you:

- Install **Node.js**
- You can either follow the official installation guide at: https://nodejs.org/en/download, or use the step-by-step instructions provided later in this page.
- After installation, verify that Node.js is installed successfully.
- Finally, run your first program: **Hello, World**.
Works for both **Linux** and **macOS**.

## Recommended Learning — Brush Up JavaScript and Node.js

### JavaScript Quick Reference  
**Link:** https://quickref.me/javascript.html  

This is a fast, compact **cheat sheet** for JavaScript. It provides quick access to commonly used syntax such as variables, loops, functions, arrays, objects, operators, and built-in methods.  
It is useful when writing code and needing a reminder of how something works without reading long documentation.

---

### Codecademy — Learn Node.js Course  
**Link:** https://www.codecademy.com/learn/learn-node-js  

This is an interactive course designed for beginners who want to learn Node.js step by step. It includes hands-on exercises, guided lessons, and small projects that explain important concepts like Node modules, asynchronous programming, file handling, npm packages, and building basic servers.

---

These two resources together help you learn JavaScript quickly and then apply it in Node.js through practical exercises.

---

## Node.js Installation Manual

This manual provides step-by-step instructions to install Node.js on:

- Linux
- macOS

It also includes verification steps and optional installation using NVM (Node Version Manager).

---

### Official References

| Resource | Link |
|----------|------|
| Node.js Homepage | https://nodejs.org |
| Download Page (Installers & Binaries) | https://nodejs.org/en/download |
| Node.js Documentation | https://nodejs.org/en/learn |
| npm Documentation | https://docs.npmjs.com |

---

## Installing Node.js on Linux

### Option A: Install Using NodeSource (Recommended)

This method installs the latest stable LTS version.

1) Update System Packages:
```sh
sudo apt update && sudo apt upgrade -y
```

2) Install curl (if not installed):
```sh
sudo apt install curl -y
```

3) Add NodeSource Repository:
```sh
curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash -
```

4) Install Node.js:
```sh
sudo apt install -y nodejs
```

5) Verify Installation:
```sh
node -v
npm -v
```

---

## Installing Node.js on macOS

### Option A: Install Using Homebrew (Recommended)

1) Install Homebrew (if not installed):
```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

2) Install Node.js:
```sh
brew install node
```

3) Verify Installation:
```sh
node -v
npm -v
```

---

### ✔️ Option B: Install from Official Installer (GUI)

1. Download installer:  
   https://nodejs.org/en/download

2. Follow installation steps:
- Open the `.pkg` file
- Accept license agreement
- Install
- Close installer

3. Verify:
```sh
node -v
npm -v
```

---

## Post-Installation Test

To test that Node.js is working, run:

```sh
echo "console.log('Node.js setup successful')" > test.js
node test.js
```

Expected output:

```
Node.js setup successful
```

 Congratulations — Node.js and npm are now installed successfully!

---

---

# Write First Node.js Program — "Hello, World"

In this exercise, you will:

1. Create a folder using File Manager / Finder
2. Create a JavaScript file named `helloworld.js`
3. Run the file using Node.js from the Terminal

---

##  Create a Folder

Create a folder named:

```
helloworld
```

Then open the folder.

---

## 2️⃣ Create the JavaScript File

Inside the folder, create a file named:

```
helloworld.js
```

Add the following content:

```js
console.log("Hello, World!");
```

Save the file.

---

## Open Terminal and Navigate to the Folder

Run:

```sh
cd ~/helloworld
```

Examples:

```sh
cd /Users/<yourname>/Desktop/helloworld
```

or

```sh
cd /home/<yourname>/helloworld
```

---

##  Run the Program

Execute:

```sh
node helloworld.js
```

---

###  Expected Output

```
Hello, World!
```

 Success! You just ran your first Node.js program.

---

##  Summary

| Task | Method |
|------|--------|
| Create folder | File Explorer / Finder |
| Create file | Any text editor |
| Run program | Terminal: `node helloworld.js` |

---

 You are now ready to explore more features of Node.js!
