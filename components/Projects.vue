<template>
    <section class="container is-fullhd">
        <h2 class="title is-2">
            Proyectos
        </h2>
    </section>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
    @import '~bulma/sass/utilities/mixins';

    @include mobile {
        section {
            margin-top: 6rem;
            padding-left: 1rem;
            padding-right: 1rem;
        }
    }

    @include desktop {
        section {
            margin-top: 7rem;
        }
    }


</style>