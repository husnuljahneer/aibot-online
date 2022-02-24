<template>
  <div
    class="
      hidden
      sm:hidden
      md:flex
      lg:flex
      bg-white
      justify-center
      w-full
      py-1
      top-0
      z-20
      px-1
      sm:px-1
      md:px-20
      lg:px-20
    "
  >
    <div class="navbar justify-center text-black w-11/12 " id="nav">
      <div class="md:flex px-2 mx-2 navbar-center lg:flex">
        <span class="text-4xl font-medium font-serif text-black">
          AIBOT
        </span>
      </div>
    </div>
  </div>
  <router-view :key="$route.fullPath"></router-view>
</template>

<script>
export default {};
</script>


<style>
#nav a.router-link-exact-active {
  color: rgb(85, 85, 238);
}
</style>
