<script setup>
    import {ref, toRefs, onMounted} from 'vue'
    import Play from 'vue-material-design-icons/Play.vue'
    import Pause from 'vue-material-design-icons/Pause.vue'
    import Heart from 'vue-material-design-icons/Heart.vue'

    let isHover = ref(false)
    let isTrackTime = ref(null)

    const props = defineProps({
        track: Object,
        artist: Object,
        index: Number,
    })

    const { track, artist, index } = toRefs(props)


</script>

<template>
    <li
        class="flex items-center justify-between rounded-md hover:bg-[#2A2929]"
        @mouseenter="isHover = true"
        @mouseleave="isHover = false"
    >
        <div class="flex items center w-full">
            <div class="w-[40px] ml-[14px] mr-[6px] cursor-pointer">
                <Play v-if="true" fillColor="#FFFFFF" :size="25" />
                <Pause v-else follColor="#FFFFFF" :size="25" />
            </div>
        </div>
    </li>
</template>