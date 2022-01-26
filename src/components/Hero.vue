<template>
    <div>
        <div class="jumbotron">
            <Title/>
        </div>
    </div>
</template>

<script>
import Title from './Title.vue';

export default {
  name: 'Hero',
  components: {
      Title,
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    .jumbotron {
        width: 100%;
        height: 400px;
        background-image: url(https://picsum.photos/1920/400);
        background-size:cover;
        background-repeat: no-repeat;
    }
</style>