<template>
  <section class="sectionone">
  <div class="container">
    <p class="welcome-text">Welcome to my portfolio!</p>
    <p class="download-text">You can download application pdf here</p>
    <a href="#" class="download-button"><i class='bx bxs-cloud-download'></i> Download PDF</a>
    <a href="https://github.com/Hakkerikakkeri" target="_blank" class="download-button"><i class='bx bxl-github'></i> Look my projects</a>
  </div>
  </section>
  <p class="blog-starts">Welcome to my portfolio!</p>
  <section class="sectionthree">
    <div class="containertwo">
      <img class="my-img" src="https://backlight.dev/img/sessions/georges_gomes.jpg">
      <p class="my-name">Jani Kuusela</p>
      <p class="my-career">Frontend Developer</p>
      <i id="icons" class='bx bxl-html5' style='color:#ffa938'  ></i>
      <i id="icons" class='bx bxl-vuejs' style='color:#49ad74'  ></i>
      <i id="icons" class='bx bxl-tailwind-css' style='color:#499bad'  ></i>
      <i id="icons" class='bx bxl-typescript' style='color:#4981ad'  ></i>
    <div class="contact-area">
      <a href="#" class="my-contact"><i class='bx bxs-navigation' ></i> Contact</a>
    </div>
    </div>
    </section>
    <p class="blog-starts">Services</p>
    <section class="sectiontwo">
      <div class="service-box">
        <div class="box">
          <i id="service-icons" class='bx bx-code'></i>
          <p class="service-text">Web Developement</p>
        </div>
        <div class="box">
          <i id="service-icons" class='bx bx-code'></i>
          <p class="service-text">Web Desing/Brand</p>
        </div>
      </div>
    </section>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
