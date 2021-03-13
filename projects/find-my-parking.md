# Find My Parking

![Swift](https://img.shields.io/badge/Swift-5.0-orange.svg)
![Platform](https://img.shields.io/badge/Platform-iOS-orange.svg)

**Find My Parking** helps user to find parking pole and parking meter location in Montréal, Canada.

<a target='_blank' href='https://itunes.apple.com/us/app/find-my-parking/id1459821681?ls=1&mt=8'>
<img src='../asset/find-my-parking/app-store-download.png' />
</a>

⬇️ Scan via iPhone's camera to open in App Store to download

<img src='../asset/find-my-parking/qrcode.png'  width="160" height="200"/>

## Demo

### Version 2.4

-   Add callout view to show paid period

![callout](../asset/find-my-parking/callout.gif)

### Version 2.1

-   Adapted `iOS 13` Dark Mode

![dark_mode](../asset/find-my-parking/darkmode.gif)

### Version 2.0

-   Integrated Core Data
-   Add Parking Meter search

![search](../asset/find-my-parking/center.gif)
![swipe](../asset/find-my-parking/searchsort.gif)
![parkingmeters](../asset/find-my-parking/parking.gif)

### Version 1.0

![menu](../asset/find-my-parking/menu.gif)
![home_screen](../asset/find-my-parking/french.gif)
![french_support](../asset/find-my-parking/info.gif)
![search_history](../asset/find-my-parking/search.gif)
![search_history](../asset/find-my-parking/cluster.gif)

## App Store Preview

![design](../asset/find-my-parking/design.png)

## Features

1. Created `Auto Layout` UI and animation programmatically (no storyboard)
2. Adapted to `iOS 13` Dark Mode
3. Request for user location with `CoreLocation` and shows it on `MapView` with `MapKit`
4. Search parking pole and nearby parking meters from open-source data provided by [Stationnement de Montréal](https://www.statdemtl.qc.ca/fr/informations/donnees-ouvertes/description-des-donnees-disponibles.html), and show result on MapView with `MapKit Annotations`, including `clustering`
5. Store persistent data with `Core Data`
6. Integrated a confetti animation with `CAEmitterLayer`
7. Customized `UICollectionView` with `UIViewPropertyAnimator` and customized `Flow Layout` to achieve a blur effect animation
8. `UITableView` and `UICollectionView` with customized cell
9. Implemented `Delegation Pattern`
10. Multiple language support: English, French and Chinese
11. Display user current facing direction
