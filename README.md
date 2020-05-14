# Project Demo

-   [Light Menu](#light-menu) (iPadOS, Core Data, Django, Wireless Print)
-   [Find My Parking](#find-my-parking) (Available on App Store)
-   [Restaurant Mobile Order Solution](#restaurant-mobile-order-solution) (Push Notification, Google Cloud Functions)

# Light Menu

![Platform](https://img.shields.io/badge/Platform-iOS-green.svg)

![preview](/asset/light-menu/light_menu_preview.jpg)

**Light Menu** helps restaurant to place order faster.

_[**Video Demo**](https://vimeo.com/336508045)_

## Screenshots

<img src="asset/light-menu/home.png" width="50%"><img src="asset/light-menu/search_customer.png" width="50%"><img src="asset/light-menu/transactions.png" width="50%"><img src="asset/light-menu/menu.png" width="50%"><img src="asset/light-menu/django_main_list.png" width="50%"><img src="asset/light-menu/django_sushi_list.png" width="50%"><img src="asset/light-menu/django_edit_sushi.png" width="50%"><img src="asset/light-menu/firebase_database.png" width="50%">

## Features

_Full-stack project, including `iPad` for mobile, `Django` for web and api, `Firebase` for backend and `PostgreSQL` for database._

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

# Find My Parking

![Swift](https://img.shields.io/badge/Swift-5.0-orange.svg)
![Platform](https://img.shields.io/badge/Platform-iOS-orange.svg)

**Find My Parking** helps user to find parking pole and parking meter location in Montréal, Canada.

Available on `App Store`

<a target='_blank' href='https://itunes.apple.com/us/app/find-my-parking/id1459821681?ls=1&mt=8'>
<img src='asset/find-my-parking/app-store-download.png' />
</a>

⬇️ Scan via iPhone's camera to open in App Store to download

<img src='asset/find-my-parking/qrcode.png'  width="160" height="200"/>

## Demo

### Version 2.4

-   Add callout view to show paid period

![callout](asset/find-my-parking/callout.gif)

### Version 2.1

-   Adapted `iOS 13` Dark Mode

![dark_mode](asset/find-my-parking/darkmode.gif)

### Version 2.0

-   Integrated Core Data
-   Add Parking Meter search

![search](asset/find-my-parking/center.gif)
![swipe](asset/find-my-parking/searchsort.gif)
![parkingmeters](asset/find-my-parking/parking.gif)

### Version 1.0

![menu](asset/find-my-parking/menu.gif)
![home_screen](asset/find-my-parking/french.gif)
![french_support](asset/find-my-parking/info.gif)
![search_history](asset/find-my-parking/search.gif)
![search_history](asset/find-my-parking/cluster.gif)

## App Store Preview

![design](asset/find-my-parking/design.png)

## Features

1. Created `Auto Layout` UI and animation programmatically (no storyboard)
2. Adapted to `iOS 13` Dark Mode
3. Request for user location with `CoreLocation` and shows it on `MapView` with `MapKit`
4. Search parking pole and nearby parking meters from open-source data provided by [Stationnement de Montréal](https://www.statdemtl.qc.ca/fr/informations/donnees-ouvertes/description-des-donnees-disponibles.html), and show result on MapView with `MapKit Annotations`, including `clustering`
5. Store persistant data with `Core Data`
6. Intergrated a confetti animation with `CAEmitterLayer`
7. Customized `UICollectionView` with `UIViewPropertyAnimator` and customized `Flow Layout` to achieve a blur effect animation
8. `UITableView` and `UICollectionView` with customized cell
9. Implemented `Delegation Pattern`
10. Multiple language support: English, French and Chinese
11. Display user current facing direction

# Restaurant Mobile Order Solution

**Restaurant Mobile Order Solution** is a simplified UberEats-like app, including a client-side app and a restaurant-side app. Both sides will receive Notification when order status changes.

## Features

1. Written in `Swift` with `Auto Layout` UI programmatically
2. Integrated `Push Notification` feature via [Firebase Cloud Messaging](https://firebase.google.com/docs/cloud-messaging)
3. Deployed two [Cloud Function](https://firebase.google.com/docs/functions) to monitor data (order status) change, written in `Node.js`
4. Customized nested `UICollectionView`

## Demo

▶️ [**Video Demo**](https://vimeo.com/384440813)

### Screenshots

##### iPhone ⬇️

![demo](asset/restaurant-solution/demo.gif)

<img src='asset/restaurant-solution/home.png' width="20%"><img src='asset/restaurant-solution/login.png' width="20%"><img src='asset/restaurant-solution/signup.png' width="20%"><img src='asset/restaurant-solution/menu.png' width="20%"><img src='asset/restaurant-solution/orders.png' width="20%"><img src='asset/restaurant-solution/order_detail.png' width="20%"><img src='asset/restaurant-solution/account.png' width="20%"><img src='asset/restaurant-solution/bag.png' width="20%">

##### iPad (Split View) ⬇️

<img src='asset/restaurant-solution/ipad.png' width="90%">
