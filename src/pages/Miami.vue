<script setup lang="ts"></script>
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
        <section class="w-full pt-16 p-6 sm:p-14 pb-0">
            <div class="text-4xl italic relative w-max mb-10">
                <h3 class="text-lg">Thank you for visiting the</h3>
                <hr class="bottom-4 absolute w-full border-t-[3px] z-0" />
                <h1 class="text-center">BEAR MARKET</h1>
            </div>
            <p class="text-gray-500 italic">
                The exhibition is designed as an immersive experience for the community
                to showcase the new Bitcoin Ordinals technology.
            </p>
            <p class="mt-10 text-gray-500 italic">
                To get a free BTC wallpaper on mobile:
            </p>

            <ol class="mt-8 flex flex-col gap-2">
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
        </section>
    </main>
</template>
