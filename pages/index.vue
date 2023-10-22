<template>
    <div class='flex flex-col w-full items-center shadow bg-white'>
        <!-- hero area -->
        <div class="hero-area w-full">
            <img src="/images/banner-bg.jpg">
        </div>

         <!-- Best Selling Product -->
         <section class="w-full py-16">
            <div class="max-w-5xl mx-auto">
                <div class="heading flex flex-col gap-3 justify-center items-center mb-12">
                    <h2 class="text-gray-800 font-semibold text-[2.5em] text-center">Best Selling Products</h2>
                    <span class="h-1 w-44 bg-gray-800"></span>
                </div>
                <div class="grid grid-cols-4 gap-12 w-full">
                    <div class="w-full">
                        <img src="/images/_1.png" alt="" class="w-full object-contain h-60" />
                        <h3 class="text-zinc-800 font-bold">Breza – Cain Aqua</h3>
                        <p class="text-zinc-800 text-sm">Softner</p>
                        <p class="text-zinc-800 text-sm">₹25,500.00</p>
                    </div>
                    <div class="w-full">
                        <img src="/images/_2.png" alt="" class="w-full object-contain h-60" />
                        <h3 class="text-zinc-800 font-bold">Breza – Cain Aqua</h3>
                        <p class="text-zinc-800 text-sm">Softner</p>
                        <p class="text-zinc-800 text-sm">₹25,500.00</p>
                    </div>
                    <div class="w-full">
                        <img src="/images/_3.png" alt="" class="w-full object-contain h-60" />
                        <h3 class="text-zinc-800 font-bold">Breza – Cain Aqua</h3>
                        <p class="text-zinc-800 text-sm">Softner</p>
                        <p class="text-zinc-800 text-sm">₹25,500.00</p>
                    </div>
                    <div class="w-full">
                        <img src="/images/_4.png" alt="" class="w-full object-contain h-60" />
                        <h3 class="text-zinc-800 font-bold">Breza – Cain Aqua</h3>
                        <p class="text-zinc-800 text-sm">Softner</p>
                        <p class="text-zinc-800 text-sm">₹25,500.00</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- About Us -->
        <section class="w-full h-screen flex items-center bg-gray-50">
            <div class="flex max-w-5xl mx-auto w-full gap-12">
                <div class="w-full">
                    <img src="/images/1.png" alt="" class="w-full object-cover">
                </div>
                <div class="w-full space-y-6">
                    <h5 class="font-bold text-cyan-500">About Us</h5>
                    <h2 class="text-4xl font-bold text-gray-900">Safe Water Is Essential For Our Healthy Life</h2>
                    <p class="text-gray-700">We know that as water is the most essential element for all living beings, not only humans, and you have to take it regularly, you are efer searching for the best.</p>
                    <div class="grid grid-cols-2 gap-6">
                        <div class="flex items-start gap-4" v-for="n in 4">
                            <Icon class="text-cyan-400 w-7 h-7" name="mdi:checkbox-marked-circle-outline" />
                            <div class="text-zinc-800">Lorem ipsum dolor sit amet consectetur</div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- What Water do for you -->
        <section class="w-full bg-gray-200">
            <div class="">
                <img src="https://www.kent.co.in/blog/wp-content/uploads/2018/05/pH-level-in-drinking-water.jpg" alt="" class="w-full">
            </div>
        </section>

        <!-- Categories -->
        <section class="w=full py-16">
            <div class="max-w-5xl mx-auto">
                <div class="heading flex flex-col gap-3 justify-center items-center mb-12">
                    <h2 class="text-gray-800 font-semibold text-[2.5em] text-center">Categories</h2>
                    <span class="h-1 w-44 bg-gray-800"></span>
                </div>
                <div class="grid grid-cols-4">
                    <img src="/images/pre.png" alt="" v-for="n in 4">
                </div>
            </div>
        </section>
    </div>
</template>

<script setup>

</script>

<style>

</style>