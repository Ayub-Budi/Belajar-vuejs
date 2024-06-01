<template>
    <div class="logos-wrapper">
        <h2 class="title-header">Find Best Logos</h2>
        <div class="item-logos">
            <img class="logo" alt="google" src="../assets/google.png">
        </div>

        <div class="item-logos">
            <img class="logo" alt="gmail" src="../assets/gmail.png">
        </div>

        <div class="item-logos">
            <img class="logo" alt="facebook" src="../assets/facebook.png">
        </div>
    </div>


</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: 'Logos'
}
</script>

<style scoped>

.title-header{
    margin-bottom: 80px;
}

.logos-wrapper{
    width: 70%;
    overflow: hidden;
    margin: auto;
}

.item-logos{
    float: left;
    margin-right: 20px;
    margin-bottom: 20px;
    width: 150px;
    height: 150px;
}

.item-logos .logo{
    width: 150px;
    height: 150px;
}

</style>