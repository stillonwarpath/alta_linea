<template>
    <div class="column is-half-desktop">
        <!--TODO: Add image ratio -->
        <b-image
            src="https://picsum.photos/id/358/314"
            alt="Project image">
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
        props:['project']
    }
</script>

<style lang="scss" scoped>

</style>