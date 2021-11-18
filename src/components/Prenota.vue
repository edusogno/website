<template>
  <div class="container">
      <h2 class="prenotazioni-title">Prenotazione</h2>
      <div class="prenotazione-main my-3">Durante un’ora di lezione viene affrontato uno dei seguenti argomenti:</div>
      <div class="row row-cols-1 row-cols-md-2 g-2">
          <!-- box verde -->
          <!-- prima box -->
          <div class="col my-2">
              <div class="big-box p-3">
                  <h4 class="box-title p-1 text-center">🏫  Scelta università e pianificazione del percorso</h4>
                  <div class="box-main p-2 text-center">Valutiamo il tuo profilo e ti guidiamo nella scelta delle migliori università all’estero in base ai tuoi interessi di studio e alle tue preferenze geografiche.</div>

              </div>
          </div>
          <!-- seconda box -->
          <div class="col my-2">
              <div class="big-box p-3">
                  <h4 class="box-title p-1 text-center">📄 Struttura personal statement ed essays</h4>
                  <div class="box-main p-2 text-center">Strutturiamo la tua lettera di presentazione per vendere al meglio le tue esperienze tramite uno storytelling originale ed efficace ai fini dell’ammissione.</div>

              </div>
          </div>
          <!-- terza box -->
          <div class="col my-2">
              <div class="big-box p-3">
                  <h4 class="box-title p-1 text-center">📝 Revisione personal statement</h4>
                  <div class="box-main p-2 text-center">Correggiamo una lettera di presentazione da te prodotta e la potenziamo per renderla piu’ appealing agli occhi della admission committee.</div>

              </div>
          </div>
          <!-- quarta box -->
          <div class="col my-2">
              <div class="big-box p-3">
                  <h4 class="box-title p-1 text-center">📇 Ottimizzazione e potenziamento CV</h4>
                  <div class="box-main p-2 text-center">Analizziamo il tuo curriculum e ti aiutiamo a strutturarlo in modo chiaro ed efficace in inglese, fornendoti indicazioni su contenuto e formattazione. </div>

              </div>
          </div>
          <!-- quinta box -->
          <div class="col my-2">
              <div class="big-box p-3">
                  <h4 class="box-title p-1 text-center">⚡️ Simulazione colloquio</h4>
                  <div class="box-main p-2 text-center">Ti prepariamo al colloquio di ammissione tramite delle simulazioni con tutor madrelingua al fine di minimizzare l’effetto sorpresa e renderti pronto per un colloquio in inglese.</div>

              </div>
          </div>
          <!-- sesto box -->
          <div class="col my-2">
              <div class="big-box p-3">
                  <h4 class="box-title p-1 text-center">⚖️ Supporto burocratico</h4>
                  <div class="box-main p-2 text-center">Ti affianchiamo nella risoluzione di tutti i problemi burocratici che si presentano durante il percorso di candidatura al fine di semplificare il processo ed evitare perdite di tempo.</div>

              </div>
          </div>
      </div>
      <h2 class="my-4 mid-title">Scegli il pacchetto adatto a te e inizia il tuo percorso</h2>
      <div class="row row-cols-1 row-cols-md-3 g-3 my-3">
          <!-- primo pacchetto -->
          <div class="col">
              <div class="pacchetti d-flex flex-column justify-content-center align-items-center">
                  <h4 class="title-pacchetti">Pacchetto 1 ora</h4>
                  <div class="time-pacchetti my-2">89€/h</div>
                  <a href="" class="btn-prenota">PRENOTA</a>
              </div>
          </div>
          <!-- secondo pacchetto -->
          <div class="col">
              <div class="pacchetti d-flex flex-column justify-content-center align-items-center">
                  <h4 class="title-pacchetti">Pacchetto 3 ore</h4>
                  <div class="time-pacchetti my-2">79€/h (237€)</div>
                  <a href="" class="btn-prenota">PRENOTA</a>
              </div>
          </div>
          <!-- terzo pacchetto -->
          <div class="col">
              <div class="pacchetti d-flex flex-column justify-content-center align-items-center">
                  <h4 class="title-pacchetti">Pacchetto 5 ore</h4>
                  <div class="time-pacchetti my-2">69€/h (345€)</div>
                  <a href="" class="btn-prenota">PRENOTA</a>
              </div>
          </div>
      </div>

  </div>
</template>

<script>
export default {

}
</script>

<style scoped lang="scss">
    .big-box{
        height: 185px;
        background: #FFFFFF;
        border: 1px solid #5CB65E;
        box-sizing: border-box;
        border-radius: 15px;
    }
    .pacchetti{
        height: 169px;
        background: #FFFFFF;
        border: 1px solid #5CB65E;
        box-sizing: border-box;
        border-radius: 15px;
        .title-pacchetti{
            font-style: normal;
            font-weight: 500;
            font-size: 28px;
            line-height: 150%;
            /* or 42px */
            display: flex;
            align-items: center;
            text-align: center;
            letter-spacing: 0.0168em;
            font-feature-settings: 'tnum' on, 'lnum' on;
            color: #2D224C;
        }
        .time-pacchetti{
            font-style: normal;
            font-weight: normal;
            font-size: 28px;
            line-height: 150%;
            /* or 42px */
            display: flex;
            align-items: center;
            text-align: center;
            letter-spacing: 0.0168em;
            font-feature-settings: 'tnum' on, 'lnum' on;
            color: #2D224C;

        }
        .btn-prenota{
            background: #5CB65E;
            border: 1px solid #5CB65E;
            box-sizing: border-box;
            border-radius: 8px;
            padding: 3px 15px;
            text-decoration: none;
            font-style: normal;
            font-weight: normal;
            font-size: 16px;
            line-height: 150%;
            text-decoration: none;
            /* identical to box height, or 24px */
            letter-spacing: 0.05em;
            color: #FFFFFF;
        }
    }
    .box-title{
        font-style: normal;
        font-weight: 500;
        font-size: 18px;
        line-height: 27px;
        /* or 27px */
        text-align: center;
        letter-spacing: 0.0168em;
        font-feature-settings: 'tnum' on, 'lnum' on;

        color: #2D224C;
    }
    .box-main{
        font-style: normal;
        font-weight: normal;
        font-size: 14px;
        line-height: 150%;
        /* or 21px */

        text-align: center;
        letter-spacing: 0.0168em;
        font-feature-settings: 'tnum' on, 'lnum' on;

        color: #30284E;
    }
    .prenotazioni-title{
        font-style: normal;
        font-weight: bold;
        font-size: 30px;
        line-height: 150%;
        /* or 45px */
        letter-spacing: 0.03em;
        text-transform: capitalize;
        color: #5CB65E;
    }
    .mid-title{
        padding: 0 20px;
        font-style: normal;
        font-weight: 500;
        font-size: 28px;
        line-height: 150%;
        /* or 42px */

        display: flex;
        align-items: center;
        letter-spacing: 0.03em;

        color: #5CB65E;
    }
    .prenotazione-main{
        font-style: normal;
        font-weight: normal;
        font-size: 24px;
        line-height: 150%;
        /* or 36px */
        letter-spacing: 0.03em;
        color: #2D224C;
    }

    @media screen and (min-width:770px ){
        .prenotazioni-title{
            font-size: 48px;
        }
        .prenotazione-main{
            font-size: 28px;
        }
        
        .big-box{
            height: 177px;
        }
        .box-title{
            font-size: 22px;
        }
        .box-main{
            font-size: 18px;
        }
        .mid-title{
            font-size: 35px;
        }

    }
</style>