<template>
    <div class="v-main-wrapper">
        <p>{{title}}</p>
        <v-catalog />
        <v-cart />
    </div>
</template>

<script>
 import vCatalog from './v-catalog'
 import vCart from './v-cart'

 export default {
    name: 'v-main-wrapper',
    components: {
        vCatalog,
        vCart
    },
    props: {},
    data() {
        return{
            title: 'Main wrapper'
        }
    },
    computed: {}, //вычисления
    methods: {}, //анимация, то, что отлавливает действия пользователя
    watch: {}, //следить за изменением элементов
    mounted() {
      console.log('Hello i am alive')
    } //отрабатывает, когда все загрузитс
 }
</script>

<style scoped>
 .v-main-wrapper {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    min-width: 900px;
    margin: 0auto;
    }
</style>