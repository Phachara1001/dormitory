<template>
    
    <div
        class="flex-row items-center justify-start bg-purple-400 text-xl p-4 space-y-3 sm:flex sm:space-y-0 sm:space-x-4">
       ตั้งค่าห้องพัก
    </div>
<section class="bg-white dark:bg-gray-900">
<div class="py- px- mx-auto ">
    <h2 class="mb-4 text-xl font-bold text-gray-900 dark:text-white">จัดการห้องพัก(ค่าห้อง)</h2>
    <h2 class="mb-4  font-bold text-gray-900 dark:text-white">แก้ไขข้อมูล รายระเอียดห้องพัก</h2>
    <form action="#">
        <div class="grid gap-4 sm:grid-cols-2 sm:gap-6">
        
            <div class="w-full">
                <label for="brand" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">เลขห้อง</label>
                <input type="text" name="brand" id="brand" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500" placeholder="" required="">
            </div>
            
            <div>
                <label for="category" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">ประเภทห้อง vip</label>
                <select id="category" class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-primary-500 focus:border-primary-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-primary-500 dark:focus:border-primary-500">
                    <option selected="">ห้องทั่วไป</option>
                    <option value="TV">vip</option>
                    <option value="PC">VVip</option>
                    <option value="GA">ปาร์ตี้</option>
                    <option value="PH">เตียงเดียว</option>
                </select>
            </div>
            
            
        </div>
        <button type="submit" class="inline-flex items-center px-5 py-2.5 mt-4 sm:mt-6 text-sm font-medium text-center text-white bg-primary-700 rounded-lg focus:ring-4 focus:ring-primary-200 dark:focus:ring-primary-900 hover:bg-primary-800">
            เพิ่ม
        </button>
    </form>
</div>



</section>

</template>