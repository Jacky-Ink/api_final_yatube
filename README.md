Учебный проект по написанию API. Как запустить:

Клонировать репозиторий и перейти в него в командной строке:
git clone https://github.com/Jacky-Ink/api_final_yatube.git
cd api_final_yatube

Cоздать и активировать виртуальное окружение:
python3 -m venv venv
source venv/bin/activate
python3 -m pip install --upgrade pip
pip install djoser

Установить зависимости из файла requirements.txt:
pip install -r requirements.txt

Выполнить миграции:
python3 manage.py migrate

Запустить проект:
python3 manage.py runserver