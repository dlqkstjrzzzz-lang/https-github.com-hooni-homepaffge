<!doctype html>
<html lang="ko">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>동타오 MMA | 종합격투기 체육관</title>
  <meta name="description" content="동타오 MMA — 종합격투기/주짓수/킥복싱. 체계적인 커리큘럼과 맞춤 지도, 첫 수업 무료 체험." />
  <meta property="og:title" content="동타오 MMA" />
  <meta property="og:description" content="종합격투기/주짓수/킥복싱 — 첫 수업 무료 체험" />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="https://images.unsplash.com/photo-1503023345310-bd7c1de61c7d?w=1200" />
  <link rel="icon" href="data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'><text y='.9em' font-size='90'>🥋</text></svg>">
  <!-- Tailwind CDN (Zero build, works on Vercel Drag&Drop) -->
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    /* Smooth scroll */
    html { scroll-behavior: smooth; }
    /* Simple gradient text utility */
    .text-gradient { background: linear-gradient(90deg, #ef4444, #f59e0b, #10b981); -webkit-background-clip: text; background-clip: text; color: transparent; }
  </style>
</head>
<body class="min-h-screen bg-slate-50 text-slate-900">
  <!-- Nav -->
  <header class="sticky top-0 z-50 bg-white/80 backdrop-blur border-b">
    <div class="max-w-7xl mx-auto px-4 py-3 flex items-center justify-between">
      <a href="#hero" class="font-black text-xl">동타오 <span class="text-gradient">MMA</span></a>
      <nav class="hidden md:flex gap-6 text-sm">
        <a class="hover:opacity-80" href="#programs">프로그램</a>
        <a class="hover:opacity-80" href="#schedule">시간표</a>
        <a class="hover:opacity-80" href="#coaches">코치</a>
        <a class="hover:opacity-80" href="#pricing">이용요금</a>
        <a class="hover:opacity-80" href="#location">오시는길</a>
        <a class="hover:opacity-80" href="#contact">문의</a>
      </nav>
      <a href="#contact" class="hidden md:inline-flex h-10 px-4 items-center justify-center rounded-xl bg-slate-900 text-white text-sm hover:opacity-90">무료 체험 신청</a>
      <button id="menuBtn" class="md:hidden h-10 px-3 rounded-lg border">메뉴</button>
    </div>
    <div id="mobileMenu" class="md:hidden hidden border-t bg-white">
      <div class="max-w-7xl mx-auto px-4 py-3 grid gap-2 text-sm">
        <a class="py-1" href="#programs">프로그램</a>
        <a class="py-1" href="#schedule">시간표</a>
        <a class="py-1" href="#coaches">코치</a>
        <a class="py-1" href="#pricing">이용요금</a>
        <a class="py-1" href="#location">오시는길</a>
        <a class="py-1" href="#contact">문의</a>
      </div>
    </div>
  </header>

  <!-- Hero -->
  <section id="hero" class="relative overflow-hidden">
    <div class="max-w-7xl mx-auto px-4 py-16 md:py-24 grid md:grid-cols-2 gap-10 items-center">
      <div>
        <h1 class="text-4xl md:text-6xl font-black leading-tight">실전이 강해지는 곳
          <span class="block text-gradient">동타오 MMA</span>
        </h1>
        <p class="mt-5 text-lg text-slate-600">종합격투기 · 주짓수 · 킥복싱 · 레슬링. 초보부터 선수 준비까지, 레벨별 맞춤 지도로 성장하세요.</p>
        <div class="mt-8 flex gap-3">
          <a href="#schedule" class="h-11 px-5 inline-flex items-center justify-center rounded-xl bg-slate-900 text-white text-sm hover:opacity-90">오늘 시간표 보기</a>
          <a href="#contact" class="h-11 px-5 inline-flex items-center justify-center rounded-xl border text-sm">무료 체험 신청</a>
        </div>
        <ul class="mt-6 text-slate-600 text-sm grid gap-1">
          <li>✔︎ 첫 수업 무료 · 체험 후 등록 가능</li>
          <li>✔︎ 체계적인 스트렝스 & 컨디셔닝</li>
          <li>✔︎ 경기 준비용 스파링 세션 운영</li>
        </ul>
      </div>
      <div class="relative">
        <div class="aspect-video rounded-3xl overflow-hidden shadow ring-1 ring-black/5">
          <img src="https://images.unsplash.com/photo-1552072092-7f9b8d63efcb?w=1600&q=80&auto=format&fit=crop" alt="MMA training" class="h-full w-full object-cover" />
        </div>
      </div>
    </div>
  </section>

  <!-- Programs -->
  <section id="programs" class="py-16 md:py-24 border-t bg-white">
    <div class="max-w-7xl mx-auto px-4">
      <h2 class="text-3xl font-black">프로그램</h2>
      <p class="mt-2 text-slate-600">기초부터 실전까지 단계별 커리큘럼.</p>
      <div class="mt-8 grid md:grid-cols-3 gap-6">
        <div class="border rounded-2xl p-6 bg-slate-50">
          <h3 class="font-bold text-lg">MMA 종합</h3>
          <p class="mt-2 text-slate-600">타격+그래플링 통합 전술, 케이지 컨트롤, 그라운드 앤 파운드.</p>
          <ul class="mt-3 text-sm text-slate-600 list-disc ps-5">
            <li>초·중·상 레벨반 운영</li>
            <li>주 2회 스파링</li>
          </ul>
        </div>
        <div class="border rounded-2xl p-6 bg-slate-50">
          <h3 class="font-bold text-lg">주짓수</h3>
          <p class="mt-2 text-slate-600">가드·패스·스윕·서브미션 기초부터 노기 스타일 실전 적용.</p>
          <ul class="mt-3 text-sm text-slate-600 list-disc ps-5">
            <li>노기 중심, 기술드릴</li>
            <li>오픈 매트 제공</li>
          </ul>
        </div>
        <div class="border rounded-2xl p-6 bg-slate-50">
          <h3 class="font-bold text-lg">킥복싱/복싱</h3>
          <p class="mt-2 text-slate-600">풋워크·타격 라인·콤비네이션과 실전 디펜스.</p>
          <ul class="mt-3 text-sm text-slate-600 list-disc ps-5">
            <li>미트/백 워크</li>
            <li>라이트 스파링</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <!-- Schedule -->
  <section id="schedule" class="py-16 md:py-24 border-t bg-slate
