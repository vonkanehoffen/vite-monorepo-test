<script setup lang="ts">
import { SharedThing, Button, Header } from "@mw/mw-common";
</script>

<template>
  <main>
    <SharedThing />
    <Button :primary="true" label="Foo" />
    <Header />
  </main>
</template>
