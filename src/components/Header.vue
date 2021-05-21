<template>
  <header id="header">
    <div class="container">

      <nav id="menu">

        <!--<img :src="settings.admin_logo" style="height: 70px; width:70px">-->
        <img alt="Vue logo" src="logo.png" style="height: 70px; width:70px; vertical-align: inherit">

        <ul>
          <li> <a class="nav-link" href="#">Home </a></li>
          <li> <a class="nav-link" href="#">Events </a></li>
          <li> <a class="nav-link" href="#">Notice </a></li>
          <li> <a class="nav-link" href="#">Gallery </a></li>
          <li> <a class="nav-link" href="#">Contact </a></li>
        </ul>

      </nav>
      <!-- / navigation -->
    </div>
    <!-- / container -->
  </header>
</template>

<script>
    export default {

        props:[
            'settings'

        ],
        methods:{
            fetchLogo(img){
                return "home/images/"+img;
            },
        }

    }
</script>

<style>

</style>
