# tried to copy amazon actual website.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amazon</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css" integrity="sha512-Kc323vGBEqzTmouAECnVceyQqyqdsSiqLQISBL29aUW4U/M7pSPA/gEUZQqv1cwx4OnYxTxve5UMg5GT6L4JJg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="project.css">
    

</head>
<body>
 <header>
    <div class="navbar">
    <div class="nav-logo">
        <div class="logo"></div>
     </div>

     <div class="nav-address">
        <p class="add-first">Deliver to</p>
        <div class="add-icon"> 
            <i class="fa-solid fa-location-dot"></i>
            <p class="add-second">India</p>
        </div>
     </div>
     <div class="nav-search">
        <select class="search-select"><option>All</option></select>
        <input placeholder="Search amazon" class="search-int">
        <div class="search-icon"> <i class="fa-solid fa-magnifying-glass"></i></div>
     </div>
     <div class="flag"><i class="fa-solid fa-flag"></i>IN
     </div>
     <div class="nav-sign border"> 
        <p><span>Hello,Sign in</span></p>
        <p class="nav-second">Accounts and lists</p>
     </div>
     <div class="nav-return border">
        <p><span>Returns</span></p>
        <p class="nav-second">& orders</p>
     </div>
     <div class="nav-cart">
        <i class="fa-solid fa-cart-shopping"></i>
        Cart
     </div>
   </div>

   <div class="panel">
      <div class="panel-all">
         <i class="fa-solid fa-bars"></i>
         All
      </div>
      <div class="panel-opt">
         <p>Today's deal</p>
         <p>Customer service</p>
         <p>Registry</p>
         <p>Gift card</p>
         <p>Sell</p>
      </div>
      <div class="panel-deal">
         shop deal in electronics
      </div>
    </div>
</header>
<div class="hero-sec">
   <div class="hero-msg">
<p>You are on amazon.com. You can also shop on Amazon India for millions of products with fast local delivery.. 
   <a> Click here to go to amazon.in</a> </p>
   </div>
   </div>
<div class="shopping">
   <div class="box1 box">
      <div class="box-content">
      <h2>Clothes</h2>
      <div class="box-img" style="background-image: url('box1_image.jpg');"></div>
      <p>see more</p>
   </div>
   </div>
   <div class="box2 box">
      <div class="box-content">
         <h2>Health & personal care</h2>
         <div class="box-img" style="background-image: url('box2_image.jpg');"></div>
         <p>see more</p>
      </div>
   </div>
   <div class="box3 box">
      <div class="box-content">
         <h2>Furniture</h2>
         <div class="box-img" style="background-image: url('box3_image.jpg');"></div>
         <p>see more</p>
      </div>
   </div>
   <div class="box4 box">
      <div class="box-content">
         <h2>Mobile phones</h2>
         <div class="box-img" style="background-image: url('box4_image.jpg');"></div>
         <p>see more</p>
      </div>
   </div>
   <div class="box5 box">
      <div class="box-content">
         <h2>Beauty products</h2>
         <div class="box-img" style="background-image: url('box5_image.jpg');"></div>
         <p>see more</p>
      </div>
   </div>
   <div class="box6 box">
      <div class="box-content">
         <h2>Animal care</h2>
         <div class="box-img" style="background-image: url('box6_image.jpg');"></div>
         <p>see more</p>
      </div>
   </div>
   <div class="box7 box">
      <div class="box-content">
         <h2>Travel & Adventure</h2>
         <div class="box-img" style="background-image: url('box7_image.jpg');"></div>
         <p>see more</p>
      </div>
   </div>
   <div class="box8 box">
      <div class="box-content">
         <h2>Fashion</h2>
         <div class="box-img" style="background-image: url('box8_image.jpg');"></div>
         <p>see more</p>
      </div>
   </div>
</div>
<footer>
   <div class="footpanel1">
      Back to top
   </div>
   <div class="footpanel2">
      <ul>
        <p> Get to Know Us</p>
<a>About Us</a>
   <a>Careers</a>
      <a>Press Releases</a>
         <a>Amazon Science</a>
      </ul>
      <ul>
         <p>Connect with Us</p>
<a>Facebook</a>
   <a>Twitter</a>
      <a>Instagram</a>
      </ul>
      <ul>
         <p>Make Money with Us</p>
<a>Sell on Amazon
   <a>Sell under Amazon Accelerator</a>
      <a>Protect and Build Your Brand</a>
         <a>Amazon Global Selling</a>
            <a>Supply to Amazon</a>
               <a>Become an Affiliate</a>
                  <a>Fulfilment by Amazon</a>
                     <a>Advertise Your Products</a>
                        <a>Amazon Pay on Merchants</a>
      </ul>
      <ul>
         <p>Let Us Help You</u>
