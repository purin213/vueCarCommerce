<script setup>
import {computed} from 'vue'
defineProps(['carView', 'carImg', 'carName', 'carMaker', 'carPrice','carDate'])
</script>
<template>
    <div class="d-flex col-md-4 col-12 flex-wrap pt-4 text-secondary">
        <div class="card m-2" style="width: 18rem;">
            <div class="card-body">
                <img v-bind:src="carImg" class="card-img-top" alt="...">
                <h5 class="card-title pt-2">{{carName}}</h5>
                <p class="card-text">Maker: {{carMaker}}</p>
                <p class="card-text">Price: ${{carPrice}}</p>
                <p class="card-text">Date: {{carDate}}</p>
            </div>
        </div>
    </div>
</template>