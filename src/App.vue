<template>
  <div class="overflow-y-hidden bg-gray-200 " >
        <div class=" bg-white sticky top-0 z-40 ">
            <nav class="shadow-lg 2xl:mx-auto sm:py-6 sm:px-7 py-5 lg:px-28 px-4">
                <!-- For large and Medium-sized Screen -->
                <div class="flex justify-between "> 
                    <div class="hidden sm:flex flex-row items-center space-x-6">
                        <img class=" focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-gray-800 cursor-pointer" src="https://i.ibb.co/GCQ9kb7/fb.png" alt="twitter" />                       
                       <img class="focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-gray-800 cursor-pointer" src="https://i.ibb.co/cQ5zTmT/twitter.png" alt="facebook" />
                        <img class="focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-gray-800 cursor-pointer" src="https://i.ibb.co/gR9RR8q/ig.png" alt="linkdin" />
                        <img class="focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-gray-800 cursor-pointer" src="https://i.ibb.co/qMwSVbQ/in.png" alt="instagram" />                                                             
                    </div>
                    <div class=" flex space-x-3 items-center">
                        <img class="w-32 pt-3" src="https://i.ibb.co/5cQ1XcT/clogo.png" alt="logo" />                 
                        <h1 class=" font-normal text-2xl leading-6 text-gray-800" ></h1>
                    </div>
                    <div class="hidden sm:flex flex-row space-x-4">
                        <button @click="scrollToAnchorPoint('services')" class="rounded-md flex space-x-2 w-24 h-10 font-normal text-sm leading-3 text-indigo-700 bg-white border border-indigo-700 focus:outline-none focus:bg-gray-200 hover:bg-gray-200 duration-150 justify-center items-center" >Our services</button>
                        <button @click="scrollToAnchorPoint('footer')" class="rounded-md flex space-x-2 w-24 h-10 font-normal text-sm leading-3 text-white bg-indigo-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-700 focus:bg-indigo-600 hover:bg-indigo-600 duration-150 justify-center items-center" >Footer</button>
                    </div>

                    <!-- Burger Icon -->
                    <div id="bgIcon" @click="toggleMenu()"  class="focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-gray-800  flex justify-center items-center sm:hidden cursor-pointer">
                        <img src="https://tuk-cdn.s3.amazonaws.com/can-uploader/header-3-svg6.svg" alt="burger" />
                       <img class=" hidden" src="https://tuk-cdn.s3.amazonaws.com/can-uploader/header-3-svg7.svg" alt="cross" />                                                               
                    </div>
                </div>

                <!-- Mobile and small-screen devices (toggle Menu) -->
                <div id="MobileNavigation" class="hidden sm:hidden mt-4 mx-auto shadow-md">
                    <div class="flex flex-row items-center justify-center space-x-6 pt-2">
                        <img src="https://tuk-cdn.s3.amazonaws.com/can-uploader/header-3-svg1.svg" alt="twitter" />                       
                        <img src="https://tuk-cdn.s3.amazonaws.com/can-uploader/header-3-svg2.svg" alt="facebook" />
                        <img src="https://tuk-cdn.s3.amazonaws.com/can-uploader/header-3-svg3.svg" alt="linkdin" />
                        <img src="https://tuk-cdn.s3.amazonaws.com/can-uploader/header-3-svg4.svg" alt="instagram" />                                                             
                    </div>
                    <div class="flex flex-col gap-4 mt-4 w-80 mx-auto pb-2 ">
                        <button @click="scrollToAnchorPoint('services')" class="rounded-md flex space-x-2 w-full h-10 font-normal text-sm leading-3 text-indigo-700 bg-indigo-600 bg-opacity-0 hover:opacity-100 duration-100 border border-indigo-700 focus:outline-none focus:bg-gray-200 hover:bg-gray-200 duration-150 justify-center items-center" >Our services</button>
                        <button @click="scrollToAnchorPoint('footer')" class="rounded-md flex space-x-2 w-full h-10 font-normal text-sm leading-3 text-white bg-indigo-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-700 focus:bg-indigo-600 hover:bg-indigo-600 duration-150 justify-center items-center" >Footer</button>
                    </div>
                </div>
            </nav>    
        </div>

     



    </div>
  
  <Slider />
