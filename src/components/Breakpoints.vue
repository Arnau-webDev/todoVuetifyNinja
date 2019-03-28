<template>
    <v-content>
        <v-btn class="hidden-md-and-down">Click Me!</v-btn>

        <v-btn class="hidden-md-and-up">Click Me!</v-btn>

        <v-btn class="hidden-sm-only">Click Me!</v-btn>
    </v-content>
</template>

<script>
export default {
    name: "breakpoints",
    mounted() {
      console.log(this.$vuetify.breakpoint);
    }
}
</script>

<style>

</style>
