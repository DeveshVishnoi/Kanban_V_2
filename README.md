<!-- @format -->

# Kanban-Board π

This project is an implementation of a Kanban Board created in Vuejs.

# Local Setup

- Make sure you have the necessary requirements installed and updated, mentioned in the requirements.txt file. If not, just to be sure, go to terminal and run command `pip install -r requirements.txt`.

# Local Development Run

- Simply run `npm install` , it will initiate the node app in development for create `node modules` file
- then run `npm run dev` then your link will be generated
- for api simply run `main.py` file using command in termina is `python main.py`



# Folder Structure

- `root` has the `kanaban.sqlite3` DB.
- `application` has the all python files.
- `src` has all the Vue  files in component folder.

```

β   main.py
β   kanaban.sqlite3
β   readme.md
|   models.py
β
|
β
ββββapplication
|        |
|        api.py
|        database.py
|        flask_celery.py
|        jwt_setup.py
|        mail_sent.py
|        models.py
|        task.py
|        worker.py
|
|
|
β
ββββsrc--
|     |__components
        β       add_cards.vue
        β       list_details.vue
        β       user_details.vue
        β       navbar.vue
        β       login.vue
        β       navbar_with_dash.vue
        β       summary.vue
        |       updatecards.vue
        |       updateList.vue
|       APp.vue
β
|      main.js
|      router.js
ββββ    
      static
      |_______Images
                    all_images
        
```
