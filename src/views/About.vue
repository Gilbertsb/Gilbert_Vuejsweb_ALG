<template>
  <div class="about">
        <div class="secbox">
          <div id="container">
            <div id="logo">
              <img src="https://drive.google.com/uc?id=1Dqx0I-FNoSOz26LrCs0n1zF8FdVU4Ay6" alt="log">
            </div>
            <div id="menu">
               <nav>
                   <a href="#">Courses</a>
                   <a href="#">Features</a> 
                   <a href="#">Support</a>
              </nav>
            </div>
            <div id="icon">
            <img src="https://drive.google.com/uc?id=1eSe8zXHW4z_xWrG9aj2pJOC5KA9UTySq" alt="msg" class="img">
            <img src="https://drive.google.com/uc?id=11WEcfqQj07giuyMUhFKcw56_2CXoiGfy" alt="g" class="imag">
            </div> 
          </div>

          <div id="text">
          <h1>Study different areas of web design easily in 3 steps:</h1>
          </div>

          <div id="list">
            <ul>
              <li><b>.01</b>Visti our website</li>
              <li><b>.02</b>Sign up</li>
              <li><b>.03</b>Find the course you want</li>
           </ul>
          </div>

          <div class="button">Sign in</div>

        </div>

       
    </div>
</template>

<style>
 body {background-color: #ecf1f5;}
    .secbox{
        float: left;
        width: 40vw;
        min-height: 80vh;
        position: left;
        box-sizing: border-box;
        position: absolute;
        
    

    }

    nav{
        float:right;
        margin-left: 80px; 
        box-sizing: border-box;
    }
    
nav a{
  text-decoration:none;
  color:gray; 
  font-size:12px; 
  padding: 20px 5px;
  display:inline-block; 
  transition: all 0.5s ease 0s;
  font-family:Montserrat;
}
#logo{
  font-size:15px; 
  color:black; 
  font-weight:bold;
  float:left;
  padding: 20px 15px; 
  margin-left:30px;
  font-family:Montserrat;
  
}

#container{
    width: 45vw;
    padding: 10px 7px;
    height: 100px;
    margin-left: 0px;
    box-sizing: border-box;

}
#menu{
    float:left;

}

#text{
    margin-top:50px;
    margin-left: 80px;
    width: 30vw;
    box-sizing: border-box;
}

h1{
    font-family:Signika Negative;
    font-style:bold;
    font-size:42px;
    color:black;
    box-sizing: border-box;

}
#list{
    margin-top:60px;
    margin-left: 70px;
    box-sizing: border-box;
}

#list ul li{
       margin-top:20px;
       list-style-type: none;
       font-family:Montserrat;
       font-size: 17px;

}

b{
       margin-right:20px;
       color: cornflowerblue;
       font-size: 10px;
       font-family:Montserrat Medium;
       

}
.button {

  margin-top:60px;
  margin-left: 80px;
  padding: 22px 80px;
  display: inline-block;
  background-color: cornflowerblue;
  border-radius: 40px;
  text-align: center;
  font-size: 17px;
  color: white;
  font-family:Montserrat Medium;
  font-style:bold;
  font-size: 17px;

  
}
.imag{
    border-radius: 50%;
    width: 40px;
    height: 40px;
    
}
.img{
    width: 30px;
    height: 30px;
    
}
#icon{
    float:right;
    padding: 0px 7px;
    box-sizing: border-box;
}
 @media screen and (max-width: 1096px){
   #text{
     margin-top: 30px;
     margin-left: 25px;
     width: 70vw;
     min-height: 20vw;
     

   }
   .button{
     align-items: center;
   }
   #list{
     margin-top: 10px;
     margin-left: 10px;
   }
   .secbox{
     margin-top: 400px;
     margin-right: 0px;
     width: 60vw;
   }
   h1{
     font-size:25px;
   }
   #list ul li{
       font-size: 15px;

}
#container{
  display: none;
}


 }
</style>
