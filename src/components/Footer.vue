<template>


  <footer id="footer" style="padding:80px  50px 0 50px">
    <div class="container-fluid">
      <section>
        <div class="row">
          <div class="col-md-3 contact">
            <h3>Contact</h3>
            <ul>
              <li class="address"><a href="#">Uttara, Dhaka</a></li>
              <li class="mail"><a href="#">example@gmail.com</a></li>
              <li class="phone last"><a href="#">0179846561</a></li>
            </ul>
          </div>

          <div class="col-md-3 forum-topic">
            <h3>Forum topics</h3>
            <ul>
              <li><a href="#">Omnis iste natus error sit</a></li>
              <li><a href="#">Nam libero tempore cum soluta</a></li>
              <li><a href="#">Totam rem aperiam eaque </a></li>
              <li><a href="#">Ipsa quae ab illo inventore veritatis </a></li>
              <li class="last"><a href="#">Architecto beatae vitae dicta sunt </a></li>
            </ul>
          </div>
          <div class="col-md-3 social-media">
            <h3>Social media</h3>
            <p>Temporibus autem quibusdam et aut debitis aut rerum necessitatibus saepe.</p>

            <ul>
              <div class="row ">
                <div class="col-md-6 ">
                  <li class="facebook"><a href="#">Facebook</a></li>
                </div>
                <div class="col-md-6">
                  <li class="google-plus"><a href="#">Google+</a></li>
                </div>
                <div class="col-md-6 ">
                  <li class="twitter"><a href="#">Twitter</a></li>
                </div>
                <div class="col-md-6">
                  <li class="pinterest"><a href="">Pinterest</a></li>
                </div>
              </div>

            </ul>
          </div>
          <div class="col-md-3">
            <h3>Newsletter</h3>
            <p>Assumenda est omnis dolor repellendus temporibus autem quibusdam.</p>
            <form action="#">
              <input placeholder="Email address..." type="text">
              <button type="submit">Subscribe</button>
            </form>
            <ul>
              <li><a href="#"></a></li>
            </ul>
          </div>
        </div>
      </section>
      <p class="copy">Copyright 2021 . All rights reserved.</p>
    </div>

  </footer>


</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
//import Home from './components/Home.vue'

export default {
  name: 'App',
    props:[
        'settings'

    ]
}
</script>

<style>

</style>
