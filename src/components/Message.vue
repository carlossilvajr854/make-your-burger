<template>
    <div class="message-container">
        <p>{{ msg }}</p>
    </div>
</template>

<script>
    export default {
        name: "Message",
        props: {
            msg: String,
        },
    };
</script>

<style scoped>
    .message-container {
        color: #146c43;
        background-color: #d1e7dd;
        border: 2px solid #a3cfbb;
        border-radius: 5px;
        padding: 10px;
        max-width: 400px;
        margin: 30px auto;
    }
</style>
