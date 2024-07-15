<template>
    <div>About</div>
    <div>
        <button @click="enableCustomLayout">Update layout</button>
    </div>
</template>

<script setup>
// 只有這頁面的 layout 會是客製化的
// definePageMeta({
//   layout: 'another'
// })

function enableCustomLayout () {
  setPageLayout('another')
}
</script>
