<template>
  <div id="infoCard">
    <div class="row">
        <div class="card" style="">
        <img src="" class="card-img-top" alt="">
        <div class="card-body">
          <table>
            <tr>
              <td><div class="cardIcon"> <i class=""><img class="iconImg" src="../styles/medicals.svg" alt="" width="30"></i></div></td>
              <td><div class="cardIcon">
                <h1>Appointment</h1>
                
                <h3>213</h3>
              </div></td>
            </tr>
          </table>
        </div>
      </div>
      <div class="card" style="">
        <img src="" class="card-img-top" alt="">
        <div class="card-body">
          <table>
            <tr>
              <td><div class="cardIcon"><i class=""><img class="iconImg" src="../styles/human.svg" alt="" width="20"></i></div></td>
              <td><div class="cardIcon">
                <h1>New Patient</h1>
     
                <h3>104</h3>
                </div></td>
            </tr>
          </table>
        </div>
      </div>
      <div class="card" style="">
          <img src="" class="card-img-top" alt="">
          <div class="card-body">
            <table>
              <tr>
                <td><div class="cardIcon"><i class=""><img class="iconImg" src="../styles/appointment.svg" alt="" width="30"></i></div></td>
                <td><div class="cardIcon">
                  <h1>Intervention</h1>
            
                  <h3>24</h3>
                  </div>
                  </td>
              </tr>
            </table>
          </div>
      </div>
      <div class="card" style="">
          <img src="" class="card-img-top" alt="">
          <div class="card-body">
            <table>
              <tr>
                <td><div class="cardIcon"><i class=""><img class="iconImg" src="../styles/bank.svg" alt="" width="30"></i></div></td>
                <td><div class="cardIcon">
                  <h1>Clafiya Earnings</h1>
           
                    <h3>$112,174</h3>
                  </div></td>
              </tr>
            </table>
          </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'CardContent',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#infoCard{
  width: 95%;
  margin-left:0;
}
#infoCard .card{
  border:none;
  background: #FFFFFF;
  margin: 0 auto;
  box-shadow: 0px 12px 26px rgba(16, 30, 115, 0.06);
  border-radius: 8px;
  width: 22%;
  height: 80px;
}
#infoCard .card .card-body table tr td h1{
  font-size: 14px;
  color: #31517A;
  font-family: lato;
  font-weight: 700;
}
#infoCard .card .card-body table tr td h3{
  font-size: 16px;
  color: #0A459F;
  font-family: lato;
  font-weight: 700;
}
#infoCard .card .card-body table tr td:nth-child(1){
  width:40%;
}
#infoCard .card .card-body table{
  width: 100%;
}
</style>
