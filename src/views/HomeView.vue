<template>
  <TheAgency />
  <TheCardSection />
  <TheIconSection />
  <TheServices />
  <TheProjects />
  <TheClientsRating />
  <TheForm />
</template>

<script>
import TheAgency from "@/components/TheAgency.vue";
import TheCardSection from "@/components/TheCardSection.vue";
import TheIconSection from "@/components/TheIconSection.vue";
import TheServices from "@/components/TheServices.vue";
import TheProjects from "@/components/TheProjects.vue";
import TheClientsRating from "@/components/TheClientsRating.vue";
import TheForm from "@/components/TheForm.vue";
export default {
  name: "HomeView",
  components: {
    TheAgency,
    TheCardSection,
    TheIconSection,
    TheServices,
    TheProjects,
    TheClientsRating,
    TheForm,
  },
};
</script>
