<template>
    <div>
        <p>This an product details of {{ id }}</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit distinctio earum cupiditate vitae similique pariatur natus laborum hic nam tenetur, iste quo reiciendis. Dolores harum corporis magnam officia perspiciatis quasi?  
        </p>
    </div>
</template>
<script setup>
    const {id}=useRoute().params
</script>
<style>
    
</style>