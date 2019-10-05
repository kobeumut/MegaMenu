<template>
  <div class="relative">
    <button
      href="#"
      class="text-sm pr-2 pl-2 shadow-sm font-semibold"
      @click="toggleVisibility">
      DROP DOWN
    </button>
    <div>
      <ul v-if="isVisible" class="absolute normal-case z-30 font-normal xs:left-0 lg:right-0 bg-white shadow overflow-hidden rounded w-48 border mt-2 py-1 lg:z-20">
        <li>
          <a
            href="#"
            class="flex items-center px-3 py-3 hover:bg-gray-200">
            <span class="ml-2">Option1</span>
          </a>
        </li>
        <li>
          <a
            href="#"
            class="flex items-center px-3 py-3 hover:bg-gray-200">
            <span class="ml-2">Option2</span>
          </a>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      isVisible: false,
    }
  },
  methods: {
    toggleVisibility() {
      this.isVisible = !this.isVisible
    },
  }
}
</script>