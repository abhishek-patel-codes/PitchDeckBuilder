### Features

- "Blog" section to create and edit a blog + Blog Category
- "Videocast" section to create and edit a videocast + Videocast Category
- "Podcast" section to create and edit a podcast + podcast Category
- "Skill" section to create and edit a skill
- "CONSTANCE" Section to manage dynamic Django settings (Blog title, Social Networks links and ...)
- Displays the list of Blog posts as paged in archive
- Displays the list of Videocast as paged in archive
- Displays the list of podcast as paged in archive
- Used "Django Admin" to manage all models
- Used "Editorial" theme by HTML5 UP
- Used "Sqlite" to create DB
- Used "CKEditor"
- Translation ready
- Auth system (login & logout and forget a password)
- Front-end forms to create new object
------------
- You can buy me a coffee so I can turn it into more open source projects :)
------------
### Special Thanks

| Python | Django | Pycharm |
| ------------- | ------------- | ------------- |

------------
### Screenshots

2. Create a development environment ready by using these commands
```
git clone https://github.com/mavenium/PyEditorial		# clone the project
cd PyEditorial		                                        # go to the project DIR
virtualenv -p python3 .venv		                        # Create virtualenv named .venv
source .venv/bin/activate		                        # Active virtualenv named .venv
pip install -r requirements.txt		                        # Install project requirements in .venv
python manage.py makemigrations		                        # Create migrations files
python manage.py migrate		                        # Create database tables
python manage.py collectstatic		                        # Create statics files
python manage.py runserver		                        # Run the project
```
3. Go to  `http://127.0.0.1:8000/` to use project
------------
------------
### Run with Docker

1. Install Docker on your operating system
2. Install docker-compose on your operating system
3. Run the following command to create and run the project
```
docker-compose up [-d]
```
3. Go to  `http://127.0.0.1:80/` or just type `localhost` in your browser to use project
------------

### Notes
The Editorial template is released under license "Creative Commons Attribution 3.0 Unported".

------------
### TODO list

- [x] Create search section
- [x] Create user Login/Logout forms in front-end
- [x] Create dynamic forms to add contents in front-end
