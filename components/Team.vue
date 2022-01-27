<template>
    <div class="container is-fullhd">
        <h2 class="title is-2">
            Nosotros
        </h2>
        <div class="columns is-variable is-0-mobile">
            <TeamMember 
                v-for="teamMember in teamMembers"
                :key="teamMember.id"
                :teamMember="teamMember"
            />
        </div> 
    </div>
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

    @include touch {
        .container {
            margin-top: 6rem;
            padding-left: 1rem;
            padding-right: 1rem;
        }
    }

    @include desktop {
        .container {
            margin-top: 7rem;
            padding-left: 4rem;
            padding-right: 4rem;
        }
        .columns {
            margin-top: 4rem;
        }
    }
</style>