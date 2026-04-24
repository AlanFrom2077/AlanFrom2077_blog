<script setup>

</script>

<template>
  <div class="relative w-screen h-300 bg-cover bg-center bg-fixed bg-[url(/1.jpg)]">
    <!--遮盖层-->
    <!--<div class="absolute bg-black/15 h-full w-full"></div>-->

    <!--导航栏-->
    <div class="bg-gray-300/50 w-screen h-15">
      <div class="float-left w-1/5 mt-4.5">
        <center>
          <p>AlanFrom2077的小站</p>
        </center>
      </div>

      <div class="center grid grid-cols-4 float-left w-4/5">
        <div class="place-content-center h-15">
          <center>
            <p class="text-black hover:text-white">主页</p>
          </center>
        </div>
        <div class="place-content-center h-15">
          <center>
            <p class="text-balck hover:text-white">项目</p>
          </center>
        </div>
        <div class="place-content-center h-15">
          <center>
            <p class="text-black hover:text-white">博客</p>
          </center>
        </div>
        <div class="place-content-center h-15">
          <center>
            <p class="text-black hover:text-white">资源</p>
          </center>
        </div>
      </div>
    </div>
      
    <div class="w-screen h-screen grid-cols-2 mt-15">
      <div class="float-left ml-15 opacity-50 bg-gray-300/50 w-70 h-200">
      </div>

      <div class="float-left ml-15 opacity-50 bg-gray-300/50 w-200 h-200">
      </div>
    </div>
  </div>
</template>
