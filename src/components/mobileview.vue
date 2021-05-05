<template>

 <div class="container firbox">
          <div class="slide">
            <slide :data="slide"/>
          </div>
        </div>
      
</template>

<script>
import slide from '@wyhaya/vue-slide'
import men from '@/components/menu2.vue'
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
        
        box-sizing: border-box;
        display: flex;
        flex-direction: column;
        justify-content: space-around;
        align-items: center;
    }
.slide{
  margin-top:0px;
  padding: 1.5em;

}
.imag{
    border-radius: 50%;
    width: 40px;
    height: 40px;
    padding: 5px 7px;
}
.img{
    margin-left: 15px;
    padding: 10px 7px;
    width: 35px;
    height: 35px;
}

</style>
