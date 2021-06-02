<template>
        <header class="lg:px-16 px-6 bg-transparent flex flex-wrap items-center lg:py-0 py-2">
             <div class="flex-1 flex justify-between items center" id="push">
                 <nuxt-link to="#"><img src="http://images.pexels.com/lib/api/pexels-white.png" alt="none" width="110px" height="120px" class="logo"></nuxt-link>

             <label for="menu-toggle" class="cursor-pointer lg:hidden block">
                 
            <img id="ham" class="fill-current text-gray-900" src="data:image/png;base64,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"  alt="none" width="28" height="25" viewBox= "0 0 20 20"> 
             <title>menu</title>
             </label>
             
             <input type="checkbox" class="hidden" id="menu-toggle">

            <div class="hidden lg:flex lg:items-center lg:w-auto w-full" id="menu">
              <nav class="text-white leading-tight font-weight: 900;">
                <ul class="lg:flex items-center justify-between text-base text-grey-700 pt-4 lg:pt-0" id="navR">
                    <li><nuxt-link to="#" class="lg:p-5 py3 px-0 block  border-transparent hover:text-gray-400">Explore</nuxt-link></li> 
                    <li><nuxt-link to="#" class="lg:p-5 py3 px-0 block  border-transparent hover:text-gray-400">License</nuxt-link></li>
                    <li><nuxt-link to="#" class="lg:p-5 py3 px-0 block  border-transparent hover:text-gray-400">Upload</nuxt-link></li>
                    <li><nuxt-link to="#" class="lg:p-5 py3 px-0 block  border-transparent hover:text-gray-400 font-bold leading-tight">...</nuxt-link></li>
                    <li><nuxt-link to="#" class="lg:p-5 py3 px-0 block  border-transparent hover:text-gray-400"><button class="bg-green-700 active:bg-green-800 focus:ring-2 focus:ring-opacity-75; py-2 px-6 text-white font-bold">Join</button></nuxt-link></li>
                </ul>
                </nav>
            </div>
             </div>
             </header>
             
</template>

<script>
    export default {
        
    }
</script>

<style scoped>



.logo{
    position: absolute;
    top: 2.1vh;
    left: 2.5vh  !important;
}

#navR{
    position: relative !important;
    left: 10vh  !important;
    margin-right: 1rem;
}

#ham{
    position: relative;
    top: 2.5vh;
    background-color: transparent;
    filter:opacity(10)
}

#menu-toogle:checked + #menu{
    display: block;
}

button{
 border-radius: 4px;
}
/* img{
    
} */


</style>