<script>
    export default{
        data(){
            return{
                jambotron: 'https://upload.wikimedia.org/wikipedia/commons/thumb/6/63/Marvel_Studios_logo.svg/2560px-Marvel_Studios_logo.svg.png',
            }
        }
    };
</script>
<template>
    <div class="jumbotron">
        <img :src="jambotron" alt="jambotron">
    </div>
</template>
<style scoped>
    .jumbotron{
        width: 100%;
        height: 31.25rem;
        background-color: #d40317;
    }
    img{
        width: 100%;
        height: 100%;
        object-fit: contain;
    }
</style>