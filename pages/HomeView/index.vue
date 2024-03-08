<template>
    <div>
        <navbar class="margin: 0;"></navbar>
        <contents></contents>
    </div>
</template>

<script>
import Contents from '~/components/contents.vue'
import navbar from '~/layouts/navbar.vue'
    export default {
  components: { navbar, Contents },
        
    }
</script>

<style lang="scss" scoped>

</style>