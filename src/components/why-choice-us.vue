<template>
  <!-- Pricing Start -->
  <section class="section bg-light" id="why-choice">
    <div v-scrollanimation class="container">
      <div class="row justify-content-center">
        <div class="col-lg-6">
          <div class="text-center mb-5">
            <h3 class="title mb-3">Why Choose Paramatech?</h3>

          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-lg-4">
          <div class="why-box rounded text-center p-4">
            <div class="why-icon-bg my-4">
              <img src="@/assets/images/hand.png" alt class="img-fluid d-block mx-auto" />
            </div>
            <h4 class="title mb-3">We Help Solve Your Business Problems</h4>
            <p class="text-muted font-weight-semibold">We sit on the same side of the table as you to provide business solutions to business problems, listen to your business problem and offer several strategies to resolve the root of the problem and achieve your objectives.</p>
            <div class="mt-4">
              <div class="hero-bottom-img">
                <img
                    src="@/assets/images/pricing-bottom-bg.png"
                    alt
                    class="img-fluid d-block mx-auto"
                />
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-4">
          <div class="why-box rounded text-center p-4">
            <div class="why-icon-bg my-4">
<!--              <i class="mdi mdi-thumb-up h1"></i>-->
              <img src="@/assets/images/thumbs-up.png" alt class="img-fluid d-block mx-auto" />
            </div>
            <h4 class="title mb-3">Committed to Quality</h4>
            <p class="text-muted font-weight-semibold">It takes teamwork and a solid commitment to good communication, excellence, and industry best practices to serve  companies in an excellent manner.</p>
            <div class="mt-4">
              <div class="hero-bottom-img">
                <img
                    src="@/assets/images/pricing-bottom-bg.png"
                    alt
                    class="img-fluid d-block mx-auto"
                />
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-4">
          <div class="why-box rounded text-center p-4">
            <div class="why-icon-bg my-4">
              <img src="@/assets/images/medal.png" alt class="img-fluid d-block mx-auto" />
            </div>
            <h4 class="title mb-3">Satisfaction Guaranteed</h4>
            <p class="text-muted font-weight-semibold">We want you to be completely satisfied with our services. We will do whatever it takes to meet your expectations.</p>
            <div class="mt-4">
              <div class="hero-bottom-img">
                <img
                    src="@/assets/images/pricing-bottom-bg.png"
                    alt
                    class="img-fluid d-block mx-auto"
                />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- Pricing End -->
</template>

<style lang="scss" scoped>

.before-enter{
  opacity: 0;
  transform: translateY(200px);
  transition: all 2s ease;
}

.enter{
  opacity: 1;
  transform: translateY(0px);
}

</style>