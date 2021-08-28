
<template>
    <div>
        <div>
        <img class="center" :src= imageUrl>
        <h2> Isaman </h2>
        <h3> {{msg}} </h3>
        <h3> {{description}} </h3>
        <h3> {{description2}} </h3>
        </div>
    </div>
</template>

<script>
export default {
    data: () => {
        return {
            msg : 'hello world' ,
            description: "I'm a software daveloper " ,
            description2: "This website deploy by heroku" ,
            imageUrl: "https://scontent.fnak3-1.fna.fbcdn.net/v/t1.6435-9/165347293_5123511061056915_1731547566445634050_n.jpg?_nc_cat=109&ccb=1-5&_nc_sid=09cbfe&_nc_eui2=AeGbbOuHhAJFT61GiUZ9PxP4U4KelnMkinxTgp6WcySKfBLuKYYdcEKXaSAVNHjAeLIarrSZRLmE7wNNuJ8q84IO&_nc_ohc=MOAqTFfGwtsAX-oaATt&_nc_ht=scontent.fnak3-1.fna&oh=31600a82036714a8184c966649825602&oe=614F60DA" 
        }
        
    }
}
</script>

<style scoped>
.a {
  color: #42b983;
}
.center {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 200px;
  height: 200px;
}
</style>
