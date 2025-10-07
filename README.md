# Ex.07 Restaurant Website
# Date:07-10-2025
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```
home.html:

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
            <h1>CLASSIC RESTAURANT</h1>
            <b>"From Field To Fork -Fresh Foods On Every Day"</b>
        </div>
        <div class="offer">
            <h2>Limited Offers</h2>
            <h3>50% off for all Food</h3>
        </div>
        <footer>
            <h6 class="bottom">BALAJI V(25012279)</h6>

        </footer>
    </body>
</html>

menu.html:

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
                <img src="dish-1.jpg"alt="pic">
                <b> $20</b>
            </div>
            <div class="food2">
                <img src="dish-2.jpg" alt="pic">
                <b>$15</b>
            </div>
            <div class="food3">
                <img src="dish-3.jpg" alt="pic">
                <b>$50</b>
            </div>
            <div class="food4">
                <img src="dish-4.jpg" alt="pic">
                <b>$60</b>
            </div>
            <div class="food5">
                <img src="dish-5.jpg" alt="pic">
                <b>$30</b>
            </div>
            <div class="food6">
                <img src="dish-6.jpg" alt="pic">
                <b>$40</b>
            </div>
            <div class="food7">
                <img src="dish-7.jpg" alt="pic">
                <b>$30</b>
            </div>
            <div class="food8">
                <img src="dish-8.jpg" alt="pic">
                <b>$40</b>
            </div>
            <div class="food9">
                <img src="dish-9.jpg" alt="pic">
                <b>$50</b>
            </div>
            <div class="food10">
                <img src="dish-10.jpg" alt="pic">
                <b>$40</b>
            </div>
            <div class="food11">
                <img src="dish-11.jpg" alt="pic">
                <b>$50</b>
            </div>
            <div class="food12">
                <img src="dish-12.jpg" alt="pic">
                <b>$60</b>
            </div>
        </div>
        <footer>
            <h6 class="bottom">BALAJI V(25012279)</h6>

        </footer>
    </body>
</html>

contact.html:

<html>
    <head>
        <title>Contact</title>
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
            <h4>Address: 234 West 42nd Street, New York, NY 10036</h4>
            <h2>Phone no: +1 678-298-2442</h2>
            <h3>Email:clasicrestaurant@gmail.com</h3>
        </div>
        <footer>
            <h6 class="bottom">BALAJI V(25012279)</h6>

        </footer>
    </body>
</html>

admin.html:

<html>
    <head>
        <title>Contact</title>
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
            <h4>Address: 234 West 42nd Street, New York, NY 10036</h4>
            <h2>Phone no: +1 678-298-2442</h2>
            <h3>Email:clasicrestaurant@gmail.com</h3>
        </div>
        <footer>
            <h6 class="bottom">BALAJI V(25012279)</h6>

        </footer>
    </body>
</html>

home.css:

*{
    margin: 0;
    border: 0;
}

body{
    background-image:url(bg-2.jpg);
    background-position: center;
    background-size:cover;
    width: 100%;
    background-color: rgb(240, 233, 233);
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    color: bisque;
}

a{
    padding: 15px;
    color:rgb(227, 226, 224);
}
a:hover{
    background-color: aquamarine;
    color:blue;
}
.name{
    text-align: center;
    position: relative;
    left: 290px;
    font-weight: bolder;
    font-family: 'Times New Roman', Times, serif;
    color: rgba(31, 1, 1, 0.855);
    font-size: 30px;
    width: 1000px;
    background-color: rgba(27, 26, 24, 0.782);
}
.offer{
    text-align: right;
    font-size: 40px;
    color: rgb(251, 255, 0);
    position: relative;
    right: 100px;
    top:200px;

}
.bottom{
    font-size: 30px;
    text-align: center;
    position: relative;
    top: 462px;
    background-color: brown;
}

menu.css:

body{
    
    background:url(bg-1.jpg);
    background-repeat: no-repeat;
    background-position:center;
    background-size: cover;
    font-size: 20px;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    margin: auto;
}
.main{
    display: grid;
    grid-template-columns: repeat(5,1fr);
}
a{
    color:rgb(227, 226, 224);
    position: relative;
    left: 1200px;
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
    width: 150px;
    height: 100px;
    border: solid rgb(87, 85, 85) 6px;
}
h1{
    text-align: center;
    position: relative;
    bottom: 10px;
   
    color: rgb(247, 6, 6);

}
.bottom{
    font-size: 30px;
    text-align: center;
    position: relative;
    top: 50px;
    background-color: brown;
}

contact.css:

body{
    background-image:url(contactback.jpg);
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    font-size: 20px;
}

a{
    padding: 15px;
    color:whitesmoke;
    position: relative;
    left: 1100px;
    top: 20px;
    font-size: 20px;
}
.bottom{
    font-size: 30px;
    text-align: center;
    background-color: rgba(37, 0, 0, 0.768);
    position: relative;
    top: 150px;
    color: white;
}
.contanct-container{
    font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    text-align: center;
    padding: 30px;
    background-color: rgb(229, 229, 229);
    height:400px;
    width:410px;
    display: block;
    gap: 20px;
    font-size: 20px;
    position: relative;
    left: 600px;
    top:20px;
    border-radius: 10%;
}
h2,h3,h4{
    font-size: 27px;
}

admin.css:

body{
    background-image:url(adminback.jpg);
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}
a{
    padding: 15px;
    color:white;
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
    background-color:white;
    position: relative;
    top: 60px;
    color:white;
}
h1{
    text-align: center;
    color:white;
    font-size: 40px;
}
.bottom{
    font-size: 30px;
    text-align: center;
    position: relative;
    top: 125px;
    background-color: brown;
    width: 1550px;
}
```
# OUTPUT:
![alt text](1.png)
![alt text](2.png)
![alt text](3.png)
![alt text](4.png)
# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
