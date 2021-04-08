<template>
  <div class="about">
    <h1>This is an about page</h1>
    <div class="slider">
      $(".slider").slick({ // normal options... infinite: false, // the magic responsive: [{ breakpoint: 1024, settings:
      { slidesToShow: 3, infinite: true } }, { breakpoint: 600, settings: { slidesToShow: 2, dots: true } }, {
      breakpoint: 300, settings: "unslick" // destroys slick }] });
    </div>
  </div>
</template>
<script>
$(document).ready(function(){
  $('.your-class').slick({
    setting-name: setting-value
  });
});
</script>
