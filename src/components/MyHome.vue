<!-- eslint-disable vue/valid-template-root -->
<template>
    <!-- <img src="Vue Logo" alt="./assets/logo.png">
    <HomeWorld></HomeWorld> -->

    <h1>{{ msg }}</h1>
    <h2>Hello My Friend</h2>

</template>
<script>
export default {
    name: 'MyHome',
    props: {
        msg: String
    }

}
</script>