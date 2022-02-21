<template>
  <div id="rightDiv">
    <header>
      <nav>
        <ul>
          <table>
            <tr>
              <td>
                <li><div id="searchDiv">
                  <div class="searchMove">
                    <i class=""><img class="iconImg" src="../styles/searchicon.svg" alt="" width="20"></i><input type="text" id="search" placeholder="Search">
                  </div>
                  </div>
                </li>
              </td>
              <td>
                <li class="notyfyList">
                  <div id="notify">
                    <i><a class="notifications">9</a><img class="iconImg" src="../styles/notify.svg" alt="" width="70"></i><img src="../styles/avatar.jpg" alt="" >
                  </div>
                </li>
              </td>
            </tr>
          </table>
        </ul>
      </nav>
    </header>
    <CardContent/>
    <StatComponent/>
    <DataTable/>
  </div>
</template>

<script>
import StatComponent from './StatComponent.vue'
import DataTable from './DataTable.vue'
import CardContent from './CardContent.vue'

export default {
  name: 'RightComponent',
  components:{
    CardContent,
    StatComponent,
    DataTable
  },
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  #rightDiv{
    width: 100%;
    height: 100%;
    top: 0;
  }
  #rightDiv header{
    margin: 0 auto;
    margin-top: 15px;
    
  }
  #rightDiv li{
    list-style-type: none;
  }
ul table{
  border-collapse: collapse;
  border: none;
  width: 100%;
}

.notyfyList #notify i{
 color: #e0e0e0;
 font-size: 15px;
 margin-top: -10px;
 margin-right: 10px;
 
}
.notyfyList #notify .notifications{
 position:relative;
 top: -20px;
 background: #FF6760;
 border-radius: 50%;
 padding-top:3px;
 padding-bottom:3px;
 padding-left:6px;
 padding-right:6px;
 font-style: normal;
 color:#fff;
 width: 100%;
 position: relative;
 left: 35px;
 top: -7px;
 font-weight: 400;
 font-size: 10px;
 font-family: lato;
 text-decoration: none;

}
.notyfyList #notify .iconImg{
  background: none;
  width: 25px;
  margin-right: 6px;
}
.notyfyList #notify img{
  width: 40px;
  height: 40px;
  border-radius: 50%;
  background: #A0A4A8;
  padding: 3px;
}

nav{
  width: 100%;
  height: 88px;
  background: #F6F8FB;
}
#searchDiv{
  background: #ffffff;
  border-radius: 50px;
  border: none;
  width: 350px;
  padding: 10px;
  font-family: lato;
  font-weight: 400;
  color: #A0A4A8;
  font-size: 14px;
}
#searchDiv #search{
  border: none;
  margin: 0 auto;
  font-family: lato;
  font-weight: 400;
  color: #A0A4A8;
  font-size: 14px;
  margin-left: 10px;
  width: 80%;
}
#searchDiv i{
  color: #A0A4A8;
  font-size: 14px;
  margin-left: 5px;

}
#searchDiv i img{
  float: left;
}
</style>
