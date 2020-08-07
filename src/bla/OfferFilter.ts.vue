<template>
  <div>foo bar</div>
</template>

<script lang="ts">
import { Vue } from 'vue-property-decorator';

export default class OfferFilter extends Vue {
    readonly moo: MyOffer[];

    constructor() {
      super();
      this.moo = [];
    }
}
</script>
