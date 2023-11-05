<template>
  <section class="section flex items-center justify-center gap-32">
    <TheSmallCard text="+5" description="anos de experiência">
      <img
        class="w-11 h-9"
        src="@/assets/Influenciadores/Icones Exportados/Home/Anos de Experiência.png"
        alt="Anos de Experiência"
      />
    </TheSmallCard>
    <TheSmallCard text="+10" description="colaboradores">
      <img
        class="w-11 h-9"
        src="@/assets/Influenciadores/Icones Exportados/Home/Colaboradores.png"
        alt="Anos de Experiência"
      />
    </TheSmallCard>
    <TheSmallCard text="+65" description="logotipos desenvolvidos">
      <img
        class="w-11 h-9"
        src="@/assets/Influenciadores/Icones Exportados/Home/Logotipos Desenvolvidos.png"
        alt="Anos de Experiência"
      />
    </TheSmallCard>
    <TheSmallCard text="+350" description="clientes já atendidos">
      <img
        class="w-11 h-9"
        src="@/assets/Influenciadores/Icones Exportados/Home/Clientes Já Atendidos.png"
        alt="Anos de Experiência"
      />
    </TheSmallCard>
  </section>
</template>

<script>
import TheSmallCard from "@/components/atoms/TheSmallCard.vue";
export default {
  name: "TheCardSection",
  components: {
    TheSmallCard,
  },
};
</script>

<style scoped>
.section {
  background-size: cover;
  background-position: center;
  background-image: url("@/assets/Influenciadores/Icones Exportados/Home/Fundo 1.png");
  height: 21rem;
}
</style>
