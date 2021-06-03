<template>
    <div class="book" >
   <div class="max-w-3xl text-white rounded-lg mx-auto my-20 py-8">
       <h1 class="text-4xl font-extrabold px-4 py-8 leading-normal space-y-6">The best free stock photos & videos shared by talented creators.</h1>
       <div class="hold leading-snug">
           <input class="py-5" type="text" placeholder="Search for free photos and videos">
           <h2 class="text-sm text-white font-thin mb-4 justify-center items-center"></h2>
               <b> Suggested: </b> 
           <nuxt-link to="#" class="hover:text-gray-400">background,</nuxt-link> 
           <nuxt-link to="#" class="hover:text-gray-400">text,</nuxt-link> 
           <nuxt-link to="#" class="hover:text-gray-400">typography,</nuxt-link> 
           <nuxt-link to="#" class="hover:text-gray-400">graphic,</nuxt-link> 
           <nuxt-link to="#" class="hover:text-gray-400">design,</nuxt-link> 
           <nuxt-link to="#" class="hover:text-gray-400">more</nuxt-link>           
       </div>
           
        
       </div>
      
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
.text{
    font-size: 36px;
    margin-top: 0;
    margin-bottom: 15px;
    position: relative;
    top:10vh;
}

.hold{
    position: relative;
    left: 2.5vh;
    bottom: 3.7vh;
    font-size: 16px !important;
}

h2{
    line-height: 0;
    font-weight: lighter !important;
}
.book{
    justify-content: center;
    align-items: center;
    display: flex;
    position: relative;
    bottom: 10vh;
    }

@media only screen and (max-width: 600px) {
  .book {
    position: relative !important;
    bottom: 17vh !important;
  }

  h2{
    line-height: 0;
    font-weight: lighter !important;
    font-size: 16px;
}
}  

input{
    height: 100%;
    width: 90%;
    font-size: 17px;
    border-radius: 6px;
    border: none;
    outline: none;
    color: #000;
    padding-left: 15px;
}
</style>