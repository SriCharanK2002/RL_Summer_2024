This repo contains code files pertaining to practical component of the summer course Reinforcement Learning in the summer of 2024

Before starting of with the code of your labs, It is recemmend you to create a virtual environment and install the required packages.

Creating a virtual environment is simple enough with VS Code or Anaconda, but if you are using a terminal, you can use the following commands:
1. Install virtualenv using pip:<br>
```pip install virtualenv```
2. Create a virtual environment:<br>
``` python<version> -m venv <virtual-environment-name>```

3. Activate the virtual environment:<br>
```source <virtual-environment-name>/bin/activate``` (for linux)<br>
```<virtual-environment-name>\Scripts\activate``` (for windows)<br>

In place of version, it better to add the version of python you are using. For example, if you are using python 3.8, the command would be:
``` python3.8 -m venv <virtual-environment-name>```

Once you created the virtual environment and activated it, you can install the required packages using the following command:<br>
```pip install -r requirements.txt```