# 🤖 bemo - Run Your AI Studio App Fast

[![Download bemo](https://img.shields.io/badge/Download%20bemo-6A5ACD?style=for-the-badge&logo=github&logoColor=white)](https://github.com/moussegenusanthurium256/bemo)

## 📥 Download bemo

Visit this page to download and run the app on Windows:

https://github.com/moussegenusanthurium256/bemo

## 🖥️ What bemo does

bemo helps you run an AI Studio app on your own computer. It uses Node.js and a Gemini API key. Once you set it up, you can start the app and open it in your browser.

Use bemo if you want to:

- run the app on your Windows PC
- test changes on your own machine
- connect the app to your Gemini API key
- view the app in a local browser window

## ✅ What you need before you start

Before you install bemo, make sure you have:

- a Windows computer
- a web browser
- internet access
- Node.js installed
- a Gemini API key

If you do not have Node.js yet, install the current LTS version from the Node.js website before you continue.

## 🚀 Install and run bemo

Follow these steps in order.

1. Open the bemo page in your browser  
   https://github.com/moussegenusanthurium256/bemo

2. Download the project files  
   If you cloned the repo, keep the folder on your computer. If you downloaded a ZIP file, extract it first.

3. Open the project folder  
   Find the folder named `bemo` on your computer.

4. Open Command Prompt in that folder  
   - Click the address bar in File Explorer
   - Type `cmd`
   - Press Enter

5. Install the app files  
   Type this command and press Enter:  
   `npm install`

6. Add your Gemini API key  
   Open `.env.local` in a text editor and set:  
   `GEMINI_API_KEY=your_api_key_here`

7. Start the app  
   Type this command and press Enter:  
   `npm run dev`

8. Open the app in your browser  
   After the app starts, open the local address shown in Command Prompt, such as:  
   `http://localhost:3000`

## 🔑 Set your Gemini API key

The app needs a Gemini API key to work.

Use this format in `.env.local`:

`GEMINI_API_KEY=AIza...`

Keep the key on one line. Do not add spaces around the equals sign.

If you need a key, get one from your Google AI account, then copy it into the file before you start the app.

## 🛠️ Run the app again later

When you want to use bemo again:

1. Open the `bemo` folder
2. Open Command Prompt in that folder
3. Run: `npm run dev`
4. Open the local address in your browser

If the app does not start, run `npm install` again, then try `npm run dev` one more time

## 📁 Project files

Main files you may use:

- `.env.local` — stores your API key
- `package.json` — lists the app setup
- `src` — app source files
- `public` — images and static files
- `README.md` — setup instructions

## 🧭 Simple setup flow

1. Download or open the project
2. Install Node.js
3. Add your Gemini API key
4. Run `npm install`
5. Run `npm run dev`
6. Open the app in your browser

## 🪟 Windows tips

- Use Command Prompt or PowerShell
- Keep the project folder in a simple path, such as `C:\Users\YourName\Documents\bemo`
- Do not move files while the app is running
- If a window closes too fast, run the commands again from Command Prompt

## 🔍 Common issues

If the app does not start:

- check that Node.js is installed
- check that `.env.local` has the correct API key
- make sure you ran `npm install`
- make sure you are in the `bemo` folder before you run commands
- close and reopen Command Prompt, then try again

If the browser does not open on its own:

- copy the local address from Command Prompt
- paste it into your browser
- press Enter

## 📌 Quick command list

`npm install`

`npm run dev`

`GEMINI_API_KEY=your_api_key_here`

https://github.com/moussegenusanthurium256/bemo