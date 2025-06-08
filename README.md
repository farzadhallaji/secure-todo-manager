# 🔒 Secure Todo Manager

A single-file, encrypted todo manager with password protection. No servers, no databases, no tracking - just a secure HTML file that works anywhere.

## ✨ Features

- **🔐 Password Protected**: All data is encrypted with your chosen password
- **📱 Single HTML File**: No installation required - just open in any browser
- **💾 Auto-Save**: Changes are automatically saved within the file
- **🌐 Works Offline**: No internet connection needed after initial download
- **🎨 Dark Theme**: Easy on the eyes with Claude-inspired orange accents
- **📋 Multiple Sections**: Organize Todos, Tasks, Goals, and Notes
- **🏷️ Priority Levels**: Mark items as High, Medium, or Low priority
- **📦 Portable**: Download and use on any device

## 🚀 Quick Start

### Online Version
Visit: `https://[your-username].github.io/secure-todo-manager/`

### Local Version
1. Download the `index.html` file
2. Open it in any modern web browser
3. Create a password on first use
4. Start organizing your life!

## 📖 How to Use

### First Time Setup
1. Open the file in your browser
2. Enter any password you want (remember it!)
3. This password encrypts all your data

### Adding Items
1. Click on any section (Todos, Tasks, Goals, Notes)
2. Fill in the title and description
3. Select priority (for Todos, Tasks, Goals)
4. Click "Add" - it auto-saves!

### Saving Your Data
- **Auto-save**: Every change is automatically encrypted and saved
- **Download Updated File**: Click "💾 Save HTML File" to download the latest version with all your data

### Security
- Your password is never stored anywhere
- All data is encrypted using XOR cipher with Base64 encoding
- Even if someone gets your HTML file, they can't read your data without the password
- If you forget your password, your data cannot be recovered (by design)

## 🎯 Sections

### 📝 Todos
For daily tasks and things you need to get done

### ✅ Tasks  
For project-related work items and assignments

### 🎯 Goals
For long-term objectives and aspirations

### 📔 Notes
For thoughts, ideas, and general information

## 🛠️ Technical Details

- **Pure HTML/CSS/JavaScript**: No frameworks or dependencies
- **Client-side Encryption**: All encryption happens in your browser
- **Zero External Requests**: Complete privacy - no analytics, no tracking
- **Responsive Design**: Works on desktop, tablet, and mobile

## 🔄 Updating Your Data

### Method 1: Download & Replace
1. Make your changes in the app
2. Click "💾 Save HTML File" 
3. Replace the old file with the new download

### Method 2: GitHub Pages Update
1. Download the updated file
2. Go to your GitHub repository
3. Upload the new file (replacing `index.html`)
4. Changes will be live in a few minutes

## ⚠️ Important Notes

- **Remember Your Password**: There's no password recovery - if you forget it, your data is lost
- **Keep Backups**: Regularly download and backup your HTML file
- **One Password Per File**: Each HTML file has its own password
- **Browser Compatibility**: Works best in modern browsers (Chrome, Firefox, Safari, Edge)

## 🤔 FAQ

**Q: What happens if I forget my password?**  
A: Your data cannot be recovered. The encryption is designed to be secure.

**Q: Can I use different passwords for different files?**  
A: Yes! Each HTML file can have its own unique password.

**Q: Is my data really secure?**  
A: The encryption provides good protection for personal use. For highly sensitive data, consider additional security measures.

**Q: Can I share my todo list with others?**  
A: Yes, share the HTML file and password. Anyone with both can access the data.

**Q: Does it work offline?**  
A: Yes! Once you have the HTML file, no internet is needed.

## 📝 License

This project is free to use, modify, and distribute. Created with ❤️ for personal productivity.

## 🐛 Known Issues

- Basic encryption (XOR cipher) - suitable for personal use but not military-grade
- Password cannot be changed after initial setup (would require re-encryption)
- No cloud sync - manual file management required

## 💡 Tips

- Use a password manager to store your password
- Set up regular backups of your HTML file
- Create separate files for different purposes (work.html, personal.html)
- The file can be stored in cloud services like Dropbox or Google Drive

---

Made with 🧡 using HTML, CSS, and JavaScript. No cookies, no tracking, just productivity.
