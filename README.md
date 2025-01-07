
# helloworld

`helloworld` — это простая библиотека на Python, которая предоставляет функции для печати приветственных сообщений. 

## Установка

Просто заюзай pip install helloeverything

## Использование

```python
from helloeverything import HelloWorld, HelloName, HelloUser

# Вывод стандартного сообщения
HelloWorld()  # Результат: Hello, World!

# Вывод сообщения с именем
HelloName("Alice")  # Результат: Hello, Alice!

# Приветствие текущего пользователя системы
HelloUser()  # Результат: Hello, <ваш_пользователь_системы>!
```

## Функции

### `HelloWorld()`
Выводит стандартное приветствие: `Hello, World!`.

### `HelloName(name)`
Выводит приветствие с именем пользователя.
- **Аргументы:**
  - `name` (str): Имя, которое будет использовано в приветствии.

### `HelloUser()`
Приветствует текущего пользователя системы. Имя пользователя определяется с помощью функции `os.getlogin()`.

## Пример работы
```python
>>> HelloWorld()
Hello, World!

>>> HelloName("John")
Hello, John!

>>> HelloUser()
Hello, your_system_username!
```

## Требования
- Python 3.x

## Лицензия
Этот проект лицензирован под лицензией MIT. См. файл [LICENSE](LICENSE) для получения подробной информации.
