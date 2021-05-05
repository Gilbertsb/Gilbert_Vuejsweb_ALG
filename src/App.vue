<template>
   <div id="app">
    <div class="container">
      
      <router-view/>
       <mob id="men"/>
      <mobileview id="mob"/>
      <rightdiv id="rightbox"/>
      
    </div>
  </div>
</template>
<script>
import rightdiv from '@/components/rightdiv.vue'
import mobileview from '@/components/mobileview.vue'
import mob from '@/components/menu.vue'
export default {
  components:{
    rightdiv,
    mobileview,
    mob,
  }
  
}
</script>

<style>
.container{
        background: white;
        margin-left: 40px;
        margin-right: 0px;
        width: 95vw;           
        position: absolute;
        padding: 1.5em;
        border-radius: 50px;
        margin-top: 10px;
        box-sizing: border-box;
        min-height: 130vh;
        display: flex;
    }
  #rightbox{
        float: left;
        left: 630px;
        width: 45vw;
        min-height: 90vh; 
        position: right;
        border-radius: 50px;
        background-color: #49a8ff;
        margin-top: 0px;
        margin-left: 20px;
        margin-right: 0px;
  }
  #mob{
        margin-top: 70px;
        min-height: 10vh;
        width: 40vw;  
        border-radius: 20px;
        background-color: #49a8ff;
        box-sizing: border-box;
        display: none;
        flex-direction: row;
        justify-content: space-around;
        
        
  }
  #men{
      display: none;
    }
  @media screen and (max-width: 1096px){

    .container{
      margin-right: 0px;
      margin-left: 0px;
      width: 100%;
      min-height: 870px;
      
    }
    #rightbox{
      display: none;
    }
    #mob{
      display: flex;
      margin-left: 80px;
      width: 60vw;  
      

    }
    #men{
      display: flex;
    }

  }
</style>