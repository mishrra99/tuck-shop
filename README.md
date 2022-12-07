# tuck-shop
for university tuck shop

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="project2.css">
    <link rel="stylesheet" href="lastpage.css">
    <link href="https://fonts.googleapis.com/css?family=Josefin+Sans&display=swap" rel="stylesheet">
    <link rel="stylesheet" type="text/css" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css">
</head>
<body>
    <header>
        <nav>
            <div class="title0">
                <h1>TUCK</h1>
            </div>
            <div class="title1">
                <h1>SHOP</h1>
                </div>
            <div class="menu">
                <a href="projectteam.html">about</a>
                <a href="project items.html">Item Available</a>
                <a href="project timing,contact,detail.html">TIMING/CONTACT</a>
                <a href="Feeback Form.html">FEEDBACK</a>
            </div>
        </nav>
        <div class = "search">
            <input class="srch" type="search" name = "" placeholder="Type to text">
            <a href="#" class="btn">search</a>
        </div>
            <main>
               <section>
                <h3>Welcome to LPU</h3>
                <h1>DO COME & VISIT <span class="change_content"></span></h1>
                <p>"LPU ONCE IS NOT ENOUGH"</p>
                <a href="help.html" class="btnone">HELP</a>
                <a href="#" class="btntwo">Signup</a>
               </section>
            </main>
    </header>
    <footer class="footer">
        <div class="container">
            <div class="row">
                <div class="footer-col">
                    <h4>company</h4>
                    <ul>
                        <li><a href="#">our services</a></li>
                        <li><a href="#">privacy policy</a></li>
                    </ul>
                </div>
                <div class="footer-col">
                    <h4>get help</h4>
                    <ul>
                        <li><a href="#">FAQ</a></li>
                        <li><a href="#">shipping</a></li>
                        <li><a href="#">returns</a></li>
                        <li><a href="#">order status</a></li>
                        <li><a href="#">payment options</a></li>
                    </ul>
                </div>
                <div class="footer-col">
                    <h4>get-connect</h4>
                    <ul>
                        <li>CONTACT-: +91-9284681752</li>
                        <li>EMAIL-: shreymishra084@gmail.com</li>
                    </ul>
                </div>
                <div class="footer-col">
                    <h4>follow us</h4>
                    <div class="social-links">
                        <a href="https://www.facebook.com/profile.php?id=100031466116343"><i class="fab fa-facebook-f"></i></a>
                        <a href="https://twitter.com/yash______19"><i class="fab fa-twitter"></i></a>
                        <a href="https://www.instagram.com/mishrra_/"><i class="fab fa-instagram"></i></a>
                        <a href="https://www.linkedin.com/in/shrey-mishra-1353a2252/"><i class="fab fa-linkedin-in"></i></a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
   </footer>
   <footer class="footer2"><p>© Copyright 2022-2023 www tuckshop.com. All rights reserved. Developed by Shrey Mishra.</p></footer>
    <style>
        *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
 }   
 header{
    width: 100%;
    height: 100vh;
    background-image:url(Lovely-Professional-University-Campus.jpg);
    background-repeat: no-repeat;
    background-size: cover;
 }
 nav{
    width: 100%;
    height: 15vh;
    color: white;
    display: flex;
    justify-content:space-between;
    align-items: center;
    text-transform: uppercase;
 }
 
 .title1{
position: absolute;
padding-left: 180px;}
.title1 h1{
color:#000;
font-size: 60px;
}
.title0 h1{
color:red;
font-size: 60px;
}
 nav .menu{
    width: 50%;
    display: flex;
    display: inline-block;
    padding: 5px 0px;
    border: 1px solid transparent;
    justify-content: space-around;
 }
 nav .menu a{
    width: 20%;
    text-decoration: none;
    color: whitesmoke;
    padding: 5px 1px;
    border: 1px solid transparent;
    font-weight: bold;
    padding-left: 60px;
    border-radius: 4px;
    outline: none;
 }
 main{
    width: 100%;
    height: 85vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: white;
 }
 section h3{
    font-size: 35px;
    font-weight: 200;
    letter-spacing: 3px;
    text-shadow: 1px 1px 2px black;
 }
 section h1{
    margin: 30px 0 20px 0;
    font-size: 55px;
    font-weight: 700;
    text-shadow: 2px 1px 5px black;
    text-transform: uppercase;
 }
 section p{
   font-size: 25px; 
   word-spacing: 2px;
   margin-bottom: 25px;
   text-shadow: 1px 1px 1px black;
 }
 section a{
    padding: 8px 30px;
    border-radius: 4px;
    outline: none;
    text-transform: uppercase;
    font-size: 13px;
    font-weight: 500;
    text-decoration: none;
    letter-spacing: 1px;
    transition: all .5s ease;
 }
 section .btnone{
    background:#000;
    color:white;
 }
 nav .menu a:hover{
    color:#000;
 }
 .btnone:hover{
    background:#00b894 ;
    color:black;
 }
 .btntwo:hover{
    background: #00b894;
    color: black;
 }
 section .btntwo{
    background:#000;
    color: white;
 }
 .change_content:after{
    content: '';
    animation: changetext 2s infinite linear;
    color: #00b894;
 }
 @keyframes changetext{
    0%{content: "LPU";}
    100%{content: "TUCKSHOPS";}
 }





 .search{
   width: 330px;
   float: right;
   margin-left: 270px;
}
.srch{
   font-family:'Times New Roman';
   width: 200px;
   height: 40px;
   background: transparent;
   border: 1px solid #000;
   margin-top: 15px;
   color: #000;
   border-right: none;
   font-size: 15px;
   display: inline-block;
   padding: 10px;
   border-bottom-left-radius: 5px;
   border-top-left-radius: 5px;

}
.btn{
   padding: 10px 20px;
   height: 40px;
   background: #000;
   border: #000;
   margin-top: 13px;
   color: rgb(255, 255, 255);
   font-size: 15px;
   border-bottom-left-radius: 5px;
   border-top-left-radius: 5px;
   text-decoration: none;

}
.btn:hover{
   color: #000;
   background-color: #00b894;
   /* padding-right: 8px; */
}
.btn:focus{
   outline: none;
}

.srch:focus{
   outline: none;
}
        <style/>
</body>
</html>
