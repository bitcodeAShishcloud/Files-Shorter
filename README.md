# 📁 Secure File Upload - Multi-File Version
[![Help Section](https://img.shields.io/badge/Help-Demo-saffron)](https://bitcodeashishcloud.github.io/Files-Shorter/guide.html/)
[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen)](https://bitcodeashishcloud.github.io/Files-Shorter/)
[![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-blue)](https://pages.github.com/)
[![Google Drive API](https://img.shields.io/badge/Google-Drive-red)](https://developers.google.com/drive)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow)](https://opensource.org/licenses/MIT)

A **secure, client-side file upload tool** that organizes and uploads multiple files directly to your Google Drive, sorted by subject. No server required - everything runs in your browser!

## 🌟 Features

✅ **25+ Languages Supported** - Including English, Spanish, French, German, Chinese, Japanese, Korean, Hindi, and many more( <b> [help](https://bitcodeashishcloud.github.io/Files-Shorter/guide.html/))</b> <br>
✅ **Multi-File Upload** - Select and upload multiple files at once  
✅ **Subject-Based Organization** - Auto-creates folders by subject (Hacking, DBMS, DSA, etc.)  
✅ **100% Secure** - Files go directly from your browser to Google Drive  
✅ **No Backend** - Pure HTML/CSS/JavaScript, hosted on GitHub Pages  
✅ **Custom Subjects** - Create your own subject categories  
✅ **Progress Tracking** - See upload status for each file  
✅ **Mobile Friendly** - Works on all devices  
✅ **Zero Storage Cost** - Uses your Google Drive storage 

## 🚀 HELP Section

**🔗 Try it now:** <b>[Multi-Language Guide & Security Details Page](https://bitcodeashishcloud.github.io/Files-Shorter/guide.html/)</b>


## 🚀 Live Demo

**🔗 Try it now:** <b>[ENJOY Secure File Upload with Best Sorting System](https://bitcodeashishcloud.github.io/Files-Shorter/)

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
```bash
Files-Shorter/
├── index.html              # Multi-file uploader (main)
├── one-file/
│   └── index.html          # Single-file uploader
├── README.md               # This file
└── .gitignore
```
**🎨 Supported File Types**
   - 📄 Documents: PDF, Word, TXT, PPT
   - 🖼️ Images: JPG, PNG, GIF, WebP, SVG
   - 🎥 Videos: MP4, AVI, MOV, MKV
   - 📦 Others: Any file type supported by Google Drive

## 🔒 Security & Privacy

**Why This is 100% Secure:**<br>
   🔐 Client-Side Only - No server processes your files<br>
   🔐 Direct Upload - Files go straight to Google Drive<br>
   🔐 No Data Storage - Nothing stored on GitHub or third-party servers<br>
   🔐 Your Data, Your Control - Only you have access to your Drive<br>
   🔐 Open Source - All code is visible and auditable<br>


**What Permissions Are Needed?**<br>
   The app requests drive.file scope which allows:<br>
   ✅ View and manage Google Drive files created by this app<br>
   ✅ Create new folders and files<br>
   ❌ Cannot access your existing files<br>
   ❌ Cannot share or delete files outside the app<br>

## 📊 Upload Summary Example

   ✅ Success: 5 file(s)
   ❌ Failed: 0 file(s)

**Files:**
   ✅ notes1.pdf
   ✅ notes2.pdf
   ✅ assignment.docx
   ✅ image.png
   ✅ video.mp4

## 🎯 Pre-configured Subjects
   - Hacking
   - Hacking
   - Ethical Hacking
   - DBMS (Database Management System)
   - AICE (Artificial Intelligence & Computer Engineering)
   - CTI (Computer Theory & Information)
   - DSA (Data Structures & Algorithms)
   - Web Technology
   - UPSC (Civil Services)
   - English
   - Mathematics
   - Science
   - History
   - Geography
   - Politics
   - ```+``` Custom subjects (create your own!)
## 🐛 Troubleshooting

| Issue | Solution |
|-------|----------|
| "Access blocked" error | Add your email to Test Users in Google Cloud Console |
| Upload button disabled | Click "Sign in with Google" first |
| "Folder ID not set" | Click ⚙️ Settings and paste your Drive folder ID |
| "Google hasn't verified" | Click Continue → Allow (normal for personal apps) |

## 🔄 Single-File Version

Prefer uploading one file at a time? Try our lightweight version:

**🔗 Single-File Uploader:** https://bitcodeashishcloud.github.io/Files-Shorter/one-file/

## 👨‍💻 Author

**Ashish Gupta**  
🔗 GitHub: https://github.com/bitcodeAShishcloud  
📧 Contact: [Google Mail](agupta38160@gmail.com)

## 📝 License

MIT License - Free to use, modify, and distribute.

---
<div style=text-align: center>
**Made with ❤️ by Ashish Gupta | Hosted on GitHub Pages**

⭐ If you find this useful, please give it a star!
</div>
