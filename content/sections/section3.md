---
title: Contests
weight: 4

---
## Active Games

{{< rawhtml >}}

<head>

<meta name="viewport" content="width=device-width, initial-scale=1">

<style>

p {

text-align: center;

margin-top: 0px;

}

\#demo {

font-size: 15px;

line-height: 50px;

text-indent: 20px;

}

\#city {

font-size: 20px;

line-height: 50px;

text-indent: 0px;

}

\#freeSeats {

font-size: 20px;

line-height: 50px;

text-indent: 0px;

}

\#boxNew{

display: flex;

flex-flow: row nowrap;

justify-content: center;

align-content: center;

align-items:center;

}

.itemNew{

flex: 1 1 auto;

}

.center {

margin-left: auto;

margin-right: auto;

}

td {

padding: 0 50px;

}

tr {

font-size: 35 px;

line-height: 50px;

text-indent: 20px;

}

</style>

</head>

<body>

<table class="center">

<tr>

    <th>CITY</th>
    
    <th>NFT DROP</th>
    
    <th>AVAILABLE PLAYERS</th>

</tr>

<tr>

    <td>Berlin</td>
    
    <td id = "demo"></td>
    
    <td>50</td>

</tr>

<tr>

    <td>Madrid</td>
    
    <td>Coming soon</td>
    
    <td>50</td>

</tr>

<tr>

    <td>Paris</td>
    
    <td>Coming soon</td>
    
    <td>50</td>

</tr>

</table>

<script>

// Set the date we're counting down to

var countDownDate = new Date("Jan 5, 2022 15:37:25").getTime();

// Update the count down every 1 second

var x = setInterval(function() {

// Get today's date and time

var now = new Date().getTime();

// Find the distance between now and the count down date

var distance = countDownDate - now;

// Time calculations for days, hours, minutes and seconds

var days = Math.floor(distance / (1000 * 60 * 60 * 24));

var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));

var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));

var seconds = Math.floor((distance % (1000 * 60)) / 1000);

// Output the result in an element with id="demo"

document.getElementById("demo").innerHTML = days + "d " + hours + "h "

* minutes + "m " + seconds + "s ";

// If the count down is over, write some text

if (distance < 0) {

    clearInterval(x);
    
    document.getElementById("demo").innerHTML = "EXPIRED";

}

}, 1000);

</script>

</body>

{{< /rawhtml >}}

| Markdown | Less | Pretty |
| --- | --- | --- |
| Still | renders | nicely |
| 1 | 2 |  |

#### Contact Start Bootstrap

Feel free to leave us a comment on the [Grayscale template Github page](https://github.com/runningstream/hugograyscale/) to give some feedback about this theme!

{{< socialhandles >}}
{{< twitter user="stream_running" >}}
{{< github user="runningstream" >}}
{{< /socialhandles >}}

{{< rawhtml >}}

<script>

document.getElementsByClassName('nav-item')\[3\].remove()

</script>

{{< /rawhtml >}}