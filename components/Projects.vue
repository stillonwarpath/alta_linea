<template>
    <section class="container is-fullhd">
        <h2 class="title is-2">
            Proyectos
        </h2>
        <div class="columns is-multiline">
            <div class="column is-half-desktop">
                <!--TODO: Add image ratio -->
                <b-image
                    src="https://picsum.photos/id/358/314"
                    alt="Project image">
                </b-image>
                <h6 class="subtitle is-6">
                    Proyecto 1
                </h6>
                <h5 class="subtitle is-5">
                    Breve descripción
                </h5>
            </div>
            <div class="column is-half-desktop">
                Proyecto 2
            </div>
            <div class="column is-half-desktop">
                Proyecto 3
            </div>
            <div class="column is-half-desktop">
                Proyecto 4
            </div>
        </div>
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