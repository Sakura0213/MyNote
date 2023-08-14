* 官方文档

https://pinia.vuejs.org/zh/getting-started.html



* 安装

```bash
yarn add pinia
# 或者使用 npm
npm install pinia
```



* 注册 pinia 插件

```javascript
//项目入口文件 main.js

import { createApp } from "vue";
import App from "./App.vue"; 
import { createPinia } from "pinia";//引入状态管理工具 pinia

const pinia = createPinia();//创建一个pinia实例

const app = createApp(App); 

app.use(pinia);//注册插件

app.mount("#app");


```



* 配置 pinia 实例

```javascript
//目录 src/stores/counter.js
//语法 vue3 组合式 api

import { ref, computed } from "vue";
import { defineStore } from "pinia";

export const useCounterStore = defineStore('counter', () => {
  const count = ref(0);
  const doubleCount = computed(() => count.value * 2);
  function increment() {
    count.value++;
  }

  return { count, doubleCount, increment };
});
```



* 使用 pinia 实例

```vue
<template>
  <el-button class="button" @click="countNum">{{ counter.count }}</el-button>
  <el-button class="button" @click="counter.increment()">
      {{counter.count}}
  </el-button>
</template>

<script setup>
import { ref } from "vue";
import { useCounterStore } from "../stores/counter";

const counter = useCounterStore();
function countNum() {
  ++counter.count; //直接使用，不用.value
}
</script>
```



