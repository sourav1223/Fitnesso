# fitnesso
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Fitness will help u to get fit.">
    <title>Fitness - Get Fit.</title>
    <link rel="shortcut icon" href="icon.svg" type="image/x-icon">

    <style>
        body{
            background-color: rgb(228, 228, 228);
            animation: body_ani forwards 1s;
        }
        @keyframes body_ani {
            0%{
                opacity:0;
                transform: translate(-50px);
            }
            100%{
                opacity: 2;
                transform: translate(0);
            }
            
        }
        *{font-family: 'Rubik', sans-serif;
            margin: 0;
            padding: 0;
            
        }
        .nav-2{
            
            height: 100px;
            width: 100%;
            background-color:rgb(199, 199, 199);
        filter:opacity(0.3);
        position:fixed;
        box-shadow: 2px 2px 8px rgb(199, 199, 199);
        top: 0;
        
        height: 55px;
       }
.nav img{
   
    transform: scale(0.5);
    z-index: 3;
    left: -30px;  
}

.div-icons{
   position: fixed;
   float: right;
    right: 0;
    top: -15px;
    z-index: 10;
    padding: 20px;
    padding-right: -15px;
    
}
#menu{
    cursor: pointer;
  border: none;

    padding: 2.5px;
    z-index: 10; 
    background-color: transparent;
    margin-right: 15px;
     
}
#menu:hover{
    animation: menu-ani forwards alternate 0.5s;
}
@keyframes menu_ani {
    
    
}
#shop{
    cursor: pointer;
    z-index: 11;
    padding: 2px;
    padding-top: 23.5px; 
}
#menu-slide{
    height: 100vh;
    width: 400px;
 border: 1px solid;
    position: fixed;
    top: 0;
    right: 0;
    z-index: -1;
    display: none;
    
}
#menu-slide ul{
    text-align: center;
    background-color: hsl(214, 100%, 87%);
    height: 100vh;
    opacity: 0.9;

}
#menu-slide li{
    list-style-type: none;
    padding: 30px;
    position: relative;
    top: 50px;

}
#menu-slide a{
    text-decoration: none;
    font-size: large;
    color: rgb(0, 0, 0);
   
    padding: 15.5px 50px;
    position: relative;
    top: -4px;
    right: -12px;

}

#menu-slide button{
   color: white;
    background-color: hsl(215, 100%, 22%);
    border: 1px solid;
    padding: 11px;
    position:relative;
    cursor: pointer;
  
}
#menu-slide button a{
    color: white;
}
#menu-slide a:hover{
    filter: opacity(0.8);
    transform: scale(1.2);
    border: 1px dashed;
}
#menu-slide button:hover{
    animation: btn_slide alternate 0.2s forwards ;
}
@keyframes btn_slide {
    0%{
        position: relative;
        right: -15.5px;

    }
    100%{
        position: relative;
        right: -25px;

    }
}
.main_pic{
    border-radius:0.3cm ;
    margin: 15px;
    
    height:100vh;
    width: 55vw;
    object-fit: cover;
    transform: scale(0.9);
     
}
.section-1 .main{
    display: flex;
    justify-content: center;
    align-items: center;
  
}

.section-1 .heading{
    font-size: 55px;
    font-weight: normal;
    margin-right: 20px;
    font-family: 'Sato', sans-serif;
    color: #081158;
}
.section-1 .name{
    font-size: medium;
    margin-bottom: 40px;
    font-family: 'Zen Kurenaido', sans-serif;
    filter: opacity(0.5);
}
.section-1 .arrow img{
    position: relative;

    height: 40px;
    width: 40px;
    cursor: pointer;
    opacity: 0.5;
    background-color: rgb(199, 199, 199);
    
}
.section-1 .arrow_1 button:hover{
    animation:arrow_slide_1 alternate 0.2s forwards;
}
@keyframes arrow_slide_1 { 
    0%{
        transform: translateX(0);  
    }
    100%{

        transform: translateX(-10px);
     
    }
    
} 
.section-1 .arrow_2 button:hover{
    animation:arrow_slide_2 alternate 0.2s forwards;
}
@keyframes arrow_slide_2 {
    0%{
        transform: translate(0px);
        
        
    }
    100%{
        transform: translate(10px);
        
    }
    
}

