<script setup lang="ts">
import Footer from './Footer.vue';
</script>
<template>
    <main class="w-full bg-black text-white">
        <header class="px-6 relative">
            <div class="w-full flex flex-row justify-between border-b border-solid border-gray-700 pb-20 pt-6">
                <div class="basis-3/5 max-w-[280px]">
                    <img src="../assets/images/logo-white.png" alt="Logo" />
                </div>

                <a href="http://nome.wtf" class="underline underline-offset-8 basis-1/5 text-end">nome.wtf</a>
            </div>
            <div class="absolute -bottom-10 right-8 flex flex-col text-center text-xl italic">
                <span>Bitcoin</span>
                <span>Phone</span>
                <span>Wallpaper</span>
            </div>
        </header>
        <section class="w-full pt-16 p-6 md:p-14 pb-0 flex flex-col md:flex-row gap-16 max-w-[1440px]">
            <article class="xl:basis-1/3 basis-1/2">
                <div class="text-4xl italic relative w-max mb-10">
                    <h3 class="text-lg">Thank you for visiting the</h3>
                    <hr class="bottom-4 absolute w-full border-t-[3px] z-0" />
                    <h1 class="text-center">BEAR MARKET</h1>
                </div>
                <p class="text-gray-500 italic text-sm">
                    The exhibition is designed as an immersive experience for the community
                    to showcase the new Bitcoin Ordinals technology.
                </p>
                <p class="mt-10 text-gray-500 italic text-sm">
                    To get a free BTC wallpaper on mobile:
                </p>

                <div class="w-full">
                    <ol class="mt-8 flex flex-col gap-2 text-sm">
                        <li>1. Download & install <a href="">Xverse</a> wallet</li>
                        <li>
                            2. Go to the browser section -
                            <img src="../assets/images/world_icon.png" alt="" class="h-4 inline" />
                        </li>
                        <li>
                            3. Enter URL on top:
                            <a class="inline underline underline-offset-4 italic" href="https://nome.gallery/miami">
                                nome.gallery/miami
                            </a>
                        </li>
                        <li>4. Proceed with the mint in the wallet</li>
                    </ol>
                    <input type="email" placeholder="email"
                        class="max-w-xs bg-black px-4 py-2 rounded-xl border border-solid border-gray-500 w-full mt-10 placeholder:italic placeholder:text-gray-600 text-lg outline-0">
                </div>
            </article>
            <aside class="xl:basis-1/3 basis-1/2">
                <img src="../assets/images/bear-wallpaper.png" alt="" class="w-auto max-h-[600px]">
            </aside>
        </section>
        <Footer />
    </main>
</template>
