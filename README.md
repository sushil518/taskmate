# taskmate
This is a todolist app

![image](https://user-images.githubusercontent.com/19988353/210066445-b0e31bdb-b8ec-4a6b-9ac2-43530588fe27.png)


### Setup


To get this repository, run the following command inside your git enabled terminal
```bash
$ git clone https://github.com/sushil518/django-todo-list-app.git
```


Once you have downloaded django, go to the cloned repo directory and run the following command

```bash
$ python manage.py makemigrations
```

This will create all the migrations file (database migrations) required to run this App.

Now, to apply this migrations run the following command
```bash
$ python manage.py migrate
```



Now let's make the App live. We just need to start the server now and then we can start using our simple todo App. Start the server by following command

```bash
$ python manage.py runserver
```

Once the server is hosted, head over to http://127.0.0.1:8000 for the App.

