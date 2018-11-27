<template>
  <div id="app">
    <b-navbar toggleable="md" type="dark" variant="info">

      <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>

      <b-navbar-brand href="#">Tageso</b-navbar-brand>


    </b-navbar>
    <router-view/>
    <div class="row footer">
      <div class="col-md-4">
        <div class="footer-content">
          <h6>Für Nutzer</h6>
          <ul>

          </ul>
        </div>
      </div>
      <div class="col-md-4">
        <div class="footer-content">
          <h6>Für Administratoren</h6>
          <ul>
            <li><a href="https://api.tageso.de/setup/">Tageso selber hosten</a></li>
          </ul>
        </div>
      </div>
      <div class="col-md-4">
        <div class="footer-content">
          <h6>Für Entwickler</h6>
          <ul>
            <li><a href="https://api.tageso.de/">API-Dokumentation</a></li>
            <li><a href="https://api.tageso.de/docs/">HTTP-Schnitstellen Dokumentation (Swagger)</a></li>
          </ul>
          <h6>Open Source</h6>
          <p>Teile dieses Projekts sind bereits als Open-Source auf Github veröffentlicht und können eingesehen, verwendet und angepasst werden</p>
          <a href="https://www.github.com/tageso">Zu Github</a>
        </div>

      </div>
    </div>
  </div>
</template>

<script>


export default {
  name: 'app',
  components: {

  }
}
</script>


<style scoped>
  .row {
    width: 100%;
    margin: 0px;
    padding: 0px;
  }
  .footer-content {
    margin-top: 30px;
    margin-bottom: 30px;
    color: #fff;
  }
  .footer-content h6 {
    color: #fff;
  }
  .footer-content a {
    text-decoration: underline;
    color: #fff;
  }
  .footer {
    background-color: #1F9BCF;
  }
</style>