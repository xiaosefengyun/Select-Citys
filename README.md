# select-city

This is an updated version of LArea, from the national administrative division of China.

***

How to use

>import css and javascript

```
    <link rel="stylesheet" href="css/LArea.css">
    <script src="js/LAreaData1.js"></script>
    <script src="js/LArea.js"></script>
```

>Initialize with the following code

```javascript
 var area1 = new LArea();
    area1.init({
        'trigger': '#demo1', //Triggers the text box that selects the control, and selects the finished name attribute to output to that location
        'valueTo': '#value1', //Select the after id attribute to output to this location
        'keys': {
            id: 'id',
            name: 'name'
        }, //The correlation field id of the bound data source corresponds to valueTo's value property output name corresponding to trigger's value attribute output
        'type': 1, //Data source type
        'data': LAreaData //Data source
    });
    area1.value=[18,2,2];//Control the initial location, note: this method does not affect the value of the input
```

