<script>
import {
  SendIcon,
  MailIcon,
  LinkIcon,
  PhoneCallIcon,
  ClockIcon,
  MapPinIcon
} from "vue-feather-icons";
export default {
  components: {
    SendIcon,
    MailIcon,
    LinkIcon,
    PhoneCallIcon,
    ClockIcon,
    MapPinIcon
  }
};
</script>
<template>
  <!-- Contact Us Start -->
  <section class="section bg-light" id="contact">
    <div class="container">
      <div v-scrollanimation class="row justify-content-center">
        <div class="col-lg-6">
          <div class="text-center mb-5">
            <h3 class="title mb-3">Contact Us</h3>
            <p class="text-muted font-size-15">
              If you have questions or just want to get in touch, use the form in the left. We look forward to hearing from you!
            </p>
          </div>
        </div>
      </div>
      <div v-scrollanimation class="row align-items-center">
        <div class="col-lg-7">
          <div class="custom-form mb-5 mb-lg-0">
            <div id="message"></div>
            <form name="contact-form" id="contact-form">
              <div class="row">
                <div class="col-md-6">
                  <div class="form-group">
                    <label for="name">Name*</label>
                    <input id="name" type="text" class="form-control" placeholder="Your name..." />
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="form-group">
                    <label for="email">Email Address*</label>
                    <input id="email" type="email" class="form-control" placeholder="Your email..." />
                  </div>
                </div>
              </div>
              <div class="row">
                <div class="col-lg-12">
                  <div class="form-group">
                    <label for="comments">Message*</label>
                    <textarea
                      id="comments"
                      rows="4"
                      class="form-control"
                      placeholder="Your message..."
                    ></textarea>
                  </div>
                </div>
              </div>
              <div class="row">
                <div class="col-sm-12">
                  <button type="button" class="btn btn-primary">
                    Send Message
                    <send-icon class="icon-size-15 ml-2 icon"></send-icon>
                  </button>
                  <div id="simple-msg"></div>
                </div>
              </div>
            </form>
          </div>
        </div>
        <div v-scrollanimation class="col-lg-5">
          <div class="contact-detail text-muted ml-lg-5">
            <ul>
              <li>
                <span>info@paramatech.id</span>
              </li>
              <li>
                <span>021 2283 6003</span>
              </li>
              <li>
                <span>Office 88 Kasablanka Tower A Lt. 9 Unit C, Jl. Casablanca No. Kav 88, Jakarta Selatan, 12870</span>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- Contact Us End -->
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