.section-1 .arrow_1 button{
    border: 1px solid ;
    border-radius: 50%;
    top:-30vh;
    position: relative;
    left: 10vw;
    opacity: 0.8;
    background: transparent;

}
.section-1 .arrow_1 img{
    border-radius: 50%;
    padding: 20px;


}


.section-1 .arrow_2 button{
    border: 1px solid ;
    border-radius: 50%;
    opacity: 0.8;
    background: transparent;
    position: absolute;
    top:-42.5vh;
    position: relative;
    left: 39vw;
    z-index: 4;
}
.section-1 .arrow_2 img{
    border-radius: 50%;
    padding: 20px;

}

.top_text{
    font-size: 50px;
    position: relative;
    left:10vw;
    z-index: -1;
    top: 10vh;
    font-family: 'Kaushan Script', cursive;
    color: rgb(81, 123, 124);
    animation: top_text_ani forwards 1s;
    

}

#main_btn{
    font-size: large;
    font-family: 'Sato', sans-serif;
    margin-top: 30px;
    padding: 20px;
    color: whitesmoke;
    background-color: #081158;
    border-radius: 5px;
    border: 1px solid;
    cursor: pointer;
}
#main_btn:hover{
    animation:main_btn_slide alternate forwards 0.5s;
    opacity: 0.9;
}
@keyframes main_btn_slide {
    0%{
        padding-left: 20px;
        transform: scale(1);
    }
    100%{
        padding-left: 35px;
        transform: scale(1.05);
    }
}
.side-text{
    margin-top: -100px;
}
.side-text .description{
    margin-right: 80px;
    font-size: large;
    padding-top: 20px;
    padding-bottom: 20px;
    opacity: 0.9;
    font-family: 'Sato', sans-serif;
}
.bend_area .area{
    background-color: #081158;
    height: 200px;
    width: 100%;
    color: white;
    transform: skewY(-2.5deg);

    
}
.bend_area .area .text{
    display: grid;
    grid-template-columns: 33.3% 33.3% 33.3%;
    
}
.bend_area .area .text .line{
    text-align: center;
    margin-top: 75px;
}

.section_2{
    background-color:rgb(255, 255, 255);
    padding-top: 50px;
}
.section_2 .heading .text h1{
    margin: 40px;
    margin-top: 90px;
    text-align: center;
    font-weight: 540;
    font-size: 40px;

}
.section_2 .heading_btn{
    text-align: center;
    
    
} 
.section_2 .heading_btn button{
    font-size: large;
    font-family: 'Varela Round', sans-serif;
    padding: 20px;
    color: whitesmoke;
    background-color: #081158;
    border-radius: 5px;
    border: 1px solid;
    cursor: pointer;
}

