<template>
<div>
    <Dashboard/>
</div>
</template>

<script>
import { Options, Vue } from 'vue-class-component';
import Dashboard from '@/components/Dashboard.vue'; // @ is an alias to /src

@Options({
  components: {
    Dashboard,
  },
})
export default class Products extends Vue {}
</script>

<style>
</style>