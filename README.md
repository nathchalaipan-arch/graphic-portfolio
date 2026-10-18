<!DOCTYPE html>
<html lang="th" class="scroll-smooth">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Nathchalai P. (Mind) — Senior Graphic & Motion Designer Portfolio</title>
  
  <!-- Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700&family=Space+Grotesk:wght@400;600;700&display=swap" rel="stylesheet">
  
  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      darkMode: 'class',
      theme: {
        extend: {
          colors: {
            bgDark: '#0B0F17',
            cardDark: '#131A26',
            accentGold: '#E2B883',
            accentMuted: '#94A3B8'
          },
          fontFamily: {
            sans: ['"Plus Jakarta Sans"', 'sans-serif'],
            display: ['"Space Grotesk"', 'sans-serif']
          }
        }
      }
    }
  </script>
  <style>
    body { background-color: #0B0F17; color: #F8FAFC; }
    .glass-nav {
      background: rgba(11, 15, 23, 0.85);
      backdrop-filter: blur(12px);
      -webkit-backdrop-filter: blur(12px);
    }
    .gold-gradient-text {
      background: linear-gradient(135deg, #FFF 20%, #E2B883 100%);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }
  </style>
</head>
<body class="font-sans antialiased selection:bg-amber-400/20 selection:text-amber-200">

  <!-- Navigation -->
  <nav class="fixed top-0 left-0 w-full z-40 glass-nav border-b border-white/5 transition-all duration-300">
    <div class="max-w-7xl mx-auto px-6 h-20 flex items-center justify-between">
      <a href="#" class="font-display text-xl font-bold tracking-tight text-white flex items-center gap-2">
        <span class="w-2.5 h-2.5 rounded-full bg-amber-400 animate-pulse"></span>
        NATHCHALAI.P
      </a>
      <div class="hidden md:flex items-center gap-8 text-sm font-medium text-slate-300">
        <a href="#work" class="hover:text-amber-300 transition-colors">Selected Work</a>
        <a href="#about" class="hover:text-amber-300 transition-colors">Experience</a>
        <a href="#contact" class="hover:text-amber-300 transition-colors">Contact</a>
      </div>
      <a href="mailto:nathchalai.pforwork@gmail.com" class="px-5 py-2.5 rounded-full text-xs font-semibold tracking-wider uppercase bg-white/10 hover:bg-amber-400 hover:text-black transition-all duration-300 border border-white/10">
        Let's Talk
      </a>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="min-h-screen pt-36 pb-20 px-6 flex flex-col justify-center relative overflow-hidden">
    <!-- Glow Effect Background -->
    <div class="absolute top-1/4 left-1/2 -translate-x-1/2 w-[600px] h-[350px] bg-amber-500/10 blur-[130px] rounded-full pointer-events-none"></div>

    <div class="max-w-5xl mx-auto text-center relative z-10">
      <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full bg-white/5 border border-white/10 text-xs font-medium text-amber-300 mb-8 tracking-wide">
        SENIOR GRAPHIC & MOTION DESIGNER
      </div>
      <h1 class="font-display text-4xl sm:text-6xl md:text-7xl font-bold tracking-tight leading-[1.1] mb-8 gold-gradient-text">
        Bridging Contemporary Visuals & High-Impact Digital Motion.
      </h1>
      <p class="max-w-2xl mx-auto text-slate-400 text-base sm:text-lg leading-relaxed mb-10">
        สร้างสรรค์ผลงานกราฟิกและโมชันที่ตอบโจทย์ทั้งความสวยงามร่วมสมัยและผลลัพธ์ทางการตลาด ด้วยประสบการณ์กว่า 5 ปี สำหรับแบรนด์ระดับภูมิภาคและสื่อชั้นนำ
      </p>
      
      <div class="flex flex-wrap items-center justify-center gap-4">
        <a href="#work" class="px-8 py-3.5 rounded-full bg-white text-black font-semibold text-sm hover:bg-amber-300 transition-all duration-300 shadow-lg shadow-white/5">
          ชมผลงานที่คัดสรร
        </a>
        <a href="https://drive.google.com/drive/folders/10BgO48Et4zsmpFcrdgoxNNCRSjM_3wJm?usp=sharing" target="_blank" class="px-8 py-3.5 rounded-full bg-white/5 border border-white/10 font-semibold text-sm text-slate-200 hover:bg-white/10 hover:text-white transition-all duration-300 flex items-center gap-2">
          <span>Google Drive Portfolio</span>
          <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"/></svg>
        </a>
      </div>
    </div>
  </section>

  <!-- Filter & Portfolio Section -->
  <section id="work" class="py-24 px-6 border-t border-white/5 bg-slate-950/40">
    <div class="max-w-7xl mx-auto">
      <div class="flex flex-col md:flex-row md:items-end justify-between mb-12 gap-6">
        <div>
          <span class="text-xs uppercase tracking-widest
