<template>
  <div class="home">
    <h1>ОТДЕЛЕНИЯ И БАНКОМАТЫ ОПТИМА БАНК</h1>
  </div>
  <ul>
    <li>
      <router-link
        to="https://www.optimabank.kg/images/files/news/2014/spisok-bankomatov-oao-optima-bank.pdf"
        >Список Банкоматов Оптима Банк СКАЧАТЬ (pdf)</router-link
      >
    </li>
    <li>
      <router-link to="https://www.optimabank.kg/images/files/pos_terminals.pdf"
        >Список POS-терминалов ОАО «Оптима Банк»</router-link
      >
    </li>
    <li>
      <router-link
        to="https://www.optimabank.kg/images/files/cashin_terminals_list.pdf"
        >Список платежных терминалов ОАО «Оптима Банк»</router-link
      >
    </li>
    <li>
      <router-link
        to="https://www.optimabank.kg/images/files/news/2015/09/spisok_podrazdeleniy_oao_optima_bank_s_telefonami_i_adresami.pdf"
        >Справочник подразделений в ОАО «Оптима Банк» (адрес и режим
        работы)</router-link
      >
    </li>
  </ul>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src

export default defineComponent({
  name: "HomeView",
  components: {},
});
</script>
