<template>
  <div>
    <!--This is the TopBar-->
    <div class="flex mx-auto bg-gray-200 px-5">
        <img src="../../assets/compassIcon.png" class="logo my-3 px-10" alt="..." />
    </div>
    <div class="grid grid-cols-12 max-w-screen-lg bg-blue-100 mx-auto h-48 pt-5">
      <div class="mx-10">
        <img src="../../assets/svgs/man.png" alt="..." class="rounded-full profile" />
      </div>
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

<style scoped>
.logo{
  max-height: 30px;
}
.profile{
  max-height: 150px;
}


</style>
