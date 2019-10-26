<template>
  <div class="header">
      <div id="logo-container">
        <router-link to="/" ><img src="cupcakes & cookies.png" />Logo</router-link>
      </div>
      <div id="header-links-container">
        <div class="pink-border-box">
          <router-link to="/" ><img src="house.png" class="my-icon" />House</router-link>
        </div>
        <div class="pink-border-box">
          <router-link to="/" ><img src="compass-arrow.png" class="my-icon" />arrow</router-link>
        </div>
        <div class="pink-border-box">
          <img src="file.png" class="my-icon" />
        </div>
        <div class="pink-border-box">
          <router-link to="/" ><img src="question-mark.png" class="my-icon" />Question mark</router-link>
        </div>
        <div class="pink-border-box">
          <router-link to="/" ><img src="person.png" class="my-icon" />Person</router-link>
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

</style>