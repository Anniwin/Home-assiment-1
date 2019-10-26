<template>
  <div class="header">
      <div class="logo-container">
        <router-link to="/" ><img src="../assets/img/cupcakes & cookies.png" />Logo</router-link>
      </div>
      <div class="header-links-container">
        <div class="pink-border-box">
          <router-link to="/" ><img src="../assets/img/house.png" class="my-icon" />House</router-link>
        </div>
        <div class="pink-border-box">
          <router-link to="/" ><img src="../assets/img/compass-arrow.png" class="my-icon" />arrow</router-link>
        </div>
        <div class="pink-border-box">
          <router-link to="/" ><img src="../assets/img/file.png" class="my-icon" />File</router-link>
        </div>
        <div class="pink-border-box">
          <router-link to="/" ><img src="../assets/img/question-mark.png" class="my-icon" />Question mark</router-link>
        </div>
        <div class="pink-border-box">
          <router-link to="/" ><img src="../assets/img/person.png" class="my-icon" />Person</router-link>
        </div>
      </div>
    </div>
</template>

<script>
export default {
name: 'TheHeader'
}
</script>

<style lang="scss" scoped>
.header {
  display: grid;
  grid-template-rows: repeat(2, 1fr);
  padding: 10px;
  }
  .logo-container{
    a {
      display: block;
      height: 82px;
      width: 282px;

    }
  }
  .header-links-container {
display: grid;
grid-template-columns: repeat(5, 1fr);
grid-gap: 10px;
}
@media (min-width: 1024px){
.header {
  border: 1px solid gray;
  display: flex;
}
@media (min-width: 768px) and (max-width: 1023px) {
  //tablet
   .header {
  display: grid;
  grid-template-rows: 1fr;
  grid-template-columns: 1fr 2fr;
  grid-gap: 20px;
  padding: 10px;
  }

}

}



</style>