<template>
    <v-app dark app>
        <v-app-bar color="deep-purple" dark app>
            <v-toolbar-title>Vuetify Tutoria</v-toolbar-title>
        </v-app-bar>
        <v-content>
            <router-view/>
        </v-content>
    </v-app>
    <!-- <div id="app">
                <v-app dark>
                    <div>
                        <v-btn color="success" v-on:click="changeProduct">Success</v-btn>
                        <v-btn color="error">Error</v-btn>
                        <v-btn color="warning">Warning</v-btn>
                        <v-btn color="info">Info</v-btn>
                    </div>
                    <h1>{{product}}</h1>
                    <ul>
                        <li v-for="detail in details">{{detail}}</li>
                    </ul>
                    <v-toolbar class="deep-purple"></v-toolbar>
                    <v-content>
                    </v-content>
                </v-app>
            </div> -->
</template>

<script>
    export default {
        mounted() {
            console.log('Component mounted.')
        },
        data() {
            return {
                product: 'askss',
                details: ['a', '1', '2']
            }
        },
        methods: {
            changeProduct() {
                this.product = "aa";
            }
        }
    }
</script>
