<template>
    <div class="conversor">
        <h2>{{ moedaA }} para {{ moedaB }}</h2>

    </div>

</template>


<script>
export default {
    name: "ConversorDeMoeda",
    props: ["moedaA","moedaB"]
};
</script>



<style scoped>

</style>