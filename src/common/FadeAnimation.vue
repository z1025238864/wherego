<template>
    <div class='fadeanimation'>
        <slot></slot>
    </div>
</template>
<script>
 export default {
    name:'FadeAnimation',

}
</script>

<style lang='stylus' scoped>
    .v-enter, .v-leave-to
        opacity 0
    .v-enter-active, .v-leave-to-active
        transition:opacity .5s 

    

</style>
