<template>
    <section class="container is-full-hd is-flex">
        <h2 class="title is-2">
            CTA 1
        </h2>
        <h5 class="subtitle is-5 has-text-centered-desktop">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Eligendi aliquam asperiores quis illo accusantium ipsam temporibus magni, libero dignissimos sint error nostrum soluta voluptas eos ea illum, consectetur placeat ullam!
        </h5>
        <b-button type="is-primary" rounded>
            Haz contacto
        </b-button>
    </section>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
    @import '~bulma/sass/utilities/mixins';

     section {
            flex-direction: column;
        }

    @include mobile {
        section {
            margin-top: 6rem;
            padding-left: 1rem;
            padding-right: 1rem;
        }
    }

 

    @include desktop {
        section {
            align-items: center;
            margin-top: 7rem;
        }
    }

</style>