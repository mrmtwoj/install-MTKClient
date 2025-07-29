# install-MTKClient

Install MTKClient on Windows OS using the required tools and drivers.

بر روی ویندوز ابزار MTKClient را با نصب وابستگی‌ها راه‌اندازی کنید.  
Установите MTKClient в Windows с помощью необходимых инструментов и драйверов.  
在 Windows 上使用所需的工具和驱动程序安装 MTKClient。

---

## 🐍 Python

Install Python from the official website. Required for running MTKClient and its dependencies.  
🔗 https://www.python.org/

نصب پایتون برای اجرای MTKClient ضروری است.  
Установите Python, необходим для запуска MTKClient.  
安装 Python，用于运行 MTKClient。

---

## 📁 Windows File System Proxy (WinFsp)

Allows user-mode file systems for tools that MTKClient depends on.  
🔗 https://winfsp.dev/rel/

WinFsp برای اجرای سیستم فایل در سطح کاربر مورد نیاز است.  
WinFsp необходим для работы пользовательских файловых систем.  
WinFsp 用于启用用户模式文件系统。

---

## 🔐 Win64 OpenSSL v3.5.1

Provides cryptographic libraries for Python modules.  
🔗 https://slproweb.com/products/Win32OpenSSL.html

کتابخانه‌های رمزنگاری موردنیاز برخی ماژول‌های پایتون را فراهم می‌کند.  
Предоставляет криптографические библиотеки для Python.  
为 Python 模块提供加密库。

---

## 🛠 Visual Studio 2022 (Build Tools with C++)

Install with C++ build tools. Required for compiling some Python dependencies.  
🔗 https://visualstudio.microsoft.com/downloads/?q=build+tools

نصب Visual Studio با ابزار C++ برای کامپایل ماژول‌ها ضروری است.  
Установите Visual Studio с C++ для сборки зависимостей.  
安装带有 C++ 的 Visual Studio 以编译依赖项。

---

## ⚙️ MTKClient Installation

Clone the repository and install required Python packages.  
```bash
git clone https://github.com/bkerler/mtkclient
cd mtkclient
pip3 install -r requirements.txt
pip3 install .
