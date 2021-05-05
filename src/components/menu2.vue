<template>
<div id="menu">
               <nav  id="mn">
                   <a href="#">Courses</a>
                   <a href="#">Features</a> 
                   <a href="#">Support</a>
              </nav>
            </div>
  
</template>

<script>
export default {
  
}
</script>

<style>

    #mn{
        float:left;
        margin-left: 80px; 
        box-sizing: border-box;
        display:inline-block; 
    }
    
#mn a{
  text-decoration:none;
  color:gray; 
  font-size:11px; 
  padding: 20px 3px;
  display:inline-block; 
  transition: all 0.5s ease 0s;
  font-family:Montserrat;
}
  @media screen and (max-width: 1096px){
     #mn{
        float:left;
        margin-left: 80px; 
        margin-top: 20px;
        box-sizing: border-box;
        display:inline-block; 
    }
    
#mn a{
  text-decoration:none;
  color:gray; 
  font-size:11px; 
  padding: 20px 3px;
  display:inline-block; 
  transition: all 0.5s ease 0s;
  font-family:Montserrat;
}



  }

</style>
