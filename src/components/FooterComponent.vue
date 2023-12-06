<script>
export default {
    name: 'FooterComponent',
    data() {
        return {
            endMessage: 'Made with love by Alex',
        }
    }
}
</script>
<template>
    <h4>{{ endMessage }}</h4>
</template>
<style>
h4 {
    margin-top: 800px;

}
</style>