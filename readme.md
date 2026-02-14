# Настройка CI/CD
## Ход работы
1. Создать репозиторий в GitHub
2. Склонировать репозиторий на локальный компьютер в папку проекта
3. Открыть папку проекта в VS Code
4. Создать файл настроек CI/CD: `.github/workflows/cicd.yaml`
5. Создать файл приложения `app.py`
6. Создать и активировать виртуальное окружение Python
    py -m venv venv
    venv\scripts\activate
7. Создать requirements.txt:
    gradio
    flake8
    mypy
8. Установить пакеты: `pip install -r requirements.txt`
9. Проверить что приложение работает `python app.py`
10. Добавить в проект файл `.gitignore`
11. Создать коммит, отправить его на GitHub