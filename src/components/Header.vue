<template>
  <div class="container header">
        <div class="row justify-content-between">
            <!-- logo -->
            <div class="col col-sm-2 logo my-line-height">
                <img src="../assets/logo-edusogno.png" alt="">
            </div>
            <!-- link -->
            <div class="mx-md-2 col-8 potion-relative text-center">
                <!-- menu da telefono -->
                <!-- bottone  -->
                <div class="d-md-none text-end me-3 my-burger" v-on:click="myactive">
                    <i class="fas fa-bars my-line-height "></i>
                <!-- dropdown-->
                </div>
                <div v-if="burgeractive" class="text-center p-4 d-flex d-md-none flex-column align-items-center position-absolute box-dropdown">
                    <ul class="d-flex d-md-none flex-column align-items-center text-center">
                        <li class="m-2 text-center">HOME</li>
                        <li class="m-2">CHI SIAMO</li>
                        <li class="m-2">SERVIZI</li>
                        <li class="m-2">RECENSIONI</li>
                        <li class="m-2">BLOG</li>
                        <li class="mt-2">FAQ</li>
                    </ul>
                </div>
                <!-- menu da pc -->
                <ul class="d-none d-md-flex justify-content-evenly my-line-height">
                    <li class="d-inline-block">HOME</li>
                    <li class="d-inline-block">CHI SIAMO</li>
                    <li class="d-inline-block active">SERVIZI</li>
                    <li class="d-inline-block">RECENSIONI</li>
                    <li class="d-inline-block">BLOG</li>
                    <li class="d-inline-block">FAQ</li>
                </ul>
            </div>
            <!-- social -->
            <div class="  d-none d-lg-block col-2">
                <ul class="d-flex  my-line-height">
                    <li class="d-inline-block mx-1"><i class="fab fa-tiktok"></i></li>
                    <li class="d-inline-block mx-1"><i class="fab fa-facebook-f"></i></li>
                    <li class="d-inline-block mx-1"><i class="fab fa-linkedin-in"></i></li>
                    <li class="d-inline-block mx-1"><i class="fab fa-instagram"></i></li>
                </ul>
            </div>
        </div>
  </div>
</template>

<script>
export default {
    data(){
        return{
            burgeractive:false,
        }
    },
    methods: {
        myactive(){
            this.burgeractive=!this.burgeractive;
        }
    }
}
</script>

<style scoped lang="scss">

    .header{
        height: 140px;
        font-weight: 700;
        .my-line-height{
            line-height: 140px;
        }
    }
    .my-burger{
        *::before{
            height: 40px;
            width: 40px;
            padding: 8px;
          /*   border:1px solid black; */
            border-radius:18px ;
            box-shadow: rgba(0, 0, 0, 0.19) 0px 10px 20px, rgba(0, 0, 0, 0.158) 0px 6px 6px;
        }
    }
    .box-dropdown{
        border: 2px solid #5CB65E;
        border-radius: 12px;
        z-index: 2;
        background-color: white;
        right:45px;
        top:90px;
        ul{
            padding: 0;
            margin: 0;
        }
        li{
            
            list-style: none;
            font-size: 20px;
        }
    }
    .active{
        text-decoration: underline;
        text-decoration-thickness:3px ;
        text-decoration-color: #FFC164;
    }
    .logo{
        min-width: 100px;
        max-width: 140px;
        img{
           
            width: 100%;
        }
    }
</style>