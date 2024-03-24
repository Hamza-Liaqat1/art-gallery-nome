<script setup lang="ts"></script>

<template>
  <div class="relative bg-black">
    <div class="w-full h-full z-10 relative flex flex-col items-center">
      <header data-v-4529bac1="" class="flex justify-between w-full">
        <div data-v-4529bac1="" class="flex-1 p-8 pl-12">
          <div data-v-4529bac1="" class="drawer">
            <input
              data-v-4529bac1=""
              id="my-drawer"
              type="checkbox"
              class="drawer-toggle peer"
            />
            <div
              data-v-4529bac1=""
              class="drawer-content peer-checked:italic peer-checked:fixed z-30"
            >
              <label
                data-v-4529bac1=""
                for="my-drawer"
                class="uppercase border-b-2 gap-x-1 flex text-lg drawer-button w-max cursor-pointer active:italic"
                ><span data-v-4529bac1="">M</span
                ><span data-v-4529bac1="">e</span
                ><span data-v-4529bac1="">n</span
                ><span data-v-4529bac1="">u</span></label
              >
            </div>
            <div data-v-4529bac1="" class="drawer-side z-20">
              <label
                data-v-4529bac1=""
                for="my-drawer"
                aria-label="close sidebar"
                class="drawer-overlay"
              ></label>
              <ul data-v-4529bac1="" class="pt-24 w-80 min-h-full pl-10">
                <li
                  data-v-4529bac1=""
                  class="mb-4 text-base-content hover:text-gray-200"
                >
                  <a
                    data-v-4529bac1=""
                    aria-current="page"
                    href="/intro"
                    class="router-link-active router-link-exact-active"
                    >→ verify</a
                  >
                </li>
                <!---->
              </ul>
            </div>
          </div>
        </div>
        <div
          data-v-4529bac1=""
          class="relative flex flex-col items-center flex-1"
        >
          <h1
            data-v-4529bac1=""
            class="uppercase text-white text-2xl text-center flex justify-between w-3/4 max-w-[18rem] sm:w-full mx-auto mt-8"
          >
            <span data-v-4529bac1="">G</span><span data-v-4529bac1="">a</span
            ><span data-v-4529bac1="">l</span><span data-v-4529bac1="">l</span
            ><span data-v-4529bac1="">e</span><span data-v-4529bac1="">r</span
            ><span data-v-4529bac1="">y</span>
          </h1>
          <img
            data-v-4529bac1=""
            src="../assets/images/logo-white-aba8b728.png"
            alt="NoMe logo"
            class="w-3/4 max-w-[18rem] sm:w-full mx-auto mt-8"
          />
        </div>
        <div
          data-v-4529bac1=""
          class="pt-8 pr-12 flex gap-x-8 flex-1 justify-end"
        >
          <a href="https://twitter.com/nome_nft" target="_blank"
            ><img
              src="../assets/images/twitter-icon-373efc30.png"
              alt=""
              class="hover:opacity-80 transition-all opacity-50 w-[1.6rem] h-[1.6rem] invert" /></a
          ><a href="https://discord.gg/nome" target="_blank"
            ><img
              src="../assets/images/discord-icon-9a7fbe08.png"
              alt=""
              class="hover:opacity-80 transition-all opacity-50 w-[1.6rem] h-[1.6rem] invert" /></a
          ><a href="https://youtube.com/@nome_nft" target="_blank"
            ><img
              src="../assets/images/youtube-icon-8db9a521.png"
              alt=""
              class="hover:opacity-80 transition-all opacity-50 w-[1.6rem] h-[1.6rem] invert"
          /></a>
        </div>
      </header>
      <div
        class="max-w-4xl text-xl sm:text-3xl text-white italic text-center mt-12 sm:mt-28 font-sans-serif px-8"
      >
        <h2 class="leading-[1.7] tracking-[0.055em]">
          Welcome to the NōME gallery – a space for premium 1/1 art and unique
          digital experiences
        </h2>
        <h2 class="mt-9 leading-[1.7] tracking-[0.055em]">
          $NOME BRC-20 gives access to gallery <br />
          exhibitions and art tools. Verify or buy tokens to enter
        </h2>
      </div>
      <div class="mt-16 sm:mt-40 pb-32 flex flex-col items-center">
        <div class="flex flex-col sm:flex-row gap-4">
          <button
            class="bg-transparent text-white rounded-lg border border-pink transition-all hover:bg-pink pl-6 py-1 pr-4 tracking-[0.3em] disabled:opacity-50 w-32"
          >
            VERIFY</button
          ><a
            href="https://unisat.io/market/brc20?tick=N0ME"
            target="_blank"
            class="bg-transparent text-white rounded-lg border border-pink transition-all hover:bg-pink pl-6 py-1 pr-4 tracking-[0.3em] disabled:opacity-50 w-32 text-center"
          >
            BUY
          </a>
        </div>
        <!---->
      </div>
    </div>
  </div>
</template>
