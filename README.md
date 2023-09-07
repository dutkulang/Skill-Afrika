# Skill-Afrika
ALX end of foundations project

![site review](preview_assets/Screenshot%20from%202023-09-06%2017-50-26.png)

![](preview_assets/Screenshot%20from%202023-09-06%2019-06-43.png)

---
## How to setup
 
`Python 3 > version 3.8 must be installed on your system`

1. clone the repo from my link

2. change into the directory created from either terminal or git bash

3. install virtual environment 

    ```sh
    pip3 install virtualenv; virtualenv myenv ; source myenv/bin/activate
    ```

 4. pip install -r requirements.txt

 5. Make and run migrations, then create super user

 ```sh
 python3 manage.py makemigrations ; python3 manage.py migrate ;
 python3 manage.py createsuperuser
 ```

 6. run server

 ```sh
python3 manage.py runserver 
 ```

 7. visit [local host](http://localhost:8000)