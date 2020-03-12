<template>
  <div class="row">
    <div class="col-xs-12 col-sm-6">
      <ul class="list-group">
        <app-server class="list-group-item" v-for="index in 5">Server #{{ index }}</app-server>
      </ul>
    </div>
    <div class="col-xs-12 col-sm-6">
      <app-server-details></app-server-details>
    </div>
  </div>
</template>

<script>
  import Server from './Server.vue'
  import ServerDetails from './ServerDetails.vue'

  export default {
    components: {
      'app-server': Server,
      'app-server-details': ServerDetails
    }
  }
</script>