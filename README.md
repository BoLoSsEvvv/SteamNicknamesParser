# Steam Profile Scraper

## Описание
Этот скрипт позволяет парсить информацию о пользователях Steam по заданному нику. Для каждого найденного пользователя собирается следующая информация:
- Ссылка на профиль
- Никнейм
- Уровень профиля
- Количество игр
- Количество значков

Результаты сохраняются в CSV-файл `steam_data.csv`.

## Установка и запуск

### Требования
- Python 3.7 или выше
- Google Chrome
- ChromeDriver

### Установка зависимостей
1. Убедитесь, что у вас установлен Python. Если нет, скачайте и установите его с [официального сайта Python](https://www.python.org/).
2. Убедитесь, что у вас установлен Google Chrome.
3. Установите зависимости из файла `requirements.txt`. Выполните следующую команду:
   ```bash
   pip install -r requirements.txt
   ```

### Как запустить
1. Скачайте репозиторий на свой компьютер.
2. Убедитесь, что у вас есть файл `requirements.txt` с необходимыми зависимостями:
   ```
   selenium
   webdriver-manager
   pandas
   ```
3. Запустите скрипт с помощью Python:
   ```bash
   python steam_scraper.py
   ```
4. Введите никнейм в консоли.
5. Дождитесь завершения работы скрипта. Результаты будут сохранены в файл `steam_data.csv` в текущей директории.
