<template>
  <DashboardLayout title="Funding">
    <template v-slot:child>
      <TableFunding/>
    </template>
  </DashboardLayout>
</template>

<script>
import DashboardLayout from "@/templates/DashboardLayout.vue";
import { TableFunding } from "@/components"
export default {
  name: "FundingPage",
  components: {
    DashboardLayout,
    TableFunding
  },
};
</script>

<style>
</style>
