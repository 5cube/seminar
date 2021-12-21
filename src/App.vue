<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import Link from './components/Link.vue'
</script>

<template>
  <h1 class="text-3xl font-bold container my-6 px-6">
    Выездной семинар в сфере ИТ "StartUP"
  </h1>
  <h2 class="text-xl font-semibold container px-6">Знакомство с инструментами веб-разработки</h2>
  <section class="container p-6">
    <ol class="list-decimal list-inside">
      <li>
        Редактор кода <Link link="https://code.visualstudio.com/">Visual Studio Code</Link>
      </li>
      <li>
        Система контроля версий с <Link link="https://git-scm.com/book/ru/v2/%D0%92%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5-%D0%A3%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BA%D0%B0-Git">Github</Link>
      </li>
      <li>
        Верстка с использованием <Link link="https://tailwindcss.com/">tailwindcss</Link>
      </li>
      <li>
        Сборка и деплой на примере <Link link="https://www.netlify.com/">Netlify</Link>
      </li>
    </ol>
  </section>
</template>
