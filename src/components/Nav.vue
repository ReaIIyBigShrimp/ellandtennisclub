<template>
    <nav>
        <ul>
            <li><a>Facilities</a></li>
            <li><a>Membership</a></li>
            <li><a>Coaching</a></li>
            <li><a>Contact</a></li>
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
    nav {
        margin-top: 20px;
        ul {
            display: flex;
            flex-direction: row;
            justify-content: center;
            list-style-type: none;
            padding: 0;
            li {
                a {
                    padding: 30px;
                }
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
    }
</style>
