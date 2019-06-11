<template>
    <nav>
        <ul>
            <li>Facilities</li>
            <li>Membership</li>
            <li>Coaching</li>
            <li>Contact</li>
        </ul>
    </nav>
</template>
<script>
export default {
    name: "Nav"
}
</script>
<style lang="scss" scoped>
@import "../scss/variables.scss";
    nav ul {
        display: flex;
        flex-direction: row;
        justify-content: center;
        list-style-type: none;
        padding: 0;
        li {
            a {
            padding: 30px;
            }
            a:link {}
            // Change to primary theme colour
            a:hover {
            color: $primary-colour;
            cursor: pointer;
            border-bottom: 1px solid $primary-colour;
            }
            a:active {
            color: $primary-colour;
            }
        }
    }
</style>
