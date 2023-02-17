# login_page
Login page for Intern Crowd
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Page</title>
    <style>
        .container{
    background-color:rgb(237, 226, 244);
    padding: 5px 20px 10px 20px;
    border-color: black solid 2px;

}
        h1{
            text-align: center;
            padding:  4px;
            margin:5px;
            background-color:rgb(176, 35, 195);
            color:whitesmoke;
            text-decoration: solid;
        }
    #box{
    
    margin: 0px;
    height: 290px;
    float: center;
    border-radius: 5px;
}
body{
    margin:0 auto;
    max-width: 45%;
   background-image: url(background.jpeg);
   background-size: auto;
    background-repeat:round;


}
a{
    color:rgb(207, 45, 229);
}
input[type= "password"],
input[type="email"],
select,
textarea {
    width: 98.5%;
    padding : 8px;
    border-color:rgb(197, 197, 197) solid 1px;
    margin: 7px;
}
input[type="submit"]{
    background-color:rgb(197, 88, 212);
    text-decoration: solid;
    color: black;
    padding: 12px 15px ;
    font-size: medium;
    cursor: pointer;
    width: 100%;
}
input[type= "submit"]:hover{
    background-color: rgb(64, 186, 133);
}   

</style>
</head>
<body>
    <div class="container">
    <h1> Intern Crowd</h1>  </div>
    <div class="container">
    <img id="box" src="Tablet login.png" alt="">
   <h3>Doesn't have an account yet? <a href="#">Sign Up</a></h3> 
   <h2> Email Address: <input type="email" name="email" id="email"> </h2>
   <h2> Password: <input type="password" name="password" id="password" required></h2>
   <input type="checkbox" id="Remember" name="Remember" value="Remember me">
   <label for="Remember">Remember me</label>
   <br><br><br>
   <input type="submit" value="Login">
   <br>
   <br><br>
   </div>

</body>
</html>
