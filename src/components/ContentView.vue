<template>
    <div class="body">
        <TopImage/>
        <SkinCare/>
        <LifeStyle/>
        <HairStyle/>
        
        <NailStyle/>
    </div>
</template>

<script >
// import TopImage from './content/TopImage.vue';
import SkinCare from './content/SkinCare.vue';
import LifeStyle from './content/LifeStyle.vue';
import HairStyle from './content/HairStyle.vue';
import NailStyle from './content/NailStyle.vue';
import TopImage from './content/TopImage.vue';
    export default {
    
    components: { SkinCare, LifeStyle, HairStyle, NailStyle, TopImage }
}
</script>

<style lang="scss" scoped>

</style>