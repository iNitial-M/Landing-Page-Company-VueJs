<script>
import Navbar from "@/components/navbar";
import Service from "@/components/services";
import Features from "@/components/features";
import Pricing from "@/components/pricing";
import Blog from "@/components/blog";
import Contact from "@/components/contact";
import Footer from "@/components/footer";
import Choice from "@/components/why-choice-us";
import AboutUs from "@/components/about-us";
import Product from "@/components/product";
import Whatsapp from "@/components/whatsapp";

/**
 * Index-6
 */
export default {
  components: { Navbar, Product, Service, Features, Choice, AboutUs, Pricing, Blog, Contact, Footer, Whatsapp },
  data() {
    return {
      navbarcolor: true
    };
  }
};
</script>

<template>
  <div>
    <Navbar :navbarcolor="this.navbarcolor" />
    <div v-scroll-spy>
      <!-- Hero Start -->
      <section
        class="hero-6-bg position-relative"
        :style="{'background-image': 'url(' + require('@/assets/images/hero-bg.jpg') + ')'}"
        id="home"
      >
        <div class="bg-overlay"></div>
        <div class="container" >
          <div class="row align-items-center justify-content-center">
            <div class="col-lg-7" >
              <h4 v-scrollanimation class="hero-1-title text-white font-weight-bold text-shadow">Your Future Solution</h4>
              <h2 v-scrollanimation class="hero-1-title text-white font-weight-bold text-shadow">PARAMATECH</h2>
              <div class="w-90 mb-5">
                <p v-scrollanimation class="text-white mb-5 pb-5 font-size-17">
                  Delivering specialized staff outsourcing services to all types of organizations, from startups to globally established brands.
                  <br>
                  Our principal solution is to provide skilled professional staffs outsourced to companies in Indonesia to meet short, medium or long term hiring needs.
                </p>
                <button v-scrollanimation href="javascript: void(0);"
                        v-scroll-to="{ el: '#features', offset: -2}" type="submit" class="btn btn-primary">Our Service</button>
              </div>
            </div>
            <div v-scrollanimation class="col-lg-5 col-md-5">
              <div class="mt-5 mt-lg-0">
                <img src="@/assets/images/hero/hero1.png" alt class="img-fluid d-block mx-auto" />
              </div>
            </div>
          </div>
        </div>
      </section>
      <!-- Hero End -->
      <Product />
      <Features />
      <Choice />
      <Pricing />
      <Service />
      <AboutUs />
      <Blog />
      <Whatsapp/>
      <Contact />
      <Footer />
    </div>
  </div>
</template>

<style lang="scss" scoped>

h4{

  transition-delay: .1s;
}

h2{

  transition-delay: .2s;
}

p{
    transition-delay: .3s;
}


    .before-enter{
      opacity: 0;
      transform: translateX(-100px);
      transition: all 2s cubic-bezier(.41,.01,.57,1.61);
    }

    .enter{
      opacity: 1;
      transform: translateX(0px);
    }

</style>