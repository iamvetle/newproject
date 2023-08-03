<template>
<div id="container" class="long-container pt-9 pb-9 border-2 border-dashed border-red-800" > <!-- CONTAINER FOR HEADER/NAVBAR-->
  <header id="header" class="border-2 border-dashed border-green-800 mx-auto w-11/12 lg:w-4/6 xl:w-[62.5%]">
      <img class="ms-2 inline-block" src="" alt="Logo"> <!-- 2/12-->
      <ul class=" list-none inline-block float-right space-x-4"> <!-- 10/12 -->
        <li class="me-3 inline font-semibold">Hello</li>
        <li class="me-3 inline font-semibold">Product</li>
        <li class="me-3 inline font-semibold">About</li>
        <li class="me-3 inline font-semibold">Searhc?</li>
        <li class="me-3 inline font-semibold">Contact</li>
        <li class="rounded-sm inline bg-blue-800 p-2 text-white">CALL TO ACTION</li>
      </ul>
  </header>
</div>

  <main> <!-- h1 and p, 8/12-->
    <div class="long-container bg-gray-600">
      
      <section class=" hero-section relative h-[70vh] border-2 border-dashed text-white bg-gray-600 w-11/12 lg:w-4/6 xl:w-[62.5%] mx-auto">
        
        <div class="w-8/12"> <!-- 8/12 -->
          <h1 class="text-7xl ms-[15%] mt-[20%] ">Headline</h1>
          <p class="ms-[15%] pt-5 w-3/5 text-lg">I can do it. Therefore you can take your trust in my hands. Then you can do it.</p> <!-- Description 1-3 lines-->
          <button class="bg-blue-800 text-white p-4 rounded-md">SIGN UP NOW</button>
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

    }
  }
}
</script>