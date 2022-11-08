## Installation


### 1. python3 -m venv myvenv
### 2. python -m pip install --upgrade pip
### 3. pip install -r requirements.txt
### 3. python manage.py migrate

---

### 1. create file .env in root directory
### 2. `run :` python -c 'from django.core.management.utils import get_random_secret_key; \
      print(get_random_secret_key())'

### 3. add `SECRET = result of previous point`

### 4. python manage.py runserver

--gl hf--


