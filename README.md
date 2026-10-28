# Multicampus_K_Digital_AI_PM

<div align="center">
  <img src="https://github.com/user-attachments/assets/ce856817-6f64-4e85-a223-e39cc9196e72" width="320" alt="프로필 이미지" />
</div>

<p align="center">
  <strong>AI 프로덕트 매니저</strong> · <strong>DJlee</strong>
</p>

<style>
  :root {
    --bg: #f4f7fb;
    --panel: #ffffff;
    --line: #e7edf7;
    --text: #1b2432;
    --muted: #707d94;
    --primary: #2b5df5;
    --primary-soft: #eef3ff;
    --accent: #ff7a59;
    --shadow: 0 16px 32px rgba(20, 37, 68, 0.08);
  }

  .pm-wrap {
    max-width: 860px;
    margin: 0 auto;
    padding: 28px 18px 48px;
    font-family: "Segoe UI", "Apple SD Gothic Neo", sans-serif;
    color: var(--text);
    background: linear-gradient(180deg, #eef3ff 0%, #f5f7fb 100%);
    border-radius: 28px;
  }

  .pm-hero {
    background: linear-gradient(135deg, #14213d 0%, #1f2c5a 48%, #2b5df5 100%);
    color: #fff;
    border-radius: 28px;
    padding: 28px 24px 20px;
    box-shadow: var(--shadow);
    position: relative;
    overflow: hidden;
  }

  .pm-hero::after {
    content: "";
    position: absolute;
    right: -30px;
    bottom: -34px;
    width: 180px;
    height: 180px;
    background: rgba(255,255,255,0.08);
    border-radius: 50%;
  }

  .pm-brand {
    display: inline-block;
    padding: 8px 12px;
    border-radius: 999px;
    background: rgba(255,255,255,0.12);
    font-size: 12px;
    letter-spacing: 0.12em;
    font-weight: 700;
    margin-bottom: 18px;
  }

  .pm-hero h1 {
    font-size: clamp(28px, 4vw, 42px);
    margin: 0;
    line-height: 1.15;
    letter-spacing: -0.04em;
  }

  .pm-subtitle {
    margin-top: 10px;
    color: rgba(255,255,255,0.8);
    font-size: 15px;
  }

  .pm-badge {
    display: inline-flex;
    align-items: center;
    gap: 8px;
    margin-top: 18px;
    padding: 8px 12px;
    border-radius: 999px;
    background: rgba(255,255,255,0.14);
    font-size: 13px;
    font-weight: 600;
  }

  .pm-badge .dot {
    width: 8px;
    height: 8px;
    border-radius: 50%;
    background: #5ee4a4;
    box-shadow: 0 0 10px rgba(94, 228, 164, 0.8);
  }

  .pm-list {
    margin-top: 24px;
    display: grid;
    gap: 16px;
  }

  .pm-card {
    background: var(--panel);
    border: 1px solid var(--line);
    border-radius: 22px;
    box-shadow: var(--shadow);
    padding: 16px;
    display: grid;
    grid-template-columns: 120px 1fr auto;
    align-items: center;
    gap: 16px;
  }

  .pm-thumb {
    width: 120px;
    height: 96px;
    border-radius: 18px;
    background: linear-gradient(135deg, #dfe9ff 0%, #eef3ff 50%, #d4e0ff 100%);
    position: relative;
    overflow: hidden;
    border: 1px solid #dfe7fb;
  }

  .pm-thumb::before,
  .pm-thumb::after {
    content: "";
    position: absolute;
    background: rgba(43, 93, 245, 0.12);
    border-radius: 12px;
  }

  .pm-research::before {
    width: 70px;
    height: 56px;
    left: 25px;
    top: 20px;
    border-radius: 14px;
    background: rgba(43, 93, 245, 0.18);
  }

  .pm-research::after {
    width: 54px;
    height: 10px;
    left: 33px;
    top: 50px;
    background: rgba(43, 93, 245, 0.22);
    box-shadow: 0 -18px 0 rgba(43, 93, 245, 0.1);
  }

  .pm-data::before {
    width: 62px;
    height: 52px;
    left: 29px;
    top: 22px;
    background: rgba(43, 93, 245, 0.12);
    clip-path: polygon(0 100%, 20% 64%, 40% 74%, 58% 35%, 80% 58%, 100% 0, 100% 100%);
  }

  .pm-data::after {
    width: 14px;
    height: 14px;
    left: 52px;
    top: 34px;
    border-radius: 50%;
    background: rgba(43, 93, 245, 0.32);
    box-shadow: -18px 8px 0 rgba(43, 93, 245, 0.18), 16px 16px 0 rgba(43, 93, 245, 0.14);
  }

  .pm-ai::before {
    width: 62px;
    height: 62px;
    left: 29px;
    top: 17px;
    border-radius: 50%;
    background: rgba(43, 93, 245, 0.16);
  }

  .pm-ai::after {
    width: 30px;
    height: 30px;
    left: 45px;
    top: 33px;
    border-radius: 50%;
    background: rgba(43, 93, 245, 0.28);
    box-shadow: 0 0 0 8px rgba(43, 93, 245, 0.08);
  }

  .pm-experiment::before {
    width: 64px;
    height: 44px;
    left: 28px;
    top: 26px;
    border-radius: 10px;
  }

  .pm-experiment::after {
    width: 62px;
    height: 10px;
    left: 29px;
    bottom: 20px;
    background: rgba(43, 93, 245, 0.2);
    box-shadow: 0 -18px 0 rgba(43, 93, 245, 0.08);
  }

  .pm-ux::before {
    width: 52px;
    height: 64px;
    left: 34px;
    top: 16px;
    border-radius: 12px;
  }

  .pm-ux::after {
    width: 30px;
    height: 12px;
    left: 45px;
    top: 25px;
    background: rgba(43, 93, 245, 0.22);
    box-shadow: 0 18px 0 rgba(43, 93, 245, 0.12), 0 36px 0 rgba(43, 93, 245, 0.08);
  }

  .pm-info {
    min-width: 0;
  }

  .pm-tag {
    display: inline-block;
    padding: 5px 8px;
    border-radius: 999px;
    background: var(--primary-soft);
    color: var(--primary);
    font-size: 11px;
    font-weight: 700;
    letter-spacing: 0.03em;
  }

  .pm-info h2 {
    font-size: 20px;
    margin: 10px 0 6px;
    letter-spacing: -0.03em;
  }

  .pm-meta {
    color: var(--muted);
    font-size: 13px;
    margin: 0;
  }

  .pm-price-box {
    text-align: right;
    min-width: 126px;
  }

  .pm-old-price {
    display: block;
    color: var(--muted);
    text-decoration: line-through;
    font-size: 12px;
    margin-bottom: 6px;
  }

  .pm-price {
    display: block;
    color: var(--primary);
    font-size: 28px;
    font-weight: 800;
    letter-spacing: -0.04em;
  }

  .pm-price small {
    font-size: 14px;
    font-weight: 700;
  }

  .pm-cta {
    display: block;
    margin-top: 26px;
    background: linear-gradient(135deg, #ff8b4d 0%, #ff6b5f 100%);
    color: #fff;
    text-align: center;
    border: none;
    border-radius: 16px;
    padding: 16px 18px;
    font-size: 16px;
    font-weight: 700;
    box-shadow: 0 12px 24px rgba(255, 121, 92, 0.28);
    cursor: pointer;
  }

  .pm-footer {
    margin-top: 26px;
    padding-top: 18px;
    border-top: 1px solid var(--line);
    text-align: center;
    color: var(--muted);
    font-size: 13px;
  }

  @media (max-width: 600px) {
    .pm-card {
      grid-template-columns: 96px 1fr;
    }

    .pm-thumb {
      width: 96px;
      height: 88px;
    }

    .pm-price-box {
      grid-column: 2;
      text-align: left;
      min-width: 0;
    }
  }
</style>

<div class="pm-wrap">
  <header class="pm-hero">
    <div class="pm-brand">AI PM PORTFOLIO</div>
    <h1>사용자 문제를 정의하고,<br/>AI로 더 나은 경험을 만듭니다.</h1>
    <div class="pm-subtitle">서비스 기획 · 데이터 기반 의사결정 · AI 서비스 설계</div>
    <div class="pm-badge"><span class="dot"></span> 지금 함께 성장할 프로젝트를 찾고 있습니다</div>
  </header>

  <main class="pm-list">
    <article class="pm-card">
      <div class="pm-thumb pm-research"></div>
      <div class="pm-info">
        <span class="pm-tag">핵심역량</span>
        <h2>사용자 리서치</h2>
        <p class="pm-meta">문제 정의 · 사용자 여정 · 니즈 분석</p>
      </div>
      <div class="pm-price-box">
        <span class="pm-old-price">기획</span>
        <span class="pm-price">문제<small>해결</small></span>
      </div>
    </article>

    <article class="pm-card">
      <div class="pm-thumb pm-data"></div>
      <div class="pm-info">
        <span class="pm-tag">핵심역량</span>
        <h2>데이터 기반 의사결정</h2>
        <p class="pm-meta">지표 설계 · 실험 분석 · 성장 전략</p>
      </div>
      <div class="pm-price-box">
        <span class="pm-old-price">분석</span>
        <span class="pm-price">성장<small>검증</small></span>
      </div>
    </article>

    <article class="pm-card">
      <div class="pm-thumb pm-ai"></div>
      <div class="pm-info">
        <span class="pm-tag">핵심역량</span>
        <h2>AI 서비스 설계</h2>
        <p class="pm-meta">추천 시스템 · 자동화 · 사용자 경험 개선</p>
      </div>
      <div class="pm-price-box">
        <span class="pm-old-price">기술</span>
        <span class="pm-price">AI<small>활용</small></span>
      </div>
    </article>

    <article class="pm-card">
      <div class="pm-thumb pm-experiment"></div>
      <div class="pm-info">
        <span class="pm-tag">핵심역량</span>
        <h2>실험과 반복</h2>
        <p class="pm-meta">가설 검증 · 피드백 반영 · 제품 개선</p>
      </div>
      <div class="pm-price-box">
        <span class="pm-old-price">반복</span>
        <span class="pm-price">실험<small>가속</small></span>
      </div>
    </article>

    <article class="pm-card">
      <div class="pm-thumb pm-ux"></div>
      <div class="pm-info">
        <span class="pm-tag">핵심역량</span>
        <h2>UX / 서비스 설계</h2>
        <p class="pm-meta">사용자 중심 사고 · 기능 우선순위 · 경험 설계</p>
      </div>
      <div class="pm-price-box">
        <span class="pm-old-price">디자인</span>
        <span class="pm-price">경험<small>설계</small></span>
      </div>
    </article>
  </main>

  <button class="pm-cta">프로젝트를 함께 만들어가고 싶습니다</button>

  <footer class="pm-footer">
    기획, 분석, 서비스 아이디어, 사용자 경험 개선에 관심이 있다면 함께 이야기해보세요.
  </footer>
</div>

---

## 소개

- 이름: DJlee
- 과정: AI 프로덕트 매니저 (2026.10 ~ 2027.04)
- 목표: 사용자 문제를 이해하고, 데이터를 기반으로 서비스를 설계하며, AI를 활용해 실제 가치를 만드는 사람
- 관심 분야: 서비스 기획, 유저 여정, 데이터 기반 의사결정, AI 서비스 설계, 제품 실험

<div id="about">

### 나는 이런 사람입니다

사용자에게 더 좋은 경험을 주는 서비스를 만드는 것에 관심이 많습니다. 제품을 기획할 때 단순히 기능을 추가하는 수준을 넘어서, 어떤 문제를 해결하고 있는지, 사용자에게 어떤 가치를 제공하는지 깊이 생각합니다. 문제를 정의하고 가설을 세우고, 데이터를 바탕으로 검증하며, 지속적으로 개선해 나가는 과정을 중요하게 생각합니다.

### 프로젝트 방향

- 사용자 문제를 명확하게 정의하고 가설을 세우기
- 데이터를 기반으로 핵심 지표를 설계하고 검증하기
- AI 기능을 제품에 자연스럽게 녹여 사용자 경험을 개선하기
- 실험과 피드백을 반복하며 제품을 성장시키기

### 핵심 가치

- 사용자 중심 사고
- 데이터 기반 의사결정
- 협업과 커뮤니케이션
- 빠른 실험과 반복
- AI를 활용한 문제 해결

</div>

---

### 한 줄 소개

“사람의 문제를 잘 정의하고, 데이터와 기술로 연결해 더 나은 경험을 만드는 AI 프로덕트 매니저입니다.”
