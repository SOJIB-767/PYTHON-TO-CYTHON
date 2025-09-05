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

### 📱 Termux
```
pkg update && pkg upgrade -y
pkg install python git clang python-dev libffi-dev -y
pip install --upgrade pip setuptools wheel cython
```

### 🐧 Linux (Ubuntu / Debian)
Update & upgrade packages :
```
sudo apt update && sudo apt upgrade -y
```

Install Rquired Dpendencies :
```
sudo apt install python3 python3-pip git clang python3-dev libffi-dev -y
```
Upgrade pip, setuptools, wheel and install Cython :
```
pip3 install --upgrade pip setuptools wheel cython
```

### 🪟 Windows
- Download and install Python 3.12+ from [python.org](https://www.python.org/downloads/).
(Make sure to tick ✅ "Add Python to PATH" during installation).
- Open Command Prompt or PowerShell and run :
```
pip install --upgrade pip setuptools wheel cython
```

### 🍏 macOS
Update & upgrade Homebrew (if installed) :
```
brew update && brew upgrade
```
Install required dependencies :
```
brew install python git llvm libffi
```
Upgrade pip, setuptools, wheel and install Cython :
```
pip3 install --upgrade pip setuptools wheel cython
```
