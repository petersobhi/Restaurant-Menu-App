# Restuarant Menu App
Udacity Full Stack Web Developer Nanodegree project

### Requirements

* [Python 2.x](https://www.python.org/)
* [Flask](http://flask.pocoo.org/)

### Installation
download  or clone the repo:
```sh
$ git clone https://github.com/petersobhi/Restaurant-Menu-App.git
```
* run ```database_setup.py``` to configure the database.
* run ```lotsofmenus.py``` to add dummy data to the database.
* run the ```project.py```.
* navigate to ```http://localhost:5000``` to use the web app

### API Endpints
currently there are 3 API Endpoints you can use
| Method | Endpoint                                        | Usage                                    | Returns     |
|:------:|-------------------------------------------------|------------------------------------------|:-----------:|
| GET    | /restaurant/JSON                                | Get all the restaurants                  | Restaurants |
| GET    | /restaurant/{restaurant_id}/menu/JSON           | Get menu items of a restaurant           | Menu items  |
| GET    | /restaurant/{restaurant_id}/menu/{menu_id}/JSON | Get a specific menu item of a restaurant | Menu item   |
