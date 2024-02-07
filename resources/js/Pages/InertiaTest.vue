<script setup>
import { Link } from '@inertiajs/inertia-vue3';
</script>

<template>
    Inertiaテストです<br>
    <a href="/">a tag経由</a><br>
    <Link href="/">Link経由</Link><br>
    <Link :href="route('inertia.index')">名前付きルート</Link><br>
    <Link :href="route('inertia.show', { id: 1 })">Route Parameter Test</Link>

</template>