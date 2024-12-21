# Ex.07 Restaurant Website
# Date: 14-12-2024
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
~~~
<html>
    <head>
        <title> Golden Plate Restaurant  </title>
        
    </head>
    
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Londrina+Sketch&display=swap" rel="stylesheet">
    <style>
        h1,ul{
            display: inline;
            padding:20px;
            
           
        }
        h1{
            margin-left: 10px;
        }
        nav{
            padding: 20px;
           background-color:lightgray;
          color: rgb(15, 12, 96);
        }
        .top{
            
           padding: 20px;
           background-color:lightgray;
          color: rgb(15, 12, 96);
          border-radius: 65px;
          background: linear-gradient(black)
        }
        li{
            
            display: inline;
            color: black;
            font-style: italic;
            
        }
        li:hover{

            color: red;
            cursor: pointer;
        }
        ul{
            margin-left: 80px;
           
        }
       
        input{
            padding: 20px;
            width: 50%;
           
        }
        .searchbar{
            margin-left: 20%;
            padding: 15px;
       
        }
        h2{
            text-align: center;
            font-size: 40px;
        }
        .img{
            display: inline-block;
            width: 420px;
            border-width: 2px;
            border-color: slategray;
            border-style: solid;
            margin-left: 30px;

        }
        .img:hover{
            
            color: blueviolet;
        }
        .info{
            margin-left: 35%;
            margin-right: 45%;
            border-width: 2px;
            border-style:inset;
            padding: 10px;
            margin-top: 20px;
            
        }
      

    </style>
    <body style="background-color: slategray;">
        <nav class="top">
            <h3 > Opening time 🕥: 10.00 am - 11.00 pm</h3>
           <h1 style="font-size: 80px;"> 𝓖𝓸𝓵𝓭𝓮𝓷 𝓟𝓵𝓪𝓽𝓮 𝓡𝓮𝓼𝓽𝓪𝓾𝓻𝓪𝓷𝓽</h1><h5 style="display: inline;">&lpar;NONVEG&rpar;</h5>
            
           <img src="retaurantlogo.webp" width="200px" height="170px" style="margin-left: 85px;" >
        
           
            <ul>
                <li>MENU |</li>
                <li>RATINGS |</li>
                <li>BLOG |</li>
                <li>COUPON |</li>
                <li> ONLINE ORDER</li>
                

            </ul>
        </nav><br>

        <hr><br><center>
              <div class="serchbar">
                <input placeholder="Search"> 
             </div></center>
        <div>
            <h2   >
                FOOD MENU
            </h2>
            
        </div>
        <div class="img">

        <img src="main dish.jpg" width="420px" height="300px" ><br>
       
       <ol ><li style="font-weight: bolder;" style="word-spacing: 210px;">DISH                         PRICES</li><br>
           <li style="word-spacing: 145px;">Chicken_briyani                       200/-</li><br> 
           <li style="word-spacing: 152px;"> Mutton_briyani                       250/-</li><br> 
           <li style="word-spacing: 126px;">Chiken_Fried_rice                     150/-</li><br> 
           <li style="word-spacing: 145px;">Egg_Fried_rice                        120/-</li><br> 
           <li style="word-spacing: 170px;">Egg_briyani                           180/- </li><br> 
           <li style="word-spacing: 133px;">Chicken_Noodles                       150/-</li><br> 
           <li style="word-spacing: 160px;">Egg_Noodles                           120/-</li><br> 
           <li style="word-spacing: 120px;">Schezwan_Noodles                      130/-</li><br> 
           <li style="word-spacing: 157px;">Mutton_curry                          100/-</li><br> 
           <li style="word-spacing: 157px;">Chicken_curry                         90/-</li><br> 
           <li style="word-spacing: 183px;">Egg_curry                             70/-</li>
        </ol> 
       </div>
        <div class="img">

            <img src="starter image.jpg" width="420px" height="300px" ><br>
            
        <ol>
            <li style="word-spacing: 200px;">STARTER                     PRICES</li><br>
           <li style="word-spacing: 150px;">Chicken_spring_roll                 100/-</li><br> 
           <li style="word-spacing: 195px;">Chilli_prawns                    130/-</li><br> 
           <li style="word-spacing: 140px;">Chicken_manuchurian                     110/-</li><br> 
           <li style="word-spacing: 222px;">Meatballs                     170/-</li><br> 
           <li style="word-spacing: 188px;">Mutton_keema                         180/- </li><br> 
           <li style="word-spacing: 215px;">Chicken_65                       80/-</li><br> 
           <li style="word-spacing: 212px;">Mutton_85                           180/-</li><br> 
           <li style="word-spacing: 211px;">sheek_kebab                      90/-</li><br> 
           <li style="word-spacing: 198px;">cheese_omelete                          70/-</li><br> 
           <li style="word-spacing: 139px;">Crispy_chicken_nuglets                        90/-</li><br> 
           <li style="word-spacing: 245px;">Egg_65                             60/-</li>
            
        </ol>
    </div> 
        <div class="img">

             <img src="beverages image.jpg" width="420px" height="300px" ><br>
       
            <ol>
                <li style="word-spacing: 150px;">BEVARAGES                    PRICES</li><br>
           <li style="word-spacing: 175px;">Milkshakes                 100/-</li><br> 
           <li style="word-spacing: 225px;">Tea                  130/-</li><br> 
           <li style="word-spacing: 171px;">Cappuccino                     110/-</li><br> 
           <li style="word-spacing: 204px;">Mojito                     170/-</li><br> 
           <li style="word-spacing: 180px;">Lemonade                        180/- </li><br> 
           <li style="word-spacing: 188px;">Ice_cream                       80/-</li><br> 
           <li style="word-spacing: 172px;">Soft_drinks                           180/-</li><br> 
           <li style="word-spacing: 185px;">Rose_milk                     90/-</li><br> 
           <li style="word-spacing: 183px;">Fresh_juice                         70/-</li><br> 
           <li style="word-spacing: 193px;">Mocktails                        90/-</li><br> 
           <li style="word-spacing: 202px;">Desserts                            60/-</li>

            </ol>

    </div> 
        <br><br>
        <hr><br>
<footer>
        <nav>
        <div style="margin-left: 37%;">
            Contact us : More information<br>  </div>
         <center>
         <div class="info" >   
            📞 +91 5345668462<br>
            🌐 www.GoldeplateRestaurant.in<br>
            📍 11,Any st,Any city,143.
         </div></center>
         <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Cumque laboriosam quo commodi, quas eveniet quis non repellat, minima incidunt impedit quam maxime quia tempora reprehenderit maiores! Corrupti amet at ex nemo laboriosam accusantium facilis. Quo tempore, tenetur accusantium neque voluptatibus obcaecati voluptatem hic quisquam deleniti nihil repellendus magnam doloremque quae?
         </p>

    </nav>
</footer>
        

  
    </body>
</html>
~~~
# OUTPUT:
![Screenshot (103)](https://github.com/user-attachments/assets/aa62ddd8-baff-4464-9c25-f735726d9477)

menu's

![Screenshot (104)](https://github.com/user-attachments/assets/64e27399-433c-49c4-af9d-4eaa21b575fc)

footer

![Screenshot (105)](https://github.com/user-attachments/assets/33dffb32-57cd-486a-93b0-a58afd29158a)



# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
