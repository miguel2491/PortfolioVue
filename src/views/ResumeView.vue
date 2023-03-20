<script setup>
import TimeLine from '../components/TimeLine.vue'
</script>

<template>
    <div class="row d_resumen">
        <hr>
        <div class="row">
            <h2>Resume</h2>
            <label class="lbl_exp">8 Years of Experience</label>
        </div>
        <hr>
        <div class="row">
            <TimeLine />
        </div>
    </div>
    
</template>
<style>
    .d_resumen{
        color:white;
    }
    .d_resumen h2{
        margin-top: 2%;
        margin-left: 5%;
        font-weight: bold;
        font-size: 42px;
    }
    .lbl_exp{
        margin: 5px 0 0 60%;
        position: absolute;
    }
</style>