# 📁 Secure File Upload - Multi-File Version

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen)](https://bitcodeashishcloud.github.io/Files-Shorter/)
[![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-blue)](https://pages.github.com/)
[![Google Drive API](https://img.shields.io/badge/Google-Drive-red)](https://developers.google.com/drive)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)

A **secure, client-side file upload tool** that organizes and uploads multiple files directly to your Google Drive, sorted by subject. No server required - everything runs in your browser!

## 🌟 Features

✅ **Multi-File Upload** - Select and upload multiple files at once  
✅ **Subject-Based Organization** - Auto-creates folders by subject (Hacking, DBMS, DSA, etc.)  
✅ **100% Secure** - Files go directly from your browser to Google Drive  
✅ **No Backend** - Pure HTML/CSS/JavaScript, hosted on GitHub Pages  
✅ **Custom Subjects** - Create your own subject categories  
✅ **Progress Tracking** - See upload status for each file  
✅ **Mobile Friendly** - Works on all devices  
✅ **Zero Storage Cost** - Uses your Google Drive storage  

## 🚀 Live Demo

**🔗 Try it now:** https://bitcodeashishcloud.github.io/Files-Shorter/

## 📋 How It Works
1. Sign in with Google → Grant Drive permissions
2. Enter your name & select subject
3. Choose one or multiple files
4. Click "Upload to Drive"
5. Files are organized in: YourFolder/Subject/YourName_FileName

## 🎯 Use Cases

- 📚 **Students** - Organize notes by subject
- 💼 **Professionals** - Backup project files
- 📸 **Photographers** - Sort images by category
- 🎓 **Teachers** - Collect student assignments
- 📝 **Researchers** - Organize documents by topic

## 🛠️ Setup Instructions

### For Users (No Setup Required!)

1. Visit the [live page](https://bitcodeashishcloud.github.io/Files-Shorter/)
2. Click the **⚙️ Settings** button (top-right)
3. Create a folder in your Google Drive
4. Copy the folder URL or ID
5. Paste it in Settings and click **Save**
6. Start uploading!

### For Developers (Deploy Your Own)

1. **Fork this repository**
   ```bash
   git clone https://github.com/yourusername/Files-Shorter.git
2. **Set up Google Cloud Console**
  - Go to Google Cloud Console
  - Create a new project
  - Enable Google Drive API
  - Create OAuth 2.0 Client ID (Web Application)
  - Add authorized origins: https://yourusername.github.io
  - Copy your Client ID
3. **Update the code**
  - Open index.html
  - Replace CLIENT_ID with your OAuth Client ID
  const CLIENT_ID = 'your-client-id.apps.googleusercontent.com';
4. **Deploy to GitHub Pages**
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
  - Go to Settings → Pages
  - Select main branch → Save
5. **Configure OAuth**
  - Add your GitHub Pages URL to Authorized JavaScript origins
  - Add redirect URI: https://yourusername.github.io
**📁 Folder Structure**
Files-Shorter/
├── index.html              # Multi-file uploader (main)
├── one-file/
│   └── index.html          # Single-file uploader
├── README.md               # This file
└── .gitignore
