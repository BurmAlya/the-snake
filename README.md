# Изгиб Питона — игра «Змейка»

Учебный проект Яндекс Практикума. Игра реализована на Python с помощью Pygame и ООП.

## Установка и запуск

Требуется Python 3.10 или новее.

```bash
python -m venv venv
```

Активируйте окружение:
- Windows: `venv\\Scripts\\activate`
- macOS/Linux: `source venv/bin/activate`

Установите зависимости и запустите игру:

```bash
python -m pip install -r requirements.txt
python main.py
```

## Управление

- Стрелки — изменить направление движения.
- Esc — выйти из игры.
- При столкновении с собственным телом змейка возвращается в начальное состояние.
- При поедании яблока змейка увеличивается на один сегмент.

## Файлы

- `the_snake.py` — игровые классы, обработка клавиш и игровой цикл; имя соответствует шаблону Практикума.
- `main.py` — точка входа.
- `requirements.txt` — зависимости.
- `tests/` — тесты, поставляемые со стартовым шаблоном.

## Отправка в GitHub

Создайте пустой репозиторий на GitHub. В терминале из папки проекта выполните:

```bash
git init
git add .
git commit -m "Complete Snake game project"
git branch -M main
git remote add origin https://github.com/ВАШ-ЛОГИН/ИМЯ-РЕПОЗИТОРИЯ.git
git push -u origin main
```

В команде `git remote add origin` замените URL на адрес своего репозитория.
