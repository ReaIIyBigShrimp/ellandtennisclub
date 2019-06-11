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
    background-color:#000;
    padding:30px;
    }

    footer p {
    color: $primary-colour;
    }
</style>