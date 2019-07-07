# Find My Parking
![MIT Licence](https://img.shields.io/github/license/mashape/apistatus.svg)
![Swift](https://img.shields.io/badge/Swift-5.0-orange.svg)
![Platform](https://img.shields.io/badge/Platform-iOS-green.svg)

## Introduction

**Find My Parking** helps user to find parking pole location in Montreal, Canada.

## Preview
![menu](images/menu.gif)
![home_screen](images/french.gif)
![share_screen](images/history.gif)
![french_support](images/info.gif)
![search_history](images/search.gif)

## Download

<a target='_blank' href='https://itunes.apple.com/us/app/find-my-parking/id1459821681?ls=1&mt=8'>
<img src='images/download.jpg' />
</a>

## Features

1. Created `Auto Layout` UI and animation programmatically (No Storyboard)
2. Request for user location with `CoreLocation` and shows it on `MapView` with `MapKit`
3. Search parking pole data (open-source and provided by [Stationnement de Montréal](https://www.statdemtl.qc.ca/fr/informations/donnees-ouvertes/description-des-donnees-disponibles.html)) from a `SQLite` database with [FMDB](https://github.com/ccgus/fmdb) library, and show result on MapView with `MapKit Annotations`
4. Implemented `UIView` Constraint Animation along with `UISwipeGestureRecongizer`
5. Intergrated a confetti animation with `CAEmitterLayer`
6. Customized `UICollectionView` with `UIViewPropertyAnimator` and customized `Flow Layout` to achieve a blur effect animation
7. `UITableView` with customized cell
8. Implemented `Delegation Pattern` and blocks to achieve communication between classes
9. Multiple language support: English, French and Chinese
10. Search History would be saved automatically and show on the map when selected
11. Display user current facing direction
12. Analyze user behaviour with `Google Analytics`, e.g. touch/share event
