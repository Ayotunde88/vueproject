<template>
  <div id="startCard">
    <div class="row">
        <div class="card" style="">
        <img src="" class="card-img-top" alt="">
        <div class="card-body">
          <table>
            <tr>
              <td><div class="cardIcon"><h2>$112,174</h2></div></td>
              <td><div class="cardIcon"><h1>Income in current month</h1></div></td>
            </tr>
            <div class="realStat">
                <line-chart :data="{'2021-01-01': 11, '2021-01-02': 6}"></line-chart>
            </div>
          </table>
        </div>
      </div>
      <div class="card" style="">
        <img src="" class="card-img-top" alt="">
        <div class="card-body">
          <table>
            <tr>
              <td><div class="cardIcon"><h2>5,210</h2></div></td>
              <td><div class="cardIcon"><h1>Total Number of Appointments</h1></div></td>
            </tr>
          </table>
          <div class="incomeChart">
              
          </div>
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
#startCard{
  width: 100%;
  margin: 0 auto;
  margin-top: 25px;
  margin-left:0;
}
#startCard .card{
  width: 43%;
  margin:0 auto;
  margin-left:15px;
  background: #FFFFFF;
  box-shadow: 0px 12px 26px rgba(16, 30, 115, 0.06);
  border-radius: 8px;
  border:none;
  height: 300px;
}
#startCard .card .card-body table tr td h1{
  float: right;
  font-family: Lato;
font-style: normal;
font-weight: bold;
font-size: 12px;
line-height: 16px;
/* identical to box height, or 133% */

text-align: right;
letter-spacing: 0.1px;
color: #A0A4A8;
/* Neutral / Gray */


}

#startCard .card .card-body{
  width: 100%;
}
#startCard .card .card-body h2{
  font-family: Lato;
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 26px;
    /* identical to box height, or 130% */

    letter-spacing: 0.2px;

    /* Neutral / Black */

    color: #25282B;
}
#startCard .card .card-body table{
  width: 100%;
}

</style>
