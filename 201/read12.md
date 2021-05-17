# Docs for the HTML <canvas> Element & Chart.js

## Chart.js

Charts are great tools to display information in a more readable (and often much better looking) way. ALso charts are often better than showing the data in a table.
And a great way to make charts in JavaScript is what's called `Charts.js`, which is an open source plugin that uses HTML5's built-in `<canvas>` element to draw charts. It's a pretty well-known plugin, and because of that it has a lot of support, and is well documented.  

There are two ways to use it, first one is by downloading it and then use the JS file it provides, and the second one is simply using that same JS file, just through a web URL instead of using the file directly.

First you need to add a `<canvas>` tag to your HTML and give it an ID. Then you need to reference the `Chart.js` file, usually at the end of your `<body>` tag, but before any script that would use it.

it'd look something like this:

```
<body>
    <canvas id="myChart" width="400" height="400"></canvas>

    <script script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <script src="app.js"></script>
</body>
```

Now you open `app.js` or add a script tag after our `Chart.js` reference, and copy a demo code from the `Chart.js` docs and paste it there.

It'll look something like:

```
var ctx = document.getElementById('myChart').getContext('2d');
var myChart = new Chart(ctx, {
    type: 'bar',
    data: {
        labels: ['Red', 'Blue', 'Yellow', 'Green', 'Purple', 'Orange'],
        datasets: [{
            label: '# of Votes',
            data: [12, 19, 3, 5, 2, 3],
            backgroundColor: [
                'rgba(255, 99, 132, 0.2)',
                'rgba(54, 162, 235, 0.2)',
                'rgba(255, 206, 86, 0.2)',
                'rgba(75, 192, 192, 0.2)',
                'rgba(153, 102, 255, 0.2)',
                'rgba(255, 159, 64, 0.2)'
            ],
            borderColor: [
                'rgba(255, 99, 132, 1)',
                'rgba(54, 162, 235, 1)',
                'rgba(255, 206, 86, 1)',
                'rgba(75, 192, 192, 1)',
                'rgba(153, 102, 255, 1)',
                'rgba(255, 159, 64, 1)'
            ],
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
```

This code should give you a Chart that looks similar to this:
<br />

<img src="https://i.imgur.com/4gdIXjP.png" width="400px" alt="barChart">

<br />

And then change the values to whatever you want, and you have a basic great looking chart.

You can also do a line, pie, doughnut and others.

And they look pretty nice:

<img src="https://i.imgur.com/Xb17DBT.png" width="50%" alt="PieChart"><img src="https://i.imgur.com/GZaIaBL.png" width="50%" alt="DoughnutChart">


## Canvas

The `<canvas>` element is an HTML5 element, meaning it's relatively new.
> At first sight a `<canvas>` looks like the `<img>` element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the `<canvas>` element has only two attributes, width and height. These are both optional and can also be set using DOM properties. When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high. The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvas, it will appear distorted.
> -MDN Web Docs















<br/><br/> 
<br/><br/>  



|201| [Go back Home](https://suhaib-ersan.github.io/reading-notes/) |
|-|-|
| read## | Name and Link |
| read01 | [Introductory HTML and JavaScript](https://suhaib-ersan.github.io/reading-notes/201/read01) |
| read02 | [HTML Text, CSS Introduction, and Basic JavaScript Instructions](https://suhaib-ersan.github.io/reading-notes/201/read02) |
| read03 | [HTML Lists, CSS Boxes, JS Control Flow](https://suhaib-ersan.github.io/reading-notes/201/read03) |
| read04 | [HTML Links, CSS Layout, JS Functions](https://suhaib-ersan.github.io/reading-notes/201/read04) |
| read05 | [HTML Images; CSS Color & Text](https://suhaib-ersan.github.io/reading-notes/201/read05) |
| read06 | [JS Object Literals; The DOM](https://suhaib-ersan.github.io/reading-notes/201/read06) |
| read07 | [HTML Tables; JS Constructor Functions](https://suhaib-ersan.github.io/reading-notes/201/read07) |
| read08 | [More CSS Layout](https://suhaib-ersan.github.io/reading-notes/201/read08) |
| read09 | [Forms and JS Events](https://suhaib-ersan.github.io/reading-notes/201/read09) |
| read10 | [Debugging](https://suhaib-ersan.github.io/reading-notes/201/read10) |
| read11 | [Audio, Video, Images](https://suhaib-ersan.github.io/reading-notes/201/read11) |
| read12 | [Docs for the HTML <canvas> Element & Chart.js](https://suhaib-ersan.github.io/reading-notes/201/read12) |
| read13 | [](https://suhaib-ersan.github.io/reading-notes/201/read13) |
| read14 | [](https://suhaib-ersan.github.io/reading-notes/201/read14) |
| read15 | [](https://suhaib-ersan.github.io/reading-notes/201/read15) |