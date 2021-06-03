<template>
    <div class="book px-4 items-center" >
   <div class="max-w-3xl text-white rounded-lg mx-auto my-20 py-8">
       <h1 class="text-4xl font-extrabold px-4 py-8 leading-relaxed">The best free stock photos & videos<br> shared by talented creators.
        <input class="py-5" type="text" placeholder="Search for free photos and videos">
        </h1>
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

.book{
    position: relative;
    bottom: 10vh;
    left: 10vh;
    }

  @media only screen and (min-width: 783px) {
  .book {
    padding-right: 10px;
    padding-left: 10px;
  }
} 

input{
    height: 100%;
    width: 90%;
    font-size: 17px;
    border-radius: 6px;
    border: none;
    outline: none;
    color: #101010;
    padding-left: 10px;
}
</style>