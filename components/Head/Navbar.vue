<template>
    <div class="fixed z-10 w-full">
        <div class="flex flex-row justify-between rounded-full bg-black mt-1.5 py-4 px-4">
            <div class="basis-1/2 flex text-white py-3 text-2xl space-x-1">
                <NuxtLink to="/">
                Niflare
                </NuxtLink>

            </div>

            <div class="basis-1/4 text-white py-3">
                <NuxtLink to="#ourservice">
                Service
                </NuxtLink>
            </div>

            <div class="basis-1/4 text-white py-3">
                <NuxtLink to="#learnwithus">
                    Learn
                </NuxtLink>
            </div>

            <!--<div class="basis-1/2 flex justify-end">-->
            <!--    <button class="bg-green-500 hover:bg-gray-50 font-bold py-3 px-5 rounded-full">-->
            <!--        Download Course-->
            <!--    </button>-->
            <!--</div>-->

        </div>


    </div>
</template>
<style>
.Navbar {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    padding: 0px 140px 0px 140px;
}
</style>

