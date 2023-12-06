<template>
  <header class="site-header site-header__header-two ">
      <nav class="navbar navbar-expand-lg navbar-light header-navigation stricky">
          <div class="container clearfix">
              <!-- Brand and toggle get grouped for better mobile display -->
              <div class="logo-box clearfix">
                  <a class="navbar-brand" href="/">
                      <img src="/assets/images/logo.png" class="main-logo" width="100" alt="logo" />
                  </a>
                  <button class="menu-toggler" data-target=".main-navigation">
                      <span class="kipso-icon-menu"></span>
                  </button>
                  <form action="#" class="header__search-form">
                     
                      <button type="submit"><i class="kipso-icon-magnifying-glass"></i>
                          <!-- /.kipso-icon-magnifying-glass --></button>
                  </form>
              </div><!-- /.logo-box -->
              <!-- Collect the nav links, forms, and other content for toggling -->
            <div class="main-navigation">
                                          <ul class=" navigation-box">
                                           <li class="current">
                                                  <nuxt-link to="/">Accueil</nuxt-link>
                                              </li>
                                              <li >
                                                  <a href="#">Qui sommes-nous</a>
                                                  <ul class="sub-menu">
                                                    <li><nuxt-link to="/about">Presentation</nuxt-link></li>
                                                    <li><nuxt-link to="/faq">Securité</nuxt-link></li>
                                                    <li><nuxt-link to="/faq">Qualité</nuxt-link></li>
                                                  </ul><!-- /.sub-menu -->
                                              </li>

                                              <li>
                                                  <nuxt-link to="/contact">Abonnement Scholaire</nuxt-link>
                                              </li>
                                              <li>
                                                  <nuxt-link to="/contact">Abonnement Fonctionnaire</nuxt-link>
                                              </li>
                                              <li>
                                                  <a href="#">Gallerie</a>
                                                  <ul class="sub-menu">
                                                      <li><nuxt-link to="/gallery">Images</nuxt-link></li>
                                                      <li><nuxt-link to="/gallery">Videos</nuxt-link></li>
                                                  </ul><!-- /.sub-menu -->
                                              </li>
                                              <li>
                                                  <nuxt-link to="#">Nouveautés</nuxt-link>
                                                  <ul class="sub-menu">
                                                      <li><nuxt-link to="/news">Nouveautés</nuxt-link></li>
                                                      <li><nuxt-link to="/news">Appel d'offre</nuxt-link></li>
                                                      <li><nuxt-link to="/courses">Evenements</nuxt-link></li>
                                                      <li><nuxt-link to="/courses">Communication Media</nuxt-link></li>

                                                  </ul><!-- /.sub-menu -->
                                              </li>
                                              
                                          
                                              <li>
                                                  <nuxt-link to="/contact">Contact</nuxt-link>
                                              </li>
                                          </ul>
                                      </div><!-- /.navbar-collapse -->
              <div class="right-side-box">
                  <div class="header__social">
                      <a class="navbar-brand" href="/">
                      <img src="/assets/images/tunisie.png" class="main-logo" width="95" alt="tunisie" />
                  </a>
                  </div><!-- /.header__social -->
              </div><!-- /.right-side-box -->
          </div>
          <!-- /.container -->
      </nav>
     
  </header>
</template>

<script>
    export default {
        name: "NavTwo"
    }
</script>

<style scoped>

</style>
