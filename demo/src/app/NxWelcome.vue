<script setup lang="ts">
import {core} from '@core-main';
import {utils} from '@core-utils';
import { helloNPM } from "my-npm-package";
defineProps<{
  title: string;
}>();
</script>

<template>
  <div class="wrapper">
    <h1>Hello world!</h1>
    <p>{{ core() }}</p>
    <p>{{ utils() }}</p>
    <p>{{ helloNPM() }}</p>
  </div>
</template>
