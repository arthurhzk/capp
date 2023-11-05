<template>
  <section class="ml-10 h-[600px] flex mt-5 mb-10">
    <div>
      <img
        class="w-[200px] h-[200px] mt-2"
        src="../assets/Influenciadores/Icones Exportados/Home/CÍRCULO - Criatividade Responsável/FUNDO BRANCO.gif"
        alt="resp-logo"
      />
      <div class="ml-40">
        <p class="text-cyan-500">SEGUNDO NOSSOS CLIENTES</p>
        <h1 class="font-bold text-6xl text-gray-700">
          O QUE NOS <br />
          DIFERENCIA!
        </h1>
      </div>
    </div>

    <div class="grid grid-cols-3 gap-10 items-center justify-center ml-30">
      <TheIconGrid
        class="p-5 mx-auto flex"
        text="Atendimento 100% <br /> disponível em horário comercial"
      >
        <img
          class="w-[70px] h-[70px] mx-auto"
          src="../assets/Influenciadores/Icones Exportados/Home/Atendimento.png"
        />
      </TheIconGrid>
      <TheIconGrid class="p-5 mx-auto" text="Time de criações">
        <img
          class="w-[70px] h-[70px] mx-auto"
          src="../assets/Influenciadores/Icones Exportados/Home/Criação.png"
        />
      </TheIconGrid>
      <TheIconGrid
        class="p-5 mx-auto"
        text="Analista digital interno <br /> para sua conta"
      >
        <img
          class="w-[70px] h-[70px] mx-auto"
          src="../assets/Influenciadores/Icones Exportados/Home/Análise Digital.png"
        />
      </TheIconGrid>
      <TheIconGrid class="p-5 mx-auto" text="Redação exclusiva">
        <img
          class="w-[70px] h-[70px] mx-auto"
          src="../assets/Influenciadores/Icones Exportados/Home/Redação.png"
        />
      </TheIconGrid>
      <TheIconGrid
        class="p-5 mx-auto"
        text="Setor de audiovisual <br /> para desenvolver suas demandas"
      >
        <img
          class="w-[70px] h-[70px] mx-auto"
          src="../assets/Influenciadores/Icones Exportados/Home/Audiovisual.png"
        />
      </TheIconGrid>
      <TheIconGrid class="p-5 mx-auto" text="Um estrategista">
        <img
          class="w-[70px] h-[70px] mx-auto"
          src="../assets/Influenciadores/Icones Exportados/Home/Estrategista.png"
        />
      </TheIconGrid>
      <TheIconGrid
        class="p-5 mx-auto"
        text="Nossos profissionais <br /> vão até sua empresa"
      >
        <img
          class="w-[70px] h-[70px] mx-auto"
          src="../assets/Influenciadores/Icones Exportados/Home/Profissionais até a empresa.png"
        />
      </TheIconGrid>
      <TheIconGrid class="p-5 mx-auto" text="Estúdio próprio">
        <img
          class="w-[70px] h-[70px] mx-auto"
          src="../assets/Influenciadores/Icones Exportados/Home/Estudio.png"
        />
      </TheIconGrid>
      <TheIconGrid
        class="p-5 mx-auto"
        text="Um espaço de 300m² <br /> com todas as soluções em marketing"
      >
        <img
          class="w-[70px] h-[70px] mx-auto"
          src="../assets/Influenciadores/Icones Exportados/Home/Espaço.png"
        />
      </TheIconGrid>
    </div>
  </section>
</template>

<script>
import TheIconGrid from "./atoms/TheIconGrid.vue";
export default {
  name: "TheIconSection",
  components: {
    TheIconGrid,
  },
};
</script>
