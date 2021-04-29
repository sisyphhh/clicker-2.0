# clicker-2.0
new version of clicker-1.0 with interface
  
  
# Сборка приложения 

### 0. Установить Python
  
### 1. Установить pyinstaller с помощью cmd
pip install pyinstaller
  
### 2. Скачать репозиторий
  
### 3. В cmd перейти у папку с файлами и совершить сборку:

#### 3.1. В единый файл(оптимальное решение):
pyinstaller --noconsole --onefile --add-data "MaShalled.ico;." --icon=MaShalled.ico main.py

#### 3.2. Либо в отделные папку с exe,ddl итд файлами:
pyinstaller --noconsole --add-data "MaShalled.ico;." --icon=MaShalled.ico main.py
  
### 4. После завершения операций в консоле - удаляем все папки кроме Dist
  
  
# Использование:
### 0. Процесс/Режим кликера запускается при нажатии на кнопку - enter(в приложении)
  
### 1. Для ввода параметров в кликер используется - enter
  
### 2. Результат калькулятора можно получить применив кнопку - равно
  
### 3. Следуйте указаниям, котороые отображаются в приложении 
  
  
## Пример

### 0. Открываем приложение (можем пользоваться урезанным калькулятором расчитывая количесво секунд для последующих вычислений - подсчет происходит после нажания на знак '=')

### 1. Нажимаем - enter(в приложении) и переходим в режим кликера
![Image alt](https://github.com/sisyphhh/hello-world/blob/master/images/clicker-2.0/Снимок0.PNG)

### 2. Далее будет предложено выбрать координату на мониторе - сделать это можно путем нажатия ПРАВОЙ кнопкой мыши по месту куда планируются последующие клики.
![Image alt](https://github.com/sisyphhh/hello-world/blob/master/images/clicker-2.0/Снимок1.PNG)

### 3. После запоминания координаты необходимо ввести количесво кликов(и явно подтвертидить через 'enter')
![Image alt](https://github.com/sisyphhh/hello-world/blob/master/images/clicker-2.0/Снимок2.PNG)
![Image alt](https://github.com/sisyphhh/hello-world/blob/master/images/clicker-2.0/Снимок3.PNG)

### 3. Завершающим этапом будет ввод интервала между кликами (все время вводится в секундах)