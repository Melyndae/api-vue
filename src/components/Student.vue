<template>
  <div class="row">
    <div class="col-md-12">
      <div class="panel panel-danger">
        <div class="panel-heading">
          <input type="text" v-model="name"> <i class="glyphicon glyphicon-floppy-disk"></i> <i class="glyphicon glyphicon-trash"></i>
        </div>
        <div class="panel-body col-md-8">
          <input type="text"  v-model="firstname">
          <input type="text"  v-model="lastname">
          <i class="glyphicon glyphicon-floppy-disk"></i> <i class="glyphicon glyphicon-trash"></i>
        </div>

      </div>
    </div>
  </div>
</template>

<style>
</style>

<script>
    export default {
        name: 'student',
        props: ['firstname', 'lastname']
        }
</script>