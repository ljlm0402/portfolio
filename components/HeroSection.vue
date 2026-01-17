<template>
  <section
    id="home"
    class="min-h-screen flex items-center justify-center bg-gradient-to-br from-gray-900 via-blue-900 to-gray-900"
  >
    <div class="container mx-auto px-6 text-center">
      <div class="max-w-4xl mx-auto">
        <!-- Profile Image -->
        <div class="mb-8">
          <div
            class="w-32 h-32 mx-auto rounded-full bg-gradient-to-r from-blue-400 to-purple-400 flex items-center justify-center text-4xl font-bold"
          >
            DEVELOPER
          </div>
        </div>

        <!-- Main Heading -->
        <h1
          class="text-4xl md:text-6xl font-bold mb-6 bg-gradient-to-r from-blue-400 to-purple-400 bg-clip-text text-transparent"
        >
          안녕하세요! 👋
        </h1>

        <h2 class="text-2xl md:text-3xl font-semibold mb-4 text-gray-200">
          저는 <span class="text-blue-400">웹 개발자</span>입니다
        </h2>

        <p class="text-lg md:text-xl text-gray-300 mb-8 max-w-2xl mx-auto">
          창의적이고 효율적인 웹 솔루션을 만드는 것을 좋아하는 개발자입니다.<br />
          사용자 경험과 코드 품질에 중점을 두고 있습니다.
        </p>

        <!-- CTA Buttons -->
        <div
          class="flex flex-col sm:flex-row gap-4 justify-center items-center"
        >
          <a
            href="#experience"
            class="px-8 py-3 bg-blue-500 hover:bg-blue-600 text-white rounded-lg transition-colors font-semibold"
          >
            주요 경력 보기
          </a>
          <a
            href="#projects"
            class="px-8 py-3 border-2 border-blue-400 text-blue-400 hover:bg-blue-400 hover:text-gray-900 rounded-lg transition-colors font-semibold"
          >
            프로젝트 보기
          </a>
        </div>

        <!-- Social Links -->
        <div class="flex justify-center space-x-6 mt-8">
          <a
            href="#"
            class="text-gray-400 hover:text-blue-400 transition-colors"
          >
            <Icon name="mdi:github" class="w-6 h-6" />
          </a>
          <a
            href="#"
            class="text-gray-400 hover:text-blue-400 transition-colors"
          >
            <Icon name="mdi:npm" class="w-6 h-6" />
          </a>
        </div>
      </div>

      <!-- Scroll indicator -->
      <div
        class="absolute bottom-8 left-1/2 transform -translate-x-1/2 animate-bounce"
      >
        <Icon name="mdi:chevron-down" class="w-8 h-8 text-gray-400" />
      </div>
    </div>
  </section>
</template>