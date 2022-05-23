<template>
  <div class="relative overflow-x-auto shadow-md sm:rounded-lg">
    <table class="w-full text-sm text-left text-gray-500 dark:text-gray-400">
      <thead class="text-xs text-gray-700 uppercase bg-gray-50 dark:bg-gray-700 dark:text-gray-400">
      <tr>
        <th scope="col" class="px-6 py-3">
          Product name
        </th>
        <th scope="col" class="px-6 py-3">
          Color
        </th>
        <th scope="col" class="px-6 py-3">
          Category
        </th>
        <th scope="col" class="px-6 py-3">
          Price
        </th>
        <th scope="col" class="px-6 py-3">
          <span class="sr-only">Edit</span>
        </th>
      </tr>
      </thead>
      <tbody>
      <tr class="border-b dark:bg-gray-800 dark:border-gray-700 odd:bg-white even:bg-gray-50 odd:dark:bg-gray-800 even:dark:bg-gray-700">
        <th scope="row" class="px-6 py-4 font-medium text-gray-900 dark:text-white whitespace-nowrap">
          Apple MacBook Pro 17"
        </th>
        <td class="px-6 py-4">
          Sliver
        </td>
        <td class="px-6 py-4">
          Laptop
        </td>
        <td class="px-6 py-4">
          $2999
        </td>
        <td class="px-6 py-4 text-right">
          <a href="#" class="font-medium text-blue-600 dark:text-blue-500 hover:underline">Edit</a>
        </td>
      </tr>
      <tr class="border-b dark:bg-gray-800 dark:border-gray-700 odd:bg-white even:bg-gray-50 odd:dark:bg-gray-800 even:dark:bg-gray-700">
        <th scope="row" class="px-6 py-4 font-medium text-gray-900 dark:text-white whitespace-nowrap">
          Microsoft Surface Pro
        </th>
        <td class="px-6 py-4">
          White
        </td>
        <td class="px-6 py-4">
          Laptop PC
        </td>
        <td class="px-6 py-4">
          $1999
        </td>
        <td class="px-6 py-4 text-right">
          <a href="#" class="font-medium text-blue-600 dark:text-blue-500 hover:underline">Edit</a>
        </td>
      </tr>
      <tr class="border-b dark:bg-gray-800 dark:border-gray-700 odd:bg-white even:bg-gray-50 odd:dark:bg-gray-800 even:dark:bg-gray-700">
        <th scope="row" class="px-6 py-4 font-medium text-gray-900 dark:text-white whitespace-nowrap">
          Magic Mouse 2
        </th>
        <td class="px-6 py-4">
          Black
        </td>
        <td class="px-6 py-4">
          Accessories
        </td>
        <td class="px-6 py-4">
          $99
        </td>
        <td class="px-6 py-4 text-right">
          <a href="#" class="font-medium text-blue-600 dark:text-blue-500 hover:underline">Edit</a>
        </td>
      </tr>
      <tr class="border-b dark:bg-gray-800 dark:border-gray-700 odd:bg-white even:bg-gray-50 odd:dark:bg-gray-800 even:dark:bg-gray-700">
        <th scope="row" class="px-6 py-4 font-medium text-gray-900 dark:text-white whitespace-nowrap">
          Google Pixel Phone
        </th>
        <td class="px-6 py-4">
          Gray
        </td>
        <td class="px-6 py-4">
          Phone
        </td>
        <td class="px-6 py-4">
          $799
        </td>
        <td class="px-6 py-4 text-right">
          <a href="#" class="font-medium text-blue-600 dark:text-blue-500 hover:underline">Edit</a>
        </td>
      </tr>
      <tr class="odd:bg-white even:bg-gray-50 odd:dark:bg-gray-800 even:dark:bg-gray-700">
        <th scope="row" class="px-6 py-4 font-medium text-gray-900 dark:text-white whitespace-nowrap">
          Apple Watch 5
        </th>
        <td class="px-6 py-4">
          Red
        </td>
        <td class="px-6 py-4">
          Wearables
        </td>
        <td class="px-6 py-4">
          $999
        </td>
        <td class="px-6 py-4 text-right">
          <a href="#" class="font-medium text-blue-600 dark:text-blue-500 hover:underline">Edit</a>
        </td>
      </tr>
      </tbody>
    </table>

    <div class="2xl:mx-auto lg:py-16 lg:px-20 md:py-12 md:px-6 py-9 px-4">
      <p class="font-normal text-sm leading-3 text-indigo-700 hover:text-indigo-800 cursor-pointer pb-2 text-left">About</p>
      <div class="flex lg:flex-row flex-col lg:gap-8 sm:gap-10 gap-12">
        <div class="w-full lg:w-6/12">
          <h2 class="w-full font-bold lg:text-4xl text-3xl lg:leading-10 leading-9 text-left">We are here to make great design accessible and delightfull for everyone</h2>
          <p class="font-normal text-base leading-6 text-gray-600 mt-6 text-left">It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum.In the first place we have granted to God, and by this our present charter confirmed for us and our heirs forever that the English Church shall be free, and shall have her rights entire,</p>
        </div>
        <div class="w-full lg:w-6/12">
          <img class="lg:block hidden w-full" src="https://i.ibb.co/RjNH7QB/Rectangle-122-1.png" alt="people discussing on board" />
          <img class="lg:hidden sm:block hidden w-full" src="https://i.ibb.co/16fPqrg/Rectangle-122-2.png" alt="people discussing on board" />
          <img class="sm:hidden block w-full" src="https://i.ibb.co/Jxhpxh6/Rectangle-122.png" alt="people discussing on board" />
        </div>
      </div>

      <div class="relative mt-24">
        <div class="grid sm:grid-cols-3 grid-cols-2 sm:gap-8 gap-4">
          <div class="z-20 w-12 h-12 bg-gray-800 rounded-full flex justify-center items-center">
            <img src="https://tuk-cdn.s3.amazonaws.com/can-uploader/about-us-3-svg1.svg" alt="flag" />
          </div>

          <img class="z-20" src="https://tuk-cdn.s3.amazonaws.com/can-uploader/about-us-3-svg2.svg" alt="note" />

          <img class="z-20 sm:block hidden" src="https://tuk-cdn.s3.amazonaws.com/can-uploader/about-us-3-svg3.svg" alt="users" />
        </div>
        <hr class="z-10 absolute top-2/4 w-full bg-gray-200" />
      </div>
      <div class="grid sm:grid-cols-3 grid-cols-2 sm:gap-8 gap-4">
        <div>
          <p class="font-semibold lg:text-2xl text-xl lg:leading-6 leading-5 text-gray-800 mt-6 text-left">Founded</p>
          <p class="font-normal text-base leading-6 text-gray-600 mt-6 text-left">It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout.</p>
        </div>
        <div>
          <p class="font-semibold lg:text-2xl text-xl lg:leading-6 leading-5 text-gray-800 mt-6 text-left">50M montly enrichments</p>
          <p class="font-normal text-base leading-6 text-gray-600 mt-6 text-left">It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout.</p>
        </div>
        <div class="sm:block hidden">
          <p class="font-semibold lg:text-2xl text-xl lg:leading-6 leading-5 text-gray-800 mt-6 text-left">400k User</p>
          <p class="font-normal text-base leading-6 text-gray-600 mt-6 text-left">It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout.</p>
        </div>
      </div>
      <div class="sm:hidden block relative mt-8">
        <div class="grid sm:grid-cols-3 grid-cols-2 sm:gap-8 gap-4">
          <img src="https://tuk-cdn.s3.amazonaws.com/can-uploader/about-us-3-svg3.svg" alt="user" />
        </div>
        <hr class="z-10 absolute top-2/4 w-full bg-gray-200" />
      </div>
      <div class="sm:hidden grid sm:grid-cols-3 grid-cols-2 sm:gap-8 gap-4">
        <div>
          <p class="font-semibold lg:text-2xl text-xl lg:leading-6 leading-5 text-gray-800 mt-6 text-left">400k User</p>
          <p class="font-normal text-base leading-6 text-gray-600 mt-6">It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout.</p>
        </div>
      </div>

      <div class="flex lg:flex-row flex-col md:gap-14 gap-16 justify-between lg:mt-20 mt-16">
        <div class="w-full lg:w-6/12">
          <h2 class="font-bold lg:text-4xl text-3xl lg:leading-9 leading-7 text-gray-800 text-left">Our Mission</h2>
          <p class="font-normal text-base leading-6 text-gray-600 mt-6 w-full lg:w-10/12 xl:w-9/12 text-left">It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum.In the first place we have granted to God, and by this our present charter confirmed for us and our heirs forever that the English Church shall be free, and shall have her rights entire, and her liberties inviolate; and we will that it be thus observed; which is apparent from</p>
          <p class="font-normal text-base leading-6 text-gray-600 w-full lg:w-10/12 xl:w-9/12 mt-10 text-left">It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum.In the first place we have granted to God, and by this our present charter confirmed for us and our heirs forever that the English Church shall be free, and shall have her rights entire, and her liberties inviolate; and we will that it be thus observed; which is apparent from</p>
        </div>
        <div class="w-full lg:w-6/12">
          <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-1 lg:gap-12 gap-10">
            <!-- Team Card -->
            <div class="flex p-4 shadow-md">
              <div class="mr-6">
                <img class="mr-6"  src="https://tuk-cdn.s3.amazonaws.com/can-uploader/about-us-3-svg4.svg" alt="team card" />
              </div>
              <div class="">
                <p class="font-semibold lg:text-2xl text-xl lg:leading-6 leading-5 text-gray-800 text-left">Team</p>
                <p class="mt-2 font-normal text-base leading-6 text-gray-600 text-left">It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout.</p>
              </div>
            </div>

            <!-- Board Card -->
            <div class="flex p-4 shadow-md">
              <div class="mr-6">
                <img src="https://tuk-cdn.s3.amazonaws.com/can-uploader/about-us-3-svg5.svg" alt="board card" />
              </div>
              <div class="">
                <p class="font-semibold lg:text-2xl text-xl lg:leading-6 leading-5 text-gray-800 text-left">Board</p>
                <p class="mt-2 font-normal text-base leading-6 text-gray-600 text-left">It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout.</p>
              </div>
            </div>

            <!-- Press Card -->
            <div class="flex p-4 shadow-md">
              <div class="mr-6">
                <img src="https://tuk-cdn.s3.amazonaws.com/can-uploader/about-us-3-svg6.svg" alt="press card" />
              </div>
              <div class="">
                <p class="font-semibold lg:text-2xl text-xl lg:leading-6 leading-5 text-gray-800 text-left">Press</p>
                <p class="mt-2 font-normal text-base leading-6 text-gray-600 text-left">It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>

</script>