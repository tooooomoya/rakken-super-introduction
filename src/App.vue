<script setup>
// ここにJavaScriptを書く（今は空っぽでOK）
</script>

<template>
  <div class="container">
    <header>
      <h1>落語研究会のおもしろ大喜利大会</h1>
      <h3>お題</h3>
      <p>中道改革連合が改名を発表。新しい政党名は？</p>
    </header>

    <main class="grid-container">
      
      <div class="card member-1">
        <h2>メンバー1</h2>
        <p>（ここに回答）</p>
      </div>


      <div class="card member-2">
        <h2>メンバー2</h2>
        <p>（ここに回答）</p>
      </div>


      <div class="card member-3">
        <h2>メンバー3</h2>
        <p>（ここに回答）</p>
      </div>


      <div class="card member-4">
        <h2>メンバー4</h2>
        <p>（ここに回答）</p>
      </div>

    </main>
  </div>
</template>

<style>
  /* 全体のレイアウト */
  body {
    margin: 0;
    background-color: #f5f5f7;
    font-family: "Helvetica Neue", Arial, sans-serif;
    color: #333;
  }

  .container {
    max-width: 1000px;
    margin: 0 auto;
    padding: 2rem;
    text-align: center;
  }

  header h1 {
    color: #2c3e50;
    margin-bottom: 0.5rem;
  }

  /* 4分割のグリッドレイアウト */
  .grid-container {
    display: grid;
    grid-template-columns: 1fr 1fr; /* 横に2つ並べる */
    gap: 20px; /* カード同士の間隔 */
    margin-top: 2rem;
  }

  /* 画面が狭いスマホの時は1列にする（レスポンシブ） */
  @media (max-width: 600px) {
    .grid-container {
      grid-template-columns: 1fr;
    }
  }

  /* 各カードの共通デザイン */
  .card {
    background: white;
    padding: 2rem;
    border-radius: 12px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    transition: transform 0.2s;
  }

  .card:hover {
    transform: translateY(-5px); /* ホバーでちょっと浮く */
  }

  .card h2 {
    color: #42b883;
    font-size: 1.5rem;
    margin-bottom: 1rem;
  }

  /* 各メンバーごとのアクセントカラー（オプション） */
  .member-1 { border-top: 5px solid #e74c3c; } /* 赤 */
  .member-2 { border-top: 5px solid #3498db; } /* 青 */
  .member-3 { border-top: 5px solid #f1c40f; } /* 黄 */
  .member-4 { border-top: 5px solid #9b59b6; } /* 紫 */
</style>