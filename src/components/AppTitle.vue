<script>
export default {
    name: "AppTitle",
    data() {
        return {
            message: 'La mia prima app con Vite!'
        }
    }
}
</script>

<template lang="">
    <div class="title">
        <h1>{{ message }}</h1>
    </div>
</template>

<style>
.title {
    color: white;
    background-color: rgba(58, 58, 58, 0.747);
    text-align: center;
    border-radius: 20px;
}
</style>