.section_2 .heading_btn button:hover{
    animation:heading_btn_ani alternate forwards 0.5s;
    opacity: 0.9;
}
@keyframes heading_btn_ani {
    0%{
        padding-left: 20px;
        transform: scale(1);
    }
    100%{
        padding-left: 30px;
        transform: scale(1.06);
    }
}
.section_2 .separate{
    display: grid;
    grid-template-rows:  80vh 80vh;
    margin-top: 100px;
    padding-bottom: 0px;
}
.separate_each{
    display: grid;
    grid-template-columns: 50% 50%;
    text-align: center;
    

   
}
.separate_each img{
    width: 40vw;
    height: 40vh;
    border-radius: 10px;
    object-fit: cover;
    
}
.separate_each h2{
    font-weight: 500;
    font-size:xx-large ;
    padding: 30px;
    color: #081158;
   
}
.separate_each h3{
    font-weight: 100;
    font-size: 18px;
    padding: 20px;
    opacity: 0.75;
}
.section_3 .top_area{
   
    margin-left: 7%;
}
.section_3 .top_area_heading{
    font-size: 70px;
    padding-top: 100px;
    color: #081158;
    font-weight:normal;
    padding-bottom:50px;
}
.section_3 .top_area .top_area_description{
    font-size: 20px;
    padding-bottom: 50px;
    opacity: 0.8;
}
.section_3 button{
    background-color: #081158;
    color: white;
    padding: 25px 30px;
    border: 1px solid;
    border-radius: 10px;
    font-size: medium;
    cursor: pointer;
    
}
.section_3 button:hover{
    animation:view forwards 0.5s;
}
@keyframes  view{
    0%{
        padding-left: 25px;
        padding-right: 25px;
        transform: scale(1);
        opacity: 1;
    }
    100%{
        padding-left: 35px;
        transform: scale(1.05);
        padding-right: 35px;
    opacity: 0.85;
    }
}
.section_3 button span{
    padding-right: 20px;
   
}
.free_plans{
    display: grid;
    grid-template-columns: 20% 20% 20%;
    grid-gap: 13%;
    
  margin-left: 7%;
    margin-top: 100px;
    text-align: center;
    margin-bottom: 100px;
  

    
}
 .free_plans img{
    height: 300px;
   width: 100%;
    text-align: center;
    margin-bottom: 20px;
    object-fit: cover;
    border-radius:10px 10px 0px 0px;
    box-sizing: border-box;
    
}

.free_plans_box_1{ 
   

    width: 140%;
/* display:grid;
grid-template-rows: 300px 100px; */
border-radius: 10px;
border: 1px transparent;
background-color: white;

cursor: pointer; 
}
.free_plans_box_1:hover{
    animation: bow_slide_up 0.7s forwards;
}
.free_plans_box_2{
    border-radius: 10px;
border: 1px transparent;
    width: 140%;
cursor: pointer;
/* display:grid;
grid-template-rows: 300px 100px;  */
background-color: white;


}
.free_plans_box_2:hover{
    animation: bow_slide_up 0.7s forwards;
}
.free_plans_box_3{
    border-radius: 10px;
border: 1px transparent;
width: 140%;
cursor: pointer;
/* display:grid;
grid-template-rows: 300px 100px;  */
background-color: white;


}
.free_plans_box_3:hover{
    animation: bow_slide_up 0.7s forwards;
}
.free_plans p{
    opacity: 0.8;
    text-align: left;
    padding: 15px;
    margin-left: 5%;
}
.free_plans h2{
    color: #081158;
    text-align: left;
    padding: 5px;
    padding-left: 15px;
}
@keyframes bow_slide_up{
    0%{
        opacity: 1;
        position: relative;
        top: 0;
    

    }
    100%{
        opacity: 0.8;
        position: relative;
        top: -10px;
    
        
    }
    
}
.section_4_bg{
    background-image:url("https://assets.website-files.com/5e80894f63c557e083ed96b4/5e808c24d802d6d97489018c_Lines%201.svg"); 
    width: 100%;
    height: 1200px;
    background-repeat: no-repeat;
    background-color: #081158;
    background-size: 50vw;
    background-position: 100% 0%;
    
    
}







