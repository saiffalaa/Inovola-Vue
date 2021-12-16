<template>
  <div className="section_space inner-space second-bg pe-4 d-flex">
    <div className="video-width d-flex justify-content-center">
      <video className="border-radius w-75" autoPlay loop muted>
        <source src="../assets/Video2.mp4" type="video/mp4" />
      </video>
    </div>
    <div className="desc-width">
      <h4 className="text-end font-primary fw-bold">
        كل ما تحتاجه لنمو متجرك في مكان واحد
      </h4>
      <p className="text-end desc mt-3">
        مميزات سوق تطبيقات زد تساعدك في سهولة و سرعة الاستفاده من خدمات و حلول
        سوق التطبيقات لنمو متجرك و مضاعفة ارباحك
      </p>
      <ul>
        <li className="text-end desc d-flex justify-content-end">
          سهولة ادارة و تفعيل تطبيقاتك من نفس لوحة تحكم متجرك
          <div className="circle shadow ms-3">
            <MessageIcon className="fs-3" />
          </div>
        </li>
        <li className="text-end mt-5 mb-5 desc  d-flex justify-content-end">
          دعم فني و تقني متكامل متوفر علي مدار الساعه
          <div className="circle shadow ms-3">
            <MessageIcon className="fs-3" />
          </div>
        </li>
        <li className="text-end mb-5 smaller-desc  d-flex justify-content-end">
          اسعار تنافسيه مع تجربة مجانيه و باقات اشتراك متنوعه
          <div className="circle shadow ms-3">
            <MessageIcon className="fs-3" />
          </div>
        </li>
      </ul>
      <div className="d-flex justify-content-end">
        <div
          className="main-button mt-3 d-flex justify-content-center align-items-center pe-3"
        >
          <ChevronLeftIcon className="animate w-25 " /> تصفح التطبيقات
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import MessageIcon from "vue-material-design-icons/Message.vue";
import ChevronLeftIcon from "vue-material-design-icons/Chevron.vue";
export default {
  name: "appdesc",
  components: {
    MessageIcon,
    ChevronLeftIcon,
  },
};
</script>
