<template>
  <section class="section">
    <div class="py-20">
      <h1 class="ml-40 text-white font-bold text-6xl">PROJETOS</h1>
      <div class="flex items-center justify-center">
        <div class="pt-20 gap-2 grid grid-cols-3">
          <ThePhotoCard>
            <img
              src="../assets/Influenciadores/Icones Exportados/Home/JC.png"
              alt="Descrição da imagem"
            />
          </ThePhotoCard>
          <ThePhotoCard>
            <img
              src="../assets/Influenciadores/Icones Exportados/Home/Konstans.png"
              alt="Descrição da imagem"
            />
          </ThePhotoCard>
          <ThePhotoCard>
            <img
              src="../assets/Influenciadores/Icones Exportados/Home/Roteiros Conventos.png"
              alt="Descrição da imagem"
            />
          </ThePhotoCard>
          <ThePhotoCard>
            <img
              src="../assets/Influenciadores/Icones Exportados/Home/Grupo Pitol.png"
              alt="Descrição da imagem"
            />
          </ThePhotoCard>
          <ThePhotoCard>
            <img
              src="../assets/Influenciadores/Icones Exportados/Home/Gip Store.png"
              alt="Descrição da imagem"
            />
          </ThePhotoCard>
          <ThePhotoCard>
            <img
              src="../assets/Influenciadores/Icones Exportados/Home/Sicredi.png"
              alt="Descrição da imagem"
            />
          </ThePhotoCard>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import ThePhotoCard from "./atoms/ThePhotoCard.vue";
export default {
  name: "TheProjects",
  components: {
    ThePhotoCard,
  },
};
</script>

<style scoped>
.section {
  background-size: cover;
  background-position: center;
  background-image: url("@/assets/Influenciadores/Icones Exportados/Para Influenciadores/Fundo 3.png");
  height: 120vh;
}

img {
  width: 600px;
  height: 400px;
}
</style>
