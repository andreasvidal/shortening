<template>
<div>
<nav class="navbar navbar-expand-lg  mt-4">
  <a class="color-txt-dv navbar-brand ml-4 font-weight-bold" href="#"><img src="../images/logo.svg" alt="" srcset=""></a>
  <button class="navbar-toggler btn btn-primary" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon color-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto">
      <li class="nav-item">
        <a class="nav-link font-weight-bold color-txt-gray ml-2" href="#">Features</a>
      </li>
      <li class="nav-item">
        <a class="nav-link font-weight-bold color-txt-gray ml-2" href="#">Pricing</a>
      </li>
      <li class="nav-item">
        <a class="nav-link font-weight-bold color-txt-gray ml-2" href="#">Resources</a>
      </li>
    </ul>
    <form class="form-inline mr-4 my-lg-0">
      <button class="btn  m-2 my-sm-0 font-weight-bold color-txt-gray" type="submit">Login</button>
      <button class="btn  m-2 my-sm-0 bg-color-menu font-weight-bold" type="submit">Sing Up</button>
    </form>
  </div>
</nav>
</div>
</template>

<script>
export default {

}
</script>

<style>
.bg-color-menu{
 background-color: hsl(180, 66%, 49%);
 color: hsl(0, 0%, 100%);
 border-radius: 3rem ;
 padding: 0.5rem 1.5rem;
}
.color-txt-gray{
  color: hsl(0, 0%, 75%);
}
 .navbar-brand {
  color: hsl(260, 8%, 14%) !important;
  font-weight: 700;
}

.color-icon{
  color: blue;
  background-color: blueviolet;
}
</style>
