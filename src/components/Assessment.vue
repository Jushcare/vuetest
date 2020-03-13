<template>

<div id="content" class="p-4">

  <div class="container-fluid">
    <div class="row">
      <div class="">Dashboard</div>
  </div>
    <div class="row">
      <div class="col-md-6 col-xs-12">
        <div class="caption"> Application Pending Assessment</div>
      <div class="table-responsive">
        <table class="table table-striped table-bordered">
          <thead class="indigo text-white" id="userTable">
            <tr>
              <th>SN</th>
              <th>Name</th>
              <th>Phone</th>
              <th>Rank</th>
              <th>Action</th>
            </tr>
          </thead>
          <tbody>
          <tr v-for="data in userDatas" :key="data.id">
            <td>{{data.id}}</td>
            <td>Johnson Johnson</td>
            <td>0123456789</td>
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

var userTable = new Vue({
  el: '#userTable',
  data: {
    userDatas: [
      { id: 1, name: "Samuel Smith", phone: '3059171301', rank: 'IT Manager' },
      { id: 2, name: "Rose John", phone: '2106848953', rank: 'Paleontologist' },
      { id: 3, name: "Rachel Smith", phone: '7653380312', rank: 'Dev'},
      { id: 4, name: "Monica Geller", phone: '7145413336', rank: 'Head Tech' },
      { id: 5, name: "Joey Tribbiani", phone: '9722976037', rank: 'SV' },
      { id: 6, name: "Bobby Buffay", phone: '7603188376', rank: 'SUE' }
    ]
  }
});
</script>
