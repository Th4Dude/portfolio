
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
            <h3>Hi, My name is</h3>
            <h1>Maurizio Gallotti</h1>
            <h3>"I'm a Junior Web Developer with a passion for continuous learning and a strong desire to constantly challenge myself. I am determined to enhance my skills and actively contribute to exciting projects, offering creative and innovative solutions."</h3>
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