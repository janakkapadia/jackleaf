<template>
    <button>{{label}}</button>
</template>
<script>
import { defineComponent } from "vue";

export default /*#__PURE__*/ defineComponent({
    name: "JackleafButton", // vue component name

    props: {
        label: {
            type: String,
            default: 'Submit'
        }
    }
});
</script>
