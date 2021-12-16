<template>
  <div className="section_space pt-5 footer-last-space">
    <div className="mb-5">
      <h2 className="text-center fs-4">التطبيقات المميزه</h2>
      <p className="text-center  small-font">
        تطبيقات تقدم حلول و خدمات مميزه نوصي بها
      </p>
    </div>
    <ul className="d-flex justify-content-center">
      <li className="card-width d-flex p-3 round">
        <div className="second">
          <div className="d-flex justify-content-end">
            <p className="fs-5 d-flex align-items-center me-5">
              5<StarIcon className="text-warning pb-1" />
            </p>
            <h4 className="text-end">قمرة</h4>
          </div>
          <small className="d-flex justify-content-end">
            <span className="text-info">عمر برهوم </span> :تطوير
          </small>
          <p className="text-end mt-3">
            نظام الولاء الامثل الذي يمكنك من رفع مبيعاتك
          </p>
          <p className="text-end">
            نظام الولاء الامثل الذي يمكنك من رفع مبيعاتك
          </p>
        </div>
        <div className="first text-center">
          <img className="rounded" src="../assets/kamra.png" />
        </div>
      </li>
      <li className="card-width d-flex p-3 ms-3 round">
        <div className="second">
          <div className="d-flex justify-content-end">
            <p className="fs-5 d-flex align-items-center me-5">
              5<StarIcon className="text-warning pb-1" />
            </p>
            <h4 className="text-end">قمرة</h4>
          </div>
          <small className="d-flex justify-content-end">
            <span className="text-info">عمر برهوم </span> :تطوير
          </small>
          <p className="text-end mt-3">
            نظام الولاء الامثل الذي يمكنك من رفع مبيعاتك
          </p>
          <p className="text-end">
            نظام الولاء الامثل الذي يمكنك من رفع مبيعاتك
          </p>
        </div>
        <div className="first text-center">
          <img className="rounded" src="../assets/kamra.png" />
        </div>
      </li>
      <li className="card-width d-flex p-3 ms-3 round">
        <div className="second">
          <div className="d-flex justify-content-end">
            <p className="fs-5 d-flex align-items-center me-5">
              5<StarIcon className="text-warning pb-1" />
            </p>
            <h4 className="text-end">قمرة</h4>
          </div>
          <small className="d-flex justify-content-end">
            <span className="text-info">عمر برهوم </span> :تطوير
          </small>
          <p className="text-end mt-3">
            نظام الولاء الامثل الذي يمكنك من رفع مبيعاتك
          </p>
          <p className="text-end">
            نظام الولاء الامثل الذي يمكنك من رفع مبيعاتك
          </p>
        </div>
        <div className="first text-center">
          <img className="rounded" src="../assets/kamra.png" />
        </div>
      </li>
      <li className="card-width d-flex p-3 ms-3 me-4 round">
        <div className="second">
          <div className="d-flex justify-content-end">
            <p className="fs-5 d-flex align-items-center me-5">
              5<StarIcon className="text-warning pb-1" />
            </p>
            <h4 className="text-end">قمرة</h4>
          </div>
          <small className="d-flex justify-content-end">
            <span className="text-info">عمر برهوم </span> :تطوير
          </small>
          <p className="text-end mt-3">
            نظام الولاء الامثل الذي يمكنك من رفع مبيعاتك
          </p>
          <p className="text-end">
            نظام الولاء الامثل الذي يمكنك من رفع مبيعاتك
          </p>
        </div>
        <div className="first text-center">
          <img className="rounded" src="../assets/kamra.png" />
        </div>
      </li>
    </ul>
    <div className="d-flex justify-content-center">
      <div
        className="second-button mt-3 d-flex justify-content-center align-items-center pe-3"
      >
        <ChevronLeftIcon className="animate w-25 " /> تصفح التطبيقات
      </div>
    </div>
  </div>
</template>
<script>
import StarIcon from "vue-material-design-icons/Star.vue";
import ChevronLeftIcon from "vue-material-design-icons/Chevron.vue";
export default {
  name: "apps",
  components: {
    StarIcon,
    ChevronLeftIcon,
  },
};
</script>
