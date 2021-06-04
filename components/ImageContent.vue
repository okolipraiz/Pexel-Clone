<template>
    <div class="images">

 <div class="grid grid-flow-col grid-rows-5 gap-8">
        <div v-for="result in imageResults" :key="result.id">
          <img :src="result.src.large" width="100%" />

          {{result.id}}
        </div>
      </div>

    </div>
</template>

<script>
// import func from 'vue-editor-bridge'
export default {
  data(){
    return{
      // API results array
        imageResults: [],
        test: 'fff'
    }
  },
   methods: {

       getApiData: function(){
         console.log('getting')
        fetch(`https://api.pexels.com/v1/search?query=random&orientation=portrait`,{
      headers: {
        Authorization: "563492ad6f91700001000001ef12a9cf83974888b31ebfc2bd14aba7"
      }
    })
       .then(resp => {
         return resp.json()
       })
       .then(data => {
         console.log(data.photos)
         console.log(data)
            this.imageResults = data.photos
        //     this.resultsData = data
        //  console.log(this.imageResults)
        //  console.log(this.resultsData)
       })
        },
        
      },
      created() {
        // call API
          this.getApiData()
        }
}
</script>