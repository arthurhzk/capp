<template>
  <section class="grid grid-cols-2 gap-4 px-64 pt-16">
    <div>
      <h1 class="font-bold text-4xl text-gray-700">
        AGÊNCIA DE PUBLICIDADE<br />
        FOCADA EM<br />
        <span class="text-cyan-500">CRIATIVIDADE RESPONSÁVEL /</span>
      </h1>
      <p class="text-gray-500 font-semibold">
        ATENDIMENTO NACIONAL . AGÊNCIA 360 . MARKETING DIGITAL
      </p>
      <p class="mt-16 text-gray-700 font-semibold">
        Aqui na CAPP, você terá um time completo de marketing para <br />a sua
        empresa, Publicitários, um setor de Audiovisual,<br />
        Designers, Analista Digital, Redação e Atendimento. Para que<br />
        todas as demandas de Marketing da sua empresa possam <br />
        ser solucionadas em um lugar só e com responsabilidade.
      </p>

      <div class="space-x-4 my-16">
        <the-button text="Ver serviços"></the-button>
        <the-button text="Somos CAPP"></the-button>
      </div>
    </div>

    <img
      src="../assets/Influenciadores/Icones Exportados/Home/CAPPVERSO/FUNDO BRANDO.gif"
      alt=""
    />
  </section>
</template>

<script>
import TheButton from "@/components/atoms/TheButton.vue";
export default {
  name: "TheAgency",
  components: {
    TheButton,
  },
};
</script>
