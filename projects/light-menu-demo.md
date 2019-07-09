# Light Menu
![Platform](https://img.shields.io/badge/Platform-iOS-green.svg)

![preview](/asset/light-menu/light_menu_preview.jpg)

**Light Menu** helps restaurant to place order faster

*[Video Demo](https://vimeo.com/336508045)*


## Screenshots
<img src="../asset/light-menu/home.png" width="50%"><img src="../asset/light-menu/search_customer.png" width="50%"><img src="../asset/light-menu/transactions.png" width="50%"><img src="../asset/light-menu/menu.png" width="50%"><img src="../asset/light-menu/django_main_list.png" width="50%"><img src="../asset/light-menu/django_sushi_list.png" width="50%"><img src="../asset/light-menu/django_edit_sushi.png" width="50%"><img src="../asset/light-menu/firebase_database.png" width="50%">

## Features
*Full-stack project, including `iPad` for mobile, `Django` for web and api, `Firebase` for backend and `PostgreSQL` for database.*

**iPad**

1. Written in `Swift` with `Auto Layout` UI programmatically
2. Print receipt wirelessly via thermal printer, connected with `Socket`
3. Store transactions with `Core Data`
4. Customized `UICollectionView` and `UITableView` 
5. Show customer location and calculated driving distance with `MapKit` and `Core Location`
6. `JSON` parsing
7. `UIView` animation for sliding menu
8. Search and create new customer through `Firebase` real-time databse

**Django**

1. Deployed on [Heroku](https://tranquil-reaches-33843.herokuapp.com), intergrated with 2 api endpoint [category](https://tranquil-reaches-33843.herokuapp.com/api/category/) and [menu data](https://tranquil-reaches-33843.herokuapp.com/api/items/)
2. Connected with `ElephantSQL`, a cloud `PostgreSQL` database
3. Implemented `Django Admin`, which allows restaurant to login and CRUD sushi menu data
