<script>
export default {
  name: "AppHeader",
  data() {
    return {
      menuItems: [
        {
          label: "Home",
          routeName: "Home",
        },
      ],
    };
  },
};
</script>

<template lang="">
  <nav
    class="navbar bg-dark border-bottom border-body navbar-expand-lg bg-body-tertiary sticky-top"
    data-bs-theme="dark"
  >
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Portfolio</a>
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
      <div
        class="collapse navbar-collapse justify-content-end"
        id="navbarSupportedContent"
      >
        <ul class="navbar-nav ms-auto me-5 mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#about">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#project">Projects</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#contact">Contacts</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<style lang="scss">
@media only screen and (min-width: 992px) {
  .navbar {
    height: 70px;
  }
}
</style>
