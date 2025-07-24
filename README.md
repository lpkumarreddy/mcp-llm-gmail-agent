## 📬 Project 1: Gmail AI Agent Integration with Cursor IDE
This project guides you through setting up Cursor AI Editor and integrating it with Gmail (via MCP Servers using Pipedream), enabling powerful AI-driven email workflows like sending, retrieving, and managing emails through natural language commands.

## 🧰 Prerequisites
**Pipedream Account** (https://pipedream.com/)

**Authenticated Gmail Account**

**Cursor AI Editor Installed** (Windows, macOS, or Ubuntu 24.04)

Familiarity with basic IDE usage

## 🚀 Installation & Setup
**1. Install Cursor AI**
**Windows**
Download Cursor for Windows

Watch Installation Tutorial (YouTube)

**macOS**
Follow official setup guide: Steps for macOS

**Ubuntu 24.04**
Follow official setup guide: Steps for Ubuntu

✅ **Sign in** to Cursor using your Gmail or GitHub account.

## ⚙️ Initial Cursor IDE Configuration
**Launch Cursor IDE**

On Welcome Screen → Click Skip → then Continue through all setup screens

Click the Settings (⚙️) icon at the top-right

Navigate to Tools & Integrations

Click Add Custom MCP

## 🌐 Adding MCP Servers (via Pipedream)
**1. Get Your Gmail MCP Server URL**
Go to Pipedream

Sign in or create an account

Search and connect the Gmail tool

Switch to the Cursor tab

Copy only the Gmail-related MCP configuration URL

⚠️ Never share this URL – it contains sensitive authentication tokens.

**2. Add MCP to Cursor**
Open Cursor Settings → Tools & Integrations

Paste the copied MCP config under MCP Servers

Save with Ctrl + S

## 🤖 Running Gmail Workflows in Cursor
**Step 1: Open AI Panel**
Click New Chat (top-right), or use shortcut Ctrl + Alt + B

**Step 2: Use AI Prompts**
Examples:
Send an email to my team using Gmail summarizing today's meeting notes.
Or combine Gmail + LinkedIn:
*Get my details from LinkedIn, apply for a job at {company name}, write a short cover letter, and send everything to {email address}.*

**Step 3: Confirm Result**
Check your Gmail Sent folder

Monitor logs in Cursor for success/failure details

## 🧪 More Example Prompts
**Fetch Emails:**
*Get the last 5 emails from my Gmail inbox and display them here.*

**Schedule Event:**
*Schedule a calendar event for tomorrow at 3 PM using Google Calendar.*

**Push to GitHub:**
*Push the current code to my GitHub repository with the commit message "MCP Integration Done".*

**🔐 Important Notes**
*Security:* Do not share your Pipedream MCP URLs.

*Error Handling:* Check logs in Pipedream or Cursor IDE.

*Scaling:* To add more services (like YouTube or Calendar), repeat the MCP server setup.

📄 License
This project is licensed under the MIT License.

MIT License

Copyright (c) 2025 lpkumarreddy

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights  
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell     
copies of the Software, and to permit persons to whom the Software is         
furnished to do so, subject to the following conditions:                       

The above copyright notice and this permission notice shall be included in    
all copies or substantial portions of the Software.                           

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR    
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,      
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE   
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER        
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, 
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN     
THE SOFTWARE.


## 🙌 Acknowledgements
Thanks to the *Cursor AI* and *Pipedream* communities for building such powerful integration tools.
