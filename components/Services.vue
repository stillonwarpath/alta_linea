<template>
    <section class="container is-fullhd services">
        <div class="columns">
            <div class="column">
                <h2 class="title is-2">
                    Apps mobile
                </h2>
                <h5 class="subtitle is-5">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorem suscipit, quo laborum fugiat repudiandae veritatis non! Eos aliquid quo beatae dicta facere voluptatibus suscipit quisquam natus mollitia possimus, culpa ratione?
                </h5>
            </div>
            <div class="column">
                <b-image
                    src="https://picsum.photos/id/358/500"
                    alt="Imagen desarrollo móvil">
                </b-image>
            </div>
        </div>
        <div class="columns web-app">
            <div class="column">
            <h2 class="title is-2">
                Apps web
            </h2>
            <h5 class="subtitle is-5">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorem suscipit, quo laborum fugiat repudiandae veritatis non! Eos aliquid quo beatae dicta facere voluptatibus suscipit quisquam natus mollitia possimus, culpa ratione?
            </h5>
            </div>
            <div class="column">
                <b-image
                    src="https://picsum.photos/id/358/314"
                    alt="Imagen desarrollo móvil">
                </b-image>
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
        .services {
            margin-top: 4rem;
        }
        .title, .subtitle {
            padding-left: 1rem;
            padding-right: 1rem;
        }

    }

    @include desktop {

        .services {
            margin-top: 6rem;
        }

        .web-app {
            flex-direction: row-reverse;
        }
    }
</style>