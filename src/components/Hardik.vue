<template>

    <div class="row">
      <div class="col-md-3">{{ txt }}:</div>
      <div class="col-md-9">
        <input type="text" class="form-control" />
      </div>
    </div>
    <div class="mt-3"></div>
    <div class="row">
      <div class="col-md-3">{{ pwd }}:</div>
      <div class="col-md-9">
        <input type="password" class="form-control" />
      </div>
    </div>
     <div class="mt-3"></div>
    <input type="submit" class="btn btn-info" />
</template>

<script>
export default {
  name: "Hardik",
  props: {
    txt: String,
    pwd: String,
  },
};
</script>

<style>
</style>