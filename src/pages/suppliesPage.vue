<template>
    <!-- Main modal -->
    <div>
        <div class="relative p-4 w-full max-w-2xl h-full md:h-auto">
            <!-- Modal content -->
            <div class="relative p-4 bg-white rounded-lg shadow dark:bg-gray-800 sm:p-5">
                <!-- Modal header -->
                
                    <div class="flex items-center space-x-4">
                        <button type="button" class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800">พัสดุค้างจำหน่าย</button>
                        <button type="button" class="text-gray-900 bg-white border border-gray-300 focus:outline-none hover:bg-gray-100 focus:ring-4 focus:ring-gray-200 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-gray-800 dark:text-white dark:border-gray-600 dark:hover:bg-gray-700 dark:hover:border-gray-600 dark:focus:ring-gray-700">พัสดุที่จำหน่ายแล้ว</button>
                        <button type="button" class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800">เพิ่มพัสดุ</button>
                    </div>
                    
                    <form>   
                        <label for="default-search" class="mb-2 text-sm font-medium text-gray-900 sr-only dark:text-white">Search</label>
                        <div class="relative">
                            <div class="absolute inset-y-0 left-0 flex items-center pl-3 pointer-events-none">
                                <svg aria-hidden="true" class="w-5 h-5 text-gray-500 dark:text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path></svg>
                            </div>
                            <input type="search" id="default-search" class="block w-full p-4 pl-10 text-sm text-gray-900 border border-gray-300 rounded-lg bg-gray-50 focus:ring-blue-500 focus:border-blue-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500" placeholder="ค้นหา ชื่อผู้รับ/ชื่อห้อง/เลขพัสดุ" required>
                            <button type="submit" class="text-white absolute right-2.5 bottom-2.5 bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-4 py-2 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">ค้นหาพัสดุ</button>
                        </div>
                    </form>
            </div>
        </div>
    </div>


    <div class="relative overflow-x-auto shadow-md sm:rounded-lg">
    <table class="w-full text-sm text-left text-gray-500 dark:text-gray-400">
        <tbody>
            <tr class="text-gray-700 uppercase dark:text-gray-400">
                <th scope="row" class="px-6 py-4 font-xl text-gray-900 uppercase whitespace-nowrap bg-gray-50 dark:text-white dark:bg-gray-800">
                    ห้อง :
                </th>
            </tr>
            <tr class="text-gray-700 uppercase dark:text-gray-400">
                <th scope="row" class="px-6 py-4 font-xl text-gray-900 uppercase whitespace-nowrap bg-gray-50 dark:text-white dark:bg-gray-800">
                    ชื่อ :
                </th>
            </tr>
            <tr class="border-b border-gray-200 dark:border-gray-700">
                <th scope="row" class="px-6 py-4 font-xl text-gray-900 whitespace-nowrap bg-gray-50 dark:text-white dark:bg-gray-800">
                    หมายเลขพัสดุ :
                </th>
            </tr>
        </tbody>

        <tbody>
            <tr class="text-gray-700 uppercase dark:text-gray-400">
                <th scope="row" class="px-6 py-4 font-xl text-gray-900 uppercase whitespace-nowrap bg-gray-50 dark:text-white dark:bg-gray-800">
                    ห้อง : ty
                </th>
            </tr>
            <tr class="text-gray-700 uppercase dark:text-gray-400">
                <th scope="row" class="px-6 py-4 font-xl text-gray-900 uppercase whitespace-nowrap bg-gray-50 dark:text-white dark:bg-gray-800">
                    ชื่อ : df 
                </th>
            </tr>
            <tr class="text-gray-700 uppercase dark:text-gray-400">
                <th scope="row" class="px-6 py-4 font-xl text-gray-900 uppercase whitespace-nowrap bg-gray-50 dark:text-white dark:bg-gray-800">
                    หมายเลขพัสดุ : df
                </th>
            </tr>
            <tr class="border-b border-gray-200 dark:border-gray-700">
                <th scope="row" class="px-6 py-4 font-xl text-gray-900 whitespace-nowrap bg-gray-50 dark:text-white dark:bg-gray-800">
                    ขนส่ง : Kerry Express
                </th>
            </tr>
        </tbody>
    </table>
</div>


    </template>
      
    