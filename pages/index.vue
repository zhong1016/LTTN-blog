<script setup lang="ts">
useHead({
  title: '聆夜',
  meta: [
    {
      name: 'description',
      content: 'LTTN-Blog about coding note , such as Java JavaScript Golang',
    },
    { name: 'author', content: '聆夜' },
  ],
});
</script>
<template>
  <div class="bg-slate-50 h-[calc(100vh-66px)]">
    <main class="container mx-auto h-full">
      <div class="flex items-center justify-center h-1/3">
        <div>
          <h1 class="text-center font-black text-6xl text-slate-700">
            Welcome to
          </h1>
          <h1 class="text-center font-black text-5xl text-slate-700">
            <span class="text-red-400">L</span>isten
            <span class="text-red-400">T</span>o
            <span class="text-red-400">T</span>he
            <span class="text-red-400">N</span>ight blog
          </h1>
        </div>
      </div>
      <div class="flex justify-center h-2/3">
        <div>
          <div class="flex justify-center">
            <img
              class="h-48 w-48 rounded-full"
              src="@/assets/img/ming.jpg"
              alt="profile"
            />
          </div>

          <div class="mt-8">
            <p class="text-center text-slate-700 text-lg font-bold">
              Hello ! 我是Ming
              <br />
              以前常使用 <span class="text-red-400">聆夜</span> 這個網名
              <br />
              因此 <span class="text-red-400">LTTN</span> 就誕生了 !
              記錄我的技術筆記 XD
              <br />
            </p>

            <p class="text-center text-slate-700 text-xl font-bold mt-2">
              Take a look at
              <NuxtLink class="text-blue-400" to="/blog">my blog</NuxtLink>
            </p>
            <div class="flex justify-center mt-4">
              <div class="w-1/3 justify-center items-center flex">
                <a
                  href="https://www.facebook.com/profile.php?id=100002257212698"
                  target="_blank"
                >
                  <img
                    class="w-10 h-10"
                    src="@/assets/img/Facebook.svg"
                    alt=""
                  />
                </a>
              </div>
              <div class="w-1/3 justify-center items-center flex">
                <a href="https://www.instagram.com/zhong1016" target="_blank">
                  <img
                    class="w-10 h-10"
                    src="@/assets/img/Instagram.svg"
                    alt="instagram"
                  />
                </a>
              </div>
              <div class="w-1/3 justify-center items-center flex">
                <a
                  href="https://github.com/zhong1016/LTTN-blog"
                  target="_blank"
                >
                  <img
                    class="w-10 h-10"
                    src="@/assets/img/Github.svg"
                    alt="github"
                  />
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </main>
  </div>
</template>
