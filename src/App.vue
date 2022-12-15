<template>
  <div class="container">
    <div class="row">
      <div class="col-4">
        <select class="form-control">
          <option>Universal Studios At Universal Orlando</option>
          <option>Universal Studios At Universal Orlando</option>
        </select>
      </div>
      <div class="col-4">
        <a class="btn btn-success">Change Park</a>
      </div>
    </div>
    <div class="row mt-4">
      <div class="col-2">
        <NavigationBar header="summary"/>
      </div>
      <div class="col-10">
        <div class="page-body">
          <div class="page-container">
            <div class="page-container-body">
              <div class="row">
                <div class="col-12">
                  <h3>Universal Studios At Universal Orlando</h3>
                  <h5>United States, North America</h5>
                </div>
              </div>
              <div class="row mt-4">
                <div class="col-6">
                  <ul class="stat-box list-group p-0">
                    <li class="list-group-item"><h5>Live Wait Times</h5></li>
                    <li class="list-group-item">Dapibus ac facilisis in</li>
                    <li class="list-group-item">Morbi leo risus</li>
                    <li class="list-group-item">Porta ac consectetur ac</li>
                    <li class="list-group-item">Vestibulum at eros</li>
                  </ul>
                </div>
                <div class="col-6">
                  <ul class="stat-box list-group p-0">
                    <li class="list-group-item"><h5>Live Wait Times</h5></li>
                    <li class="list-group-item">Dapibus ac facilisis in</li>
                    <li class="list-group-item">Morbi leo risus</li>
                    <li class="list-group-item">Porta ac consectetur ac</li>
                    <li class="list-group-item">Vestibulum at eros</li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import NavigationBar from './components/NavigationBar.vue'

export default {
  name: 'App',
  components: {
    NavigationBar
  }
}
</script>

<style>
@import 'bootstrap/dist/css/bootstrap.min.css';
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300;400&display=swap');
body {
  background: #f3f5fd !important;
  margin: 0;
  padding: 0;
  font-family: 'Open Sans', sans-serif;
}
.container{
  margin-top:50px;
}
.page-body{
  padding: 0 15px 0 15px;
}
.page-container{
  margin-bottom: 30px;
  border: none;
  -webkit-transition: all 0.3s ease;
  transition: all 0.3s ease;
  letter-spacing: 0.5px;
  border-radius: 15px;
  -webkit-box-shadow: 0px 4px 30px rgb(95 94 231 / 7%);
  box-shadow: 0px 4px 30px rgb(95 94 231 / 7%);

  position: relative;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  flex-direction: column;
  min-width: 0;
  word-wrap: break-word;
  background-color: #fff;
  background-clip: border-box;
}
.page-container-body{
  -webkit-box-flex: 1;
  -ms-flex: 1 1 auto;
  flex: 1 1 auto;
  padding: 1rem 1rem;
  padding: 30px;
  background-color: rgba(0,0,0,0);
}
.stat-box{
  border-radius: 5px;
  padding: 30px;
  margin-bottom: 30px;
  position: relative;
}
</style>
