# Amozon_clone
html***

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>amozon</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css"
        integrity="sha512-z3gLpd7yknf1YoNbCzqRKc4qyor8gaKU1qmn+CShxbuBusANI9QpRohGBreCFkKxLhei6S9CQXFEbbKuqLg0DA=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <header>
        <div class="navbar">
            <div class="nav-logo border">
                <div class="logo">
                </div>
            </div>
            <div class="nav-address border">
                <p class="add-first">Dilever to</p>
                <div class="add-icon">
                    <i class="fa-solid fa-location-dot"></i>
                    <p class="add-second">India</p>
                </div>
            </div>
            <div class="nav-search">
                <select class="search-select">
                    <option>ALL</option>
                </select>
                <input placeholder="search amozon" class="search-input">
                <div class="search-icon">
                    <i class="fa-solid fa-magnifying-glass"></i>
                </div>
            </div>
            <div class="nav-signin border">
                <p><span>Hello , sign in</span></p>
                <p class="nav-second">Account & list</p>
            </div>
            <div class="nav-return border">
                <p><span>Returns</span></p>
                <p class="nav-second">& Orders</p>
            </div>
            <div class="nav-cart border">
                <i class="fa-solid fa-cart-shopping"></i>
                Cart
            </div>
        </div>
        <div class="pannel">
            <div class="pannel-all">
                <i class="fa-solid fa-bars"></i>
                Menu
            </div>
            <div class="pannel-ops">
                <p>Todays's deals</p>
                <p>Customers Services</p>
                <p>Registry</p>
                <p>Gift Cards</p>
                <p>Sell</p>
            </div>
            <div class="pannel-deals">
                Shop deals for Electronics
            </div>
        </div>
    </header>
    <div class="hero-section">
        <div class="hero-msg">
            You are on amozonclone.com . you can shop on amozon India for millions of products with fast delivery.
            <a>click here to go amozon.in</a>
        </div>
    </div>
    <div class="shop-section">
        <div class="box1 box">
            <div class="box-content">
                <h2>Cloths</h2>
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
                <h2>Furnituue</h2>
                <div class="box-img" style="background-image: url('box3_image.jpg');"></div>
                <p>see more</p>
            </div>
        </div>
        <div class="box4 box">
            <div class="box-content">
                <h2>Electronics</h2>
                <div class="box-img" style="background-image: url('box4_image.jpg');"></div>
                <p>see more</p>
            </div>
        </div>
        <div class="box5 box">
            <div class="box-content">
                <h2>Beauty trends</h2>
                <div class="box-img" style="background-image: url('box5_image.jpg');"></div>
                <p>see more</p>
            </div>
        </div>
        <div class="box6 box">
            <div class="box-content">
                <h2>Shops for your pets</h2>
                <div class="box-img" style="background-image: url('box6_image.jpg');"></div>
                <p>see more</p>
            </div>
        </div>
        <div class="box7 box">
            <div class="box-content">
                <h2>New arrivals in toys</h2>
                <div class="box-img" style="background-image: url('box7_image.jpg');"></div>
                <p>see more</p>
            </div>
        </div>
        <div class="box8 box">
            <div class="box-content">
                <h2>Discover new fashions </h2>
                <div class="box-img" style="background-image: url('box8_image.jpg');"></div>
                <p>see more</p>
            </div>
        </div>
    </div>
    <footer>
        <div class="foot-pannel1">
            Back to top
        </div>
        <div class="foot-pannel2">
            <ul>
                <p>Get to Know Us</p>
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
               <p>Make Money With Us</p>
                <a>Sell On Amozon</a>
                <a>Sell Under Amozon Acceletor</a>
                <a>Protect And Build Your Demand</a>
                <a>Amazon Global selling</a>
                <a>Become an Affilate</a>
                <a>Fullfill by Amozon</a>
                <a>Amazon Pay on Merchants</a>
            </ul>
            <ul>
               <p>Let us Help You</p>
                <a>Covid-19 & Amozon</a>
                <a>Your Account</a>
                <a>Amozon Center</a>
                <a>Return Center</a>
            </ul>

        </div>
        <div class="foot-pannel3">
            <div class="logo"></div>
        </div>
        <div class="foot-pannel4">
            <div class="pages">
                <a>Conditions of use & sale</a>
                <a>Privacy notice</a>
                <a>Intrest based ads</a>
            </div>
            <div class="copyright">
                © 1996-2023, Amazon.com, Inc. or its affiliates
            </div>
        </div>
    </footer>
</body>

</html>

**css***

* {
    margin: 0;
    padding: 0;
    font-family: Arial;
    border: border-box;
}

