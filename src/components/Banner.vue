<template>  
   <div>
     <div id="banner">
         <div id="wave">
            <img :src="imagem" alt="">
         </div>
         <div id="telas">
             <div class="container">
                 <div class="row">
                     <div class="col-lg-6 col-md-6">
                         <div id="div_block-204-35" class="ct-div-block">
                            <h1 id="headline-206-35" class="ct-headline">
                                Simples e muito mais <br />
                                que um CRM
                            </h1>
                            <div id="text_block-208-35" class="ct-text-block">Um sistema que nutre, alimenta e facilita a conversão do lead <br /> em um contrato fechado. <br /></div>
                            <div id="div_block-247-35" class="ct-div-block">
                                <div id="-ou_ha_button-246-35" class="oxy-ou-ha-button oxy-ultimate-element">
                                    <div class="ou-ha-button-container hover-effect-sweep_right">
                                        <a href="#section-201-35" target="_self" rel="nofollow" role="button" aria-lable="hidden" class="ou-ha-button ou-button-effect"><span class="btn-text">Comprar agora</span></a>
                                    </div>
                                </div>
                            </div>
                        </div>

                     </div>
                     <div class="col-lg-6 col-md-6">
                         <img :src="tela1" alt="">
                         <img :src="tela2" alt="">
                     </div>
                 </div>
             </div>
         </div>
     </div>
   </div>
</template>

<script>

export default {
  name: 'Banner',
  el: "#banner",
  data: () => ({
      imagem: "wave.png",
      tela1: "https://projetosprospecta.com.br/dodotools/wp-content/uploads/2021/03/unknown-8-1.png",
      tela2: "https://projetosprospecta.com.br/dodotools/wp-content/uploads/2021/03/unknown-1-1.png"
  })
}


</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

    #wave img{
      transform: rotate(180deg);
      width: 100%;
    }

    #telas{

        position: relative;
        top: -34rem;
    }

    #telas img{

        width: 100%;
        height: auto;
    }

    #telas img:last-child{

            position: relative;
            top: -14rem;
            width: 96%;
            left: 7rem;
            box-shadow: 0px 3px 6px #00000016;
    }

    /*! CSS Used from: https://projetosprospecta.com.br/dodotools/wp-content/plugins/oxygen/component-framework/oxygen.css?ver=3.7 ; media=all */
