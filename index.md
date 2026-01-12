---
layout: page
title: 📚 程式課程學習中心
---

# 歡迎來到我的線上講義

這是一個專為 **MATLAB** 與 **AI** 學習者設計的免費資源平台。請點選下方區塊開始學習。

<style>
    /* 核心變數定義 */
    :root {
        --apple-bg: #F5F5F7;
        --apple-blue: #007AFF;
        --apple-card-bg: rgba(255, 255, 255, 0.8);
        --apple-text: #1d1d1f;
        --apple-subtext: #86868b;
    }

    body {
        background-color: var(--apple-bg);
        color: var(--apple-text);
        font-family: -apple-system, BlinkMacSystemFont, "SF Pro Display", "Helvetica Neue", Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
    }

    /* 標題區域優化 */
    .hero-section {
        text-align: center;
        padding: 60px 20px;
    }

    .hero-section h1 {
        font-size: 3rem;
        font-weight: 700;
        letter-spacing: -0.02em;
        margin-bottom: 10px;
    }

    .hero-section p {
        font-size: 1.25rem;
        color: var(--apple-subtext);
        max-width: 600px;
        margin: 0 auto;
    }

    /* 卡片容器：自動適應排版 */
    .card-container {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
        gap: 24px;
        max-width: 1100px;
        margin: 40px auto;
        padding: 0 20px;
    }

    /* Apple 風格卡片 */
    .card {
        position: relative;
        background: var(--apple-card-bg);
        backdrop-filter: blur(20px) saturate(180%);
        -webkit-backdrop-filter: blur(20px) saturate(180%);
        border-radius: 22px;
        padding: 30px;
        text-align: center;
        text-decoration: none !important;
        color: var(--apple-text) !important;
        border: 1px solid rgba(255, 255, 255, 0.3);
        box-shadow: 0 4px 24px rgba(0, 0, 0, 0.04);
        transition: all 0.4s cubic-bezier(0.25, 1, 0.5, 1);
        overflow: hidden;
    }

    /* 懸停動效：微微放大並增加陰影 */
    .card:hover {
        transform: translateY(-8px) scale(1.01);
        box-shadow: 0 12px 40px rgba(0, 0, 0, 0.08);
        background: rgba(255, 255, 255, 0.9);
    }

    .card h2 {
        font-size: 24px;
        font-weight: 600;
        margin-bottom: 12px;
        color: var(--apple-text);
    }

    .card p {
        font-size: 15px;
        line-height: 1.5;
        color: var(--apple-subtext);
        margin-bottom: 24px;
    }
<style>

<div class="card-container">
    <a href="./matlab/ch01" class="card">
        <h2>📊 MATLAB</h2>
        <p>矩陣運算、數據繪圖與科學計算基礎。</p>
        <span class="btn-start">開始學習</span>
    </a>

<a href="./ai/ch01" class="card">
        <h2>🤖 AI 課程</h2>
        <p>機器學習導論與神經網路實作教學。</p>
        <span class="btn-start">開始學習</span>
    </a>

<a href="./newcorse/newproject" class="card">
        <h2>📊 報告內容</h2>
        <p>期末報告</p>
        <span class="btn-start">檢閱</span>
    </a>
</div>

---

### 📢 最新更新
- **2025-12-28**: 新增 AI 課程第二章「神經網路」。
- **2025-12-28**: 修正 MATLAB 側邊欄導覽連結。
