<template>
    <header class="shadow-md fixed top-0 w-full z-10">
        <div class="container-fluid">
            <nav class="flex w-full justify-between h-[70px] items-center p-4">
                <a href="#" class="nav__logo text-2xl font-bold text-indigo-500">
                    LOGO
                </a>

                <div class="nav__menu flex items-center justify-between w-[200px]  p-2">
                    <i @click="toogleBtn" class="bx bx-menu text-3xl text-indigo-600"></i>
                    <div class="nav__user flex items-center">
                        <span class=" font-semibold text-indigo-800 mr-2">Sardor Boltayev</span>
                        <i class="bx bxs-user-circle text-2xl text-indigo-500  duration-300 rounded-full"></i>
                    </div>
                </div>
            </nav>
        </div>
</header>
</template>

<script>
    export default {
        name:'Header',
        props: {
            toogleBtn: {
                type:Function,
                required:true
            }
        }
    }
</script>

<style>
</style>