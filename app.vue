<template>
  <div class="index">
      <Header />
      <router-view></router-view>
      <Footer></Footer>
  </div>
</template>

<style lang="scss">
*,
*::before,
*::after {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
</style>