<template>
  <section id="cart_items">
    <div class="container">
      <div class="shopper-informations">
        <div class="row">
          <div class="col-sm-5">
            <div class="shopper-info">
              <p>Track order</p>

              <form @submit.prevent="track()">
                <input type="text" placeholder="Email" readonly name="email" />
                <input
                  type="text"
                  placeholder="Track id"
                  name="trackid"
                  required
                />
                <button class="btn btn-primary" type="submit">Submit</button>
              </form>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Tracking",
  data() {
    return {};
  },
  methods: {
    track() {},
  },
};
</script>

<style></style>
