<template>
  <div class="fixed-center text-center">
    <p>
      <img
        src="~assets/sad.svg"
        style="width:30vw;max-width:150px;"
      >
    </p>
    <strong class="q-py-sm">Oops!</strong>
    <p class="text-faded q-mt-sm">页面未找到 <strong>(404)</strong></p>
    <q-btn
      color="secondary"
      style="width:200px;"
      @click="$router.push('/')"
    >返回主页</q-btn>
  </div>
</template>

<script>
export default {
  name: 'Error404'
}
</script>
