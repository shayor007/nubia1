<template>
    <div class="relative">
        <TabUppertab class=""/>
        <div class="container mx-auto relative">
        <TabMaintab class="my-2 absolute z-10"/>
        </div>

        <div class="">
            <img :src="require('@/images/interview.jpg')" class="object-cover h-96 w-full justify-center" />
        </div>

        <div class="absolute z-10 top-52 w-full flex justify-center text-white text-5xl">
            Join Nubia Capital
        </div>


        <div class="p-8"></div>
        <div class="container mx-auto max-w-5xl">
            At Nubia, we believe that winning requires having the very best people work on the very best opportunities using the very best practices. Hence, our
             indefatigable pursuit of the best talent globally. We hire on a rolling basis so if you believe that you are a good fit for what we are doing at Nubia, 
             email your resume along with a purpose statement to <span class="font-bold text-primary-100">career@nubiacap.com</span>.
        </div>
    </div>
</template>

<script>
export default {
    name: 'IndexPage'
}
</script>

<style>
    
</style>