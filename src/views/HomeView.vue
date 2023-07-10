<template>
  <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
    <div class="carousel-indicators">
      <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active"
        aria-current="true" aria-label="Slide 1"></button>
      <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1"
        aria-label="Slide 2"></button>
      <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2"
        aria-label="Slide 3"></button>
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
    <h3 class="heading">Norsemen Hauling</h3>
    <h5 class="title">What we do</h5>
    <ul class="services">
      <li>Junk Removal</li>
      <li>House, Estate, Rental & Hoarding Cleanouts</li>
      <li>Light Demolition</li>
      <li>Interior Painting</li>
      <li>Hauling Services</li>
      <li>Storm & Yard Waste Removal</li>
    </ul>
  </section>
</template>

<style scoped>
#CarImg {
  height: 80vh;
  width: 100%;
  object-fit: scale-down;
}

.carousel {
  background-color: rgb(30, 30, 30);
}

.heading,
.title {
  text-transform: uppercase;
  letter-spacing: .65rem;
  text-align: center;
  margin: 0;
}

.title {
  padding: 10px;
}

.heading {
  padding: 25px;
}

.services {
  list-style: none;
  text-align: center;
  letter-spacing: .3rem;
  padding: 0;
}
</style>