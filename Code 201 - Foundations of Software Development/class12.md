# Class 12 Notes

## [JavaScript Canvas](https://www.javascripttutorial.net/web-apis/javascript-canvas/)

+ What does the `<canvas>` allow a developer to acheive? 

  + Allows you to draw 2D graphics like shapes or graphs 

+ What is the importance of the closing `</canvas>` tag? 

  + This content displays when the browser doesn’t support `<canvas>` elements 

+ Explain what the `getContext()` method does. 

  + It returns a render context object 

  + 1 argument - the type of context 

## [Chart.js Documentation](http://www.chartjs.org/docs/)

+ What is Chart.js and how can it be brought into your project? 

  + Chart library for JavaScript application developers 

  + By using the CDN link in a `<script>` and a `<canvas>` and chart object in JavaScript  

``` 
<div> 

  <canvas id="myChart"></canvas> 

</div> 

  

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script> 

  

<script> 

  const ctx = document.getElementById('myChart'); 

  

  new Chart(ctx, { 

    type: 'bar', 

    data: { 

      labels: ['Red', 'Blue', 'Yellow', 'Green', 'Purple', 'Orange'], 

      datasets: [{ 

        label: '# of Votes', 

        data: [12, 19, 3, 5, 2, 3], 

        borderWidth: 1 

      }] 

    }, 

    options: { 

      scales: { 

        y: { 

          beginAtZero: true 

        } 

      } 

    } 

  }); 
</script> 
``` 

+ List 3 different Chart types you can create using Chart.js. 

  + Bar chart 

  + Line chart 

  + Pie chart 

## [Easily Create Stunning Animated Charts with Chart.js](https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/)

+ What are some advantages to displaying data via a chart over a table? 

  + Charts display data like a table in more efficiently  

  + They allow you to understand the data quicker 

+ How could Chart.js aid your previously created applications visually? 

  + Charts would break up all the text and add more visually pleasing graphics  

## Things I want to know more about

+ How to get a horizonal bar graph
+ How to draw shapes
+ How to draw text

© Marco Villafana 201d93