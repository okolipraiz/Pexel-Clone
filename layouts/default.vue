<template>
  
    <div class="background-image font-sans">
   <AppBar />
   <BackGround />
    <Nuxt />
    </div>
    

</template>

<style>
.background-image{
     background-image: url('https://images.pexels.com/photos/2635817/pexels-photo-2635817.jpeg?auto=compress&crop=focalpoint&cs=tinysrgb&fit=crop&fp-y=0.6&h=500&sharp=20&w=1400');
     background-size: cover;
     background-repeat: no-repeat;
     width: 100%;
     height: 500px;
     filter: blur(var(0.5px)); --value:2px;
 }

</style>
