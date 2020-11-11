<template>
      <li class="swiperItem">
          <slot>
          </slot>
      </li>
</template>

<script>
export default {
    name:'swiperItem'
}
</script>

<style>
    li.swiperItem img
    {
        vertical-align:bottom;
        width: 400px;
    }
    li.swiperItem 
    {
        float: left;
        list-style: none;
    }
</style>