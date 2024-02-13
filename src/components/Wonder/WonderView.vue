<template>
    <div class="container mt-4">
        <div class="row">
            <div class="col-md-3 mb-3" v-for="item in allWonders" :key="item.id">
                <div class="card shadow" style="height:18rem;">
                    <img :src="item.imageUrl" class="card-img-top" height="200px" alt="wonders">
                    <div class="card-body">
                        <h5 class="card-title">{{ item.name }}</h5>
                        <h5 class="card-title">{{ item.price }}</h5>
                        <p class="card-text">Location - {{ item.location }}</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>
import axios from 'axios'
import { onMounted,ref } from 'vue';

const allWonders = ref([]);

onMounted(() => {
    axios.get(`https://json-server-vue3-lm62.onrender.com/Thai_food`)
        .then((response) => {
            // console.log(response.data)
            allWonders.value = response.data
        })
})

</script>

<style lang="scss" scoped></style>