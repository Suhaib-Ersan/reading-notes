# Read: 07 - HTML Tables; JS Constructor Functions

## HTML Tables

### What is a table?

An HTML table is a way to represent information, usually in a grid format similar to how a spreadsheet works.
Example:

<br/>

![Table](https://res.cloudinary.com/practicaldev/image/fetch/s--Zhu5E2Bm--/c_imagga_scale,f_auto,fl_progressive,h_900,q_auto,w_1600/https://dev-to-uploads.s3.amazonaws.com/i/02lxssgxrwv7ywp2lhix.jpg)

<br>

To create them we would use a few elements, like:
- `<table>`, which is used to create a table, then the content is written row by row.

- `<tr>`, which is the start of a new row, and it stands for table row.

- `<td>`, this is the element that's used to write each cell, which stands for table data.

- `<th>` is similar to `<td>` but is used to write in headings, either in the columns or the rows, `<th>` helps people who use screen readers to read your page, also helps search engines in finding what's important in the page.

Browsers deal with tables differently, some automatically draw lines around the table and/or the cells, some don't.

## JS Constructor Functions

You can create objects using the `new` keyword with the object constructor to create a blank object,
Example:

```
var car = new Object();
```

To add properties and methods, you'd have to add them using dot notations, example:

```
car.name = 'kia';
car.price = 3000;
car.originalPrice = 12000;
car.lostValue = function () {
    return this.originalPrice - this.price;
}
```

You can also update objects, using the same dot notations, example:

```
car.name = 'honda';
```

This will change the var from 'kia' to 'honda'.
You could also use the brackets way, example:

```
car['name'] = 'honda';
```

But this way doesn't work with methods.

### Creating many objects

Using the constructor notation, you could create multiple objects using a function as a template for those objects.

first, you'll create the function that will serve as a template:

```
function Hotel (name, rooms, booked) {
    this.name = name;
    this.rooms = rooms;
    this.booked = booked;

    this.checkAvailability = function() {
        return this.rooms - this.booked;
    }
}
```
###### example from Jon Duckett JS book

Then using this function, we can create object easily, example :

```
var quayHotel = new Hotel('Quay', 40, 25);
var parkHotel = new Hotel('Park', 120, 77);
```
###### example from Jon Duckett JS book

This will create two new objects, one named quayHotel and one named parkHotel, with different values to their properties.
For example, quayHotel will have it's name be 'Quay', and it's rooms number be 40 rooms, 25 of which are booked.



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
| **read07** | **HTML Tables; JS Constructor Functions** |
| read08 | [More CSS Layout](https://suhaib-ersan.github.io/reading-notes/201/read08) |
| read09 | [Forms and JS Events](https://suhaib-ersan.github.io/reading-notes/201/read09) |
| read10 | [Debugging](https://suhaib-ersan.github.io/reading-notes/201/read10) |
| read11 | [Audio, Video, Images](https://suhaib-ersan.github.io/reading-notes/201/read11) |
| read12 | [Docs for the HTML <canvas> Element & Chart.js](https://suhaib-ersan.github.io/reading-notes/201/read12) |
| read13 | [](https://suhaib-ersan.github.io/reading-notes/201/read13) |
| read14 | [](https://suhaib-ersan.github.io/reading-notes/201/read14) |
| read15 | [](https://suhaib-ersan.github.io/reading-notes/201/read15) |