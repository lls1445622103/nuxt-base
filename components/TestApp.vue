<!--
 * @Author: lls 1445622103@qq.com
 * @Date: 2024-07-12 15:09:08
 * @LastEditors: lls 1445622103@qq.com
 * @LastEditTime: 2024-07-12 16:51:53
 * @FilePath: /nuxt-base/components/test.vue
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
<template>
  <div @click="handle">{{ teet }}</div>
</template>

<script setup>
const teet = defineModel();
const app = ref(222);
function handle() {
  teet.value = "asdni";
}
</script>

<style lang="scss" scoped></style>
