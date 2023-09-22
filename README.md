## Практика оформления готового кода модуля создания персонажа для RPG игры с учетом парадигмы ООП
- оформление кода по стандартам PEP8;
- аннотация типов, docstring;
- работа с линтерами (flake8);
- дебаггинг с применением The Python Debugger;
- применение классов.

### Как запустить проект:
Клонировать репозиторий и перейти в него в командной строке:
```
git clone git@github.com:Elllym-em/character_creation_module.git
```
```
cd character_creation_module
```
Cоздать и активировать виртуальное окружение:
```
python3 -m venv env
```
* Если у вас Linux/macOS
    ```
    source env/bin/activate
    ```
* Если у вас windows
    ```
    source env/scripts/activate
    ```
Запустить файл:
```
python3 main.py
```

Для проверки кода установить библиотеку pytest и flake8:
```
pip install pytest
```
```
pip install flake8
```
