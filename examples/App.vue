<template>
  <div id="app" class="antialiased text-gray-900 flex flex-col min-h-screen bg-gray-100">
    <router-view class="flex-1" />
    <div class="flex-shrink-0 py-12 text-center">
      <div>
        <router-link class="font-semibold text-gray-700 hover:underline" to="/">Home</router-link>
        <span class="mx-4 text-gray-500">|</span>

        <router-link class="font-semibold text-gray-700 hover:underline" :to="{name: 'vacation-notify'}">Vacation Notify</router-link>
        <span class="mx-4 text-gray-500">|</span>

        <router-link class="font-semibold text-gray-700 hover:underline" :to="{name: 'foreign-account'}">Account</router-link>
        <span class="mx-4 text-gray-500">|</span>

        <router-link class="font-semibold text-gray-700 hover:underline" :to="{name: 'foreign-real-account'}">Real Account</router-link>
        <span class="mx-4 text-gray-500">|</span>

        <router-link class="font-semibold text-gray-700 hover:underline" :to="{name: 'foreign-demo-account'}">Demo Account</router-link>
        <span class="mx-4 text-gray-500">|</span>

        <router-link class="font-semibold text-gray-700 hover:underline" :to="{name: 'foreign-login-account'}">Login Account</router-link>
      </div>
      <div class="mt-2">
        <a target="_blank" href="https://github.com/curder/ava-vue-components" class="text-sm font-semibold text-gray-600 hover:underline">Source on GitHub</a>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "app",
  components: {}
};

</script>
