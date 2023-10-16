---
title: Blog section 6
category: marketing-ui
subCategory: blog-sections
previewUrl: /blog-sections/6/
info: This section can be used for ......
---

::unify-tab
---
items : ["html", "vue", "nuxt"]
initial_: blg_sec6_
---
    :::tab-panel{id="blg_sec6_1"}
    ```html
    <section py20>
        <div px="5 sm:10 md:12 lg:5" class="max-w-7xl mx-auto space-y-14">
            <div class="flex md-justify-between">
                <div text="center md:left" class="space-y-6 max-w-2xl mx-auto md-mx-0">
                    <div text="center md:left" class="md-max-w-lg space-y-5">
                        <span before="absolute content-empty w4 h0.5 rd-md left-0 top-1/2 bg-sky-7 dark:bg-sky-6" text="sky-7 dark:sky-5" class="pl5 relative">
                            Our latest news
                        </span>
                        <h2 text="3xl md:4xl xl:5xl blue-950 dark:gray-2" class="font-semibold leading-tight">From our latest Blog Post</h2>
                    </div>
                </div>
                <div class="">
                    <a href="#" border="~ gray-1 dark:gray-9" text="blue-6 dark:gray-3" class="px6 py3 flex items-center gap-x-3">
                        See More
                        <span i-carbon-chevron-right text-lg></span>                      
                    </a>
                </div>
            </div>
            <div class="grid grid-cols-1 sm-grid-cols-2 gap-8 lg-gap-12">
                <a href="#" bg="white dark:gray-9" border="~ gray-6 dark:gray-8" class="h-full flex flex-col p6 space-y-4">
                    <img alt="banner image" class="w-full aspect-video object-cover relative" src="https://devolio-template.vercel.app/_next/image?url=%2Fimages%2Farticle1.webp&w=1920&q=75" width="1263" height="1291">
                    
                    <div class="flex flex-col space-y-4">
                        <h1 text="2xl lg:3xl gray-9 dark:white" class="font-semibold">How to create a Hotel booking web application</h1>
                        <p text="gray-7 dark:gray-3" class="line-clamp-2">
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga incidunt nam, nihil earum animi ducimus exercitationem facilis explicabo dicta illum delectus, ipsum cum unde enim deleniti repellat. Ipsum, vitae doloremque.
                        </p>
                        <div class="flex flex-wrap gap-3 w-full">
                            <span class="bg-sky-6 text-white px2">Tailwindcss</span>
                            <span class="bg-yellow-3 text-gray-8 px2">Javascript</span>
                        </div>
                    </div>
                </a>
                <a href="#" bg="white dark:gray-9" border="~ gray-6 dark:gray-8" class="h-full flex flex-col p6 space-y-4">
                    <img alt="banner image" class="w-full aspect-video object-cover relative" src="https://devolio-template.vercel.app/_next/image?url=%2Fimages%2Farticle1.webp&w=1920&q=75" width="1263" height="1291">
                    
                    <div class="flex flex-col space-y-4">
                        <h1 text="2xl lg:3xl gray-9 dark:white" class="font-semibold">How to create a Hotel booking web application</h1>
                        <p text="gray-7 dark:gray-3" class="line-clamp-2">
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga incidunt nam, nihil earum animi ducimus exercitationem facilis explicabo dicta illum delectus, ipsum cum unde enim deleniti repellat. Ipsum, vitae doloremque.
                        </p>
                        <div class="flex flex-wrap gap-3 w-full">
                            <span class="bg-sky-6 text-white px2">Tailwindcss</span>
                            <span class="bg-yellow-3 text-gray-8 px2">Javascript</span>
                        </div>
                    </div>
                </a>
            </div>
        </div>
    </section>
    ```
    :::
    :::tab-panel{id="blg_sec6_2"}
    ```vue
  <template>
      <section py20>
          <div px="5 sm:10 md:12 lg:5" class="max-w-7xl mx-auto space-y-14">
              <div class="flex md-justify-between">
                  <div text="center md:left" class="space-y-6 max-w-2xl mx-auto md-mx-0">
                      <div text="center md:left" class="md-max-w-lg space-y-5">
                          <span before="absolute content-empty w4 h0.5 rd-md left-0 top-1/2 bg-sky-7 dark:bg-sky-6"
                              text="sky-7 dark:sky-5" class="pl5 relative">
                              Our latest news
                          </span>
                          <h2 text="3xl md:4xl xl:5xl blue-950 dark:gray-2" class="font-semibold leading-tight">From our
                              latest Blog Post</h2>
                      </div>
                  </div>
                  <div class="">
                      <a href="#" border="~ gray-1 dark:gray-9" text="blue-6 dark:gray-3"
                          class="px6 py3 flex items-center gap-x-3">
                          See More
                          <span i-carbon-chevron-right text-lg></span>
                      </a>
                  </div>
              </div>
              <div class="grid grid-cols-1 sm-grid-cols-2 gap-8 lg-gap-12">
                  <a href="#" bg="white dark:gray-9" border="~ gray-6 dark:gray-8" class="h-full flex flex-col p6 space-y-4">
                      <img alt="banner image" class="w-full aspect-video object-cover relative"
                          src="https://devolio-template.vercel.app/_next/image?url=%2Fimages%2Farticle1.webp&w=1920&q=75"
                          width="1263" height="1291">

                      <div class="flex flex-col space-y-4">
                          <h1 text="2xl lg:3xl gray-9 dark:white" class="font-semibold">How to create a Hotel booking web
                              application</h1>
                          <p text="gray-7 dark:gray-3" class="line-clamp-2">
                              Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga incidunt nam, nihil earum animi
                              ducimus exercitationem facilis explicabo dicta illum delectus, ipsum cum unde enim deleniti
                              repellat. Ipsum, vitae doloremque.
                          </p>
                          <div class="flex flex-wrap gap-3 w-full">
                              <span class="bg-sky-6 text-white px2">Tailwindcss</span>
                              <span class="bg-yellow-3 text-gray-8 px2">Javascript</span>
                          </div>
                      </div>
                  </a>
                  <a href="#" bg="white dark:gray-9" border="~ gray-6 dark:gray-8" class="h-full flex flex-col p6 space-y-4">
                      <img alt="banner image" class="w-full aspect-video object-cover relative"
                          src="https://devolio-template.vercel.app/_next/image?url=%2Fimages%2Farticle1.webp&w=1920&q=75"
                          width="1263" height="1291">

                      <div class="flex flex-col space-y-4">
                          <h1 text="2xl lg:3xl gray-9 dark:white" class="font-semibold">How to create a Hotel booking web
                              application</h1>
                          <p text="gray-7 dark:gray-3" class="line-clamp-2">
                              Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga incidunt nam, nihil earum animi
                              ducimus exercitationem facilis explicabo dicta illum delectus, ipsum cum unde enim deleniti
                              repellat. Ipsum, vitae doloremque.
                          </p>
                          <div class="flex flex-wrap gap-3 w-full">
                              <span class="bg-sky-6 text-white px2">Tailwindcss</span>
                              <span class="bg-yellow-3 text-gray-8 px2">Javascript</span>
                          </div>
                      </div>
                  </a>
              </div>
          </div>
      </section>
  </template>
    ```
    :::
    :::tab-panel{id="blg_sec6_3"}
    ```vue
  <template>
    <section py20>
        <div px="5 sm:10 md:12 lg:5" class="max-w-7xl mx-auto space-y-14">
            <div class="flex md-justify-between">
                <div text="center md:left" class="space-y-6 max-w-2xl mx-auto md-mx-0">
                    <div text="center md:left" class="md-max-w-lg space-y-5">
                        <span before="absolute content-empty w4 h0.5 rd-md left-0 top-1/2 bg-sky-7 dark:bg-sky-6" text="sky-7 dark:sky-5" class="pl5 relative">
                            Our latest news
                        </span>
                        <h2 text="3xl md:4xl xl:5xl blue-950 dark:gray-2" class="font-semibold leading-tight">From our latest Blog Post</h2>
                    </div>
                </div>
                <div class="">
                    <nuxt-link to="#" border="~ gray-1 dark:gray-9" text="blue-6 dark:gray-3" class="px6 py3 flex items-center gap-x-3">
                        See More
                        <span i-carbon-chevron-right text-lg></span>                      
                    </nuxt-link>
                </div>
            </div>
            <div class="grid grid-cols-1 sm-grid-cols-2 gap-8 lg-gap-12">
                <nuxt-link to="#" bg="white dark:gray-9" border="~ gray-6 dark:gray-8" class="h-full flex flex-col p6 space-y-4">
                    <img alt="banner image" class="w-full aspect-video object-cover relative" src="https://devolio-template.vercel.app/_next/image?url=%2Fimages%2Farticle1.webp&w=1920&q=75" width="1263" height="1291">
                    
                    <div class="flex flex-col space-y-4">
                        <h1 text="2xl lg:3xl gray-9 dark:white" class="font-semibold">How to create a Hotel booking web application</h1>
                        <p text="gray-7 dark:gray-3" class="line-clamp-2">
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga incidunt nam, nihil earum animi ducimus exercitationem facilis explicabo dicta illum delectus, ipsum cum unde enim deleniti repellat. Ipsum, vitae doloremque.
                        </p>
                        <div class="flex flex-wrap gap-3 w-full">
                            <span class="bg-sky-6 text-white px2">Tailwindcss</span>
                            <span class="bg-yellow-3 text-gray-8 px2">Javascript</span>
                        </div>
                    </div>
                </nuxt-link>
                <nuxt-link to="#" bg="white dark:gray-9" border="~ gray-6 dark:gray-8" class="h-full flex flex-col p6 space-y-4">
                    <img alt="banner image" class="w-full aspect-video object-cover relative" src="https://devolio-template.vercel.app/_next/image?url=%2Fimages%2Farticle1.webp&w=1920&q=75" width="1263" height="1291">
                    
                    <div class="flex flex-col space-y-4">
                        <h1 text="2xl lg:3xl gray-9 dark:white" class="font-semibold">How to create a Hotel booking web application</h1>
                        <p text="gray-7 dark:gray-3" class="line-clamp-2">
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga incidunt nam, nihil earum animi ducimus exercitationem facilis explicabo dicta illum delectus, ipsum cum unde enim deleniti repellat. Ipsum, vitae doloremque.
                        </p>
                        <div class="flex flex-wrap gap-3 w-full">
                            <span class="bg-sky-6 text-white px2">Tailwindcss</span>
                            <span class="bg-yellow-3 text-gray-8 px2">Javascript</span>
                        </div>
                    </div>
                </nuxt-link>
            </div>
        </div>
    </section>
  </template>
    ```
    :::
::