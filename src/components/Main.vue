
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
    <div class="d-flex justify-content-center py-5">
        <div style="max-width: 75rem;">
            <h3>Hi, My name is</h3>
            <h1 class="font_size_big">Maurizio Gallotti</h1>
            <h2>"I'm a Junior Web Developer with a passion for continuous learning and a strong desire to constantly challenge myself. I am determined to enhance my skills and actively contribute to exciting projects, offering creative and innovative solutions."</h2>
        </div>
    </div>
    <Projects/>
    <Resume/>
   

</template>

<style lang="scss" scoped>
h1 {
    color:#ccd8f8;

    span {
        color: blue;
    }
}

h2 {
  color:#8892b0 ;  
}

h3{
    color: #50c8b0;
}

.font_size_big{
    font-size: 86px;
}

</style>