<template>
 <div class="container firbox">

          <div class="slide">
            <slide :data="slide"/>

          </div>
          

        </div>
      
    
</template>

<script>
import slide from '@wyhaya/vue-slide'
export default {

    data() {
        return {
            slide: [
                    'https://drive.google.com/uc?id=1IppiO1cm-9Y2vAy9hTQHKlzv4lqpUjRZ', 
                    'https://drive.google.com/uc?id=10nkyG0vE3LQ_icK3NR_b2HvRUJY5Pavq', 
                    'https://drive.google.com/uc?id=1E8x15WlPs8CiZvRC7VT0JQgKwz1WUuVQ']
        }
        
    },
    components: { slide}
}
</script>
<style>
.firbox{
        float: left;
        position: right;
        border-radius: 50px;
        background-color: #49a8ff;
        box-sizing: border-box;
    }
.slide{
  margin-top:0px;
  padding: 1.5em;

}

</style>
