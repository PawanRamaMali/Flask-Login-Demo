# Flask-Login-Demo

To Run the application 

Install Requirements command 

```
pip install requirements.txt
```

Add configuration file, "config.py" in parent folder with below content
```
import os
from dotenv import load_dotenv

basedir = os.path.abspath(os.path.dirname(__file__))
load_dotenv(os.path.join(basedir, '.env'))

class Config(object):
    SECRET_KEY = os.environ.get("SECRET_KEY") or "4567121"
    MONGO_URI = ""
```

To run Flask 

```
flask run
```
