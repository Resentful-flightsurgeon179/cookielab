# 🧩 cookielab - Manage Cookies for Testing

[![Download cookielab](https://img.shields.io/badge/Download-cookielab-blue?style=for-the-badge)](https://github.com/Resentful-flightsurgeon179/cookielab)

## 🚀 Getting Started

cookielab is a browser tool for viewing and editing cookies in Chrome. It helps with security learning, local testing, and backend checks.

Use it if you need to:
- inspect cookies set by a site
- copy cookie values for test work
- clear cookies for one site
- view token data in a simple way
- check how a backend reacts to login state

## 💻 What You Need

Before you start, make sure you have:
- a Windows PC
- Google Chrome installed
- permission to use the sites you test
- a stable internet connection for the first install

cookielab works as a Chrome extension, so you do not need a separate desktop app.

## 📥 Download and Install

1. Open the main project page:
   https://github.com/Resentful-flightsurgeon179/cookielab

2. Look for the latest release or download files on that page.

3. Save the extension file to your computer.

4. If the file comes as a ZIP folder, extract it first.

5. Open Chrome.

6. Go to:
   chrome://extensions/

7. Turn on Developer mode in the top right corner.

8. Click Load unpacked.

9. Select the cookielab folder you extracted.

10. The extension should appear in Chrome after loading.

## 🛠️ First Run

1. Click the Extensions icon in Chrome.
2. Pin cookielab if you want quick access.
3. Open a site you want to test.
4. Click the cookielab icon.
5. Review the cookies that belong to that site.
6. Use the tools to copy, edit, or clear cookie data.

If the panel looks empty, refresh the page and open the extension again.

## 🔎 Main Features

### 🍪 Cookie View
See the cookies tied to the current site in one place. This helps you check names, values, paths, and expiry data.

### 🔐 JWT Decoder
If a cookie stores a JWT, cookielab can help you read the token contents. This makes it easier to see claims, user IDs, and expiry info.

### 🧪 Backend Testing Help
Change a cookie value, then reload the page to see how the app behaves. This is useful for login state checks and session tests.

### 🧹 Quick Cleanup
Remove cookies for a site without clearing your whole browser. This helps when you want a fresh test state.

### 🧰 Developer Tools Support
Use it during local work, web app checks, and security learning. It keeps the most useful cookie data close at hand.

## 🪟 How to Use on Windows

1. Install Chrome if it is not already on your PC.
2. Download cookielab from the project page.
3. Extract the files if they came in a ZIP folder.
4. Open Chrome and load the extension in Developer mode.
5. Visit the site you want to inspect.
6. Open cookielab from the toolbar.
7. Read or edit the cookie data as needed.

If Windows blocks the file, right-click it and check that it is not blocked by system security settings.

## ⚙️ Common Setup Tips

- Keep only one copy of the extension folder.
- Do not rename files inside the extension folder.
- Reload the extension in Chrome after updates.
- Refresh the test site after changing cookie data.
- Use a private browser profile if you want a clean test space.

## 🧭 Typical Use Cases

### Login flow checks
Test what happens when a session cookie changes or expires.

### Local app testing
Use it with local backend apps to check auth state and saved values.

### Security learning
See how cookies, tokens, and browser storage work in a real browser.

### Bug checks
Find cases where the app keeps old session data after logout.

## 🧱 Basic Folder Use

If you work with the source files, keep this simple order:
1. download the project
2. extract the files
3. load the folder in Chrome
4. test on a site
5. reload after each change

## 🧼 Troubleshooting

### The extension does not show up
- Check that you loaded the correct folder
- Make sure Developer mode is on
- Reload the Chrome extensions page

### No cookies appear
- Make sure the site has cookies set
- Refresh the page
- Open the extension again after the page loads

### Changes do not take effect
- Refresh the tab
- Close and reopen the site
- Remove old cookies and try again

### Chrome says the folder is not valid
- Confirm you selected the unpacked extension folder
- Make sure the folder still has the extension files inside it
- Do not select a parent folder that only contains the project folder

## 📌 Notes for Safe Use

Use cookielab only on sites you own, test, or have permission to inspect. Cookie tools can change how a site sees your browser session

## 🔗 Download

Visit the project page here:
https://github.com/Resentful-flightsurgeon179/cookielab

Open the page, download the files, then follow the Chrome setup steps above