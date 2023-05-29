<template>
  <div>
    <button @click="openModal">button</button>
  </div>
</template>

<script setup>
import { useModal } from 'vue-js-modal'


const { showModal } = useModal()

function openModal() {
  showModal('my-modal')
}

</script>
