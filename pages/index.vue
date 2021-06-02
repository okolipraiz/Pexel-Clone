<template>
  <div class="wrapper min-h-screen flex justify-center items-center text-center mx-auto">
    <div class="card">
      <div class="title">
       <span class="text-emerald-800">NUXt</span>JS Introduction
        </div>
        </div>


        <ImageContent/>
    </div>
</template>

<script>
import ImageContent from '../components/ImageContent'
export default {
  components: {
  ImageContent
},
  data(){
    return{

    }
  }
}
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/

</style>
