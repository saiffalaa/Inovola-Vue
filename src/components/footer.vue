<template>
  <footer className="section-space footer-bg mt-5 pt-3">
    <div
      className="d-flex flex-column align-items-center justify-content-center"
    >
      <div className="fs-1 text-white mb-5">
        <img src="../assets/bigLogo.png" />
      </div>
      <div className="d-flex justify-content-around w-25 mb-5">
        <YouTubeIcon className="fs-5 text-white" />
        <LinkedInIcon className="fs-5 text-white" />
        <InstagramIcon className="fs-5 text-white" />
        <TwitterIcon className="fs-5 text-white" />
      </div>
    </div>
    <div className="pos">
      <ArrowCircleUpIcon class="text-warning" />
    </div>
    <div class="bg-yellow pos2">
      <CommentIcon />
    </div>
  </footer>
</template>
<script>
import LinkedInIcon from "vue-material-design-icons/Linked.vue";
import YouTubeIcon from "vue-material-design-icons/Youtube.vue";
import InstagramIcon from "vue-material-design-icons/Instagram.vue";
import TwitterIcon from "vue-material-design-icons/Twitter.vue";
import ArrowCircleUpIcon from "vue-material-design-icons/Arrowupcircle.vue";
import CommentIcon from "vue-material-design-icons/Comment.vue";

export default {
  name: "footer",
  components: {
    YouTubeIcon,
    LinkedInIcon,
    InstagramIcon,
    TwitterIcon,
    ArrowCircleUpIcon,
    CommentIcon,
  },
};
</script>
