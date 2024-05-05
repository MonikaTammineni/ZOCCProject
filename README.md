# ZOCCProject
#The code from css file starting line to the before the services of the css 
body, html{
  background-color: #fff;  
  font-family: 'Playfair Display', serif;
  overflow-x: hidden !important;
  margin: 0px !important;
  padding: 0px !important;

}
*{
    text-decoration: none !important;
}

.nav{
    position: fixed;
    z-index: 1000;
    top: 0;
    right: 0;
    left: 0;
    height: 80px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    padding: 0 25px 0 25px;
    background-color: #fff;
    box-shadow: 0 19px 38px rgba(0,0,0,0.10);
    border-bottom-left-radius: 10px;
    border-bottom-right-radius: 10px;
}
.nav .links a{
    margin-right: 25px;
    font-size: 16px;
    font-weight: 600;
    color: #000;
}
.nav .links .mainlinks{
    color: #e0501b;
}
.nav .links a:hover{
    color: #007bff;
}
.nav .links .button {
    padding: 8.5px 34px;
    margin-left: 65px;
    display: inline-block;
    padding: 10.5px 36px;
    font-size: 14px;
    color: #000;
    -o-transition: all .4s ease-in-out;
    -webkit-transition: all .4s ease-in-out;
    transition: all .4s ease-in-out;
    text-transform: capitalize;
    border: 1px solid #e4e6ea;
    font-family: 'Playfair Display', serif;
}
.nav .links .button:hover{
    color: #007bff;
}

/* Landing CSS */
.landing{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    padding: 0 10vw 0 10vw;
    height: 10vh;
}
.landingText h1{
    font-size: 6vw;
    margin: 0 !important;
}
.landingText h3{
    margin: 6px !important;
    font-size: 15px;
    line-height: 1.8;
    color: #777777;
    font-family: 'Playfair Display', serif;
    padding-right: 20px;
}
.landingText .btn{
    width: 120px;
    margin-top: 30px;
    padding: 14px 20px 12px 20px;
    background-color: #007bff;
    border-radius: 45px;
    text-align: center;
}
.landingText .btn a{
    font-size: 1.2vw;
    color: #fff;
}
.landingImage img{
    width: 28vw;
}
