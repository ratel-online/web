<template>
    <div class="login">
        <h1>This is {{ msg || 'undefined' }} page</h1>
    </div>
</template>
<script>
    export default {
        name: 'Login',
        data() {
            return {
                msg: 'Login'
            }
        }
    }
</script>