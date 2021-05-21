<template>

        <section class="notice-section m-top50">
          <div class="notice-board">
            <div class="aside-heading">
              <h3 class="headings"><span>Notice Board</span></h3>
            </div>
            <div class="notice-item aside-items notice-box" style="background: gainsboro">
              <ul class="items">
                <li class="text-center" style="padding:8px; line-height:20px; border-bottom: dashed 1px #aaaaaa" >

                </li>
              </ul>
            </div>
            <div class="read-more">
              <a class="nav-link" href="#">View all Notice </a>
            </div>
          </div>
        </section>

</template>

<script>

    export default {
        props:[

        ],
        components: {

        },
        data(){
            return {
                notices :[],
            };
        },
        mounted() {


        },

        computed:{

        },

        methods:{

        }
    }
</script>

<style>

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
