<template>
  <div id= "Active Trips">
    <h2> Trip Info </h2>
    <table id = 'my-table'>
        <tr>
          <th>Trip Times</th>
          <th>Trip Locations</th>
          <th>Routes</th>
        </tr>
        <tr>
          <th class ="anim:id">TripID</th>
          <th class ="anim:starttime">StartTime</th>
          <th class ="anim:endtime">EndTime</th>
          <th class ="anim:startpoint">StartPoint</th>
          <th class ="anim:endpoint">EndPoint</th>
          <th class ="anim:tripnodes">TripNodes</th>
        </tr>
      <tbody>
        <tr>
            <td>1</td>
            <td>"11:43:00"</td>
            <td>"14:32:00"</td>
            <td>"Montreal"</td>
            <td>"Ottawa"</td>
        </tr>

        <tr>
            <td>2</td>
            <td>"09:00:00"</td>
            <td>"15:30:00"</td>
            <td>"Montreal"</td>
            <td>"Toronto"</td>
        </tr>
      </tbody>
    </table>
    <p>
    <span style="color:red">Error: Message text comes here</span>
    </p>
  </div>
</template>

<script>

</script>

<input id='inputFilter'>
<button id='filter'>filter</button>

<style>

  #h2 {
  font-weight: normal;
  font-size: 48px;

  }

  #th {
  font-weight: normal;
  font-size; 24px;
  display: -webkit-flex;
  height: 340px;
  -webkit-flex-wrap: wrap;
  flex-wrap: wrap;
  -webkit-flex-direction: column;
  flex-direction: column;
  -webkit-justify-content: space-between;
  justify-content: space-between;

  }

  #p {
  flex-wrap: wrap;
  }

  #initialview {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    color: #2c3e50;
    background: #494949;
  }

</style>
