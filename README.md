<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="login.CSS">
   </head>
<body>
    <div class="bg_container">
        <div class="login">
            <h1 class="font_style heading">login</h1>
            <div class="login_border">
                <label class="head font_style user">User_name</label><br>
                <input class="head" type="email"><br>
                <label class="head font_style user  ">Password</label><br>
                <input class="head" type="password"><br>
                <h3 class="forget">forgotPassword</h3>
                <button class="head button1" ><a href="sign.html">Sign up</a></button>
                <button class="head button1">Sign in</button>
            </div>
        </div>

    </div>
    
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="login.css">
</head>
<body id="sign_up_page1">
    <div class="bg-container1">
        <h1 class="head">SIGN UP</h1>
        <div class="border1">
            <label class="name1 text1" >Name : </label>
            <input class="name1 box1" type="text" placeholder="First   Name">
            <input class="name1 box1 " type="text" placeholder="Middle Name">
            <input class="name1 box1" type="text" placeholder="Last Name"><br>
            <label class="name1 text1">DOB : </label>
            <input class="name1 box1" type="date"><br>
            <label class="name1 text1">Phone Number : </label>
            <input class="name1 box1" type="number"><br>
            <label class="name1  text1">Email : </label>
            <input class="name1 box1" type="email"><br>
            <label class="name1  text1">Address : </label>
            <input class="name1 box1" type="text"><br>
            <label class="name1 text1">City : </label>
            <input class="name1 box1" type="text" placeholder="City Name"><br>
            <label class="name1 text1">State : </label>
            <input class="name1 box1" type="text" placeholder="State Name"><br>
            <label class="name1 text1">Post Code : </label>
            <input class="name1 box1" type="number"><br>
            <button class="name1 text1 button12"><a href="">Sign In</a></button>
          



        </div>

    </div>
</body>
</html>

.bg_container{
    background-image: url("lock.jpg");
    background-size: cover;
    height: 100vh;
    width:100vw;
    text-align: center;
    padding-top: 80px;
}
.login{
    color: whitesmoke;
    padding-top: 100px;
}
.login_border{
    border-style: solid;
    border-radius: 10px;
    border-top-left-radius: 30px;
    border-bottom-right-radius: 30px;
    width: 30vw;
    height:27vh;
    margin-left: 550px;
    padding:10px;
    justify-content: center;
    
}
.head{
    margin-bottom: 20px;
}
.button1{
    margin:10px;
    padding:10px;
    background-color:rgb(65, 134, 134);
    color:rgb(49, 55, 52);
    border-top-left-radius: 10px;
    border-bottom-right-radius: 10px;
    font-weight: bold;
}
.font_style{
    font-style: normal;
    font-family: serif;
    text-shadow:2px 2px 2px black ;
    font-weight: bolder;
    font-size: x-large;

}
.heading{
    font-size: xx-large;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    font-style: oblique;
    text-shadow: 2px 2px black;
}
.forget{
    color:rgb(74, 89, 94);
    text-decoration: underline;
    font-size: small;

}
/*sign up */
.bg-container1{
    background-image: url("sign_up1.jpg");
    background-size: cover;
    height: 100vh;
    width:100vw;
    text-align: center;
    padding-top: 80px;
    
}
.border1{
    border-style:solid;
    border-radius: 10px;
    width:50vw;
    margin-left: 400px;
    height:50vh;
    text-align: left;
    padding:20px;
    border-color: rgb(177, 158, 54);
   
}
.name1{
    margin:10px;

}
.text1{
    font-weight: bolder;
    font-style: normal;
    font-size: large;
    
    color:black;
}
.box1{
    background-color:transparent;
    border-color: black;
    border-radius: 10px;
}

.button12{
    background-color: goldenrod;
    font-weight: bolder;
    margin-left:330px;
    padding:10px;
    margin-top:36px;
    border-top-left-radius: 20px;
    border-bottom-right-radius: 20px;
    text-shadow: 2px 2px 2px rgb(123, 90, 90);
}
.head1{
    text-shadow: 2px 2px 2px  rgb(123, 90, 90);
}
