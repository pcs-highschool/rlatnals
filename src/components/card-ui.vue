<template>
    <div class="amuz-card">
        <h2 v-if="menuTitie">
            {{ menuTitie}}
        </h2>
        <p v-else class="untitle">
            no title
        </p>
    </div>
</template>

<script>

export default {
    props :{
        menuTitie : String,
    }
}
</script>

<style>
.custom_input{
    padding: 20px;
    font-size: 20px;
    display: block;
    widows: 100%;
    box-sizing: border-box;
    margin: 20px 0;
}
</style>