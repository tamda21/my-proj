<template>
    <ul class="mySit">
        <li>html</li>
        <li>css</li>
        <li>js</li>
        <li>vue</li>
    </ul>
</template>

<script>
export default {
    name: "Seting",
};
</script>
<style scoped lang="scss">
.mySit {
    list-style: none;
    display: inline-block;
    li {
        width: 100px;
        float: left;
        color: red;
        font-size: 30px;
    }
}
</style>
