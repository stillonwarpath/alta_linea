<template>
    <div class="container is-fullhd">
        <h2 class="title is-2">
            Proyectos
        </h2>
        <div class="columns is-gapless is-multiline">
            <Project
                v-for="project in projects"
                :key="project.id"
                :project="project"         
             />
        </div>
    </div>
</template>

<script>

    export default {
        data() {
            return {
                projects: [
                    {
                        id: 1,
                        name: 'Proyecto 1',
                        description: 'Breve descripción',
                        image: 'https://picsum.photos/id/358/314'
                    },
                    {
                        id: 2,
                        name: 'Proyecto 2',
                        description: 'Breve descripción',
                        image: 'https://picsum.photos/id/358/314'
                    },
                    {
                        id: 3,
                        name: 'Proyecto 3',
                        description: 'Breve descripción',
                        image: 'https://picsum.photos/id/358/314'
                    },
                    {
                        id: 4,
                        name: 'Proyecto 4',
                        description: 'Breve descripción',
                        image: 'https://picsum.photos/id/358/314'
                    }
                ]
            }
        }
    }
</script>

<style lang="scss" scoped>
    @import '~bulma/sass/utilities/mixins';

    @include mobile {
        .container {
            margin-top: 6rem;
            padding-left: 1rem;
            padding-right: 1rem;
        }
    }

    @include desktop {
        .container {
            margin-top: 7rem;
        }
    }


</style>