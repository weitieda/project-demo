# Find My Parking
![MIT Licence](https://img.shields.io/github/license/mashape/apistatus.svg)
![Swift](https://img.shields.io/badge/Swift-5.0-orange.svg)
![Platform](https://img.shields.io/badge/Platform-iOS-green.svg)

## Introduction

**Find My Parking** helps user to find parking pole location in Montreal, Canada.

## Preview
![menu](https://i.loli.net/2019/06/15/5d0426e734e2542915.gif)
![home_screen](https://i.loli.net/2019/05/01/5cc915425f77c.gif)
![share_screen](https://i.loli.net/2019/05/01/5cc9160bbdb87.gif)
![french_support](https://i.loli.net/2019/05/01/5cc916e2e317d.gif)
![search_history](https://i.loli.net/2019/05/12/5cd7582a376a9.gif)

# Design
![design](https://github.com/weitieda/find-my-parking-demo/blob/master/images/design.png)

## Download

<a target='_blank' href='https://itunes.apple.com/us/app/find-my-parking/id1459821681?ls=1&mt=8'>
<img src='https://i.loli.net/2019/04/20/5cba21ac64d13.jpg' />
</a>

## Features

1. Created `Auto Layout` UI and animation programmatically (No Storyboard)
1. Request for user location with `CoreLocation` and shows it on `MapView` with `MapKit`
1. Search parking pole data (open-source and provided by [Stationnement de Montréal](https://www.statdemtl.qc.ca/fr/informations/donnees-ouvertes/description-des-donnees-disponibles.html)) from a `SQLite` database with [FMDB](https://github.com/ccgus/fmdb) library, and show result on MapView with `MapKit Annotations`
1. Implemented `UIView` Constraint Animation along with `UISwipeGestureRecongizer`
1. Intergrated a confetti animation with `CAEmitterLayer`
1. Customized `UICollectionView` with `UIViewPropertyAnimator` and customized `Flow Layout` to achieve a blur effect animation
1. `UITableView` with customized cell
1. Implemented `Delegation Pattern` and blocks to achieve communication between classes
1. Multiple language support: English, French and Chinese
1. Search History would be saved automatically and show on the map when selected
1. Display user current facing direction
1. Analyze user behaviour with `Google Analytics`, e.g. touch/share event
