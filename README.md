# Ex.07 Restaurant Website
## Date:09.10.25

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
<html>
    <head>
        <title>Admin</title>
        <link rel="stylesheet" href="admin.css">
    </head>
    <body>
        <nav>
            <a  href="home.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Admin</a>
            <a href="contact.html">Contanct</a>
        </nav>
        <h1>Administration</h1>
        <div class="admin">
            <div class="a1">
                <img src="Screenshot (90).png">
                <b>Guhan</b>
                <p>CEO</p>
            </div>
            <div class="a2">
                <img src="9d4d7d545f482e6a8ccfc2d639699cf8.jpg">
                <b>Hrithik Roshan</b>
                <p>Reception</p>
            </div>
            <div class="a3">
                <img src="FPV6WrwVEAcYDtr.jpg">
                <b>Veera Raghavan</b>
                <p>Service Manager</p>
            </div>
            <div class="a4">
                <img src="Samantha_At_The_Irumbu_Thirai_Trailer_Launch.jpg">
                <b>Samantha</b>
                <p>Manager</p>
            </div>
            <div class="a5">
                <img src="2a0797046757029d961f00f3bf353229.jpg">
                <b>leo</b>
                <p>Accounts Manager</p>
            </div>
            <div class="a6">
                <img src="m.s.gandhi.jpg"
                <b>M.S.Gandhi</b>
                <p>Maintenance Manager</p>
            </div>
        </div>
        <footer>
            <h6 class="bottom">Guhan.K (25014479)</h6>
        </footer>
    </body>
</html>

<html>
    <head>
        <title>Contanct</title>
        <link rel="stylesheet" href="contact.css">
    </head>
    <body>
         <nav>
            <a  href="home.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Admin</a>
            <a href="contact.html">Contanct</a>
        </nav>
        <div class="contanct-container">
            <h1>Contact Us:</h1>
            <h4>Address:660, MV 60478, United Kingdom</h4>
            <h2>Phone no: +044-1234-1234</h2>
            <h3>Email:guhanrestaurant@gmail.com</h3>
        </div>
        <footer>
            <h6>Guhan.K (25014479)</h6>

        </footer>
    </body>
</html>

<html>
    <head>
        <title>Home</title>
        <link rel="stylesheet" href="home.css"> 
    </head>
    <body>
        <nav>
            <a  href="home.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Admin</a>
            <a href="contact.html">Contanct</a>
        </nav>
        <div class="name">
            <h1>GUHAN RESTAURANT</h1>
            <b>"Foof is our common ground, a universal experience"</b>
        </div>
        <div class="offer">
            <h2>Limited Offer</h2>
            <h3>50% off for all combos </h3>
        </div>
    
        <footer>
            <h6 class="bottom">Guhan.K (25014479)</h6>

        </footer>
    </body>
</html>

<html>
    <head>
        <title>Menu</title>
        <link rel="stylesheet" href="menu.css">
    </head>
    <body>
        <nav>
            <a  href="home.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Admin</a>
            <a href="contact.html">Contanct</a>
        </nav>
        <h1>Menu Lists</h1>
        <div class="main">
            <div class="food1">
                <img src="ai-generated-tcookie-plate-dessert-food-photo.jpg"alt="pic">
                <b>Dessert-$60</b>
            </div>
            <div class="food2">
                <img src="140430115517-06-comfort-foods.jpg" alt="pic">
                <b>Lazzania-$15</b>
            </div>
            <div class="food3">
                <img src="photo-1565299624946-b28f40a0ae38.jpg" alt="pic">
                <b>pizza-$50</b>
            </div>
            <div class="food4">
                <img src="Screenshot (99).png" alt="pic">
                <b>Burger-$60</b>
            </div>
            <div class="food5">
                <img src="Screenshot (100).png" alt="pic">
                <b>fried chicken-$30</b>
            </div>
            <div class="food6">
                <img src="images (1).jpg" alt="pic">
                <b>-Fish fry-$60</b>
            </div>
            <div class="food7">
                <img src="images.jpg" alt="pic">
                <b>Mint chicken-$60</b>
            </div>
            <div class="food8">
                <img src="tandoori.jpg" alt="pic">
                <b>Tandoori chicken-$50</b>
            </div>
            <div class="food9">
                <img src="hq720.jpg" alt="pic">
                <b>Curd chicken-$60</b>
            </div>
            <div class="food10">
                <img src="Sticky-Honey-Chicken.png" alt="pic">
                <b>Honey chicken-$60</b>
            </div>
            <div class="food11">
                <img src="Chicken-Biryani-Recipe.jpg" alt="pic">
                <b>-shrimp Skewers-$60</b>
            </div>
            <div class="food12">
                <img src="Spicy-Prawn-Roast-1-500x480.jpg" alt="pic">
                <b>prawn fry-$60</b>
            </div>
        </div>
         <footer>
            <h6 class="bottom">Guhan.K (25014479)</h6>

        </footer>
    </body>
</html>

home.css

