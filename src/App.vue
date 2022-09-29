<script>
import MenuLateral from "@/components/MenuLateral.vue";
import MenuPrincipal from "./components/MenuPrincipal.vue";
import MenuCabecalho from "./components/MenuCabecalho.vue";
import MenuFooter from "./components/MenuFooter.vue";
export default {
  components: { MenuLateral, MenuPrincipal, MenuCabecalho, MenuFooter },
};
</script>
<template>
  <MenuLateral />
  <MenuCabecalho />
  <MenuPrincipal />
  <MenuFooter />
</template>
<style></style>
