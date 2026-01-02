Запуск тестов

# Установка зависимостей
pip install -r requirements.txt

# Запуск всех тестов
pytest tests/ -v

# Запуск только позитивных тестов
pytest tests/ -m positive -v

# Запуск с генерацией HTML отчета
pytest tests/ --html=report.html

# Запуск с разными размерами окна браузера
pytest tests/ --browser_size=desktop  # 1920x1080
pytest tests/ --browser_size=mobile   # 390x844
