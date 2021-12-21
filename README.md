# rememberthee-admin

<!-- Source code for www.rememberthee.com - the marketing website for Remember Thee. -->

## Technologies
Backend
-  [Python](https://www.python.org) 3.10.0
-  [FastAPI](https://fastapi.tiangolo.com/)

Frontend
-

## Installation
Reference Documentation:
- [FastAPI Installation](https://fastapi.tiangolo.com/#installation)
- [venv](https://docs.python.org/3/library/venv.html#module-venv)

Fork and then clone your fork into your file system and navigate to the project root:
```
 git clone https://github.com/{your_username}/rememberthee-admin.git
 cd rememberthee-admin
```

Set the upstream remote
```
 git remote add upstream https://github.com/tdowds/rememberthee-admin.git
```

Make sure you have Python 3 installed on your machine.
```
 which python3
/usr/local/bin/python3
```
or
```
python
Python 3.10.0 (v3.10.0:b494f5935c, Oct  4 2021, 14:59:20) [Clang 12.0.5 (clang-1205.0.22.11)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>>
```

Create a virtual environment using the python module [venv](https://docs.python.org/3/library/venv.html#module-venv).

If you don't already have a `.venv` directory in your file system, I would recommend creating it in your root directory.
```
 mkdir ~/.venv
```

Then create your virtual environment in that `.venv` folder.
```
 python3 -m venv ~/.venv/rememberthee-admin
```

Then activate your virtual environment:
```
 source ~/.venv/rememberthee-admin/bin/activate
```

Next you need to download FastAPI and Uvicorn. Make sure you have [pip](https://pypi.org/project/pip/) installed:
```
 pip install FastAPI
 pip install "uvicorn[standard]"
```

## Development
When you begin development, make sure you're in your virtual environment:
```
 source ~/.venv/rememberthee-admin/bin/activate
```

Turn on debug mode:
```
 uvicorn main:app --reload
```

Then execute `flask run` and navigate to `localhost:5000` in your browser.

## Deployment
https://help.pythonanywhere.com/pages/UploadingAndDownloadingFiles
- Need to automatically perform new packages downloads and package updates
