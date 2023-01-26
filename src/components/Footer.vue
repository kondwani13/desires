<template>
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
export default {
    name: "index",
    data() {
        return {
            auto: true,
            light: false,
            dark: false,
        };
    },
    mounted() {},
    methods: {
        toggle(event) {
            if (event.target.value === "auto") {
                this.auto = true;
                this.light = false;
                this.dark = false;
            }
            if (event.target.value === "light") {
                this.auto = false;
                this.light = true;
                this.dark = false;
            }
            if (event.target.value === "dark") {
                this.auto = false;
                this.light = false;
                this.dark = true;
            }
        },
    },
};
</script>

<style scoped>
@import url("https://cdn.tuk.dev/dist/css/tailwind-v2.2.11.min.css");
</style>
