---
layout: page
title: Map
permalink: /map/
nav-order: 5
---
  <head>
    <script type="text/javascript" src="https://www.gstatic.com/charts/loader.js"></script>
    <script type="text/javascript">
      google.charts.load('current', {
        'packages':['geochart'],
        'mapsApiKey': 'AIzaSyBnhctFPZgzxpPKjdpIHvJYYjgIX7yaPTI'
"
      });
      google.charts.setOnLoadCallback(drawRegionsMap);
      function drawRegionsMap() {
        var data = google.visualization.arrayToDataTable([
          ['Country'],
          ['England'],
          ['UK']
        ]);
        var options = {};
        var chart = new google.visualization.GeoChart(document.getElementById('regions_div'));
        chart.draw(data, options);
      }
    </script>
  </head>
  <body>
    <div id="regions_div" style="width: 900px; height: 500px;"></div>
  </body>

<p>Coming soon, I'm still trying to figure this part out...</p>

<img src="/images/under construction.jpg"> 
