<template>
  <div id="nav">
    <swiper>
        <swiper-item >
            <img src="./assets/img/10.jpg" />
        </swiper-item>
          <swiper-item >
            <img src="./assets/img/11.jpg" />
        </swiper-item>
          <swiper-item >
            <img src="./assets/img/12.jpg" />
        </swiper-item>
          <swiper-item >
            <img src="./assets/img/13.jpg" />
        </swiper-item>
          <swiper-item >
            <img src="./assets/img/14.jpg" />
        </swiper-item>
          <swiper-item >
            <img src="./assets/img/15.jpg" />
        </swiper-item>
          <swiper-item >
            <img src="./assets/img/16.jpg" />
        </swiper-item>
    </swiper>
   </div>
</template>
<script>
    import swiper from "./components/swiper"
    import SwiperItem from "./components/swiperItem";
    export default{
      name:'app',
      components:{
          SwiperItem,
        swiper
      },
        data()
        {
            return {
                imgList:[]
            }
        }
    }
</script>
<style>

</style>
