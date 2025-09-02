<!doctype html>
<html lang="ko">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>01 Consulting — 디지털 컨설팅 세일즈 페이지</title>
  <meta name="description" content="Strategy → Automation → Growth. 실행 중심 설계로 매출과 문의를 직접 올립니다." />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Pretendard:wght@400;600;700;800&display=swap" rel="stylesheet">
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    html { scroll-behavior: smooth; }
    body { font-family: Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans KR", "Apple SD Gothic Neo", "Malgun Gothic", sans-serif; }
  </style>
</head>
<body class="min-h-screen bg-slate-50 text-slate-900">
  <!-- Header -->
  <header class="sticky top-0 z-40 backdrop-blur bg-white/70 border-b border-slate-200">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex items-center justify-between h-16">
      <a href="#top" class="flex items-center gap-2 font-semibold">
        <!-- sparkles icon -->
        <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#4f46e5" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 3l1.9 3.9L18 9l-4.1 2.1L12 15l-1.9-3.9L6 9l4.1-2.1L12 3z"/><path d="M5 3l.7 1.3L7 5l-1.3.7L5 7l-.7-1.3L3 5l1.3-.7L5 3z"/><path d="M19 17l.7 1.3L21 19l-1.3.7L19 21l-.7-1.3L17 19l1.3-.7L19 17z"/></svg>
        <span>01 Consulting</span>
      </a>
      <nav class="hidden md:flex items-center gap-8 text-sm">
        <a href="#services" class="hover:text-indigo-600">서비스</a>
        <a href="#pricing" class="hover:text-indigo-600">요금</a>
        <a href="#process" class="hover:text-indigo-600">프로세스</a>
      </nav>
      <button id="scroll-contact-btn" class="inline-flex items-center gap-2 rounded-xl px-4 py-2 bg-indigo-600 text-white text-sm font-semibold hover:bg-indigo-500">
        상담 요청
      </button>
    </div>
  </header>

  <!-- Hero -->
  <div id="top" class="relative overflow-hidden">
    <section class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-20 lg:py-28">
      <div class="grid lg:grid-cols-2 gap-10 items-center">
        <div>
          <h1 class="text-3xl sm:text-4xl lg:text-5xl font-extrabold leading-tight tracking-tight">
            디지털 컨설팅,
            <span class="block mt-2 bg-gradient-to-r from-indigo-600 via-fuchsia-600 to-pink-600 bg-clip-text text-transparent">결과로 증명합니다.</span>
          </h1>
          <p class="mt-5 text-slate-600 text-base sm:text-lg">
            Strategy → Automation → Growth. <span class="font-medium">AI × Growth × Automation</span>
            <br class="hidden sm:block" />
            실행 중심 설계로 매출과 문의를 <span class="font-semibold">직접</span> 올립니다.
          </p>
        </div>
        <div class="grid grid-cols-2 gap-3">
          <div class="rounded-2xl overflow-hidden shadow-xl shadow-slate-900/10 border border-white">
            <img loading="lazy" referrerpolicy="no-referrer" src="https://images.unsplash.com/photo-1556157382-97eda2d62296?q=80&w=1600&auto=format&fit=crop" alt="dashboard 1" class="h-36 sm:h-48 w-full object-cover" />
          </div>
          <div class="rounded-2xl overflow-hidden shadow-xl shadow-slate-900/10 border border-white">
            <img loading="lazy" referrerpolicy="no-referrer" src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f?q=80&w=1600&auto=format&fit=crop" alt="team work" class="h-36 sm:h-48 w-full object-cover" />
          </div>
          <div class="rounded-2xl overflow-hidden shadow-xl shadow-slate-900/10 border border-white">
            <img loading="lazy" referrerpolicy="no-referrer" src="https://images.unsplash.com/photo-1551434678-e076c223a692?q=80&w=1600&auto=format&fit=crop" alt="engineers" class="h-36 sm:h-48 w-full object-cover" />
          </div>
          <div class="rounded-2xl overflow-hidden shadow-xl shadow-slate-900/10 border border-white">
            <img loading="lazy" referrerpolicy="no-referrer" src="https://images.unsplash.com/photo-1521791136064-7986c2920216?q=80&w=1600&auto=format&fit=crop" alt="planning" class="h-36 sm:h-48 w-full object-cover" />
          </div>
        </div>
      </div>
    </section>
  </div>

  <!-- Features -->
  <section class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-10">
    <div class="grid sm:grid-cols-3 gap-4">
      <div class="rounded-2xl border border-slate-200 bg-white p-6 shadow-sm">
        <div class="w-10 h-10 rounded-xl bg-indigo-50 text-indigo-600 flex items-center justify-center mb-3">
          <!-- line chart icon -->
          <svg class="w-6 h-6" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M3 3v18h18"/><path d="M19 9l-5 5-4-4-6 6"/></svg>
        </div>
        <h3 class="font-semibold text-lg">데이터 기반 전략</h3>
        <p class="text-slate-600 mt-1 text-sm">Analytics → Insight → Action으로 전환하는 실행 설계.</p>
      </div>
      <div class="rounded-2xl border border-slate-200 bg-white p-6 shadow-sm">
        <div class="w-10 h-10 rounded-xl bg-indigo-50 text-indigo-600 flex items-center justify-center mb-3">
          <!-- zap icon -->
          <svg class="w-6 h-6" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polygon points="13 2 3 14 12 14 11 22 21 10 12 10 13 2"/></svg>
        </div>
        <h3 class="font-semibold text-lg">자동화 시스템</h3>
        <p class="text-slate-600 mt-1 text-sm">반복 업무를 AI·노코드로 자동화하여 효율 극대화.</p>
      </div>
      <div class="rounded-2xl border border-slate-200 bg-white p-6 shadow-sm">
        <div class="w-10 h-10 rounded-xl bg-indigo-50 text-indigo-600 flex items-center justify-center mb-3">
          <!-- rocket icon -->
          <svg class="w-6 h-6" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M4.5 16.5L7 14l3 3-2.5 2.5a2.121 2.121 0 0 1-3-3z"/><path d="M15 4l-3 3 5 5 3-3a8 8 0 0 0-5-5z"/><path d="M9 11l4 4"/></svg>
        </div>
        <h3 class="font-semibold text-lg">그로스 실험</h3>
        <p class="text-slate-600 mt-1 text-sm">주간 실험/리포트 루프로 빠르게 학습하고 확장.</p>
      </div>
    </div>
  </section>

  <!-- Services -->
  <section id="services" class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-16">
    <div class="mb-8">
      <h2 class="text-2xl sm:text-3xl font-extrabold tracking-tight">서비스 구성</h2>
      <p class="text-slate-600 mt-2">선택형 · 조합형 · 성장형. 필요한 것만 빠르게.</p>
    </div>
    <div class="grid lg:grid-cols-3 gap-6">
      <!-- Trend Subscription -->
      <div class="group rounded-2xl overflow-hidden border border-slate-200 bg-white shadow-sm hover:shadow-md transition-shadow">
        <div class="relative">
          <img loading="lazy" referrerpolicy="no-referrer" src="https://images.unsplash.com/photo-1589829545856-d10d557cf95f?q=80&w=1600&auto=format&fit=crop" alt="트렌드 구독 리포트" class="h-44 w-full object-cover" />
          <span class="absolute top-4 left-4 text-xs bg-black/70 text-white px-2 py-1 rounded-full">Subscription</span>
        </div>
        <div class="p-6">
          <h3 class="font-semibold text-lg">트렌드 구독 리포트 (월 10만원)</h3>
          <ul class="mt-3 space-y-2">
            <li class="flex items-start gap-2 text-sm text-slate-700"><svg class="w-4 h-4 mt-0.5 text-emerald-600" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><path d="M20 6L9 17l-5-5"/></svg> 주간/월간 인더스트리 트렌드 요약</li>
            <li class="flex items-start gap-2 text-sm text-slate-700"><svg class="w-4 h-4 mt-0.5 text-emerald-600" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><path d="M20 6L9 17l-5-5"/></svg> 경쟁/키워드/콘텐츠 인사이트</li>
            <li class="flex items-start gap-2 text-sm text-slate-700"><svg class="w-4 h-4 mt-0.5 text-emerald-600" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><path d="M20 6L9 17l-5-5"/></svg> 다음 액션 3가지 제안</li>
          </ul>
        </div>
      </div>

      <!-- Face-to-face Consulting -->
      <div class="group rounded-2xl overflow-hidden border border-slate-200 bg-white shadow-sm hover:shadow-md transition-shadow">
        <div class="relative">
          <img loading="lazy" referrerpolicy="no-referrer" src="https://images.unsplash.com/photo-1551836022-d5d88e9218df?q=80&w=1600&auto=format&fit=crop" alt="대면 컨설팅" class="h-44 w-full object-cover" />
          <span class="absolute top-4 left-4 text-xs bg-black/70 text-white px-2 py-1 rounded-full">Workshop</span>
        </div>
        <div class="p-6">
          <h3 class="font-semibold text-lg">대면 컨설팅 5회 (70만원)</h3>
          <ul class="mt-3 space-y-2">
            <li class="flex items-start gap-2 text-sm text-slate-700"><svg class="w-4 h-4 mt-0.5 text-emerald-600" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><path d="M20 6L9 17l-5-5"/></svg> 현황 진단 & 목표 재설정</li>
            <li class="flex items-start gap-2 text-sm text-slate-700"><svg class="w-4 h-4 mt-0.5 text-emerald-600" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><path d="M20 6L9 17l-5-5"/></svg> 퍼널/콘텐츠/세일즈 파이프라인 설계</li>
            <li class="flex items-start gap-2 text-sm text-slate-700"><svg class="w-4 h-4 mt-0.5 text-emerald-600" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><path d="M20 6L9 17l-5-5"/></svg> 자동화 플로우 맵 + 실행 가이드</li>
          </ul>
        </div>
      </div>

      <!-- Production -->
      <div class="group rounded-2xl overflow-hidden border border-slate-200 bg-white shadow-sm hover:shadow-md transition-shadow">
        <div class="relative">
          <img loading="lazy" referrerpolicy="no-referrer" src="https://images.unsplash.com/photo-1551292831-023188e78222?q=80&w=1600&auto=format&fit=crop" alt="제작 서비스" class="h-44 w-full object-cover" />
          <span class="absolute top-4 left-4 text-xs bg-black/70 text-white px-2 py-1 rounded-full">Production</span>
        </div>
        <div class="p-6">
          <h3 class="font-semibold text-lg">제작 서비스 (A la carte)</h3>
          <ul class="mt-3 space-y-2">
            <li class="flex items-start gap-2 text-sm text-slate-700"><svg class="w-4 h-4 mt-0.5 text-emerald-600" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><path d="M20 6L9 17l-5-5"/></svg> 이미지 편집 1만원 / 홍보 이미지 2만원</li>
            <li class="flex items-start gap-2 text-sm text-slate-700"><svg class="w-4 h-4 mt-0.5 text-emerald-600" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><path d="M20 6L9 17l-5-5"/></svg> 영상 편집 1만원</li>
            <li class="flex items-start gap-2 text-sm text-slate-700"><svg class="w-4 h-4 mt-0.5 text-emerald-600" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"><path d="M20 6L9 17l-5-5"/></svg> 홍보 영상 30초 30만원 · 1분 50만원 · 3분 100만원</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <!-- Pricing -->
  <section id="pricing" class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-16">
    <div class="mb-8 text-center">
      <h2 class="text-2xl sm:text-3xl font-extrabold tracking-tight">요금 플랜</h2>
      <p class="text-slate-600 mt-2">명확하고 합리적인 가격. 필요하면 지금 시작하세요.</p>
    </div>
    <div class="grid lg:grid-cols-3 gap-6">
      <div class="rounded-2xl border border-slate-200 bg-white p-6 shadow-sm">
        <h3 class="font-semibold text-lg mb-2">트렌드 구독</h3>
        <div class="text-2xl font-extrabold mb-4">₩100,000 <span class="text-base font-medium text-slate-500">/월</span></div>
        <ul class="space-y-2 text-sm">
          <li>주간·월간 리포트</li>
          <li>산업/키워드/콘텐츠 인사이트</li>
          <li>다음 액션 제안 3가지</li>
        </ul>
      </div>
      <div class="rounded-2xl border border-slate-200 bg-white p-6 shadow-sm">
        <h3 class="font-semibold text-lg mb-2">대면 5회 컨설팅</h3>
        <div class="text-2xl font-extrabold mb-4">₩700,000 <span class="text-base font-medium text-slate-500">/패키지</span></div>
        <ul class="space-y-2 text-sm">
          <li>현황 진단 & 목표 설정</li>
          <li>퍼널·세일즈 파이프라인 설계</li>
          <li>자동화 구축 가이드</li>
        </ul>
      </div>
      <div class="rounded-2xl border border-slate-200 bg-white p-6 shadow-sm">
        <h3 class="font-semibold text-lg mb-2">제작 서비스</h3>
        <div class="text-2xl font-extrabold mb-4">A la carte</div>
        <ul class="space-y-2 text-sm">
          <li>이미지 편집 1만원 / 홍보 이미지 2만원</li>
          <li>영상 편집 1만원</li>
          <li>홍보 영상 30초 30만원 · 1분 50만원 · 3분 100만원</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- Process -->
  <section id="process" class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-16">
    <div class="mb-8 text-center">
      <h2 class="text-2xl sm:text-3xl font-extrabold tracking-tight">진행 프로세스</h2>
      <p class="text-slate-600 mt-2">진단 → 설계 → 자동화 → 실행 → 리포트</p>
    </div>
    <div class="grid md:grid-cols-5 gap-4">
      <div class="rounded-2xl bg-white border border-slate-200 p-6 text-center shadow-sm">
        <div class="mx-auto w-10 h-10 rounded-xl bg-indigo-50 text-indigo-600 flex items-center justify-center font-bold">1</div>
        <h3 class="mt-3 font-semibold">진단</h3>
        <p class="text-sm text-slate-600">현황/데이터/경쟁 분석</p>
      </div>
      <div class="rounded-2xl bg-white border border-slate-200 p-6 text-center shadow-sm">
        <div class="mx-auto w-10 h-10 rounded-xl bg-indigo-50 text-indigo-600 flex items-center justify-center font-bold">2</div>
        <h3 class="mt-3 font-semibold">설계</h3>
        <p class="text-sm text-slate-600">퍼널·콘텐츠·세일즈 구조화</p>
      </div>
      <div class="rounded-2xl bg-white border border-slate-200 p-6 text-center shadow-sm">
        <div class="mx-auto w-10 h-10 rounded-xl bg-indigo-50 text-indigo-600 flex items-center justify-center font-bold">3</div>
        <h3 class="mt-3 font-semibold">자동화</h3>
        <p class="text-sm text-slate-600">CRM·메시징·리포팅 자동화</p>
      </div>
      <div class="rounded-2xl bg-white border border-slate-200 p-6 text-center shadow-sm">
        <div class="mx-auto w-10 h-10 rounded-xl bg-indigo-50 text-indigo-600 flex items-center justify-center font-bold">4</div>
        <h3 class="mt-3 font-semibold">실행</h3>
        <p class="text-sm text-slate-600">캠페인/콘텐츠 운영</p>
      </div>
      <div class="rounded-2xl bg-white border border-slate-200 p-6 text-center shadow-sm">
        <div class="mx-auto w-10 h-10 rounded-xl bg-indigo-50 text-indigo-600 flex items-center justify-center font-bold">5</div>
        <h3 class="mt-3 font-semibold">리포트</h3>
        <p class="text-sm text-slate-600">실험 결과 & 다음 액션</p>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-16">
    <div class="mb-8 text-center">
      <h2 class="text-2xl sm:text-3xl font-extrabold tracking-tight">지금 상담을 신청하세요</h2>
      <p class="text-slate-600 mt-2">빠르게 현황을 진단하고, 다음 주부터 실행할 수 있습니다.</p>
    </div>
    <div class="grid lg:grid-cols-2 gap-6">
      <div class="rounded-2xl bg-white border border-slate-200 p-6 shadow-sm">
        <form action="mailto:nijohiohc2@gmail.com" method="POST" enctype="text/plain" class="space-y-4">
          <div>
            <label class="text-sm font-medium">이름</label>
            <input name="name" required class="mt-1 w-full rounded-xl border border-slate-300 px-3 py-2" placeholder="홍길동" />
          </div>
          <div>
            <label class="text-sm font-medium">연락처/이메일</label>
            <input name="contact" required class="mt-1 w-full rounded-xl border border-slate-300 px-3 py-2" placeholder="010-0000-0000 / you@email.com" />
          </div>
          <div>
            <label class="text-sm font-medium">요청 사항</label>
            <textarea name="message" rows="4" class="mt-1 w-full rounded-xl border border-slate-300 px-3 py-2" placeholder="현재 상황과 원하는 목표를 적어주세요."></textarea>
          </div>
          <button type="submit" class="inline-flex items-center gap-2 rounded-xl bg-indigo-600 text-white px-5 py-3 font-semibold hover:bg-indigo-500">
            <!-- phone icon -->
            <svg class="w-5 h-5" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6A19.79 19.79 0 0 1 2.09 4.18 2 2 0 0 1 4.07 2h3a2 2 0 0 1 2 1.72 12.66 12.66 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.23a2 2 0 0 1 2.11-.45 12.66 12.66 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"/></svg>
            상담 요청 보내기
          </button>
        </form>
      </div>
      <div class="rounded-2xl bg-gradient-to-br from-indigo-600 via-fuchsia-600 to-pink-600 text-white p-6 shadow-sm">
        <h3 class="font-semibold text-lg">바로 연락하기</h3>
        <ul class="mt-3 space-y-2 text-sm">
          <li>✉️ 이메일: <a class="underline" href="mailto:nijohiohc2@gmail.com">nijohiohc2@gmail.com</a></li>
          <li>📞 전화: <a class="underline" href="tel:01032934345">01032934345</a></li>
          <li>💬 카카오톡: <a class="underline" href="https://open.kakao.com/o/yourroom" target="_blank" rel="noreferrer noopener">오픈채팅 연결</a></li>
        </ul>
        <div class="mt-6 text-sm text-white/90">✅ 영수증·세금계산서 발행 가능 / NDA 요청 시 협의 / B2B·개인 모두 가능</div>
      </div>
    </div>
  </section>

  <script>
    // 상단 버튼으로 하단 상담 섹션으로 스크롤
    document.getElementById('scroll-contact-btn')?.addEventListener('click', function () {
      document.getElementById('contact')?.scrollIntoView({ behavior: 'smooth', block: 'start' });
    });
  </script>

  <!-- Footer (customized for Glomile) -->
  <footer class="bg-slate-900 text-slate-100">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-10">
      <div class="grid md:grid-cols-4 gap-6">
        <div class="md:col-span-2">
          <div class="font-semibold text-lg">글로마일</div>
          <p class="mt-3 text-sm text-slate-300 leading-6">
            대표 최호진<br/>
            사업자등록번호 169-45-00708<br/>
            서울특별시 송파구 송파대로 G-129 테라타워2
          </p>
        </div>
        <div>
          <div class="font-semibold">정책</div>
          <ul class="mt-3 space-y-2 text-sm text-slate-300">
            <li><a href="#" class="hover:underline">이용약관</a></li>
            <li><a href="#" class="hover:underline">개인정보 취급방침</a></li>
            <li><a href="#" class="hover:underline">회사소개서</a></li>
          </ul>
        </div>
      </div>
      <div class="mt-8 pt-6 border-t border-white/10 text-xs text-slate-400">
        Copyright©2025 Glomile All rights reserved.
      </div>
    </div>
  </footer>
</body>
</html>
