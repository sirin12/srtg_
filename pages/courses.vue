<template>
  <div>
    <NavTwo />
    <PageHeader title="Courses" />
    <Course />
    <Footer />
  </div>
</template>
<script>
  import PageHeader from "../components/PageHeader";
  import NavTwo from "../components/NavTwo";
  import Footer from "../components/Footer";
  import Course from "../components/Course";
  export default {
    components: {Course, Footer, NavTwo, PageHeader},
    head(){
      return {
        title: "Course"
      }
    }
  }
</script>
