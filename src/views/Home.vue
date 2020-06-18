<template>
<div class="hero is-fullheight">
  <section class="hero  is-medium">
    <div class="hero-body image">
      <div class="container">
        <h1 class="title">
          A Five Star hotel
        </h1>
        <h2 class="subtitle">
          And we like to keep it that way!
        </h2>
      </div>
    </div>
  </section>
  <div class="container">
    <h1 class="title-1 is-size-3">WELCOME TO THE ABODE OF TRANQUILITY</h1>
    <p>
      Located just a few minutes from the city,
      The Golkonda Resorts & Spa offers you a chance to unwind,
      let go and embrace life itself. Nestled right next to the
      picturesque Osman Sagar, the space boasts of thirteen acres of
      outdoor spaces and
      lush greenery for you to get in touch with nature.
    </p>
    <p>
      The Golkonda Resorts & Spa is a perfect destination for family
      getaways, corporate conferences and weddings. The royal treatment
      on offer at Hyderabad’s only five star resort is
      complemented by the calming influence of the elements of nature.
    </p>
  </div>
  <div class="columns">
    <div class="column is-7">
      <img src="@/assets/4.jpg" alt="">
    </div>
    <div class="column is-5">
      <strong class="flex-1 is-info">Stay</strong>
      <p class="text-items">
        Every one of our 44 luxury villas and 24 premium rooms
        have been designed to your comfort and convenience. With
        Lush greens, swaying palms and serene pool views, every villa
        has its own private garden in the
        front with huge windows as if extending in to the landscape
      </p>
      <div class="pa-1">
        <button id="stay-button" class="button is-rounded is-info">
          book now
        </button>
      </div>
    </div>
  </div>
  <div id="col-background" class="columns">
    <div class="column is-5">
      <strong  class="flex-2 is-info">Dining</strong>
      <p class="text-items">
        Every one of our 44 luxury villas and 24 premium rooms
        have been designed to your comfort and convenience. With
        Lush greens, swaying palms and serene pool views, every villa
        has its own private garden in the
        front with huge windows as if extending in to the landscape
      </p>
      <div class="pa-1">
        <button id="dining-button" class="button is-rounded is-info">
          book now
        </button>
      </div>
    </div>
    <div class="column is-7">
      <img src="@/assets/dining.jpg" alt="">
    </div>
  </div>
  <div class="columns">
    <div class="column is-7">
      <img src="@/assets/spa.jpg" alt="">
    </div>
    <div class="column is-5">
      <strong class="flex-1 is-info">THE SPA</strong>
      <p class="text-items">
       Indulge and take your senses on a journey
       of relaxation and rejuvenation. An ethereal experience
       awaits with our traditional Thai therapies designed to put your mind
       at ease and help relieve the stress from your body.
      </p>
      <div class="pa-1">
        <button id="stay-button" class="button is-rounded is-info">
          book now
        </button>
      </div>
    </div>
  </div>
</div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home',
  components: {
  },
};
</script>

<style>
.image {
  background-image: url(../assets/background-image.jpg);
}
 .title {
   color: black;
 }
 .subtitle {
   color: black;
 }

 .title-1 {
   padding-top: 5vh;
 }
 .columns {
   padding-top: 5vh;
 }
 .flex-1 {
   display: flex;
   flex-direction: row;
   align-items: flex-start;
   color: blue;
 }
.flex-2 {
   display: flex;
   flex-direction: row;
   align-items: flex-end;
   color: blue;
 }
 .text-items {
   text-align: justify;
   padding-top: 3vh;
   padding-right: 3vh;
 }

 #col-background {
   background-color: lightgrey;
 }

 #stay-button {
   display: flex;
   flex-direction: row;
   align-items: flex-start;
 }

 .pa-1 {
   padding-top: 5vh;
 }

 #dining-button {
   display: flex;
   flex-direction: row;
   align-items: flex-end;
 }
</style>
