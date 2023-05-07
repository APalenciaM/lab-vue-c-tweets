<script>
export default {
    props: [
        'userData'
    ]
}

</script>

<template>
    <div>
        <span class="user">
          <span class="name">{{userData.name}}</span>
          <span class="handle">{{userData.handle}}</span>
        </span>
    </div>
</template>



<style scoped>

</style>