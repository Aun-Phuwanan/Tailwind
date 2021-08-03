<template>
  
    <main class="px-16 py-6 bg-gray-100 md:col-span-2">
        <div class="flex justify-center md:justify-end">
            <a href="#" class="btn text-primary border-primary md:border-2 hover:bg-primary hover:text-white">Log in</a>
            <a href="#" class="btn text-primary ml-2 border-primary md:border-2 hover:bg-primary hover:text-white">Sing up</a>
        </div>

        <header>
            <h2 class="text-gray-700 text-6xl font-semibold">Recipes</h2>
        </header>

        <div>
            <h4 class="font-bold mt-12 pb-2 border-b border-gray-200">Latest Recipes</h4>

            <div class="mt-8 grid lg:grid-cols-3 gap-10">
                <!-- cards go here --> 
                <div class="card">
                    <img src="~/static/stew.jpg" alt="stew" class="w-full h-32 sm:h-48 object-cover">
                    <div class="m-4">
                        <span class="font-bold">5 bean Chilli Stew</span>
                        <span class="block text-gray-500 text-sm">Recipe by Mr.A</span>
                    </div>
                    <div class="badge">
                        <svg class="w-4" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                        <span>25 mins</span>
                    </div>
                </div>

                <div class="card">
                    <img src="~/static/noodles.jpg" alt="stew" class="w-full h-32 sm:h-48 object-cover">
                    <div class="m-4">
                        <span class="font-bold">Veg Noodles</span>
                        <span class="block text-gray-500 text-sm">Recipe by Mr.B</span>
                    </div>
                    <div class="badge">
                        <svg class="w-4" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                        <span>25 mins</span>
                    </div>
                </div>

                <div class="card">
                    <img src="~/static/curry.jpg" alt="stew" class="w-full h-32 sm:h-48 object-cover">
                    <div class="m-4">
                        <span class="font-bold">Tofu Curry</span>
                        <span class="block text-gray-500 text-sm">Recipe by Mr.C</span>
                    </div>
                    <div class="badge">                                
                        <svg class="w-4" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                        <span>25 mins</span>
                    </div>
                </div>
            </div>

            <h4 class="font-bold mt-12 pb-2 border-b border-gray-200">Most Popular</h4>

            <div class="mt-8">
                <!-- cards go here -->
            </div>

            <div class="flex justify-center">
                <div class="btn bg-secondary-100 text-secondary-200">Load more</div>
            </div>
        </div>
    </main>
  
</template>

<script>
export default {

}
</script>

<style  scoped>
.card{
    @apply bg-white rounded overflow-hidden shadow-md relative hover:shadow-lg;
}
.badge{
    @apply flex space-x-1 items-center bg-secondary-100 text-secondary-200 text-xs uppercase font-bold rounded-full p-2 absolute top-0 ml-2 mt-2;
}
.btn{
    @apply rounded-full py-2 px-3 uppercase text-xs font-bold cursor-pointer tracking-wider hover:shadow-inner;
}
</style>