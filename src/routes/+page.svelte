<section
    class="min-h-screen bg-gray-800 text-white flex justify-center items-center w-full flex-col gap-30"
>
    <span class="flex flex-col items-center w-2/3 gap-3">
        <h1 class="font-bold text-3xl">
            Website terbaik untuk informasi seputar game
        </h1>
        <p class="text-center">
            Bitech.id memberikan berita terbaru, tier list, informasi game, dan
            panduan untuk game seperti: Honkai Star Rail, Genshin Impact,
            Zenless Zone Zero, Wuthering Waves dan masih banyak lagi. Mari
            bangun komunitas yang sehat
        </p>
    </span>

    <div class="flex flex-col gap-5 items-center w-full">
        <h3 class="text-xl font-bold">Game yang sering dicari</h3>
        <div class="grid grid-cols-4 gap-5 w-full pl-10 pr-10 h-30">
            {#each { length: 4 }}
                <div class="border rounded-lg">
                    <h5>Harvest Moon Back To Nature</h5>
                </div>
            {/each}
        </div>
    </div>
</section>
