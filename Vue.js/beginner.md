# Vue.js

## Vue.vue template    
    <template>
       <p>Hello {{name}}</p>
    </template>

    <script>
       module.exports = {
           data(){
               return name: 'Padraic'
           }
       }
    </script>

    <style scoped>
        p {color: blue}
    </style>


## NPM
    npm install vue


## Directives
    v-on:click="click()"

    v-model="modelName"

    v-for="item in items"