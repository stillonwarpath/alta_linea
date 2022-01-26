<template>
    <footer>
        
    </footer>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
    @import '~bulma/sass/utilities/mixins';

    
    footer {
        background-image: url("https://picsum.photos/500/844");
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
        height: 844px;
        width: 100%;
    }
    

    @include mobile {
        footer {
            margin-top: 6rem;
        }
    }

    @include desktop {
        footer {
            margin-top: 7rem;
        }
    }
</style>