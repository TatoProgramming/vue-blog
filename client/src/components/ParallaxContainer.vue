<template>
   <div :id="id" class="parallax-container">
    <div class="section no-pad-bot">
      <div class="container">
        <slot></slot>
      </div>
    </div>
    <div class="parallax"><img :src="imgSrc" :alt="imgAlt"></div>
  </div>
</template>

<script>
export default {
    name: 'ParallaxContainer',
    props:{
      id: String,
      imgSrc: String, 
      imgAlt: String
    }
}
</script>

