<template>
  <div class="col-md-5">
    <div class="card">
      <div class="card-header">
        <h3 class="card-title">Daftar Agenda</h3>
      </div>
      <div class="card-body">
        <div class="table-renponsive">
          <table class="table table-hover table-bordered">
            <thead>
              <tr>
                <th>#</th>
                <th>Hari</th>
                <th>Agenda</th>
                <th></th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <th scope="row">1</th>
                <td>Mark</td>
                <td>Otto</td>
                <td>@mdo</td>
              </tr>
              <tr>
                <th scope="row">2</th>
                <td>Jacob</td>
                <td>Thornton</td>
                <td>@fat</td>
              </tr>
              <tr>
                <th scope="row">3</th>
                <td colspan="2">Larry the Bird</td>
                <td>@twitter</td>
              </tr>
            </tbody>
          </table>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "AgendaShow",
};
</script>