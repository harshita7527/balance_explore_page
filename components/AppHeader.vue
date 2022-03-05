<template>
  <header class="header">
    <div class="logo">
      <div class="logoIcon">
        <img src="~/assets/explorer.png" alt="logo" />
      </div>
      <div class="logoText">EXPLORER</div>
    </div>
    <div class="searchBox">
      <form>
        <input type="text" v-model="text" placeholder="Search contract address" />
      </form>
      <button class="searchIcon"><img src="~/assets/search.png" alt="search" /></button>
    </div>
  </header>
</template>

<script>
export default {
  name: "AppHeader",
};
</script>

<style scoped>
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1.2rem 2rem;
}

.logo {
  display: flex;
  justify-content: center;
  align-items: center;
}

.logoIcon {
  margin-right: 0.8rem;
}

.logoText {
  font-weight: 700;
}

.searchBox{
  border: 1px solid rgb(182, 178, 178);
  border-radius: 8px;
  padding: 5px 5px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  font-size: 0.8rem;
  width: 30%;
}

.searchIcon{
  height: 18px;
  width: 18px;
}
</style>
