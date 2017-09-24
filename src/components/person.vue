<template>
</template>
<script>
    export default {
        name: 'person',
        props: {
            "width": {
                type: Number,
                default: 1
            },
            "length": {
                type: Number,
                default: 1
            },
            "height": {
                type: Number,
                default: 2
            }
        },
        computed: {

        },
        data() {
            return {
                name: 'person',
                type: 'Solid'
            }
        }
    }

</script>

<style scoped>

</style>