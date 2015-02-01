# mysite
This is a version of the offical Django tutorial application configured for deployment into a production environment on Heroku.

At the moment this project is at the end of part 2 of the official Django tutorial.
https://docs.djangoproject.com/en/1.7/intro/tutorial02/

On to part 3!

# Getting started
Start your DAD virtual environment.
```
& $Env:WORKON_HOME\DAD\Scripts\activate.ps1
```
Change to your project directory
```
cd $Env:PROJECT_HOME\DAD
```
Then clone this repository.  
```
git clone git@github.com:usma-it394/mysite.git
```

Change your current working directory to the clone'd project directory.
```
cd mysite
```
Install the packages from requirements.txt (you probably already have these installed in your DAD environment):
```
pip install -r requirements.txt
```

Then set the DATABASE_URL environment variable. Finally, create the initial database structure with:
```
python manage.py syncdb
```
