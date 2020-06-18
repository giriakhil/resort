<template>
  <div class="hero is-fullheight">
    <div class="columns">
      <div class="column is-half">
        <h1 class="text is-size-4">We'd like to hear from you!</h1>
        <strong class="text">
          Your Name
        </strong>
        <div class="pa-1">
          <input class="input is-rounded is-danger" type="text" placeholder="name">
        </div>
        <strong class="text">
          Email Address
        </strong>
        <div class="pa-1">
          <input class="input is-rounded is-danger" type="text" placeholder="Email">
        </div>
        <strong class="text">
          Mobile
        </strong>
        <div class="pa-1">
          <input class="input is-rounded is-danger" type="text" placeholder="number">
        </div>
        <strong class="text">
          Reason for contact
        </strong>
        <div class="pa-1">
          <input class="input is-rounded is-danger" type="text" placeholder="reason">
        </div>
        <strong class="text">
          How can we assist you?
        </strong>
        <div class="pa-1">
          <textarea class="textarea is-danger" placeholder=""></textarea>
        </div>
        <div class="pa-1">
          <button class="button is-rounded is-danger">
            submit
          </button>
        </div>
      </div>
      <div class="column is-half">
        <div class="text-1 is-size-5">
          Leonia Holistic Destination
        </div>
        <p class="address">Bommaraspet, Shameerpet,</p>
        <p  class="address">Hyderabad 500 078, India.</p>
        <div class="text-2">
          phone us: +91 123456789
        </div>
         <div class="text-2">
          email us: abc@gmail.com
        </div>
         <div class="text-2">
          like us: facebbok.com
        </div>
         <div class="text-1 is-size-5">
          corporate address
        </div>
         <p class="address">H. No 6-3-886, Beside My Home Hill View Apartments,</p>
        <p  class="address">
          Somajiguda Circle, Raj Bhavan Road
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Contact',
};
</script>

<style>

.text {
  display: flex;
  flex-direction: row;
  align-items: flex-start;
  padding-left: 5vh;
  padding-top:3vh;
}
.pa-1 {
  padding-left: 5vh;
  padding-top:2vh;
}

.text-1 {
  display: flex;
  flex-direction: row;
  align-items: flex-start;
  padding-left: 10vh;
  padding-top:10vh;
}
.address {
  display: flex;
  flex-direction: row;
  align-items: flex-start;
  padding-left: 10vh;
}
.text-2 {
  display: flex;
  flex-direction: row;
  align-items: flex-start;
  padding-left: 10vh;
   padding-top: 5vh;
}

</style>
