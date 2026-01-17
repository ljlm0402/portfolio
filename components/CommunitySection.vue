<template>
  <section id="community" class="py-20 bg-gray-800">
    <div class="container mx-auto px-6">
      <div class="max-w-6xl mx-auto">
        <!-- Section Header -->
        <div class="text-center mb-16">
          <h2 class="text-3xl md:text-4xl font-bold mb-4 text-white">
            커뮤니티 활동
          </h2>
          <p class="text-gray-400 text-lg">개발 커뮤니티 기여 및 멘토링 활동</p>
        </div>

        <!-- Activity Grid -->
        <div class="grid md:grid-cols-3 gap-8 mb-12">
          <!-- Facebook Groups -->
          <div
            class="bg-gray-900 rounded-xl p-8 hover:bg-gray-850 transition-colors"
          >
            <div class="text-center mb-6">
              <div
                class="w-16 h-16 mx-auto bg-blue-500 rounded-lg flex items-center justify-center mb-4"
              >
                <Icon name="mdi:facebook" class="w-8 h-8 text-white" />
              </div>
              <h3 class="text-xl font-semibold text-white mb-2">
                Facebook 그룹 운영
              </h3>
              <p class="text-gray-400">개발 지식 공유 커뮤니티</p>
            </div>

            <div class="space-y-4">
              <a
                href="https://www.facebook.com/groups/765872100510405/"
                target="_blank"
                class="flex items-center space-x-3 p-3 rounded-lg bg-gray-800 hover:bg-gray-700 transition-colors group"
              >
                <Icon name="mdi:facebook" class="w-6 h-6 text-blue-500" />
                <div class="flex-1">
                  <div class="text-white font-medium">DEVLOG</div>
                  <div class="text-gray-400 text-sm">개발자 커뮤니티 그룹</div>
                </div>
                <Icon
                  name="mdi:arrow-right"
                  class="w-5 h-5 text-gray-500 group-hover:text-blue-400 transition-colors"
                />
              </a>

              <a
                href="https://www.facebook.com/groups/smcoding/"
                target="_blank"
                class="flex items-center space-x-3 p-3 rounded-lg bg-gray-800 hover:bg-gray-700 transition-colors group"
              >
                <Icon name="mdi:facebook" class="w-6 h-6 text-blue-500" />
                <div class="flex-1">
                  <div class="text-white font-medium">실무코딩</div>
                  <div class="text-gray-400 text-sm">실무 개발 지식 공유</div>
                </div>
                <Icon
                  name="mdi:arrow-right"
                  class="w-5 h-5 text-gray-500 group-hover:text-blue-400 transition-colors"
                />
              </a>
            </div>
          </div>

          <!-- Boostcamp Mentoring -->
          <div
            class="bg-gray-900 rounded-xl p-8 hover:bg-gray-850 transition-colors"
          >
            <div class="text-center mb-6">
              <div
                class="w-16 h-16 mx-auto bg-purple-500 rounded-lg flex items-center justify-center mb-4"
              >
                <Icon name="mdi:school" class="w-8 h-8 text-white" />
              </div>
              <h3 class="text-xl font-semibold text-white mb-2">
                부스트캠프 멘토
              </h3>
              <p class="text-gray-400">개발자 성장 멘토링</p>
            </div>

            <div class="space-y-3">
              <a
                href="https://github.com/boostcampwm-2022"
                target="_blank"
                class="flex items-center justify-between p-3 rounded-lg bg-gray-800 hover:bg-gray-700 transition-colors group"
              >
                <div class="flex items-center space-x-3">
                  <Icon name="mdi:github" class="w-5 h-5 text-gray-400" />
                  <span class="text-white">웹·모바일 7기</span>
                </div>
                <span
                  class="px-2 py-1 bg-purple-600 text-white text-xs rounded-full"
                  >2022</span
                >
              </a>

              <a
                href="https://github.com/boostcampwm2023"
                target="_blank"
                class="flex items-center justify-between p-3 rounded-lg bg-gray-800 hover:bg-gray-700 transition-colors group"
              >
                <div class="flex items-center space-x-3">
                  <Icon name="mdi:github" class="w-5 h-5 text-gray-400" />
                  <span class="text-white">웹·모바일 8기</span>
                </div>
                <span
                  class="px-2 py-1 bg-purple-600 text-white text-xs rounded-full"
                  >2023</span
                >
              </a>

              <a
                href="https://github.com/boostcampwm-2024"
                target="_blank"
                class="flex items-center justify-between p-3 rounded-lg bg-gray-800 hover:bg-gray-700 transition-colors group"
              >
                <div class="flex items-center space-x-3">
                  <Icon name="mdi:github" class="w-5 h-5 text-gray-400" />
                  <span class="text-white">웹·모바일 9기</span>
                </div>
                <span
                  class="px-2 py-1 bg-purple-600 text-white text-xs rounded-full"
                  >2024</span
                >
              </a>
            </div>
          </div>

          <!-- Beta Reading -->
          <div
            class="bg-gray-900 rounded-xl p-8 hover:bg-gray-850 transition-colors"
          >
            <div class="text-center mb-6">
              <div
                class="w-16 h-16 mx-auto bg-green-500 rounded-lg flex items-center justify-center mb-4"
              >
                <Icon
                  name="mdi:book-open-page-variant"
                  class="w-8 h-8 text-white"
                />
              </div>
              <h3 class="text-xl font-semibold text-white mb-2">베타리딩</h3>
              <p class="text-gray-400">기술 서적 검토 참여</p>
            </div>

            <div class="space-y-4">
              <a
                href="https://www.yes24.com/Product/Goods/133974034"
                target="_blank"
                class="block p-3 rounded-lg bg-gray-800 hover:bg-gray-700 transition-colors group"
              >
                <div class="flex items-start space-x-3">
                  <Icon name="mdi:book" class="w-5 h-5 text-green-400 mt-1" />
                  <div class="flex-1">
                    <div class="text-white font-medium">러닝 Vue.js</div>
                    <div class="text-gray-400 text-sm">베타리딩 참여</div>
                  </div>
                  <Icon
                    name="mdi:external-link"
                    class="w-4 h-4 text-gray-500 group-hover:text-green-400 transition-colors"
                  />
                </div>
              </a>

              <a
                href="https://www.yes24.com/product/goods/91213376"
                target="_blank"
                class="block p-3 rounded-lg bg-gray-800 hover:bg-gray-700 transition-colors group"
              >
                <div class="flex items-start space-x-3">
                  <Icon name="mdi:book" class="w-5 h-5 text-green-400 mt-1" />
                  <div class="flex-1">
                    <div class="text-white font-medium">
                      Node.js 교과서 개정 2판
                    </div>
                    <div class="text-gray-400 text-sm">베타리딩 참여</div>
                  </div>
                  <Icon
                    name="mdi:external-link"
                    class="w-4 h-4 text-gray-500 group-hover:text-green-400 transition-colors"
                  />
                </div>
              </a>
            </div>
          </div>
        </div>

        <!-- 개발 외 활동 섹션 -->
        <div class="mt-12">
          <h3 class="text-2xl font-semibold text-white mb-8 text-center">
            ✨ 개발 외 활동
          </h3>
          <div class="grid md:grid-cols-4 gap-6">
            <div
              class="bg-gray-900 rounded-xl p-6 hover:bg-gray-850 transition-colors text-center"
            >
              <Icon
                name="mdi:book"
                class="w-12 h-12 mx-auto text-blue-400 mb-3"
              />
              <h4 class="text-white font-medium mb-2">📚 기술 서적 독서</h4>
              <p class="text-gray-400 text-sm">최신 기술 트렌드 학습</p>
            </div>
            <div
              class="bg-gray-900 rounded-xl p-6 hover:bg-gray-850 transition-colors text-center"
            >
              <Icon
                name="mdi:pencil"
                class="w-12 h-12 mx-auto text-green-400 mb-3"
              />
              <h4 class="text-white font-medium mb-2">✍️ 기술 블로그 작성</h4>
              <p class="text-gray-400 text-sm">지식 공유 및 기록</p>
            </div>
            <div
              class="bg-gray-900 rounded-xl p-6 hover:bg-gray-850 transition-colors text-center"
            >
              <Icon
                name="mdi:microphone"
                class="w-12 h-12 mx-auto text-purple-400 mb-3"
              />
              <h4 class="text-white font-medium mb-2">🎤 컨퍼런스 참여</h4>
              <p class="text-gray-400 text-sm">개발자 네트워킹</p>
            </div>
            <div
              class="bg-gray-900 rounded-xl p-6 hover:bg-gray-850 transition-colors text-center"
            >
              <Icon
                name="mdi:forum"
                class="w-12 h-12 mx-auto text-yellow-400 mb-3"
              />
              <h4 class="text-white font-medium mb-2">💬 개발 커뮤니티</h4>
              <p class="text-gray-400 text-sm">활발한 소통과 기여</p>
            </div>
          </div>
        </div>

        <!-- Stats Summary -->
        <div class="grid grid-cols-3 gap-6 mt-12">
          <div class="text-center p-6 bg-gray-900 rounded-xl">
            <div class="text-3xl font-bold text-blue-400 mb-2">2</div>
            <div class="text-gray-400">커뮤니티 그룹</div>
          </div>
          <div class="text-center p-6 bg-gray-900 rounded-xl">
            <div class="text-3xl font-bold text-purple-400 mb-2">3</div>
            <div class="text-gray-400">멘토링 활동</div>
          </div>
          <div class="text-center p-6 bg-gray-900 rounded-xl">
            <div class="text-3xl font-bold text-green-400 mb-2">2</div>
            <div class="text-gray-400">베타리딩</div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

