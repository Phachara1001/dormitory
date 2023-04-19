<template>
  <section class="flex-row items-center justify-center pt-4 h-screen">
    <div class="w-full max-w-screen-xl px-4 mx-auto lg:px-12">
      <!-- start coding -->
      <br>
      <div class="flex-row items-center justify-end bg-gray-400 text-xl p-4 space-y-3 sm:flex sm:space-y-0 sm:space-x-4">
        <div class="w-50">
          <select id="countries"
            class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full h-14 p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500">
            <option selected>ประเภทห้องพัก</option>
            <option value="US">ห้องแอร์</option>
            <option value="CA">ห้องพัดลม</option>
            <option value="FR">ห้องสูท</option>
          </select>
        </div>
        <div class="w-70">
          <form>
            <div class="relative">
              <div class="absolute inset-y-0 left-0 flex items-center pl-3 pointer-events-none">
                <svg aria-hidden="true" class="w-5 h-5 text-gray-500 dark:text-gray-400" fill="none" stroke="currentColor"
                  viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                    d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path>
                </svg>
              </div>
              <input type="search" id="default-search"
                class="block w-full p-4 pl-10 text-sm text-gray-900 border border-gray-300 rounded-lg bg-gray-50 focus:ring-blue-500 focus:border-blue-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                placeholder="ค้นหาหมายเลขห้อง" required>
            </div>
          </form>
        </div>
        <div class="w-50">
          <button type="button" class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800">ค้นหา</button>
        </div>
      </div>
      <br>
      <div
        class="flex-row items-center justify-end bg-gray-400 text-xl p-4 space-y-3 sm:flex sm:space-y-0 sm:space-x-4 h-16">
        <div class=" w-full h-16 bg-gray  border-gray-200 dark:bg-gray-700 dark:border-gray-600">
          <div class="grid h-full w-175 max-w-lg grid-cols-4 mx-auto font-medium">
            <button type="button"
              class="inline-flex flex-col items-center justify-center px-5 hover:bg-gray-50 dark:hover:bg-gray-800 group">
              <span
                class="text-sm text-black-500 dark:text-gray-400 group-hover:text-green-600 dark:group-hover:text-blue-500">ห้องทั้งหมด</span>
            </button>
            <button type="button"
              class="inline-flex flex-col items-center justify-center px-5 hover:bg-gray-50 dark:hover:bg-gray-800 group">
              <span
                class="text-sm text-black-500 dark:text-gray-400 group-hover:text-green-600 dark:group-hover:text-blue-500">ห้องว่าง</span>
            </button>
            <button type="button"
              class="inline-flex flex-col items-center justify-center px-5 hover:bg-gray-50 dark:hover:bg-gray-800 group">
              <span
                class="text-sm text-black-500 dark:text-gray-400 group-hover:text-green-600 dark:group-hover:text-blue-500">จองแล้ว</span>
            </button>
            <button type="button"
              class="inline-flex flex-col items-center justify-center px-5 hover:bg-gray-50 dark:hover:bg-white-800 group">
              <span
                class="text-sm text-black-500 dark:text-gray-400 group-hover:text-green-600 dark:group-hover:text-blue-500">ค้างชำระ</span>
            </button>
          </div>
        </div>
      </div>
      <br>
      <div
        class="flex-row items-center justify-end bg-gray-400 text-xl p-4 space-y-3 sm:flex sm:space-y-0 sm:space-x-4 text-white">
        <h5 class="mr-3 font-semibold dark:text-white">ห้องพักทั้งหมด</h5>
      </div>
      <br>
      <div class="flex items-center justify-center h-80 px-5 py-5">
        <div class="grid grid-cols-3 md:grid-cols-4 gap-4 w-400">
          <a href="roomdetail" class="block w-full rounded-lg bg-white border border-gray-200 p-6">
            <h5 class="mb-2  font-bold tracking-tight text-gray-900 dark:text-white">ห้อง : 101</h5>
            <button type="button" class="text-gray-900 bg-white border border-gray-300 focus:outline-none hover:bg-gray-100 focus:ring-4 focus:ring-gray-200 font-medium rounded-full text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-gray-800 dark:text-white dark:border-gray-600 dark:hover:bg-gray-700 dark:hover:border-gray-600 dark:focus:ring-gray-700">ห้องว่าง</button>
            <h5 class="mb-2   tracking-tight text-green-600 dark:text-white">ประเภทห้องพัก : ห้องสูท</h5>
          </a>
          <a href="roomdetail" class="block w-full rounded-lg bg-white border border-gray-200 p-6">
            <h5 class="mb-2  font-bold tracking-tight text-gray-900 dark:text-white">ห้อง : 102</h5>
            <button type="button" class="text-white bg-green-700 hover:bg-green-800 focus:outline-none focus:ring-4 focus:ring-green-300 font-medium rounded-full text-sm px-5 py-2.5 text-center mr-2 mb-2 dark:bg-green-600 dark:hover:bg-green-700 dark:focus:ring-green-800">ชำระแล้ว</button>
            <h5 class="mb-2   tracking-tight text-green-600 dark:text-white">ประเภทห้องพัก : ห้องสูท</h5>
          </a>
          <a href="roomdetail" class="block w-full rounded-lg bg-white border border-gray-200 p-6">
            <h5 class="mb-2  font-bold tracking-tight text-gray-900 dark:text-white">ห้อง : 103</h5>
            <button type="button" class="text-white bg-purple-700 hover:bg-purple-800 focus:outline-none focus:ring-4 focus:ring-purple-300 font-medium rounded-full text-sm px-5 py-2.5 text-center mb-2 dark:bg-purple-600 dark:hover:bg-purple-700 dark:focus:ring-purple-900">รอย้ายออก</button>
            <h5 class="mb-2   tracking-tight text-green-600 dark:text-white">ประเภทห้องพัก : ห้องแอร์</h5>
          </a>
          <a href="roomdetail" class="block w-full rounded-lg bg-white border border-gray-200 p-6">
            <h5 class="mb-2  font-bold tracking-tight text-gray-900 dark:text-white">ห้อง : 104</h5>
            <button type="button" class="text-white bg-red-700 hover:bg-red-800 focus:outline-none focus:ring-4 focus:ring-red-300 font-medium rounded-full text-sm px-5 py-2.5 text-center mr-2 mb-2 dark:bg-red-600 dark:hover:bg-red-700 dark:focus:ring-red-900">ค้างชำระ</button>
            <h5 class="mb-2   tracking-tight text-green-600 dark:text-white">ประเภทห้องพัก : ห้องแอร์</h5>
          </a>
          <a href="roomdetail" class="block w-full rounded-lg bg-white border border-gray-200 p-6">
            <h5 class="mb-2  font-bold tracking-tight text-gray-900 dark:text-white">ห้อง : 105</h5>
            <button type="button" class="text-gray-900 bg-white border border-gray-300 focus:outline-none hover:bg-gray-100 focus:ring-4 focus:ring-gray-200 font-medium rounded-full text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-gray-800 dark:text-white dark:border-gray-600 dark:hover:bg-gray-700 dark:hover:border-gray-600 dark:focus:ring-gray-700">ห้องว่าง</button>
            <h5 class="mb-2   tracking-tight text-green-600 dark:text-white">ประเภทห้องพัก : ห้องพัดลม</h5>
          </a>
          <a href="roomdetail" class="block w-full rounded-lg bg-white border border-gray-200 p-6">
            <h5 class="mb-2  font-bold tracking-tight text-gray-900 dark:text-white">ห้อง : 106</h5>
            <button type="button" class="text-white bg-yellow-400 hover:bg-yellow-500 focus:outline-none focus:ring-4 focus:ring-yellow-300 font-medium rounded-full text-sm px-5 py-2.5 text-center mr-2 mb-2 dark:focus:ring-yellow-900">จองแล้ว</button>
            <h5 class="mb-2   tracking-tight text-green-600 dark:text-white">ประเภทห้องพัก : ห้องพัดลม</h5>
          </a>
        </div>

      </div>
      <!-- end coding -->
    </div>
</section></template>