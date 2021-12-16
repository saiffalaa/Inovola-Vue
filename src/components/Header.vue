<template>
  <div className="text-center section_space">
    <h1 className="font-primary">
      طور متجرك و وسع أفاق تجارتك مع سوق تطبيقات زد
    </h1>
    <p className="mt-5 w-50 mx-auto fs-4 fw-bold">
      طور تجارتك من خلال تطبيقات و حلول سوق تطبيقات زد التي تساعدك في نمو ارباحك
      عبر ادارة عمليات متجرك بشكل احترافي
    </p>
    <div className="d-flex justify-content-center">
      <div
        className="main-button mt-3 d-flex justify-content-center align-items-center pe-3"
      >
        <ChevronLeftIcon className=" animate w-25 " /> تصفح التطبيقات
      </div>
    </div>
  </div>
</template>
<script>
import ChevronLeftIcon from "vue-material-design-icons/Chevron.vue";
export default {
  name: "Header",
  components: {
    ChevronLeftIcon,
  },
};
</script>
