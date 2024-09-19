# Auto-grader: Django Tutorial part 2

# VIDEO LINK:
```
https://drive.google.com/file/d/1XBirQDQrEM9S7gKz0cdXaU_oAsmHb5po/view?usp=sharing
```
## Fork My page:
```
git clone https://github.com/Darkwebnew/Django-2
```

```
mkvirtualenv --python=/usr/bin/python3.10 mysite-env
```

```
cd mysite
```

```
pip install -r requirements.txt
```

```
python manage.py migrate
```

```
python manage.py collectstatic
```
## In enviromental edit
```
import os
import sys

path = '/home/<your_username>/mysite'
if path not in sys.path:
     sys.path.insert(0, path)

os.environ['DJANGO_SETTINGS_MODULE'] = 'mysite.settings'
from django.core.wsgi import get_wsgi_application
application = get_wsgi_application()
```

## LocalHost id,pass

admin

password

## ADD NEW AND CREATE NEW USER

Account: dj4e

Password: ceb4163dd
