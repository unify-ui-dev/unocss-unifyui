---
title: Agency Hero
category: marketing-ui
subCategory: hero-sections
previewUrl: /hero-sections/agency/
info: This section can be used for ......
---

::unify-tab
---
items : ["html", "vue", "nuxt"]
initial_: hero1_
---
    :::tab-panel{id="hero1_1"}
    ```html
<!-- add this styles 
        button[data-toggle-navbar][data-is-open="true"] #line-1 {
            transform: rotate(45deg) translateY(0.375rem);
        }

        button[data-toggle-navbar][data-is-open="true"] #line-2 {
            transform: rotate(-45deg) translateY(-0.375rem);
        }
-->
    <div data-nav-overlay aria-hidden="true" bg="gray-8/40" class="fixed inset-0 z30 hidden lg-hidden"></div>
    <header border-b="~ gray-1 dark:gray-9" bg="white/80 dark:gray-950/80"
        class="backdrop-filter backdrop-blur-xl z40 sticky top-0 w-full flex items-center h20">
        <nav px="5 sm:10 md:12 lg:5" class="relative mxauto max-w-7xl w-full flex gap-x-5 justify-between items-center">
            <div class="flex items-center min-w-max">
                <a href="/" class="relative flex items-center gap-2.5">
                    <span class="flex">
                        <span w3 h6 rd-l-full flex bg-blue-4></span>
                        <span w3 h6 rd-r-full flex bg-indigo-6 mt2></span>
                    </span>
                    <span text="indigo-950 dark:white" inline-flex text-lg font-bold>
                        Estam
                    </span>
                </a>
            </div>

            <div lg="top-0 relative w-max flex" bg="white dark:gray-950 lg:transparent"
                border-b="~ gray-2 dark:gray-8 lg:none" py="8 lg:0" px="5 sm:10 md:12 lg:px-0"
                class="translate-y-10 lg:translate-y-0 op-0 lg:op-100 invisible lg-visible ease-linear lg-transition-none gap-x-6 absolute top-full left-0 w-full duration-300"
                data-navbar>
                <ul flex flex-col lg-flex-row gap-6 text="gray-7 dark:gray-3" lg="w-full justify-center items-center">
                    <li>
                        <a href="#" relative py-2.5 duration-300 ease-linear text-indigo-6 hover-text-indigo-600
                            after="absolute content-empty bg-indigo-600 w-full left-0 bottom-0 h-px rd-md origin-left ease-linear after-duration-300 after-scale-x-0 hover:scale-x-100">Home</a>
                    </li>
                    <li>
                        <a href="#" relative py-2.5 duration-300 ease-linear hover-text-indigo-6
                            after="absolute content-empty w-full left-0 bottom-0 h-px rd-md origin-left ease-linear duration-300 scale-x-0 bg-indigo-6 hover:scale-x-100">Portfolio</a>
                    </li>
                    <li>
                        <a href="#" relative py-2.5 duration-300 ease-linear hover-text-indigo-6
                            after="absolute content-empty w-full left-0 bottom-0 h-px rd-md origin-left ease-linear duration-300 scale-x-0 bg-indigo-6 hover:scale-x-100">Services</a>
                    </li>
                    <li>
                        <a href="#" relative py-2.5 duration-300 ease-linear hover-text-indigo-6
                            after="absolute content-empty w-full left-0 bottom-0 h-px rd-md origin-left ease-linear duration-300 scale-x-0 bg-indigo-600 hover:scale-x-100">Company</a>
                    </li>
                    <li>
                        <a href="#" relative py-2.5 duration-300 ease-linear hover-text-indigo-6
                            after="absolute content-empty w-full left-0 bottom-0 h-px rd-md origin-left ease-linear duration-300 scale-x-0 bg-indigo-600 hover:scale-x-100">Contact</a>
                    </li>
                </ul>
                <div mt="10 lg:0" flex flex-col sm-flex-row sm-items-center gap-4 lg-min-w-max>
                    <a href="#" flex justify-center relative px6 py3
                        before="absolute content-empty inset-0 rd-lg transition bg-gray-1 dark:bg-gray-9  hover:scale-105">
                        <span relative text="indigo-6 dark:white">
                            Book a call
                        </span>
                    </a>
                </div>
            </div>
            <div flex items-center lg-hidden>
                <button data-toggle-navbar data-is-open="false" outline-none border-l="~ indigo-1 dark:gray-7"
                    p-3 relative bg-transparent aria-label="toggle navbar">
                    <div h0.5 w6 rd bg="gray-7 dark:gray-3" transition duration-300 id="line-1" aria-hidden="true">
                    </div>
                    <div mt2 h0.5 w6 rd bg="gray-7 dark:gray-3" transition duration-300 id="line-2" aria-hidden="true">
                    </div>
                </button>
            </div>
        </nav>
    </header>

    <main w-full>
        <section relative pt="10 xl:14">
            <div mx-auto max-w-7xl w-full px="5 sm:10 md:12 lg:5" gap="8 lg:10 xl:12" flex flex-col lg-flex-row>
                <div
                    class="mx-auto text-center lg-text-left flex flex-col max-w-3xl justify-center lg-justify-start lg-py-8 flex-1 lg-w-1/2 lg-max-w-none">
                    <h1 text="indigo-950 dark:white 4xl/snug sm:5xl/tight xl:6xl/tight" class="font-semibold">
                        Build Your Online Platform with best <span bg="indigo-50 dark:gray-8" border="~ dashed indigo-6"
                            class="dark-text-indigo-3 inline-block px-3">Digital
                            Agency</span>
                    </h1>
                    <p text="gray-7 dark:gray-300 lg:lg" mt10 max-w-2xl lg-max-w-none mx-auto>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Dignissimos, fugit! Laborum quo maxime
                        at sapiente
                        quasi
                    </p>
                    <div mt10 flex gap-4 justify-center lg-justify-start flex-wrap>
                        <a href="#" flex justify-center relative px6 py3
                            before="absolute content-empty inset-0 rd-lg transition bg-indigo-7 dark:bg-indigo-6  hover:scale-105">
                            <span relative text-white>
                                Get in touch
                            </span>
                        </a>
                        <a href="#" flex justify-center relative px6 py3
                            before="absolute content-empty inset-0 rd-lg transition bg-gray-1 dark:bg-gray-9 hover:scale-105">
                            <span relative text="indigo-6 dark:white">
                                See Project
                            </span>
                        </a>
                    </div>
                </div>
                <div class="flex flex-1 lg-w-1/2 relative max-w-3xl mx-auto lg-max-w-none">
                    <img src="/images/heroImg.webp" alt="happy team" width="1850" height="auto"
                        class="lg-absolute w-full lg-inset-x-0 object-cover lg-h-full">
                    <div bg="white dark:gray-950"
                        class="absolute left-1/2 -translate-x-1/2 lg--translate-x-0 -bottom-10 w-60 p-4 rd-lg  border dark-border-gray-8">
                        <div flex -space-x-1 children="object-cover rd-full w-9 h-9 ring-4 ring-white dark:ring-gray-950 object-cover rd-full">
                            <img src="/images/creative-agency-production.webp" alt="employee image" width="1920"
                                height="1320" !-ml-0>
                            <img src="/images/creative-agency-production.webp" alt="employee image" width="1920"
                                height="1320">
                            <img src="/images/creative-agency-production.webp" alt="employee image" width="1920"
                                height="1320">
                            <img src="/images/creative-agency-production.webp" alt="employee image" width="1920"
                                height="1320">
                        </div>
                        <div>
                            <p text="indigo-950 dark:white lg" font-semibold>45+ employees</p>
                            <p text="gray-7 dark:gray-3" flex>
                                <span class="text-yellow-5 text-xl">&starf;</span> 5.0 (2.5k reviews)
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <!-- add script
        const btnHumb = document.querySelector("[data-toggle-navbar]")
        const navbar = document.querySelector("[data-navbar]")
        const overlay = document.querySelector("[data-nav-overlay]")
        if (btnHumb && navbar) {
            const toggleBtnAttr = () => {
                const isOpen = btnHumb.getAttribute("data-is-open")
                btnHumb.setAttribute("data-is-open", isOpen === "true" ? "false" : "true")
                if (isOpen === "false") {
                    document.body.classList.remove("overflow-y-auto")
                    overlay.classList.toggle("hidden")
                } else {
                    document.body.classList.add("overflow-y-auto")
                    overlay.classList.add("hidden")
                }
            }
            btnHumb.addEventListener("click", () => {
                navbar.classList.toggle("invisible")
                navbar.classList.toggle("op-0")
                navbar.classList.toggle("translate-y-10")
                toggleBtnAttr()
            })

            overlay.addEventListener("click", () => {
                navbar.classList.add("invisible")
                navbar.classList.add("op-0")
                navbar.classList.add("translate-y-10")
                toggleBtnAttr()
            })
        }
    -->
    ```
    :::
    :::tab-panel{id="hero1_2"}
    ```vue
  <script setup>
  import { ref } from 'vue'

  const navIsOpen = ref(false)
  const navItems = [
      {
          id:1,
          text:"Home",
          href:"/",
          isActive:true
      },
      {
          id:2,
          text:"Portfolio",
          href:"#",
          isActive:false
      },
      {
          id:3,
          text:"Services",
          href:"#",
          isActive:false
      },
      {
          id:4,
          text:"Company",
          href:"#",
          isActive:false
      },
      {
          id:5,
          text:"Contact",
          href:"#",
          isActive:false
      },
  ]

  function toggleNavBar(){
      navIsOpen.value = !navIsOpen.value
      document.body.classList.toggle("overflow-y-auto")
  }
  function closeNavBar(){
      navIsOpen.value = false
      ocument.body.classList.add("overflow-y-auto")
  }
  </script>
  <template>
      <div aria-hidden="true" @click="closeNavBar()" bg="gray-8/40" class="fixed inset-0 z30" :class="navIsOpen ? 'visible flex lg-hidden lg-invisible':'invisible hidden'"></div>
      <header border-b="~ gray-1 dark:gray-9" bg="white/80 dark:gray-950/80"
          class="backdrop-filter backdrop-blur-xl z40 sticky top-0 w-full flex items-center h20">
          <nav px="5 sm:10 md:12 lg:5" class="relative mxauto max-w-7xl w-full flex gap-x-5 justify-between items-center">
              <div class="flex items-center min-w-max">
                  <a href="/" class="relative flex items-center gap-2.5">
                      <span class="flex">
                          <span w3 h6 rd-l-full flex bg-blue-4></span>
                          <span w3 h6 rd-r-full flex bg-indigo-6 mt2></span>
                      </span>
                      <span text="indigo-950 dark:white" inline-flex text-lg font-bold>
                          Estam
                      </span>
                  </a>
              </div>
              <div lg="top-0 relative w-max flex" bg="white dark:gray-950 lg:transparent"
                  border-b="~ gray-2 dark:gray-8 lg:none" py="8 lg:0" px="5 sm:10 md:12 lg:px-0"
                  class="ease-linear lg-transition-none gap-x-6 absolute top-full left-0 w-full duration-300"
                  :class="navIsOpen ? 'visible op100 translate-y-0':'translate-y-10 lg-translate-y-0 invisible lg-visible op0 lg-op100'">
                  <ul text="gray-7 dark:gray-3" class="flex flex-col lg-flex-row gap6 lg-w-full lg-justify-center lg-items-center">
                      <li v-for="navItem in navItems" :key="navItem.id">
                          <router-link :to="navItem.href"  class="py2.5 duration-300 ease-linear hover-text-indigo-6  relative after-absolute after-content-empty after-bg-indigo-6 after-w-full after-left-0 after-bottom-0 after-h-px after-rd-md after-duration-300 after-ease-linean" :class="navItem.isActive ?'text-indigo-6 after-scale-x-100':'after-scale-x-0 hover-after-scale-x-100'"> 
                              {{ navItem.text }}
                          </router-link>
                      </li>
                  </ul>
                  <div mt="10 lg:0" flex flex-col sm-flex-row sm-items-center gap-4 lg-min-w-max>
                      <a href="#" class="flex justify-center relative px6 py3"
                          un-before="absolute content-empty inset-0 rd-lg transition bg-gray-1 dark-bg-gray-9 after-origin-left after-ease-linear after-after-duration-300">
                          <span relative text="indigo-6 dark:white">
                              Book a call
                          </span>
                      </a>
                  </div>
              </div>
              <div flex items-center lg-hidden>
                  <button @click="toggleNavBar()" outline-none border-l="~ indigo-1 dark:gray-7"
                      p-3 relative bg-transparent aria-label="toggle navbar">
                      <div h0.5 w6 rd bg="gray-7 dark:gray-3" transition duration-300 aria-hidden="true" :class="navIsOpen ? 'rotate-45 translate-y-1.5':''">
                      </div>
                      <div mt2 h0.5 w6 rd bg="gray-7 dark:gray-3" transition duration-300 aria-hidden="true" :class="navIsOpen ? '-rotate-45 -translate-y-1.5':''">
                      </div>
                  </button>
              </div>
          </nav>
      </header>

      
      <main w-full>
          <section relative pt="10 xl:14">
              <div mx-auto max-w-7xl w-full px="5 sm:10 md:12 lg:5" gap="8 lg:10 xl:12" flex flex-col lg-flex-row>
                  <div
                      class="mx-auto text-center lg-text-left flex flex-col max-w-3xl justify-center lg-justify-start lg-py-8 flex-1 lg-w-1/2 lg-max-w-none">
                      <h1 text="indigo-950 dark:white 4xl/snug sm:5xl/tight xl:6xl/tight" class="font-semibold">
                          Build Your Online Platform with best <span bg="indigo-50 dark:gray-8" border="~ dashed indigo-6"
                              class="dark-text-indigo-3 inline-block px-3">Digital
                              Agency</span>
                      </h1>
                      <p text="gray-7 dark:gray-300 lg:lg" mt10 max-w-2xl lg-max-w-none mx-auto>
                          Lorem ipsum dolor sit amet consectetur adipisicing elit. Dignissimos, fugit! Laborum quo maxime
                          at sapiente
                          quasi
                      </p>
                      <div mt10 flex gap-4 justify-center lg-justify-start flex-wrap>
                          <router-link to="#" class="flex justify-center relative px6 py3"
                              un-before="absolute content-empty inset-0 rd-lg transition bg-indigo-7 dark:bg-indigo-6  hover:scale-105">
                              <span relative text-white>
                                  Get in touch
                              </span>
                          </router-link>
                          <a href="#" flex justify-center relative px6 py3
                              un-before="absolute content-empty inset-0 rd-lg transition bg-gray-1 dark:bg-gray-9 hover:bg-opacity-90 hover:scale-105">
                              <span relative text="indigo-6 dark:white">
                                  See Project
                              </span>
                          </a>
                      </div>
                  </div>
                  <div class="flex flex-1 lg-w-1/2 relative max-w-3xl mx-auto lg-max-w-none">
                      <img src="/images/heroImg.webp" alt="happy team" width="1850" height="auto"
                          class="lg-absolute w-full lg-inset-x-0 object-cover lg-h-full">
                      <div bg="white dark:gray-950"
                          class="absolute left-1/2 -translate-x-1/2 lg--translate-x-0 -bottom-10 w-60 p-4 rd-lg  border dark-border-gray-8">
                          <div class="flex -space-x-1" un-children="object-cover rd-full w-9 h-9 ring-4 ring-white dark:ring-gray-950 object-cover rd-full">
                              <img src="/images/creative-agency-production.webp" alt="employee image" width="1920"
                                  height="1320" class="!-ml-0">
                              <img src="/images/creative-agency-production.webp" alt="employee image" width="1920"
                                  height="1320">
                              <img src="/images/creative-agency-production.webp" alt="employee image" width="1920"
                                  height="1320">
                              <img src="/images/creative-agency-production.webp" alt="employee image" width="1920"
                                  height="1320" >
                          </div>
                          <div>
                              <p text="indigo-950 dark:white lg" font-semibold>45+ employees</p>
                              <p text="gray-7 dark:gray-3" flex>
                                  <span class="text-yellow-5 text-xl">&starf;</span> 5.0 (2.5k reviews)
                              </p>
                          </div>
                      </div>
                  </div>
              </div>
          </section>
      </main>
  </template>
    ```
    :::
    :::tab-panel{id="hero1_3"}
    ```vue
  <script setup>
  const navIsOpen = useState('navIsOpen', ()=>false)
  const navItems = [
      {
          id:1,
          text:"Home",
          href:"/",
          isActive:true
      },
      {
          id:2,
          text:"Portfolio",
          href:"#",
          isActive:false
      },
      {
          id:3,
          text:"Services",
          href:"#",
          isActive:false
      },
      {
          id:4,
          text:"Company",
          href:"#",
          isActive:false
      },
      {
          id:5,
          text:"Contact",
          href:"#",
          isActive:false
      },
  ]

  function toggleNavBar(){
      navIsOpen.value = !navIsOpen.value
      document.body.classList.toggle("overflow-y-auto")
  }
  function closeNavBar(){
      navIsOpen.value = false
      ocument.body.classList.add("overflow-y-auto")
  }
  </script>
  <template>
      <div aria-hidden="true" @click="closeNavBar()" bg="gray-8/40" class="fixed inset-0 z30" :class="navIsOpen ? 'visible flex lg-hidden lg-invisible':'invisible hidden'"></div>
      <header border-b="~ gray-1 dark:gray-9" bg="white/80 dark:gray-950/80"
          class="backdrop-filter backdrop-blur-xl z40 sticky top-0 w-full flex items-center h20">
          <nav px="5 sm:10 md:12 lg:5" class="relative mxauto max-w-7xl w-full flex gap-x-5 justify-between items-center">
              <div class="flex items-center min-w-max">
                  <nuxt-link to="/" class="relative flex items-center gap-2.5">
                      <span class="flex">
                          <span w3 h6 rd-l-full flex bg-blue-4></span>
                          <span w3 h6 rd-r-full flex bg-indigo-6 mt2></span>
                      </span>
                      <span text="indigo-950 dark:white" inline-flex text-lg font-bold>
                          Estam
                      </span>
                  </nuxt-link>
              </div>
              <div lg="top-0 relative w-max flex" bg="white dark:gray-950 lg:transparent"
                  border-b="~ gray-2 dark:gray-8 lg:none" py="8 lg:0" px="5 sm:10 md:12 lg:px-0"
                  class="ease-linear lg-transition-none gap-x-6 absolute top-full left-0 w-full duration-300"
                  :class="navIsOpen ? 'visible op100 translate-y-0':'translate-y-10 lg-translate-y-0 invisible lg-visible op0 lg-op100'">
                  <ul text="gray-7 dark:gray-3" class="flex flex-col lg-flex-row gap6 lg-w-full lg-justify-center lg-items-center">
                      <li v-for="navItem in navItems" :key="navItem.id">
                          <nuxt-link :to="navItem.href"  class="py2.5 duration-300 ease-linear hover-text-indigo-6  relative after-absolute after-content-empty after-bg-indigo-6 after-w-full after-left-0 after-bottom-0 after-h-px after-rd-md after-duration-300 after-ease-linean" :class="navItem.isActive ?'text-indigo-6 after-scale-x-100':'after-scale-x-0 hover-after-scale-x-100'"> 
                              {{ navItem.text }}
                          </nuxt-link>
                      </li>
                  </ul>
                  <div mt="10 lg:0" flex flex-col sm-flex-row sm-items-center gap-4 lg-min-w-max>
                      <nuxt-link to="#" class="flex justify-center relative px6 py3"
                          un-before="absolute content-empty inset-0 rd-lg transition bg-gray-1 dark-bg-gray-9 after-origin-left after-ease-linear after-after-duration-300">
                          <span relative text="indigo-6 dark:white">
                              Book a call
                          </span>
                      </nuxt-link>
                  </div>
              </div>
              <div flex items-center lg-hidden>
                  <button @click="toggleNavBar()" outline-none border-l="~ indigo-1 dark:gray-7"
                      p-3 relative bg-transparent aria-label="toggle navbar">
                      <div h0.5 w6 rd bg="gray-7 dark:gray-3" transition duration-300 aria-hidden="true" :class="navIsOpen ? 'rotate-45 translate-y-1.5':''">
                      </div>
                      <div mt2 h0.5 w6 rd bg="gray-7 dark:gray-3" transition duration-300 aria-hidden="true" :class="navIsOpen ? '-rotate-45 -translate-y-1.5':''">
                      </div>
                  </button>
              </div>
          </nav>
      </header>

      
      <main w-full>
          <section relative pt="10 xl:14">
              <div mx-auto max-w-7xl w-full px="5 sm:10 md:12 lg:5" gap="8 lg:10 xl:12" flex flex-col lg-flex-row>
                  <div
                      class="mx-auto text-center lg-text-left flex flex-col max-w-3xl justify-center lg-justify-start lg-py-8 flex-1 lg-w-1/2 lg-max-w-none">
                      <h1 text="indigo-950 dark:white 4xl/snug sm:5xl/tight xl:6xl/tight" class="font-semibold">
                          Build Your Online Platform with best <span bg="indigo-50 dark:gray-8" border="~ dashed indigo-6"
                              class="dark-text-indigo-3 inline-block px-3">Digital
                              Agency</span>
                      </h1>
                      <p text="gray-7 dark:gray-300 lg:lg" mt10 max-w-2xl lg-max-w-none mx-auto>
                          Lorem ipsum dolor sit amet consectetur adipisicing elit. Dignissimos, fugit! Laborum quo maxime
                          at sapiente
                          quasi
                      </p>
                      <div mt10 flex gap-4 justify-center lg-justify-start flex-wrap>
                          <nuxt-link to="#" class="flex justify-center relative px6 py3"
                              un-before="absolute content-empty inset-0 rd-lg transition bg-indigo-7 dark:bg-indigo-6  hover:scale-105">
                              <span relative text-white>
                                  Get in touch
                              </span>
                          </nuxt-link>
                          <nuxt-link to="#" flex justify-center relative px6 py3
                              un-before="absolute content-empty inset-0 rd-lg transition bg-gray-1 dark:bg-gray-9 hover:bg-opacity-90 hover:scale-105">
                              <span relative text="indigo-6 dark:white">
                                  See Project
                              </span>
                          </nuxt-link>
                      </div>
                  </div>
                  <div class="flex flex-1 lg-w-1/2 relative max-w-3xl mx-auto lg-max-w-none">
                      <img src="/images/heroImg.webp" alt="happy team" width="1850" height="auto"
                          class="lg-absolute w-full lg-inset-x-0 object-cover lg-h-full">
                      <div bg="white dark:gray-950"
                          class="absolute left-1/2 -translate-x-1/2 lg--translate-x-0 -bottom-10 w-60 p-4 rd-lg  border dark-border-gray-8">
                          <div class="flex -space-x-1" un-children="object-cover rd-full w-9 h-9 ring-4 ring-white dark:ring-gray-950 object-cover rd-full">
                              <img src="/images/creative-agency-production.webp" alt="employee image" width="1920"
                                  height="1320" class="!-ml-0">
                              <img src="/images/creative-agency-production.webp" alt="employee image" width="1920"
                                  height="1320">
                              <img src="/images/creative-agency-production.webp" alt="employee image" width="1920"
                                  height="1320">
                              <img src="/images/creative-agency-production.webp" alt="employee image" width="1920"
                                  height="1320" >
                          </div>
                          <div>
                              <p text="indigo-950 dark:white lg" font-semibold>45+ employees</p>
                              <p text="gray-7 dark:gray-3" flex>
                                  <span class="text-yellow-5 text-xl">&starf;</span> 5.0 (2.5k reviews)
                              </p>
                          </div>
                      </div>
                  </div>
              </div>
          </section>
      </main>
  </template>
    ```
    :::
::