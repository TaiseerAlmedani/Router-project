<template>
  <section class="hero is-medium" :class="BulmaColor">
      <div class="hero-body has-text-centered">
        <p class="title">
         <slot name="title">Welocme , And Hi</slot>
        </p>
        <p class="subtitle">
        <slot name="subtitle">We are the best</slot>
        </p>
      </div>
    </section>
</template>
<script>
export default{
  props: {
    color : String,
  },
  computed:{
    BulmaColor(){
      return `is-${this.color}`
    }
  },
}
</script>