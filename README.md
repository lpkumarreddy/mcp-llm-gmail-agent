````markdown
# 📬 Gmail AI Agent Integration with Cursor IDE

Integrate **Cursor AI Editor** with **Gmail** and other services using **MCP servers via Pipedream**, enabling natural language-based workflows such as sending emails, retrieving inbox content, pushing to GitHub, scheduling events, and more — all from inside your IDE.

---

## 🧰 Prerequisites

- ✅ [Pipedream Account](https://pipedream.com/)
- ✅ Authenticated Gmail Account
- ✅ Cursor AI Editor installed on:
  - Windows
  - macOS
  - Ubuntu 24.04
- ✅ Basic knowledge of IDE usage

---

## 🛠️ Cursor Installation & Setup

### 1️⃣ Install Cursor AI Editor

#### 🪟 For Windows:
- [Download Cursor for Windows](https://www.cursor.so/)
- [Watch YouTube Installation Tutorial](https://www.youtube.com/)

#### 🍎 For macOS:
- [Setup Guide for macOS](https://www.cursor.so/)

#### 🐧 For Ubuntu 24.04:
- [Setup Guide for Ubuntu 24.04](https://www.cursor.so/)

> ✅ **Sign in with your Gmail or GitHub account**  
> After authentication (in a new browser tab), return to the Cursor IDE to continue.

---

## ⚙️ Initial Configuration in Cursor IDE

### Welcome & Preferences Setup

1. **Launch Cursor IDE**
2. On Welcome Screen:
   - Click **Skip**
   - Click **Continue** through each screen:
     - Theme Selection
     - Quick Start
     - Data Sharing
     - Review Settings

---

## 🌐 MCP Integration via Pipedream

### Step 1: Access Cursor Settings

- Click the **⚙️ Settings** icon in the top-right
- Go to **Tools & Integrations**
- Click **Add Custom MCP**

---

### Step 2: Get MCP Server URL from Pipedream

1. Go to [Pipedream](https://pipedream.com/)
2. **Sign in / Sign up**
3. Search for a tool (e.g., **Gmail**, **LinkedIn**, **GitHub**)
4. Click **Connect Account** and complete authentication
5. Click the **Cursor** tab from the list of clients
6. **Copy the Gmail-specific MCP configuration URL**

> ⚠️ **Do not share your Pipedream URLs** — they include private authentication tokens.

---

### Step 3: Add MCP Server in Cursor IDE

- Go back to **Cursor → Settings → Tools & Integrations**
- Paste the copied Gmail MCP configuration
- Press `Ctrl + S` to **save**

---

### ➕ Add More MCP Services (YouTube, Calendar, GitHub)

To connect additional services:

1. In the `mcpServers` object:
   - Add a new entry using this format:
```json
{
  "name": "YouTube",
  "url": "https://example.m.pipedream.net"
}
````

2. Place a comma `,` after the previous entry if needed.
3. Save changes (`Ctrl + S`).

---

## 🤖 Using MCP Workflows in Cursor IDE

### Open the AI Panel

* Click **New Chat** (top-right)
* Or press shortcut: `Ctrl + Alt + B`

---

### 💬 Example Prompts You Can Use

You can now ask Cursor AI to perform real-world tasks via your integrated MCP services:

* 📧 **Send Email via Gmail**
  `"Send an email to my team using Gmail summarizing today's meeting notes."`

* 📥 **Retrieve Emails**
  `"Get the last 5 emails from my Gmail inbox and display them here."`

* 🔁 **Translate and Email**
  `"Translate this paragraph into French and send it via email."`

* 🗓️ **Schedule Calendar Events**
  `"Schedule a calendar event for tomorrow at 3 PM using Google Calendar."`

* 🧑‍💻 **Push Code to GitHub**
  `"Push the current code to my GitHub repository with the commit message 'MCP Integration Done'."`

---

## 🔐 Security & Best Practices

* **Confidentiality**: Never share your Pipedream URLs publicly.
* **Error Logs**: Use **Cursor IDE logs** and **Pipedream logs** to debug issues.
* **Service Expansion**: Repeat the MCP setup process for each new integration (LinkedIn, GitHub, Calendar, etc.).

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
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```

---

## 🙌 Acknowledgements

Big thanks to the **Cursor AI** and **Pipedream** communities for building powerful tools that make natural language programming and automation simple and accessible.

---
