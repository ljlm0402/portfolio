<template>
  <section id="about" class="py-20 bg-gray-800">
    <div class="container mx-auto px-6">
      <div class="max-w-6xl mx-auto">
        <!-- Section Header -->
        <div class="text-center mb-16">
          <h2 class="text-3xl md:text-4xl font-bold mb-4 text-white">소개</h2>
          <p class="text-gray-400 text-lg">저에 대해 더 알아보세요</p>
        </div>

        <div class="grid md:grid-cols-2 gap-12 items-center">
          <!-- Left Column - Text Content -->
          <div>
            <h3 class="text-2xl font-semibold mb-6 text-blue-400">
              안녕하세요! 저는 웹 개발자입니다.
            </h3>

            <div class="space-y-4 text-gray-300 leading-relaxed">
              <p>
                창의적이고 효율적인 웹 애플리케이션을 개발하는 것에 열정을 가진
                웹 개발자입니다. <br />
                사용자 중심의 인터페이스와 견고한 백엔드 시스템을 구축하는 것을
                좋아합니다.
              </p>

              <p>
                최신 기술과 프레임워크를 활용하여 성능이 뛰어나고 확장 가능한
                솔루션을 제공합니다. <br />
                코드 품질과 사용자 경험을 최우선으로 생각하며, 지속적인 학습과
                개선에 노력하고 있습니다.
              </p>

              <p>
                팀워크를 중시하며, 다양한 배경을 가진 동료들과 협업하여 더 나은
                결과를 만들어내는 것을 즐깁니다.
              </p>
            </div>

            <!-- Philosophy -->
            <div class="mt-8">
              <h4 class="text-xl font-semibold text-blue-400 mb-4">
                💡 개발 철학
              </h4>
              <div class="grid grid-cols-2 gap-4">
                <div class="p-4 bg-gray-900 rounded-lg">
                  <div class="flex items-center mb-2">
                    <Icon
                      name="mdi:book-open-variant"
                      class="w-5 h-5 text-blue-400 mr-2"
                    />
                    <div class="text-white font-medium">가독성</div>
                  </div>
                  <div class="text-gray-400 text-sm">
                    읽기 쉽고 유지보수하기 좋은 코드
                  </div>
                </div>
                <div class="p-4 bg-gray-900 rounded-lg">
                  <div class="flex items-center mb-2">
                    <Icon
                      name="mdi:sitemap"
                      class="w-5 h-5 text-purple-400 mr-2"
                    />
                    <div class="text-white font-medium">유연한 구조</div>
                  </div>
                  <div class="text-gray-400 text-sm">
                    확장 가능한 아키텍처 설계
                  </div>
                </div>
                <div class="p-4 bg-gray-900 rounded-lg">
                  <div class="flex items-center mb-2">
                    <Icon
                      name="mdi:lightning-bolt"
                      class="w-5 h-5 text-yellow-400 mr-2"
                    />
                    <div class="text-white font-medium">최신 기술</div>
                  </div>
                  <div class="text-gray-400 text-sm">트렌드의 합리적 도입</div>
                </div>
                <div class="p-4 bg-gray-900 rounded-lg">
                  <div class="flex items-center mb-2">
                    <Icon
                      name="mdi:account-group"
                      class="w-5 h-5 text-green-400 mr-2"
                    />
                    <div class="text-white font-medium">협업과 성장</div>
                  </div>
                  <div class="text-gray-400 text-sm">
                    함께 발전하는 개발 문화
                  </div>
                </div>
              </div>
            </div>

            <!-- 현재 집중 분야 -->
            <div class="mt-8">
              <h4 class="text-xl font-semibold text-blue-400 mb-4">
                🎯 현재 집중 분야
              </h4>
              <div class="flex flex-wrap gap-2">
                <span
                  class="px-3 py-1 bg-blue-900 text-blue-300 rounded-full text-sm"
                  >아키텍처 설계</span
                >
                <span
                  class="px-3 py-1 bg-purple-900 text-purple-300 rounded-full text-sm"
                  >클린 코드</span
                >
                <span
                  class="px-3 py-1 bg-green-900 text-green-300 rounded-full text-sm"
                  >디자인 패턴</span
                >
                <span
                  class="px-3 py-1 bg-yellow-900 text-yellow-300 rounded-full text-sm"
                  >시스템 설계</span
                >
                <span
                  class="px-3 py-1 bg-red-900 text-red-300 rounded-full text-sm"
                  >성능 최적화</span
                >
              </div>
            </div>

            <!-- Stats -->
            <div class="grid grid-cols-2 gap-6 mt-8">
              <div class="text-center p-4 bg-gray-900 rounded-lg">
                <div class="text-3xl font-bold text-blue-400 mb-2">8+</div>
                <div class="text-gray-400">경력 년수</div>
              </div>
              <div class="text-center p-4 bg-gray-900 rounded-lg">
                <div class="text-3xl font-bold text-blue-400 mb-2">6+</div>
                <div class="text-gray-400">개인 프로젝트</div>
              </div>
            </div>
          </div>

          <!-- Right Column - Image/Visual -->
          <div class="text-center">
            <div class="relative">
              <div
                class="w-80 h-80 mx-auto bg-gradient-to-br from-blue-400 to-purple-500 rounded-2xl flex items-center justify-center"
              >
                <Icon name="mdi:code-tags" class="w-32 h-32 text-white" />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>