<div class="relative lg:px-28 px-4  container mx-auto grid sm:grid-cols-1 md:grid-cols-2 lg:grid-cols-2 xl:grid-cols-2 pt-16 lg:pt-36 gap-8">
            <div class="text-color -mt-6">
                <h1 class="lg:text-7xl text-6x1 lg:w-1/2 xl:w-full xl:text-8xl font-black f-f-l">Optimal. Durable. Efficient.</h1>
                <div class="f-f-r -mt-4 text-xl lg:text-3xl pb-20 sm:pb-0 pt-10 xl:pt-20">
                    <h2>Are you tired of using a slow PC?</h2>
                    <h2>We would like to give you a PC hardware upgrade.</h2>
                    <h2>Or better yet offer you a deal for a high end machine.</h2>
                </div>
                
            </div>
            <div class="">
                <img class="w-full -mt-8 lg:-ml-16 xl:-ml-44" src="https://i.ibb.co/tsB09wS/de3.png" alt="" />
                <button class="hover:opacity-90 text-xl w-full rounded-lg xl:text-3xl xl:w-10/12 mt-4 xl:mt-11 f-f-r py-6 bg-indigo-700 text-white text-bold">New stock</button>
            </div>
        </div>
        <Product />
        <div class="px-4">
        <button ref="serives" class="hover:opacity-90 text-xl w-full rounded-lg xl:text-3xl xl:w-10/12 mt-4 xl:mt-11 f-f-r py-6  bg-indigo-700 text-white text-bold">Our services</button>
        </div>
        <Services />
        <div class="-mt-8 lg:px-28 px-8">
    
   <p class="">     We are skilled in working with all operating systems and makes of computers. Whether you own a desktop, laptop, iMac, MacBook, all-in-one or touchscreen we can repair your machines software & hardware. <br> Is your computer suffering from :</p>
  </div>
        <div ref="services" class="flex justify-center py-8">
        <div class="inline-grid grid-cols-1 gap-4 ">
        
  <div class="flex">
   <img class="w-4" src="https://i.ibb.co/N7KygVJ/go.png"  alt="go" >
   <p class="">Slow Running Computer</p>
  </div>
  <div class="flex">
    <img class="w-4" src="https://i.ibb.co/N7KygVJ/go.png"  alt="go" >
   <p class="">Computer wont turn on</p>
  </div>
  <div class="flex text-center">
    <img class="w-4" src="https://i.ibb.co/N7KygVJ/go.png"  alt="go" >
   <p class="">Computer randomly freezes</p>
  </div>
  <div class="flex text-center">
    <img class="w-4" src="https://i.ibb.co/N7KygVJ/go.png"  alt="go" >
   <p class="">Can not connect to internet</p>
  </div>
  <div class="flex text-center">
    <img class="w-4" src="https://i.ibb.co/N7KygVJ/go.png"  alt="go" >
   <p class="">Reinstall operating system</p>
  </div>
  <div class="flex text-center">
    <img class="w-4" src="https://i.ibb.co/N7KygVJ/go.png"  alt="go" >
   <p class="">Virus removal</p>
  </div>
  <div class="flex text-center">
    <img class="w-4" src="https://i.ibb.co/N7KygVJ/go.png"  alt="go" >
   <p class="">Spyware removal</p>
  </div>
  <div class="flex text-center">
    <img class="w-4" src="https://i.ibb.co/N7KygVJ/go.png"  alt="go" >
   <p class="">Malware removal</p>
  </div>
  <div class="flex text-center">
    <img class="w-4" src="https://i.ibb.co/N7KygVJ/go.png"  alt="go" >
   <p class="">Screen repair</p>
  </div>
  <div class="flex text-center">
    <img class="w-4" src="https://i.ibb.co/N7KygVJ/go.png"  alt="go" >
   <p class="">Software problems</p>
  </div>
  <div class="flex text-center">
    <img class="w-4" src="https://i.ibb.co/N7KygVJ/go.png"  alt="go" >
   <p class="">Mouse/keyboard/accesory problems</p>
  </div>


  </div>

  
  
</div>
<div class="flex flex-col justify-center items-center pt-6">
<img class="w-64 " src="https://i.ibb.co/vqzXRV9/de4.png" alt="de4" >
</div>
<faq />
  
<div ref="footer" class="pt-12 lg:px-28">
        <footer id="footer" class="relative z-50 dark:bg-gray-900 pt-24">
            
            <div class="py-16 flex flex-col justify-center items-center">
                <img class="w-20" src="https://i.ibb.co/5cQ1XcT/clogo.png" alt="bs1" >
                <p class="mt-6 text-xs lg:text-sm leading-none text-gray-900 dark:text-gray-50">2022 BackSpace Tech. All Rights Reserved.</p>
            </div>
        </footer>
    </div>

</template>

<script>


import Services from './components/Services.vue'
import Slider from './components/Slider.vue'
import Product from './components/Product.vue'
import Faq from './components/Faq.vue'

export default {
  name: 'App',
  components: {
  
    
    Services,
    Slider,
    Product,
    Faq
  },
  methods: {
    toggleMenu(){

                var icon = document.getElementById('bgIcon');
                const childEle = icon.children;

                childEle[0].classList.toggle('hidden');
                childEle[1].classList.toggle('hidden');

                var mobileNav = document.getElementById('MobileNavigation').classList.toggle('hidden');
                
            },
    scrollToAnchorPoint(refName) {
            const el = this.$refs[refName]
            el.scrollIntoView({ behavior: 'smooth'})
        }

  }
}
</script>


