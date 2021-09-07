# Dead By Daylight Skillcheck Bot
Бот написанный на основе компьютерного зрения
Данный скрипт написан сугубо в образовательных целях, использование в игре не рекомендуется и запрещено пользовательским соглашением
## Что умеет
- Автоматически нажимает скиллчек
- Автоматически вырывается из рук убийцы
- Автоматически зажимать ЛКМ
- Автоматически зажимать ПКМ
# Требуемые параметры для работы скрипта
- Цвета: стандартные
- Установленный питон, библиотеки: opencv, numpy, mss, pynput, pywin32, pyautogui, pyqt5
- Повышенная яркость и контрастность допускается
# Установка
1. Установить питон и добавить в PATH
2. Установить библиотеки: в cmd
```bash
pip install opencv-python numpy mss pynput pywin32 pyautogui pyqt5 requests
```
Или, находясь в директории с файлами проекта: в cmd
```bash
pip install -r requirements.txt
```
3. Скачать python файлы
4. Запустить main.pyw
# Рекомендации по использованию
Рекомендации по использованию:
1. Скрипт работает на основе детекта цвета в определенных областях экрана, при работе AutoSkillCheck старайтесь избегать появления красного и белого цветов в области появления скиллчека, дабы избежать ложного срабатывания.
2. AutoWigle сейчас нормально работает только при разрешении 1920 на 1080, при этом вызывая ложные срабатывания в особо ярких местах.
3. Рекомендуется НЕ использовать комплексные кнопки (типа space), из-за которых возможны ложные срабатывания
# Скриншот
![dq](https://user-images.githubusercontent.com/69106429/131217271-0a477dd2-c7cd-42b7-948e-6c828d5ea784.png)
# Видео
https://youtu.be/KhAYn-e8cK4
