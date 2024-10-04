#### MVP

1. Home page

   - when app starts request user location permission

   - Display a list of stores
     Get location from user using geolocation library[var location = {
     latitude,
     longitude
     }]
     request Mapbox api to get list of stores neaby location
     store list format
     | StoreName | Address | DistanceFromUser(calculate using geolocation) |
     | --------------- | --------------- | --------------- |
     | Item1.1 | Item2.1 | Item3.1 |
   - add search bar to filter the list

2. Store details screen

   - when clicked on a store name navigate to store details page
   - details like name address, contact, opening hours, and description
   - add option to call the user in native caller

3. Map integration

   - view on map takes user to map screen
   - use google maps or flutter_maps(personal preference)

4. Database management
   - store list of store in local database (use sqflite(personal preference)/hive)
   - Include atleast 5 store samples
