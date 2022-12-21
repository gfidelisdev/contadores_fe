<template>
    <v-container fluid grid-list-xs>
        <!-- Top Tabs-->
        <topnav />
        <by-month />
        <!-- Main body -->
    </v-container>
</template>

<script>
import ByMonth from './ByMonth.vue'
import Topnav from './Topnav.vue'
export default {
  components: { Topnav, ByMonth },

}
</script>

<style>

</style>