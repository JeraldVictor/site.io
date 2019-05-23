<template>
  <div>
    <nav class="">
      <ul class="nav justify-content-center">
        <router-link to="/" class="nav-item" tag="li" exact><a class="nav-link">Home</a></router-link>
        <router-link to="/about" class="nav-item" tag="li"><a class="nav-link">About</a></router-link>
        <router-link to="/skills" class="nav-item" tag="li"><a class="nav-link">Skills</a></router-link>
        <router-link to="/projects" class="nav-item" tag="li"><a class="nav-link">Projects</a></router-link>
        <router-link to="/resume" class="nav-item" tag="li"><a class="nav-link">Resume</a></router-link>
        <router-link to="/contact" class="nav-item" tag="li"><a class="nav-link">Contact</a></router-link>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
}
</script>

<style scoped>
nav{
  background: yellow;
  padding: 10px;
}
ul li a{
  color: black;
}
</style>
