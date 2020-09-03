<template>
  <div class="header-container">
    <div class="left-nav">
      <div class="menu-item">
        Game The Video
      </div>
    </div>
    <div class="right-nav">
      <div class="menu-item">
        Reviews
      </div>
      <div class="menu-item">
        News
      </div>
      <div class="menu-item">
        Blog
      </div>
      <div class="menu-item">
        Gallery
      </div>
      <div class="menu-item">
        About Us
      </div>
      <div class="menu-item">
        Contact
      </div>
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
  margin: 10px 20px;
  color: #ffffff;
  font-weight: bold;
}
</style>