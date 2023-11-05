<template>
  <section class="section">
    <div class="py-20">
      <h1 class="ml-40 text-white font-bold text-6xl">SERVIÇOS</h1>
      <div class="flex items-center justify-center">
        <div class="pt-20 gap-2 grid grid-cols-3">
          <TheGradientCard
            title="MARKETING DIGITAL </br> & SITES"
            description="Vamos guiar você a melhor alternativa de </br> investimento, sendo ela em mecanismos de </br> busca da Internet ou nas redes sociais."
          >
            <img
              class="w-12 h-12"
              src="../assets/Influenciadores/Icones Exportados/Home/Marketing Digital e Sites.png"
              alt="Imagem 1"
            />
          </TheGradientCard>

          <TheGradientCard
            title="IDENTIDADE VISUAL"
            description="Pacotes fixos podem ter custos elevados </br> e o que você precisa pode levar menos </br> tempo, mas não encontra ninguém que </br> se disponha a fazer."
          >
            <img
              class="w-12 h-12"
              src="../assets/Influenciadores/Icones Exportados/Home/Identidade Visual.png"
              alt="Imagem 2"
            />
          </TheGradientCard>

          <TheGradientCard
            title="AUDIOVISUAL"
            description="Convertendo conceitos em vídeos </br> emocionantes: nossa especialidade </br> é dar vida às suas ideias."
          >
            <img
              class="w-12 h-12"
              src="../assets/Influenciadores/Icones Exportados/Home/Audiovisual 02.png"
              alt="Imagem 3"
            />
          </TheGradientCard>

          <TheGradientCard
            title="DESIGN"
            description="Pacotes fixos podem ter custos elevados </br> e o que você precisa pode levar menos </br> tempo, mas não encontra ninguém que </br> se disponha a fazer."
          >
            <img
              class="w-12 h-12"
              src="../assets/Influenciadores/Icones Exportados/Home/Identidade Visual.png"
              alt="Imagem 4"
            />
          </TheGradientCard>

          <TheGradientCard
            title="CURSOS & </br> PALESTRAS"
            description="Convertendo conceitos em vídeos </br> emocionantes: nossa especialidade é </br> dar vida às suas ideias."
          >
            <img
              class="w-12 h-12"
              src="../assets/Influenciadores/Icones Exportados/Home/Audiovisual 02.png"
              alt="Imagem 5"
            />
          </TheGradientCard>

          <TheGradientCard
            title="MARKETING DE </br> INFLUÊNCIA"
            description="Lorem ipsum dolor sit amet, consectetur </br> adipiscing elit. Ut elit tellus, luctus nec </br> ullamcorper mattis, pulvinar dapibus leo."
          >
            <img
              class="w-12 h-12"
              src="../assets/Influenciadores/Icones Exportados/Home/Marketing Digital e Sites.png"
              alt="Imagem 6"
            />
          </TheGradientCard>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import TheGradientCard from "./atoms/TheGradientCard.vue";
export default {
  name: "TheServices",
  components: {
    TheGradientCard,
  },
};
</script>

<style scoped>
.section {
  background-size: cover;
  background-position: center;
  background-image: url("@/assets/Influenciadores/Icones Exportados/Para Influenciadores/Fundo 3.png");
  height: 110vh;
}
</style>
