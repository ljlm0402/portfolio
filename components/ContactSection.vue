<template>
  <section id="contact" class="py-20 bg-gray-900">
    <div class="container mx-auto px-6">
      <div class="max-w-6xl mx-auto">
        <!-- Section Header -->
        <div class="text-center mb-16">
          <h2 class="text-3xl md:text-4xl font-bold mb-4 text-white">
            연락하기
          </h2>
          <p class="text-gray-400 text-lg">
            프로젝트나 협업에 대해 이야기해보세요
          </p>
        </div>

        <div class="grid md:grid-cols-2 gap-12">
          <!-- Contact Information -->
          <div>
            <h3 class="text-2xl font-semibold text-white mb-6">연락 정보</h3>
            <p class="text-gray-300 mb-8 leading-relaxed">
              새로운 프로젝트나 협업 기회에 대해 언제든지 연락주세요. 창의적인
              아이디어를 함께 현실로 만들어보아요!
            </p>

            <!-- Contact Items -->
            <div class="space-y-6">
              <div class="flex items-center space-x-4">
                <div
                  class="w-12 h-12 bg-blue-500 rounded-lg flex items-center justify-center"
                >
                  <Icon name="mdi:email" class="w-6 h-6 text-white" />
                </div>
                <div>
                  <h4 class="text-white font-semibold">이메일</h4>
                  <p class="text-gray-400">example@email.com</p>
                </div>
              </div>

              <div class="flex items-center space-x-4">
                <div
                  class="w-12 h-12 bg-green-500 rounded-lg flex items-center justify-center"
                >
                  <Icon name="mdi:phone" class="w-6 h-6 text-white" />
                </div>
                <div>
                  <h4 class="text-white font-semibold">전화번호</h4>
                  <p class="text-gray-400">+82 10-1234-5678</p>
                </div>
              </div>

              <div class="flex items-center space-x-4">
                <div
                  class="w-12 h-12 bg-purple-500 rounded-lg flex items-center justify-center"
                >
                  <Icon name="mdi:map-marker" class="w-6 h-6 text-white" />
                </div>
                <div>
                  <h4 class="text-white font-semibold">위치</h4>
                  <p class="text-gray-400">서울, 대한민국</p>
                </div>
              </div>
            </div>

            <!-- Social Links -->
            <div class="mt-8">
              <h4 class="text-white font-semibold mb-4">소셜 미디어</h4>
              <div class="flex space-x-4">
                <a
                  href="#"
                  class="w-10 h-10 bg-gray-800 rounded-lg flex items-center justify-center hover:bg-blue-500 transition-colors"
                >
                  <Icon name="mdi:github" class="w-5 h-5 text-white" />
                </a>
                <a
                  href="#"
                  class="w-10 h-10 bg-gray-800 rounded-lg flex items-center justify-center hover:bg-blue-500 transition-colors"
                >
                  <Icon name="mdi:linkedin" class="w-5 h-5 text-white" />
                </a>
                <a
                  href="#"
                  class="w-10 h-10 bg-gray-800 rounded-lg flex items-center justify-center hover:bg-blue-500 transition-colors"
                >
                  <Icon name="mdi:twitter" class="w-5 h-5 text-white" />
                </a>
                <a
                  href="#"
                  class="w-10 h-10 bg-gray-800 rounded-lg flex items-center justify-center hover:bg-blue-500 transition-colors"
                >
                  <Icon name="mdi:instagram" class="w-5 h-5 text-white" />
                </a>
              </div>
            </div>
          </div>

          <!-- Contact Form -->
          <div class="bg-gray-800 rounded-xl p-8">
            <h3 class="text-2xl font-semibold text-white mb-6">
              메시지 보내기
            </h3>

            <form @submit.prevent="submitForm" class="space-y-6">
              <div class="grid md:grid-cols-2 gap-4">
                <div>
                  <label
                    for="name"
                    class="block text-sm font-medium text-gray-300 mb-2"
                    >이름</label
                  >
                  <input
                    type="text"
                    id="name"
                    v-model="form.name"
                    class="w-full px-4 py-3 bg-gray-700 border border-gray-600 rounded-lg text-white focus:outline-none focus:ring-2 focus:ring-blue-400 focus:border-transparent"
                    placeholder="당신의 이름"
                    required
                  />
                </div>
                <div>
                  <label
                    for="email"
                    class="block text-sm font-medium text-gray-300 mb-2"
                    >이메일</label
                  >
                  <input
                    type="email"
                    id="email"
                    v-model="form.email"
                    class="w-full px-4 py-3 bg-gray-700 border border-gray-600 rounded-lg text-white focus:outline-none focus:ring-2 focus:ring-blue-400 focus:border-transparent"
                    placeholder="your@email.com"
                    required
                  />
                </div>
              </div>

              <div>
                <label
                  for="subject"
                  class="block text-sm font-medium text-gray-300 mb-2"
                  >제목</label
                >
                <input
                  type="text"
                  id="subject"
                  v-model="form.subject"
                  class="w-full px-4 py-3 bg-gray-700 border border-gray-600 rounded-lg text-white focus:outline-none focus:ring-2 focus:ring-blue-400 focus:border-transparent"
                  placeholder="메시지 제목"
                  required
                />
              </div>

              <div>
                <label
                  for="message"
                  class="block text-sm font-medium text-gray-300 mb-2"
                  >메시지</label
                >
                <textarea
                  id="message"
                  v-model="form.message"
                  rows="6"
                  class="w-full px-4 py-3 bg-gray-700 border border-gray-600 rounded-lg text-white focus:outline-none focus:ring-2 focus:ring-blue-400 focus:border-transparent resize-none"
                  placeholder="메시지를 입력하세요..."
                  required
                ></textarea>
              </div>

              <button
                type="submit"
                :disabled="isSubmitting"
                class="w-full px-6 py-3 bg-blue-500 hover:bg-blue-600 disabled:bg-blue-400 text-white font-semibold rounded-lg transition-colors flex items-center justify-center"
              >
                <Icon
                  v-if="isSubmitting"
                  name="mdi:loading"
                  class="w-5 h-5 mr-2 animate-spin"
                />
                <Icon v-else name="mdi:send" class="w-5 h-5 mr-2" />
                {{ isSubmitting ? "전송 중..." : "메시지 보내기" }}
              </button>
            </form>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
const form = ref({
  name: "",
  email: "",
  subject: "",
  message: "",
});

const isSubmitting = ref(false);

const submitForm = async () => {
  isSubmitting.value = true;

  // Simulate form submission
  setTimeout(() => {
    alert("메시지가 성공적으로 전송되었습니다!");
    // Reset form
    form.value = {
      name: "",
      email: "",
      subject: "",
      message: "",
    };
    isSubmitting.value = false;
  }, 2000);
};
</script>