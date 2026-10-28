<template>
    <header class="flex items-center justify-between border-b-2 border-[gray] m-4">
        <picture>
            <img src="https://www.thuisarts.nl/themes/custom/thuisarts_theme/logo.svg?v=2" alt="">
        </picture>

        <a href="#footer" class="font-semibold">Menu</a>
    </header>

    <main class="m-4">
        <h1 class="text-[2rem] font-medium leading-[1.1] mt-4 mb-2">Betrouwbare informatie over ziekte en gezondheid</h1>
        <p>De eerste plek waar je het checkt.</p>
        <img class="rounded-2xl my-4" src="https://www.thuisarts.nl/themes/custom/thuisarts_theme/storybook/images/hero/hero--homepage--v2--x1.webp" alt="">

        <div class="flex justify-between">
            <figure class="relative rounded-2xl overflow-hidden w-[48%]">
                <img src="https://www.thuisarts.nl/sites/default/files/styles/page_header_mobile_x1/public/2025-11/shutterstock_717576340.jpg.webp?itok=6i-UE7Yz" alt="">
                <figcaption class="absolute bottom-0 w-full pt-20 px-6 pb-6 text-white text-xl font-semibold bg-linear-to-t from-[#002b20f2] via-[#002b20cc] via-40% to-[#002b2000]">Door artsen</figcaption>
            </figure>

            <figure class="relative rounded-2xl overflow-hidden w-[48%]">
                <img src="https://bynder.nhg.org/asset/b32f9c6d-67c7-461c-975a-d92e662f944b/Subject-Sidebar/Bloed-in-je-urine.jpg" alt="">
                <figcaption class="absolute bottom-0 w-full pt-20 px-6 pb-6 text-white text-xl font-semibold bg-linear-to-t from-[#002b20f2] via-[#002b20cc] via-40% to-[#002b2000]">Voor iedereen</figcaption>
            </figure>
        </div>

        <section class="mt-4">
            <article class="mb-4 min-[495px]:flex min-[495px]:items-center min-[495px]:gap-2">
                <img class="rounded-2xl min-[495px]:w-[200px]" src="https://www.thuisarts.nl/themes/custom/thuisarts_theme/storybook/images/hero/hero--homepage--v2--x1.webp" alt="">
                <section>
                    <span class="uppercase text-[red] text-[13px]">Haarverzorging</span>
                    <h3 class="text-xl font-medium">Luizen op het hoofd: kam 2 weken elke dag</h3>
                </section>
            </article>
        </section>

        <section class="bg-[#D73F0D] text-white p-4 rounded-2xl mb-4">
            <h2 class="text-2xl font-medium">Download nu de app van Thuisarts</h2>
            <p>Met de app heb je Thuisarts steeds bij de hand. Zo vind je snel een betrouwbaar antwoord op al je vragen over gezondheid en ziekte.</p>
            <div class="flex justify-between my-4">
                <a class="flex items-center gap-2 bg-black w-fit rounded-[20px] p-2">
                    <img class="size-[50px] rounded-none object-cover" src="https://rabbitlogo.com/wp-content/uploads/2026/01/apple-1.jpg" alt="">
                    <section>
                        <p>Download in de</p>
                        <h3 class="text-xl font-medium">App Store</h3>
                    </section>
                </a>
                <a class="flex items-center gap-2 bg-black w-fit rounded-[20px] p-2">
                    <img class="size-[50px] rounded-none object-cover" src="https://cdn.vectorstock.com/i/500p/55/50/google-play-logo-white-vector-46345550.jpg" alt="">
                    <section>
                        <p>Ontdek het op</p>
                        <h3 class="text-xl font-medium">Google Play</h3>
                    </section>
                </a>
            </div>
            <img src="https://www.thuisarts.nl/sites/default/files/styles/promotion_block_highres/public/app_promotion_banner_image/phone-with-app--in-hand_0.png.webp?itok=ngBC8rJw" alt="">
        </section>
    </main>

    <footer id="footer" class="bg-[#023729] p-4">
        <nav class="grid mb-8">
            <h3 class="text-[#D8FF7C] text-xl font-medium">Thuisarts</h3>
            <a class="text-white w-fit" href="">Spoed: wie bellen?</a>
            <a class="text-white w-fit" href="">Over Thuisarts</a>
            <a class="text-white w-fit" href="">Nieuws</a>
            <a class="text-white w-fit" href="">Dutch Healthcare</a>
        </nav>

        <nav class="grid mb-8">
            <h3 class="text-[#D8FF7C] text-xl font-medium">Informatie</h3>
            <a class="text-white w-fit" href="">Disclaimer</a>
            <a class="text-white w-fit" href="">Toegankelijkheid</a>
            <a class="text-white w-fit" href="">Privacyverklaring</a>
            <a class="text-white w-fit" href="">Samenwerken met Thuisarts</a>
            <a class="text-white w-fit" href="">Contact</a>
        </nav>

        <nav class="grid mb-8">
            <h3 class="text-[#D8FF7C] text-xl font-medium">Handige links</h3>
            <a class="text-white w-fit" href="">Alle klachten en ziektes</a>
            <a class="text-white w-fit" href="">Video's</a>
            <a class="text-white w-fit" href="">Afbeeldingen</a>
            <a class="text-white w-fit" href="">Keuzehulpen</a>
            <a class="text-white w-fit" href="">Keuzekaarten</a>
        </nav>

        <span class="text-white font-medium">© Thuisarts 2026</span>
    </footer>
</template>