.section_4 .top_area{
   
   margin-left: 7%;
}
.section_4 .top_area_heading{
   font-size: 70px;
   padding-top: 100px;
   color: #081158;
   font-weight:normal;
   padding-bottom:50px;
   color: white;
}
.section_4 .top_area .top_area_description{
   font-size: 20px;
   padding-bottom: 50px;
   opacity: 0.8;
   color: white;
}
.section_4 button{
   background-color: #ffffff;
   color: rgb(0, 0, 0);
   padding: 25px 30px;
   border: 1px solid;
   border-radius: 10px;
   font-size: medium;
   cursor: pointer;
   
}
.section_4 button:hover{
   animation:view_4 forwards 0.5s;
}
@keyframes  view_4{
   0%{
       padding-left: 25px;
       padding-right: 25px;
       transform: scale(1);
       opacity: 1;
   }
   100%{
       padding-left: 35px;
       transform: scale(1.05);
       padding-right: 35px;
   opacity: 0.85;
   }
}
.section_4 button span{
   padding-right: 15px;
}
/* .sweat .img{
    
    
    background-repeat: no-repeat;
    background-position: 100% 0%;
    transform: rotateY(180deg);
    z-index: 2;
    object-fit: cover;
    width: 200%;
    
    
    

} */
.sweat .mid_line{
    display: flex;
    justify-content: center;
    
    
    
    font-size: xx-large;
    font-weight: 700;
    color: rgb(0, 0, 0);
    opacity: 1;
    

    
}
.sweat .mid_line p{
    
    margin-top: 27%;
    color: white;
    
    
}
.sweat img{
    position: absolute;
    width: 97vw;
    z-index: -1;
    opacity: 0.7;
    color: white;
}
  

</style>
</head>
<body>
<div class="upper-layer">
    <div class="nav">
        <img src="icon.svg" alt="">
        <div class="div-icons">
        <button id="menu" onclick="menu_func()" name="submit"><img src="menu.png" alt="" height="35px" ></button>
        <buttun id="shop" onclick="shop_func()" name="submit"><img src="shop.png" alt="" height="35px" ></buttun>
        <div id="menu-slide">
            <ul>
                <li><a href="#">ABOUT</a></li>
                <li><a href="#">LOGIN</a></li>
                <li><a href="#">REGISTER</a></li>
                <li><button name="submit"><span><img src="arrow.png" alt=""></span><a href="#">CONTACT US</li></button></a>
                
            </ul>

            
        </div>
        </div>
            

    </div>
    <nav class="nav-2"></nav>
</div>
<div class="section-1">
<div class="main">
    <div class="img-sec">
        <div class="top_text">
            Johnny Sins
        </div>
        <img src="main-pic.png" alt="" class="main_pic">
        <div class="arrow">
            <div class="arrow_1"><button id="arrow_1_btn" onclick="change_img_1()" name="submit"><img src="west.png" alt="side arrow"></button></div>
            <div class="arrow_2"><button id="arrow_2_btn" onclick="change_img_2()" name="submit"><img src="east.png" alt="side arrow"></button></div>
        </div>
    </div>
    <div class="side-text">
        
        <div class="name">
            HI I'M JOHNY SINS
        </div>
        <div class="heading">
            Your go to online fitness trainer and nutritionist.
        </div>
        <div class="description">After getting a bachelors in nutrition and fitness training I started working with people all around and changing their lives forever.

        </div>
        <button id="main_btn" onclick="" name="submit"><pre>>  Online Coaching</pre></button>
    </div>

</div>
<div class="bend_area">
    <div class="area">
        <div class="text">
            <div class="line"><h1>1900+</h1> <div>HAPPY CLIENTS</div></div>
            <div class="line"><h1>5 YEARS</h1> <div>OF EXPERIENCE</div></div>
            <div class="line"><h1>156K </h1><div>FOLLOWING ME</div></div>

        </div>
        
    </div>
</div>
</div>


<div class="section_2">
    <div class="heading">
        <div class="text">
            <h1>The Journey To A Healthier Body Starts Right Now</h1>
        </div>
        <div class="heading_btn"><a href=""><button name="submit">>  ONLINE COACHING</button></a></div>
    </div>

    <div class="separate">
        <div class="separate_each" id="each_1">
            <div class="separate_1">
                <img src="main-pic.png" alt="">
                <h2>Learn to live a healthy life with fitness</h2>
                <h3>Changing your lifestyle with a fast paced life may seem hard or impossible, but with small steps each week you can achieve your dream physique and live a healthier life.</h3>
            </div>
            <div class="separate_2">
                <img src="pic 2.jpeg" alt="">
                <h2>Understand how to do excercises properly</h2>
                <h3>Just going to the gym and lifting weights won't make you healthy, after all it may even cause some harm to your body. We teach proper exercise techniques</h3>


            </div>


        </div>
        <div class="separate_each" id="each_2">
            <div class="separate_3">
                <img src="pic 3.jpeg" alt="">
                <h2>Track your progress weekly</h2>
                <h3>We're tracking your goal weight with body fat measures, weight and general feeling. You may have the same body weight but feel 10x better.</h3>

            </div>
            <div class="separate_4">
                <img src="pic 4.png" alt="">
                <h2>Follow a specific plan made just for you</h2>
                <h3>Everyone is different, and we know it. That's why all of our clients get a programme specific just for their lifestyle and body tipe. This give the best possible results.</h3>

            </div>
        </div>
    </div>

