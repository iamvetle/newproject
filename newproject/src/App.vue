<template>

<!--  border-2 border-dashed border-red-800 -->


<div class="pt-9 pb-9 h-auto" > <!-- CONTAINER FOR HEADER/NAVBAR-->
  <header id="header" class="mx-auto w-11/12 lg:w-4/6 xl:w-[62.5%]">
      <img class="ms-2 inline" src="vite.svg" alt="Logo"> <!-- 2/12-->
      <ul class=" list-none inline float-right space-x-8"> <!-- 10/12 -->
        <li class="me-3 inline font-semibold">Hello</li>
        <li class="me-3 inline font-semibold">Product</li>
        <li class="me-3 inline font-semibold">About</li>
        <li class="me-3 inline font-semibold">Searhc?</li>
        <li class="me-3 inline font-semibold">Contact</li>
        <li class="rounded-sm inline bg-blue-800 py-2 px-3 text-white">CALL TO ACTION</li>
      </ul>
  </header>
</div>

  <main> <!-- h1 and p, 8/12-->
    <div class="bg-gray-600">
      
      <section class=" hero-section h-[70vh] text-white bg-gray-600 w-11/12 lg:w-4/6 xl:w-[62.5%] mx-auto">
        
        <div class="w-8/12"> <!-- 8/12 -->
          <h1 class="text-7xl ms-[10%] mt-[15%] font-medium">The Headline that saves Lives</h1>
          <p class="ms-[10%] mt-7 w-3/5 text-lg leading-8">I can do it. Therefore you can take your trust in my hands. Then you can do it.</p> <!-- Description 1-3 lines-->
          <button class="ms-[10%] mt-9 bg-blue-800 text-white px-5 py-4 rounded-md">SIGN UP NOW</button>
        </div>

          <div class="4/12"></div> <!-- 4/12 -->
      </section>
    </div> 
  
  </main>
  <hr id="fold">


</template>

<script>

export default {
  data() {
    return {
      logo: '/vites'

    }
  }
}
</script>