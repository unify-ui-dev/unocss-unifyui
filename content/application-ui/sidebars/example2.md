---
title: Sidebar 2
category: application-ui
subCategory: sidebars
previewUrl: /sidebars/2/
info: Require JS
---

::unify-tab
---
items : ["html", "vue", "nuxt"]
initial_: sideb2_
---
    :::tab-panel{id="sideb2_1"}
    ```html
    <!-- copy this styles
        button[data-toggle-sidebar][data-is-open="true"] #line-1 {
            transform: translateY(0.375rem) rotate(40deg);
        }

        button[data-toggle-sidebar][data-is-open="true"] #line-2 {
            transform: scaleX(0);
            opacity: 0;
            /* scale-x-0 op-0 */
        }

        button[data-toggle-sidebar][data-is-open="true"] #line-3 {
            transform: translateY(-0.375rem) rotate(-40deg);
        }
    -->

    <aside data-sidebar bg="white dark:gray-950" shadow="lg gray-2/40 dark:gray-8/60"
        class="fixed h-[100dvh] py3 overflow-hidden lg-static w11/12 max-w-[18rem] md-w72 transition-all -translate-x-full lg-translate-x-0 flex flex-col justify-between px4 lg-transition-none ease-linear">
        <div class="min-h-max py4">
            <a href="#" text="gray-8 dark:gray-2"
                class="flex items-center gap-x-3 font-semibold">
                <span>
                    <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-10 h-10">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M13.5 21v-7.5a.75.75 0 01.75-.75h3a.75.75 0 01.75.75V21m-4.5 0H2.36m11.14 0H18m0 0h3.64m-1.39 0V9.349m-16.5 11.65V9.35m0 0a3.001 3.001 0 003.75-.615A2.993 2.993 0 009.75 9.75c.896 0 1.7-.393 2.25-1.016a2.993 2.993 0 002.25 1.016c.896 0 1.7-.393 2.25-1.016a3.001 3.001 0 003.75.614m-16.5 0a3.004 3.004 0 01-.621-4.72L4.318 3.44A1.5 1.5 0 015.378 3h13.243a1.5 1.5 0 011.06.44l1.19 1.189a3 3 0 01-.621 4.72m-13.5 8.65h3.75a.75.75 0 00.75-.75V13.5a.75.75 0 00-.75-.75H6.75a.75.75 0 00-.75.75v3.75c0 .415.336.75.75.75z" />
                    </svg>                      
                </span>
                UniDash
            </a>
        </div>
        <nav class="h-full pt10">
            <ul text="gray-7 dark:gray-3" class="space-y-3">
                <li>
                    <a href="" data-nav-item text="gray-1 dark:gray-9" bg="gray-9 dark:gray-1"
                        class="flex items-center gap-x-4 px5 py3 rd-2xl">
                        <span class="min-w-max inline-flex">
                            <span i-carbon-home text-2xl></span>                             
                        </span>
                        <span data-item-text class="inline-flex ease-linear transition-colors duration-300">
                            Home
                        </span>
                    </a>
                </li>
                <li>
                    <a href="" data-nav-item
                        text="hover:gray-7 dark:hover:white" class="flex items-center gap-x-4 px5 py3">
                        <span class="min-w-max inline-flex">
                            <span i-carbon-purchase text-2xl></span>                            
                        </span>
                        <span data-item-text class="inline-flex ease-linear transition-colors duration-300">
                            Contacts
                        </span>
                    </a>
                </li>
                <li>
                    <a href="" data-nav-item
                        text="hover:gray-7 dark:hover:white" class="flex items-center gap-x-4 px5 py3">
                        <span class="min-w-max inline-flex">
                            <span i-carbon-data-share text-2xl></span>                                                                                                                       
                        </span>
                        <span data-item-text class="inline-flex ease-linear transition-colors duration-300">
                            Transactions
                        </span>
                    </a>
                </li>
                <li>
                    <a href="" data-nav-item
                        text="hover:gray-7 dark:hover:white" class="flex items-center gap-x-4 px5 py3">
                        <span class="min-w-max inline-flex">
                            <span i-carbon-analytics text-2xl></span>                                                                                        
                        </span>
                        <span data-item-text class="inline-flex ease-linear transition-colors duration-300">
                            Analytics
                        </span>
                    </a>
                </li>
            </ul>
        </nav>
        <div border="~ gray-2 dark:gray-8" class="mt6 p4 rd-2xl bg-gradient-to-tr from-gray-50 to-slate-2 dark-from-slate-8 dark-to-gray-950 ">
            <div class="flex flex-col items-center gap-y-4">
                <h2 text="lg gray-8 dark:gray-2" class="font-semibold">
                    Welcome to UniDash App
                </h2>
                <a href="#" bg="gray-2 dark:gray-8" border="~ gray-3 dark:gray-7" text="gray-9 dark:gray-1" class="px5 py2.5 rd-xl w-full justify-center text-center">
                    Go to pro
                </a>
            </div>
        </div>
    </aside>
    <main>
        <div class="flex lg-hidden fixed right-2 top-2 p4">
            <button data-toggle-sidebar bg="gray-9 dark:gray-1"
                class="p3 rd-full outline-none w12 aspect-square flex flex-col relative justify-center items-center">
                <span class="sr-only">
                    toggle sidebar
                </span>
                <span id="line-1" bg="gray-1 dark:gray-9"
                    class="w6 h0.5 rd-full transition-transform duration-300 ease-linear"></span>
                <span id="line-2" bg="gray-1 dark:gray-9"
                    class="w6 origin-center  mt1 h0.5 rd-full transition-all duration-300 ease-linear"></span>
                <span id="line-3" bg="gray-1 dark:gray-9"
                    class="w6 mt1 h0.5 rd-full transition-all duration-300 ease-linear"></span>
            </button>
        </div>
    </main>

    <!-- copy this script 
    <script>
        const sidebar = document.querySelector("[data-sidebar]")
        if (sidebar) {
            const toggleSidebar = document.querySelector("[data-toggle-sidebar]")
            if (toggleSidebar) {
                const toggleBtnAttr = () => {
                    const isOpen = toggleSidebar.getAttribute("data-is-open")
                    toggleSidebar.setAttribute("data-is-open", isOpen === "true" ? "false" : "true")
                    if (isOpen === "false") {
                        document.body.classList.toggle("overflow-y-auto")
                    } else {
                        document.body.classList.add("overflow-y-auto")
                    }
                }
                toggleSidebar.addEventListener("click", () => {
                    sidebar.classList.toggle("-translate-x-full")
                    toggleBtnAttr()
                })
            }
        }
    </script> 
    -->
    
    ```
    :::
    :::tab-panel{id="sideb2_2"}
    ```vue
    <script setup>
    import { ref } from 'vue';

    const sidebarIsToggled = ref(false)
    const toggleSidebar = () => {
    sidebarIsToggled.value = !sidebarIsToggled.value
    if (!sidebarIsToggled) {
        document.body.classList.toggle("overflow-y-auto")
    } else {
        document.body.classList.add("overflow-y-auto")
    }
    }

    const navItems = [
    {
        id: 1,
        icon: 'i-carbon-home',
        text: 'Home',
        link: '/',
        isActive: true
    },
    {
        id: 2,
        icon: 'i-carbon-purchase',
        text: 'Contacts',
        link: '/',
        isActive: false
    },
    {
        id: 3,
        icon: 'i-carbon-data-share',
        text: 'Transactions',
        link: '/',
        isActive: false
    },
    {
        id: 4,
        icon: 'i-carbon-analytics',
        text: 'Analytics',
        link: '/',
        isActive: false
    },
    ]
    </script>
    <template>
    <aside un-bg="white dark:gray-950" shadow="lg gray-2/40 dark:gray-8/60"
        class="fixed h-[100dvh] py3 overflow-hidden lg-static w11/12 max-w-[18rem] md-w72 transition-all flex flex-col justify-between px4 lg-transition-none ease-linear"
        :class="{
        'translate-x-0': sidebarIsToggled,
        '-translate-x-full lg-translate-x-0': !sidebarIsToggled
        }">
        <div class="min-h-max py4">
        <a href="#" un-text="gray-8 dark:gray-2" class="flex items-center gap-x-3 font-semibold">
            <span>
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"
                class="w-10 h-10">
                <path stroke-linecap="round" stroke-linejoin="round"
                d="M13.5 21v-7.5a.75.75 0 01.75-.75h3a.75.75 0 01.75.75V21m-4.5 0H2.36m11.14 0H18m0 0h3.64m-1.39 0V9.349m-16.5 11.65V9.35m0 0a3.001 3.001 0 003.75-.615A2.993 2.993 0 009.75 9.75c.896 0 1.7-.393 2.25-1.016a2.993 2.993 0 002.25 1.016c.896 0 1.7-.393 2.25-1.016a3.001 3.001 0 003.75.614m-16.5 0a3.004 3.004 0 01-.621-4.72L4.318 3.44A1.5 1.5 0 015.378 3h13.243a1.5 1.5 0 011.06.44l1.19 1.189a3 3 0 01-.621 4.72m-13.5 8.65h3.75a.75.75 0 00.75-.75V13.5a.75.75 0 00-.75-.75H6.75a.75.75 0 00-.75.75v3.75c0 .415.336.75.75.75z" />
            </svg>
            </span>
            UniDash
        </a>
        </div>
        <nav class="h-full pt10">
        <ul un-text="gray-7 dark:gray-3" class="space-y-3">
            <li v-for="item in navItems" :key="item.id">
            <router-link :to="item.link" class="flex items-center gap-x-4 px5 py3 rd-2xl "
                :class="item.isActive ? 'text-gray-1 dark-text-gray-9 bg-gray-9 dark-bg-gray-1' : 'hover-text-gray-7 dark-hover-text-white'">
                <span class="min-w-max inline-flex">
                <span class="text-2xl" :class="item.icon"></span>
                </span>
                <span class="inline-flex ease-linear transition-colors duration-300">
                {{ item.text }}
                </span>
            </router-link>
            </li>

        </ul>
        </nav>
        <div un-border="~ gray-2 dark:gray-8"
        class="mt6 p4 rd-2xl bg-gradient-to-tr from-gray-50 to-slate-2 dark-from-slate-8 dark-to-gray-950 ">
        <div class="flex flex-col items-center gap-y-4">
            <h2 un-text="lg gray-8 dark:gray-2" class="font-semibold">
            Welcome to UniDash App
            </h2>
            <a href="#" un-bg="gray-2 dark:gray-8" border="~ gray-3 dark:gray-7" un-text="gray-9 dark:gray-1"
            class="px5 py2.5 rd-xl w-full justify-center text-center">
            Go to pro
            </a>
        </div>
        </div>
    </aside>
    <main>
        <div class="flex lg-hidden fixed right-2 top2 p4">
        <button @click="toggleSidebar" un-bg="blue-6 dark:blue-5"
            class="p3 rd-full outline-none w12 aspect-square flex flex-col relative justify-center items-center"
            aria-label="toggle sidebar">
            <span class="w6 h0.5 rd-full bg-gray-3 transition-transform duration-300 ease-linear"
            :class="sidebarIsToggled ? 'translate-y-1.5 rotate-40' : ''"></span>
            <span class="w6 origin-center  mt-1 h-0.5 rd-full bg-gray-3 transition-all duration-300 ease-linear"
            :class="sidebarIsToggled ? 'scale-x-0 op-0' : ''"></span>
            <span class="w6 mt1 h0.5 rd-full bg-gray-3 transition-all duration-300 ease-linear"
            :class="sidebarIsToggled ? '-translate-y-1.5 -rotate-40' : ''"></span>
        </button>
        </div>
    </main>
    </template>
    ```
    :::
    :::tab-panel{id="sideb2_3"}
    ```vue
    <script setup>
    const sidebarIsToggled = useState('sidebarIsToggled',()=>false)
    const toggleSidebar = () => {
    sidebarIsToggled.value = !sidebarIsToggled.value
    if (!sidebarIsToggled) {
        document.body.classList.toggle("overflow-y-auto")
    } else {
        document.body.classList.add("overflow-y-auto")
    }
    }
    const navItems = [
    {
        id: 1,
        icon: 'i-carbon-home',
        text: 'Home',
        link: '/',
        isActive: true
    },
    {
        id: 2,
        icon: 'i-carbon-purchase',
        text: 'Contacts',
        link: '/',
        isActive: false
    },
    {
        id: 3,
        icon: 'i-carbon-data-share',
        text: 'Transactions',
        link: '/',
        isActive: false
    },
    {
        id: 4,
        icon: 'i-carbon-analytics',
        text: 'Analytics',
        link: '/',
        isActive: false
    },
    ]
    </script>
    <template>
    <aside un-bg="white dark:gray-950" shadow="lg gray-2/40 dark:gray-8/60"
        class="fixed h-[100dvh] py3 overflow-hidden lg-static w11/12 max-w-[18rem] md-w72 transition-all flex flex-col justify-between px4 lg-transition-none ease-linear"
        :class="{
        'translate-x-0': sidebarIsToggled,
        '-translate-x-full lg-translate-x-0': !sidebarIsToggled
        }">
        <div class="min-h-max py4">
        <nuxt-link to="#" un-text="gray-8 dark:gray-2" class="flex items-center gap-x-3 font-semibold">
            <span>
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"
                class="w-10 h-10">
                <path stroke-linecap="round" stroke-linejoin="round"
                d="M13.5 21v-7.5a.75.75 0 01.75-.75h3a.75.75 0 01.75.75V21m-4.5 0H2.36m11.14 0H18m0 0h3.64m-1.39 0V9.349m-16.5 11.65V9.35m0 0a3.001 3.001 0 003.75-.615A2.993 2.993 0 009.75 9.75c.896 0 1.7-.393 2.25-1.016a2.993 2.993 0 002.25 1.016c.896 0 1.7-.393 2.25-1.016a3.001 3.001 0 003.75.614m-16.5 0a3.004 3.004 0 01-.621-4.72L4.318 3.44A1.5 1.5 0 015.378 3h13.243a1.5 1.5 0 011.06.44l1.19 1.189a3 3 0 01-.621 4.72m-13.5 8.65h3.75a.75.75 0 00.75-.75V13.5a.75.75 0 00-.75-.75H6.75a.75.75 0 00-.75.75v3.75c0 .415.336.75.75.75z" />
            </svg>
            </span>
            UniDash
        </nuxt-link>
        </div>
        <nav class="h-full pt10">
        <ul un-text="gray-7 dark:gray-3" class="space-y-3">
            <li v-for="item in navItems" :key="item.id">
            <nuxt-link :to="item.link" class="flex items-center gap-x-4 px5 py3 rd-2xl "
                :class="item.isActive ? 'text-gray-1 dark-text-gray-9 bg-gray-9 dark-bg-gray-1' : 'hover-text-gray-7 dark-hover-text-white'">
                <span class="min-w-max inline-flex">
                <span class="text-2xl" :class="item.icon"></span>
                </span>
                <span class="inline-flex ease-linear transition-colors duration-300">
                {{ item.text }}
                </span>
            </nuxt-link>
            </li>

        </ul>
        </nav>
        <div un-border="~ gray-2 dark:gray-8"
        class="mt6 p4 rd-2xl bg-gradient-to-tr from-gray-50 to-slate-2 dark-from-slate-8 dark-to-gray-950 ">
        <div class="flex flex-col items-center gap-y-4">
            <h2 un-text="lg gray-8 dark:gray-2" class="font-semibold">
            Welcome to UniDash App
            </h2>
            <nuxt-link to="#" un-bg="gray-2 dark:gray-8" border="~ gray-3 dark:gray-7" un-text="gray-9 dark:gray-1"
            class="px5 py2.5 rd-xl w-full justify-center text-center">
            Go to pro
            </nuxt-link>
        </div>
        </div>
    </aside>
    <main>
        <div class="flex lg-hidden fixed right-2 top2 p4">
        <button @click="toggleSidebar" un-bg="blue-6 dark:blue-5"
            class="p3 rd-full outline-none w12 aspect-square flex flex-col relative justify-center items-center"
            aria-label="toggle sidebar">
            <span class="w6 h0.5 rd-full bg-gray-3 transition-transform duration-300 ease-linear"
            :class="sidebarIsToggled ? 'translate-y-1.5 rotate-40' : ''"></span>
            <span class="w6 origin-center  mt-1 h-0.5 rd-full bg-gray-3 transition-all duration-300 ease-linear"
            :class="sidebarIsToggled ? 'scale-x-0 op-0' : ''"></span>
            <span class="w6 mt1 h0.5 rd-full bg-gray-3 transition-all duration-300 ease-linear"
            :class="sidebarIsToggled ? '-translate-y-1.5 -rotate-40' : ''"></span>
        </button>
        </div>
    </main>
    </template>
    ```
    :::
::