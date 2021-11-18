<template>
  <div class="container-fluid padding-fullscreen">
      <div class="row padding-fullscreen px-5 faq">
          <h3 class="mb-4">Domande più frequenti ⁉️</h3>
          <div class="col-12 mb-4 d-flex justify-content-between">Come avvengono le lezioni? <span class="text-end"><i class="fas fa-chevron-down"></i></span></div>
          <hr class="yellow">
          <div class="col-12 mb-4 d-flex justify-content-between">Qual è il processo per parlare con uno dei tutor di Edusogno? <span class="text-end"><i class="fas fa-chevron-down"></i></span></div>
          <hr class="yellow">
          <div class="col-12 mb-4 d-flex justify-content-between">Come Edusogno assegna il tutor una volta che è stato effettuato il pagamento? <span class="text-end"><i class="fas fa-chevron-down"></i></span></div>
          <hr class="yellow">
          <div class="col-12 mb-4 d-flex justify-content-between">In quali campi di studio possono dare consigli i vostri tutor? <span class="text-end"><i class="fas fa-chevron-down"></i></span></div>
          <hr class="yellow">
          <div class="col-12 mb-4 d-flex justify-content-between">Vorrei prenotare più di 5 lezioni, è possibile ottenere un prezzo speciale? <span class="text-end"><i class="fas fa-chevron-down"></i></span></div>
          <hr class="yellow mb-4">
          <div class="col-12 d-flex flex-column flex-md-row justify-content-center align-items-center">
            <div class="m-2 my-foot-btn btn-grandi"><a href="">Leggi le domande più frequenti</a></div>
            <div class="m-2 my-foot-btn btn-grandi"><a class=" mt-3" href="">contattaci  <i class="fab fa-whatsapp mx-2"></i></a></div>
          </div>
          <div class="col-12 d-flex flex-column  align-items-center">
            <div class="text-center my-2 my-foot-btn torna-su"><a href=""><i class="fas fa-arrow-up"></i></a></div>
          </div>
      </div>
      <div class="row justify-content-center padding-fullscreen align-items-center row-social">
        <!-- logo -->
            <div class="col-12 col-lg-3 padding-fullscreen logo">
                <img src="../assets/logo-edusogno.png" alt="">
            </div>
            <div class="d-none d-lg-block col-lg-6">
                <ul class="d-none d-lg-flex justify-content-evenly">
                    <li class="d-inline-block foot-nav">HOME</li>
                    <li class="d-inline-block foot-nav">CHI SIAMO</li>
                    <li class="d-inline-block foot-nav">SERVIZI</li>
                    <li class="d-inline-block foot-nav">RECENSIONI</li>
                    <li class="d-inline-block foot-nav">BLOG</li>
                    <li class="d-inline-block foot-nav">FAQ</li>
                </ul>
            </div>
            <div class="col-12 col-lg-3 d-flex align-items-center flex-column">
                <div class="segui">Seguici su</div>
                <ul class="d-flex justify-content-center  ">
                    <li class="d-inline-block mx-1"><i class="fab fa-tiktok"></i></li>
                    <li class="d-inline-block mx-1"><i class="fab fa-facebook-f"></i></li>
                    <li class="d-inline-block mx-1"><i class="fab fa-linkedin-in"></i></li>
                    <li class="d-inline-block mx-1"><i class="fab fa-instagram"></i></li>
                </ul>
            </div>
            <hr>
            <div class="col-12 copyright">
                Copyright © 2021 Edusogno. Tutti i diritti riservati. | Privacy Policy | Cookie Policy | P.IVA 0‍8587960728
            </div>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped lang="scss">
.yellow{
    color: #FFC164;
    height:2px;
    border-width:0;
    color:#FFC164;
    background-color:#FFC164;
}
.my-foot-btn{
    background-color: white;
    color: #5CB65E;
    border: 1px solid #5CB65E;
    box-sizing: border-box;
    text-transform: uppercase;
    a{
        text-decoration: none;
        color: #5CB65E;
    }
    text-align: center;
}
.btn-grandi{
    width: 316px;
    padding: 8px;
    border: 1px solid #5CB65E;
    box-sizing: border-box;
    border-radius: 8px;
}
.torna-su{
    width: 72px;
    height: 72px;
    border: 2px solid #5CB65E;
    font-size:50px ;
    box-sizing: border-box;
    border-radius: 50px;
}

.padding-fullscreen{
        padding: 0;
        margin:0;
    }
    .faq{
        background: #5CB65E;
        color: white;
        h3{

            font-style: normal;
            font-weight: 500;
            font-size: 30px;
            line-height: 133%;
            /* or 40px */
            letter-spacing: -0.01em;
            font-feature-settings: 'tnum' on, 'lnum' on, 'ordn' on;

        }
    }
        .header{
        height: 140px;
        font-weight: 700;
        .my-line-height{
            line-height: 140px;
        }
    }
    .row-social{
        color: white;
        background-color: #2D224C;
        .foot-nav{
            font-style: normal;
            font-weight: bold;
            font-size: 16px;
            line-height: 150%;
            /* identical to box height, or 24px */
            letter-spacing: 0.005em;
            font-feature-settings: 'tnum' on, 'lnum' on;

        }
        .segui{
            font-style: normal;
            font-weight: bold;
            font-size: 28px;
            line-height: 150%;
            /* or 42px */

            display: flex;
            align-items: center;
            letter-spacing: 0.05em;

            color: #FFFFFF;
        }
    .copyright{ 
        font-style: normal;
        font-weight: normal;
        font-size: 10px;
        line-height: 150%;
        /* or 15px */

        display: flex;
        align-items: center;
        letter-spacing: 0.05em;
    }
    }
    .logo{
        width: 175px;
        
        img{
            width: 100%;
            filter: brightness(0) invert(1);
        }
    }
</style>