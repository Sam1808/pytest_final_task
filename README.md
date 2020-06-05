# Финальное задание 
Решение в соответвии с [заданием Stepik.org](https://stepik.org/lesson/237240/step/9?unit=209628).
1. Пожалуйста скачайте файлы `conftest.py` и `test_items.py`
2. Установите зависимости в виртуальном окружении python в соответвии с requirements.txt
  `pip install -r requirements.txt`
3. Тест работает под web-драйвером Chrome. [Как установить](https://stepik.org/lesson/25969/).
4. Запустите тест командой: 
  `pytest --language=es test_items.py`
  Вы можете менять язык открываемой страницы 
  `pytest --language=ru test_items.py` - русский язык
  `pytest --language=fr test_items.py` - французский язык
В коде заложена пауза в 10 секунд для визуальной проверки.
