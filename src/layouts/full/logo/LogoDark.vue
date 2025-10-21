<script setup lang="ts">
import { RouterLink } from 'vue-router';
import logo from '@/assets/images/logos/SfondoBianco.svg';
</script>
<template>
    <div>
        <RouterLink to="/">
            <img class="logo" :src="logo" alt="logo" />
        </RouterLink>
    </div>
</template>

<style>
    .logo {
        max-height: 150px;
    }
</style>
