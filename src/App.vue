<template>
  <div class="flex flex-col">
    <nav class="bg-white px-32 my-8">
      <div class="container flex flex-wrap justify-between items-center">
        <a class="logo flex items-center">
          <img :src="logoURL" alt="" srcset="" class="w-20 h-full" />
        </a>
        <div class="links hidden w-full md:block md:w-auto">
          <ul
            class="
              flex flex-col
              md:flex-row md:space-x-16 md:mt-0 md:text-2xl md:font-normal
              text-tblack
            "
          >
            <li><a href="block p-4 text-tblack">Home</a></li>
            <li><a href="">About</a></li>
            <li><a href="">Podcast</a></li>
            <li><a href="">Donate</a></li>
          </ul>
        </div>
        <div class="contact_us">
          <button class="bg-primary text-white text-3xl py-7 px-12 rounded-2xl font-semibold ">
            Contact Us
          </button>
        </div>
      </div>
    </nav>
    <main>
      <header class="box bg-blue-800">Hero Section</header>
      <section class="box bg-yellow-800"><h1>What is what</h1></section>
      <section class="box bg-yellow-500">Mission</section>
      <section class="box bg-blue-500">What we offer</section>
      <section class="box bg-blue-800">Why O what</section>
      <section class="box bg-yellow-800">Dont miss out</section>
      <section class="box bg-blue-500">Membership</section>
      <section class="box bg-yellow-800">Membership</section>
      <section class="box bg-blue-800">Our projects</section>
      <section class="box bg-green-800">be involved</section>
      <section class="box bg-gray-800">Join the community</section>
    </main>
    <footer class="bg-footer text-white">
      <div class="footer-top"></div>
      <div class="flex footer-bottom">
        <p class="flex items center">&copy;owhat</p>
        <p>Powered by 25designstudio</p>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: "App",
  components: {},
  data() {
    return {
      logoURL:
        "https://99designs-blog.imgix.net/blog/wp-content/uploads/2017/06/attachment_54890439.jpg?auto=format&q=60&fit=max&w=930",
    };
  },
};
</script>

<style>
.button {
  /* width: 14.9rem;
  height: 5.6rem;
  border-radius: 1rem;
  Padding: 1.7rem, 3rem, 1.7rem, 3rem; */
}
</style>
