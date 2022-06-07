<template>
  <!-- Navbar -->
  <MDBNavbar expand="lg" dark bg="dark" container>
    <MDBNavbarBrand href="#">Andrew Gavgavian</MDBNavbarBrand>
    <MDBNavbarToggler target="#navbarExample01"></MDBNavbarToggler>
    <MDBNavbarNav collapse="navbarExample01" class="mb-2 mb-lg-0">
      <MDBNavbarItem to="#" active> Home </MDBNavbarItem>
    </MDBNavbarNav>
  </MDBNavbar>
  <!-- Navbar -->
</template>
<script>
import {
  MDBNavbar,
  MDBNavbarToggler,
  MDBNavbarNav,
  MDBNavbarItem,
  MDBNavbarBrand,
} from "mdb-vue-ui-kit";
export default {
  name: "HeaderBar",
  components: {
    MDBNavbar,
    MDBNavbarToggler,
    MDBNavbarNav,
    MDBNavbarItem,
    MDBNavbarBrand,
  },
};
</script>

<style></style>
