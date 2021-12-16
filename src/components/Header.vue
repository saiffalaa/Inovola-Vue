<template>
  <div class="text-center section_space">
    <h1 class="font-primary">طور متجرك و وسع أفاق تجارتك مع سوق تطبيقات زد</h1>
    <p class="mt-5 w-50 mx-auto fs-4 fw-bold">
      طور تجارتك من خلال تطبيقات و حلول سوق تطبيقات زد التي تساعدك في نمو ارباحك
      عبر ادارة عمليات متجرك بشكل احترافي
    </p>
    <div class="d-flex justify-content-center">
      <div
        class="main-button mt-3 d-flex justify-content-center align-items-center pe-3"
      >
        <ChevronLeftIcon class="animate w-25" /> تصفح التطبيقات
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
