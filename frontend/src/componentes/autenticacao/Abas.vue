<template>
    <v-container fluid>
        <v-tabs
            color="grey lighten-3"
            slider-color="blue">
            <v-tab ripple>
                Sign up
            </v-tab>
            <v-tab ripple>
                Sign in
            </v-tab>
            <v-tab-item>
                <Registrar />
            </v-tab-item>
            <v-tab-item>
                <Login />
            </v-tab-item>
        </v-tabs>
    </v-container>
</template>

<script>
import Registrar from './Registrar'
import Login from './Login'
export default {
    components: { Registrar, Login }
}
</script>

<style>

</style>
