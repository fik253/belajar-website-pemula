# belajar-website-pemula
baru belajar buat website

HTML

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="belajar.css">
</head>
<body >

     <link rel="stylesheet" href="">
    <!-- NAVIGATION BAR -->
    <div class="navigation">
        <ul class="ul_navigation">
            <li class="li_navigation"><a href="halaman_1.html" class="pi">HALAMAN 1</a></li>
            
            <li class="li_navigation"><a href="halaman_2.html" class="pi">HALAMAN 2</a></li>
            <li class="li_navigation"><a href="halaman_3.html" class="pi">HALAMAN 3</a></li>
        </ul>
    </div>
    <!-- NAVIGATION BAR SELESAI -->
    
    <!-- CONTEMT 1 -->
    <Div class="div_img">
     <a href="" class="oke">
        <img src="fikri.png" width="30%" height="30%" class="img1"><h3>buat project namber one</h3> </a>
        
    </Div>
    <!-- CONTEMT 1 END -->
    
    <!-- FOOTER -->
     <div a class="div_footer">
     <H1 a class="footer">BELAJAR BIKIN WEBSITE</H1>
     </div>
    <!-- FOOTER END -->
</body>
</html>


CSS


 *,html {
    margin: 0;
    padding: 0;
 }
 body {
    background-color: rgb(255, 255, 255);
 }

.navigation{
    background-color: rgb(29, 207, 71);
    width: 100%;
    height: 15vh;
}

.ul_navigation{
    display: flex;
    height: 100px;
    justify-content: center;
    align-items: center;

}

.li_navigation {
    list-style-type: none;
    padding: 10px;
    margin: 5px;
    color: rgb(253, 251, 251);
    
}

.li_navigation:hover{
    background-color: rgb(192, 238, 23);
    transition-delay: .3s;
    transition: .4s ease-in-out;
    border-radius: 30px;
}

.pi {
    color: aliceblue;
    text-decoration: none;
}

.div_img{
    background-color: rgb(240, 255, 78);
    display: flex;
    justify-content: center;
    align-items: center;
    height: 75vh;
}


.oke{
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    color: aliceblue;
    background-color: rgb(202, 208, 36);
     text-decoration: none;
     height: 200px;
     width: 200px;
     border-radius: 10%;
     box-shadow:10px 10px 5px 0px rgba(0,0,0,0.75);
-webkit-box-shadow: 10px 10px 5px 0px rgba(0,0,0,0.75);
-moz-box-shadow: 10px 10px 5px 0px rgba(0,0,0,0.75); ;
    
}

.img{
width:30%;
height:30%;

}

.div_footer {
    background-color: rgb(29, 207, 71);
    display: flex;
    justify-content: center;
    align-items: center;
    height: 10vh;
    color: aliceblue;
}
