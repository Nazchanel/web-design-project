---
layout: post
title: Reserve
description: Reserve A Car
image: /assets/images/grocery-cart.png
nav-menu: true
---

<style>
	.comment {
		resize: none;
		height: 200px;
		width: 500px;
	}
	.comment1 {
		height: 50px;
		width: 500px;
	}
</style>

<form action="https://submit-form.com/kPfVw0BD" method="POST">
	<label for="name">Car Model</label><div class="field half first">
		<input type="checkbox" id="2012 Chevrolet Cruze" name="car-selection" value="2012 Chevrolet Cruze" >
		<label for="2012 Chevrolet Cruze">2012 Chevrolet Cruze ($21,500)</label>
		<br>
		<br>
		<input type="checkbox" id="2014 Nissan Altima" name="car-selection" value="2014 Nissan Altima" >
		<label for="2014 Nissan Altima">2014 Nissan Altima ($18,216)</label>
		<br>
		<br>
		<input type="checkbox" id="2010 Ford Fusion" name="car-selection" value="2010 Ford Fusion" >
		<label for="2010 Ford Fusion">2010 Ford Fusion ($34,252)</label>
		<br>
		<br>
		<input type="checkbox" id="2018 Subaru Outback" name="car-selection" value="2018 Subaru Outback" >
		<label for="2018 Subaru Outback">2018 Subaru Outback ($35,560)</label>
		<br>
		<br>
		<input type="checkbox" id="2020 Kia Optima" name="car-selection" value="2020 Kia Optima" >
		<label for="2020 Kia Optima">2020 Kia Optima ($44,390)</label>
		<br>
		<br>
		<input type="checkbox" id="2021 Hyndai Sonata" name="car-selection" value="2021 Hyndai Sonata" >
		<label for="2021 Hyndai Sonata">2021 Hyndai Sonata ($42,595)</label>
		<br>
		<br>
		<input type="checkbox" id="2002 Honda Civic" name="car-selection" value="2002 Honda Civic" >
		<label for="2002 Honda Civic">2002 Honda Civic ($10,500)</label>
		<br>
		<br>
		<input type="checkbox" id="2006 Toyota Camry" name="car-selection" value="2006 Toyota Camry" >
		<label for="2006 Toyota Camry">2006 Toyota Camry ($18,895)</label>
		<br>
		<br>
		<input type="checkbox" id="2019 Audi Q5" name="car-selection" value="2019 Audi Q5" >
		<label for="2019 Audi Q5">2019 Audi Q5 ($29,850)</label>
		<br>
		<br>
		<input type="checkbox" id="2018 Mazda 3" name="car-selection" value="2018 Mazda 3" >
		<label for="2018 Mazda 3">2018 Mazda 3 ($34,850)</label>
	</div>

<div class="field half first">
<label for="name">Name</label>
<input type="text" name="name" id="name" />
<br>

<label for="email">Email</label>
<input type="email" name="email" id="email" />
<br>
<label for="phone">Phone Number</label>
<input type="tel" name="phone" maxlength="14" minlength="7" placeholder="(123) 456-7890"  class="comment1">
<br>
<label for="appointment-time">Choose Appointment Time:</label>

<select name="appointment-time" id="appointment-time" class="comment1">
  <option value="12-1">12PM to 1PM</option>
  <option value="2-3">2PM to 3PM</option>
  <option value="3-4">3PM to 4PM</option>
  <option value="4-5">4PM to 5PM</option>
</select>
<br>
	<label for="message">Comments</label>

<textarea
id="message"
name="message"
placeholder="Message"

class = comment
>

</textarea>
</div>

<ul class="actions">
	<li>
		<input type="submit" value="Reserve" class="special" />
	</li>
	<li>
		<input type="reset" value="Clear" />
	</li>
</ul>

</form>