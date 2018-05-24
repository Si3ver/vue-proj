<template>
  <li class="item" @click="handleDelete">{{content}}</li>
</template>

<script>
export default {
    props: ['content', 'index'],
    methods: {
        handleDelete () {
            this.$emit('delete', this.index)
        }
    }
}
</script>

<style scoped>
.item {
    color: red;
}
li {
  list-style-type: decimal;
}
li.complete {
  text-decoration: line-through;
}
</style>