<script>
import {
  LayoutIcon,
  LifeBuoyIcon,
  ServerIcon,
  RssIcon
} from "vue-feather-icons";
export default {
  components: { LayoutIcon, LifeBuoyIcon, ServerIcon, RssIcon }
};
</script>

<template>
  <div>
    <!-- Features Start -->
    <section class="section bg-light feather-bg-img"
             :style="{'background-image': 'url(' + require('@/assets/images/features-bg-img.png') + ')'}"
             id="product" >
      <div class="container">
        <div class="row justify-content-center">
          <div class="col-lg-6">
            <div class="text-center mb-5">
              <h3 class="title mb-3">Our Product</h3>
            </div>
          </div>
        </div>

        <div class="row align-items-center justify-content-center">

          <div class="col-lg-4">
            <div v-scrollanimation class="product-box rounded text-left p-5">
              <div class="row">
                <div class="mb-4 mb-lg-0 img-product">
                  <img src="@/assets/images/content/manage-service.png" alt class="img-fluid d-block mx-auto" />
                </div>
              </div>
              <div class="row">
                <h3 class="font-weight-semibold line-height-1_4 mb-4">
                  <b>Manage Services</b>
                </h3>
                <p class="text-muted font-size-15 mb-4">
                  To support customer objectives in Managed Services & Outsourcing with or without IT.
                </p>
              </div>
              <div class="row">
                <button type="submit" class="btn btn-primary product-btn" v-b-modal.manage-modal>See Detail</button>
              </div>
            </div>
          </div>
          <div class="col-lg-4">
            <div v-scrollanimation class="product-box rounded text-left p-5">
              <div class="row">
                <div class="mb-4 mb-lg-0 img-product">
                  <img src="@/assets/images/content/infra.png" alt class="img-fluid mx-auto mt-4" />
                </div>
              </div>
              <div class="row tex">
                <h3 class="font-weight-semibold line-height-1_4 mb-4">
                  <b>Infrastructure</b>
                </h3>
                <p class="text-muted font-size-15 mb-4">
                  Network Solution and Cable System Infrastructure for our customer.
                </p>
              </div>
              <div class="row">
                <button type="submit" class="btn btn-primary product-btn" v-b-modal.infra-modal>See Detail</button>
              </div>
            </div>
          </div>
          <div class="col-lg-4">
            <div v-scrollanimation class="product-box rounded text-left p-5">
              <div class="row">
                <div class="mb-4 mb-lg-0 img-product">
                  <img src="@/assets/images/content/apps.png" alt class="img-fluid d-block mx-auto" />
                </div>
              </div>
              <div class="row">
                <h3 class="font-weight-semibold line-height-1_4 mb-4">
                  <b>Application</b>
                </h3>
                <p class="text-muted font-size-15 mb-4">
                  From the development of new applications, through modernization, management and maintenance, we cover all stages of the application lifecycle.
                </p>
              </div>
              <div class="row">
                <button type="submit" class="btn btn-primary product-btn" v-b-modal.app-modal>See Detail</button>
              </div>
            </div>
          </div>
<!--          <div class="col-lg-4">
            <div v-scrollanimation class="product-box rounded text-left p-5">

              <div class="row">
                <div class="mb-4 mb-lg-0">
                  <img src="@/assets/images/features-img.png" alt class="img-fluid d-block mx-auto" />
                </div>
              </div>

              <div class="row">

                <h3 class="font-weight-semibold line-height-1_4 mb-4">
                  <b>Manage Services</b>
                </h3>
                <p class="text-muted font-size-15 mb-4">
                  To support customer objectives in Managed Services & Outsourcing with or without IT.
                </p>
              </div>
            </div>
          </div>
          <div class="col-lg-4">
            <div v-scrollanimation class="product-box rounded text-left p-5">

              <div class="row">
                <div class="mb-4 mb-lg-0">
                  <img src="@/assets/images/features-img.png" alt class="img-fluid d-block mx-auto" />
                </div>
              </div>

              <div class="row">

                <h3 class="font-weight-semibold line-height-1_4 mb-4">
                  <b>Manage Services</b>
                </h3>
                <p class="text-muted font-size-15 mb-4">
                  To support customer objectives in Managed Services & Outsourcing with or without IT.
                </p>
              </div>
            </div>
          </div>
          <div class="col-lg-4">
            <div v-scrollanimation class="product-box rounded text-left p-5">

              <div class="row">
                <div class="mb-4 mb-lg-0">
                  <img src="@/assets/images/features-img.png" alt class="img-fluid d-block mx-auto" />
                </div>
              </div>

              <div class="row">

                <h3 class="font-weight-semibold line-height-1_4 mb-4">
                  <b>Manage Services</b>
                </h3>
                <p class="text-muted font-size-15 mb-4">
                  To support customer objectives in Managed Services & Outsourcing with or without IT.
                </p>
              </div>
            </div>
          </div>-->

          <b-modal id="manage-modal" title="Paramatech Product" hide-footer centered>
            <div class="text-center">
              <h3 class="title mb-4">Manage Services</h3>
              <div class="text-center">
                <p class="title mb-4">To Support customer objectives in Managed Services & Outsourcing</p>
                <ul class="text-left">
                  <li>Reduce & control operating cost</li>
                  <li>Improve company focus</li>
                  <li>Gain access to 1st class company capabilities</li>
                  <li>Free internal resources for other purposes</li>
                  <li>Provide resources that are not available internally</li>
                  <li>Accelerate re-engineering benefits</li>
                  <li>Handle functions that are difficult to managed</li>
                </ul>
              </div>
            </div>



          </b-modal>
          <b-modal id="infra-modal" title="Paramatech Product" hide-footer centered>
            <div class="text-center">
              <h3 class="title mb-4">Infrastructure</h3>
              <div class="text-center">
                <p class="title mb-4">To Support customer objectives </p>
                <ul class="text-left">
                  <li>Reduce & control operating cost</li>
                  <li>Improve company focus</li>
                  <li>Gain access to 1st class company capabilities</li>
                  <li>Free internal resources for other purposes</li>
                  <li>Provide resources that are not available internally</li>
                  <li>Accelerate re-engineering benefits</li>
                  <li>Handle functions that are difficult to managed</li>
                </ul>
              </div>
            </div>



          </b-modal>
          <b-modal id="app-modal" title="Paramatech Product" hide-footer centered>
            <div class="text-center">
              <h3 class="title mb-4">Application</h3>
              <div class="text-center">
                <p class="title mb-4">To Support customer objectives in Making Application.</p>
                <ul class="text-left">
                  <li>Reduce & control operating cost</li>
                  <li>Improve company focus</li>
                  <li>Gain access to 1st class company capabilities</li>
                  <li>Free internal resources for other purposes</li>
                  <li>Provide resources that are not available internally</li>
                  <li>Accelerate re-engineering benefits</li>
                  <li>Handle functions that are difficult to managed</li>
                </ul>
              </div>
            </div>



          </b-modal>

        </div>
      </div>
    </section>
  </div>
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
