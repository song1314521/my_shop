<template>
    <div>
        这里有一个数字：{{this.$store.state.num}}
        <button @click="sub">-</button>
    </div>
</template>


<script>
export default {
    methods: {
        sub(){
            this.$store.commit('sub');
        }
    },
}
</script>

<style scoped>

</style>