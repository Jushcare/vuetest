<template>

<div id="content" class="p-4">

  <div class="container-fluid">
    <div class="row">
      <div class="">Dashboard</div>
  </div>
    <div class="row">
      <div class="col-md-6 col-xs-12" id="userTable">
        <div class="caption"> Application Pending Assessment</div>
      <div class="table-responsive">
        <table class="table table-striped table-bordered">
          <thead class="indigo text-white">
            <tr>
              <th>SN</th>
              <th>Name</th>
              <th>Phone</th>
              <th>Action</th>
            </tr>
          </thead>
          <tbody>
          <tr>
            <td>1</td>
            <td>Johnson Johnson</td>
            <td>0123456789</td>
      <td><a href="#" class="btn btn-info"> Process </a></td>
          </tr>
          <tr>
            <td>1</td>
            <td>Johnson Johnson</td>
            <td>0123456789</td>
      <td><a href="#" class="btn btn-info"> Process </a></td>
          </tr>
          </tbody>
        </table>
      </div>
      </div>


<div class="col-md-6 col-xs-12">
    <div class="table-caption"> Application Processed</div>
      <div class="table-responsive">
      <table class="table table-striped table-bordered">
      <thead class="indigo text-white">
        <tr>
          <th>SN</th>
          <th>Name</th>
          <th>Phone</th>
          <th>Action</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>1</td>
          <td>Johnson Johnson</td>
          <td>0123456789</td>
    <td><a href="#" class="btn btn-info"> Processed </a> <a href="#" class="btn btn-primary"> View </a></td>
        </tr>
      </tbody>
      </table>
      </div>
   </div>

</div>
</div>


</div>

</template>

<script>
//import VueRouter from 'vue-router';
//const route = new VueRouter;
//export default {
//  name: 'assessment',
//  data() {
  //  return {
  //    userDatas: [
//        { id: 1, name: "Johnson Johnson", phone: '0123456789' },
  //      { id: 2, name: "Johnson Johnson2", phone: '0123456789' },
  //      { id: 3, name: "Johnson Johnson3", phone: '0123456789'},
  //    ]
//  },

//  methods : {
//    processData() {
//      route.push('process');
//    }
//  },

//}
</script>
