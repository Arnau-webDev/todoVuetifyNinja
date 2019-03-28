<template>
    <v-content>
        <v-btn class="pink white--text">Click Me!</v-btn>
        <v-btn depressed color="pink">Click me!</v-btn>
        <v-btn flat color="green">Click Me</v-btn>

        <v-btn depressed class="pink white--text">
        <v-icon left>email</v-icon>
        <span>email Me!</span>
        </v-btn>

        <v-btn depressed small class="pink white--text">
        <v-icon left small>email</v-icon>
        <span>email Me!</span>
        </v-btn>

        <v-btn depressed large class="pink white--text">
        <span>email Me!</span>
            <v-icon right large>email</v-icon>
        </v-btn>

        <v-btn fab depressed small dark color="purple">
        <v-icon>favorite</v-icon>
        </v-btn>
    </v-content>
</template>

<script>
export default {
    name: "buttons"
}
</script>
