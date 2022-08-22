# Daniel's Blog

This is a blog built entirely from scratch with flask following a tutorial. I wrote almost the codes with the help of documentation of new libraries, stack overflow and previous knowledge.

Still a long way to go though

### You can check out the live website [here](https://daniels-blog-project.herokuapp.com)

## To run it locally on your machine

### Clone the Repo
Fork the repository and clone it to your machine using 
```
git clone https://github.com/DanAdewole/My-Blog.git
```


### Change directory
Change directory to where you cloned the repository
```
cd My-Blog
```

### Create a virtual eenvironment in the Project level folder
Run this command while in the My-Blog directory to create a virtualenvironment called venv
```virtualenv venv
```

### Activate the Environement
To activate the environment, run this command
```
venv\scripts\activate
```

### Install all Dependencies
To install all packages needed for the app to work, run this command
```
pip install -r requirements.txt
```

### Insert random secret key
Make use of [Djecrety](https://djecrety.ir/) to generate your secret key.
On line 18 in the main.py file, there is 
```app.config['SECRET_KEY']```, replace the ```os.environ.get("SECRET_KEY")``` with secret key generated from djecrety

### Run the Program
Depending on your IDE, go to the main.py file and run the main.py file