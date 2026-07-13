<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>박형주 — Cloud Engineer Portfolio</title>
<meta name="description" content="박형주 클라우드 엔지니어 포트폴리오. 인프라를 만들고, 배포하고, 기록합니다.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Archivo:wght@500;700;800&family=IBM+Plex+Sans+KR:wght@400;500;700&family=IBM+Plex+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
  :root {
    --black: #0e0d0b;
    --cream: #f7f4ea;
    --red: #e8451d;
    --violet: #6c47ff;
    --white: #ffffff;
    --line: #14130f;
    --dim: #8a8578;
  }
  * { margin: 0; padding: 0; box-sizing: border-box; }
  html { scroll-behavior: smooth; }
  body {
    background: var(--black);
    color: var(--cream);
    font-family: "IBM Plex Sans KR", "Apple SD Gothic Neo", sans-serif;
    line-height: 1.65;
  }
  .en { font-family: "Archivo", sans-serif; }
  .mono { font-family: "IBM Plex Mono", monospace; }
  a { color: inherit; }
  a:focus-visible, button:focus-visible {
    outline: 3px solid var(--red);
    outline-offset: 3px;
  }

  /* ---------- 벤토 그리드 ---------- */
  .board {
    display: grid;
    grid-template-columns: repeat(12, 1fr);
    gap: 6px;
    padding: 6px;
    max-width: 1200px;
    margin: 0 auto;
  }
  .tile {
    background: var(--cream);
    color: var(--black);
    padding: clamp(20px, 3vw, 36px);
    display: flex;
    flex-direction: column;
    justify-content: center;
    min-height: 180px;
    position: relative;
    overflow: hidden;
  }
  .tile--dark { background: var(--black); color: var(--cream); border: 1px solid #1e1c17; }
  .tile--red  { background: var(--red);   color: var(--cream); }
  .tile--grad {
    background: radial-gradient(120% 140% at 20% 10%, var(--violet) 0%, #2b1a66 38%, #b3300f 74%, var(--cream) 115%);
    color: var(--white);
    align-items: center;
    justify-content: center;
  }

  /* 타일 스팬 */
  .s-4  { grid-column: span 4; }
  .s-5  { grid-column: span 5; }
  .s-6  { grid-column: span 6; }
  .s-7  { grid-column: span 7; }
  .s-8  { grid-column: span 8; }
  .s-12 { grid-column: span 12; }
  .tall { grid-row: span 2; }

  /* ---------- 픽셀 모노그램 (시그니처) ---------- */
  .pixel {
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    gap: 4px;
    width: 90px;
  }
  .pixel i { aspect-ratio: 1; background: currentColor; }
  .pixel i.off { background: transparent; }
  .pixel--lg { width: 130px; }

  /* ---------- 히어로 ---------- */
  .hero h1 {
    font-family: "Archivo", "IBM Plex Sans KR", sans-serif;
    font-weight: 800;
    font-size: clamp(2.6rem, 7vw, 5rem);
    letter-spacing: -0.03em;
    line-height: 1.05;
  }
  .hero .sub { margin-top: 14px; font-size: 1.05rem; color: #3c3a33; font-weight: 500; }
  .eyebrow {
    font-family: "IBM Plex Mono", monospace;
    font-size: 0.75rem;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    margin-bottom: 14px;
    color: var(--red);
  }
  .tile--dark .eyebrow, .tile--red .eyebrow { color: var(--cream); opacity: 0.75; }

  .tagline {
    font-family: "Archivo", sans-serif;
    font-weight: 700;
    font-size: clamp(1.4rem, 3vw, 2rem);
    line-height: 1.25;
    letter-spacing: -0.01em;
  }

  /* ---------- 리스트/스킬 ---------- */
  h2.tile-title {
    font-family: "Archivo", "IBM Plex Sans KR", sans-serif;
    font-weight: 800;
    font-size: 1.35rem;
    letter-spacing: -0.01em;
    margin-bottom: 14px;
  }
  ul.flat { list-style: none; }
  ul.flat li {
    padding: 9px 0;
    border-bottom: 1px solid rgba(0,0,0,0.12);
    display: flex;
    justify-content: space-between;
    gap: 16px;
    font-size: 0.95rem;
  }
  .tile--dark ul.flat li { border-color: #26241d; }
  ul.flat li:last-child { border-bottom: none; }
  ul.flat .tag { font-family: "IBM Plex Mono", monospace; font-size: 0.75rem; color: var(--dim); white-space: nowrap; align-self: center; }

  /* ---------- 프로젝트 ---------- */
  .proj { border-bottom: 1px solid #26241d; padding: 18px 0; }
  .proj:last-child { border-bottom: none; }
  .proj h3 { font-size: 1.05rem; font-weight: 700; }
  .proj p { font-size: 0.9rem; color: #b7b2a4; margin-top: 6px; }
  .proj .stack { font-family: "IBM Plex Mono", monospace; font-size: 0.72rem; color: var(--red); margin-top: 8px; letter-spacing: 0.04em; }

  /* ---------- 배포 로그 ---------- */
  .log { font-family: "IBM Plex Mono", monospace; font-size: 0.85rem; line-height: 2; }
  .log .ok::before { content: "✔ "; }
  .log .cmd { opacity: 0.65; }

  /* ---------- 푸터 ---------- */
  .contact a {
    font-family: "Archivo", sans-serif;
    font-weight: 700;
    font-size: clamp(1.3rem, 3vw, 2rem);
    text-decoration: none;
    border-bottom: 3px solid var(--cream);
    width: fit-content;
    transition: color .2s, border-color .2s;
  }
  .contact a:hover { color: var(--black); border-color: var(--black); }

  /* 등장 애니메이션 */
  @media (prefers-reduced-motion: no-preference) {
    .tile { animation: rise .5s ease both; }
    .tile:nth-child(2) { animation-delay: .05s; }
    .tile:nth-child(3) { animation-delay: .1s; }
    .tile:nth-child(4) { animation-delay: .15s; }
    .tile:nth-child(5) { animation-delay: .2s; }
    .tile:nth-child(6) { animation-delay: .25s; }
    .tile:nth-child(7) { animation-delay: .3s; }
    .tile:nth-child(8) { animation-delay: .35s; }
    @keyframes rise { from { opacity: 0; transform: translateY(14px); } to { opacity: 1; transform: none; } }
  }

  /* ---------- 반응형 ---------- */
  @media (max-width: 860px) {
    .s-4, .s-5, .s-6, .s-7, .s-8 { grid-column: span 12; }
    .tall { grid-row: auto; }
    .tile { min-height: 140px; }
  }
</style>
</head>
<body>

<main class="board">

  <!-- 히어로: 이름 -->
  <section class="tile hero s-7" aria-label="소개">
    <p class="eyebrow">Cloud Engineering Portfolio</p>
    <h1>박형주<br><span style="color:var(--red)">HYUNGJU PARK</span></h1>
    <p class="sub">인프라를 만들고, 배포하고, 기록합니다.</p>
  </section>

  <!-- 픽셀 모노그램 (다크) -->
  <section class="tile tile--dark s-5" aria-hidden="true" style="align-items:center; justify-content:center;">
    <div class="pixel pixel--lg" role="img" aria-label="픽셀 스타일 HJ 모노그램">
      <i></i><i class="off"></i><i></i><i class="off"></i><i></i>
      <i></i><i class="off"></i><i></i><i class="off"></i><i></i>
      <i></i><i></i><i></i><i class="off"></i><i></i>
      <i></i><i class="off"></i><i></i><i class="off"></i><i></i>
      <i></i><i class="off"></i><i></i><i></i><i></i>
    </div>
  </section>

  <!-- 태그라인 (레드) -->
  <section class="tile tile--red s-4" aria-label="키워드">
    <p class="eyebrow">Keywords</p>
    <p class="tagline en">Build.<br>Deploy.<br>Document.</p>
  </section>

  <!-- 그라디언트 + 픽셀 마크 -->
  <section class="tile tile--grad s-4" aria-hidden="true">
    <div class="pixel">
      <i class="off"></i><i></i><i></i><i></i><i class="off"></i>
      <i class="off"></i><i></i><i class="off"></i><i></i><i class="off"></i>
      <i class="off"></i><i></i><i></i><i></i><i class="off"></i>
      <i class="off"></i><i class="off"></i><i></i><i class="off"></i><i class="off"></i>
      <i class="off"></i><i></i><i class="off"></i><i></i><i class="off"></i>
    </div>
  </section>

  <!-- 스킬 -->
  <section class="tile s-4" aria-label="기술 스택">
    <h2 class="tile-title">Skills</h2>
    <ul class="flat">
      <li>Linux · Bash 스크립팅 <span class="tag">Ubuntu/WSL</span></li>
      <li>AWS EC2 3-tier 아키텍처 <span class="tag">VPC·SG</span></li>
      <li>Nginx · 리버스 프록시 <span class="tag">Web</span></li>
      <li>Python Flask · MariaDB <span class="tag">Backend</span></li>
      <li>NCP 클라우드 <span class="tag">NCA 취득</span></li>
    </ul>
  </section>

  <!-- 자격증 -->
  <section class="tile tile--dark s-8 tall" aria-label="프로젝트">
    <h2 class="tile-title">Projects</h2>
    <article class="proj">
      <h3>협업 서버 플랫폼 (진행 중)</h3>
      <p>Redmine에서 영감을 받은 팀 협업 서버. 간트차트, 진척률 관리, 파일 저장소, 실시간 코딩 지원 기능을 직접 설계하고 구축합니다.</p>
      <p class="stack">FLASK · MARIADB · NGINX · SOCKET.IO · AWS EC2</p>
    </article>
    <article class="proj">
      <h3>3-Tier 보안 실습 랩</h3>
      <p>의도적으로 취약한 웹 애플리케이션을 포함한 보안 교육용 3계층 환경을 구성하고, 네트워크 토폴로지와 프록시 설정을 트러블슈팅했습니다.</p>
      <p class="stack">NGINX · TOMCAT 10 · MARIADB</p>
    </article>
    <article class="proj">
      <h3>AWS 3-Tier 로그인 시스템</h3>
      <p>EC2 위에 JSP와 MariaDB 기반 로그인 시스템을 배포하며 경로 오류, 인코딩, DB 연결 문제를 해결했습니다.</p>
      <p class="stack">AWS EC2 · JSP · MARIADB</p>
    </article>
  </section>

  <!-- 자격증 / 배포 로그 -->
  <section class="tile s-4" aria-label="자격증">
    <h2 class="tile-title">Certificates</h2>
    <ul class="flat">
      <li>NCA (Naver Cloud) <span class="tag">2026</span></li>
      <li>프로그래밍기능사 <span class="tag">2026</span></li>
      <li>AWS SAA-C03 <span class="tag">준비 중</span></li>
    </ul>
  </section>

  <section class="tile tile--dark s-4" aria-label="배포 기록">
    <p class="eyebrow">Deploy Log</p>
    <div class="log">
      <div class="cmd">$ git push origin main</div>
      <div class="ok" style="color:#7de8a0">2026-07-13 GitHub Pages 배포</div>
      <div class="cmd">이 페이지가 그 증거입니다.</div>
    </div>
  </section>

  <!-- 연락처 -->
  <section class="tile tile--red s-12 contact" aria-label="연락처">
    <p class="eyebrow">Contact</p>
    <a class="en" href="https://github.com/내아이디">github.com/내아이디 →</a>
  </section>

</main>

</body>
</html>
