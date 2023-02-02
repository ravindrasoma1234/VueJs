<!-- eslint-disable vue/multi-word-component-names -->
<!-- eslint-disable vue/valid-template-root -->
<template>
    <div class="hello">

        <h1>{{ msg }}</h1>
    </div>
</template>

<script>
export default {
    name: 'helloWorld',
    props: {
        msg: String
    }
}
</script>