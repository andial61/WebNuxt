<template>
    <div>
        <div class="container-fluid pt-5 pb-5 kontak">
      <div class="container">
        <h2 class="display-3 text-center">Contact Us</h2>
        <p class="text-center">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Neque, porro.
        </p>
        <div class="row pb-3">
          <div class="col-md-6">
            <input
              class="form-control form-control-lg mb-3"
              type="text"
              placeholder="Name"
            />
            <input
              class="form-control form-control-lg mb-3"
              type="text"
              placeholder="Email"
            />
            <input
              class="form-control form-control-lg"
              type="text"
              placeholder="Phone Number"
            />
          </div>
          <div class="col-md-6">
            <textarea class="form-control form-control-lg" rows="5"></textarea>
          </div>
        </div>
        <div class="col-md-3 mx-auto text-center">
          <button type="button" class="btn btn-danger btn-lg">
            Send
          </button>
        </div>
      </div>
    </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
.kontak {
  background: url("https://wallpaperaccess.com/full/1867010.jpg") no-repeat
    center center;
  background-size: cover;
  padding-bottom: 20%;
  padding-top: 20%;
  color: #fff;
}
</style>