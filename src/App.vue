<script>
import Card from "./components/Card";
import Footer from "./components/Footer";
import Form from "./components/Form";
import Header from "./components/Header";
import Hero from "./components/Hero";
import Navigation from "./components/Navigation";

export default {
  name: "app",
  components: {
    Card,
    Footer,
    Form,
    Header,
    Hero,
    Navigation
  }
};
</script>

<template>
  <fragment>
    <Header />

    <Navigation />

    <Hero />

    <main class="container">
      <div class="row">
        <Card v-for="index in 3" :key="index" type="card--vertical flex--column" />
      </div>

      <div class="row row--two-columns">
        <Card v-for="index in 2" :key="index" type="card--horizontal flex--row" />
      </div>

       <Form />
    </main>
    
    <Footer />
  </fragment>
</template>
