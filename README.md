<!DOCTYPE html>
<!-- saved from url=(0073)file:///C:/Users/Shruti/Documents/WEB%20DEVELOPMENT%20PROJECTS/index.html -->
<html lang="en"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ozone Fitness</title>
<link href="./Ozone Fitness_files/css2" rel="stylesheet"><link rel="stylesheet" href="file:///C:/Users/Shruti/Documents/WEB%20DEVELOPMENT%20PROJECTS/css/style.css"><style>
    /* CSS Reset */
    body {
        font-family: 'Bakbak One', cursive;
        color: rgb(216, 176, 16);
        margin: 0px;
        padding: 0px;
        background: url('girl.jpg');
        height: 0px;
        font-weight: bold;
    }

    .left {
        display: inline-block;
       /* border: 2px solid rgb(230, 5, 5);*/
        position: absolute;
        left: 50px;
        top: 25px;


    }

    .left img {
        width: 200px;
    }

    .left div {
        text-align: center;
        list-style: 20px;
        font-size: 25px;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    }

    .mid {
       /* border: 2px solid rgb(225, 228, 222);*/
        display: block;
        width: 40%;
        margin: 18px auto;




    }

    .right {
        position: absolute;
        right: 33px;
        top: 25px;
       /* border: 2px solid rgb(173, 173, 132);*/
        display: inline-block;
    }

    .navbar {
        display: inline-block;
    }

    .navbar li {
        display: inline-block;
    }

    .navbar li a {
        color: rgb(219, 223, 205);
        text-decoration: none;
        padding: 18px 10px;

    }

    .navbar li a:hover,
    .navbar li a.active {
        color: rgb(153, 124, 115);
        text-decoration: underline;
    }

    .btn {
        font-family: 'Bakbak One', cursive;
        margin: 0px 10px;
        color: black;
        background: rgb(207, 80, 80);
        padding: 5px 15px;
       /* border: 3px solid rgb(173, 201, 14);*/
        border-radius: 8px;
        font-size: 12px;
        cursor: pointer;
    }

    .btn:hover {
        background-color: rgb(85, 206, 29);
    }

    .container {
        border: 4px solid rgb(0, 0, 0);
        margin: 100px;
        border-radius: 12px;
        width: 30%;
        padding: 10px 10px;

    }

    .form-group input {
        text-align: center;
        display: block;
        margin: 4px auto;
        padding: 4px;
        width: 70%;
        border: 2px solid rgb(8, 3, 14);
        font-size: 15px;
        font-family: Verdana, Geneva, Tahoma, sans-serif;
        border-radius: 10px;
        font-weight: bold;
    
    }

    .container h1 {
        text-align: center;
    }

    .container button {
        display: block;
        width: 70%;
        margin: 20px auto;
    }
</style></head>





<body>
    <header class="header"></header>
    <!--left box for logo-->
    <div class="
    left">
        <img src="o3-zone-gwalior.webp" >
        <div>OZONE FITNESS</div>


    </div>
    <!--mid box for navbar-->
    <div class="mid">
        <ul class="navbar">
            <li><a href="file:///C:/Users/Shruti/Documents/WEB%20DEVELOPMENT%20PROJECTS/index.html#" class="active">HOME</a></li>
            <li><a href="file:///C:/Users/Shruti/Documents/WEB%20DEVELOPMENT%20PROJECTS/index.html#">ABOUT US</a></li>
            <li><a href="file:///C:/Users/Shruti/Documents/WEB%20DEVELOPMENT%20PROJECTS/index.html#">FITNESS CALCULATOR</a></li>
            <li><a href="file:///C:/Users/Shruti/Documents/WEB%20DEVELOPMENT%20PROJECTS/index.html#">CONTACT US</a></li>

    </ul></div>
    <!--right box for button-->
    <div class="right">
        <button class="btn">call us now</button>
        <button class="btn">Email us</button>

    </div>

    
    <div class="container">
        <h1>Join the top rated gym of gwalior now</h1>
        <form action="file:///C:/Users/Shruti/Documents/WEB%20DEVELOPMENT%20PROJECTS/noaction.php">
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your name">

            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Contact number">

            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Age">

            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Locality">

            </div>
            <div>
                <div class="form-group">
                    <input type="text" name="" placeholder="Gender">
    

            </div>
            <button class="btn">Submit</button>



        
    </div></form>


</div></body></html>