.navbar {
    height: 60px;
    background-color: #0f1111;
    color: white;
    display: flex;
    align-items: center;
    justify-content: space-evenly;
}

.nav-logo {
    height: 50px;
    width: 100px;

}

.logo {
    background-image: url("amazon_logo.png");
    height: 50px;
    width: 100%;
    background-size: cover;
}

.border {
    border: 1.5px solid transparent;
}

.border:hover {
    border: 1.5px solid white;
}


/* box 2 */

.add-first {
    color: #cccccc;
    font-size: 0.85rem;
    margin-left: 5px;
}

.add-second{
    font-size: 1rem;
    margin-left: 5px;
}

.add-icon {
    display: flex;
    align-items: center;
    margin-left: 5px;
}

/* box-3 */

.nav-search{
    display: flex;
    justify-content: space-evenly;
    background-color:pink;
    width: 620px;
    height: 40px;
    border-radius: 4px;
    /* text-align: center; */

}
.nav-search:hover{
    border: 2px solid orange;
}
.search-select{
    background-color: #f3f3f3;
    width: 50px;
    text-align: center;
    border-top-left-radius: 4px;
    border-bottom-left-radius: 4px;
    border: none;
}
.search-input{
    width: 100%;
    border: none;
    font-size: 1rem;
}
.search-icon{
    width: 45px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 1.2rem;
    background-color: rgb(248, 156, 18);
    border-top-right-radius: 4px;
    border-bottom-right-radius: 4px;
    color: #0f1111;
}

/* box-4 */
span{
    font-size: 0.9rem;
}
.nav-second{
font-size: 0.85rem;
font-weight: 900;
}

/* box-6 */
.nav-cart i{
   font-size: 30px;
}
.nav-cart{
font-size: 0.85rem;
font-weight: 900;
}

/* pannel */
.pannel{
    background-color: #222f3d;
    height: 40px;
    display: flex;
    color: white;
    align-items: center;
    justify-content: space-evenly;
}
.pannel-ops p {
    display: inline;
    margin-left: 15px;
}
.pannel-ops{
    width: 70%;
    font-size: 0.85rem;
}
.pannel-deals{
    font-size: 0.9rem;
    font-weight: 900;
}

/* hero-section */
.hero-section{
    background-image: url("hero_image.jpg");
    background-size: cover;
    height: 350px;
    display: flex;
    justify-content: center;
    align-items: flex-end;
}
.hero-msg{
    background-color: white;
    display: flex;
    justify-content: center;
    align-items: center;
    color: black;
    height: 30px;
    font-size: 0.95rem;
    margin-bottom: 25px;
    width: 80%;
}
.hero-msg a{
    color: #007185;
}

/* shop-section */
.shop-section{
    display: flex;
    flex-wrap:wrap;
    justify-content: space-evenly;
    background-color: #e2e7e6;
}
.box{
    border: 2px solid black;
    height: 380px;
    width: 23%;
    background-color: white;
    padding: 20px 0px 15px;
    margin: 10px;
}
.box-img{
    height:300px ;
    background-size: cover;
    margin-top: 1rem;
    margin-left: 1rem;
}
.box-content{
    margin-left: 0.5rem;
    margin-right: 1rem;
}
.box-content h2,p{
    margin-left: 1rem;
}
.box-content p{
    color: #007185;
}

/* fotter sections */
footer{
    margin-top: 15px;
}
.foot-pannel1{
    background-color: #37475a;
    color: white;
    height: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 0.85rem;
}
.foot-pannel2{
    display: flex;
    background-color: #222f3d;
    color: white;
    height: 300px;
    justify-content: space-evenly;
}
ul{
    margin-top: 20px;
}
ul a{
    display: block;
    font-size: 0.85rem;
    margin-top: 10px;
    color: #dddddd;
}
.foot-pannel3{
    background-color: #222f3d;
    color: white;
    border-top: 0.5px solid white;
    height: 70px;
    display: flex;
    justify-content: center;
    align-items: center;
}
.logo {
    background-image: url("amazon_logo.png");
    height: 50px;
    width: 100px;
    background-size: cover;
}
.foot-pannel4{
    background-color: #0f1111;
    color: white;
    height: 80px;
    /* display: flex;
    justify-content: center;
    align-items: center; */
}
.pages{
   font-size: 0.85rem;
   align-items: center;
   padding-top: 25px;
   display: flex;
   justify-content: center;
}
.copyright{
    font-size: 0.85rem;
   padding: 5px;
    align-items: center;
    display: flex;
    justify-content: center;
}
