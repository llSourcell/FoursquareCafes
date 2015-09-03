# Foursquare cafes
- Gets user’s current Latitude and longitude via CLLocationManager
- Send HTTP request  with current-location for FourSquare API and parse the json file asynchronously.
- Ability to call coffee shop
- 2 views in 1! 

--UITableView : to show the shops near user’s current location.
--MapView : graphically show user’s locations and shops nenear by.


————things to need to be refined next version———
* Code structure needs to be improved such as adding more isolation functions for better testing.
* Call out MKAnnotationView can be customised to show the shops pictures as FourSquare API do  provide the image links for some shops
* validate the phone number 
* use shared Application to pass the address and open Apple/Google map for navigation
--------Screen Shots--------

<img src="https://cloud.githubusercontent.com/assets/7435852/6040429/dc260702-acc5-11e4-8f43-0591bbc5f9a0.jpg" alt="screen shot">

<img src="https://cloud.githubusercontent.com/assets/7435852/6040428/dbb4470c-acc5-11e4-95a1-0064d97d86e2.jpg" alt="screen shot">
