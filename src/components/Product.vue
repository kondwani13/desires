<template>
    <div class="bg-gray-100">
        <!-- Remove py-8 -->
        <div class="mx-auto container py-8">
            <div class="flex flex-wrap items-center lg:justify-between justify-center">
                <div v-for="index in 4" v-bind:key="index" class="mx-2 w-72 lg:mb-0 mb-8">
                    <div>
                        <img v-bind:src="cardImage" class="w-full h-44" />
                    </div>
                    <div class="bg-white">
                        <div class="flex items-center justify-between px-4 pt-4">
                            <div>
                                <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-bookmark" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke-width="1.5" stroke="#2c3e50" stroke-linecap="round" stroke-linejoin="round">
                                    <path stroke="none" d="M0 0h24v24H0z" fill="none" />
                                    <path d="M9 4h6a2 2 0 0 1 2 2v14l-5-3l-5 3v-14a2 2 0 0 1 2 -2" />
                                </svg>
                            </div>
                            <div class="bg-yellow-200 py-1.5 px-6 rounded-full">
                                <a href="https://wa.me/260977622866"> <button  class="text-xs text-yellow-500">Buy</button></a>
                            </div>
                        </div>
                        <div class="p-4">
                            <div class="flex items-center">
                                <h2 class="text-lg font-semibold">
                                  Asus ZenBook
                                </h2>
                                <p class="text-xs text-gray-600 pl-5">4 days ago</p>
                            </div>
                            <p class="text-xs text-gray-600 mt-2">
                                {{ description }}
                            </p>
                            <div class="flex mt-4">
                                <div>
                                    <p class="text-xs text-gray-600 px-2 bg-gray-200 py-1">12 months warranty</p>
                                </div>
                                <div class="pl-2">
                                    <p class="text-xs text-gray-600 px-2 bg-gray-200 py-1">Refurbished</p>
                                </div>
                            </div>
                            <div class="flex items-center justify-between py-4">
                                <h2 class="text-indigo-700 text-xs font-semibold">Lusaka Town, Chachacha Rd</h2>
                                <h3 class="text-indigo-700 text-xl font-semibold">k3500</h3>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="flex flex-wrap items-center lg:justify-between justify-center pb-10 mt-16">
                <div v-for="index in 4" v-bind:key="index" class="mx-2 w-72 lg:mb-0 mb-8">
                    <div>
                        <img v-bind:src="cardImage2" class="w-full h-44" />
                    </div>
                    <div class="bg-white">
                        <div class="flex items-center justify-between px-4 pt-4">
                            <div>
                                <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-bookmark" width="20" height="20" viewBox="0 0 24 24" stroke-width="1.5" stroke="#2c3e50" fill="none" stroke-linecap="round" stroke-linejoin="round">
                                    <path stroke="none" d="M0 0h24v24H0z" fill="none" />
                                    <path d="M9 4h6a2 2 0 0 1 2 2v14l-5-3l-5 3v-14a2 2 0 0 1 2 -2" />
                                </svg>
                            </div>
                            <div class="bg-yellow-200 py-1.5 px-6 rounded-full">
                                <a href="https://wa.me/260977622866"> <button  class="text-xs text-yellow-500">Buy</button></a>
                            </div>
                        </div>
                        <div class="p-4">
                            <div class="flex items-center">
                                <h2 class="text-lg font-semibold">
                                    {{ item }}
                                </h2>
                                <p class="text-xs text-gray-600 pl-5">4 days ago</p>
                            </div>
                            <p class="text-xs text-gray-600 mt-2">
                                {{ description }}
                            </p>
                            <div class="flex mt-4">
                                <div>
                                    <p class="text-xs text-gray-600 px-2 bg-gray-200 py-1">12 months warranty</p>
                                </div>
                                <div class="pl-2">
                                    <p class="text-xs text-gray-600 px-2 bg-gray-200 py-1">Refurbished</p>
                                </div>
                            </div>
                            <div class="flex items-center justify-between py-4">
                                <h2 class="text-indigo-700 text-xs font-semibold">Lusaka Town, Chachacha Rd</h2>
                                <h3 class="text-indigo-700 text-xl font-semibold">k3500</h3>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            cardImage: "https://i.ibb.co/fqZ4CD0/asus.jpg",
            cardImage2: "https://i.ibb.co/MgFf0Bm/xps.jpg",
            item: "Dell XPS",
            description: "core i7 processor 8th Gen, 8GB DDR4 RAM, 500GB Hard drive, display 15.6' ",
            isClicked: "none",
        };
    },
};
</script>
