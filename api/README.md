# Django Class Based API

- We can also write our API views using class-based views, rather than function based views. As we'll see this is a powerful pattern that allows us to reuse common functionality, and helps us keep our code DRY.

## Setup

**For install in your system you just need to**

- install virtual env package

```sh
pip install virtualenv
```

- Create Virtual Env

```sh
python3 -m venv env_name
```

- The clone this repo

- Install requirements

```sh
pip install -r requirements.txt
```

- Make Migration & Migrate

```sh
py manage.py makemigrations

py manage.py migrate
```

- Runserver

```sh
py manage.py runserver PORT_NO_IF_NEEDED
```

- For Checking Rest API Uncomment the Comment in myapi file

```sh
python myapi.py
```
