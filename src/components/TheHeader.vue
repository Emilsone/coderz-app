<template>
    <nav class=" bg-menu w-full flex relative justify-between items-center mx-auto px-8 h-20">
        <!-- logo -->
        <div class="inline-flex items-center">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"
                class="w-6 h-6">
                <path stroke-linecap="round" stroke-linejoin="round"
                    d="M17.25 6.75L22.5 12l-5.25 5.25m-10.5 0L1.5 12l5.25-5.25m7.5-3l-4.5 16.5" />
            </svg>


            <h1 class="text-2xl font-bold px-2 text-white">Coderz</h1>
        </div>

        <!-- end logo -->

        <!-- second menu  bar -->
        <div class="hidden sm:block flex-shrink flex-grow-0 justify-start px-2">
            <div class="inline-block">
                <div class="inline-flex items-center max-w-full ">

                    <a class="inline-block py-2 px-10  " href="#">
                        <div class="flex items-center relative cursor-pointer whitespace-nowrap">Services</div>
                    </a>
                    <a class="inline-block py-2 px-10  " href="#">
                        <div class="flex items-center relative cursor-pointer whitespace-nowrap">Pricing</div>
                    </a>
                    <button class=" border-0 py-2 px-6 mx-4 focus:outline-none rounded text-md">Workspace Visible</button>

                </div>
            </div>
        </div>
        <!-- end of second menu bar -->

        <!-- login -->
        <div class="flex-initial">
            <div class="flex justify-end items-center relative">
                <div class="flex mr-4 items-center">
                    <a class="inline-block py-2 px-10 bg-btn " href="#">
                        <div class="flex items-center relative cursor-pointer whitespace-nowrap">TRY FOR FREE</div>
                    </a>

                </div>
            </div>
        </div>
    </nav>
</template>

<style>
.bg-menu {
    background-color: #1E1822;
    color: rgb(191, 191, 191);
}

.bg-btn {
    background-color: #1E1822;
    color: white;
    border: 2px solid white;
}
</style>
