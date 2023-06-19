
<div class="card-display">
  <h1>Testimonios y reseñas</h1>
  <h1>Test other Pull Request</h1>
  <div class="cards">
  <div class="card-container">
    <Card padded>" Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae. "
      <br><br>Martha Stewart
     </Card>
  </div>

  <div class="card-container">
    <Card>
      <Content>" Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae. "
        <br> <br>Ariana Menage</Content>
    </Card>
  </div>

  <div class="card-container">
    <Card variant="outlined" padded>" Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae. "
      <br><br>Sean Carter</Card>
  </div>
</div>
</div>



<script lang="ts">
  import Card, { Content } from '@smui/card';
</script>

<style>

  .card-display{
    display: flex;
    flex-direction: column;
    text-align: center;
  
    margin: 20px;
  }

  .cards{
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
  }
  .card-container{
    width: 250px;
border: solid grey 1px;
  }
</style>


