# Ex.07 Restaurant Website
## Date:

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>TastyBite Restaurant</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Georgia, serif;
}

/* Background */
body{
background:linear-gradient(to right,#e0f7ff,#ffe6ff);
}

/* Navbar */
.nav{
width:100%;
padding:20px 60px;
display:flex;
justify-content:flex-end;
gap:30px;
position:fixed;
top:0;
background:rgba(0,0,0,0.3);
backdrop-filter:blur(6px);
}

.nav a{
color:white;
text-decoration:none;
font-weight:bold;
}

.nav a:hover{
color:#ffd700;
}

/******** HOME *********/
#home{
padding:150px 100px;
color:#7b0018;
}

#home h1{
font-size:60px;
}

/* Offer Box */
.offer{
background:#19b7ce;
width:340px;
padding:20px;
border-radius:10px;
box-shadow:0 0 10px gray;
color:white;
margin-top:30px;
text-align:center;
}

/******** MENU *********/
.section-title{
text-align:center;
margin-top:40px;
font-size:35px;
color:#7b0018;
}

.menu-box{
display:flex;
justify-content:center;
gap:25px;
padding:40px;
flex-wrap:wrap;
}

.card{
background:#eebbcd;
width:220px;
padding:12px;
border-radius:10px;
text-align:center;
}

.card img{
width:100%;
height:140px;
border-radius:10px;
}

.card h3{
margin-top:10px;
}

/******** TEAM *********/
.team-box{
display:flex;
justify-content:center;
gap:30px;
flex-wrap:wrap;
padding:40px;
}

.member{
background:#cda5d3;
width:230px;
padding:15px;
border-radius:12px;
text-align:center;
}

.member img{
width:130px;
height:130px;
border-radius:50%;
}

/******** CONTACT *********/
.contact{
width:430px;
background:white;
margin:30px auto;
padding:20px;
border-radius:10px;
text-align:center;
}

/******** FOOTER *********/
footer{
text-align:center;
padding:10px;
color:white;
background:black;
margin-top:30px;
}
</style>
</head>

<body>

<!-- NAVIGATION -->
<div class="nav">
<a href="#home">HOME</a>
<a href="#menu">MENU</a>
<a href="#team">TEAM</a>
<a href="#contact">CONTACT</a>
</div>

<!-- HOME -->
<section id="home">
<h1>Welcome to The Royal Spoon</h1>
<p style="margin-top:10px;">Fresh • Delicious • Served with Love</p>

<div class="offer">
<h2>Weekend Offer</h2>
<p>Flat 40% OFF on Burgers & Pizza</p>
</div>
</section>

<!-- MENU -->
<h1 class="section-title" id="menu">Our Menu</h1>

<div class="menu-box">

<div class="card">
<img src="https://th.bing.com/th/id/OIP.mrfxfslC8OHWhK6pLHHVMQHaHa?w=212&h=204&c=7&r=0&o=7&dpr=1.3&pid=1.7&rm=3">
<h3>Burger ₹120</h3>
<p>Juicy & Tasty</p>
</div>

<div class="card">
<img src="https://th.bing.com/th/id/OIP.N_lo-uI7txMqPQlMgUATcwHaE8?w=221&h=185&c=7&r=0&o=7&dpr=1.3&pid=1.7&rm=3">
<h3>Pizza ₹199</h3>
<p>Cheesy Delight</p>
</div>

<div class="card">
<img src="https://th.bing.com/th/id/OIP.jA-PSfzX6QxEvmRrTVfJgQHaF7?w=229&h=183&c=7&r=0&o=7&dpr=1.3&pid=1.7&rm=3">
<h3>Fried Chicken ₹250</h3>
<p>Spicy & Crispy</p>
</div>

<div class="card">
<img src="https://th.bing.com/th/id/OIP.UoM0EgqRvycfbwVCnxgdrQHaEo?w=282&h=180&c=7&r=0&o=7&dpr=1.3&pid=1.7&rm=3">
<h3>Ice Cream ₹99</h3>
<p>Sweet Happiness</p>
</div>

</div>

<!-- TEAM -->
<h1 class="section-title" id="team">Our Team</h1>

<div class="team-box">

<div class="member">
<img src="https://th.bing.com/th/id/OIP.x4zDlrC1oOeECS_jEQOCSAHaHa?w=162&h=180&c=7&r=0&o=7&dpr=1.3&pid=1.7&rm=3">
<h3>Rohan</h3>
<p>Head Chef</p>
</div>

<div class="member">
<img src="https://th.bing.com/th/id/OIP.fozI4oLgRNlMyOKID3H_jwHaFc?w=253&h=186&c=7&r=0&o=7&dpr=1.3&pid=1.7&rm=3">
<h3>Ananya</h3>
<p>Manager</p>
</div>

<div class="member">
<img src="https://th.bing.com/th/id/OIP.QdVKgEN7zLZ61_npuHAESAHaHa?w=142&h=186&c=7&r=0&o=7&dpr=1.3&pid=1.7&rm=3">
<h3>Arjun</h3>
<p>Customer Care</p>
</div>

</div>

<!-- CONTACT -->
<h1 class="section-title" id="contact">Contact Us</h1>

<div class="contact">
<p><b>Phone:</b> 9876543210</p>
<p><b>Email:</b> tastybite@gmail.com</p>
<p><b>Address:</b> City Center, India</p>
</div>

<footer>
© 2025 TastyBite Restaurant
</footer>

</body>
</html>
```

## OUTPUT:
<img width="1919" height="984" alt="image" src="https://github.com/user-attachments/assets/55008139-bc76-42df-aae7-8d40e95d286a" />


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
