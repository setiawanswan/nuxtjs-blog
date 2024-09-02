<template>
    <div>
        <header class="shadow-sm bg-white">
            <nav class="container mx-auto p-4 flex justify-between">
                <NuxtLink to="/" class="font-bold">BMKG </NuxtLink>
                <ul class="flex gap-4">
                    <li><NuxtLink to="/">Home</NuxtLink></li>
                    <li><NuxtLink to="/about">Blog</NuxtLink></li>
                </ul>
                <ul class="flex gap-4">
                    <li><NuxtLink to="/">Login</NuxtLink></li>
                </ul>
            </nav>
        </header>
        <div class="container mx-auto p-4">
            <slot />
        </div>
        <div class="bg-stone-700">
            <div class="container mx-auto p-4 flex justify-center text-white">
                    <div class="px-2 py-2 mt-2">BMKG</div>
                    <div class="px-2 py-2">
                        <div>
                            Kantor Pusat Jl. Angkasa I No.2 Kemayoran, Jakarta Pusat,
                        </div>
                        <div>
                            DKI Jakarta 10610 PO Box 3540 Jkt. Call Center (021) 196
                        </div>
                    </div>
            </div>
        </div>
        <div class="bg-stone-900">
            <div class="container mx-auto p-4 flex justify-center text-white">
                <div class="px-2 py-2 mt-2">2021 – Badan Meteorologi, Klimatologi, dan Geofisika</div>
            </div>
        </div>
    </div>
</template>

<style scoped>
    .router-link-exact-active {
        color: green;
    }
</style>