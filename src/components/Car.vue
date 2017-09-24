<template>
</template>
<script>
    export default {
        name: 'car',
        props: {
            "width": {
                type: Number,
                default: 2
            },
            "length": {
                type: Number,
                default: 4
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
                name: 'Car',
                type: 'Solid'
            }
        }
    }

</script>

<style scoped>

</style>