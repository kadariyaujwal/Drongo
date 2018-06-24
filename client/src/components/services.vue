<template>
<div id="services" class="w-100  sidebar">
  <div class="container">
    <div class="card bg-color-black" style="height:30px;margin-bottom:10px">
      <p style="color:white;">Services</p>
    </div>
    <!-- service card is repeated -->
    <div class="scrollable">
    <!-- First service card start-->
    <div class="card service-card" style="background-color:#415064">
        <div class="row">
          <div class="text-left col-md-10">
            <h4 class="card-title color-white">Payment service</h4>
          </div>
          <div class="text-right col-md-2">
            <button type="button" class="close color-white" aria-label="Close">
            <span aria-hidden="true">&times;</span>
        </button>
          </div>
        </div>

        <h1 class="text-left color-orange">46</h1>
        <div class="row">
          <p class="text-left col-md-5 color-white">Now serving</p>
          <a href="#" class="link-green w-25 h-25">Open</a>
          <a href="#" class="link-orange w-25 h-25">Close</a>
        </div>
    </div>
    <!-- End of first service card -->
    <!-- Start of second service card -->
    <div class="card service-card" style="background-color:#415064">
        <div class="row">
          <div class="text-left col-md-10">
            <h4 class="card-title color-white">Payment service</h4>
          </div>
          <div class="text-right col-md-2">
            <button type="button" class="close color-white" aria-label="Close">
            <span aria-hidden="true">&times;</span>
        </button>
          </div>
        </div>

        <h1 class="text-left color-orange">46</h1>
        <div class="row">
          <p class="text-left col-md-5 color-white">Now serving</p>
          <a href="#" class="link-green w-25 h-25">Open</a>
          <a href="#" class="link-orange w-25 h-25">Close</a>
        </div>
    </div>
    <!-- End second service card -->
  </div>
  <!-- Scrollable end -->
  </div>

</div>
</template>
<script>
export default {
  name: "Services",
  data: () => ({

  })
}
</script>
<style>

</style>
