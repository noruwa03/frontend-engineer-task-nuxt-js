<template>
  <header class="">
    <!-- Image Logo -->
    <div class="img-logo">
      <a href="">
        <img src="@/assets/images/logo-real.svg" alt="alternative" />
        <span class="fw-bold ms-2">Untitle UI</span>
      </a>
    </div>

    <!-- Text Logo - Use this if you don't have a graphic logo -->
    <!-- <a class="navbar-brand logo-text" href="index.html">Your Site Name</a> -->

    <div class="nav-row mt-2">
      <nav>
        <ul>
          <li><a href="">Home</a></li>
          <li><a href="">Dashboard</a></li>
          <li><a href="">Projects</a></li>
          <li><a href="">Tasks</a></li>
          <li><a href="">Reporting</a></li>
          <li><a href="">Users</a></li>
        </ul>
      </nav>
    </div>

    <div class="nav-end">
      <a href="" class="upgrade-now">
        <img src="@/assets/images/flash.svg" class="img-fluid me-1" alt="" />
        Upgrade now</a
      >
      <i class="bi bi-gear"></i>
      <i class="bi bi-bell"></i>
      <!-- User avatar -->
      <div
        class="user"
        type="button"
        id="dropdownMenuButton1"
        data-bs-toggle="dropdown"
        aria-expanded="false"
      >
        <img src="@/assets/images/img-1.jpg" alt="" />
      </div>
      <ul class="dropdown-menu" aria-labelledby="dropdownMenuButton1">
        <li>
          <a class="dropdown-item"><span class="name">Obaseki Noruwa</span></a>
        </li>
        <li>
          <a class="dropdown-item"
            ><span class="email">noruwaobaseki@gmail.com</span></a
          >
        </li>
        <div class="dropdown-divider"></div>
        <li>
          <a class="dropdown-item"
            >Logout <i class="bi bi-box-arrow-in-right"></i
          ></a>
        </li>
      </ul>

      <!-- end of user avatar -->
    </div>
  </header>
</template>

<script>
export default {
  
}
</script>

<style>
</style>