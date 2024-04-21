# Модуль создания персонажа для RPG игры. 

## Проект для работы с форматированием кода с помощью линтер flake8 (line-length, docstrings, isort, naming etc)

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/Forget-me-not-crossyroad/code_rules_and_linters.git
```

```
cd code_rules_and_linters
```

Cоздать и активировать виртуальное окружение:

```
python -m venv env
```

```
source venv/Scripts/activate
```

Установить зависимости из файла requirements.txt:

```
python -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python manage.py runserver
```

Запустить линтер

```
python manage.py flake8
```

