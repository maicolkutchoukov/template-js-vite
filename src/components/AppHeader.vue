<script>
export default {
    data() {
        return { 
            title : 'Ciao Ragazzi' 
        };
    },
};
</script>

<template>
    <header class="main-title">
        <h1>
            {{ title }}
        </h1>
    </header>
</template>

<style scoped>
    header {
        padding: 20px;
        background-color: black;
    }
</style>
