<template>
  <div class="row">
    <div class="col-md-12">
      <div class="panel panel-danger">
        <div class="panel-heading">
          <input type="text" v-model="name"> <i class="glyphicon glyphicon-floppy-disk"></i> <i class="glyphicon glyphicon-trash"></i>
        </div>
        <div class="panel-body col-md-8" promotion_id="1">
          <input placeholder="Prénom" type="text"  value="Myriam">
          <input placeholder="Nom" type="text"  value="Pennequin">
          <i class="glyphicon glyphicon-floppy-disk"></i> <i class="glyphicon glyphicon-trash"></i>
        </div>
        <div class="panel-body col-md-8" promotion_id="1">
          <input placeholder="Prénom" type="text" value="Alexandre">
          <input placeholder="Nom" type="text" value="Mahieu">
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
        name: 'promotion',
        props: ['name']
        }
</script>