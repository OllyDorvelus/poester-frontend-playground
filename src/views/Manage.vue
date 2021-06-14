<template>
  <section>
    <PoemTable />
  </section>
</template>

<script>
import PoemTable from "@/components/PoemTable.vue";

export default {
  name: "Manage",

  components: {
    PoemTable: PoemTable,
  },
};
</script>
