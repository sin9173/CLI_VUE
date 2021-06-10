<template>
    
    <div>
        <h1>{{ title }}</h1> <!-- PROPS 사용 -->
        <p>{{ name }}</p>
        <button @click="updateName">Click</button>
    </div>
</template>


<script>
export default {
    props : {
        title : {
            type: String,
            required: false,
            default : 'DEFAULT_TITLE'
        }
    }, //PROPS 받기
    data() {
        return {
            
            name : 'ko',
        }
    },

    methods : {
        updateName() {
            this.name = 'ko updated';
        }
    }
}
</script>


<style scoped>

</style>