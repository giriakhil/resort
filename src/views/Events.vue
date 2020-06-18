<template>
  <div class="hero is-fullheight">
   <div class="box">
     <div class="columns">
       <div class="column is-5">
         <img src="@/assets/convection.jpg" alt="">
       </div>
       <div class="column is-7">
         <div class="title is-size-4">CONVENTION CENTRE</div>
         <p class="text">
           Located on the ground floor with collapsible partitions,
           which can be joined into one big space for your events, the
           Iris 1, 2 & 3 Halls are the perfect
           choice from huge conventions to private get-togethers.
          </p>
          <strong class="pa-1">Size : 12900 square feet | 1200 Square Metres</strong>
          <strong class="pa-1">Seating Capacity : 300 - 1500</strong>
          <div class="title is-size-4">
            AMENITIES
          </div>
          <div class="level">
            <div class="level-left">
                <div class="text">
                  <h1>wifi</h1>
                  <h1>projectors</h1>
                  <h1>sound systems</h1>
                </div>
            </div>
            <div class="level-right">
              <div class="level-item">
                <div id="button" class="button is-rounded is-link">
                  Enquire Now
                </div>
              </div>
            </div>
          </div>
       </div>
     </div>
   </div>
   <div id="card-color" class="box">
     <div class="columns">
       <div class="column is-5">
         <img src="@/assets/wedding.jpg" alt="">
       </div>
       <div class="column is-7">
         <div class="title is-size-4">Weddings</div>
         <p class="text">
           Located on the ground floor with collapsible partitions,
           which can be joined into one big space for your events, the
           Iris 1, 2 & 3 Halls are the perfect
           choice from huge conventions to private get-togethers.
          </p>
          <strong class="pa-1">Size : 12900 square feet | 1200 Square Metres</strong>
          <strong class="pa-1">Seating Capacity : 300 - 1500</strong>
          <div class="title is-size-4">
            AMENITIES
          </div>
          <div class="level">
            <div class="level-left">
                <div class="text">
                  <h1>wifi</h1>
                  <h1>projectors</h1>
                  <h1>sound systems</h1>
                </div>
            </div>
            <div class="level-right">
              <div class="level-item">
                <div id="button" class="button is-rounded is-link">
                  Enquire Now
                </div>
              </div>
            </div>
          </div>
       </div>
     </div>
   </div>
   <div class="box">
     <div class="columns">
       <div class="column is-5">
         <img src="@/assets/board.jpg" alt="">
       </div>
       <div class="column is-7">
         <div class="title is-size-4">THE BOARD ROOM</div>
         <p class="text">
           Located on the ground floor with collapsible partitions,
           which can be joined into one big space for your events, the
           Iris 1, 2 & 3 Halls are the perfect
           choice from huge conventions to private get-togethers.
          </p>
          <strong class="pa-1">Size : 12900 square feet | 1200 Square Metres</strong>
          <strong class="pa-1">Seating Capacity : 300 - 1500</strong>
          <div class="title is-size-4">
            AMENITIES
          </div>
          <div class="level">
            <div class="level-left">
                <div class="text">
                  <h1>wifi</h1>
                  <h1>projectors</h1>
                  <h1>sound systems</h1>
                </div>
            </div>
            <div class="level-right">
              <div class="level-item">
                <div id="button" class="button is-rounded is-link">
                  Enquire Now
                </div>
              </div>
            </div>
          </div>
       </div>
     </div>
   </div>
  </div>
</template>

<script>
export default {
  name: 'Events',
};
</script>

<style lang="scss" scoped>

img {
  padding-top: 3vh;
}
#card-color {
  background: lightgrey;
}
.box {
  padding-top: 5vh;
}
.text {
  text-align: justify;
}
.title {
  display: flex;
  flex-direction: row;
  align-items: flex-start;
  color: grey;
  padding-top: 2vh;
}
.pa-1 {
  padding-top: 2vh;
  display: flex;
   flex-direction: row;
  align-items: flex-start;
}
</style>