body{
    background-image:url(tabletop-looking-out-empty-restaurant_23-2147701293.jpg);
    background-position: center;
    background-size: cover;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    color: rgb(253, 140, 3) ;
    background-repeat: no-repeat;
}

a{
    padding: 15px;
    color:rgb(214, 5, 190);
    position: relative;
    left: 1100px;
    top: 20px;
}
a:hover{
    background-color: rgb(57, 110, 147);
    color:blue;
}
.name{
    text-align: center;
    position: relative;
    left: 295px;
    top:20px;
    font-weight: bolder;
    font-family: 'Times New Roman', Times, serif;
    color:  rgb(75, 64, 118);
    font-size: 30px;
    width: 1000px;
   
}

.offer{
    text-align: right;
    font-size: 40px;
    color: rgb(252, 114, 114);
    position: relative;
    right: 100px;
    top:200px;

}
.bottom{
    font-size: 30px;
    text-align: center;
    position: relative;
    top: 190px;
    background-color: rgb(34, 3, 90);
}

contanct.css

body{
    background-image:url(contact.jpg);
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    font-size: 20px;
}

a{
    padding: 15px;
    color:rgb(166, 223, 253);
    position: relative;
    left: 1100px;
    top: 20px;
    font-size: 20px;
}
.bottom{
    font-size: 30px;
    text-align: center;
    background-color: rgba(181, 222, 14, 0.768);
    position: relative;
    top: 120px;
}
.contanct-container{
    font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    text-align: center;
    padding: 30px;
    
    height:400px;
    width:390px;
    display: block;
    gap: 20px;
    font-size: 20px;
    position: relative;
    left: 600px;
    top:20px;
    border-radius: 10%;
}
h2,h3,h4{
    font-size: 27px;
}

menu.css

body{
    
    background:url(Sticky-Honey-Chicken.png);
    background-repeat: no-repeat;
    background-position:center;
    background-size: cover;
    font-size: 20px;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    margin: auto;
}

a{
    padding: 15px;
    color:rgb(227, 144, 0);
    position: relative;
    left: 1100px;
    top: 20px;
}
.main{
    display: grid;
    grid-template-columns: repeat(5,1fr);
}
.food1{
    padding: 10px;
    background-color: rgba(218, 156, 64, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    bottom: 30px;
    left: 80px;
}
.food2{
    padding: 10px;
    background-color: rgba(218, 156, 64, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    bottom: 30px;
    left: 80px;
    
}
.food3{
    padding: 10px;
    background-color: rgba(218, 156, 64, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    bottom: 20px;
    left: 80px;
}
.food4{
    padding: 10px;
    background-color: rgba(218, 156, 64, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    bottom: 20px;
    left: 80px;
    
}
.food5{
    padding: 10px;
    background-color: rgba(218, 156, 64, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    bottom: 20px;
    
}
.food6{
    padding: 10px;
    background-color: rgba(218, 156, 64, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    
}
.food7{
    padding: 10px;
    background-color: rgba(218, 156, 64, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    
}
.food8{
    padding: 10px;
    background-color: rgba(218, 156, 64, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    
}
.food9{
    padding: 10px;
    background-color: rgba(218, 156, 64, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    
}
.food10{
    padding: 10px;
    background-color: rgba(218, 156, 64, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    
}
.food11{
    padding: 10px;
    background-color: rgba(218, 156, 64, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    top: 10px;
    
}
.food12{
    padding: 10px;
    background-color: rgba(218, 156, 64, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    top: 10px;
}
img{
    width: 170px;
    height: 100px;
    
}
h1{
    text-align: center;
    position: relative;
    bottom: 20px;
    left:600px;
    padding: 10px;
    background-color: rgba(107, 83, 32, 0.951);
    color: rgb(184, 170, 170);
    width:200px;
}
.bottom{
    font-size: 30px;
    text-align: center;
    background-color: brown;
    position: relative;
    top: 30px;
}

admin.css

body{
    background-image: url(tabletop-looking-out-empty-restaurant_23-2147701293.jpg);
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}
a{
    padding: 15px;
    color:rgb(145, 119, 4);
    position: relative;
    left: 1100px;
    top: 20px;
    font-size: 20px;
    font-size: x-large;
}
.admin{
    display: grid;
    grid-template-columns: repeat(6,1fr);
    font-size: 20px;
    gap:10px;
}
img{
    width: 210px;
    height: 300px;
    border:solid 5px rgb(240, 235, 235);
}
.a1,.a2,.a3,.a4,.a5,.a6{
    padding: 5px;
    background-color: antiquewhite;
    text-align: center;
    font-size: 24px;
    
}
.bottom{
    font-size: 30px;
    text-align: center;
    background-color: rgba(44, 35, 35, 0.632);
    position: relative;
    top: 60px;
    color:white;
}
h1{
    text-align: center;
    color:white;
    font-size: 40px;
}


```

## OUTPUT:
![alt text](<Screenshot 2025-10-09 091043.png>)

![alt text](<Screenshot 2025-10-09 091112.png>)

![alt text](<Screenshot 2025-10-09 091136.png>)

![alt text](<Screenshot 2025-10-09 091214.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
