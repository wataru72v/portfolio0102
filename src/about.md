---
autonav:
  enable: true
  order: 8
---

# About

## Profile

<img src="wataru_icon.png" width=33%>

**名前： ワタル**

2021 年から活動を開始。  
世の中の役に立つサービスを作ることを目標に個人開発を行う。  
好きなことはプログラミングと毛布にくるまって眠ること。  
大好物はサツマイモ。

## Skills

<template>
  <img class="skill" v-for="image in images" :src="image.path" style="width: 19%; margin: 3%;"/>
</template>

<script>
export default {
  data() {
    return {
      images: [
        { path: "html.png" },
        { path: "css.png" },
        { path: "js.png" },
        { path: "nodejs.png" },
        { path: "vuejs.png" },
      ],
    };
  },
};
</script>
