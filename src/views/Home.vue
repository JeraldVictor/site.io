<template>
  <transition>
    <div class="img">
      <div class="row">
      <div class="col thiscol">
        <div class="info">
          <h1>Jerald Victor B J</h1>
          <p> <span class="uperline">Bsc.</span>Computer Science</p>
          <p>VIT UNIVERSITY VELLORE</p>
        </div>
      </div>
      <div class="col text-center">
      </div>
    </div>
    <footer>
			&copy; Jerald Victor B J
		</footer>
    </div>
  </transition>
</template>

<style scoped>
.img{
  height: 92vh;
  background-image: url('/images/jerald victor b j.jpg');
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;
}
.uperline{
  text-decoration: overline;
}
.thiscol{
  height: 20em;
  position: relative
}
.info{
  color: white;
  text-align: center;
  margin: 0;
  position: absolute;
  top: 100%;
  left: 35%;
}
footer {
  position: fixed;
  left: 0;
  bottom: 0;
  width: 100%;
  background-color: white;
  color: black;
  text-align: center;
  padding: 10px;
}
</style>

