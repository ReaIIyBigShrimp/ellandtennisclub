<template>
    <footer>
        <p>This is the footer.</p>
    </footer>
</template>
<script>
export default {
    name: "Footer"
}
</script>
<style lang="scss" scoped>
@import "../scss/variables.scss";
    footer {
        background-color: #191919;
        padding: 30px;
        p {
            color: #fff;
            font-family: $primary-text;
        }
    }
</style>