@media all {
    h1 {
        margin: 0;
    }
    a {
        background-color: transparent;
        -webkit-text-decoration-skip: objects;
    }
    *,
    ::after,
    ::before {
        box-sizing: inherit;
    }
}
/*! CSS Used from: https://projetosprospecta.com.br/dodotools/wp-content/uploads/oxygen/css/home-35.css?cache=1615291233&ver=5.6.2 ; media=all */
@media all {
    #div_block-204-35 {
        flex-direction: column;
        display: flex;
        align-items: flex-start;
        width: 100%;
        text-align: center;
        margin-right: 50px;
    }
    #div_block-247-35 {
        width: 100%;
        flex-direction: row;
        display: flex;
        justify-content: flex-start;
        text-align: left;
        margin-top: 25px;
    }
    @media (max-width: 479px) {
        #div_block-204-35 {
            flex-direction: column;
            display: flex;
            align-items: center;
            text-align: center;
            padding-bottom: 0px;
            padding-left: 0px;
            padding-right: 0px;
            margin-bottom: 0px;
            margin-top: 0px;
            margin-left: 0px;
            margin-right: 0px;
            width: 100%;
            padding-top: 40%;
        }
    }
    @media (max-width: 479px) {
        #div_block-247-35 {
            flex-direction: column;
            display: flex;
            align-items: center;
            text-align: center;
        }
    }
    #headline-206-35 {
        font-size: 40px;
        font-family: "Montserrat";
        color: #ffffff;
        line-height: 1.4;
        text-align: left;
    }
    @media (max-width: 479px) {
        #headline-206-35 {
            text-align: center;
        }
    }
    #text_block-208-35 {
        color: #ffffff;
        font-size: 15px;
        font-family: "Open Sans";
        text-align: left;
        line-height: 1.8;
        z-index: 1;
    }
    @media (max-width: 479px) {
        #text_block-208-35 {
            text-align: center;
        }
    }
    #-ou_ha_button-246-35 .ou-ha-button {
        font-family: "Montserrat";
        font-size: 15px;
        font-weight: 500;
        color: #ffffff;
        background-color: #00a1d3;
        border-top-width: 0px;
        border-right-width: 0px;
        border-bottom-width: 0px;
        border-left-width: 0px;
        border-top-color: #eceeef;
        border-right-color: #eceeef;
        border-bottom-color: #eceeef;
        border-left-color: #eceeef;
        border-top-style: none;
        border-right-style: none;
        border-bottom-style: none;
        border-left-style: none;
        border_radius_border-radius: 50px;
        border-radius: 50px;
        padding-left: 30px;
        padding-right: 30px;
        padding-top: 10px;
        padding-bottom: 10px;
    }
    #-ou_ha_button-246-35 .ou-ha-button:hover,
    #-ou_ha_button-246-35 .ou-ha-button:before {
        background-color: #005289;
    }
    #-ou_ha_button-246-35 .ou-ha-button:hover,
    #-ou_ha_button-246-35 .ou-ha-button:before {
        color: #ffffff;
    }
    .ou-ha-button-container {
        display: inline-block;
        position: relative;
        width: auto;
    }
    a.ou-ha-button {
        background-color: #333333;
        color: #ffffff;
        display: inline-block;
        padding: 10px;
        position: relative;
        text-align: center;
        overflow: hidden;
        width: auto;
        vertical-align: middle;
        -webkit-transform: translateZ(0);
        transform: translateZ(0);
        -webkit-backface-visibility: hidden;
        backface-visibility: hidden;
        -moz-osx-font-smoothing: grayscale;
    }
    a.ou-ha-button span {
        display: inline-block;
    }
    a.ou-ha-button:before {
        position: absolute;
        z-index: -1;
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
        -webkit-transition-property: transform;
        -moz-transition-property: transform;
        -o-transition-property: transform;
        -ms-transition-property: transform;
        transition-property: transform;
        -webkit-transition-timing-function: ease-out;
        -moz-transition-timing-function: ease-out;
        -o-transition-timing-function: ease-out;
        -ms-transition-timing-function: ease-out;
        transition-timing-function: ease-out;
    }
    a.ou-ha-button,
    a.ou-ha-button:before {
        transition-duration: 0.3s;
    }
    a.ou-ha-button:before,
    a.ou-ha-button:hover:before {
        background-color: #f90c0c;
    }
    #-ou_ha_button-246-35 .ou-ha-button-container:not(.hover-effect-none) .ou-ha-button:hover {
        background-color: color(7);
    }
    .hover-effect-sweep_right .ou-button-effect:before {
        content: " ";
        -webkit-transform: scaleX(0);
        -moz-transform: scaleX(0);
        -o-transform: scaleX(0);
        -ms-transform: scaleX(0);
        transform: scaleX(0);
        -webkit-transform-origin: 0 50%;
        -moz-transform-origin: 0 50%;
        -o-transform-origin: 0 50%;
        -ms-transform-origin: 0 50%;
        transform-origin: 0 50%;
    }
    .hover-effect-sweep_right .ou-button-effect:hover:before {
        -webkit-transform: scaleX(1);
        -moz-transform: scaleX(1);
        -o-transform: scaleX(1);
        -ms-transform: scaleX(1);
        transform: scaleX(1);
    }
    #-ou_ha_button-246-35:hover {
        oxy-ou-ha-button-btn-effect: sweep_right;
    }
}
/*! CSS Used from: https://projetosprospecta.com.br/dodotools/wp-content/uploads/oxygen/css/universal.css?cache=1615291233&ver=5.6.2 ; media=all */
@media all {
    .ct-div-block {
        display: flex;
        flex-wrap: nowrap;
        flex-direction: column;
        align-items: flex-start;
    }
    @media screen and (-ms-high-contrast: active), (-ms-high-contrast: none) {
        .ct-div-block,
        .ct-text-block,
        .ct-headline {
            max-width: 100%;
        }
        body * {
            min-height: 1px;
        }
    }
    h1 {
        font-family: "Montserrat";
        font-size: 30px;
        font-weight: 600;
        color: 444f60;
    }
    a {
        color: #e96199;
        text-decoration: none;
    }
    a:hover {
        color: #e9435a;
        text-decoration: none;
    }
}
/*! CSS Used fontfaces */
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 100;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTUQjIg1_i6t8kCHKm45_QpRxC7mw9c.woff2) format("woff2");
    unicode-range: U+0460-052F, U+1C80-1C88, U+20B4, U+2DE0-2DFF, U+A640-A69F, U+FE2E-FE2F;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 100;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTUQjIg1_i6t8kCHKm45_QpRzS7mw9c.woff2) format("woff2");
    unicode-range: U+0400-045F, U+0490-0491, U+04B0-04B1, U+2116;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 100;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTUQjIg1_i6t8kCHKm45_QpRxi7mw9c.woff2) format("woff2");
    unicode-range: U+0102-0103, U+0110-0111, U+0128-0129, U+0168-0169, U+01A0-01A1, U+01AF-01B0, U+1EA0-1EF9, U+20AB;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 100;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTUQjIg1_i6t8kCHKm45_QpRxy7mw9c.woff2) format("woff2");
    unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 100;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTUQjIg1_i6t8kCHKm45_QpRyS7m.woff2) format("woff2");
    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 200;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTURjIg1_i6t8kCHKm45_aZA3gTD_u50.woff2) format("woff2");
    unicode-range: U+0460-052F, U+1C80-1C88, U+20B4, U+2DE0-2DFF, U+A640-A69F, U+FE2E-FE2F;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 200;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTURjIg1_i6t8kCHKm45_aZA3g3D_u50.woff2) format("woff2");
    unicode-range: U+0400-045F, U+0490-0491, U+04B0-04B1, U+2116;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 200;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTURjIg1_i6t8kCHKm45_aZA3gbD_u50.woff2) format("woff2");
    unicode-range: U+0102-0103, U+0110-0111, U+0128-0129, U+0168-0169, U+01A0-01A1, U+01AF-01B0, U+1EA0-1EF9, U+20AB;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 200;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTURjIg1_i6t8kCHKm45_aZA3gfD_u50.woff2) format("woff2");
    unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 200;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTURjIg1_i6t8kCHKm45_aZA3gnD_g.woff2) format("woff2");
    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 300;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTURjIg1_i6t8kCHKm45_cJD3gTD_u50.woff2) format("woff2");
    unicode-range: U+0460-052F, U+1C80-1C88, U+20B4, U+2DE0-2DFF, U+A640-A69F, U+FE2E-FE2F;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 300;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTURjIg1_i6t8kCHKm45_cJD3g3D_u50.woff2) format("woff2");
    unicode-range: U+0400-045F, U+0490-0491, U+04B0-04B1, U+2116;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 300;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTURjIg1_i6t8kCHKm45_cJD3gbD_u50.woff2) format("woff2");
    unicode-range: U+0102-0103, U+0110-0111, U+0128-0129, U+0168-0169, U+01A0-01A1, U+01AF-01B0, U+1EA0-1EF9, U+20AB;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 300;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTURjIg1_i6t8kCHKm45_cJD3gfD_u50.woff2) format("woff2");
    unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 300;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTURjIg1_i6t8kCHKm45_cJD3gnD_g.woff2) format("woff2");
    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 400;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTUSjIg1_i6t8kCHKm459WRhyzbi.woff2) format("woff2");
    unicode-range: U+0460-052F, U+1C80-1C88, U+20B4, U+2DE0-2DFF, U+A640-A69F, U+FE2E-FE2F;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 400;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTUSjIg1_i6t8kCHKm459W1hyzbi.woff2) format("woff2");
    unicode-range: U+0400-045F, U+0490-0491, U+04B0-04B1, U+2116;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 400;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTUSjIg1_i6t8kCHKm459WZhyzbi.woff2) format("woff2");
    unicode-range: U+0102-0103, U+0110-0111, U+0128-0129, U+0168-0169, U+01A0-01A1, U+01AF-01B0, U+1EA0-1EF9, U+20AB;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 400;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTUSjIg1_i6t8kCHKm459Wdhyzbi.woff2) format("woff2");
    unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 400;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTUSjIg1_i6t8kCHKm459Wlhyw.woff2) format("woff2");
    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 500;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTURjIg1_i6t8kCHKm45_ZpC3gTD_u50.woff2) format("woff2");
    unicode-range: U+0460-052F, U+1C80-1C88, U+20B4, U+2DE0-2DFF, U+A640-A69F, U+FE2E-FE2F;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 500;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTURjIg1_i6t8kCHKm45_ZpC3g3D_u50.woff2) format("woff2");
    unicode-range: U+0400-045F, U+0490-0491, U+04B0-04B1, U+2116;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 500;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTURjIg1_i6t8kCHKm45_ZpC3gbD_u50.woff2) format("woff2");
    unicode-range: U+0102-0103, U+0110-0111, U+0128-0129, U+0168-0169, U+01A0-01A1, U+01AF-01B0, U+1EA0-1EF9, U+20AB;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 500;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTURjIg1_i6t8kCHKm45_ZpC3gfD_u50.woff2) format("woff2");
    unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 500;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTURjIg1_i6t8kCHKm45_ZpC3gnD_g.woff2) format("woff2");
    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 600;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTURjIg1_i6t8kCHKm45_bZF3gTD_u50.woff2) format("woff2");
    unicode-range: U+0460-052F, U+1C80-1C88, U+20B4, U+2DE0-2DFF, U+A640-A69F, U+FE2E-FE2F;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 600;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTURjIg1_i6t8kCHKm45_bZF3g3D_u50.woff2) format("woff2");
    unicode-range: U+0400-045F, U+0490-0491, U+04B0-04B1, U+2116;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 600;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTURjIg1_i6t8kCHKm45_bZF3gbD_u50.woff2) format("woff2");
    unicode-range: U+0102-0103, U+0110-0111, U+0128-0129, U+0168-0169, U+01A0-01A1, U+01AF-01B0, U+1EA0-1EF9, U+20AB;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 600;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTURjIg1_i6t8kCHKm45_bZF3gfD_u50.woff2) format("woff2");
    unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 600;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTURjIg1_i6t8kCHKm45_bZF3gnD_g.woff2) format("woff2");
    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 700;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTURjIg1_i6t8kCHKm45_dJE3gTD_u50.woff2) format("woff2");
    unicode-range: U+0460-052F, U+1C80-1C88, U+20B4, U+2DE0-2DFF, U+A640-A69F, U+FE2E-FE2F;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 700;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTURjIg1_i6t8kCHKm45_dJE3g3D_u50.woff2) format("woff2");
    unicode-range: U+0400-045F, U+0490-0491, U+04B0-04B1, U+2116;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 700;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTURjIg1_i6t8kCHKm45_dJE3gbD_u50.woff2) format("woff2");
    unicode-range: U+0102-0103, U+0110-0111, U+0128-0129, U+0168-0169, U+01A0-01A1, U+01AF-01B0, U+1EA0-1EF9, U+20AB;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 700;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTURjIg1_i6t8kCHKm45_dJE3gfD_u50.woff2) format("woff2");
    unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 700;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTURjIg1_i6t8kCHKm45_dJE3gnD_g.woff2) format("woff2");
    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 800;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTURjIg1_i6t8kCHKm45_c5H3gTD_u50.woff2) format("woff2");
    unicode-range: U+0460-052F, U+1C80-1C88, U+20B4, U+2DE0-2DFF, U+A640-A69F, U+FE2E-FE2F;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 800;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTURjIg1_i6t8kCHKm45_c5H3g3D_u50.woff2) format("woff2");
    unicode-range: U+0400-045F, U+0490-0491, U+04B0-04B1, U+2116;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 800;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTURjIg1_i6t8kCHKm45_c5H3gbD_u50.woff2) format("woff2");
    unicode-range: U+0102-0103, U+0110-0111, U+0128-0129, U+0168-0169, U+01A0-01A1, U+01AF-01B0, U+1EA0-1EF9, U+20AB;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 800;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTURjIg1_i6t8kCHKm45_c5H3gfD_u50.woff2) format("woff2");
    unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 800;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTURjIg1_i6t8kCHKm45_c5H3gnD_g.woff2) format("woff2");
    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 900;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTURjIg1_i6t8kCHKm45_epG3gTD_u50.woff2) format("woff2");
    unicode-range: U+0460-052F, U+1C80-1C88, U+20B4, U+2DE0-2DFF, U+A640-A69F, U+FE2E-FE2F;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 900;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTURjIg1_i6t8kCHKm45_epG3g3D_u50.woff2) format("woff2");
    unicode-range: U+0400-045F, U+0490-0491, U+04B0-04B1, U+2116;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 900;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTURjIg1_i6t8kCHKm45_epG3gbD_u50.woff2) format("woff2");
    unicode-range: U+0102-0103, U+0110-0111, U+0128-0129, U+0168-0169, U+01A0-01A1, U+01AF-01B0, U+1EA0-1EF9, U+20AB;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 900;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTURjIg1_i6t8kCHKm45_epG3gfD_u50.woff2) format("woff2");
    unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
}
@font-face {
    font-family: "Montserrat";
    font-style: normal;
    font-weight: 900;
    src: url(https://fonts.gstatic.com/s/montserrat/v15/JTURjIg1_i6t8kCHKm45_epG3gnD_g.woff2) format("woff2");
    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
}
@font-face {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 300;
    src: url(https://fonts.gstatic.com/s/opensans/v18/mem5YaGs126MiZpBA-UN_r8OX-hpOqc.woff2) format("woff2");
    unicode-range: U+0460-052F, U+1C80-1C88, U+20B4, U+2DE0-2DFF, U+A640-A69F, U+FE2E-FE2F;
}
@font-face {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 300;
    src: url(https://fonts.gstatic.com/s/opensans/v18/mem5YaGs126MiZpBA-UN_r8OVuhpOqc.woff2) format("woff2");
    unicode-range: U+0400-045F, U+0490-0491, U+04B0-04B1, U+2116;
}
@font-face {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 300;
    src: url(https://fonts.gstatic.com/s/opensans/v18/mem5YaGs126MiZpBA-UN_r8OXuhpOqc.woff2) format("woff2");
    unicode-range: U+1F00-1FFF;
}
@font-face {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 300;
    src: url(https://fonts.gstatic.com/s/opensans/v18/mem5YaGs126MiZpBA-UN_r8OUehpOqc.woff2) format("woff2");
    unicode-range: U+0370-03FF;
}
@font-face {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 300;
    src: url(https://fonts.gstatic.com/s/opensans/v18/mem5YaGs126MiZpBA-UN_r8OXehpOqc.woff2) format("woff2");
    unicode-range: U+0102-0103, U+0110-0111, U+0128-0129, U+0168-0169, U+01A0-01A1, U+01AF-01B0, U+1EA0-1EF9, U+20AB;
}
@font-face {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 300;
    src: url(https://fonts.gstatic.com/s/opensans/v18/mem5YaGs126MiZpBA-UN_r8OXOhpOqc.woff2) format("woff2");
    unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
}
@font-face {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 300;
    src: url(https://fonts.gstatic.com/s/opensans/v18/mem5YaGs126MiZpBA-UN_r8OUuhp.woff2) format("woff2");
    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
}
@font-face {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 400;
    src: url(https://fonts.gstatic.com/s/opensans/v18/mem8YaGs126MiZpBA-UFWJ0bbck.woff2) format("woff2");
    unicode-range: U+0460-052F, U+1C80-1C88, U+20B4, U+2DE0-2DFF, U+A640-A69F, U+FE2E-FE2F;
}
@font-face {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 400;
    src: url(https://fonts.gstatic.com/s/opensans/v18/mem8YaGs126MiZpBA-UFUZ0bbck.woff2) format("woff2");
    unicode-range: U+0400-045F, U+0490-0491, U+04B0-04B1, U+2116;
}
@font-face {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 400;
    src: url(https://fonts.gstatic.com/s/opensans/v18/mem8YaGs126MiZpBA-UFWZ0bbck.woff2) format("woff2");
    unicode-range: U+1F00-1FFF;
}
@font-face {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 400;
    src: url(https://fonts.gstatic.com/s/opensans/v18/mem8YaGs126MiZpBA-UFVp0bbck.woff2) format("woff2");
    unicode-range: U+0370-03FF;
}
@font-face {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 400;
    src: url(https://fonts.gstatic.com/s/opensans/v18/mem8YaGs126MiZpBA-UFWp0bbck.woff2) format("woff2");
    unicode-range: U+0102-0103, U+0110-0111, U+0128-0129, U+0168-0169, U+01A0-01A1, U+01AF-01B0, U+1EA0-1EF9, U+20AB;
}
@font-face {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 400;
    src: url(https://fonts.gstatic.com/s/opensans/v18/mem8YaGs126MiZpBA-UFW50bbck.woff2) format("woff2");
    unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
}
@font-face {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 400;
    src: url(https://fonts.gstatic.com/s/opensans/v18/mem8YaGs126MiZpBA-UFVZ0b.woff2) format("woff2");
    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
}
@font-face {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 600;
    src: url(https://fonts.gstatic.com/s/opensans/v18/mem5YaGs126MiZpBA-UNirkOX-hpOqc.woff2) format("woff2");
    unicode-range: U+0460-052F, U+1C80-1C88, U+20B4, U+2DE0-2DFF, U+A640-A69F, U+FE2E-FE2F;
}
@font-face {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 600;
    src: url(https://fonts.gstatic.com/s/opensans/v18/mem5YaGs126MiZpBA-UNirkOVuhpOqc.woff2) format("woff2");
    unicode-range: U+0400-045F, U+0490-0491, U+04B0-04B1, U+2116;
}
@font-face {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 600;
    src: url(https://fonts.gstatic.com/s/opensans/v18/mem5YaGs126MiZpBA-UNirkOXuhpOqc.woff2) format("woff2");
    unicode-range: U+1F00-1FFF;
}
@font-face {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 600;
    src: url(https://fonts.gstatic.com/s/opensans/v18/mem5YaGs126MiZpBA-UNirkOUehpOqc.woff2) format("woff2");
    unicode-range: U+0370-03FF;
}
@font-face {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 600;
    src: url(https://fonts.gstatic.com/s/opensans/v18/mem5YaGs126MiZpBA-UNirkOXehpOqc.woff2) format("woff2");
    unicode-range: U+0102-0103, U+0110-0111, U+0128-0129, U+0168-0169, U+01A0-01A1, U+01AF-01B0, U+1EA0-1EF9, U+20AB;
}
@font-face {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 600;
    src: url(https://fonts.gstatic.com/s/opensans/v18/mem5YaGs126MiZpBA-UNirkOXOhpOqc.woff2) format("woff2");
    unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
}
@font-face {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 600;
    src: url(https://fonts.gstatic.com/s/opensans/v18/mem5YaGs126MiZpBA-UNirkOUuhp.woff2) format("woff2");
    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
}
@font-face {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 700;
    src: url(https://fonts.gstatic.com/s/opensans/v18/mem5YaGs126MiZpBA-UN7rgOX-hpOqc.woff2) format("woff2");
    unicode-range: U+0460-052F, U+1C80-1C88, U+20B4, U+2DE0-2DFF, U+A640-A69F, U+FE2E-FE2F;
}
@font-face {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 700;
    src: url(https://fonts.gstatic.com/s/opensans/v18/mem5YaGs126MiZpBA-UN7rgOVuhpOqc.woff2) format("woff2");
    unicode-range: U+0400-045F, U+0490-0491, U+04B0-04B1, U+2116;
}
@font-face {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 700;
    src: url(https://fonts.gstatic.com/s/opensans/v18/mem5YaGs126MiZpBA-UN7rgOXuhpOqc.woff2) format("woff2");
    unicode-range: U+1F00-1FFF;
}
@font-face {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 700;
    src: url(https://fonts.gstatic.com/s/opensans/v18/mem5YaGs126MiZpBA-UN7rgOUehpOqc.woff2) format("woff2");
    unicode-range: U+0370-03FF;
}
@font-face {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 700;
    src: url(https://fonts.gstatic.com/s/opensans/v18/mem5YaGs126MiZpBA-UN7rgOXehpOqc.woff2) format("woff2");
    unicode-range: U+0102-0103, U+0110-0111, U+0128-0129, U+0168-0169, U+01A0-01A1, U+01AF-01B0, U+1EA0-1EF9, U+20AB;
}
@font-face {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 700;
    src: url(https://fonts.gstatic.com/s/opensans/v18/mem5YaGs126MiZpBA-UN7rgOXOhpOqc.woff2) format("woff2");
    unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
}
@font-face {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 700;
    src: url(https://fonts.gstatic.com/s/opensans/v18/mem5YaGs126MiZpBA-UN7rgOUuhp.woff2) format("woff2");
    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
}
@font-face {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 800;
    src: url(https://fonts.gstatic.com/s/opensans/v18/mem5YaGs126MiZpBA-UN8rsOX-hpOqc.woff2) format("woff2");
    unicode-range: U+0460-052F, U+1C80-1C88, U+20B4, U+2DE0-2DFF, U+A640-A69F, U+FE2E-FE2F;
}
@font-face {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 800;
    src: url(https://fonts.gstatic.com/s/opensans/v18/mem5YaGs126MiZpBA-UN8rsOVuhpOqc.woff2) format("woff2");
    unicode-range: U+0400-045F, U+0490-0491, U+04B0-04B1, U+2116;
}
@font-face {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 800;
    src: url(https://fonts.gstatic.com/s/opensans/v18/mem5YaGs126MiZpBA-UN8rsOXuhpOqc.woff2) format("woff2");
    unicode-range: U+1F00-1FFF;
}
@font-face {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 800;
    src: url(https://fonts.gstatic.com/s/opensans/v18/mem5YaGs126MiZpBA-UN8rsOUehpOqc.woff2) format("woff2");
    unicode-range: U+0370-03FF;
}
@font-face {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 800;
    src: url(https://fonts.gstatic.com/s/opensans/v18/mem5YaGs126MiZpBA-UN8rsOXehpOqc.woff2) format("woff2");
    unicode-range: U+0102-0103, U+0110-0111, U+0128-0129, U+0168-0169, U+01A0-01A1, U+01AF-01B0, U+1EA0-1EF9, U+20AB;
}
@font-face {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 800;
    src: url(https://fonts.gstatic.com/s/opensans/v18/mem5YaGs126MiZpBA-UN8rsOXOhpOqc.woff2) format("woff2");
    unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
}
@font-face {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 800;
    src: url(https://fonts.gstatic.com/s/opensans/v18/mem5YaGs126MiZpBA-UN8rsOUuhp.woff2) format("woff2");
    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
}


</style>
