# dolphin-anty
Скрипт для бесконечного количества профилей бесплатно dolphin-anty

0.скачиваем  python  https://www.python.org/downloads/
## **Настройка:**
1. Сначала вам нужно войти в свою учетную запись в программе Dolphin Any или создать новую, так как старые профили браузера все равно 
не будут видны. Вам нужно убедиться, что у вас есть ** по крайней мере 1 незанятый профиль ** в наличии до истечения лимита 
профиля (9/10), в противном случае профилирование не сработает. Затем мы закрываем антидетект.
2. Скопируйте файл **app.asar** файл из папки files скрипта и переместите его с заменой в папку с установленным anti detect \Dolphin Anty\resources. Скорее всего, вы сможете найти нужную папку anti detect по одному из следующих путей:
 - C:\Users\*your username*\AppData\Local\Programs\Dolphin Anty\resources
 - C:\Program Files\Dolphin Anty\resources
3. pip install -r requirements.txt
4. python main.py

## **Настройки:**
Вы можете открыть **settings.py** file and set the **backup** variable to **True** or **False**. Каждый раз, когда профиль успешно закрывается, он будет копироваться в папку browsers_backup
