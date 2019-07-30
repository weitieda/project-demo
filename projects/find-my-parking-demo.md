# Find My Parking

![Swift](https://img.shields.io/badge/Swift-5.0-orange.svg)
![Platform](https://img.shields.io/badge/Platform-iOS-orange.svg)

**Find My Parking** helps user to find parking pole location in Montréal, Canada.

Available for download at `App Store`

<a target='_blank' href='https://itunes.apple.com/us/app/find-my-parking/id1459821681?ls=1&mt=8'>
<img src='../asset/find-my-parking/app-store-download.png' />
</a>

## Demo

#### Version 2.0

![search](../asset/find-my-parking/search2.gif)
![swipe](../asset/find-my-parking/swipe_delete.gif)
![parkingmeters](../asset/find-my-parking/parking_meters.gif)

#### Version 1.0

![menu](../asset/find-my-parking/menu.gif)
![home_screen](../asset/find-my-parking/french.gif)
![share_screen](../asset/find-my-parking/history.gif)
![french_support](../asset/find-my-parking/info.gif)
![search_history](../asset/find-my-parking/search.gif)
![search_history](../asset/find-my-parking/cluster.gif)

## Preview

![design](../asset/find-my-parking/design.png)

## Features

1. Created `Auto Layout` UI and animation programmatically (no storyboard)
2. Request for user location with `CoreLocation` and shows it on `MapView` with `MapKit`
3. Search parking pole and nearby parking meters from open-source data provided by [Stationnement de Montréal](https://www.statdemtl.qc.ca/fr/informations/donnees-ouvertes/description-des-donnees-disponibles.html)), and show result on MapView with `MapKit Annotations`, including `clustering`
4. Store persistant data with `Core Data`
5. Intergrated a confetti animation with `CAEmitterLayer`
6. Customized `UICollectionView` with `UIViewPropertyAnimator` and customized `Flow Layout` to achieve a blur effect animation
7. `UITableView` and `UICollectionView` with customized cell
8. Implemented `Delegation Pattern`
9. Multiple language support: English, French and Chinese
10. Display user current facing direction

---

<a href="mailto:hi@tiedawei.com"><img src="https://img.shields.io/badge/Contact-suc.svg?style=for-the-badge&logo=minutemailer&logoColor=white"></a>&nbsp;&nbsp;&nbsp;
