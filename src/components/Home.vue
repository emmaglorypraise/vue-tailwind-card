<template>
    <div class="home flex justify-center flex-col items-center">
        <img src="https://source.unsplash.com/random" class="w-full h-64 object-cover" alt="">
        <div class="flex flex-col items-center bg-white lg:bg-black lg:text-white md:w-1/3 w-full p-10 rounded-lg shadow-xl -m-24">
            <img class="md:h-64 md:w-64 w-40 h-40 mt-5 rounded-full object-cover" src="https://source.unsplash.com/random" alt="image">
            <h5 class="text-2xl text-center font-semibold">Some Image Information</h5>
            <p class="text-center  mt-4">
                <span class="font-extrabold">Lorem ipsum</span> dolor sit amet consectetur adipisicing elit. Et aut, debitis labore laudantium laborum aspernatur quidem quisquam veniam nihil repellendus.</p>
            <p class="text-red-500 mt-5 text-center">Image credit: Unsplash</p>
        </div>
    </div>
</template>

<script>
export default {
    name: "Home",
    components: {}
}
</script>