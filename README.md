# Laravel Windows Portable 5.14.2 – Stable Version

This is a **portable version of Laravel Installer 5.14.2** for Windows, packaged to run without requiring a full system setup. It's ideal for developers who need a quick, self-contained Laravel environment without installing Laravel or Composer globally.

The entire environment is included in a `.7z` archive — just extract, run, and start developing.

---

## 📦 Distribution

The project is distributed as a `.7z` archive:

```
laravel_windows_5.14.2-portable-stable.7z
```

---

## 📥 How to Install

1. Extract the `.7z` archive using **7-Zip**, **WinRAR**, or any compatible tool.
2. Navigate into the extracted folder.
3. Run the installer:

   ```
   LARAVEL-INSTALL.exe
   ```

4. Wait for the setup to complete. Laravel CLI and all dependencies will be ready to use.

---

## ❌ How to Uninstall

To completely remove the Laravel portable environment:

```
LARAVEL-UNINSTALL.exe
```

This will clean up all associated files and configurations.

---

## 🚀 Key Features

- ✅ Fully portable Laravel Installer 5.14.2
- ✅ Composer and Carbon CLI included
- ✅ No need for global Laravel or PHP installation
- ✅ Ready-to-use out of the box
- ✅ Ideal for testing, education, or lightweight development

---

## 📁 Directory Structure

```
laravel_windows_5.14.2-portable-stable/
├── Composer/
│   └── vendor/
│       └── bin/
│           ├── laravel
│           └── carbon
├── LARAVEL-INSTALL.exe
├── LARAVEL-UNINSTALL.exe
├── php/ (optional, portable PHP)
├── README.md
```

---

## 🧩 Laravel CLI Usage

After installation, you can run the following Laravel commands:

```bash
laravel -v             # Display Laravel Installer version (5.14.2)
laravel new app-name   # Create a new Laravel application
laravel list           # List available commands
laravel help           # Show help for a command
```

---

## 🕒 Carbon CLI Support

This portable package also includes Carbon CLI tools:

- **carbon-cli version:** 1.3.0
- **Installed dependencies:**
  - `nesbot/carbon` v3.9.1
  - `carbonphp/carbon-doctrine-types` v3.2.0
  - `symfony/translation`, `clock`, `polyfill`, and more

These packages are pre-installed and ready to use for date/time handling in the CLI.

---

## 🔧 How to Use

1. Open **Command Prompt** or **PowerShell**
2. Navigate to the Laravel CLI directory:

   ```bash
   cd D:\upload-github\portable\fix\laravel_windows_5.14.2-portable-stable\Composer\Composer\vendor\bin
   ```

3. Run any Laravel command:

   ```bash
   laravel -v
   laravel new blog
   ```

---

## 💡 Notes

- This version is ideal for offline use or situations where you cannot modify system settings.
- Optional `php/` folder may be included to run Laravel without a system-installed PHP.
- No internet connection or admin privileges are required to use or remove this portable environment.

---

## ✅ Recommended Use Cases

- Educational environments
- Laravel workshops and training sessions
- Development on restricted machines (e.g., company PCs)
- Temporary projects or testing environments

---

**Start building Laravel applications in seconds — no installation, no hassle. Just extract and go!**
