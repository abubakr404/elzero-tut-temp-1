<script setup>
import Service from "./section-components/Service.vue";
</script>
<template>
  <section class="services" id="services">
    <div class="container">
      <div class="big-header">
        <h2>services</h2>
        <p>Don't be busy, be productive</p>
      </div>
      <div class="content">
        <div class="col">
          <Service>
            <template #icon><i class="fa-solid fa-palette fa-2x"></i></template>
            <template #serv-title>Graphic Design</template>
            <template #serv-text
              >Graphic design is the process of visual communication and
              problem-solving using one or more of typography, photography and
              illustration.</template
            >
          </Service>
          <Service>
            <template #icon><i class="fa-brands fa-sketch fa-2x"></i></template>
            <template #serv-title>UI & UX</template>
            <template #serv-text
              >Process of enhancing user satisfaction with a product by
              improving the usability, accessibility, and pleasure provided in
              the interaction.</template
            >
          </Service>
        </div>
        <div class="col">
          <Service>
            <template #icon
              ><i class="fa-solid fa-vector-square fa-2x"></i
            ></template>
            <template #serv-title>Web Design</template>
            <template #serv-text
              >Web design encompasses many different skills and disciplines in
              the production and maintenance of websites.</template
            >
          </Service>
          <Service>
            <template #icon
              ><i class="fa-solid fa-pen-ruler fa-2x"></i
            ></template>
            <template #serv-title>Web Development</template>
            <template #serv-text
              >Web development is a broad term for the work involved in
              developing a web site for the Internet or an intranet.</template
            >
          </Service>
        </div>
        <div class="col">
          <div class="image">
            <img src="../../assets/images/services.jpg" alt="" />
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
