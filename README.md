![Alt](https://cdn.discordapp.com/attachments/283757952186449920/1108152594662174730/image.png)

# accuenergy_OA

### Technologies

- Javascript
- VueJs
- TailwindCSS
- Google Maps Javascript API

# To Run Project

1. (optional) create a `.env` file with the google maps api.

```
REACT_APP_MAP_API="API_KEY"
```

2. Install NPM packages

   > npm install

3. Run the client
   > npm run dev

### Features

1.  Ability to acquire the current location of the user using `navigator.geolocation.getCurrentPosition`
2.  Displays the current location and centers the map based on the current location
3.  Search module that parses the user's inputs. Search is triggered by keypress (ENTER) or clicking on the `Search` button
    1. A search history that lists all searched items.
    2. Checkbox for deleting searched places.
    3. A detailed and dynamic pagination system that returns 10 entries.
    4. Returns the local time of the latest search item.
4.  Integration with Google Maps API for displaying searched items.
    1. Markers are placed based on the pagination results of the searched items.

### Possible Improvements

1. Use a better API for parsing Search queries.
2. Update the map to show text or dynamic information based on the location that is searched for.
3. Responsiveness for all brower sizes
4. Unit / Integration testing
5. Backend for storing or aggregating data
6. User Profiles and Authentication
7. Improved Error Handling
