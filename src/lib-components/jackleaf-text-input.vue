<template>
    <input type="text" :name="name">
</template>
<script>
import { defineComponent } from "vue";

export default /*#__PURE__*/ defineComponent({
    name: "JackleafTextInput", // vue component name

    props: {
        name: {
            type: String,
            default: Math.random().toString(5)
        }
    }
});
</script>
