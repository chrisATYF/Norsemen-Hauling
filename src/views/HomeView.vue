<script setup>
import Intro from '../components/Introduction.vue';
</script>

<template>
  <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
    <div class="carousel-indicators">
      <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active"
        aria-current="true" aria-label="Slide 1"></button>
      <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1"
        aria-label="Slide 2"></button>
      <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2"
        aria-label="Slide 3"></button>
      <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="3"
        aria-label="Slide 4"></button>
      <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="4"
        aria-label="Slide 5"></button>
    </div>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="../../images/Jackhammer.jpg" id="CarImg" class="d-block w-100" alt="...">
      </div>
      <div class="carousel-item">
        <img src="../../images/OutsideHouse.jpg" id="CarImg" class="d-block w-100" alt="...">
      </div>
      <div class="carousel-item">
        <img src="../../images/Trailer.jpg" id="CarImg" class="d-block w-100" alt="...">
      </div>
      <div class="carousel-item">
        <img src="../../images/NoahWork.jpg" id="CarImg" class="d-block w-100" alt="...">
      </div>
      <div class="carousel-item">
        <img src="../../images/Shieldmaidens.jpg" id="CarImg" class="d-block w-100" alt="...">
      </div>
    </div>
    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div>
  <section>
    <Intro></Intro>
  </section>
  <section class="dark-section">
    <p>
      Therefore God also has highly exalted Him and given Him the name which is above every name, that at the name
      of Jesus every knee should bow, of those in heaven, and of those on earth, and of those under the earth, and
      that every tongue should confess that Jesus Christ is Lord, to the glory of God the Father.
    </p>
    <span>Philippians 2: 9-11</span>
  </section>
</template>

<style scoped>
#CarImg {
  height: 80vh;
  width: 100%;
  object-fit: scale-down;
}

.carousel {
  background-color: var(--darkBg);
  animation: fade-in .5s;
}

section {
  text-align: center;
  padding: 100px 20px;
}

.dark-section {
  background-color: var(--darkBg);
  color: rgb(226, 226, 226);
}

p {
  letter-spacing: .5px;
  font-size: 25px;
}

@keyframes fade-in {
  0% {
    opacity: 0;
    transform: translateY(50px);
  }

  100% {
    opacity: 1;
    transform: translate(0px);
  }
}

@media (max-width: 768px) {
  section {
    padding: 50px 10px;
  }
}
</style>