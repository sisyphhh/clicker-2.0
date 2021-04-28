# clicker-2.0
new version of clicker-1.0 with interfave

# Сборка приложения 
## Оптимум:

### 1. В единый файл:
pyinstaller --noconsole --onefile --add-data "MaShalled.ico;." --icon=MaShalled.ico main.py

### 2. В отделную папку с ддл итд файлами:
pyinstaller --noconsole --add-data "MaShalled.ico;." --icon=MaShalled.ico main.py
