<template>
  <div class="header">
      <div id="logo-container">
        <router-link to="/" ><img src="../assets/img/cupcakes & cookies.png" />Logo</router-link>
      </div>
      <div id="header-links-container">
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

<style>
.header {
  border: 1px solid gray;
  display: flex;
}

#logo-container {
  flex: 1;
}

#header-links-container {
  flex: 1;
  display: flex;
  justify-content: flex-end;
  align-items: center;
}
</style>