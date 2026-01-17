<template>
  <header
    class="fixed top-0 w-full bg-gray-900/90 backdrop-blur-sm z-50 border-b border-gray-800"
  >
    <nav class="container mx-auto px-6 py-4">
      <div class="flex justify-between items-center">
        <div class="text-xl font-bold text-blue-400">Portfolio</div>

        <!-- Desktop Navigation -->
        <div class="hidden md:flex space-x-8">
          <a href="#home" class="hover:text-blue-400 transition-colors">홈</a>
          <a href="#about" class="hover:text-blue-400 transition-colors"
            >소개</a
          >
          <a href="#skills" class="hover:text-blue-400 transition-colors"
            >스킬</a
          >
          <a href="#experience" class="hover:text-blue-400 transition-colors"
            >경력사항</a
          >
          <a href="#projects" class="hover:text-blue-400 transition-colors"
            >프로젝트</a
          >
          <a href="#community" class="hover:text-blue-400 transition-colors"
            >커뮤니티</a
          >
        </div>

        <!-- Mobile menu button -->
        <button
          @click="toggleMobileMenu"
          class="md:hidden text-white hover:text-blue-400 transition-colors"
        >
          <Icon name="mdi:menu" class="w-6 h-6" />
        </button>
      </div>

      <!-- Mobile Navigation -->
      <div
        v-show="isMobileMenuOpen"
        class="md:hidden mt-4 pb-4 border-t border-gray-800"
      >
        <div class="flex flex-col space-y-4 pt-4">
          <a
            href="#home"
            @click="closeMobileMenu"
            class="hover:text-blue-400 transition-colors"
            >홈</a
          >
          <a
            href="#about"
            @click="closeMobileMenu"
            class="hover:text-blue-400 transition-colors"
            >소개</a
          >
          <a
            href="#skills"
            @click="closeMobileMenu"
            class="hover:text-blue-400 transition-colors"
            >스킬</a
          >
          <a
            href="#experience"
            @click="closeMobileMenu"
            class="hover:text-blue-400 transition-colors"
            >경력사항</a
          >
          <a
            href="#projects"
            @click="closeMobileMenu"
            class="hover:text-blue-400 transition-colors"
            >프로젝트</a
          >
          <a
            href="#community"
            @click="closeMobileMenu"
            class="hover:text-blue-400 transition-colors"
            >커뮤니티</a
          >
        </div>
      </div>
    </nav>
  </header>
</template>

<script setup>
const isMobileMenuOpen = ref(false);

const toggleMobileMenu = () => {
  isMobileMenuOpen.value = !isMobileMenuOpen.value;
};

const closeMobileMenu = () => {
  isMobileMenuOpen.value = false;
};
</script>