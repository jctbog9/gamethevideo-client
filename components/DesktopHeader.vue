<template>
  <div class="header-container">
    <div class="left-nav">
      <nuxt-link to="/" class="menu-item">
        Game The Video
      </nuxt-link>
    </div>
    <div class="right-nav">
      <nuxt-link to="/reviews" class="menu-item">
        Reviews
      </nuxt-link>
      <nuxt-link to="/news" class="menu-item">
        News
      </nuxt-link>
      <nuxt-link to="/blog" class="menu-item">
        Blog
      </nuxt-link>
      <nuxt-link to="/gallery" class="menu-item">
        Gallery
      </nuxt-link>
      <nuxt-link to="/about-us" class="menu-item">
        About
      </nuxt-link>
      <nuxt-link to="/contact" class="menu-item">
        Contact
      </nuxt-link>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeaderContainer'
}
</script>

<style>
.header-container {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  height: 85px;
  width: 100%;
  background-color: #A92728;
}

.right-nav {
  display: flex;
  flex-direction: row;
}

.menu-item {
  display: flex;
  height: 65px;
  justify-content: center;
  align-items: center;
  margin: 10px 10px;
  padding: 0px 20px;
  color: #ffffff;
  font-weight: bold;
}

.menu-item:hover {
  background-color: #D33F3E;
}
</style>