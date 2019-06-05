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

C:\Users\YourUserName\AppData\Local\Programs\Python\Python36\

also add 
C:\Users\YourUserName\AppData\Local\Programs\Python\Python36\Scripts
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

Download the repository for this lab from https://github.com/simjoh/AI-Lab-Neural-Net-and-Python/

Create a new virtual enviroment
```
python -m venv myenv
```

Activate the virtual enviroment
```
.\myvenv\Scripts\activate
```

Install from requirements.txt
```
pip install -r requirements.txt
```

Activate the virtual enviroment
.\venv\Scripts\activate

### Linux
Check if python is installed
```
python --version
or
python3 --version
```

If python 3 is not installed download and install from https://www.python.org/downloads/ and install 3.6.8

Check if python got installed by `python --version` or `python3 --version`.

```
sudo apt-get install python3-pip
```
Update pip if you are asked to

Install virtual enviroment
```
sudo pip3 install virtualenv
```

Create a virtual enviroment
virtualenv -p python3 myvenv

Activate virtual enviroment
```
source ./venvs/tf2/bin/activate
```


### Mac
Check if python is installed
```
python --version
or
python3 --version
```

If python 3 is not installed download and install from https://www.python.org/downloads/ and install 3.6.8

curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
python get-pip.py

Then follow the installation instructions for windows but start wach line with sudo

### If everythin fails
A Binder-compatible repo with a `requirements.txt` file.

Access this Binder at the following URL 

https://mybinder.org/v2/gh/simjoh/BinderBase.git/master


## Credits
This project is created with:  
[![Binder](http://mybinder.org/badge_logo.svg)](http://beta.mybinder.org/v2/gh/binder-examples/requirements/master)
