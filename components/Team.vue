<template>
    <section class="container is-fullhd">
        <h2 class="title is-2">
            Nosotros
        </h2>
        <div class="columns">
            <div class="column">
                <b-image
                    src="https://picsum.photos/id/358/314"
                    alt="Team member image">
                </b-image>
                <h5 class="title is-5">
                    Integrante 1
                </h5>
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