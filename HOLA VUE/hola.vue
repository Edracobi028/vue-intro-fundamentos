<template>
    <div>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Omnis sequi at molestiae pariatur expedita debitis nesciunt facilis quas cum libero alias natus corrupti, eligendi quis autem quia ducimus eos repudiandae!</p>
        <div>{{ text }}</div>
    </div>
    

</template>
<script>
    export default{
        data(){
            return{
                text:"Hola!"
            }
        }
    };
</script>

<style>
    p {
        color: red;
    }
</style>