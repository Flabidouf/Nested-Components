<script setup>

import {useNumbersStore} from '../stores/numbers';
    
    const {numbers, filterNum} = useNumbersStore();

</script>      

<template>

    <div>

        <h1>Great GrandChild Component {{ filterNum(6) }}</h1>
       
    </div>

</template>