<template >
  <div class="flex-none w-full bg-neutral-800 lg:w-8/12 h-4/6 absolute top-2/4 left-2/4 -translate-y-2/4 -translate-x-2/4 rounded-3xl max-w-6xl border-gray-200 border-8 sm:flex">
    <div class=" h-full w-7/12 bg-slate-200 rounded-l-xl ">
      <div class=" relative top-16 text-left ml-20">
        <h2 class=" font-bold text-gray-400 text-4xl w-fit">Name-Brand</h2>
      </div>
      <div class=" w-full relative top-[30%] flex justify-center -translate-y-[30%]">
        <img src="/contrast.svg" class=" w-5/6">
      </div>
      <div class=" relative -bottom-[150px] text-center">
          <h2 class=" font-bold text-gray-400 text-lg">lets Get Started</h2>
          <p class="text-sm text-gray-700">Start From here....</p>
      </div>
    </div>
    <div class=" h-full w-5/12 rounded-r-xl flex align-middle ">
      <form action="" class=" w-[90%] h-[70%] m-auto flex flex-col text-gray-500 text-sm" >
        <h3 class="p-[10px] text-left text-lg">Login</h3>
        <input type="text" name="username" placeholder="Username" class=" w-[100%] p-[5px] rounded-[10px] my-[10px] bg-transparent border-gray-400 border-[1px]">
        <input type="password" name="username" placeholder="Password" class=" w-[100%] p-[5px] rounded-[10px] my-[10px] bg-transparent border-gray-400 border-[1px]">
        <button type="submit" class=" p-[5px] bg-green-900 text-white w-[80%] mx-auto my-[10px] px-6 rounded-md">Login</button>
        <!-- <a href="">Forgot password?</a> -->
        <a href="" class=" my-[10px]">Register</a>
      </form>
    </div>
  </div>
</template>

<script>

export default {

}

</script>

<style>

</style>