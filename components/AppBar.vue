<template>
        <header class="lg:px-16 px-6 bg-transparent flex flex-wrap items-center lg:py-0 py-2">
             <div class="flex-1 flex justify-between items-center">
                 <nuxt-link to="#"><img src="http://images.pexels.com/lib/api/pexels-white.png" alt="none" width="100px" height="110px" class="logo border-transparent"></nuxt-link>
             </div>
             <label for="menu-toggle" class="cursor-pointer lg:hidden block">
                 
            <img class="fill-current text-gray-900" src="https://mpng.subpng.com/20180422/uve/kisspng-hamburger-button-computer-icons-menu-clip-art-5adcc45cad2da2.9774904315244176287094.jpg" id="ham"  alt="none" width="23" height="20" viewBox= "0 0 20 20" /> 
             <title>menu</title>
             </label>
             
             <input type="checkbox" class="hidden" id="menu-toggle" />

            <div class="hidden lg:flex lg:items-center lg:w-auto w-full" id="menu">
              <nav class="text-white leading-tight font-weight: 900" id="nav1">
                <ul class="lg:flex items-center justify-between text-base text-grey-700 pt-4 lg:pt-0 cursor-pointer" id="navR">
                    <li><nuxt-link to="#" class="lg:p-4 py3 px-0 block   hover:text-gray-400">Explore</nuxt-link></li> 
                    <li><nuxt-link to="#" class="lg:p-4 py3 px-0 block   hover:text-gray-400">License</nuxt-link></li>
                    <li><nuxt-link to="#" class="lg:p-4 py3 px-0 block   hover:text-gray-400">Upload</nuxt-link></li>
                    <li><nuxt-link to="#" class="lg:p-4 py3 px-0 block   hover:text-gray-400 font-bold leading-tight">...</nuxt-link></li>
                    <li><nuxt-link to="#" class="lg:p-4 py3 px-0 block   hover:text-gray-400"><button class="bg-green-700 active:bg-green-800 focus:ring-2 focus:ring-opacity-75; py-2 px-6 text-white font-bold">Join</button></nuxt-link></li>
                </ul>
                </nav>
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
    z-index: 9999;

}

#navR{
    position: relative !important;
    left: 12vh  !important;
    margin-right: 1rem;
    cursor: pointer !important ;
    z-index: 9999;
}

#menu{
    z-index: 9999;
}

#ham{
    position: relative;
    top: 2.5vh;
    background-color: transparent;
    filter: invert(var(--value, 100%)); --value:100%;
    z-index: 9999;
}

#menu-toggle:checked + #menu{
    display: block;
    cursor: pointer !important;
    background: #444;
}

button{
 border-radius: 4px;
}



</style>