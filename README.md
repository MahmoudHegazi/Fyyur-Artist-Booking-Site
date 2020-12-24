# Fyyur-Artist-Booking-Site


# programming languages and libraries:
Python3, JavaScript, SQL, jinja2, SQLalchemy,  Relational Database: PostgreSQL

# front-end
HTML5, CSS3, W3.css, JavaScript, ES6, AJAX, grid, flexbox

# Database and connection:
1. ```code app.secret_key = 'S&Djry636qyye21777346%%^&&&#^$^^y___' ```
2. 2 tables Band, Event


# Advanced Features
1. search feature (AJAX with KeyUp fast) you do not need a button to search
*. search can check for all recoreds even it's a band or event without even tell it  the search know what to do
2. Pure AI pagination created from scratch it has some math advanced logic
3. Free Advanced GRID Game Created 1 day before from that project The game Lightweight and none canvas 
* the game has good story and goal and good game
4. Notifications System never miss any event or error with friendly UX message
5. Due to relational Database You Can Direct Delete Band You have to deleted it's events My App handle this easy Error
6. Error Handling And Fast performance and care of fast and advanced search IT like Google and Better in only it has no Button

# packeges:
1. flask
3. flask_sqlalchemy
4. datetime
5. requests
6. os
7. sys
8. sqlalchemy
9. text
10. string



# What You Need To Start:
1. you have to download virtualbox and vagrant install them and start your server
2. if you are using Linux/Mac, escap this step, else Download GitBash for Windows Users
3. Clone the project, unzip it, run vagrant init, vagrant up, and vagrant ssh, If you have problem in this step use my vagrantfile included
4. make sure to use pip3 and python3, and install all packges 

# Notes While Use it:
1. Make sure to add many Events and Many band small help to make it fast 
*. (if you submited a band you can go back and will find the old data you can duplicate this action better 30 band and 30 event for text 
*. which is very good feature pagination)
2. Make sure to add All data in any form to be able to see the template in prefect way and compelete features
3. there are 2 lists for bands one without pagination effect but still has the links for it and one use full pagination and limit 9 only


# What App Can DO:
1. if you started the APP you Will start it in Admin Mode which give you full Controll to the web app not like public user
2. you can add new Band, Edit Band, Delete Band, and Read all Bands, Search For Band, and do the same for events
3. each Band Can add unlimited events connected to it, and apears in it's page


# app Routes:
```python
@app.route('/search_ajax', methods=['POST'])

@app.route('/golden_arrow', methods=['GET'])

@app.route('/event/<int:event_id>', methods=['GET','POST'])

@app.route('/edit_band/<int:band_id>', methods=['GET','POST'])

@app.route('/submit_edit', methods=['POST'])

@app.route('/edit_event/<int:event_id>', methods=['GET','POST'])

@app.route('/submit_edit/event', methods=['POST'])

@app.route('/band/<int:band_id>', methods=['GET','POST'])

@app.route('/remove_band/<int:band_id>', methods=['GET','POST'])

@app.route('/remove_event/<int:event_id>', methods=['GET','POST'])

@app.route('/bandlist', methods=['GET','POST'])

@app.route('/band_list/page/<int:request_start>', methods=['GET','POST'])

@app.route('/event_list/page/<int:request_start>', methods=['GET','POST'])

@app.route('/home')

@app.route('/')

@app.route('/addevent', methods=['GET', 'POST'])

@app.route('/add_band', methods=['GET','POST'])

```


<img src="/static/app.JPG">
