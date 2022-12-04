<template>
    <div class="left">
        <ul>
            <li>Home</li>
            <li>About</li>
        </ul>
    </div>
</template>

<script>
export default {
    name: "LeftMenu"
}
</script>

<style scoped>
    .left{
        flex: 1;
        width: 250px;
        height: 100%;
        overflow: hidden;
        position: fixed;
        border-right: 1px solid #ededed;
    }
</style>