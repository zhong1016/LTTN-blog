<script setup lang="ts"></script>
<template>
  <main>
    <ContentDoc v-slot="{ doc }">
      <h1>{{ doc.tags }}</h1>
      <ContentRenderer :value="doc" />
    </ContentDoc>
  </main>
</template>
