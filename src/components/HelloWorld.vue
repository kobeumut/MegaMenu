<template>
<div class="bg-gray-300">
  <div class="mx-auto flex items-center py-3 justify-around bg-gray-200
text-teal-800 shadow-md">
      <ul class="lg:list-none lg:block hidden table-row ">
        <li class="table-cell border-solid border-r border-gray-400 "><a href="" class="text-sm pr-2 pl-2 shadow-sm"><i
              class="fa fa-home fa-lg"></i></a></li>
        <li class="table-cell pl-5 pr-5 border-solid border-r border-gray-400 "><a href=""
            class="text-sm pr-2 pl-2 shadow-sm font-semibold">PORTALLAR</a></li>
        <li class="table-cell pl-5 pr-5 border-solid border-r border-gray-400 "><a href=""
            class="text-sm pr-2 pl-2 shadow-sm font-semibold">HIZLI MENU</a></li>
        <li class="table-cell pl-5 pr-5 border-solid border-r border-gray-400 "><a href=""
            class="text-sm pr-2 pl-2 shadow-sm font-semibold">HIZLI MENU</a></li>
        <li class="table-cell pl-5 pr-5 border-solid border-r border-gray-400 "><a href=""
            class="text-sm pr-2 pl-2 shadow-sm font-semibold">HIZLI MENU</a></li>
        <li class="table-cell pl-5 pr-5 border-solid border-r border-gray-400 "><a href=""
            class="text-sm pr-2 pl-2 shadow-sm font-semibold">HIZLI MENU</a></li>
      </ul>
    <div class="block lg:hidden">
      <button class="flex items-center px-3 py-2 border rounded text-teal-900 border-teal-900 hover:text-white hover:border-white">
        <svg class="fill-current h-3 w-3" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><title>Menu</title><path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"/></svg>
      </button>
    </div>

  </div>
</div>

</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}

