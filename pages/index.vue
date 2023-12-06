<template>
  <div>
    <NavTwo />
    <BannerTwo />
    <CourseCatTwo />
    <AboutOne />
    <CourseTwo />
    <Pricing />
    <Meeting />
    <CallToActionTwo />
    <BlogHome />
    <Footer />
  </div>
</template>
<script>
  import NavTwo from "../components/NavTwo";
  import Footer from "../components/Footer";
  import BannerTwo from "../components/BannerTwo";
  import CourseCatTwo from "../components/CourseCatTwo";
  import AboutOne from "../components/AboutOne";
  import CourseTwo from "../components/CourseTwo";
  import Pricing from "../components/Pricing";
  import Meeting from "../components/Meeting";
  import CallToActionTwo from "../components/CallToActionTwo";
  import BlogHome from "../components/BlogHome";
  export default {
    components: {
      BlogHome,
      CallToActionTwo,
      Meeting,
      Pricing,
      CourseTwo,
      AboutOne,
      CourseCatTwo,
      BannerTwo,
      Footer,
      NavTwo
    },
    head(){
      return{
        title: "SRTG"
      }
    }
  }
</script>
