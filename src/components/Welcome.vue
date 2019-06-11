<template>
    <div class="welcome">
        <h1>Welcome to Elland Tennis Club</h1>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam at augue finibus tortor feugiat volutpat ut eget nulla. Nulla ut ex in dui suscipit pretium. Pellentesque dapibus justo eget ante tempor, et lacinia nunc malesuada. Maecenas sed odio eu sem vehicula tempus. Vestibulum sed quam ligula. Nunc dapibus sapien at mauris mollis laoreet. Donec sem arcu, ornare in felis ac, bibendum porta justo. Sed et enim lobortis, tempor justo in, porttitor est. In ornare orci sed auctor condimentum. Phasellus sollicitudin quam sed sodales tincidunt.</p>
    </div>
</template>
<script>
export default {
    name: "Welcome"
}
</script>
<style lang="scss" scoped>
    @import "../scss/variables.scss";
    .welcome {
        h1 {
            font-family: $primary-heading;
        }
        p {
            font-family: $primary-text;
            padding: 30px;
        }
    }
</style>


