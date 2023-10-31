<template>
    <div>
        <h1>Job Details Page</h1>
        <p>The job ID is {{ id }}</p>
    </div>
</template>

<script>
export default {
    props: ['id'],
    // data() {
    //     return {
    //         id : this.$route.params.id //take the id from the url
    //     }
    // },
}
</script>

<style>

</style>