## **📌 ABOUT**
A simple tool to convert Python (`.py`) files into compiled Cython (`.so`) modules.  
This helps protect source code and improve performance.  

### FEATURES
- Auto strip compiled binaries (optional)  
- Automatically delete generated `.c` files (optional)  
- Control Python language level (default: 3)  
- Colorful menu interface  

---

## **🚀 INSTALLATION**

### 📱 TERMUX
```
pkg update && pkg upgrade -y
pkg install python git clang python-dev libffi-dev -y
pip install --upgrade pip setuptools wheel cython
```

### 🐧 LINUX (UBUNTU / DEBIAN)
Update & Upgrade Packages :
```
sudo apt update && sudo apt upgrade -y```
