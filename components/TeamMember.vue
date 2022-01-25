<template>
    <div class="column">
        <b-image
            src="https://picsum.photos/id/358/314"
            alt="Team member image">
        </b-image>
        <h5 class="title is-5">
            {{ teamMember.name }}
        </h5>
    </div>
</template>

<script>
    export default {
        props:['teamMember']
    }
</script>

<style lang="scss" scoped>

</style>