My simple web & rest-api

0. Check your OS version ?
If Windows, please install **"Microsoft Visual C++ Build Tools**
```
https://go.microsoft.com/fwlink/?LinkId=691126
```
or
```
https://visualstudio.microsoft.com/visual-cpp-build-tools/
```

after install this, you can install cffi, bcrypt, jwt,...libs

(free space from 4GB to 9GB :(( )

1. Install requirement


```
pip install -r requirements.txt
```


2. Start application

```
python manage.py runserver
```

3. Connect to web-route:

http://127.0.0.1:5001/myApi/hello


4. Connect to healtCheck API

http://127.0.0.1:5001/myApi/healthCheck/


5. Connect to swagger

http://127.0.0.1:5001/myApi/

