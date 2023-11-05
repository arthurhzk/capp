<template>
  <form @submit.prevent="handleSubmit">
    <section class="section">
      <div class="ml-40 w-full flex flex-col">
        <h1 class="text-white text-6xl font-semibold pt-16">
          FICOU COM <br />
          <span class="text-cyan-500">ALGUMA DÚVIDA?</span>
        </h1>
        <div class="flex space-x-4">
          <div class="w-1/2">
            <p class="text-white font-semibold pt-11 mb-1">Nome:</p>
            <TheInput
              inputStyle="w-full h-12 rounded-md"
              placeholder="Nome"
              type="text"
            />
          </div>
        </div>
        <div class="flex space-x-4">
          <div class="w-[468px]">
            <p class="text-white font-semibold pt-11 mb-1">Email:</p>
            <TheInput
              inputStyle="w-full h-12 rounded-md "
              placeholder="Email:"
              type="email"
            />
          </div>
          <div class="w-[468px]">
            <p class="text-white font-semibold pt-11 mb-1">Telefone:</p>
            <TheInput
              inputStyle="w-full h-12 rounded-md"
              placeholder="Telefone"
            />
          </div>
        </div>
        <div class="w-1/2 mb-7">
          <p class="text-white font-semibold pt-11 mb-1">Mensagem:</p>
          <TheInput
            inputStyle="w-full h-44 rounded-md align-top"
            placeholder="Mensagem"
            type="text"
          />
        </div>
        <TheSubmit
          styledButton="text-white font-semibold w-[180px] h-[60px] border border-solid border-4 border-white text-xl rounded-full"
          text="Enviar"
        />
      </div>
    </section>
  </form>
</template>

<script>
import TheInput from "./atoms/TheInput.vue";
import TheSubmit from "./atoms/TheSubmit.vue";
export default {
  name: "TheForm",
  components: {
    TheInput,
    TheSubmit,
  },
  methods: {
    handleSubmit(e) {
      e.preventDefault();
    },
  },
};
</script>

<style scoped>
.section {
  background-size: cover;
  background-position: center;
  background-image: url("@/assets/Influenciadores/Icones Exportados/Para Influenciadores/Fundo 3.png");
  height: 90vh;
}
</style>
