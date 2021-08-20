<template>
    <div class="help">
        <h1>first header</h1>
        <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Nam
            consectetur nulla corporis? Magnam, mollitia deleniti laborum
            officiis nisi autem sapiente?
        </p>
        <MyAge />
    </div>
</template>

<script>
import MyAge from "@/components/MyAge.vue";

export default {
    name: "help",
    components: {
        MyAge,
    },
};
</script>
