<script>
import { defineComponent } from "vue";
// Uncomment import and local "components" registration if library is not registered globally.
import { JackleafSample } from "@/entry.esm";

export default defineComponent({
    name: "ServeDev",
    components: {
        JackleafSample,
    },
});
</script>
