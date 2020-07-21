# Star Social
This is a social networking website focused to foster conversations for space enthusiasts. A user can get registered, join the groups of their interest and read/post articles of their interest. Because there is very less clutter, I believe that this webspace will lead to more meaningful conversations about space

# Installation
Firstly, you can select a text editor to run your code. I personally prefer Atom Text Editor since it has a lot of easy tools to construct and deploy your code. You can download Atom [here](https://atom.io/).
Then, you can install the Miniconda version onto your computer from [here](https://docs.conda.io/en/latest/miniconda.html)
Then, once you open Atom, open the terminal, create a virtual environment with Django with the following command:
```bash
conda create --name myEnv python=3.8
```
where **MyEnv** is the name of the virtual environment 
You can activate your virtual environment with
```bash
activate MyEnv
```
Now, lets install django with this command:
```bash
conda install django
```

# Usage
In the terminal, navigate into the folder where you downloaded the _simplesocial_ folder. Using the following command, you can start the server using the following command:
```bash
python manage.py runserver
```
You might get some commands that might say a module is missing - **_modulename_ not found**. Then, you can install the module with this command:
```bash
pip install modulename
```
If that fails, try:
```bash
pip install django-modulename
```
Once you install all the necessary modules, you will be able to run the server successfully and you will see something like this:

![runserver](https://github.com/nitinkondiparthi/simplesocial/blob/master/runserver.PNG)

Then, copy the link to the clipboard and paste it into your web browser and you'll see something like this
