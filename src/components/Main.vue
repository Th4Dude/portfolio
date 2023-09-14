
<script>
import Projects from './Projects.vue';
import Resume from './Resume.vue';
export default {
    name: 'Main',
    components : {
       Projects,
       Resume
    }
}
</script>

<template>
    <div class="d-flex justify-content-center">
        <div style="max-width: 75rem;">
            <h3>Prova</h3>
            <h1>Maurizio Gallotti</h1>
            <h3>Lorem ipsum dolor, siesse ipsa ipsum delectus, ducimus ratione temporibus animi dolor quidem tempore magni
                cupiditate inventore eius dolorum aperiam unde ullam.</h3>
        </div>
    </div>
    <Projects/>
    <Resume/>
   

</template>

<style lang="scss" scoped>
h1 {
    color: red;

    span {
        color: blue;
    }
}
</style>