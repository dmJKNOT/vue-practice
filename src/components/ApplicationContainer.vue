<template>
  <div class="d-flex" id="wrapper">
    <ContentRaterSidebar/>
    <div id="page-content-wrapper">
      <ContentRaterNavbar @toggle-content="toggleContent"/>
      <ContentRaterPageContent v-if="display"/>
    </div>
  </div>
</template>
<script>
import ContentRaterSidebar from "@/components/ContentRaterSidebar";
import ContentRaterPageContent from "@/components/ContentRaterPageContent";
import ContentRaterNavbar from "@/components/ContentRaterNavbar";
export default {
  components: {ContentRaterNavbar, ContentRaterPageContent, ContentRaterSidebar},
  data: () => ({ display: true }),
  methods: {
    toggleContent() {
      this.display = !this.display;
    }
  },
  emits:['toggle-content']
}
</script>

<style src="../assets/css/styles.css"/>