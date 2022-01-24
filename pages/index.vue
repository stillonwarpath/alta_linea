<template>
  <div class="container is-fullhd">
    <!--Hero-->
    <section>
      <div class="is-flex is-flex-direction-column is-align-items-center first-title">
        <h1 class="title is-1">
          Title 1
        </h1>
        <h3 class="subtitle is-3">
          Subtitle 3
        </h3>
      </div>
      <div class="is-flex is-flex-direction-column is-align-items-center second-title">
        <h2 class="title is-2">
          Title 2
        </h2>
        <h4 class="subtitle is-4">
          Subtitle 4
        </h4>
      </div>
    </section>
    <!--Services-->
    <section>
      <h2 class="title is-2">
        Apps mobile
      </h2>
      <h5 class="subtitle is-5">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorem suscipit, quo laborum fugiat repudiandae veritatis non! Eos aliquid quo beatae dicta facere voluptatibus suscipit quisquam natus mollitia possimus, culpa ratione?
      </h5>
    </section>
  </div>

</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage',
})
</script>
<style lang="scss" scoped>
  .first-title {
    margin-top: 4rem;
  }
  .second-title {
    margin-top: 6rem;
  }
</style>
