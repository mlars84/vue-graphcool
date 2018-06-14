<template>
  <div class="home">
    <LinkItem link="some link" />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import LinkItem from '@/components/LinkItem.vue';

@Component({
  components: {
    LinkItem,
  },
})
export default class Home extends Vue {}
</script>
