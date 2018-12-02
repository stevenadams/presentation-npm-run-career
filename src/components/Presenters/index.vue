<template>
  <section
    class="Prsenters"
  >
    <ul class="Presenters-list">
      <li class="Presenters-item">
        <div class="Presenter">
          <figure class="Presenter-item">
            <img :src="stevenImage" class="Presenter-image">
          </figure>
          <h1>Steven Adams</h1>
          <!-- <p>UI Engineer</p> -->
          <p>@steven_adams</p>
        </div>
      </li>
      <li class="Presenters-item">
        <div class="Presenter">
          <figure class="Presenter-item">
            <img :src="leeImage" class="Presenter-image">
          </figure>
          <h1>Lee Campbell</h1>
          <!-- <p>UI Engineer</p> -->
          <!-- <p>@steven_adams</p> -->
        </div>
      </li>
    </ul>

  </section>
</template>
<style lang="scss" scoped src="./Presenters.scss"></style>
<script>
import stevenImage from './img/steven-adams.png'
import leeImage from './img/lee-campbell.jpg'
export default {
  data () {
    return {
      stevenImage: stevenImage,
      leeImage: leeImage
    }
  }
}
</script>
