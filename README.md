# MyTest Project

## Setup

### Update the System
To ensure your system is up to date, run the following command:
```sh
sudo apt-get update
***Clone the Repository
To get this repository, run the following command inside your Git-enabled terminal:


git clone https://github.com/Theogene-dotcom/mytest.git

Install Django
You will need Django to be installed on your computer to run this app. Head over to Django's official website for the download guide.

###Download Django Using pip
First, install pip if you haven't already:


sudo apt install python3-pip -y
Then, install Django:


***pip install django***
Setup the Project
Once you have downloaded Django, go to the cloned repository directory and run the following command to generate a requirements.txt file:


pip freeze > requirements.txt
Create Migrations
To create all the migration files (database migrations) required to run this app, run:

***Bold and Italic***
[Link Text](https://www.example.com)

python3 manage.py makemigrations
Apply Migrations
To apply these migrations, run:


python3 manage.py migrate
Create an Admin User
We need to create an admin user to run this app. On the terminal, type the following command and provide a username, password, and email for the admin user:


python3 manage.py createsuperuser
Start the Server
Now let's make the app live. Start the server by running:


python3 manage.py runserver
Once the server is hosted, head over to http://127.0.0.1:8000/mytest to access the app.

Cheers and Happy Coding :)
