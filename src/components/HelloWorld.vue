<template>
  <!-- Template-Idee: https://startbootstrap.com/template-overviews/landing-page/ !-->
  <div class="hello">

    <div class="img-container">
      <img src="../assets/dublin-2344423_1920.jpg" width="100%;" style="height: 100%;width: 100%;">
      <div class="centered">
        <h1>Tageso</h1>
        <h4>Die Tagesordnung <br>und Protokoll-Verwaltung</h4>
      </div>
      <div class="centered-bottom">
        <a href="https://app.tageso.de/#/login" class="btn btn-success">Login</a>
        <a href="https://app.tageso.de/#/register" class="btn btn-secondary">Register</a>
      </div>
    </div>
    <div class="tbox">
      <div class="row">
        <div class="col-md-6">
          <div class="con">
            <h1>Agenda</h1>
            <p>
              Lege für ein Organisation eine fortlaufende Agenda an. Offene punkte bleiben solange in dieser Agenda bis diese geschlossen wurden.
              Durch die Agenda wird kein Agendapunkt beim nächsten Treffen vergessen.
            </p>
            <p>
              Die Verwaltung der Organisation sowie der Agenda kann direkt online über die WebApp erfolgen.
            </p>
            <p>
              Für jede Organisation gibt es eine Nutzerverwaltung so das du öffentliche Agendas anlegen kannst.
              Alternativ kannst du eine private Organisation anlegen und einzelnde Nutzer die rechte zum lesen, bearbeiten und protokollieren geben.
            </p>
          </div>
        </div>
        <div class="col-md-6 d-none d-md-block d-lg-block d-xl-block" style="background-color: #CCFFAF;">
          <img src="../assets/checklist-2023731_1280.png" class="" width="100%" style="height: 100%;width: 100%;">
        </div>
      </div>
    </div>
    <div class="tbox">
      <div class="row">
        <div class="col-md-6 d-none d-md-block d-lg-block d-xl-block" style="">
          <img src="../assets/papers-3819540_cut.jpg" width="100%" style="height: 100%;width: 100%;">
        </div>
        <div class="col-md-6">
          <div class="con">
            <h1>Protokol</h1>
            <p>
              Zu jeder Organisation/Agenda können belibig viele Protokolle erzeugt werden. Hierbei kann zu jedem Agenda-Punkt ein Protokoll eintrag erzeugt werden.
            </p>
            <p>
              Die Ansicht der Protkolle kann pro Teffen erfolgen. Jedoch ist es auch möglich zu einem Agenda-Punkt alle Protokoll-Einträge aus der Vergangenheit anzuzeigen um so einen verlauf zu sehen.
            </p>
            <p>
              Die Protokolle können auch als PDF oder für Office exportiert werden. Bei neuen Protkollen kann auf wunsch auch eine E-Mail benachrichtigung erfolgen.
            </p>
          </div>
        </div>
      </div>
    </div>
    <div class="tbox">
      <div class="row">
        <div class="col-md-6">
          <div class="con">
            <h1>Stukturierte Daten und Schnitstellen</h1>
            <p>
              Da die Daten in eine Stukturierten Form (pro Agenda Item) erfasst werden können diese auch in der selben Stuktur ausgegeben und verwertet werden.
            </p>
            <p>
              Die Daten können über eine Dokumentierte Schnitstelle von anderen Programmen genutzt und weiter verarbeitet werden. Außerdem können diese im Maschienenlesbarer-form archivier werden.
            </p>
          </div>
        </div>
        <div class="col-md-6 d-none d-md-block d-lg-block d-xl-block" style="">
          <img src="../assets/programming-1857236_cut.jpg" width="100%" style="height: 100%;width: 100%;">
        </div>
      </div>
    </div>

  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  @media (max-width: 992px) {
    .con h1 {
      margin-bottom: 20px;
      margin-top: 40px;
    }
    .centered {
      position: absolute;
      top: 30%;
      left: 50%;
      transform: translate(-50%, -50%);
    }
    .centered-bottom {
      position: absolute;
      bottom: 0%;
      left: 50%;
      transform: translate(-50%, -50%);
    }

  }
  @media (min-width: 992px) {
    .con {
      margin-left: 100px;
      margin-right: 100px;
      margin-top:120px;
    }
    .con h1 {
      margin-bottom: 60px;
    }
    .col-md-6 {
      padding: 0px;
      margin: 0px;
    }
    .centered {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
    }
    .centered-bottom {
      position: absolute;
      bottom: 15%;
      left: 50%;
      transform: translate(-50%, -50%);
    }

  }
  .con {
    top: 100px;
    line-height: 2;
  }

  .row {
    width: 100%;
    margin: 0px;
    padding: 0px;
  }
  .img-container {
    position: relative;
    text-align: center;
    color: white;
    height: calc(100vh - 90px);
    overflow: hidden;
  }
  .img-container h1 {
     color: #fff;
   }
  .img-container h4 {
    color: #fff;
  }


</style>
