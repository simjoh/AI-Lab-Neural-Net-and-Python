# AI labs Region Västerbotten

## Installation of python enviroment
One of the following ways can be used to get the enviroment up and running:

### If python exist on computer.
The `requirements.txt` file list all Python libraries that your notebooks
depend on, and they will be installed using pip. If you don´t have pip install it by downloading https://bootstrap.pypa.io/get-pip.py then run
```
python get-pip.py
```
Then install all libraries in the requirements.txt file

```
pip install -r requirements.txt
```

### If you don't have python 
#### Windows
Download the excecutable installer file from

https://www.python.org/downloads/release/python-368/


C:\Users\YourUserName\AppData\Local\Programs\Python\Python36\python .\Documents\test.py

save the path to 

Add the path to your python installation in the Systeme varialbe Path (skip the ending python)

C:\Users\sjohanss\AppData\Local\Programs\Python\Python36\

also add 
C:\Users\sjohanss\AppData\Local\Programs\Python\Python36\Scripts
to the path. This will be needed for pip that will also be installed.

Write
```
python --version
```
in the command editor to test if installation succeded.

Install pip by downloading https://bootstrap.pypa.io/get-pip.py then run
```
python get-pip.py
```

Install virtual enviroments
```
pip install virtualenv
```

Activate the virtual enviroment
.\venv\Scripts\activate

Install from requirements.txt

### If everythin fails
A Binder-compatible repo with a `requirements.txt` file.

Access this Binder at the following URL 

https://mybinder.org/v2/gh/simjoh/BinderBase.git/master


## Credits
This project is created with:  
[![Binder](http://mybinder.org/badge_logo.svg)](http://beta.mybinder.org/v2/gh/binder-examples/requirements/master)