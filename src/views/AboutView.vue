<template>
  <div>
    <div class="greenbox">
      <div class="redbox">
      </div>
    </div>
    <div class="box"></div>
  
    <div class="Routine">
      <h1>Time Table</h1>
      <table border="1px solid red">
        <tr class="row">
          <th>Day/Period</th>
          <th>I <br> 9:30-10:20</th>
          <th>II <br> 10:20-11:10</th>
          <th>III <br> 11:10-12:00</th>
          <th> <br> 12:00-12:40</th>
          <th>IV<br> 12:40-1:30</th>
          <th>V <br> 1:30-2:20</th>
          <th>VI<br> 2:20-3:10</th>
          <th>VII <br> 3:10-4:00</th>
        </tr>
        <tr>
          <td><b>Monday</b></td>
          <td>Eng</td>
          <td>Mat</td>
          <td> Che</td>
          <td rowspan="6"><b>L<br>U<br>N<br>C<br>H</b></td>
          <td colspan="3">LAB</td>
          <td>Phy</td>
        </tr>
        <tr>
          <td><b>Tuesday</b></td>
          <td colspan="3">LAB</td>
          <td> Eng</td>
          <td>Che</td>
          <td>Mat</td>
          <td>SPORTS</td>
        </tr>
        <tr>
          <td><b>Wednesday</b></td>
          <td>Mat</td>
          <td>Phy</td>
          <td>Eng</td>
          <td> Che</td>
          <td colspan="3">LIBRARY</td>
        </tr>
        <tr>
          <td><b>Thursday</b></td>
          <td>Phy</td>
          <td>Eng</td>
          <td> Che</td>
          <td colspan="3">LAB</td>
          <td>Mat</td>
        </tr>

        <tr>
          <td><b>Friday</b></td>
          <td colspan="3">LAB</td>
          <td>Mat</td>
          <td> Che</td>
          <td>Eng</td>
          <td>Phy</td>
        </tr>
        <tr>
          <td><b>Saturday</b></td>
          <td>Eng</td>
          <td> Che</td>
          <td>Mat</td>
          <td colspan="3">SEMINAR</td>
          <td>SPORTS</td>
        </tr>
      </table>
    </div>
</div>

</template>
<style>
  table{
    height: auto;
    width: 80%;
    border-collapse: collapse;
    margin: 0% 10% 10%; 
    border: 3px solid black;
  }
  table td{
    width: 8%;
    height: 30px;
  }
  table th, td{
    border: 2px solid black;

  }


.row{
  width: 8%;
    height: 30px;
    padding: 5px;
}


  .box{
    height: 20%;
    width: 20%;
    background: blue;
    position:absolute;
    top: 0;
    bottom: 0;
    right: 0;
    left:0;
    margin:auto;
    transform: translate(150px, -70px);
  }
.box:hover{
  height: 30%;
  width: 30%;
  transition: 2s;
  transition-delay: 1s;
  transform: rotate(180deg);
  transform: translate(150px, -70px);
}
.greenbox{
  height:300px;
  width: 500px;
  background: green;
  position:relative;
  top: 0;
  bottom: 0;
  left:0;

}
.redbox{
  height: 180px;
  width: 180px;
  background: red;
  position: absolute;
  top:0;
  bottom:0;
  left:0;
  right:0;
  margin:auto;
  border-radius: 90px;
}



</style>
