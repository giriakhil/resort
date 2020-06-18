<template>
  <div class="hero is-fullheight">
    <div class="columns">
      <div class="column">
        <div class="button  is-info">
          STAY
        </div>
      </div>
      <div class="column">
        <div class="button  is-info">
          DINE
        </div>
      </div>
      <div class="column">
         <div class="button is-info">
          EVENTS
        </div>
      </div>
      <div class="column">
         <div class="button is-info">
          FACILITIES
        </div>
      </div>
    </div>
    <div class="container">
      <div class="row">
        <div class="column">
          <img src="@/assets/1.jpg" alt="">
        </div>
        <div class="column">
          <img src="@/assets/2.jpg" alt="">
        </div>
        <div class="column">
           <img src="@/assets/3.jpg" alt="">
        </div>
      </div>
      <div class="row">
        <div class="column">
          <img src="@/assets/6.jpg" alt="">
        </div>
        <div class="column">
          <img src="@/assets/5.jpg" alt="">
        </div>
        <div class="column">
           <img src="@/assets/8.jpg" alt="">
        </div>
      </div>
      <div class="row">
        <div class="column">
          <img src="@/assets/8.jpg" alt="">
        </div>
        <div class="column">
          <img src="@/assets/9.jpg" alt="">
        </div>
        <div class="column">
           <img src="@/assets/1.jpg" alt="">
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Gallery',
};
</script>

<style>
.row {
  display: flex;
  flex-direction: row;
  align-items: center;
}

</style>
