<script setup lang="ts">
import { ref } from "vue"
const words = ref(['交通规划', '桥梁工程', '道路施工', '隧道建设', '交通监控',])
</script>
<template>
 <div class="text-gray-700 text-xs lg:text-sm">
    <span>热词：</span>
    <span 
        v-for="item in words" :key="item" class="mr-2">
        {{ item }}
    </span>
</div>   
</template>