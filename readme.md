### LIBRARIES
- LEAFLET JavaScript library for mobilefriendly interactive maps .
- REACT React is a JavaScript library for building user interfaces .
- MOMENT Parse,validate,manipulate and display dates in javascript .

[![N|Solid](http://leafletjs.com/docs/images/logo.png)](https://nodesource.com/products/nsolid)
its a JavaScript mapping library


[![N|Solid](https://react.parts/react-logo.svg)](https://nodesource.com/products/nsolid)
its a javascript library in MVC


[![N|Solid](http://jquery-plugins.net/image/plugin/moment-js.jpg)](https://nodesource.com/products/nsolid)
its a javascript library so that it would be easier to work with an object


### EXAMPLES OF THE LIBRARIES
- LEAFLET = leaflet on mobile
```For the css =
body {
    padding: 0;
    margin: 0;
}
html, body, #map {
    height: 100vh;
    width: 100vw;
}

For the html =
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />

For the javascript =
var map = L.map('map').fitWorld();

L.tileLayer('https://api.tiles.mapbox.com/v4/MapID/997/256/{z}/{x}/{y}.png?access_token={accessToken}', {
    attribution: 'Map data &copy; <a href="http://openstreetmap.org">OpenStreetMap</a> contributors, <a href="http://creativecommons.org/licenses/by-sa/2.0/">CC-BY-SA</a>, Imagery © <a href="http://mapbox.com">Mapbox</a>',
    maxZoom: 18
}).addTo(map);
```
- REACT = react navigation menu
 ```For the html =
 <script src="http://fb.me/react-0.10.0.min.js"></script>


For the javascript =
var MenuExample = React.createClass({

    getInitialState: function(){
        return { focused: 0 };
    },

    clicked: function(index){

        // The click handler will update the state with
        // the index of the focused menu entry

        this.setState({focused: index});
    },

 ```
- MOMENT = moment in node.js
``` For the html =
<html>
  <head>
    <title>in a Moment.js</title>
  </head>

  <body>
    <h1>Moment.js here now: <span id="then" data-date="Sat Mar 24 2012 08:42:14 GMT-0400 (EDT)"></span></h1>

    <script src="http://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.min.js"></script>
    <script src="/js/moment.js"></script>
    <script>
      $(document).ready(function(){
        var then = $('#then'),
            date = moment(new Date(then.attr('data-date'))),
            update = function(){
                       then.html(date.fromNow());
                     };

        update();
        setInterval(update, 60000);
      });
    </script>
  </body>

</html>

For the javascript =

// node:
var moment = require('moment');

moment().add('days', 2).fromNow();
// 'in 2 days'

moment().subtract('days', 2).fromNow();
// '2 days ago'

moment('November 1977').fromNow()
// '34 years ago'

moment().add('days', 2).calendar();
// 'Monday at 8:30 AM'

moment().subtract('days', 2).calendar();
// 'last Thursday at 8:30 AM'

moment('1977-08-20 14:29:00 UTC').format('MMM. d, YYYY');
// 'Aug. 5, 1977'

moment('1977-08-20 14:29:00 UTC').fromNow();
// 'il y a 35 années'
```
### WHEN ARE THEY BEST USED
 LEAFLET = its best used in displaying tiled web maps you can do it without even GIS background

 REACT = its best used when creating a large web applications because of its speed and simplicity

 MOMENT = its used when accessing all the date and time parsing and manipulation functionality

### PERSONAL RATING FOR EACH library

leaflet = Very Good
react = Very Good
moment = Very Good

why very good because their all very easy to use ive checked all three libraries and they all are fun to use

### Differences between Library and Framework

First ive got to tell you what is library and framework is

= framework: Some JavaScript libraries, such as YUI, are classified as frameworks since they exhibit full-stack capabilities and properties not found in general JavaScript libraries.[citation needed]

= Library: With the expanded demands for JavaScript, an easier means for programmers to develop such dynamic interfaces was needed. Thus, JavaScript libraries and JavaScript widget libraries were developed, allowing for developers to concentrate more upon more distinctive applications of Ajax. This has led to other companies and groups, such as Microsoft and Yahoo! developing their own JavaScript-based user interface libraries, which find their way into the web applications developed by these companies.

Some JavaScript libraries allow for easier integration of JavaScript with other web development technologies, such as CSS, PHP, Ruby, and Java. Many libraries include code to detect differences between runtime environments, and remove the need for applications to allow for such inconsistencies.

Almost all JavaScript libraries are released under either a copycenter or copyleft license to ensure license-free distribution, usage, and modification.

THE DIFFERENCES

The key difference between a library and a framework is “Inversion of Control”. When you call a method from a library, you are in control. But with a framework, the control is inverted: the framework calls you.
