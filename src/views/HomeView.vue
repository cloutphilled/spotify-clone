<script setup>
    import HomeCard from '../components/HomeCard.vue'
</script>

<template>
    <div class="p-8">
        <button
            type="button"
            class="text-white text-2xl font-semibold hover:underline cursor-pointer"
        >
            Podcasts to make you smarter
        </button>

        <div class="py-1.5"></div>
        <div class="flex items-center">
            <HomeCard image="../public/images/albumCovers/delude.png" title="Delude" subTitle="Telos" />
            <HomeCard image="../public/images/albumCovers/abyss.jpg" title="Abyss" subTitle="Regarding Ambiguity"/>
            <HomeCard class="md:block hidden" image="../public/images/albumCovers/flayed.png" title="Flayed" subTitle="Regarding Ambiguity"/>
            <HomeCard class="lg:block hidden" image="https://picsum.photos/id/67/300/300" title="2" subTitle="2"/>
            <HomeCard class="xl:block hidden" image="https://picsum.photos/id/100/300/300" title="2" subTitle="2"/>
        </div>
        
    </div>
    <div class="p-8">
        <button
            type="button"
            class="text-white text-2xl font-semibold hover:underline cursor-pointer"
        >
            Recommended radio
        </button>

        <div class="py-1.5"></div>
        <div class="flex items-center">
            <HomeCard image="https://picsum.photos/id/30/300/300" title="Title is here" subTitle="Subtitle is here"/>
            <HomeCard image="https://picsum.photos/id/45/300/300" title="Title is here" subTitle="Subtitle is here"/>
            <HomeCard class="md:block hidden" image="https://picsum.photos/id/65/300/300" title="Title is here" subTitle="Subtitle is here"/>
            <HomeCard class="lg:block hidden" image="https://picsum.photos/id/67/300/300" title="Title is here" subTitle="Subtitle is here"/>
            <HomeCard class="xl:block hidden" image="https://picsum.photos/id/100/300/300" title="Title is here" subTitle="Subtitle is here"/>
        </div>
        
    </div>
    <div class="p-8">
        <button
            type="button"
            class="text-white text-2xl font-semibold hover:underline cursor-pointer"
        >
            Recommended songs
        </button>

        <div class="py-1.5"></div>
        <div class="flex items-center">
            <HomeCard image="https://picsum.photos/id/30/300/300" title="Title is here" subTitle="Subtitle is here"/>
            <HomeCard image="https://picsum.photos/id/45/300/300" title="Title is here" subTitle="Subtitle is here"/>
            <HomeCard class="md:block hidden" image="https://picsum.photos/id/65/300/300" title="Title is here" subTitle="Subtitle is here"/>
            <HomeCard class="lg:block hidden" image="https://picsum.photos/id/67/300/300" title="Title is here" subTitle="Subtitle is here"/>
            <HomeCard class="xl:block hidden" image="https://picsum.photos/id/100/300/300" title="Title is here" subTitle="Subtitle is here"/>
        </div>
        
    </div>
</template>
