<template>
  <div>
    <Modal></Modal>
  </div>
</template>

<script>
import { defineComponent } from 'vue';
import Modal from '@/components/Modal.vue';

export default defineComponent({
  name: 'App',
  components: {
    Modal,
  },
});
</script>
