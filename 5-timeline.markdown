---
layout: page
title: Timeline
nav_order: 6
permalink: /timeline/
---

  <head>
<script type="text/javascript" src="https://www.gstatic.com/charts/loader.js"></script>

<script type="text/javascript">
  google.charts.load("current", {packages:["timeline"]});
  google.charts.setOnLoadCallback(drawChart);
  function drawChart() {
    var container = document.getElementById('example4.2');
    var chart = new google.visualization.Timeline(container);
    var dataTable = new google.visualization.DataTable();

    dataTable.addColumn({ type: 'string', id: 'Role' });
    dataTable.addColumn({ type: 'string', id: 'Name' });
    dataTable.addColumn({ type: 'date', id: 'Start' });
    dataTable.addColumn({ type: 'date', id: 'End' });
    dataTable.addRows([
      [ 'Diary', 'A Prairie as Wide as the Sea', new Date(1926, 5, 1), new Date(1927, 4, 18)]]);

    var options = {
      timeline: { groupByRowLabel: false, colorByRowLabel: true}
    };
    var options = {
      colors: ['#edb800'],
    };

    chart.draw(dataTable, options);
  }
</script>

<div id="example4.2" style="height: 200px;"></div>
  </head>
  <body>
    <div id="timeline" style="height: 180px;"></div>
  </body>

  <p>More coming soon...</p>

