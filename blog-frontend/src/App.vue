<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>


<div class="grid grid-cols-1 gap-2 mt-2 p-4">

  <h1 class="text-2xl font-bold">Posts</h1>
  <table class="min-w-full divide-y divide-gray-300">
    <thead>
      <tr>
        <th scope="col" class="px-8 py-4 text-start text-sm uppercase">Id</th>
        <th scope="col" class="px-8 py-4 text-start text-sm uppercase">User</th>
        <th scope="col" class="px-8 py-4 text-start text-sm uppercase">Title</th>
        <th scope="col" class="px-8 py-4 text-start text-sm uppercase">Date</th>
      </tr>
    </thead>
    <tbody>
      <tr class="hover-me">
        <td class="px-8 py-4 text-start text-sm">1</td>
        <td class="px-8 py-4 text-start text-sm">Frank</td>
        <td class="px-8 py-4 text-start text-sm">Post 1</td>
        <td class="px-8 py-4 text-start text-sm">2025-10-02</td>
      </tr>

       <tr class="hover-me">
        <td class="px-8 py-4 text-start text-sm">2</td>
        <td class="px-8 py-4 text-start text-sm">Ken</td>
        <td class="px-8 py-4 text-start text-sm">Post 2</td>
        <td class="px-8 py-4 text-start text-sm">2025-10-06</td>
      </tr>
    </tbody>
  </table>
  <!-- <button class="bg-blue-500 text-white hover:bg-blue-700 rounded py-2 px-4"> Create</button> -->
</div>


</template>

<style scoped>
.hover-me:hover {
  background-color: #f3f4f6; /* Tailwind's gray-100 */
}
</style>
