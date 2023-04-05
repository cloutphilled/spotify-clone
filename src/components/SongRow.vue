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
    <div>

    </div>
</template>