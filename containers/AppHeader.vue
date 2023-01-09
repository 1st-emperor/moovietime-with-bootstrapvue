<template>
  <div>
    <nav
      class="navbar navbar-expand-lg navbar-dark"
      style="background-color: #292e35"
    >
      <div class="container">
        <nuxt-link to="/">
          <b-img
            src="../assets/img/MoovieTime-Logo@2x.png"
            width="112px"
            height="31px"
          ></b-img>
        </nuxt-link>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <Autocomplete
          :data="[
            'Wonder Woman 1984',
            'Wonder Woman',
            'Wonder',
            'Wonder Woman: Bloodlines',
            'Wonder Park',
            'Wonder Boys',
          ]"
          v-model="query"
          class="ml-5 mr-5"
          style="width: 531px"
          placeholder="Find Moovie"
        />
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li
              class="nav-item active mr-2"
              v-b-popover.hover.bottom="hoverData"
            >
              <a class="nav-link" aria-current="page">
                <nuxt-link class="navbar-item-size" to="#">
                  <b-icon class="mr-1" icon="grid" font-scale="1"></b-icon>
                  Categories
                </nuxt-link>
              </a>
            </li>
            <li class="nav-item mr-2">
              <a class="nav-link">
                <nuxt-link class="navbar-item-size" to="/moovie">
                  Movies
                </nuxt-link>
              </a>
            </li>
            <li class="nav-item mr-2">
              <a class="nav-link">
                <nuxt-link class="navbar-item-size" to="#">
                  Tv Shows
                </nuxt-link>
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link">
                <nuxt-link class="navbar-item-size" to="/auth/login">
                  Login
                </nuxt-link>
              </a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
import Autocomplete from "vue-typeahead-bootstrap";

export default {
  name: "AppHeader",
  components: { Autocomplete },
  data() {
    return {
      query: "",
    };
  },
  computed: {
    hoverData() {
      // Both title and content specified as a function in this example
      // and will be called the each time the popover is opened
      return {
        html: true,
        title: () => {
          // Note this is called only when the popover is opened
          return "";
        },
        content: () => {
          // Note this is called only when the popover is opened
          return "<small>ACTION<br>ADVENTURE<br>ANIMATION<br>COMEDY<br>CRIME<br>DOCUMENTARY<br>DRAMA<br>FAMILY<br>FANTASY<br>HISTORY<br>HORROR</small>";
        },
      };
    },
  },
};
</script>

<style>
.navbar-item-size {
  text-transform: uppercase;
  color: #e5e5e5 !important;
  font-weight: 600;
  font-size: 14px;
  line-height: 17.07px;
}
</style>