<a>Your Account</a>
<a>Returns Centre</a>
<a>Recalls and Product Safety Alerts</a>
<a>100% Purchase Protection</a>
<a>Amazon App Download</a>
<a>Help</a>
      </ul>
   </div>
   <div class="footpanel3" >
      <div class="logo1"></div>
      </div>
   </div>
   <div class="footpanel4">
      <div class="pages">
      <a>Conditions of Use & Sale</a>
      <a>Privacy Notice</a>
      <a>Interest-Based Ads</a>
   </div> 
   <div>
#html codes above
 #css codes below      
*{
    margin:0;
    font-family: arial;
    border: border-box;
}
.navbar{
height: 60px;
background-color: black;
color: white;
display: flex;
align-items: center;
justify-content: space-evenly;
width: 1340px;
}
 .nav-logo{height: 50px;
width:100px;} 
.border-hover{
    border:1.5px solid white
}

.logo{
    background-image: url("amazon_logo.png");
    width: 110px;
    height: 50px;
    background-size: cover;
}
.add-first{
    color:white;
    font-size: 0.85rem;
    height: 18px;
    margin-left: 18px;
}
.add-second{
    font-size: 1rem;
  height: 15px;
  margin-left: 1px;
}
.add-icon{
    display:flex;
    align-items: center;
    margin-left: 14px;
}
.nav-search{display: flex;
/* background-color: orange; */
height: 40px;
/* border-radius: 4px; */
justify-content: space-evenly;

}

.search-select{
    border-top-left-radius: 4px;
    border-bottom-left-radius: 4px;
    background-color: #f3f3f3;
    margin-left: 20px;
    width:40px;
}
.search-int{
    width:500px;
    font-size: 1rem;
}
.search-icon{
    height: 40px;
    width: 40px;
    align-items: center;
    justify-content: center;
    display: flex;
    background-color: orange;
    border-top-right-radius: 4px;
    border-bottom-right-radius: 4px;
    font-size: 1.2rem;
    color: #0f1111;
}
.flag i{font-size: 20px;
color: peachpuff;}
span{
    font-size: 0.75rem;
}

.nav-second{
    font-size: 0.85rem;
    font-weight: 700;
}

.nav-cart i{
    font-size: 30px;
}
.nav-cart{
    font-size: 0.85rem;
    font-weight: 600;
}
.panel{
    height: 39px;
    background-color: #222f22;
    display: flex;
    color: white;
    align-items: center;
    justify-content: space-evenly;
    width: 1340px;
}
.panel-opt p{
    display: inline;
    margin-left: 20px;
}
.panel-opt{
    width: 70%;
    font-size: 14px;
  
}
.panel-deal{
    font-weight: 600;
    font-size: 16px;
    margin-left: 115px;
}
.hero-sec{
    background-image: url(hero_image.jpg);
    height: 350px;
    background-size: cover;
    width: 1340px;
    display: flex;
    justify-content: center;
    align-items: flex-end;
}
.hero-msg{
    background-color: white;
    color: black;
    height: 40px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 14px;
    width: 80%;
    margin-bottom: 25px;
}
.hero-msg a{
    color: #007185;
}
.box{
    /* border:2px solid black; */
    height: 400px;
    width: 23%;
    padding: 20px 0px 15px;
    background-color: white;
    margin-top: 15px;
}
.shopping{
    display: flex;
    justify-content: space-evenly;
    background-color: #e2e7e6;
    flex-wrap: wrap;
   }
.box-img{
    height: 350px;
    background-size: cover;
    margin-top: 10px;
    margin-bottom:10px;
}
.box-content{
    margin-left: 10px;
    margin-right: 10px;
}
.box-content p {
    color: #007185;
}
.footer{
    margin-top: 15px;
}
.footpanel1{
    background-color: #37475a;
    color: white;
    height: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 0.85rem;
    margin-top: 10px;
}
.footpanel2{
    background-color: #222f3d;
    color: white;
    height: 350px;
    display: flex;
    justify-content: space-evenly;
}
ul a {
    display: block;
    font-size: 0.85rem;
    color: #dddddd;
    margin-top: 10px;
}
ul p{
    font-weight: 700;
}
ul{
    margin-top: 15px;
}
.footpanel3{
    background-color: #222f3d;
    height: 70px;
    justify-content: center;
    align-items: center;
    color: white;
    border-top: 0.5px solid white;
    display: flex
}
.logo1{
    background-image: url("amazon_logo.png");
    width: 100px;
    height: 50px;
    background-size: cover;
    align-items: center;
    justify-content: center;
}
.footpanel4{
    background-color:  #0f1111;
    color: white;
    /* justify-content: center;
    display: flex;
    align-items: center; */
    height: 80px;
}
.pages{
    font-size: 0.7rem;
    align-items: center;
    text-align: center;
    padding-top: 25px;
}
.copyright{
    font-size: 0.7rem;
    align-items: center;
    text-align: center;
    padding-top:5px;
}
       
   <div class="copyright">
      ©1996-2024, Amazon.com, Inc. or its affiliates</div>
   </div>
</footer>



    
</body>
</html>
