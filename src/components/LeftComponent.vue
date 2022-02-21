<template>
    <div id="sideMenu">
        <h1><i class=""><img class="iconImg" src="../styles/long.svg" alt="" width="150"></i></h1>
        <div class="links">
            <li><a class="active" href=""><i class=""><img class="iconImg" src="../styles/piechart.svg" alt="" width="15"></i> Dashboard</a></li>
            <li><a href=""><i class=""><img class="iconImg" src="../styles/appointmenticon.svg" alt="" width="15"></i> Appointments</a></li>
            <li><a href=""><i class=""><img class="iconImg" src="../styles/staff.svg" alt="" width="15"></i> Health Workers</a></li>
            <li><a href=""><i class=""><img class="iconImg" src="../styles/departments.svg" alt="" width="15"></i> Departments</a></li>
            <li><a href=""><i class=""><img class="iconImg" src="../styles/patient.svg" alt="" width="15"></i> Patients</a></li>
            <li><a href=""><i class=""><img class="iconImg" src="../styles/creditcard.svg" alt="" width="15"></i> Payments</a></li>
            <li class="help"><i class=""><img class="iconImg" src="../styles/questionmark.svg" alt="" width="15"></i> <a href="">Help</a></li>
        </div>
    </div>
</template>

<script>
export default {
  name: 'LeftComponent',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    #sideMenu{
        background: #fff;
        /* float: left; */
        width: 100%;
        height: 100vh;
        padding: 10px;
    }
    #sideMenu .links{
        list-style: none;
        margin: 0 auto;
        margin-top: 20px;
        width: 100%;
    }
    #sideMenu .links li{
        list-style: none;
        margin: 0 auto;
        padding: 10px;
    }
    #sideMenu .links li.help{
        margin-top: 10px;
        padding-top: 20px;
        border-top: 1px solid #E8E8E8;
    }
    #sideMenu .links li a{
        text-decoration: none;
        font-family: Lato;
        font-style: normal;
        font-weight: bold;
        font-size: 14px;
        line-height: 20px;
        /* identical to box height, or 143% */

        letter-spacing: 0.1px;

        /* Neutral / Gray dark */

        color: #52575C;
    }
    #sideMenu .links li a i{
        padding-right: 10px;
        
    }
    #sideMenu .links li a.active{
        font-family: Lato;
        font-style: normal;
        font-weight: bold;
        font-size: 14px;
        line-height: 20px;
        /* identical to box height, or 143% */
        letter-spacing: 0.1px;
        color: #0A459F;
    }
    #sideMenu h1{
        text-align: center;
        margin: 0 auto;
        font-size: 32px;
        margin-top: 10px;
        color: #31517A;
        font-weight: 800;
        font-family: lato;
    }
</style>
