<template>
  <div>
<!--    <TreeRelationGraph/>-->
    <OrgRelationGraph/>
  </div>
</template>

<script>
import TreeRelationGraph from "@/components/TreeRelationGraph"
import OrgRelationGraph from "@/components/OrgRelationGraph"

export default {
  name: 'App',
  components:{
    TreeRelationGraph,
    OrgRelationGraph
  }

}
</script>

<style>

</style>
