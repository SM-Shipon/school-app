<template>
  <AboutSchool/>
  <Message/>
</template>

<script>


    import AboutSchool from './about-school.vue'
    import Message from './Message.vue'

    export default {
        name: 'Home',
        props:[
            'settings',
            'username'

        ],
        components: {
            AboutSchool,
            Message,
        },
        data(){
            return {

            };
        },
        mounted() {


        },
        created() {

            console.log('Home created')

        },

        computed(){

        },

        methods:{

        }
    }
</script>

<style>
  .m-top50 {
    margin-top:5px;
  }

  .notice-board .aside-heading h3 {
    background: #002147;
    border-color: #002147;
    color: #fff;
    border-bottom-color: #011429;
  }
  .aside-heading h3 {
    font-size: 22px;
    text-transform: capitalize;
    font-family: Roboto Slab;
    font-weight: bold;
    text-align: center;
    position: relative;
    padding: 10px;
    border-top: 2px solid #e8e8e8;
    border-bottom: 3px solid #e8e8e8;
  }
  .notice-item {
    background: #002147;
    min-height:150px;
    /*max-height:100px;*/
  }
  .aside-items {
    background: #fff;
    padding: 10px 0;
  }
  .aside-items li{
    font-size:13px;
  }
  .notice-board .read-more {
    text-align: center;
    background: #011429;
    text-transform: uppercase;
  }

  .notice-box ul {
    height:300px;
    text-align: left;
    overflow: hidden;
    overflow-y: scroll;
  }





</style>
