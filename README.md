# Ecommerce-Website
*{
    margin: 0;
    padding: 0;
    box-sizing : border-box;
}
body{
    font-family: 'Poppins', sans-serif;
}
  .navbar{
    display: flex;
    align-items: center;
    padding: 20px;
}
nav{flex: 1;
    text-align: right;
}
nav ul{
    display: inline-block;
    list-style-type: none;
}
nav ul li{
    display: inline-block;
    margin-right: 20px;
}
a{
    text-decoration: none;
    color: #555;
}
p{
    color: #555;
}
.container{
    max-width: 1300px;
    margin: auto;
    padding-left: 25px;
    padding-right: 25px;
}
.row{
    display: flex;
    align-items: center;
    flex-wrap: wrap;
    justify-content: space-around;
}
.col-2{
    flex-besis: 50%;
    min-width: 300px;
}
.col-2 img{
    max-width: 100%;
    padding: 50px 0;
}
.col-2 h1{
    font-size: 50px;
    line-height: 60px;
    margin: 25 px 0;
}
.btn{
    display: inline-block;
    background: #ff523b;
    color:#fff;
    padding: 8px 30px;
    margin: 30px 0;
    border-radius: 30px;
    transition: background 0.5s;
}
.btn:hover{
    background: #563434;
}

}
.header{
     background: radial-gradient(#fff,#ffd6d6);
}
.header .row{
    margin-top: 70px;

}
.categories{
    margin: 70px 0;
}
.col-3{
    flex-basis: 30%;
    min-width: 250px;
    margin-bottom: 30px;
}
.small-container{
    max-width: 1080px;
    margin: auto;
    padding-left: 25px;
    padding-right: 25px;
}
.col-4{
    flex-basis: 25%;
    padding: 10px;
    min-width: 200px;
    margin-bottom: 50px;
    transition: transform 0.5s;
}
.col-4 img{
    width: 100%;

}
.title{
    text-align: center;
    margin: 0 auto 80px;
    position: relative;
    line-height:  60px;
    color: #555:
}
.title::after{
   content:  " ";
   background: #ff523b;
   width: 80px;
   height: 5px;
   border-radius: 5px;
   position: absolute;
   bottom: 0;
   left: 50%;
   transform:translateX(-50%);
}
h4{
    color: #555;
    font-weight: normal;
}
.col-4 p{
    font-size: 14px;
}
.col-4:hover{
    transform: translatey(-5px);
}
.testimonials{
    padding-top: 100px;
}
.testimonial col-3{
    text-align: center;
    padding: 40px 20px;
    box-shadow: 0 0 20px 0 rgba ( 0,0,0,0.1);
    cursor: pointer;
    transition: transform 0.5s
}
.testimonial col-3 img{
    width: 50px;
    margin-top: 20px;
    border-radius: 50%;
}
.testimonial .col-3:hover{
    transform: translateY(-10px);
}
.menu-icon{
    width: 28px;
    margin-left: 20px;
}
