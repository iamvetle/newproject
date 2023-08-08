<template>

<!--  border-2 border-dashed border-red-800 -->


<div class="pt-9 pb-9" > <!-- FLEX-CONTAINER FOR HEADER/NAVBAR-->
  <header id="header" class="mx-auto w-11/12 lg:w-4/6 xl:w-[62.5%]">
      <img class="ms-2 inline" src="vite.svg" alt="Logo"> <!-- 2/12-->
        <ul id="menu-links" class=" list-none inline float-right space-x-8"> <!-- 10/12 -->
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
    <div class="bg-gray-600"> <!-- FLEX-CONTAINER for Hero section -->
      
      <section class="hero-section min-h-[550px] h-[70vh] text-white bg-gray-600 w-11/12 lg:w-4/6 xl:w-[62.5%] mx-auto">
        
        <div class="w-8/12 ps-[10%] pt-[15%] "> <!-- 8/12 -->
          <h1 class="text-7xl font-medium">The Headline that saves Lives</h1>
          <p class="pt-7 w-3/5 text-lg leading-8">I can do it. Therefore you can take your trust in my hands. Then you can do it.</p> <!-- Description 1-3 lines-->
          <button class="mt-9 bg-blue-800 text-white px-5 py-4 rounded-md">SIGN UP NOW</button>
        </div>

          <div class="4/12"></div> <!-- 4/12 -->
      </section>
    </div>

      <!-- ROW 1 -->

      <div class="bg-[#F7F7F7]"> <!-- FLEX-CONTAINER for row-->
        <section id="row1" class="py-[65px] mx-auto w-11/12 lg:w-4/6 xl:w-[62.5%]">

          <h2 class="text-4xl pt-4 pb-7 text-center">lorem ipsum</h2>
        
          <div class="inline-block w-4/12 px-1 py-2 mx-auto ">          
            <img alt="" src="https://geocominstal.ro/wp-content/uploads/2018/11/blog-ph.jpg" class="block h-auto max-h-96 w-auto mx-auto">
            <p class="block pt-4 text-base">Lorem ipsum dolor sit amet consectetur adipisicing elit. Nostrum voluptatum facilis iusto ducimus explicabo, id dicta assumenda neque quibusdam vero maiores pariatur atque voluptates, unde tempora, nihil molestias illo non.</p>
          </div>
          <div class="inline-block w-4/12 px-1 py-2 mx-auto ">          
            <img alt="" src="https://geocominstal.ro/wp-content/uploads/2018/11/blog-ph.jpg" class="block h-auto max-h-96 w-auto mx-auto">
            <p class="block pt-4 text-base">Lorem ipsum dolor sit amet consectetur adipisicing elit. Nostrum voluptatum facilis iusto ducimus explicabo, id dicta assumenda neque quibusdam vero maiores pariatur atque voluptates, unde tempora, nihil molestias illo non.</p>
          </div>
          <div class="inline-block w-4/12 px-1 py-2 mx-auto ">          
            <img alt="" src="https://geocominstal.ro/wp-content/uploads/2018/11/blog-ph.jpg" class="block h-auto max-h-96 w-auto mx-auto">
            <p class="block pt-4 text-base">Lorem ipsum dolor sit amet consectetur adipisicing elit. Nostrum voluptatum facilis iusto ducimus explicabo, id dicta assumenda neque quibusdam vero maiores pariatur atque voluptates, unde tempora, nihil molestias illo non.</p>
          </div>
  
        </section>
      </div>

      <div class="bg-[#FFFFFF]"> <!-- FLEX-CONTAINER for row-->
        <section id="row2" class="py-[65px] mx-auto w-11/12 lg:w-4/6 xl:w-[62.5%] flex items-start">
          <div class="w-7/12 inline-block mx-auto">
            <img alt="" src="https://geocominstal.ro/wp-content/uploads/2018/11/blog-ph.jpg" class="block px-5 h-[500px] w-auto mx-auto">
          </div>
          
          <div class="w-5/12 inline-block mx-auto">
            <h2 class="text-3xl pt-4 ">lorem ipsum dolor sit</h2>
            <p class="pt-3 pe-5">Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam error dignissimos veritatis. Cumque rerum accusamus odit obcaecati autem quidem? Voluptatibus tempore aperiam dolor! Facere, vero eveniet. Incidunt doloremque consequuntur labore!</p>
            <button class="bg-gray-400 rounded-md ms-5 px-6 py-3 mt-5 text-lg ">CTA</button>
          </div>
  
  
        </section>
      </div>

      <div class="bg-[#F8F2EF]"> <!-- FLEX-CONTAINER for row-->

        <section id="row3" class="py-[65px] mx-auto w-11/12 lg:w-4/6 xl:w-6/12" >
          <h1 class="text-4xl text-center">Row 3</h1>

          <div class="w-6/12 inline-block mx-auto px-5 mt-8">
            <h3 class="text-xl ">lorem ipsum dolor sit</h3>
            <p class="pt-3">Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam error dignissimos veritatis. Cumque rerum accusamus odit obcaecati autem quidem? Voluptatibus tempore aperiam dolor! Facere, vero eveniet. Incidunt doloremque consequuntur labore!</p>          
          </div>
          
          <div class="w-6/12 inline-block mx-auto mt-8 px-5">
            <h3 class="text-xl ">lorem ipsum dolor sit</h3>
            <p class="pt-3">Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam error dignissimos veritatis. Cumque rerum accusamus odit obcaecati autem quidem? Voluptatibus tempore aperiam dolor! Facere, vero eveniet. Incidunt doloremque consequuntur labore!</p>          
          </div>

        </section>
      </div>

      <!-- Color row: #FFFFFF -->
      <!-- Color row: #353535 -->


      <!-- Color row: #FFFFFF -->
      <!-- Color row: #F7F7F7 -->
      <!-- Color row: #FFFFFF -->
      <!-- Color row: #F8F2EF -->
      <!-- Color row: #FFFFFF -->
      <!-- Color row: #F8F8F8 -->
      <!-- Color row: #FFFFFF -->

      <!-- Color row: #353535 -->



  </main>
  <hr id="fold">


</template>

<script>

import aboutus from './assets/people-2557396_960_720.jpg'

export default {
  data() {
    return {
      logo: '/vites',
      aboutus

    }
  }
}
</script>