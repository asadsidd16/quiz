<script setup>
    import { defineProps } from 'vue';

    const props = defineProps(['quiz'])
</script>

<template>
    <div class="card">
        <img src="http://jobs.newscientist.com/getasset/c40a5488-11be-43b0-843f-a2e6ef9f0612/" alt="pic">
        <div class="card-text">
            <h2>Math</h2>
            <p>3 questions</p>
        </div>
    </div>
</template>

<style scoped>
.card {
    width: 310px;
    overflow: hidden;
    border-radius: 2%;
    box-shadow: 1px 1px 10px rgba(0, 0, 0, 0.1);
    margin-bottom: 35px;
    margin-right: 20px;
    cursor: pointer;
  }
  
  .card img {
    width: 100%;
    height: 190px;
    margin: none;
  }
  
  .card .card-text {
    padding: 0 5px;
  }
  
  .card .card-text h2 {
    font-weight: bold;
  }
</style>