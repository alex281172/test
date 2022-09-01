Решение тестового задания: скрипт для парсинга диалогов из файла test_data.csv 

Скрипт разработан на базе: pandas, pymorphy2, nltk


Установка и запуск:
1. Склонировать репозитарий с Github
2.
https://github.com/alex281172/test.git

3. Скопировать в директорую файл test_data.csv. По условиям теста его не должно быть на Github.

5. Перейти в директорую проекта

7. Создать виртуальное окружение

python -m venv venv

4. Активировать окружение

source\venv\bin\activate

5. Установить зависимости

pip install -r requirements.txt

6. Запуск

pasr_txt.py

NB: во время первого запуска необходимо дополнительно загрузить библиотеки nltk!

Далее можно отключить - #nltk.download() в pasr_txt.py

