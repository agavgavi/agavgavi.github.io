<template>
  <div
    id="intro-example"
    class="p-5 text-center bg-image"
    style="
      background-image: url('https://mdbootstrap.com/img/new/slides/041.webp');
    "
  >
    <div class="mask" style="background-color: rgba(0, 0, 0, 0.7)">
      <div class="d-flex justify-content-center align-items-center h-100">
        <div class="text-white">
          <h1 class="mb-3 header-text">Welcome</h1>
          <h5 class="mb-4 header-subtext">{{ message }}</h5>
          <MDBBtn
            lg
            tag="a"
            outline="primary"
            class="m-2"
            href="#"
            role="button"
            >Check It Out</MDBBtn
          >
        </div>
      </div>
    </div>
  </div>
  <!-- Background image -->
</template>

<script>
import { MDBBtn } from "mdb-vue-ui-kit";
export default {
  props: ["message"],
  name: "HeroComponent",
  components: { MDBBtn },
};
</script>

<style>
.header-subtext {
  color: #fff;
  display: table;
  margin: 0 auto 30px;
  padding: 0 15px 30px;
  font-size: 24px;
  border-bottom: 1px solid rgba(255, 255, 255, 0.1);
  letter-spacing: 5px;
  font-weight: 300;
  line-height: 1.1;
  text-align: center;
}
.header-text {
  margin: 0 auto;
  color: #fff;
  font-size: 76px;
  display: table;
  text-transform: uppercase;
  letter-spacing: 5px;
}
/* Default height for small devices */
#intro-example {
  height: 400px;
}

/* Height for devices larger than 992px */
@media (min-width: 992px) {
  #intro-example {
    height: 600px;
  }
}
</style>
