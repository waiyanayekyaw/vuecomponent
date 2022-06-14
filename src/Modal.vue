<template>
  <div class="backdrop">
    <div class="modal">
        <h2>Login Successful</h2>
        <p>Welcome to our website.</p>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
    .backdrop{
        width: 100%;
        height: 100%;
        background-color: rgba(0, 0, 0, 0.5);

        position: fixed;
        top: 0;
    }

    .modal{
        width: 300px;
        height: 100px;
        background-color: seagreen;
        padding: 20px;
        margin: 20px auto;
    }
</style>