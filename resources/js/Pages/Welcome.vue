<template>
    <h1>
        Hello World {{ name }}
    </h1>
</template>

<script lang="ts" setup>
import { PropType } from 'vue';

defineProps({
    name: String
})
</script>

<style>

</style>
