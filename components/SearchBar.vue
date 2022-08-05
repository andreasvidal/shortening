<template>
<nav class="navbar d-flex justify-content-center space-top">
  <form class="form-inline">
    <input class="form-control mr-sm-3 size-place" type="search" placeholder="Shorten a link Here..." aria-label="Search">
    <button class="btn my-2 my-sm-0 bg-color" type="submit">Shorten it</button>
  </form>
</nav>
</template>

<script>
export default {

}
</script>

<style>
.space-top{
  margin-top: 5rem;
  background-color: hsl(257, 27%, 26%);
  border-radius: 0.6rem;
  margin: 3rem 6rem;
  background-image: url(../images/bg-shorten-desktop.svg);
}
.bg-color{

 background-color: hsl(180, 66%, 49%);
 color: hsl(0, 0%, 100%);
 border-radius: 0.6rem;
 font-weight: bold;
}

.size-place{
  border-radius: 0.6rem;
  padding-right: 20rem;
  margin: 1rem auto;
}
</style>
