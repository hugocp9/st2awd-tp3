<template>
    <div>
        <h1>{{fakehomelink}}</h1>
        <h1>{{logininfo}}</h1>
    </div>
</template>

<script>

export default {

    name: 'header',
    data: function () {
        return {
            fakehomelink : 'Fake Home Link',
            logininfo : 'Not Yet Logged In'

        }
    }
}

</script>

<style scoped>

</style>