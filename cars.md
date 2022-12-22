---
layout: post
title: Cars
description: Our car inventory
# image: /assets/images/blue-3.png
image: /assets/images/chevrolet-cruze.jpg
nav-menu: true
---
<style>
	/* Important stuff for this demo. */

img {
  width: 100%;
  height: auto;
  vertical-align: middle;
}

.pics_in_a_row {
  display: flex;
}

.img1 { flex: 1.3344; }
.img2 { flex: 1.3345; }
.img3 { flex: 0.7505; }
.img4 { flex: 2; }
.img5 { flex: 2; }



/* Aaaand just some general styling. */

*, *:before, *:after {
  box-sizing: border-box;
}


.container {
  background: #242943;
  margin: 0 auto;
  padding: 5%;
  width: 75%;
}

h1 {
  margin-top: 0;
}

/*h2 {
  font-weight: normal;
  font-size: 19px;
  margin-bottom: 30px;
}
*/
.muted {
  font-style: italic;
  color: #666;
}

p, li {
  line-height: 1.5
}

li {
  margin-bottom: 7px;
}

p + p {
  margin-top: -7px;
}

code {
  background: #eee;
  padding: 2px 5px;
  font-size: 90%;
  border: 1px solid #ccc;
  border-radius: 4px;
  margin: 0 2px;
}

.pics_in_a_row {
  margin: 25px 0;
}

.pics_in_a_row > div:not(:last-child) {
  margin-right: 2%;
}
</style>
<h2 id="content">About</h2>
<p>Our used car lot is stocked with a wide variety of brands and models, all at affordable prices. Our team of professional salesmen are here to help you find the perfect vehicle to fit your needs and budget.

We understand that buying a used cae can be stressful, which is why we go above and beyond to ensure that each and every vehicle on our lot is in excellent condition. All of our cars are thoroughly inspected and tested before they go on sale, so you can buy with confidence.
</p>

<p align = "center">
<a href="purchase-form.html	" class="button special">Purchase your car</a>
</p>

<h2>Our Inventory:</h2>
<hr>
<div class='container'>
 <div class="column">
  <div class='pics_in_a_row'>
    <div class='img4'>
      <img src='/assets/images/chevrolet-cruze.jpg'>
      <h3>About:</h3>
		<p>Car Name: 2012 Chevrolet Cruze<br></p>
		<p>Mileage: 30 mpg<br></p>
		<p>Current Miles: 7,000 miles<br></p>
		<p>Price: $21,500<br></p>
    </div>
    <div class='img5'>
      <img src='/assets/images/nissan-altima.jpg'>
      <h3>About:</h3>
		<p>Car Name: 2014 Nissan Altima<br></p>
		<p>Mileage: 27-37 mpg<br></p>
		<p>Current Miles: 12,421 miles<br></p>
		<p>Price: $18,216<br></p>
    </div>
  </div>
</div>
<div class="column">
  <div class='pics_in_a_row'>
    <div class='img4'>
      <img src='/assets/images/ford-fusion.webp'>
      <h3>About:</h3>
		<p>Car Name: 2010 Ford Fusion<br></p>
		<p>Mileage: 22-31 mpg<br></p>
		<p>Current Miles: 16,212 miles<br></p>
		<p>Price: $34,252<br></p>
    </div>
    <div class='img5'>
      <img src='/assets/images/subaru-outback.jpg'>
      <h3>About:</h3>
		<p>Car Name: 2016 Subaru Outback<br></p>
		<p>Mileage: 20-32 mpg<br></p>
		<p>Current Miles: 8,122 miles<br></p>
		<p>Price: $36,920<br></p>
    </div>
  </div>
</div>
<div class="column">
  <div class='pics_in_a_row'>
    <div class='img4'>
      <img src='/assets/images/mazda-3.jpg'>
      <h3>About:</h3>
		<p>Car Name: 2018 Mazda 3<br></p>
		<p>Mileage: 28-38 mpg<br></p>
		<p>Current Miles: 6,129 miles<br></p>
		<p>Price: $35,560<br></p>
    </div>
    <div class='img5'>
      <img src='/assets/images/kia-optima.jpg'>
      <h3>About:</h3>
		<p>Car Name: 2020 Kia Optima<br></p>
		<p>Mileage: 27-37 mpg<br></p>
		<p>Current Miles: 3,125 miles<br></p>
		<p>Price: $44,390<br></p>
    </div>
  </div>
</div>
<div class='pics_in_a_row'>
    <div class='img4'>
      <img src='/assets/images/hyundai-sonata.jpg'>
     <h3>About:</h3>
		<p>Car Name: 2021 Hyundai Sonata<br></p>
		<p>Mileage: 28-38 mpg<br></p>
		<p>Current Miles: 1,231 miles<br></p>
		<p>Price: $42,595<br></p>
    </div>
    <div class='img5'>
      <img src='/assets/images/honda-civic.jpg'>
      <h3>About:</h3>
		<p>Car Name: 2002 Honda Civic<br></p>
		<p>Mileage: 26-34 mpg<br></p>
		<p>Current Miles: 20,246 miles<br></p>
		<p>Price: $10,500<br></p>
    </div>
  </div>
  <div class='pics_in_a_row'>
    <div class='img4'>
      <img src='/assets/images/toyota-camry.jpg'>
     <h3>About:</h3>
		<p>Car Name: 2006 Toyota Camry<br></p>
		<p>Mileage: 24-34 mpg<br></p>
		<p>Current Miles: 13,502 miles<br></p>
		<p>Price: $18,895<br></p>
    </div>
    <div class='img5'>
          <img src='/assets/images/audi-q5.jpg'>
      <h3>About:</h3>
		<p>Car Name: 2019 Audi Q5<br></p>
		<p>Mileage: 22-27 mpg<br></p>
		<p>Current Miles: 9,231 miles<br></p>
		<p>Price: $34,850<br></p>
    </div>
  </div>

</div>

<p align = "center">
<a href="purchase-form.html	" class="button special">Purchase your car</a>
</p>

