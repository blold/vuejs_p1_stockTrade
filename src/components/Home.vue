<template>
    <div>
        <h1>Trade or View your portfolio</h1>
        <h6>You may Save & load Data</h6>
        <h6>Click on 'End day' to begin a new Day!</h6>
        <hr>
        <p>your Funds: {{funds | currency}}</p>
    </div>    
</template>

<script>
export default {
    computed: {
        funds(){
            return this.$store.getters.funds;
        }
    }
}
</script>

<style>

</style>

