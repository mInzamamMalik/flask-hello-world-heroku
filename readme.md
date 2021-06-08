# Run this project locally:


> to run this project you must have to have `python v3.6.8` in your machines, like this:
```
malik@Apples-MBP ~ % python3 --version
Python 3.6.8
malik@Apples-MBP ~ % 
```
> and your pip must be associated with that python3.6.8 installation lioke this:
```
malik@Apples-MBP ~ % pip3 --version
pip 18.1 from /Library/Frameworks/Python.framework/Versions/3.6/lib/python3.6/site-packages/pip (python 3.6)
malik@Apples-MBP ~ % 

```

#### install dependencies:
`pip3 install -r requirements.txt`


#### run project:

`python wsgi.py`

sample output: 
```
malik@Apples-MBP flask-hello-world-heroku % pyhton3 wsgi.py 
zsh: command not found: pyhton3
malik@Apples-MBP flask-hello-world-heroku % python3 wsgi.py 
 * Serving Flask app 'app.main' (lazy loading)
 * Environment: production
   WARNING: This is a development server. Do not use it in a production deployment.
   Use a production WSGI server instead.
 * Debug mode: off
 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
```



# Deploy this project on cloud: