<template>

  <div class="wrapper mx-auto">
    <div class="card">
      <div class="title">
       
         <header class="lg:px-16 px-6 bg-transparent flex flex-wrap items-center lg:py-0 py-2" id="nav1">
            <div class="hidden lg:flex lg:items-center lg:w-auto w-full" id="menu">
              <nav class="text-black text-center leading-tight font-weight: 900" id="nav1">
                <ul class="lg:flex items-center justify-center text-base text-grey-700 pt-4 lg:pt-0 cursor-pointer" id="navR">
                    <li><nuxt-link to="#" class="lg:p-4 py3 px-0 block   hover:text-gray-400 font-bold leading-tight">Home</nuxt-link></li> 
                    <li><nuxt-link to="#" class="lg:p-4 py3 px-0 block   hover:text-gray-400 font-bold leading-tight">Discover</nuxt-link></li>
                    <li><nuxt-link to="#" class="lg:p-4 py3 px-0 block   hover:text-gray-400 font-bold leading-tight">Videos</nuxt-link></li>
                    <li><nuxt-link to="#" class="lg:p-4 py3 px-0 block   hover:text-gray-400 font-bold leading-tight">LeaderBoard</nuxt-link></li>
                    <li><nuxt-link to="#" class="lg:p-4 py3 px-0 block   hover:text-gray-400 font-bold leading-tight">Challenges</nuxt-link></li>
                </ul>
                </nav>
            </div>
             </header>

        </div>
        </div>

        <ImageContent/>
    </div>
</template>

<script>
import ImageContent from '../components/ImageContent';



export default {
  components: {
  ImageContent,
},
  data(){
    return{

    }
  }
}
</script>


<style>

#nav1{
  text-align: center  !important;
  display: flex !important;
  justify-content: center !important;
  align-items: center !important;
}

</style>
