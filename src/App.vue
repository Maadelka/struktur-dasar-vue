

<template>

  <!-- <h1 :class="ha1" class="text-2xl">hello : {{message}}!</h1>

  <button @click="ubah">ubah </button>
  <h2>{{count}}</h2> -->
  <nav class="w-full h-14 bg-gray-700 flex">
    <div class="w-[20%] h-full flex justify-center items-center text-2xl font-semibold text-gray-50">{{namaPerusahaan}}</div>
    <div class="w-[80%] h-full flex justify-evenly items-center">
      <p class="text-slate-400 hover:text-slate-100 cursor-pointer">home</p>
      <p class="text-slate-400 hover:text-slate-100 cursor-pointer">software</p>
      <p class="text-slate-400 hover:text-slate-100 cursor-pointer">hardware</p>
      <p class="text-slate-400 hover:text-slate-100 cursor-pointer">about</p>
    </div>
  </nav>


  <header class="w-full h-40 bg-cyan-700"></header>

  <main class="flex w-full">
    <div class="w-[70%] h-60 bg-slate-600"></div>
    <aside class="w-[30%] h-60 bg-neutral-500"></aside>
  </main>

  <footer class="w-full h-40 bg-zinc-800"></footer>

</template>



<script>
  export default {
    data() {
      return {
        namaPerusahaan: 'Maadelka',
        ha1: 'hasatu',
        count: 1
      }
    },
    // method / blueprint
    methods: {
    ubah() {
      // update component state
      this.count++
    }
  }
  }
</script>


<style>
  .hasatu{
    color: blue;
  }
</style>
