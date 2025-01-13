<template>
    <div id="niflare" class="Simplify rounded-b-3xl sm:px-5">
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6 sm:gap-0 mx-auto w-[90%]">
            <div class=" mt-40 sm:mt-0">
                <div class="text-4xl font-bold"><span class="text-yellow-400">Innovative </span>solutions tailored for you at Niflare</div>

                <div class="text-lg mt-12 text-gray-300">We transform your ideas into reality by leveraging cutting-edge technologies whether you're a business owner seeking robust digital solutions or an individual eager to learn and grow, we're Here to deliver exceptional services and training</div>

                <div class="py-10">
                    <button class="bg-green-500 hover:bg-gray-50 font-bold py-3 px-12 text-black text-2xl rounded-full">
                        Download TrendHunter 
                    </button>
                </div>
            </div>

            <div class="mt-10 sm:mt-50">
                <img :src="img">
            </div>

        </div>

    </div>
</template>

<script setup>
defineProps(
   ['name', 'title', 'img']
)

</script>

<style>
.Simplify {
    font-family: Arial, sans-serif;
    color: #fff;
    background-color: rgb(0, 0, 0);
    margin: 0;
}
</style>