<template>
  <div id="online-friends">
    <h2>Online Friends</h2>
    <div v-for="(friend, index) in friends" v-bind:key="index">
      <div v-if="friend.online">{{ friend.name }}</div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'OnlineFriends',
  props: ['friends'],
  data () {
    return {
    }
  }
}
</script>

<style>

</style>
