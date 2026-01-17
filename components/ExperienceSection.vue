<template>
  <section id="experience" class="py-20 bg-gray-50">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="text-center mb-16">
        <h2 class="text-3xl font-bold text-gray-900 mb-4">경력사항</h2>
        <div class="w-20 h-1 bg-blue-600 mx-auto"></div>
      </div>

      <div class="space-y-16">
        <!-- 안랩 (AhnLab) -->
        <div class="company-section">
          <h3 class="text-2xl font-bold text-gray-900 mb-8 text-center">
            안랩 (AhnLab)
          </h3>
          <div class="grid md:grid-cols-2 gap-8">
            <!-- XTD 프로젝트 -->
            <div
              class="project-card bg-white rounded-xl shadow-lg p-6 hover:shadow-xl transition-shadow"
            >
              <div class="mb-4">
                <h4 class="text-xl font-semibold text-blue-600 mb-1">XTD</h4>
                <p class="text-sm text-gray-600 mb-2">
                  OT 가시성 및 위협 탐지 모니터링 솔루션
                </p>
                <p class="text-sm text-gray-500 mb-3">2025.04 ~ 현재</p>
              </div>

              <div class="mb-4">
                <h5 class="font-semibold text-gray-800 mb-2">기술 스택</h5>
                <div class="flex flex-wrap gap-2">
                  <span
                    class="px-3 py-1 bg-blue-100 text-blue-800 rounded-full text-sm"
                    >TypeScript</span
                  >
                  <span
                    class="px-3 py-1 bg-blue-100 text-blue-800 rounded-full text-sm"
                    >React</span
                  >
                  <span
                    class="px-3 py-1 bg-blue-100 text-blue-800 rounded-full text-sm"
                    >Next.js</span
                  >
                  <span
                    class="px-3 py-1 bg-blue-100 text-blue-800 rounded-full text-sm"
                    >Express.js</span
                  >
                  <span
                    class="px-3 py-1 bg-blue-100 text-blue-800 rounded-full text-sm"
                    >MariaDB</span
                  >
                </div>
              </div>

              <div class="mb-4">
                <h5 class="font-semibold text-gray-800 mb-2">주요 역할</h5>
                <p class="text-gray-600 text-sm">
                  프론트엔드 & 백엔드 개발, RESTful API 설계 및 구현
                </p>
              </div>

              <div class="mb-4">
                <h5 class="font-semibold text-gray-800 mb-2">주요 성과</h5>
                <div class="bg-green-50 p-3 rounded-lg">
                  <p class="text-green-800 text-sm font-medium">
                    ⚡ 실시간 토폴로지 성능 30% 개선
                  </p>
                  <p class="text-green-700 text-sm">
                    • 사용자 인터페이스 반응 속도 25% 향상<br />
                    • Turborepo 모노레포 구조로 빌드 시간 40% 단축<br />
                    • 데이터 시각화 렌더링 최적화
                  </p>
                </div>
              </div>

              <div>
                <h5 class="font-semibold text-gray-800 mb-2">설명</h5>
                <ul class="text-gray-600 text-sm space-y-1">
                  <li>• Next.js + Node.js 기반 모니터링 솔루션 구축</li>
                  <li>• Cytoscape, Highcharts 기반 데이터 시각화 구현</li>
                  <li>• Tailwind, pnpm, Turborepo 등 최신 스택 도입</li>
                </ul>
              </div>
            </div>

            <!-- ICM 프로젝트 -->
            <div
              class="project-card bg-white rounded-xl shadow-lg p-6 hover:shadow-xl transition-shadow"
            >
              <div class="mb-4">
                <h4 class="text-xl font-semibold text-blue-600 mb-1">ICM</h4>
                <p class="text-sm text-gray-600 mb-2">
                  CPS 보안 중앙 모니터링 및 통합 관리 시스템
                </p>
                <p class="text-sm text-gray-500 mb-3">2020.03 ~</p>
              </div>

              <div class="mb-4">
                <h5 class="font-semibold text-gray-800 mb-2">기술 스택</h5>
                <div class="flex flex-wrap gap-2">
                  <span
                    class="px-3 py-1 bg-blue-100 text-blue-800 rounded-full text-sm"
                    >JavaScript</span
                  >
                  <span
                    class="px-3 py-1 bg-blue-100 text-blue-800 rounded-full text-sm"
                    >Vue.js</span
                  >
                  <span
                    class="px-3 py-1 bg-blue-100 text-blue-800 rounded-full text-sm"
                    >Express.js</span
                  >
                  <span
                    class="px-3 py-1 bg-blue-100 text-blue-800 rounded-full text-sm"
                    >PostgreSQL</span
                  >
                  <span
                    class="px-3 py-1 bg-blue-100 text-blue-800 rounded-full text-sm"
                    >Kubernetes</span
                  >
                </div>
              </div>

              <div class="mb-4">
                <h5 class="font-semibold text-gray-800 mb-2">주요 역할</h5>
                <p class="text-gray-600 text-sm">
                  풀스택, 아키텍처 설계, DevOps 자동화
                </p>
              </div>

              <div class="mb-4">
                <h5 class="font-semibold text-gray-800 mb-2">주요 성과</h5>
                <div class="bg-blue-50 p-3 rounded-lg">
                  <p class="text-blue-800 text-sm font-medium">
                    🚀 무중단 배포 구축 / 성능 30% 향상
                  </p>
                  <p class="text-blue-700 text-sm">
                    • Kubernetes 기반 컨테이너 오케스트레이션<br />
                    • CI/CD 파이프라인 자동화<br />
                    • 실시간 모니터링 시스템 구축
                  </p>
                </div>
              </div>

              <div>
                <h5 class="font-semibold text-gray-800 mb-2">설명</h5>
                <ul class="text-gray-600 text-sm space-y-1">
                  <li>• Vue.js + Node.js 기반 통합 대시보드 구축</li>
                  <li>• Kubernetes(k3s) 컨테이너 오케스트레이션 설계</li>
                  <li>• 실시간 모니터링 및 데이터 비주얼라이제이션</li>
                </ul>
              </div>
            </div>
          </div>
        </div>

        <!-- 푸딩 (Fooding) -->
        <div class="company-section">
          <h3 class="text-2xl font-bold text-gray-900 mb-8 text-center">
            열두달
          </h3>
          <div class="flex justify-center">
            <div
              class="project-card bg-white rounded-xl shadow-lg p-6 hover:shadow-xl transition-shadow max-w-lg w-full"
            >
              <div class="mb-4">
                <h4 class="text-xl font-semibold text-green-600 mb-1">
                  Fooding
                </h4>
                <p class="text-sm text-gray-600 mb-2">
                  단체음식 배송 플랫폼 서비스
                </p>
                <p class="text-sm text-gray-500 mb-3">
                  2018.10 ~ 2020.03 (1년 6개월)
                </p>
              </div>

              <div class="mb-4">
                <h5 class="font-semibold text-gray-800 mb-2">기술 스택</h5>
                <div class="flex flex-wrap gap-2">
                  <span
                    class="px-3 py-1 bg-green-100 text-green-800 rounded-full text-sm"
                    >TypeScript</span
                  >
                  <span
                    class="px-3 py-1 bg-green-100 text-green-800 rounded-full text-sm"
                    >Angular</span
                  >
                  <span
                    class="px-3 py-1 bg-green-100 text-green-800 rounded-full text-sm"
                    >Express.js</span
                  >
                  <span
                    class="px-3 py-1 bg-green-100 text-green-800 rounded-full text-sm"
                    >MySQL</span
                  >
                  <span
                    class="px-3 py-1 bg-green-100 text-green-800 rounded-full text-sm"
                    >AWS</span
                  >
                  <span
                    class="px-3 py-1 bg-green-100 text-green-800 rounded-full text-sm"
                    >GitHub</span
                  >
                </div>
              </div>

              <div class="mb-4">
                <h5 class="font-semibold text-gray-800 mb-2">주요 역할</h5>
                <p class="text-gray-600 text-sm">
                  프론트/백엔드, 아키텍처 설계, 클라우드 인프라 구축
                </p>
              </div>

              <div class="mb-4">
                <h5 class="font-semibold text-gray-800 mb-2">주요 성과</h5>
                <div class="bg-purple-50 p-3 rounded-lg">
                  <p class="text-purple-800 text-sm font-medium">
                    ☁️ ECS 기반 자동 배포 구축
                  </p>
                  <p class="text-purple-700 text-sm">
                    • 서비스 가용성 99.9% 달성<br />
                    • CI/CD 파이프라인 완전 자동화<br />
                    • 실시간 모니터링 & 자동 알림 시스템
                  </p>
                </div>
              </div>

              <div>
                <h5 class="font-semibold text-gray-800 mb-2">설명</h5>
                <ul class="text-gray-600 text-sm space-y-1">
                  <li>• Angular + Express.js 기반 플랫폼 구축</li>
                  <li>• AWS ECS + CodePipeline 기반 CI/CD 파이프라인 설계</li>
                  <li>• 카카오톡 + SMS 알림 서비스 연동</li>
                </ul>
              </div>
            </div>
          </div>
        </div>

        <!-- 씨큐프라임 -->
        <div class="company-section">
          <h3 class="text-2xl font-bold text-gray-900 mb-8 text-center">
            씨큐프라임 (SECUPRIME)
          </h3>
          <div class="flex justify-center">
            <div
              class="project-card bg-white rounded-xl shadow-lg p-6 hover:shadow-xl transition-shadow max-w-lg w-full"
            >
              <div class="mb-4">
                <h4 class="text-xl font-semibold text-purple-600 mb-1">
                  E-MORDER KIOSK
                </h4>
                <p class="text-sm text-gray-600 mb-2">
                  All-In-One 무인 결제 키오스크
                </p>
                <p class="text-sm text-gray-500 mb-3">
                  2017.12 ~ 2018.10 (10개월)
                </p>
              </div>

              <div class="mb-4">
                <h5 class="font-semibold text-gray-800 mb-2">기술 스택</h5>
                <div class="flex flex-wrap gap-2">
                  <span
                    class="px-3 py-1 bg-purple-100 text-purple-800 rounded-full text-sm"
                    >JavaScript</span
                  >
                  <span
                    class="px-3 py-1 bg-purple-100 text-purple-800 rounded-full text-sm"
                    >Express.js</span
                  >
                  <span
                    class="px-3 py-1 bg-purple-100 text-purple-800 rounded-full text-sm"
                    >MariaDB</span
                  >
                </div>
              </div>

              <div class="mb-4">
                <h5 class="font-semibold text-gray-800 mb-2">주요 역할</h5>
                <p class="text-gray-600 text-sm">
                  풀스택 개발, 시스템 설계 및 구현
                </p>
              </div>

              <div class="mb-4">
                <h5 class="font-semibold text-gray-800 mb-2">주요 성과</h5>
                <div class="bg-yellow-50 p-3 rounded-lg">
                  <p class="text-yellow-800 text-sm font-medium">
                    🎯 POS 연동 재고·정산 자동화 시스템
                  </p>
                  <p class="text-yellow-700 text-sm">
                    • Serial 통신 기반 결제 모듈 개발<br />
                    • 설치형 무중단 서비스 안정성 확보<br />
                    • 실시간 재고 관리 및 자동 정산
                  </p>
                </div>
              </div>

              <div>
                <h5 class="font-semibold text-gray-800 mb-2">설명</h5>
                <ul class="text-gray-600 text-sm space-y-1">
                  <li>• Web 기반 KIOSK 서비스 개발</li>
                  <li>• 카드리더기·POS기 Serial 통신 결제 모듈</li>
                  <li>• 재고 및 정산 통합 자동화</li>
                  <li>• 설치형(On-Premise) 무중단 서비스 운영</li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
// 필요한 경우 여기에 스크립트 로직을 추가할 수 있습니다
</script>

<style scoped>
.company-section {
  position: relative;
}

.project-card {
  border-top: 4px solid transparent;
  transition: all 0.3s ease;
}

.company-section:nth-child(1) .project-card {
  border-top-color: #3b82f6; /* blue-500 */
}

.company-section:nth-child(2) .project-card {
  border-top-color: #10b981; /* green-500 */
}

.company-section:nth-child(3) .project-card {
  border-top-color: #8b5cf6; /* purple-500 */
}

.project-card:hover {
  transform: translateY(-2px);
}

@media (max-width: 768px) {
  .project-card {
    margin-bottom: 1rem;
  }
}
</style>
