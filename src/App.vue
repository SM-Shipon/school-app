<template>

  <Header/>

  <Slider/>

  <div class="pb-5">
      <div class="container-fluid">
        <div class="row  mb-4">
          <div  class="col-md-9" >
             <Home/>
          </div>
          <div class="col-md-3" >
            <aside class="col-xs-12 col-sm-12">
              <Notice/>
            </aside>
          </div>
        </div>
      </div>
  </div>
  <Footer/>
</template>

<script>

import Header from './components/Header.vue'
import Slider from './components/Slider.vue'
import Home from './components/Home.vue'
import Footer from './components/Footer.vue'
import Notice from './components/Notice.vue'
    export default {
        name: 'app',
        components: {
            Header,
            Slider,
            Home,
            Footer,
            Notice
        },



    }
</script>

<style>

</style>
