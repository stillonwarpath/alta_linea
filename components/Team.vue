<template>
    <section class="container is-fullhd">
        <h2 class="title is-2">
            Nosotros
        </h2>
        <div class="columns">
            <TeamMember 
                v-for="teamMember in teamMembers"
                :key="teamMember.id"
                :teamMember="teamMember"
            />
        </div> 
    </section>
</template>

<script>
    export default {
        data() {
            return {
                teamMembers: [
                    {
                        id: 1,
                        name: 'Integrante 1',
                        image: 'https://picsum.photos/id/358/314'
                    },
                    {
                        id: 2,
                        name: 'Integrante 2',
                        image: 'https://picsum.photos/id/358/314'
                    },
                    {
                        id: 3,
                        name: 'Integrante 3',
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