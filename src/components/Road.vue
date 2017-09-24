<template>
</template>
<script>
    export default {
        name: 'road',
        props: {
            "width": {
                type: Number,
                default: 8
            },
            "length": {
                type: Number,
                default: 100
            }, 
            "startX": {
                type: Number,
                default: 2
            }, 
            "startY": {
                type: Number,
                default: 2
            }
        },
        computed: {
            endX: function () {
                return this.startX + this.width
            },
            endY: function () {
                return this.startY + this.length;
            },
            height: function () {
                return this.height || 100;
            }
        },
        data() {
            return {
                name: 'road',
                type:"container"
            }
        }
    }

</script>

<style scoped>

</style>