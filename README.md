# Home Assignment - Frontend Engineer

We developers often have to convert data between different formats. For example CSV to JSON and vice versa. Let’s write an app for this!

Follow these tasks:
1. Use the latest [Create React App](https://create-react-app.dev/) to set up a React project
2. Add two text areas with the following behavior:
    1. The user can paste CSV files (with header line) into the left text area
    2. If the user presses a button labeled “CSV → JSON”, the CSV is converted into JSON data and displayed in the right text area
3. Add a second button labeled “CSV ← JSON”, if it is pressed the JSON data in the right text area is converted to CSV and displayed in the left text area.
4. Add a button labeled "Geolookup". If the button is pressed a Geocode lookup API of choice is called. It takes the address for each entry and adds the latitude and longtitude values to the CSV and JSON representation of each entry.
5. Add another feature of your choice that you would like to see in this app


> Note: You can use Material UI or plain HTML/CSS. Don’t use a library to do the CSV/JSON conversion. 

For testing you can use, the following test data:

CSV file:
```
Name,Address,Company
Marcus,"Schloßstraße 17, 98547 Kühndorf, Germany",Apple Inc.
John,"Tropical-Islands-Allee 1, 15910 Krausnick, Germany",IKEA Furnitures
David,"Am Rheinufer 2, 65366 Geisenheim, Germany",Nokia Communications
```

JSON file:
```
[
{“name”: “Marcus”, “address”: “Schloßstraße 17, 98547 Kühndorf, Germany”, “company”: “Apple
Inc.”},
{“name”: “John”, “address”: “Tropical-Islands-Allee 1, 15910 Krausnick, Germany”, “company”: “IKEA
Furniture”},
{“name”: “David”, “address”: “Am Rheinufer 2, 65366 Geisenheim, Germany”, “company”: “Nokia
Communications”}
]
```

> Note: The solution should work with any CSV and JSON files. This is just an example.






