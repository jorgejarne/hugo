---
title: Contests
weight: "4"

---
## Active Games

The games that are being played and the ones that are going to be played are shown below. Any news about new games will be published through our **Twitter page**.

The column **NFT Drop** indicates when the purchase of shares in Opensea is available

{{< rawhtml >}}

<head>

<meta name="viewport" content="width=device-width, initial-scale=1">

<style>

p {

text-align: center;

margin-top: 0px;

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

\#pruba1 {

    text-align: justify;

}

\# prueba2{

font-size: 1.5em;

border: 1px solid black;

padding: 10px;

width: 95%;

margin: 10px auto;

text-align: justify;

}

\#draft {

text-align: justify;

text-justify: inter-word;

}

</style>

</head>

<body>

<table class="center">

<tr>

    <th>CITY</th>
    
    <th>NFT DROP</th>

</tr>

<tr>

    <td>Berlin</td>
    
    <td id = "demo"></td>

</tr>

<tr>

    <td>Madrid</td>
    
    <td>Coming soon</td>

</tr>

<tr>

    <td>Paris</td>
    
    <td>Coming soon</td>

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