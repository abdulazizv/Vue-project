<template>
    <header class="shadow-md fixed top-0 w-full">
        <div class="container-fluid">
            <nav class="flex w-full justify-between h-[70px] items-center p-4">
                <a href="#" class="nav__logo text-2xl font-bold text-indigo-500">
                    LOGO
                </a>

                <div class="nav__menu flex justify-between w-[180px]">
                    <i class="bx bx-menu"></i>
                    <div class="nav__user flex">
                        <span>Sardor Boltayev</span>
                        <i class="bx bxs-user-circle"></i>
                    </div>
                </div>
            </nav>
        </div>
</header>
</template>

<script>
    export default {
        name:'Header'
    }
</script>

<style>
</style>