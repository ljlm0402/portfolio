<template>
  <section id="skills" class="py-20 bg-gray-900">
    <div class="container mx-auto px-6">
      <div class="max-w-6xl mx-auto">
        <!-- Section Header -->
        <div class="text-center mb-16">
          <h2 class="text-3xl md:text-4xl font-bold mb-4 text-white">
            기술 스택
          </h2>
          <p class="text-gray-400 text-lg">사용할 수 있는 기술들입니다</p>
        </div>

        <div class="grid md:grid-cols-3 gap-8">
          <!-- Frontend -->
          <div
            class="bg-gray-800 rounded-xl p-8 hover:bg-gray-750 transition-colors"
          >
            <div class="text-center mb-6">
              <div
                class="w-16 h-16 mx-auto bg-blue-500 rounded-lg flex items-center justify-center mb-4"
              >
                <Icon name="mdi:monitor" class="w-8 h-8 text-white" />
              </div>
              <h3 class="text-xl font-semibold text-white mb-2">Frontend</h3>
              <p class="text-gray-400">사용자 인터페이스 개발</p>
            </div>

            <div class="space-y-4">
              <div class="flex items-center space-x-3">
                <Icon
                  name="mdi:language-javascript"
                  class="w-6 h-6 text-yellow-500"
                />
                <span class="text-gray-300">JavaScript</span>
              </div>
              <div class="flex items-center space-x-3">
                <Icon
                  name="mdi:language-typescript"
                  class="w-6 h-6 text-blue-500"
                />
                <span class="text-gray-300">TypeScript</span>
              </div>
              <div class="flex items-center space-x-3">
                <Icon name="mdi:vuejs" class="w-6 h-6 text-green-400" />
                <span class="text-gray-300">Vue.js</span>
              </div>
              <div class="flex items-center space-x-3">
                <Icon name="mdi:react" class="w-6 h-6 text-blue-400" />
                <span class="text-gray-300">React.js / Next.js</span>
              </div>
            </div>
          </div>

          <!-- Backend -->
          <div
            class="bg-gray-800 rounded-xl p-8 hover:bg-gray-750 transition-colors"
          >
            <div class="text-center mb-6">
              <div
                class="w-16 h-16 mx-auto bg-green-500 rounded-lg flex items-center justify-center mb-4"
              >
                <Icon name="mdi:server" class="w-8 h-8 text-white" />
              </div>
              <h3 class="text-xl font-semibold text-white mb-2">Backend</h3>
              <p class="text-gray-400">서버 및 API 개발</p>
            </div>

            <div class="space-y-4">
              <div class="flex items-center space-x-3">
                <Icon name="mdi:nodejs" class="w-6 h-6 text-green-500" />
                <span class="text-gray-300">Node.js</span>
              </div>
              <div class="flex items-center space-x-3">
                <Icon
                  name="mdi:lightning-bolt"
                  class="w-6 h-6 text-yellow-400"
                />
                <span class="text-gray-300">Express.js</span>
              </div>
              <div class="flex items-center space-x-3">
                <Icon name="mdi:database" class="w-6 h-6 text-blue-500" />
                <span class="text-gray-300">PostgreSQL / MongoDB</span>
              </div>
              <div class="flex items-center space-x-3">
                <Icon name="mdi:api" class="w-6 h-6 text-purple-400" />
                <span class="text-gray-300">RESTful API</span>
              </div>
            </div>
          </div>

          <!-- Tools & Others -->
          <div
            class="bg-gray-800 rounded-xl p-8 hover:bg-gray-750 transition-colors"
          >
            <div class="text-center mb-6">
              <div
                class="w-16 h-16 mx-auto bg-purple-500 rounded-lg flex items-center justify-center mb-4"
              >
                <Icon name="mdi:tools" class="w-8 h-8 text-white" />
              </div>
              <h3 class="text-xl font-semibold text-white mb-2">도구 & 기타</h3>
              <p class="text-gray-400">개발 도구 및 협업</p>
            </div>

            <div class="space-y-4">
              <div class="flex items-center space-x-3">
                <Icon name="mdi:git" class="w-6 h-6 text-orange-500" />
                <span class="text-gray-300">Git / GitHub</span>
              </div>
              <div class="flex items-center space-x-3">
                <Icon name="mdi:docker" class="w-6 h-6 text-blue-400" />
                <span class="text-gray-300">Docker</span>
              </div>
              <div class="flex items-center space-x-3">
                <Icon name="mdi:aws" class="w-6 h-6 text-yellow-500" />
                <span class="text-gray-300">AWS</span>
              </div>
              <div class="flex items-center space-x-3">
                <Icon
                  name="mdi:visual-studio-code"
                  class="w-6 h-6 text-blue-500"
                />
                <span class="text-gray-300">VS Code</span>
              </div>
            </div>
          </div>
        </div>

        <!-- 워크플로우 & 협업 스킬 -->
        <div class="mt-16">
          <h3 class="text-2xl font-semibold text-white mb-8 text-center">
            💡 워크플로우 & 협업
          </h3>
          <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
            <div
              class="bg-gray-800 rounded-xl p-6 hover:bg-gray-750 transition-colors text-center"
            >
              <Icon
                name="mdi:arrow-decision-auto"
                class="w-12 h-12 mx-auto text-blue-400 mb-3"
              />
              <h4 class="text-white font-medium mb-2">애자일 스크럼</h4>
              <p class="text-gray-400 text-sm">스프린트 기반 개발 방법론</p>
            </div>
            <div
              class="bg-gray-800 rounded-xl p-6 hover:bg-gray-750 transition-colors text-center"
            >
              <Icon
                name="mdi:source-branch"
                class="w-12 h-12 mx-auto text-green-400 mb-3"
              />
              <h4 class="text-white font-medium mb-2">Git Flow</h4>
              <p class="text-gray-400 text-sm">체계적인 브랜치 관리</p>
            </div>
            <div
              class="bg-gray-800 rounded-xl p-6 hover:bg-gray-750 transition-colors text-center"
            >
              <Icon
                name="mdi:account-search"
                class="w-12 h-12 mx-auto text-purple-400 mb-3"
              />
              <h4 class="text-white font-medium mb-2">코드 리뷰</h4>
              <p class="text-gray-400 text-sm">품질 향상 협업 문화</p>
            </div>
            <div
              class="bg-gray-800 rounded-xl p-6 hover:bg-gray-750 transition-colors text-center"
            >
              <Icon
                name="mdi:test-tube"
                class="w-12 h-12 mx-auto text-yellow-400 mb-3"
              />
              <h4 class="text-white font-medium mb-2">TDD</h4>
              <p class="text-gray-400 text-sm">테스트 주도 개발</p>
            </div>
            <div
              class="bg-gray-800 rounded-xl p-6 hover:bg-gray-750 transition-colors text-center"
            >
              <Icon
                name="mdi:file-document-outline"
                class="w-12 h-12 mx-auto text-red-400 mb-3"
              />
              <h4 class="text-white font-medium mb-2">문서화</h4>
              <p class="text-gray-400 text-sm">지식 공유 및 유지보수</p>
            </div>
            <div
              class="bg-gray-800 rounded-xl p-6 hover:bg-gray-750 transition-colors text-center"
            >
              <Icon
                name="mdi:speedometer"
                class="w-12 h-12 mx-auto text-orange-400 mb-3"
              />
              <h4 class="text-white font-medium mb-2">성능 최적화</h4>
              <p class="text-gray-400 text-sm">모니터링 & 개선</p>
            </div>
          </div>
        </div>

        <!-- Skills Progress Bars -->
        <div class="mt-16">
          <h3 class="text-2xl font-semibold text-white mb-8 text-center">
            숙련도
          </h3>
          <div class="grid md:grid-cols-2 gap-8">
            <div
              v-for="skill in skillLevels"
              :key="skill.name"
              class="space-y-2"
            >
              <div class="flex justify-between">
                <span class="text-gray-300">{{ skill.name }}</span>
                <span class="text-blue-400">{{ skill.level }}%</span>
              </div>
              <div class="w-full bg-gray-700 rounded-full h-2">
                <div
                  class="bg-gradient-to-r from-blue-400 to-purple-400 h-2 rounded-full transition-all duration-1000"
                  :style="{ width: skill.level + '%' }"
                ></div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
const skillLevels = [
  { name: "JavaScript / TypeScript", level: 90 },
  { name: "Vue.js", level: 85 },
  { name: "React.js / Next.js", level: 80 },
  { name: "Node.js", level: 75 },
  { name: "Database (PostgreSQL, MongoDB)", level: 70 },
];
</script>