</div>
<div class="section_3">
    <div class="top_area">
        <div class="top_area_heading">
            <p>Free home workouts <br> and fitness plans</p>

        </div>
        <div class="top_area_description">
            <p>With free online classes people who don’t have the time or money to afford a <br><br> personal coach can make change their lives forever.</p>
        </div>
        <button><pre><span>></span>     VIEW ALL</pre></button>
    </div>
    <div class="free_plans">
        <div class="free_plans_box_1">
        <div class="free_plans_img">
        <img src="1.jpeg" alt="">
        </div>
        <div class="free_plans_heading">
        <h2>The Ultimate <br> Abs Workout</h2>
        <br>
        <p>Train Now</p>
        </div>
        
        

        </div>
        <div class="free_plans_box_2">
            <div class="free_plans_img">
            <img src="2.jpeg" alt="">
            </div>
            
                <div class="free_plans_heading">
                <h2>The Perfect <br> Outdoor Workout</h2><br>
        <p>Train Now</p>
        </div>
        </div>
        <div class="free_plans_box_3">
            <div class="free_plans_img">
            <img src="3.jpeg" alt="">
            </div>
            
                <div class="free_plans_heading">
                <h2>Back Day For Everyone</h2><br><br>
        <p>Train Now</p>
        </div>
        </div>
    </div>
</div>
<div class="section_4">
    <div class="section_4_bg">
        <div class="top_area">
            <div class="top_area_heading">
                <p>Free home workouts <br> and fitness plans</p>
    
            </div>
            <div class="top_area_description">
                <p>I’ve created these premium fitness classes for everyone starting<br><br> from beginner to advanced level with an in depth FAQ.</p>
            </div>
            <button><pre><span>></span>     VIEW ALL</pre></button>
        </div>
        <div class="free_plans">
            <div class="free_plans_box_1">
            <div class="free_plans_img">
            <img src="main-pic.png" alt="">
            </div>
            <div class="free_plans_heading">
            <h2>The Ultimate <br> Home Burn</h2>
            <br>
            <p>Train Now</p>
            </div>
            
            
    
            </div>
            <div class="free_plans_box_2">
                <div class="free_plans_img">
                <img src="5.jpeg" alt="">
                </div>
                
                    <div class="free_plans_heading">
                    <h2>The Best<br> Gainers</h2><br>
            <p>Train Now</p>
            </div>
            </div>
            <div class="free_plans_box_3">
                <div class="free_plans_img">
                <img src="6.jpeg" alt="">
                </div>
                
                    <div class="free_plans_heading">
                    <h2>Arms Workout Anywhere</h2><br><br>
            <p>Train Now</p>
            </div>
            </div>
        </div>
    </div>
<div class="sweat">
    <div class="imgages">
        <img src="sweat.png" alt="">
        <img src="lines.svg" alt="" class="li">
        
    
   
        <div class="mid_line">
            <p>SWEAT. GAIN. DO</p>
        </div>
    </div>
    
</div>
</div>




<script>
    function menu_func() {
        let btn = document.getElementById('menu')
        let slide = document.getElementById('menu-slide')
        if (slide.style.display!='none') {
            slide.style.display='none'
            
        } else {
            slide.style.display='block'
            
        }


    }

</script>
</body>
</html>
