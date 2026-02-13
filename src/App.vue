<script setup>
// ここにJavaScriptを書く（今は空っぽでOK）
</script>

<template>
  <div class="container">
    <div class="card">
      <h1>こんにちは！</h1>
      <p>名前：<span>ここに名前を入れてね</span></p>
      <p>好きなこと：プログラミング勉強中</p>
    </div>
  </div>
</template>

<style>
  /* ページ全体の背景 */
  body {
    margin: 0;
    background-color: #f0f2f5;
    font-family: sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
  }

  /* カードのデザイン */
  .card {
    background: white;
    padding: 2rem;
    border-radius: 12px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    text-align: center;
    width: 300px;
  }

  h1 {
    color: #42b883; /* Vueの色 */
  }

  span {
    font-weight: bold;
    color: #35495e;
  }
</style>
