<template>
  <div>
    <NavOne />
    <PageHeader title="About" />
    <AboutOne />
    <TeamOne />
    <VideoOne />
    <ClientsLogoOne />
    <div class="border-bottom"></div>
    <Footer />
  </div>

</template>
<script>
  import NavOne from "../components/NavTwo";
  import PageHeader from "../components/PageHeader";
  import Footer from "../components/Footer";
  import AboutOne from "../components/AboutOne";
  import TeamOne from "../components/TeamOne";
  import VideoOne from "../components/VideoOne";
  import ClientsLogoOne from "../components/ClientsLogoOne";
  export default {
    components: {
      ClientsLogoOne,
      VideoOne,
      TeamOne,
      AboutOne,
      Footer,
      PageHeader,
      NavOne
    },
    head(){
      return {
        title: "Presentation"
      }
    }
  }
</script>
