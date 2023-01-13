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
    <section
      class="section bg-light feather-bg-img"
      :style="{'background-image': 'url(' + require('@/assets/images/features-bg-img.png') + ')'}"
      id="about"
    >
      <div class="container">
        <div v-scrollanimation class="row justify-content-center">
          <div class="col-lg-6">
            <div class="text-center mb-5">
              <h3 class="title mb-3">About Us</h3>
            </div>
          </div>
        </div>

        <div v-scrollanimation class="row align-items-center">
          <div class="col-lg-6">
            <div class="mb-4 mb-lg-0">
              <img src="@/assets/images/features-img.png" alt class="img-fluid d-block mx-auto" />
            </div>
          </div>

          <div v-scrollanimation class="col-lg-5 offset-lg-1">
            <h3 class="font-weight-semibold line-height-1_4 mb-4">
              We are product thinkers who love building disruptive digital products and see our customers succeed.
            </h3>
            <p class="text-muted font-size-15 mb-4">
              Delivering specialized staff outsourcing services to all types of organizations, from startups to globally established brands. Our principal solution is to provide skilled professional staffs outsourced to companies in Indonesia to meet short, medium or long term hiring needs.
            </p>
          </div>
        </div>
      </div>
    </section>

    <section
      class="section feather-bg-img"
      :style="{'background-image': 'url(' + require('@/assets/images/features-bg-img-1.png') + ')'}"
    >
      <div class="container">
        <div class="row align-items-center">
          <div class="col-lg">
            <h3 v-scrollanimation class="font-weight-semibold line-height-1_4 mb-2">
              <b>Visi Kami</b>
            </h3>
            <!-- <h3 class="font-weight-semibold line-height-1_4 mb-4">Build <b>community</b> & <b>conversion</b> with our suite of <b>social tool</b></h3> -->
            <p v-scrollanimation class="text-muted font-size-15 mb-5">
              Diakui sebagai perusahaan penyedia jasa sumber daya manusia yang unggul dan berwawasan saling menguntungkan
            </p>
            <h3 v-scrollanimation  class="font-weight-semibold line-height-1_4 mb-2">
              <b>Misi Kami</b>
            </h3>
            <ul>
              <li v-scrollanimation class="text-muted font-size-15 mb-1">
                Terwujudnya Sumber Daya Manusia yang berkualitas.
              </li>
              <li v-scrollanimation class="text-muted font-size-15 mb-1">
                Meningkatkan profesionalisme tenaga kerja.
              </li>
              <li v-scrollanimation class="text-muted font-size-15 mb-1">
                Membentuk tenaga kerja yang inisiatif, inovatif dan kreatifitas yang tinggi.
              </li>
              <li v-scrollanimation class="text-muted font-size-15 mb-1">
                Membentuk kualitas Sumber Daya Manusia secara efektif dan efesien.
              </li>
              <li v-scrollanimation class="text-muted font-size-15 mb-1">
                Mengarahkan pekerjaan pada kepuasan pelanggan.
              </li>
              <li v-scrollanimation class="text-muted font-size-15 mb-1">
                Memberikan pelayanan kepada perusahaan dan masyarakat secara maksimal serta menjadi pioneer dalam kegiatan penempatan dan pengelolaan tenaga kerja yang profesional.
              </li>
            </ul>
          </div>
        </div>
      </div>
    </section>
    <!-- Features End -->
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