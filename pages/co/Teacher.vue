<template>
  <div>
    <div class="flex mx-auto bg-red-300 max-w-screen-md">
      asdfas
    </div>
    <div class="grid grid-cols-12 gap-5">
      <div class="col-span-1 bg-gray-400">
        <div class="flex flex-col justify-center">
          <div>1</div>
          <div>2</div>
          <div>3</div>
        </div>
      </div>
      <div class="col-span-4 bg-gray-500 rounded">ProfileDiv</div>
      <div class="col-span-1 bg-gray-600 rounded">Content</div>
      <div class="col-span-1 bg-gray-700 rounded">Right Span</div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Teacher",
  data: () => ({}),
  layout: "PrimaryProfile"
};
</script>

<style scoped></style>
