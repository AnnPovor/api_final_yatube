# api_final
API для проекта Yatube
***
## Установка проекта:
### 
```python 
git clone git@github.com:AnnPovor/api_final_yatube.git
```
```python 
cd yatube_api
```
## Создать и активировать виртуальное окружение:
###
```python
python -m venv venv
```
```python
source venv/Scripts/activate
```
## Установить зависимости из файла requirements.txt:
###
```python
python -m pip install --upgrade pip
```
```python
pip install -r requirements.txt
```
## Выполнить миграции
###
```python
python manage.py migrate
```
## Запустить проект:
###
```python 
python manage.py runserver
```