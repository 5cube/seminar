<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import Link from './components/Link.vue'
</script>

<template>
  <main class="flex-grow bg-gradient-to-r from-fuchsia-100 text-gray-900">
    <h1 class="text-3xl font-bold container my-6">
      Выездной семинар в сфере ИТ "StartUP"
    </h1>
    <h2 class="text-xl font-semibold container mb-4">Знакомство с инструментами веб-разработки</h2>

    <section class="container my-6">
      <h3 class="text-lg mb-4">Настройка окружения</h3>
      <div class="flex space-x-4 mb-4">
        <a href="https://code.visualstudio.com/">
          <img src="./assets/vscode-svgrepo-com.svg" alt="vscode" class="h-6">
        </a>
        <a href="https://nodejs.org/en/">
          <img src="./assets/nodejs-logo-svgrepo-com.svg" alt="nodejs" class="h-6">
        </a>
        <a href="https://classic.yarnpkg.com/lang/en/docs/install/">
          <img src="./assets/yarn-svgrepo-com.svg" alt="yarn" class="h-6">
        </a>
      </div>

      <ul class="list-disc list-inside">
        <li>
          Установка <Link href="https://code.visualstudio.com/">Visual Studio Code</Link>
        </li>
        <li>
          Установка <Link href="https://nodejs.org/en/">nodejs, npm</Link>
        </li>
        <li>
          Установка <Link href="https://classic.yarnpkg.com/lang/en/docs/install/">yarn</Link>
        </li>
      </ul>
    </section>

    <section class="container my-6">
      <h3 class="text-lg mb-4">Git</h3>
      <div class="flex space-x-4 mb-4">
        <a href="https://code.visualstudio.com/">
          <img src="./assets/git-svgrepo-com.svg" alt="git" class="h-6">
        </a>
        <a href="https://code.visualstudio.com/">
          <img src="./assets/github-svgrepo-com.svg" alt="github" class="h-6">
        </a>
      </div>

      <ul class="list-disc list-inside">
        <li>
          Установка <Link href="https://git-scm.com/book/ru/v2/%D0%92%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5-%D0%A3%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BA%D0%B0-Git">git</Link>
        </li>
        <li>
          Инициализиция git-репозитория
        </li>
        <li>
          Создание локального коммита
        </li>
        <li>
          Создание репозитария в Github
        </li>
        <li>
          Отправление локального изменения в Github
        </li>
      </ul>
    </section>

    <section class="container my-6">
      <h3 class="text-lg mb-4">Фреймворки</h3>
      <div class="flex space-x-4 mb-4">
        <a href="https://tailwindcss.com/docs/guides/vite">
          <img src="./assets/vitejs-svgrepo-com.svg" alt="vitejs" class="h-6">
        </a>
        <a href="https://code.visualstudio.com/">
          <img src="./assets/tailwindcss-icon-svgrepo-com.svg" alt="tailwindcss" class="h-6">
        </a>
      </div>

      <ul class="list-disc list-inside">
        <li>
          Установка <Link href="https://vitejs.dev/guide/#scaffolding-your-first-vite-project">vitejs</Link>
        </li>
        <li>
          Установка <Link href="https://tailwindcss.com/docs/guides/vite">tailwindcss</Link>
        </li>
        <li>
          Установка <Link href="https://tailwindcss.com/docs/editor-setup#intelli-sense-for-vs-code">расширения tailwindcss для vscode tailwindcss</Link>
        </li>
      </ul>
    </section>

    <section class="container my-6">
      <h3 class="text-lg mb-4">Сборка и хостинг</h3>
      <div class="flex space-x-4 mb-4">
        <a href="https://www.netlify.com/">
          <img src="./assets/netlify-svgrepo-com.svg" alt="netlify" class="h-6">
        </a>
      </div>

      <ul class="list-disc list-inside">
        <li>
          Создание аккаунта в <Link href="https://www.netlify.com/">netlify</Link>
        </li>
      </ul>
    </section>

    <footer class="container text-sm text-gray-500 flex justify-between py-4">
      <a href="https://github.com/5cube/seminar" class="hover:text-gray-900">
        Исходный код
        <img src="./assets/github-svgrepo-com.svg" alt="github" class="inline h-6">
      </a>
      <span>&copy;2021</span>
    </footer>
  </main>
</template>
