<template>
    <section class="container is-full-hd services">
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

    .services {
        margin-top: 4rem;
        padding-left: 1rem;
        padding-right: 1rem;
    }

    @include desktop {
        .web-app {
            flex-direction: row-reverse;
        }
    }
</style>