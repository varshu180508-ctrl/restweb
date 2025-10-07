# Ex.07 Restaurant Website
## Date:7.10.25

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

rest.html

<html>
    <head>
        <title>
            VARSHU SHOKUDO
        </title>
        <link rel="stylesheet" href="style1.css">
    </head>
    <body>
        <div class="heading">
            <p>VARSHU SHOKUDO</p>
        </div>
        <div class="slogan">
            <p>Varshu Shokudo makes your mouth watering,tempting you to come again</p>
        </div>
        <div class="hyperl">
            <a href="rest.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Admin</a>
            <a href="contact.html">Contact</a>
        </div>
        <div class="footer">&copy;DHANVARSINI S (25012184)</div>
    </body>
</html>

style1.css

body{
    background-image:url("Screenshot 2025-10-07 111250.png");
    background-repeat:no-repeat;
    background-size:cover;
    justify-content:space-between;
    justify-content:space-between;
    display:flex;
}
.heading{
    position:fixed;
    top:0;
    font-family:'cambria','sans-serif','calibri','serif';
    margin-left:5px;
    font-size:50px;
    font-weight:bolder;
    color: black;

}
.slogan{
     position:absolute;
     bottom:75%;
     margin-left: 5px;
     font-family:'cambria','sans-serif','calibri';
     font-weight:bolder;
     font-size:xx-large;
     color:rgb(6, 5, 5);
}
.hyperl{
    position:fixed;
    top:0;
    @media(any-hover: hover){
        a:hover{
            background-color:rgb(6, 5, 5);
        }
    }
    margin-top:40px;
    margin-left:1055px;
    margin-right:50px;
    font-family: 'cambria','serif','calibri';
    font-size:22px;
}
.footer{
    position:fixed;
    bottom:0;
    width:100%;
    background-color:black;
    color:white;
    text-align:center;
    padding:10px;
}


menu.html

<html>
    <head>
        <title>
           Menu:VARSHU SHOKUDO
        </title>
        <link rel="stylesheet" href="style2.css">
        <body>
            <div class="hyperlink">
                <a href="rest.html">Home</a>
                <a href="menu.html">Menu</a>
                <a href="admin.html">Admin</a>
                <a href="contact.html">Contact</a> 
            </div>
            <div class="headings">
                <p>MENU</p>
            </div>
            <div class="column">
                <div class="item">
                    <img src="Screenshot 2025-10-07 080810.png">
                    <h3>Sushi Rolls-rs299</h3>
                </div>
                <div class="item">
                    <img src="Screenshot 2025-10-07 080944.png">
                    <h3>Samurai ramen bowl-rs279</h3>
                </div>
                <div class="item">
                    <img src="Screenshot 2025-10-07 081157.png">
                    <h3>Crispy tempura platter-rs279</h3>
                </div>
                <div class="item">
                    <img src="Screenshot 2025-10-07 083220.png">
                    <h3>Takoyaki-rs249</h3>
                </div>
                <div class="item">
                    <img src="Screenshot 2025-10-07 083315.png">
                    <h3>Osaka Okonomiyaki-rs299</h3>
                </div>
                <div class="item">
                    <img src="Screenshot 2025-10-07 083453.png">
                    <h3>Onigiri rice ball-rs199</h3>
                </div>
                <div class="item">
                     <img src="Screenshot 2025-10-07 083534.png">
                     <h3>Sweet Mochi-rs159</h3>
                 </div>
                 <div class="footer">&copy; DHANVARSINI S (25012184)</div>
        </body>
    </head>
</html>

style2.css

body{
    background-image:url("Screenshot 2025-10-07 180001.png");
    background-repeat:no-repeat;
    background-size:cover;
    justify-content:space-between;
    display:flex;
}
.headings{
    position:relative;
    top:0;
    font-family:'Verdana', 'Geneva', 'Tahoma', 'sans-serif','lucida sans';
    margin-left:5px;
    font-size:60px;
    font-weight:bolder;
    color:rgb(10, 0, 2)
}
.hyperlink{
    position:fixed;
    top:0;
    @media(any-hover:hover){
        a:hover{
            background-color:rgb(116, 11, 29);
        }
    }
    margin-top:40px;
    margin-left:1040px;
    margin-right:50px;
    font-family:'Verdana','Geneva','Tahoma','sans-serif','serif';
    font-size:22px;
}
.column{
    align-items:center;
    display:grid;
    grid-template-columns:repeat(4,1fr);
    gap:10px;
    padding:20px;
    background-size:50%;
}
.item{
    background-color:black;
    background-size:700px;
    padding:1px;
    border-radius:5px;
    text-align:center;
    border:2px solid bisque;
}
.item img{
    width:100%;
    height:auto;
    border-radius:4px;
    margin-bottom:5px;
}
.item h3{
    margin:0;
    font-size:20px;
    color:bisque;
}
.footer{
    position:fixed;
    bottom:0;
    width:50%;
    background-color:rgb(119,32,46);
    color:white;
    text-align:center;
    padding:10px;
}


admin.html

