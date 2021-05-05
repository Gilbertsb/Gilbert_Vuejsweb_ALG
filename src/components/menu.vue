<template>
  <div id="container">
            <div id="logo">
              <img src="https://drive.google.com/uc?id=1Dqx0I-FNoSOz26LrCs0n1zF8FdVU4Ay6" alt="log">
            </div>
            <div class="customselect">
              <select>
                <option value="0">Menu</option>
                 <option value="1">Courses</option>
                 <option value="2">Features</option>
                 <option value="3">Support</option>
              </select>
            </div>
            <div id="icon2">
            <img src="https://drive.google.com/uc?id=1eSe8zXHW4z_xWrG9aj2pJOC5KA9UTySq" alt="msg" class="img2">
            <img src="https://drive.google.com/uc?id=11WEcfqQj07giuyMUhFKcw56_2CXoiGfy" alt="g" class="imag2">
            </div> 
          </div> 
</template>
<script>

</script>
<style>
#cont{
  width: 100vw;
  background: blue;
}

.imag2{ 
    margin-left: 0px;
    border-radius: 50%;
    width: 35px;
    height: 35px;
}
.img2{
    margin-left: 0px;
    width: 25px;
    height: 25px;
}
 #icon2{
   width: 25vw;
   padding: 3px 0px;
   margin-left: 60px;
   
 }
.customselect{
  margin-left: 30px;
  width: 20vw;
}
 select {
  width: 15vw;
  height: 10vh;
  font-size: 16px;
  font-weight: bold;
  cursor: pointer;
  border-radius: 0;
  background-color: #49a8ff;
  border: none;
  border-bottom: 2px solid #49a8ff;
  color: white;
  padding: 15px;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
  padding: 17px;
  
  
}
select::-ms-expand {
  display: none; 
}
select:hover,
select:focus {
  color: #49a8ff;
  background-color: white;
  border-bottom-color: #DCDCDC;
}
</style>