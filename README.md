## **📌 ABOUT**
A simple tool to convert Python (`.py`) files into compiled Cython (`.so`) modules.  
This helps protect source code and improve performance.  

### Features
- Auto strip compiled binaries (optional)  
- Automatically delete generated `.c` files (optional)  
- Control Python language level (default: 3)  
- Colorful menu interface  

---

## 🚀 Installation (Termux)

```bash
pkg update && pkg upgrade -y
pkg install python git clang python-dev libffi-dev -y
pip install --upgrade pip setuptools wheel cython
