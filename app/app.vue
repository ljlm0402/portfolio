<template>
  <div class="min-h-screen bg-gray-900 text-white">
    <NuxtRouteAnnouncer />
    <Header />
    <main>
      <Hero />
      <About />
      <Skills />
      <Experience />
      <Projects />
      <Community />
    </main>
  </div>
</template>

<script setup>
import Header from "../components/TheHeader.vue";
import Hero from "../components/HeroSection.vue";
import About from "../components/AboutSection.vue";
import Skills from "../components/SkillsSection.vue";
import Experience from "../components/ExperienceSection.vue";
import Projects from "../components/ProjectsSection.vue";
import Community from "../components/CommunitySection.vue";

// SEO meta tags
useHead({
  title: "포트폴리오 | 웹 개발자",
  meta: [
    {
      name: "description",
      content: "전문적인 웹 개발자의 포트폴리오 사이트입니다.",
    },
  ],
});
</script>

<style>
html {
  scroll-behavior: smooth;
}
</style>
