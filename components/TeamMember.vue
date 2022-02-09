<template>
  <div class="column is-one-third">
    <b-image src="https://picsum.photos/id/358/314" alt="Team member image">
    </b-image>
    <h5 class="title is-5">
      {{ teamMember.name }}
    </h5>
  </div>
</template>

<script>
export default {
  props: ['teamMember'],
}
</script>

<style lang="scss" scoped>
@import '~bulma/sass/utilities/mixins';

.column {
  padding-top: 0;
  padding-bottom: 0;
}

@include touch {
  .column:first-child {
    margin-top: 4rem;
  }
  .column:not(:first-child) {
    margin-top: 3rem;
  }
}
</style>
