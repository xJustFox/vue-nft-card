<script>
export default {
  
}
</script>

<template>
  <div class="my-container">
    <div class="h-full flex-center justify-center">
      <div class="card">
        <img class="w-full rounded-xl" src="/imgs/image-equilibrium.jpg" alt="">  

        <h1 class="title">Equilibrium #3429</h1>
        <p class=" text-slate-400 pb-4">Our Equilibrium collection promotes balance and clam.</p>

        <div class="flex justify-between">

          <div class=" flex-center text-[#00fff7]">
            <img class="img-style" src="/imgs/icon-ethereum.svg" alt="">
            <span class=" font-semibold">0.041 ETH</span>
          </div>

          <div class="flex-center text-slate-400">
            <img class="img-style" src="/imgs/icon-clock.svg" alt="">
            <span>3 days left</span>
          </div>

        </div>
        <hr class="border-slate-600 my-3">

        <div class="flex-center">
          <img class="h-9 border rounded-full me-5" src="/imgs/image-avatar.png" alt="">
          <div class="text-slate-400">Creation of <span class="text-white">Jules Wyvern</span></div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
@use './style/generals.scss' as *;

.my-container{
  @apply h-svh w-full bg-[#0c1729] overflow-y-auto;
  
  .flex-center{
    @apply flex items-center;

  }

  .card{
    @apply w-[356px] p-6 bg-[#15273f] rounded-xl;
  
    .title{
      @apply text-white text-2xl font-medium py-4;
    }
  
    .img-style {
      @apply pe-2 h-4;
    }
  }
}
</style>