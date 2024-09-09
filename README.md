Склонировать себе репозиторий

Поднять виртуальное окружение. Например, командой:
python -m venv test_env

Активировать окружение:
python test_env/bin/activate

Установить зависимости:
pip install -r requirements.txt

Запустить тест:
pytest --language=fr test_items.py
В качестве --language можно передавать различные локали, например es, ru, ar, it и т.д.
