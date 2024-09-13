<template>
    <div>
        <h2>{{ heading }}</h2>
        <p>{{ paragraph }}</p>
        <ButtonComponent />
        

    </div>
</template>

<script>
import ButtonComponent from '@/components/ButtonComponent.vue'
    export default {
        name: 'HomeAbout',
        components: {
            ButtonComponent
        },
        data(){
            return{
                heading: 'calling component from component/home path',
                paragraph: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum tempore ullam laboriosam voluptate mollitia debitis, sed impedit quo, incidunt, dolor illo cum illum quasi! Nesciunt minima laudantium suscipit ab harum!'

            }
        }
    }
</script>

<style lang="scss" scoped>

</style>