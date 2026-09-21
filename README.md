### Features
- Django LTS
- Funtion Based
- User authentication
- Responsive Design
- Bootstrap5



### Setup
To get this repository, run the following command inside your git enabled terminal
```bash
git clone git@github.com:mohsenmostafavi/Django_FBV_Todo.git
```

### Getting ready
Create an enviroment in order to keep the repo dependencies seperated from your local machine.
```bash
python -m venv venv
```

Make sure to install the dependencies of the project through the requirements.txt file.
```bash
pip install -r requirements.txt
```

Once you have installed django and other packages, go to the cloned repo directory and run the following command

```bash
python manage.py makemigrations
```

This will create all the migrations file (database migrations) required to run this App.

Now, to apply this migrations run the following command
```bash
python manage.py migrate
```

### options
Project it self has the user creation form but still in order to use the admin you need to create a super user.you can use the createsuperuser option to make a super user.
```bash
python manage.py createsuperuser
```

And lastly let's make the App run. We just need to start the server now and then we can start using our simple todo App. Start the server by following command

```bash
python manage.py runserver
```

Once the server is up and running, head over to http://127.0.0.1:8000 for the App.

### Database schema
A simple view of the project model schema.
<p align="center">
<img src="https://user-images.githubusercontent.com/29748439/134964183-595bd7cf-df01-4089-8d22-bfb765d62c18.png" alt="database schema" width="300"/>
</p>

### Todo
- [ ] leave comments for codes
- [ ] add unit tests
- [ ] add heroku config files
- [ ] complete the documentation
- [ ] create a video tutorial

### Bugs or Opinion
Feel free to let me know if there are any problems or any request you have for this repo.