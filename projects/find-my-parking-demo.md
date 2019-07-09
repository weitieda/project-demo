# Find My Parking
![MIT Licence](https://img.shields.io/github/license/mashape/apistatus.svg)
![Swift](https://img.shields.io/badge/Swift-5.0-orange.svg)
![Platform](https://img.shields.io/badge/Platform-iOS-green.svg)

**Find My Parking** helps user to find parking pole location in Montreal, Canada.

Available for download at `App Store`:

<a target='_blank' href='https://itunes.apple.com/us/app/find-my-parking/id1459821681?ls=1&mt=8'>
<img src='../asset/find-my-parking/app-store-download.png' />
</a>

## Preview
![menu](../asset/find-my-parking/menu.gif)
![home_screen](../asset/find-my-parking/french.gif)
![share_screen](../asset/find-my-parking/history.gif)
![french_support](../asset/find-my-parking/info.gif)
![search_history](../asset/find-my-parking/search.gif)

# Design
![design](../asset/find-my-parking/design.png)

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
13. Customized `MKAnnotationView`