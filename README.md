
# EgoBird 🐦

เกมนกบินข้ามสิ่งกีดขวาง สร้างด้วย Python + Tkinter

## วิธีรันเกม

```bash
python main.py
```

## วิธีสร้างไฟล์ .exe

ติดตั้ง PyInstaller:

```bash
pip install pyinstaller
```

สร้างไฟล์ exe:

```bash
pyinstaller --onefile --windowed --icon=egobird.ico main.py
```

ไฟล์ exe จะอยู่ในโฟลเดอร์ `dist`

## วิธีอัปโหลดขึ้น GitHub

```bash
git init
git add .
git commit -m "First commit"
git branch -M main
git remote add origin YOUR_GITHUB_REPO_URL
git push -u origin main
```

## Requirements

- Python 3.x
- tkinter
