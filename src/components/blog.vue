<script>
import { CalendarIcon, UserIcon } from "vue-feather-icons";
export default {
  components: {
    CalendarIcon,
    UserIcon
  }
};
</script>
<template>
  <!-- Blog start -->
  <section class="section" id="blog">
    <div class="container">
      <div v-scrollanimation class="row justify-content-center">
        <div class="col-lg-6">
          <div class="text-center mb-5">
            <h3 class="title mb-3">Meet Our Team</h3>
          </div>
        </div>
      </div>

      <div class="row justify-content-center">
<!--        <div class="col-lg-4">
          <div v-scrollanimation class="blog-box mb-4 mb-lg-0">
            <img src="@/assets/images/blog/img-1.jpg" alt class="img-fluid d-block mx-auto rounded" />
            <h3 class="text-dark font-weight-bold h5 mt-4">Agnesia Vica Hardy</h3>
            <p class="text-muted font-size-15">Chief Executive Officer</p>
            <ul class="list-inline text-muted text-uppercase font-size-15 font-weight-medium mt-1 mb-2">
              <li class="list-inline-item mr-3">
                <i class="mdi mdi-linkedin h3"></i>
              </li>
              <li class="list-inline-item">
                <i class="mdi mdi-email-mark-as-unread h2"></i>
              </li>
            </ul>
          </div>
        </div>-->
        <div class="col-lg-4 ">
          <div v-scrollanimation class="blog-box mb-4 mb-lg-0">
            <img src="@/assets/images/team/vica.png" alt class="img-fluid d-block mx-auto rounded" />
            <h3 class="text-dark font-weight-bold h5 mt-4">Agnesia Vica Hardy</h3>
            <p class="text-muted font-size-15">Chief Executive Officer</p>
            <ul class="list-inline text-muted text-uppercase font-size-15 font-weight-medium mt-1 mb-2">
              <li class="list-inline-item mr-3">
                <a href="https://www.linkedin.com/in/agnesia-vica-hardy-b2794a93/" target="_blank"><i class="mdi mdi-linkedin h3"></i></a>
              </li>
              <li class="list-inline-item">
                <i class="mdi mdi-email-mark-as-unread h2"></i>
              </li>
            </ul>
          </div>
        </div>
<!--        <div class="col-lg-4">
          <div v-scrollanimation class="blog-box mb-4 mb-lg-0">
            <img src="@/assets/images/blog/img-1.jpg" alt class="img-fluid d-block mx-auto rounded" />
            <h3 class="text-dark font-weight-bold h5 mt-4">Agnesia Vica Hardy</h3>
            <p class="text-muted font-size-15">Chief Executive Officer</p>
            <ul class="list-inline text-muted text-uppercase font-size-15 font-weight-medium mt-1 mb-2">
              <li class="list-inline-item mr-3">
                <i class="mdi mdi-linkedin h3"></i>
              </li>
              <li class="list-inline-item">
                <i class="mdi mdi-email-mark-as-unread h2"></i>
              </li>
            </ul>
          </div>
        </div>-->
      </div>
    </div>
  </section>
  <!-- Blog End -->
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