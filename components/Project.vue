<template>
  <div class="column is-half-desktop">
    <!--TODO: Add image ratio -->
    <b-image :src="project.image" alt="Project image" class="project-image">
    </b-image>
    <h6 class="subtitle is-6">
      {{ project.name }}
    </h6>
    <h5 class="subtitle is-5">
      {{ project.description }}
    </h5>
  </div>
</template>

<script>
export default {
  props: {
    project: any,
  },
}
</script>

<style lang="scss" scoped>
@import '~bulma/sass/utilities/mixins';

@include touch {
  .column:not(:first-child) {
    margin-top: 3rem;
  }
}

@include desktop {
}
</style>
