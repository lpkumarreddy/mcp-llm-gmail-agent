# 📬 Project 1: Gmail AI Agent Integration with Cursor IDE

This project demonstrates how to integrate **Cursor AI Editor** with **Gmail** using **MCP servers via Pipedream**, enabling AI-driven workflows to send, retrieve, and manage emails through natural language commands inside your IDE.

---

## 🧰 Prerequisites

* ✅ [Pipedream Account](https://pipedream.com/)
* ✅ Authenticated Gmail Account
* ✅ Cursor AI Editor installed on:

  * Windows
  * macOS
  * Ubuntu 24.04
* ✅ Basic familiarity with using an IDE

---

## 🚀 Installation & Setup

### 1. Install Cursor AI Editor

* **Windows**: [Download Cursor for Windows](https://www.cursor.so/)
* **macOS**: [Installation Steps for macOS](https://www.cursor.so/)
* **Ubuntu 24.04**: [Installation Steps for Ubuntu](https://www.cursor.so/)

🎥 [Watch Installation Tutorial (YouTube)](https://www.youtube.com/)

> Sign in to Cursor using your **Gmail** or **GitHub** account.

---

## ⚙️ Cursor IDE Configuration

1. Launch **Cursor IDE**
2. On Welcome Screen:

   * Click **Skip**
   * Continue through all setup screens
3. Click the **⚙️ Settings** icon (top-right)
4. Navigate to **Tools & Integrations**
5. Click **Add Custom MCP**

---

## 🌐 Adding MCP Servers (via Pipedream)

### Step 1: Get Your Gmail MCP Server URL

* Go to [Pipedream](https://pipedream.com/)
* Sign in / Sign up
* Search and connect the **Gmail** integration
* Switch to the **Cursor** tab
* Copy your **Gmail-specific MCP URL**

> ⚠️ **Never share this URL** – it contains sensitive authentication tokens.

### Step 2: Add MCP to Cursor IDE

* Open **Cursor Settings → Tools & Integrations**
* Paste the copied **MCP configuration URL**
* Save (Ctrl + S)

---

## 🤖 Running Gmail Workflows in Cursor

### Step 1: Open AI Panel

* Click **New Chat** (top-right), or use shortcut `Ctrl + Alt + B`

### Step 2: Use AI Prompts

Examples:

* `"Send an email to my team using Gmail summarizing today's meeting notes."`
* `"Get my details from LinkedIn, apply for a job at {company name}, write a short cover letter, and send everything to {email address}."`

### Step 3: Confirm Results

* Check your Gmail **Sent folder**
* Monitor logs in **Cursor IDE** for success or errors

---

## 🧪 More Example Prompts

* 📥 **Fetch Emails**: `Get the last 5 emails from my Gmail inbox and display them here.`
* 🗓️ **Schedule Event**: `Schedule a calendar event for tomorrow at 3 PM using Google Calendar.`
* 🧑‍💻 **Push to GitHub**: `Push the current code to my GitHub repository with the commit message "MCP Integration Done".`

---

## 🔐 Security & Notes

* **Security**: Never share your **MCP URL** with anyone.
* **Error Handling**: Check logs in **Pipedream** or **Cursor IDE**.
* **Extend Functionality**: To connect other tools like YouTube or Calendar, repeat the **MCP setup** steps.

---

## 📄 License

This project is licensed under the **MIT License**.

```
MIT License

Copyright (c) 2025 lpkumarreddy

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is furnished
to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 🙌 Acknowledgements

Special thanks to the **Cursor AI** and **Pipedream** communities for building such powerful integration tools that simplify complex AI workflows.


