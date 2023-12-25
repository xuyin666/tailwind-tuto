<template>
  <main className="relative">
    <Nav />
    <section className="xl:padding-l wide:padding-r padding-b">
      <Hero />
    </section>
    <section className="padding">
      <PopularProducts />
    </section>
    <section className="padding">
      <SuperQuality />
    </section>
    <section className="padding-x py-10">
      <Services />
    </section>
    <section className="padding">
      <SpecialOffer />
    </section>
    <section className="bg-pale-blue padding">
      <CustomerReviews />
    </section>
    <section className="padding-x sm:py-32 py-16 w-full">
      <Subscribe />
    </section>
    <section className="bg-black padding-x padding-t pb-8">
      <Footer />
    </section>
  </main>
</template>

<script>
import Hero from './sections/Hero.vue';
import Footer from './sections/Footer.vue';
import CustomerReviews from './sections/CustomerReviews.vue';
import PopularProducts from './sections/PopularProducts.vue';
import Services from './sections/Services.vue';
import SpecialOffer from './sections/SpecialOffer.vue';
import Subscribe from './sections/Subscribe.vue';
import SuperQuality from './sections/SuperQuality.vue';
import Nav from './components/Nav.vue'

export default {
  components: {
    Nav,
    Hero,
    PopularProducts,
    Footer,
    CustomerReviews,
    Services,
    SpecialOffer,
    Subscribe,
    SuperQuality
  }
}

</script>