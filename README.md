# Web Application Exercise

## Product vision statement

Our product aims to provide information and purchase functions to consumers who would like to make a purchase at our bakery, while also increasing profits with intentional marketing through its design.


## User stories

- As a user, I want to be able to view item information, so that I know what the item tastes like.
- As a user, I want to be able to view common allergens, so that I can make safe purchases.
- As a user, I want to be able to select items and place them in my shopping cart, so that I can collect the goods that I want to buy.
- As a user, I want to be able to search for specific items using keywords, so that I can find what I am looking for efficiently.
- As a user, I want to be able to view my shopping cart, so that I see what items I have currently listed.
- As a user, I want to be able to delete order history, so that I can keep my orders secret so I can surprise my friends with baked goods without them knowing.
- As a user, I want to be able to view my order history, so that I can keep track of the purchases I made with this bakery.
- As a user, I want to be able to contact the bakery, so that I can file complaints.
- As a user, I want to be able to view what the item looks like, so I know what to expect.
- As a user, I want to be able to remove items from my shopping cart, so I don’t have to buy items I changed my mind about.
- As a user, I want to be able to view items by category, so that I have an easier time searching through the menu.
- As a user, I want to be able to specify whether my order is for pickup or delivery, so that I can use the appropriate delivery method.
- As a user, I want to be able to enter my credit card information, so I can pay directly through the website.
- As a user, I want to see the subtotal in the cart, so that I know how much my order is as I add items.
- As a user, I want to be able to get lists of what items the bakery has, so I can see what items are available
- As a user, I want to indicate the name on the purchase, so the bakery knows who it is for.
- As a user, I want to view calorie information, so I can keep track of my daily calories.
- As a user, I want to be able to enter a shipping address, so the bakery can ship my goods to the correct location.



## Steps necessary to run the software


1. First, clone the respository:

```
git clone https://github.com/software-students-spring2025/2-web-app-ducklings.git
```
2. Then change directories into the repository:

```
cd 2-web-app-ducklings
```

### Mac

3. Set up virtual environment


```
python3 -m venv venv
```


4. Activate environment


```
source venv/bin/activate
```

5. Enter app

```
cd app/
```

6. Install dependencies


```
pip install -r requirements.txt
```


7. Set Flask app environment variable


```
export FLASK_APP=app.py
```

8. Start MongoDB

```
brew install mongodb-community@6.0
brew services start mongodb-community@6.0
```

9. Set Mongo URI

```
export MONGO_URI='mongodb://localhost:27017/anatidelicious'
```

10. Run App

```
python -m flask run
```

11. Open page at http://127.0.0.1:5000


### Windows

3. Set up virtual environment


```
py -m venv .venv
```


4. Activate environment


```
.venv\Scripts\activate
```


5. Install pip + dependencies


```
py -m pip install --upgrade pip
py -m pip install requests
```


6. Install pymongo


```
pip install pymongo
```


7. Install Flask


```
pip install Flask
set FLASK_APP=app.py
```


8. Install MongoDB Community version via the zip file on the MongoDB official website


9. Go to app


```
cd 2-web-app-ducklings\app
```


10. Set Mongo URI


```
set MONGO_URI='mongodb://localhost:27017/anatidelicious'
```


11. Install other additions


```
pip install flask_pymongo
pip install flask_session
pip install dotenv
```


12. Run


```
flask run
```

13. Open page at http://127.0.0.1:5000



## Task boards

[Task Board Sprint 1 Link](https://github.com/orgs/software-students-spring2025/projects/10/)

[Task Board Sprint 2 Link](https://github.com/orgs/software-students-spring2025/projects/73/)
