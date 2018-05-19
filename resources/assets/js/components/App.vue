<template>
    <div>
        <p>
           Let's rock!
        </p>
    </div>
</template>

<script>
    export default {
        mounted() {
            console.log('Seems to be working ok.')
        }
    }
</script>

<style lang="scss">
//These are supposed to be global. Not scoped.

   @import "../../sass/app.scss";


    body {
        //color: #535353;
        //font-family: 'Raleway', sans-serif;

        >div {
            font-size: 24px;
            font-weight: bold;
            text-transform: uppercase;
        }
    }
</style>
