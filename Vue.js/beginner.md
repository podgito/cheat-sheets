# Vue.js

## Vue.vue template    
    <template>
       <p>Hello {{name}}</p>
    </template>

    <script>
       module.exports = {
           data(){ //function
               return name: 'Padraic'
           },
           methods:{ //object
                userAction(){

                }
           }
           computed:{
               computedData(){

               }
           }
       }
    </script>

    <style scoped>
        p {color: blue}
    </style>


## NPM
    npm install vue

    npm install vue-router


## Directives
    v-on:click="click()"

    v-model="modelName"

    v-for="item in items"

    v-if="booleanValue"

    v-bind:src="someProperty"

    v-once (optimisation for bindings that will be evaulated once)

## Ecosystem
#### Nuxt
Server-side rendering?
#### Vuex
State management. Very similar to Flux and Redux
#### Vuetify
Material components for Vue
#### Vue-CLI
Scaffolding

    - vue serve

    - vue build

    - vue create
    - vue ui

    - vue add

