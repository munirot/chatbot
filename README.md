# User-Authentication-in-Flask

## Set up & Installation.

### 1 .Clone
                    
**Windows**
          
```bash
git clone 
cd chatbot
py -3 -m venv venv

```
          
**macOS/Linux**
          
```bash
git clone 
cd chatbot
python3 -m venv venv

```

### 2 .Activate the environment
          
**Windows** 

```venv\Scripts\activate```
          
**macOS/Linux**

```. venv/bin/activate```
or
```source venv/bin/activate```

### 3 .Install the requirements

Applies for windows/macOS/Linux

```
cd main
pip install -r requirements.txt
```
### 4 .Migrate/Create a database

```python manage.py```

### 5. Run the application 

**For linux and macOS**
Make the run file executable by running the code

```chmod 777 run```

Then start the application by executing the run file

```./run```

**On windows**
```
set FLASK_APP=routes
flask run
```