<html>
    <head>
        <title>
            ADMIN-VARSHU SHOKUDO
        </title>
        <link rel="stylesheet" href="style3.css">
    </head>
    <body>
        <div class="hyperlink">
            <a href="rest.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Admin</a>
            <a href="contact.html">Contact</a>
        </div>
         <div class="headings">
            <p>VARSHU SHOKUDO-Meet Our Team</p>
        </div>
        <div class="columnt">
            <div class="itemt">
                <img src="Screenshot 2025-10-07 201128.png">
                <h2>DHANVARSINI</h2>
                <p>CEO</p>
            </div>
            <div class ="itemt">
                <img src="Screenshot 2025-10-07 083818.png">
                <h2>VIJAY</h2>
                <p>Manager</p>
            </div>
            <div class="itemt">
                <img src="Screenshot 2025-10-07 083947.png">
                <h2>Samantha</h2>
                <p>Associator</p>
            </div>
            <div class="itemt">
                <img src="Screenshot 2025-10-07 084143.png">
                <h2>Thugir</h2>
                <p>cook</p>
            </div>
            <div class="itemt">
                <img src="Screenshot 2025-10-07 091151.png">
                <h2>Siva</h2>
                <p>Coordinator</p>
             </div>
        </div>
        <div class="footer">&copy; DHANVARSINI S (25012184)</div>
    </body>
</html>

style3.css

body{
    background-image:url('Screenshot 2025-10-07 201950.png');
    background-repeat:no-repeat;
    background-size:cover;
    justify-content:space-between;
    display:flex;
}
.headings{
    position:absolute;
    top:0;
    font-family:'Verdana','Geneva','Tahoma','sans-serif','serif';
    margin-left:5px;
    font-size:50px;
    font-weight:bolder;
    color:black
}
.hyperlink{
    position:fixed;
    top:0;
    @media(any-hover:hover){
        a:hover{
            background-color:black;
        }
    }
    margin-top:40px;
    margin-left:1040px;
    margin-right:50px;
    font-family:'verdana','geneva','tahoma','serif','Gill Sans';
    font-size:22px;
}
.columnt{
    /* align-items:center; */
    bottom:0;
    display:grid;
    grid-template-columns:repeat(6,1fr);
    gap:30px;
    padding:40px;
    max-width:1200px;
    margin:0 auto;
}
.itemt{
    background-color:bisque;
    background-size:200px;
    border-radius:5px;
    text-align:center;
    border:2px solid bisque;
    margin-top:250px;
}
.itemt img{
    width:130px;
    height:auto;
    border-radius:50%;
    border:3px solid bisque;
    margin-bottom:20px;
    margin-left:auto;
    margin-right:auto;
}
.itemt h2{
    margin:0;
    font-size:20px;
    color:black;

}
.itemt p{
    margin:0;
    font-size:20px;
    color:black;
}
.footer{
    position:fixed;
    bottom:0;
    width:100%;
    background-color:black;
    color:white;
    text-align:center;
    padding:10px;
}

contact.html

<html>
    <head>
        <title>
            CONTACT:VARSHU SHOKUDO
        </title>
        <link rel="stylesheet" href="style4.css">
    </head>
    <body>
        <div class="hyperlink">
            <a href="rest.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Admin</a>
            <a href="contact.html">Contact</a>
        </div>
        <div class="headings">
            <p>VARSHU SHOKUDO</p>
        </div>
        <div class="address">
            <h2>CONTACT DETAILS</h2>
            <P>Address</P>
            <p>354/3 shinchan street,tokyo,Japan</p>
            <p>Mobile no: 9363131367</p>
            <p>Email: varshu@gmail.com</p>
       </div>
       <div class="footer">&copy; DHANVARSINI S(25012184)</div>
   </body>
</html>

style4.css

body{
    background-image:url('Screenshot 2025-10-07 180001.png');
    background-repeat:no-repeat;
    background-size:cover;
    justify-content:space-between;
    display:flex;
    align-items:center;
}
.headings{
    position:absolute;
    top:0;
    font-family:'Verdana', 'Geneva', 'Tahoma',' sans-serif','serif';
    margin-left:5px;
    font-size:60px;
    font-weight:bolder;
    color:black;

}
.hyperlink{
    position:fixed;
    top:0;
    @media(any-hover:hover){
        a:hover{
            background-color:black;
        }
    }
    margin-top:40px;
    margin-left:1040px;
    margin-right:50px;
    font-family:'Verdana','Geneva', 'Tahoma', 'sans-serif','serif';
    font-size:20px;
}
.address{
    margin-left:600px;
    border:8px solid black;
    background-color:bisque;
    width:250px;
    height:auto;
    text-align:center;
    padding:20px;
}
.address h2{
    font-size:35px;
    color:black;
}
.address p{
    font-size:larger;
    color:black;
}
.footer{
    position:fixed;
    bottom:0;
    width:100%;
    background-color:rgb(243, 166, 106);
    color:white;
    text-align:center;
    padding:10px;
}


```


##OUTPUT
![alt text](<varshuini/restapp/static/Screenshot (21).png>)
![alt text](<varshuini/restapp/static/Screenshot (22).png>)
![alt text](<varshuini/restapp/static/Screenshot (23).png>)
![alt text](<varshuini/restapp/static/Screenshot (24).png>)



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
