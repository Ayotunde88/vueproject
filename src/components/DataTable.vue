<template>
  <div id="dataTable">
    <div class="row">
        <div class="card">
            <h2>Appointment Activity</h2>
            <div class="card-body">
                <table class="">
                    
                    <thead>
                        <th>Name</th>
                        <th>Email</th>
                        <th>Date</th>
                        <th>Visit Time</th>
                        <th>CHWS</th>
                        <th>Plana</th>
                        <th></th>
                        <th></th>
                        <th></th>
                    </thead>
                    <tr>
                        <td><i class=""><img class="iconImg" src="../styles/catoonAvat.svg" alt="" width="30"></i> Mike Mosh</td>
                        <td>moash@gmail.com</td>
                        <td>20/03/2022</td>
                        <td>09:15-9:55am</td>
                        <td>Blessing Chidi</td>
                        <td>Family</td>
                        <td></td>
                        <td><i class=""><img class="iconImg" src="../styles/edit.svg" alt="" width="16"></i></td>
                        <td><i class=""><img class="iconImg" src="../styles/delete.svg" alt="" width="16"></i></td>
                        
                    </tr>
                    <tr>
                        <td><i class=""><img class="iconImg" src="../styles/catoonAvat.svg" alt="" width="30"></i> Mike Mosh</td>
                        <td>moash@gmail.com</td>
                        <td>20/03/2022</td>
                        <td>09:15-9:55am</td>
                        <td>Blessing Chidi</td>
                        <td>Family</td>
                        <td></td>
                        <td><i class=""><img class="iconImg" src="../styles/edit.svg" alt="" width="16"></i></td>
                        <td><i class=""><img class="iconImg" src="../styles/delete.svg" alt="" width="16"></i></td>
                        
                    </tr>
                    <tr>
                        <td><i class=""><img class="iconImg" src="../styles/catoonAvat.svg" alt="" width="30"></i> Mike Mosh</td>
                        <td>moash@gmail.com</td>
                        <td>20/03/2022</td>
                        <td>09:15-9:55am</td>
                        <td>Blessing Chidi</td>
                        <td>Family</td>
                        <td></td>
                        <td><i class=""><img class="iconImg" src="../styles/edit.svg" alt="" width="16"></i></td>
                        <td><i class=""><img class="iconImg" src="../styles/delete.svg" alt="" width="16"></i></td>
                        
                    </tr>
                    <tr>
                        <td><i class=""><img class="iconImg" src="../styles/catoonAvat.svg" alt="" width="30"></i> Mike Mosh</td>
                        <td>moash@gmail.com</td>
                        <td>20/03/2022</td>
                        <td>09:15-9:55am</td>
                        <td>Blessing Chidi</td>
                        <td>Family</td>
                        <td></td>
                        <td><i class=""><img class="iconImg" src="../styles/edit.svg" alt="" width="16"></i></td>
                        <td><i class=""><img class="iconImg" src="../styles/delete.svg" alt="" width="16"></i></td>
                        
                    </tr>
                </table>
            </div>
        </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'StatComponent',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.row{
    padding: 0;
}
#dataTable{
  width: 100%;
  margin: 0 auto;
  margin-top: 25px;
  margin-left:0;
}
#dataTable .card{
  width: 90%;
  margin:0 auto;
  margin-left:30px;
  background: #FFFFFF;
  box-shadow: 0px 12px 26px rgba(16, 30, 115, 0.06);
  border-radius: 8px;
  border:none;
  height: 300px;
  padding: 0;
}
#dataTable .card h2{
  font-family: Lato;
    font-weight: 600;
    font-size: 20px;
    line-height: 26px;
    letter-spacing: 0.2px;
    color: #25282B;
    margin-left: 10px;
    margin-top: 20px;
}
#dataTable .card .card-body{
  width: 100%;
  padding:0;
}
#dataTable .card .card-body table{
  width:100%;
  margin-top: 10px;
}
#dataTable .card .card-body table tr td{
  padding: 5px;
  border-bottom: 1px solid #E8E8E8;
}
#dataTable .card .card-body table thead{
  width:100%;
  margin: 0 auto;
  background: #f5f5f5;
  padding: 40px;
  padding-right: 60px;
}
#dataTable .card .card-body table thead th{
  font-family: Lato;
  margin: 0 auto;
font-style: normal;
font-weight: bold;
font-size: 14px;
line-height: 20px;
letter-spacing: 0.1px;
color: #25282B;
padding: 10px;
}

</style>
