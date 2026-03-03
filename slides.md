---
# Slidev frontmatter
theme: default
title: QI4U in Finland Day1
class: text-center font-sans
transition: slide-left
mdc: true
duration: 35min
colorSchema: dark
# 背景をグラデーション風に
background: linear-gradient(180deg, #0f1c47 0%, #1e2a78 100%)
---

# QI4U in Finland Day1
## The basics of Quantum Computing

<div
  @click="$slidev.nav.next"
  class="mt-12 mx-auto py-3 px-6 w-100 rounded-xl text-white font-bold cursor-pointer
         relative overflow-hidden text-center transition-all duration-300
         hover:scale-[1.02] active:scale-[0.99]
         bg-[#0b0f19]/70 backdrop-blur border border-white/10 shadow-lg"
>
  <!-- うっすらグラデ（Day2: 紫→青→シアン） -->
  <div class="absolute inset-0 bg-gradient-to-r from-purple-700/25 via-blue-500/20 to-cyan-400/25 -z-10"></div>

  <!-- ハイライトが流れる -->
  <div class="shine absolute -inset-y-2 -left-1/2 w-1/2 rotate-12 -z-10"></div>

  <!-- テキスト：1行固定で自動縮小 -->
  <span class="inline-flex items-center justify-center w-full whitespace-nowrap tracking-[0.07em]">
    <span class="text-sm leading-tight">
      Can quantum become a toy?
    </span>
    <carbon:arrow-right class="inline w-8 h-6 ml-1 opacity-90 flex-none" />
  </span>
</div>

---
transition: slide-left
layout: center
---
# Quantum computing can impact **many fields**
## The impact grows when **people from different backgrounds** learn it

<div class="fields">
  <span class="tag">🧪 Chemistry</span>
  <span class="tag">💊 Drug discovery</span>
  <span class="tag">🏭 Materials</span>
  <span class="tag">⚡ Energy</span>
  <span class="tag">📦 Logistics</span>
  <span class="tag">🚦 Traffic</span>
  <span class="tag">💰 Finance</span>
  <span class="tag">📈 Economics</span>
  <span class="tag">🔐 Cybersecurity</span>
  <span class="tag">🧠 Machine learning</span>
</div>

<style>
/* Field tags */
.fields{
  margin-top: 1.6rem;
  display:flex;
  flex-wrap:wrap;
  gap:.55rem;
  justify-content:center;
  width: min(980px, 92vw);
  margin-left:auto;
  margin-right:auto;
}
.tag{
  padding: .45rem .7rem;
  border-radius: 999px;
  border: 1px solid rgba(255,255,255,.14);
  background: rgba(255,255,255,.06);
  font-size: .95rem;
  line-height: 1;
  letter-spacing: .01em;
  box-shadow: 0 10px 25px rgba(0,0,0,.25);
}
</style>

---
transition: fade-out
layout: center
---

# But quantum computing **feels hard**
## Many people see it as a **high barrier**

<div class="barriers">
  <span class="tag">📘 Math-heavy textbooks</span>
  <span class="tag">🌫 “Quantum is mysterious”</span>
  <span class="tag">💻 Programming anxiety</span>
  <span class="tag">🧩 Hard to imagine real use cases</span>
</div>

<style>
h1{ letter-spacing:-.02em; }
h2{ opacity:.9; margin-top:.35rem; }

.barriers{
  margin-top: 1.7rem;
  display:flex;
  flex-wrap:wrap;
  gap:.6rem;
  justify-content:center;
  width: min(860px, 92vw);
  margin-left:auto;
  margin-right:auto;
}
.tag{
  padding: .48rem .75rem;
  border-radius: 999px;
  border: 1px solid rgba(255,255,255,.14);
  background: rgba(255,255,255,.06);
  font-size: .98rem;
  line-height: 1;
  box-shadow: 0 10px 25px rgba(0,0,0,.25);
}
</style>

---
transition: fade-out
layout: center
---

# The main reason is: it feels **unfamiliar**
## Not “too hard” — just “hard to get close to”

<div class="reasons">
  <span class="tag">📘 Full of equations</span>
  <span class="tag">🌀 Quantum mechanics feels abstract</span>
  <span class="tag">💻 “I can’t code”</span>
  <span class="tag">🔎 Use cases feel unclear</span>
</div>

<style>
h1{ letter-spacing:-.02em; }
h2{ opacity:.9; margin-top:.35rem; }

.reasons{
  margin-top: 1.7rem;
  display:flex;
  flex-wrap:wrap;
  gap:.6rem;
  justify-content:center;
  width: min(900px, 92vw);
  margin-left:auto;
  margin-right:auto;
}
.tag{
  padding: .48rem .75rem;
  border-radius: 999px;
  border: 1px solid rgba(255,255,255,.14);
  background: rgba(255,255,255,.06);
  font-size: .98rem;
  line-height: 1;
  box-shadow: 0 10px 25px rgba(0,0,0,.25);
}
</style>
---
transition: fade-out
layout: center
---

# It’s hard to learn quantum computing as something **personal**
## But to apply it, we must treat quantum as a **tool**

<div class="panel">
  <div class="col">
    <div class="label">Reality</div>
    <div class="big">Overwhelmed by “quantum”</div>
    <div class="small">Concepts feel distant · not connected to our own problems</div>
  </div>

  <div class="arrow">→</div>

  <div class="col highlight">
    <div class="label">Goal</div>
    <div class="big">Use quantum as a tool</div>
    <div class="small">“Put options into superposition…”<br/>“Use interference to boost the answer…”</div>
  </div>
</div>

<style>
h1{ letter-spacing:-.02em; }
h2{ opacity:.9; margin-top:.35rem; }

.panel{
  margin-top: 1.8rem;
  display:grid;
  grid-template-columns: 1fr auto 1fr;
  gap: 1rem;
  align-items: stretch;
  width: min(980px, 92vw);
  margin-left:auto;
  margin-right:auto;
}

.col{
  padding: 1.1rem 1.1rem;
  border-radius: 20px;
  border: 1px solid rgba(255,255,255,.12);
  background: rgba(255,255,255,.04);
}

/* No gradient: just a slightly stronger outline + subtle glow */
.col.highlight{
  border: 1px solid rgba(255,255,255,.22);
  background: rgba(255,255,255,.06);
  box-shadow: 0 18px 45px rgba(55, 45, 125, 0.35);
}

.label{
  display:inline-block;
  padding: .28rem .65rem;
  border-radius: 999px;
  border: 1px solid rgba(255,255,255,.14);
  background: rgba(255,255,255,.06);
  font-size: .9rem;
  opacity: .9;
}

.big{
  margin-top: .65rem;
  font-size: 1.35rem;
  font-weight: 600;
  letter-spacing: -.02em;
}

.small{
  margin-top: .55rem;
  opacity: .82;
  font-size: 1rem;
  line-height: 1.25;
}

.arrow{
  display:flex;
  align-items:center;
  justify-content:center;
  font-size: 2.2rem;
  font-weight: 800;
  opacity: .85;
  filter: drop-shadow(0 10px 25px rgba(0,0,0,.35));
}
</style>

---
transition: fade-out
layout: center
---

# 1. Can participants make quantum computing feel **personal**?

# 2. Can we teach quantum computing more **operationally** — like playing with a toy?

# 3. Can we build this workshop **together** and explore exciting applications of quantum algorithms?

---
transition: fade-out
layout: center
---
# What we will do in this workshop

1. In group work, you will design applications of quantum algorithms. (Day 2 & Day 3)

2. To make that possible, we will explain quantum mechanics in an operational way using **Circle Notation**. (Day 1 & Day 2)

3. To make learning even more hands-on, we prepared interactive learning materials.

---
transition: slide-left
---
# What you will do (more concretely)

<div style="position:relative;padding-bottom:50%;">
    <!-- 56.25 comes from aspect ratio of 16:9, change this accordingly -->
    <iframe
        style="width:100%;height:100%;position:absolute;left:0px;top:0px;"
        frameborder="0"
        width="100%"
        height="100%"
        allowfullscreen
        allow="autoplay"
        src="graph-builder2.html">
    </iframe>
</div>

---
transition: slide-left
layout: center
---

# About us

<div class="grid">
  <div class="card">
    <div class="label">Host</div>
    <div class="main"><a href="https://altema.is.tohoku.ac.jp/~mohzeki">Ohzeki Lab</a></div>
    <div class="sub">Tohoku University / Institute of Science Tokyo</div>
  </div>

  <div class="card">
    <div class="label">Supporters</div>
    <div class="main"><a href="https://meetiqm.com">IQM Quantum Computers</a></div>
    <div class="sub">+ students from Aalto University</div>
  </div>

  <div class="card wide">
    <div class="label">What is the Quantum Universe EXPO?</div>
    <div class="sub2">
      An outreach initiative where Ohzeki Lab hosts quantum computing workshops in countries around the world.
    </div>
    <div class="chips">
      <span class="chip">🇮🇹 Italy</span>
      <span class="chip">🇰🇷 Korea</span>
      <span class="chip">🇫🇮 Finland</span>
      <span class="chip">🇵🇱 Poland</span>
      <span class="chip">🇨🇳 China</span>
      <span class="chip">🇵🇪 Peru</span>
      <span class="chip">🇹🇼 Taiwan</span>
      <span class="chip">🇬🇧 UK</span>
    </div>
  </div>
</div>

<style>
h1{ letter-spacing:-.02em; text-align:center; }

.grid{
  margin-top: 1.6rem;
  width: min(700px, 92vw);
  margin-left:auto;
  margin-right:auto;
  display:grid;
  grid-template-columns: 1fr 1fr;
  gap: 1rem;
}
.card{
  padding: 1.15rem 1.2rem;
  border-radius: 18px;
  border: 1px solid rgba(255,255,255,.12);
  background: rgba(255,255,255,.04);
  box-shadow: 0 14px 35px rgba(0,0,0,.22);
}
.card.wide{ grid-column: 1 / -1; }

.label{
  display:inline-block;
  padding: .28rem .65rem;
  border-radius: 999px;
  border: 1px solid rgba(255,255,255,.14);
  background: rgba(255,255,255,.06);
  font-size: .rem;
  opacity: .9;
}

.main{
  margin-top: .65rem;
  font-size: 1.45rem;
  font-weight: 700;
  letter-spacing: -.02em;
}

.sub{
  margin-top: .25rem;
  opacity: .82;
  font-size: 1.05rem;
}

.sub2{
  margin-top: .7rem;
  opacity: .88;
  font-size: 1.15rem;
  line-height: 1.35;
  max-width: 920px;
}

.chips{
  margin-top: 1rem;
  display:flex;
  flex-wrap:wrap;
  gap:.55rem;
}
.chip{
  padding: .42rem .7rem;
  border-radius: 999px;
  border: 1px solid rgba(255,255,255,.14);
  background: rgba(255,255,255,.06);
  font-size: .98rem;
  line-height: 1;
}
</style>

---
transition: slide-left
layout: center
---

# Organizing Team

<div class="team">
  <div class="card">
    <div class="avatar">TS</div>
    <div class="name">Taiga Suzuki</div>
    <div class="aff">Institute of Science Tokyo</div>
    <div class="role">Lead Organizer · M1</div>
  </div>

  <div class="card">
    <div class="avatar">SK</div>
    <div class="name">Sasuke Kimata</div>
    <div class="aff">Tohoku University</div>
    <div class="role">Vice Lead Organizer · M1</div>
  </div>

  <div class="card">
    <div class="avatar">DM</div>
    <div class="name">Daiki Masuguchi</div>
    <div class="aff">Tohoku University</div>
    <div class="role">M1</div>
  </div>

  <div class="card">
    <div class="avatar">TU</div>
    <div class="name">Togo Urayama</div>
    <div class="aff">Tohoku University</div>
    <div class="role">B4</div>
  </div>

  <div class="card">
    <div class="avatar">SH</div>
    <div class="name">Shugo Hosokawa</div>
    <div class="aff">Tohoku University</div>
    <div class="role">B4</div>
  </div>

  <div class="card">
    <div class="avatar">MO</div>
    <div class="name">Motoharu Onodera</div>
    <div class="aff">Science Tokyo</div>
    <div class="role">B1</div>
  </div>

  <div class="card">
    <div class="avatar">UB</div>
    <div class="name">Upanyan Baskota</div>
    <div class="aff">Aalto University</div>
    <div class="role">B1</div>
  </div>

  <div class="card">
    <div class="avatar">RU</div>
    <div class="name">Rafet Uregen</div>
    <div class="aff">Aalto University</div>
    <div class="role">B1</div>
  </div>

  <div class="card">
    <div class="avatar">NN</div>
    <div class="name">Niklas Näsman</div>
    <div class="aff">Aalto University</div>
    <div class="role">B1</div>
  </div>

  <div class="card">
    <div class="avatar">AM</div>
    <div class="name">Aditya Mukherjee</div>
    <div class="aff">Aalto University</div>
    <div class="role">B1</div>
  </div>
</div>

<style>
h1{ text-align:center; letter-spacing:-.02em; }

.team{
  margin-top: 1.4rem;
  margin-left:auto;
  margin-right:auto;
  display:grid;
  grid-template-columns: repeat(5, minmax(0, 1fr));
  gap: .5rem;
}

.card{
  padding: .5rem .5rem;
  border-radius: 18px;
  border: 1px solid rgba(255,255,255,.12);
  background: rgba(255,255,255,.04);
  box-shadow: 0 14px 35px rgba(0,0,0,.22);
  display:flex;
  flex-direction:column;
  align-items:center;
  text-align:center;
}

.avatar{
  width: 3.1rem;
  height: 3.1rem;
  border-radius: 999px;
  display:flex;
  align-items:center;
  justify-content:center;
  font-weight: 900;
  letter-spacing: .02em;
  border: 1px solid rgba(255,255,255,.16);
  background: rgba(255,255,255,.06);
  margin-bottom: .55rem;
}

.name{
  font-size: 1.05rem;
  font-weight: 700;
  letter-spacing: -.01em;
  line-height: 1.15;
}

.aff{
  margin-top: .25rem;
  opacity: .8;
  font-size: .92rem;
  line-height: 1.2;
}

.role{
  margin-top: .45rem;
  font-size: .7rem;
  opacity: .9;
  padding: .22rem .55rem;
  border-radius: 999px;
  border: 1px solid rgba(255,255,255,.12);
  background: rgba(255,255,255,.05);
}

/* Responsive: if screen is narrow, reduce columns */
@media (max-width: 900px){
  .team{ grid-template-columns: repeat(3, minmax(0, 1fr)); }
}
@media (max-width: 520px){
  .team{ grid-template-columns: repeat(2, minmax(0, 1fr)); }
}
</style>
---
transition: slide-left
---
# Schedule

## Day 1 (Fundamentals of Quantum Computing)
- 17:20 – 18:25: Lecture + Hands-on
- 18:30 – 19:00: Invited Talk (Dr. Juha Vartiainen)
- 19:00 – 19:30: Group work

## Day 2 (Fundamentals of Quantum Algorithms)
- 17:00 – 18:45: Lecture + Hands-on (with a short break)
- 18:45 – 19:30: Group work

## Day 3 (Applications & Presentations)
- 17:00 – 17:30: Preparation (group work)
- 17:30 – ~18:45: Presentations
- 18:50 – 19:30: Closing ceremony + group photo

---
transition: slide-left
---

# Notes & Guidelines

1. We welcome questions anytime via Slido! Feel free to ask through Slido or by raising your hand.
<div class="flex justify-center mt-8">
  <a href="https://app.sli.do/event/hGPa8UXZbgRqGi2ueJr91M/live/questions"
     target="_blank" rel="noopener"
     class="inline-flex items-center gap-3 px-4 py-2 rounded-lg bg-[#4285F4] hover:bg-[#357ae8] text-white font-medium shadow-md">
    <svg width="20" height="20" viewBox="0 0 24 24" fill="none" aria-hidden>
      <path d="M12 2L22 7v10l-10 5-10-5V7z" fill="white" opacity="0.12"/>
      <path d="M12 2l10 5-10 5-10-5z" fill="white"/>
    </svg>
    # 12259224
  </a>
 </div>

2. Please do not share the materials URL with third parties.  
- It may include special access links (e.g., to quantum hardware).

3. Please be respectful of one another.  
- Participants come from diverse nationalities and backgrounds. If anything makes you uncomfortable, please contact the organizers.

4. Please be an active learner.  
- Keep in mind that over these three days you will work on developing your own application ideas, so listen with that goal in mind.

5. About Q&A  
- We are student organizers, not professors. We may not be able to answer very deep theoretical questions in quantum mechanics, but we can recommend appropriate resources and support your learning.\

---
transition:  slide-left
---

# Part 1: Lecture

<div class="flex justify-center mt-4">
  <div class="flex w-full max-w-5xl h-[400px] bg-[#222222] rounded-2xl overflow-hidden shadow-2xl border border-gray-600">

  <div class="flex flex-col justify-between p-12 flex-1">
      <div>
        <h3 class="text-4xl font-bold text-white mb-6">The concept of quantum computing</h3>
        <p class="text-xl text-gray-300 leading-relaxed">
          In Part 1, we will review the overall flow of quantum computing: encoding, computation, and decoding.
        </p>
        <p class="text-lg text-gray-400 mt-8 font-medium">Instructors: Shugo</p>
      </div>
    </div> <div class="flex w-[500px] h-full shrink-0 border-l border-gray-700">
      <img src="/images/Hosokawa.jpg" alt="Shugo" class="w-full h-full object-cover object-[40%_center] border-r border-gray-700" />
    </div>

  </div> </div>

---
transition:  fade-out
---

<div class="absolute inset-0 opacity-15 pointer-events-none overflow-hidden">
  <div class="absolute inset-0" style="background-image: linear-gradient(rgba(59, 130, 246, 0.1) 1px, transparent 1px), linear-gradient(90deg, rgba(59, 130, 246, 0.1) 1px, transparent 1px); background-size: 50px 50px;"></div>
  
  <div class="absolute bottom-10 right-10 font-mono text-7xl text-white opacity-5 text-right leading-none select-none">
    10110<br>01101<br>11010
  </div>
</div>

<div class="relative z-10 px-10 h-full flex flex-col justify-center items-center text-center">
  <h1 class="text-7xl font-black tracking-tighter italic leading-none text-white">
    Why <span class="text-blue-400">Quantum?</span>
  </h1>
  
  <p class="mt-4 text-lg font-light tracking-[0.3em] text-blue-200/70 uppercase">
    Understanding the Logic of Future Computation
  </p>

  <div class="mt-12 h-px w-24 bg-white/20 mx-auto"></div>

  <div class="mt-12 max-w-3xl mx-auto">
    <div class="grid grid-cols-4 gap-4 text-[10px] font-bold tracking-[0.15em] uppercase">
      <div class="space-y-3 p-4 bg-white/5 border border-white/10 rounded-lg group hover:border-blue-400/50 transition-colors">
        <span class="text-blue-400 block text-xs font-mono">01</span>
        <span class="text-white">Optimization Problems</span>
        <p class="lowercase font-normal text-gray-400 leading-tight">
		Problem Settings and its hardness</p>
      </div>
      <div class="space-y-3 p-4 bg-white/5 border border-white/10 rounded-lg group hover:border-blue-400/50 transition-colors">
        <span class="text-blue-400 block text-xs font-mono">02</span>
        <span class="text-white">Computation<br> in general</span>
        <p class="lowercase font-normal text-gray-400 leading-tight">
	    how the computer handle the problems</p>
      </div>
      <div class="space-y-3 p-4 bg-white/5 border border-white/10 rounded-lg group hover:border-blue-400/50 transition-colors">
        <span class="text-blue-400 block text-xs font-mono">03</span>
        <span class="text-white">Basics of <br>Quantum Computing</span>
        <p class="lowercase font-normal text-gray-400 leading-tight">
	    how it works and why it is fast</p>
      </div>
      <div class="space-y-3 p-4 bg-white/5 border border-white/20 border-dashed rounded-lg">
        <span class="text-gray-500 block text-xs font-mono">next lecture</span>
        <span class="text-gray-300">Quantum <br>gate & circuit</span>
        <p class="lowercase font-normal text-gray-500 leading-tight">
	    basic mechanism of the computation</p>
      </div>
    </div>
  </div>

  <div class="mt-16 flex items-center justify-center gap-6">
    <div class="text-right">
      <div class="text-[12px] text-blue-300/60 font-mono">Shugo Hosokawa</div>
    </div>
    <div class="w-px h-8 bg-white/20"></div>
    <div class="text-left text-[10px] text-gray-400 leading-relaxed uppercase tracking-widest">
      Tohoku University
    </div>
  </div>
</div>
	
---
transition:  fade-out
---

# Computers as "Problem Solvers"

<div class="text-sm font-light text-blue-100/60 italic -mt-2">
  Beyond simple math, we solve 
  <span class="px-1.5 py-0.5 rounded border border-white/20 text-white font-bold bg-white/5">Optimization Puzzles</span>
</div>

<div class="grid grid-cols-[1.6fr_1fr] gap-8 mt-6">

  <section class="space-y-3">
    <h2 class="text-[10px] text-blue-400 tracking-[0.2em] mb-2">Real-World Challenges</h2>
    <div v-for="(item, i) in [
      { title: 'Logistics', desc: 'Finding the most efficient route among millions of paths.', icon: '🚚' },
      { title: 'Scheduling', desc: 'Creating timetables without any teacher/room conflicts.', icon: '📅' },
	{ title: 'Resource Allocation', desc: 'Assigning uniform colors to football teams', icon: '⚽️' }
    ]" :key="i" 
      class="flex items-center gap-4 p-3 border rounded-lg transition-all duration-800"
      :class="[
        i === 2 && $clickCount === 1 
          ? 'fixed top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-[80%] h-[60%] z-50 bg-blue-900 border-blue-400 scale-125 shadow-[0_0_50px_rgba(59,130,246,0.5)]' 
          : 'bg-white/3 border-white/5 relative',
        i !== 2 && $clickCount === 1 ? 'opacity-0 scale-95' : 'opacity-100'
      ]"
    >
      <div class="text-xl opacity-80" :class="i === 2 && $clickCount === 1 ? 'text-4xl' : ''">{{ item.icon }}</div>
      <div>
        <h4 class="text-blue-200 font-bold text-sm" :class="i === 2 && $clickCount === 1 ? 'text-2xl' : ''">{{ item.title }}</h4>
        <p class="text-[11px] text-gray-400 leading-tight" :class="i === 2 && $clickCount === 1 ? 'text-lg mt-2' : ''">{{ item.desc }}</p>
      </div>
    </div>
  </section>

  <section class="flex flex-col gap-3">
    <div class="p-4 bg-blue-500/5 border border-blue-500/10 rounded-xl">
      <h2 class="text-[10px] font-bold text-white mb-2 opacity-50 uppercase">The Goal</h2>
      <p class="text-sm font-bold text-white leading-snug">
        Find the <span class="text-blue-400 font-black text-base italic underline decoration-blue-500/30">BEST answer</span> <br>
        among <span class="text-blue-200">countless options</span>.
      </p>
    </div>
    <div class="p-4 bg-red-500/5 border border-red-500/10 rounded-xl">
      <h2 class="text-[10px] font-bold text-red-400 mb-2 opacity-80 uppercase font-mono">Core Issue</h2>
      <p class="text-sm font-bold text-white leading-tight">
        The scale is so massive that solving it <span class="text-red-400 border-b border-red-500/50">manually</span> is humanly impossible.
      </p>
    </div>
    <div class="mt-2 text-center border border-white/5 rounded p-2 bg-white/2">
      <span class="text-[10px] font-mono uppercase tracking-widest">
	  Let's look at the football example!</span>
    </div>
  </section>

</div>

---
transition:  fade-out
---

# The Example of Optimization Problem

<div class="flex flex-col h-[80%] mt-2">
  <div class="grid grid-cols-2 gap-4 items-stretch">
    <section class="h-full">
      <div class="p-4 bg-red-500/10 border-2 border-red-500/30 rounded-2xl shadow-xl h-full flex flex-col">
        <h3 class="text-red-400 font-black text-[11px] mb-2">Football Competition</h3>
        <div class="space-y-3">
          <p class="text-[12px] text-white leading-snug">
            You are managing a football tournament.<br>
            There are <b class="text-blue-400">8 teams</b>, so you usually need 8 different colors.
          </p>
          <p class="text-[12px] text-white leading-snug">
            However, you notice that you accidentally ordered only <b class="text-red-400">4 colors</b>...
          </p>
          <div class="flex items-center gap-4 bg-black/40 p-3 rounded-xl border border-white/10 relative overflow-hidden">
            <div class="text-4xl">📦</div>
            <div class="text-[11px] font-mono text-gray-300 leading-tight">
              Inside the box:<br>
              <span class="text-red-500 text-lg">🔴🔴</span> 
              <span class="text-blue-500 text-lg">🔵🔵</span> 
              <span class="text-yellow-400 text-lg">🟡🟡</span> 
              <span class="text-green-500 text-lg">🟢🟢</span>
            </div>
            <div class="absolute top-1 right-[-25px] bg-red-600 text-white text-[8px] font-black px-8 py-0.5 rotate-45 shadow-lg">ERROR</div>
          </div>
          <p class="text-[11px] text-red-200 font-black italic text-center pt-1 border-t border-red-500/20">
            "How do you allocate the uniforms to the teams?"
          </p>
        </div>
      </div>
    </section>
    <section class="h-full">
      <div class="p-5 bg-green-500/10 border-2 border-green-500/30 rounded-2xl relative shadow-lg h-full flex flex-col justify-center">
        <h3 class="text-green-400 font-black text-[11px] mb-3 italic">
          There might be a solution!
        </h3>
        <p class="text-[13px] text-gray-100 leading-snug mb-3">
          I checked the <b class="text-white underline decoration-green-500/50 underline-offset-4">Match Schedule</b>. <br>
          Wait... not every team plays everyone else!
        </p>
        <div class="p-3 bg-black/60 rounded-xl border-l-4 border-green-500 shadow-xl mb-3">
          <div class="flex items-start gap-1">
            <p class="text-[12px] text-white font-bold leading-tight">
              "If opponents wear different colors, it works.<br>
              <span class="text-green-400">Non-opponents can share colors!</span>"
            </p>
          </div>
        </div>
        <p class="text-[11px] text-gray-300 italic leading-tight">
          Example: Team A never faces Team B, so they both can wear <span class="text-red-400">Red</span>.
        </p>
      </div>
    </section>
  </div>

  <div class="mt-4 p-3 bg-purple-500/20 border-2 border-dashed border-purple-500/40 rounded-xl text-center shadow-lg">
    <h3 class="text-[11px] font-black text-purple-200 mb-1">
      Mission: Avoid Color Conflicts
    </h3>
  </div>
</div>

---
transition:  fade-out
---

# Let's Try Out!

<script setup>
import { reactive } from 'vue'

// 0:赤, 1:青, 2:黄, 3:緑
const colors = ['#ef4444', '#3b82f6', '#facc15', '#10b981']
const teamColors = reactive(new Array(8).fill(0)) // 初期値はすべて赤(0)

const cycleColor = (i) => {
  teamColors[i] = (teamColors[i] + 1) % 4
}

// 試合の定義 (0=A, 1=B, ..., 7=H)
const matchEdges = [
  { id: 'AC', n: [0, 2] }, { id: 'AF', n: [0, 5] }, { id: 'AH', n: [0, 7] },
  { id: 'BC', n: [1, 2] }, { id: 'BD', n: [1, 3] }, { id: 'BG', n: [1, 6] },
  { id: 'BH', n: [1, 7] }, { id: 'CD', n: [2, 3] }, { id: 'DG', n: [3, 6] },
  { id: 'EH', n: [4, 7] }, { id: 'EF', n: [4, 5] }, { id: 'FG', n: [5, 6] }
]

const teamLabels = ['A', 'B', 'C', 'D', 'E', 'F', 'G', 'H']
</script>

<div class="grid grid-cols-[1.2fr_2fr] gap-10 mt-6">

  <section class="flex flex-col gap-6 py-4 border-r border-white/10 pr-6">
    <div>
      <h3 class="text-blue-400 text-[10px] font-bold uppercase tracking-widest mb-2">Goal</h3>
      <p class="text-sm font-bold leading-snug">Assign uniform colors to 8 teams (A–H)</p>
    </div>
    <div>
      <h3 class="text-red-400 text-[10px] font-bold uppercase tracking-widest mb-2">Constraint</h3>
	  <p class="text-sm leading-snug">There are only <b>4</b> different colors.</p>
      <p class="text-sm leading-snug">Opponents <b class="text-red-400">cannot</b> wear the same color.</p>
    </div>
    <div>
      <h3 class="text-gray-400 text-[10px] font-bold uppercase tracking-widest mb-2">Key Point</h3>
      <p class="text-sm italic opacity-70">Non-opponents <b>can</b> wear the same color.</p>
    </div>
  </section>

  <section class="flex flex-col gap-8">
    <div class="space-y-3">
      <h3 class="text-[10px]">Click to change 🔴→🔵→🟡→🟢</h3>
      <div class="flex justify-between">
        <div v-for="(label, i) in teamLabels" :key="label" class="flex flex-col items-center gap-2">
          <span class="text-xs font-mono font-bold">{{ label }}</span>
          <div 
    @click="cycleColor(i)"
    class="w-10 h-10 rounded border border-white/30 cursor-pointer hover:scale-110 transition-all duration-200 shadow-lg relative"
    :style="{ backgroundColor: colors[teamColors[i]] }"
  >
    <div v-if="i === 0" 
      class="absolute top-8 -right-2 text-xl pointer-events-none transform -rotate-12 animate-bounce group-hover:opacity-0 transition-opacity"
    >
      👆
    </div>
  </div>
        </div>
      </div>
    </div>
    <div class="space-y-3">
	<div class="flex items-baseline gap-2 mb-3">
  <h3 class="text-[10px] font-bold">
    Matches
  </h3>
  <span class="text-[12px] text-blue-400 font-medium italic">
    Find the allocation with 0 conflicts
  </span>
</div>
      <div class="grid grid-cols-4 gap-3">
        <div v-for="edge in matchEdges" :key="edge.id" 
             class="p-2 bg-white/5 border rounded flex flex-col items-center gap-2 transition-colors duration-300"
             :class="teamColors[edge.n[0]] === teamColors[edge.n[1]] ? 'border-red-500/50 bg-red-500/10' : 'border-white/10'">
          <div class="flex gap-1">
            <div v-for="nodeIdx in edge.n" :key="nodeIdx"
                 class="w-7 h-7 rounded flex items-center justify-center text-[10px] font-mono font-black border border-white/20 shadow-sm"
                 :style="{ backgroundColor: colors[teamColors[nodeIdx]], color: teamColors[nodeIdx] === 2 ? 'black' : 'white' }">
              {{ teamLabels[nodeIdx] }}
            </div>
          </div>
          <div class="text-[9px] font-bold uppercase tracking-tighter">
            <span v-if="teamColors[edge.n[0]] === teamColors[edge.n[1]]" class="text-red-500 font-black">CONFLICT</span>
            <span v-else class="text-green-500 opacity-50 font-mono">OK</span>
          </div>
        </div>
      </div>
    </div>

  </section>

</div>
---
transition: fade-out
---

# Why is it hard?
<div class="text-lg font-light text-white mt-2 italic opacity-80">
  This is a classic 
  <span class="px-2 py-0.5 rounded border border-red-500/50 text-red-400 font-bold bg-red-500/5">Graph Coloring Problem</span>
  <span class="ml-2 text-xs font-mono opacity-50 underline">(NP-Hard)</span>
</div>

<div class="grid grid-cols-[1.5fr_1fr] gap-10 mt-4">

  <section>
    <h2 class="text-xl font-bold text-blue-400 mb-4">Abstracting the Problem</h2>
    <ul class="space-y-3 text-white text-sm">
      <li class="flex items-center gap-2">
        <b class="w-24 text-blue-200">Nodes:</b> 
        <span>8 Teams (Soccer A–H) <span class="text-[10px] opacity-40 italic">→ Search Variables</span></span>
      </li>
      <li class="flex items-center gap-2">
        <b class="w-24 text-blue-200">Edges:</b> 
        <span>Match Schedule <span class="text-[10px] opacity-40 italic">→ Constraints (Rules)</span></span>
      </li>
      <li class="flex items-center gap-2">
        <b class="w-24 text-blue-200">Colors:</b> 
        <span>4 Uniform Colors <span class="ml-1 text-xs">🔴 🔵 🟡 🟢</span></span>
      </li>
      <li class="mt-4 p-3 bg-white/5 border-l-2 border-yellow-400 rounded-r text-[13px]">
        <b>Goal:</b> Assign colors so that 
        <span class="text-yellow-300 font-bold">adjacent nodes never share the same color.</span>
      </li>
    </ul>
  </section>

  <div class="flex justify-center items-center bg-white/5 rounded-xl p-2">
	<svg viewBox="0 0 200 200" class="w-48 h-48">
	  <!-- Edges (more complex) -->
	  <g stroke="white" stroke-width="0.6" opacity="0.35">
		<line x1="100" y1="20" x2="180" y2="100"/>
		<line x1="50" y1="40" x2="100" y2="180"/>
		<line x1="160" y1="50" x2="180" y2="100"/>
		<line x1="160" y1="50" x2="150" y2="160"/>
		<line x1="180" y1="100" x2="150" y2="160"/>
		<line x1="100" y1="180" x2="50" y2="160"/>
		<line x1="50" y1="160" x2="20" y2="100"/>
		<line x1="50" y1="40" x2="160" y2="50"/>
		<line x1="50" y1="40" x2="100" y2="20"/>
		<line x1="150" y1="160" x2="20" y2="100"/>
		<line x1="160" y1="50" x2="20" y2="100"/>
		<line x1="100" y1="20" x2="50" y2="160"/>
	  </g>
	  <!-- Nodes with colors -->
	  <g stroke="white" stroke-width="1.2">
		<circle cx="100" cy="20" r="9" fill="#ef4444"/>   <!-- A red -->
		<circle cx="160" cy="50" r="9" fill="#3b82f6"/>  <!-- B blue -->
		<circle cx="180" cy="100" r="9" fill="#10b981"/> <!-- C green -->
		<circle cx="150" cy="160" r="9" fill="#facc15"/> <!-- D yellow -->
		<circle cx="100" cy="180" r="9" fill="#ef4444"/> <!-- E red -->
		<circle cx="50" cy="160" r="9" fill="#3b82f6"/>  <!-- F blue -->
		<circle cx="20" cy="100" r="9" fill="#10b981"/>  <!-- H green -->
		<circle cx="50" cy="40" r="9" fill="#facc15"/>   <!-- G yellow -->
	  </g>
	  <!-- Labels (smaller text) -->
	  <g fill="black" font-size="4" font-family="sans-serif" text-anchor="middle">
		<text x="100" y="26">A</text>
		<text x="160" y="56">B</text>
		<text x="180" y="106">C</text>
		<text x="150" y="166">D</text>
		<text x="100" y="186">E</text>
		<text x="50" y="166">F</text>
		<text x="20" y="106">H</text>
		<text x="50" y="46">G</text>
	  </g>
	</svg>
  </div>
</div>

<div class="grid grid-cols-2 gap-10 pt-6 mt-4 font-bold border-t border-white/10">
  <section>
    <h2 class="text-xs text-red-400 mb-3  font-mono">Sequential Strategy</h2>
    <ul class="text-[13px] text-gray-300 space-y-2">
      <li class="flex items-start gap-2"><span>1.</span> Pick a node and assign 1 of 4 colors.</li>
      <li class="flex items-start gap-2"><span>2.</span> Move to next node and repeat (Trial & Error).</li>
      <li class="flex items-start gap-2"><span>3.</span> <b>Backtrack</b> if a conflict is found.</li>
    </ul>
  </section>

  <section>
    <h2 class="text-[10px] font-bold text-yellow-400 mb-1.5 font-mono">
      Total Search Space
    </h2>
    <div class="flex flex-col">
      <p class="text-[12px] text-gray-400 leading-none">
        For 8 nodes: <span class="text-white font-mono font-bold">4⁸ = 65,536</span> options.
      </p>
      <p class="text-xl font-black text-yellow-200 italic leading-[0.9] mt-1 tracking-tighter">
        Searching for 1 needle in 65,536 haystacks.
      </p>
    </div>
  </section>
</div>

---
transition: fade-out
---

# How does a computer "calculate"?
<div class="text-lg font-light text-blue-100/60 mt-2 italic">
  To solve the puzzle, we must translate it into the language of machines.
</div>

<div class="mt-10 grid grid-cols-2 gap-12">

  <section>
    <h2 class="text-xl font-bold text-blue-400 mb-4">
	The Language: Bits</h2>
    <div class="space-y-4">
      <p class="text-sm text-white leading-snug">
        Computers don't see "red" or "football". <br>
        They process only <span class="text-blue-400 font-bold">Binary States</span>:
      </p>
      <div class="flex gap-6 justify-center py-6 bg-white/3 border border-white/10 rounded-2xl shadow-inner">
        <div class="flex flex-col items-center">
          <div class="text-5xl font-black text-gray-600 font-mono tracking-tighter">0</div>
          <div class="mt-1 px-2 py-0.5 rounded bg-gray-500/10 text-[9px] uppercase opacity-50 font-bold">Off / Low</div>
        </div>
        <div class="w-px h-12 bg-white/10 my-auto"></div>
        <div class="flex flex-col items-center">
          <div class="text-5xl font-black text-blue-400 font-mono tracking-tighter shadow-blue-400/20 drop-shadow-sm">1</div>
          <div class="mt-1 px-2 py-0.5 rounded bg-blue-400/10 text-[9px] uppercase text-blue-400 font-bold">On / High</div>
        </div>
      </div>
      <p class="text-[11px] italic text-gray-500 text-center">
        This is a <b>"Bit"</b>—the smallest unit of information.
      </p>
    </div>
  </section>

  <section>
    <h2 class="text-xl font-bold text-green-400 mb-4">
	Calculation Flow</h2>
    <div class="relative space-y-8 pl-6 border-l border-white/10 ml-2">
      <div class="relative group">
        <div class="absolute -left-[30px] top-1 w-3 h-3 rounded-full bg-green-500 ring-4 ring-green-500/20"></div>
        <h3 class="font-bold text-white text-sm tracking-wide">1. Encoding</h3>
        <p class="text-[11px] text-gray-400 leading-tight mt-1">
          Map the puzzle (Teams, Colors, Constraints) into long strings of bits.
        </p>
      </div>
      <div class="relative group">
        <div class="absolute -left-[30px] top-1 w-3 h-3 rounded-full bg-blue-500 ring-4 ring-blue-500/20"></div>
        <h3 class="font-bold text-white text-sm tracking-wide">2. Computation</h3>
        <p class="text-[11px] text-gray-400 leading-tight mt-1">
          Perform logic operations to find a bit string that satisfies all rules.
        </p>
      </div>
      <div class="relative group">
        <div class="absolute -left-[30px] top-1 w-3 h-3 rounded-full bg-purple-500 ring-4 ring-purple-500/20"></div>
        <h3 class="font-bold text-white text-sm tracking-wide">3. Decoding</h3>
        <p class="text-[11px] text-gray-400 leading-tight mt-1">
          Translate the final bits back into the real-world answer (Red, Blue...).
        </p>
      </div>
    </div>
  </section>

</div>

---
transition: fade-out
---
	
# Encoding: Mapping to Bitstrings
<div class="text-sm font-light text-blue-100/60 -mt-2 italic">Translating teams and colors into a single searchable sequence</div>

<div class="grid grid-cols-[1fr_1.2fr] gap-8 mt-6">

  <section class="space-y-4">
    <h2 class="text-[10px] font-bold text-blue-400">
	Mapping 1:<br> Color as Bits</h2>
    <div class="p-4 bg-white/3 border border-white/10 rounded-xl grid grid-cols-2 gap-y-3 text-xs font-mono">
      <div class="flex items-center gap-2">🔴 <span class="opacity-50 text-[10px]">Red</span> <b class="text-blue-400">00</b></div>
      <div class="flex items-center gap-2">🔵 <span class="opacity-50 text-[10px]">Blue</span> <b class="text-blue-400">01</b></div>
      <div class="flex items-center gap-2">🟡 <span class="opacity-50 text-[10px]">Yellow</span> <b class="text-blue-400">10</b></div>
      <div class="flex items-center gap-2">🟢 <span class="opacity-50 text-[10px]">Green</span> <b class="text-blue-400">11</b></div>
    </div>
    <div class="mt-4">
      <div class="bg-blue-500/5 border border-blue-500/20 p-3 rounded-lg flex flex-col items-center">
         <div class="flex gap-1.5 mb-1.5 opacity-40">
           <span v-for="t in ['A','B','C','D','E','F','G','H']" class="text-[9px] font-bold w-4 text-center">{{t}}</span>
         </div>
         <div class="font-mono text-xs tracking-widest text-white bg-black/40 px-3 py-1.5 rounded border border-white/5">
           00 00 01 10 00 11 01 10
         </div>
      </div>
    </div>
  </section>

  <section class="space-y-4">
    <h2 class="text-[10px] font-bold text-green-400">
	Mapping 2:<br> The Logic "Black Box"</h2>
    <p class="text-[11px] text-gray-400 leading-snug">The computer runs a program to check all constraints at once.</p>
    <div class="flex flex-col gap-2 mt-4">
      <div v-for="res in [
        { seq: '00000110...', val: 0, color: 'text-red-500', bg: 'bg-red-500/5', border: 'border-red-500/20' },
        { seq: '11010010...', val: 0, color: 'text-red-500', bg: 'bg-red-500/5', border: 'border-red-500/20' },
        { seq: '00011000...', val: 1, color: 'text-green-400', bg: 'bg-green-500/10', border: 'border-green-500/30' }
      ]" class="flex items-center justify-between p-2 rounded border font-mono text-[10px]" :class="[res.bg, res.border]">
        <span class="opacity-50 tracking-tighter">{{res.seq}}</span>
        <span class="i-carbon-arrow-right opacity-30"></span>
        <span class="font-bold text-[11px] text-right" :class="res.color">Output: {{res.val}}</span>
      </div>
    </div>
  </section>
</div>

<div class="mt-8 p-2.5 border-l-4 border-purple-500 bg-purple-500/5 rounded-r-xl relative overflow-hidden">
  
  <div class="flex items-baseline gap-3">
    <p class="text-[9px] font-bold text-purple-400 uppercase tracking-[0.2em] font-mono whitespace-nowrap">The Mission</p>
    <p class="text-[13px] leading-none text-white/90">
      Find a <b class="text-white underline decoration-purple-500/40 underline-offset-2">
	  16-bit sequence</b> that outputs <b class="text-green-400 font-black italic text-base">1</b>
    </p>
  </div>
</div>

---
transition: fade-out
---

# Whole Calculation Process!

<script setup>
import { reactive, computed, ref } from 'vue'

// 1. 16ビットデータ (8チーム × 2ビット)
const bits = reactive(new Array(16).fill(0))
const getBitIndex = (col, row) => col + row * 8

const toggleBit = (col, row) => {
  const index = getBitIndex(col, row)
  bits[index] = bits[index] === 0 ? 1 : 0
}

// 2. エッジ（制約）の定義
const edgeDefinitions = [
  { id: 'AC', n: [0, 2] }, { id: 'AF', n: [0, 5] }, { id: 'AH', n: [0, 7] },
  { id: 'BC', n: [1, 2] }, { id: 'BD', n: [1, 3] }, { id: 'BG', n: [1, 6] },
  { id: 'BH', n: [1, 7] }, { id: 'CD', n: [2, 3] }, { id: 'DG', n: [3, 6] },
  { id: 'EH', n: [4, 7] }, { id: 'EF', n: [4, 5] }, { id: 'FG', n: [5, 6] }
]

const selectedEdgeId = ref('AC')

// 3. 色の計算ロジック
const getColor = (teamIdx) => {
  const b1 = bits[getBitIndex(teamIdx, 0)]
  const b2 = bits[getBitIndex(teamIdx, 1)]
  const code = `${b1}${b2}`
  if (code === '00') return '#ef4444' // Red
  if (code === '01') return '#3b82f6' // Blue
  if (code === '10') return '#facc15' // Yellow
  return '#10b981' // Green
}

// 全ノードの状態
const nodes = computed(() => {
  const labels = ['A', 'B', 'C', 'D', 'E', 'F', 'G', 'H']
  const coords = [{x:100,y:20},{x:160,y:50},{x:180,y:100},{x:150,y:160},{x:100,y:180},{x:50,y:160},{x:20,y:100},{x:50,y:40}]
  return labels.map((id, i) => ({ id, ...coords[i], color: getColor(i) }))
})

// 各エッジの判定結果 (1=OK, 0=Conflict)
const edgeResults = computed(() => {
  return edgeDefinitions.map(e => (getColor(e.n[0]) !== getColor(e.n[1]) ? 1 : 0))
})

// 全体のバリデーション
const isValid = computed(() => edgeResults.value.every(r => r === 1))

// 現在選択中のエッジの判定
const currentResult = computed(() => {
  const idx = edgeDefinitions.findIndex(e => e.id === selectedEdgeId.value)
  return edgeResults.value[idx]
})

const isUnderlined = (teamIdx) => {
  const edge = edgeDefinitions.find(e => e.id === selectedEdgeId.value)
  return edge.n.includes(teamIdx)
}
</script>

<div class="grid grid-cols-[1fr_1.4fr] gap-8 mt-2">

  <section class="space-y-4">
    <h3 class="text-sm font-bold text-blue-400 uppercase tracking-widest">1. Pick a sequence</h3>
    <div class="bg-white/5 border border-white/10 rounded-2xl p-4 flex flex-col items-center">
      <svg viewBox="0 0 200 200" class="w-56 h-53">
        <g stroke="white" stroke-width="0.8" opacity="0.2">
          <line v-for="e in edgeDefinitions" :x1="nodes[e.n[0]].x" :y1="nodes[e.n[0]].y" :x2="nodes[e.n[1]].x" :y2="nodes[e.n[1]].y" />
        </g>
        <g stroke="white" stroke-width="1.2">
          <circle v-for="node in nodes" :key="node.id" :cx="node.x" :cy="node.y" r="8" :fill="node.color" class="transition-all duration-300" />
        </g>
        <g fill="black" font-size="4" font-family="sans-serif" text-anchor="middle">
          <text v-for="node in nodes" :key="node.id" :x="node.x" :y="node.y + 6">{{node.id}}</text>
        </g>
      </svg>
      <div class="w-full mt-2 px-2">
        <div class="grid grid-rows-2 gap-1">
          <div v-for="r in [0, 1]" :key="r" class="grid grid-cols-8 gap-1">
            <div v-for="c in 8" :key="c" @click="toggleBit(c-1, r)"
                 class="h-7 flex items-center justify-center rounded text-[10px] font-mono cursor-pointer border transition-all"
                 :class="bits[getBitIndex(c-1, r)] === 1 ? 'bg-blue-500 border-blue-400 text-white' : 'bg-white/10 border-white/20 text-gray-400'">
              {{ bits[getBitIndex(c-1, r)] }}
			  <div v-if="c === 8 && r === 1" 
      class="absolute bottom-30 left-25 text-lg pointer-events-none transform -rotate-12 animate-bounce group-hover:opacity-0 transition-opacity"
    >
      👆
    </div>
            </div>
          </div>
        </div>
        <div class="flex justify-between mt-2 px-1 opacity-50">
          <span v-for="label in ['A','B','C','D','E','F','G','H']" :key="label" class="text-[9px] font-bold w-full text-center">{{label}}</span>
        </div>
      </div>
	  <div class="mt-2 w-full border-t border-white/10 pt-4 px-2 text-center">
        <div class="bg-black/20 py-2 rounded font-mono text-xs tracking-[0.2em] text-blue-300">
          <span v-for="(b, i) in bits" :key="i" :class="b === 1 ? 'text-blue-400 font-bold' : 'opacity-40'">{{b}}</span>
        </div>
      </div>
    </div>
  </section>

  <section class="flex flex-col space-y-4">
    <div>
      <h3 class="text-sm font-bold text-green-400 uppercase tracking-widest mb-2">2. Check Edges</h3>
      <div class="p-3 bg-white/5 border border-white/10 rounded-xl">
        <div class="grid grid-cols-6 gap-1.5 mb-4">
          <button v-for="(e, idx) in edgeDefinitions" :key="e.id" @click="selectedEdgeId = e.id"
                  class="py-1 border rounded text-[9px] font-mono transition-all"
                  :class="selectedEdgeId === e.id ? 'bg-green-500 border-green-400 text-black font-bold' : (edgeResults[idx] === 1 ? 'bg-green-900/20 border-green-900/50 text-green-400' : 'bg-white/5 border-white/10 text-gray-400')">
            {{e.id}}
			<div v-if="idx === edgeDefinitions.length - 1" 
    class="absolute top-42 right-115 text-base pointer-events-none transform -rotate-12 animate-bounce group-hover:opacity-0 transition-opacity"
  >
    👆</div>
          </button>
        </div>
        <div class="bg-black/40 p-3 rounded-lg border transition-all" :class="currentResult === 1 ? 'border-green-500/30' : 'border-red-500/30'">
          <div class="flex flex-col items-center">
            <div class="font-mono text-sm tracking-[0.3em] text-white mb-2 flex gap-1">
              <span v-for="t in 8" :key="t" :class="isUnderlined(t-1) ? 'underline decoration-white decoration-2 underline-offset-4 font-bold' : 'opacity-20'">
                {{bits[getBitIndex(t-1, 0)]}}{{bits[getBitIndex(t-1, 1)]}}
              </span>
            </div>
            <div class="flex items-center gap-4 py-1">
              <span class="text-xl font-black font-mono" :class="currentResult === 1 ? 'text-green-400' : 'text-red-500'">
                RESULT: {{currentResult}}
              </span>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="flex-grow">
      <h3 class="text-sm font-bold text-yellow-400 uppercase tracking-widest mb-2">3. Global Status</h3>
      <div class="p-3 bg-white/5 border border-white/10 rounded-xl">
        <div class="grid grid-cols-6 gap-1.5 mb-4">
          <div v-for="(res, idx) in edgeResults" :key="idx" 
               class="py-1 flex items-center justify-center rounded border font-mono text-[9px] transition-all"
               :class="res === 1 ? 'bg-green-500/20 border-green-500/50 text-green-400' : 'bg-red-500/20 border-red-500/50 text-red-400'">
            {{res}}
          </div>
        </div>
        <div class="h-16 flex items-center justify-center rounded-lg transition-all" :class="isValid ? 'bg-green-500/20 border border-green-500' : 'bg-red-500/10 border border-red-500/40'">
          <h3 class="text-2xl font-black italic tracking-widest font-mono" :class="isValid ? 'text-green-400 animate-pulse' : 'text-red-500'">
            {{ isValid ? 'VALID' : 'INVALID' }}
          </h3>
        </div>
      </div>
    </div>
  </section>
</div>

---
transition: fade-out
---

# Physical Limitations
<div class="text-lg font-light -mt-2 italic">
  Computers are fast, but they hit a wall when faced with exponential growth.
</div>

<div class="mt-8 grid grid-cols-[1fr_2fr] gap-8 items-center">
  
  <section class="flex flex-col items-center justify-center p-6 bg-red-500/5 border border-red-500/20 rounded-2xl relative overflow-hidden">
    <h3 class="text-[10px] font-bold text-red-400 uppercase tracking-widest mb-4">Complexity</h3>
    <div class="text-7xl font-mono font-black text-white tracking-tighter flex items-start">
      4<span class="text-4xl text-red-500 -mt-2">N</span>
    </div>
    <p class="text-[10px] text-gray-500 mt-4 font-mono uppercase tracking-widest">Exponential Explosion</p>
  </section>

  <section class="flex flex-col gap-2">
    <div class="px-3 py-2 bg-white/3 border-l-2 border-blue-400 rounded-r shadow-sm">
      <div class="flex justify-between items-baseline">
        <h3 class="text-blue-400 font-bold uppercase tracking-widest text-[9px]">N = 8 (Teams)</h3>
        <span class="text-[9px] font-mono opacity-30 tracking-tighter">4⁸ = 65,536</span>
      </div>
      <p class="text-[12px] text-white font-bold leading-none mt-1">Solvable in milliseconds.</p>
    </div>
    <div class="px-3 py-2 bg-red-900/10 border-l-2 border-red-500 rounded-r relative overflow-hidden">
      <div class="flex justify-between items-baseline relative z-10">
        <h3 class="text-red-500 font-bold uppercase tracking-widest text-[9px]">N = 100 (Teams)</h3>
        <span class="text-[9px] font-mono opacity-30 text-red-400 tracking-tighter">4¹⁰⁰ ≈ 1.6×10⁶⁰</span>
      </div>
      <div class="mt-1 flex items-baseline gap-2 relative z-10">
        <p class="text-[12px] text-white font-bold leading-none">
		Billions of years to finish</p>
      </div>
    </div>
  </section>
</div>



<div class="mt-8 p-4 bg-blue-500/5 border border-blue-500/20 rounded-xl flex items-center justify-center gap-4 group">
  <div class="w-10 h-10 rounded-full bg-blue-500/20 flex items-center justify-center text-blue-400 group-hover:scale-110 transition-transform">
    <span class="i-carbon-idea text-xl"></span>
  </div>
  <p class="text-blue-100 font-bold italic text-base tracking-tight">
    How can we solve this <span class="text-blue-400 underline decoration-blue-500/30">without</span> checking them one by one?
  </p>
</div>

---
transition: fade-out
---

# Classical Bit vs. Quantum Bit

<div class="grid grid-cols-2 gap-10 mt-12">

  <section class="flex flex-col items-center">
    <h2 class="text-sm font-bold text-red-400 mb-8 uppercase font-mono">
	Classical Bit</h2>
    <div class="flex gap-6 justify-center items-center h-28 relative">
      <div class="flex flex-col items-center gap-2">
        <div class="w-14 h-14 rounded-xl bg-gray-800 border-2 border-gray-600 shadow-inner flex items-center justify-center">
          <span class="font-mono text-xl text-gray-400">0</span>
        </div>
      </div>
      <div class="text-[10px] text-gray-600 font-bold uppercase tracking-widest">or</div>
      <div class="flex flex-col items-center gap-2">
        <div class="w-14 h-14 rounded-xl bg-white border-2 border-gray-300 flex items-center justify-center">
          <span class="font-mono text-xl text-black">1</span>
        </div>
      </div>
    </div>
    <div class="mt-8 w-full max-w-[240px]">
      <div class="text-[11px] text-gray-400 text-center mb-2 italic">A fixed state, like a switch.</div>
      <p class="py-2 bg-red-500/5 border border-red-500/20 rounded text-center text-xs text-red-200">
        Can only handle <b>0 or 1</b> at a time.
      </p>
    </div>
  </section>

  <section class="flex flex-col items-center border-l border-white/5 pl-10">
    <h2 class="text-sm font-bold text-blue-400 mb-8 uppercase font-mono">Quantum Bit (Qubit)</h2>
    <div class="flex flex-col items-center">
      <div class="relative w-32 h-32 flex items-center justify-center">
        <div class="absolute inset-0 rounded-full border-2 border-dashed border-blue-400/20 animate-spin-slow"></div>
        <div class="relative w-16 h-16 rounded-full bg-blue-600 shadow-[0_0_40px_rgba(59,130,246,0.6)] flex items-center justify-center border border-blue-400/50">
          <div class="text-white font-black text-2xl italic tracking-tighter">?</div>
        </div>
        <div class="absolute top-0 left-0 bg-white/5 px-2 py-1 rounded border border-white/10 backdrop-blur-sm">
          <div class="text-[8px] text-blue-300 uppercase font-bold leading-none mb-1 opacity-60">Chance</div>
          <div class="text-sm font-mono text-white leading-none">20% <span class="text-blue-400 font-black ml-1 text-base">0</span></div>
        </div>
        <div class="absolute bottom-0 right-0 bg-white/5 px-2 py-1 rounded border border-white/10 backdrop-blur-sm text-right">
          <div class="text-[8px] text-blue-300 uppercase font-bold leading-none mb-1 opacity-60">Chance</div>
          <div class="text-sm font-mono text-white leading-none"><span class="text-blue-400 font-black mr-1 text-base">1</span> 80%</div>
        </div>
      </div>
    </div>
	<div class="mt-8 w-full max-w-[240px]">
      <p class="py-2 bg-blue-500/10 border border-blue-500/30 rounded text-center text-xs text-blue-200">
        Holds <b>both 0 and 1</b> simultaneously!
      </p>
    </div>
    </section>

</div>



<div class="absolute bottom-10 left-10 right-10 text-center">
  <p class="text-[10px] border-t border-white/10 pt-4">
    Next: But what does it mean that the bit is 50% 0?
  </p>
</div>

---
transition: fade-out
---

# Probability & Measurement

<div class="p-4 bg-blue-500/5 border border-blue-500/20 rounded-2xl mb-4">
  <h2 class="text-[11px] font-black text-blue-400 uppercase mb-2">
  1. Measurement 
  <span class="ml-4 text-[15px] text-blue-300/60 lowercase italic font-light">
  -- Projecting the Superposition into a Definite State</span>
  </h2>
  
  <div class="flex items-center justify-around px-10">
    <div class="flex flex-col items-center gap-1">
  <div class="relative w-20 h-20 flex items-center justify-center">
    <div class="absolute inset-0 rounded-full border-2 border-dashed border-blue-400/40 animate-spin-slow"></div>
    <div class="relative w-10 h-10 rounded-full bg-blue-600 shadow-[0_0_20px_rgba(59,130,246,0.5)] flex items-center justify-center border border-blue-400/50 z-10">
      <div class="text-white font-black text-lg italic tracking-tighter">?</div>
    </div>
    <div class="absolute -top-1 -left-4 bg-white/5 px-1.5 py-0.5 rounded border border-white/10 backdrop-blur-sm z-20 scale-140">
      <div class="text-[6px] text-blue-300 uppercase font-bold leading-none mb-0.5 opacity-60 text-center">Chance</div>
      <div class="text-[9px] font-mono text-white leading-none">20% <span class="text-blue-400 font-black ml-0.5">0</span></div>
    </div>
    <div class="absolute -bottom-1 -right-4 bg-white/5 px-1.5 py-0.5 rounded border border-white/10 backdrop-blur-sm z-20 scale-140">
      <div class="text-[6px] text-blue-300 uppercase font-bold leading-none mb-0.5 opacity-60 text-center">Chance</div>
      <div class="text-[9px] font-mono text-white leading-none"><span class="text-blue-400 font-black mr-0.5">1</span> 80%</div>
    </div>
  </div>
  <span class="text-[9px] font-mono text-blue-300 mt-1">Superposition</span>
</div>
    <div class="text-2xl text-white/20">➔</div>
    <div class="px-6 py-2 border-2 border-white/30 bg-white/5 rounded-xl flex items-center gap-3 shadow-lg">
      <span class="text-3xl">🔍</span>
      <span class="text-[10px] font-black uppercase tracking-widest">Measure</span>
    </div>
    <div class="text-2xl text-white/20">➔</div>
    <div class="flex flex-col items-center gap-1">
      <div class="w-16 h-16 border-4 border-green-500 rounded-2xl flex items-center justify-center bg-green-500/20 shadow-[0_0_20px_rgba(34,197,94,0.3)]">
        <span class="text-3xl font-mono font-black text-white">1</span>
      </div>
      <span class="text-[10px] font-black text-green-400 uppercase tracking-tighter">Certainty</span>
    </div>
  </div>
</div>

<div class="p-5 bg-purple-500/5 border border-purple-500/20 rounded-2xl relative overflow-hidden">
  <h2 class="text-[11px] font-black text-purple-400 uppercase mb-2">
  2. Probability</h2>
  
  <div class="flex items-center justify-between gap-4 px-4 h-36">
  <div class="flex flex-col items-center justify-between h-full py-1">
    <span class="text-[10px] font-bold text-gray-400 uppercase tracking-tighter">
	Prepare 100 Qubits</span>
    <div class="grid grid-cols-5 gap-1 p-2 bg-white/5 rounded-lg border border-white/10 shadow-inner w-[110px] h-[110px]">
      <div v-for="i in 25" :key="i" class="w-4 h-4 rounded-full border-2 border-blue-400/30 bg-blue-400/20 flex items-center justify-center">
        <div class="w-2 h-2 animate-pulse bg-blue-400/20 rounded-full"></div>
      </div>
    </div>
    <span class="text-[9px] font-mono text-blue-300">All: 20% 0 / 80% 1</span>
  </div>

  <div class="text-2xl text-purple-400/30 self-center">➔</div>

  <div class="flex flex-col items-center justify-between h-full py-1">
    <span class="text-[10px] font-bold text-purple-400 text-center">
    Measure each Qubits</span>
    <div class="grid grid-cols-5 gap-1 p-2 bg-purple-500/10 border-2 border-purple-500/30 rounded-lg shadow-lg w-[110px] h-[110px]">
      <div v-for="i in 25" :key="i" class="w-4 h-4 flex items-center justify-center text-[10px] leading-none opacity-80">
        🔍
      </div>
    </div>
    <div class="h-[10px]"></div> </div>

  <div class="text-2xl text-purple-400/30 self-center">➔</div>

  <div class="flex flex-col items-center justify-between h-full py-1">
    <span class="text-[10px] font-bold text-gray-400 uppercase tracking-tighter">Statistical Result</span>
    <div class="grid grid-cols-5 gap-1 p-2 bg-black/50 rounded-lg border border-white/20 shadow-2xl w-[110px] h-[110px]">
      <div v-for="i in 25" :key="i" 
           class="w-4 h-4 rounded-md flex items-center justify-center font-mono text-[11px] font-black border-2 transition-all duration-1000 leading-none"
           :class="i <= 5 ? 'bg-blue-600 border-blue-400 text-white shadow-[0_0_10px_rgba(59,130,246,0.6)]' : 'bg-gray-800 border-gray-600 text-gray-500'">
        {{ i <= 5 ? '0' : '1' }}
      </div>
    </div>
    <div class="gap-4">
      <div class="flex items-center gap-1.5"><div class="w-2 h-2 bg-blue-500 rounded-sm"></div><span class="text-[9px] font-bold">~20% (0)</span></div>
      <div class="flex items-center gap-1.5"><div class="w-2 h-2 bg-gray-600 rounded-sm"></div><span class="text-[9px] font-bold">~80% (1)</span></div>
    </div>
  </div>
</div>
</div>

---
transition: fade-out
---

# Calculation flow in Quantum Computer

<div class="flex flex-col items-center justify-center h-full -mt-4">
  <div class="flex items-center justify-between w-full px-4 gap-2 h-40">
    <div class="flex flex-col items-center justify-center h-full gap-4">
      <span class="text-[10px] font-bold uppercase tracking-widest">Input</span>
      <div class="relative w-28 h-28 flex items-center justify-center">
        <div class="absolute inset-0 rounded-full border-2 border-dashed border-blue-400/40 animate-spin"></div>
        <div class="relative w-12 h-12 rounded-full bg-blue-600 shadow-[0_0_40px_rgba(59,130,246,0.6)] flex items-center justify-center border border-blue-400/50">
          <div class="text-white font-black text-xl italic tracking-tighter">?</div>
        </div>
        <div class="absolute -top-1 -left-2 bg-white/5 px-2 py-1 rounded border border-white/10 backdrop-blur-sm">
          <div class="text-[7px] text-blue-300 uppercase font-bold leading-none mb-0.5 opacity-60">Chance</div>
          <div class="text-xs font-mono text-white leading-none">50% <span class="text-blue-400 font-black">0</span></div>
        </div>
        <div class="absolute -bottom-1 -right-2 bg-white/5 px-2 py-1 rounded border border-white/10 backdrop-blur-sm text-right">
          <div class="text-[7px] text-blue-300 uppercase font-bold leading-none mb-0.5 opacity-60">Chance</div>
          <div class="text-xs font-mono text-white leading-none"><span class="text-blue-400 font-black">1</span> 50%</div>
        </div>
      </div>
      <p class="text-[9px] text-blue-300 font-mono italic">Superposed</p>
    </div>
    <div class="text-xl text-white/20">➔</div>
    <div class="flex flex-col items-center justify-center h-full gap-4">
      <div class="px-6 py-10 border-2 border-blue-400 bg-blue-400/5 rounded-2xl flex flex-col items-center justify-center relative shadow-2xl">
        <div class="text-center leading-tight">
  <div class="text-[20px] text-blue-100 font-bold  mb-1">
    Calculation!
  </div>
  <div class="text-[13px] font-mono text-blue-200 italic leading-snug">
    Manipulating<br>Probabilities...
  </div>
</div>
      </div>
    </div>
    <div class="text-xl text-white/20">➔</div>
    <div class="flex flex-col items-center justify-center h-full gap-4">
      <span class="text-[10px] font-bold uppercase tracking-widest">Output</span>
      <div class="relative w-28 h-28 flex items-center justify-center">
        <div class="absolute inset-0 rounded-full border-2 border-dashed border-green-400/40 animate-spin"></div>
        <div class="relative w-12 h-12 rounded-full bg-green-600 shadow-[0_0_40px_rgba(34,197,94,0.6)] flex items-center justify-center border border-green-400/50">
          <div class="text-white font-black text-xl italic tracking-tighter">!</div>
        </div>
        <div class="absolute -top-1 -left-2 bg-white/5 px-2 py-1 rounded border border-white/10 backdrop-blur-sm opacity-40">
          <div class="text-[7px] text-green-300 uppercase font-bold leading-none mb-0.5 opacity-60">Chance</div>
          <div class="text-xs font-mono text-white leading-none">1% <span class="text-green-400 font-black">0</span></div>
        </div>
        <div class="absolute -bottom-1 -right-2 bg-white/5 px-2 py-1 rounded border border-white/10 backdrop-blur-sm text-right ring-2 ring-green-400">
          <div class="text-[7px] text-green-300 uppercase font-bold leading-none mb-0.5 opacity-60">Chance</div>
          <div class="text-xs font-mono text-white leading-none"><span class="text-green-400 font-black">1</span> 99%</div>
        </div>
      </div>
      <p class="text-[9px] text-green-300 font-mono italic">Highly Biased</p>
    </div>
    <div class="text-xl text-white/20">➔</div>
    <div class="flex flex-col items-center gap-4 justify-center h-full">
      <div class="p-4 bg-purple-600 rounded-xl shadow-lg flex flex-col items-center gap-1">
        <span class="text-2xl">🔍</span>
        <span class="text-[15px] text-white">Measure</span>
      </div>
    </div>
    <div class="text-xl text-white/20">➔</div>
    <div class="flex flex-col items-center gap-4 justify-center h-full">
      <div class="w-16 h-16 border-4 border-green-500 bg-green-500/20 rounded-2xl flex items-center justify-center font-mono text-3xl font-black text-white shadow-[0_0_20px_rgba(34,197,94,0.4)]">
        1
      </div>
      <span class="text-[9px] font-black text-green-400 uppercase tracking-tighter">Certainty</span>
    </div>
  </div>
  <div class="mt-12 p-3 bg-white/5 border border-white/10 rounded-lg w-full max-w-2xl text-center">
    <h4 class="text-xs leading-relaxed text-gray-300 italic">
  Quantum calculation doesn't just "calculate" numbers; <br>
  it <b class="text-blue-400 font-bold">redistributes probabilities</b>.<br>
  Through the calculation, we <b class="text-green-400 font-black">boost the chance</b> 
  of getting the right answer before we measure it!
</h4>
  </div>
</div>

---
transition: fade-out
---

# Quantum Calculation with Multi-bit

<div class="grid grid-cols-3 gap-4 h-full pb-20">

  <section class="flex flex-col items-center bg-white/3 rounded-xl p-4 border border-white/5 shadow-xl">
    <h3 class="text-[10px] font-black text-blue-400 mb-4 uppercase tracking-widest font-mono text-center">1 Qubit</h3>
    <div class="mb-4 relative w-8 h-8 rounded-full bg-blue-600 shadow-[0_0_15px_rgba(59,130,246,0.6)] border border-blue-400/50 flex items-center justify-center">
      <span class="text-[8px] italic font-black text-white">0/1</span>
    </div>
    <div class="flex flex-col items-center gap-1.5">
      <span class="text-[10px] font-bold">Initial (2 States)</span>
      <div class="flex gap-1">
        <div v-for="p in ['50%', '50%']" :key="p" class="w-10 h-10 border border-blue-400/30 bg-blue-400/5 rounded flex items-center justify-center text-[9px] font-mono">{{ p }}</div>
      </div>
    </div>
    <div class="my-3 text-blue-400/30 text-lg">↓</div>
    <div class="w-full py-2 border border-blue-400/50 bg-blue-400/10 rounded-lg text-center text-[9px] font-bold uppercase">Calculation</div>
    <div class="my-3 text-blue-400/30 text-lg">↓</div>
    <div class="flex flex-col items-center gap-1.5">
      <div class="flex gap-1">
        <div class="w-10 h-10 border border-white/10 bg-white/5 rounded flex items-center justify-center text-[9px] font-mono opacity-30">1%</div>
        <div class="w-10 h-10 border-2 border-green-500 bg-green-500/20 rounded flex items-center justify-center text-[9px] font-mono font-bold shadow-[0_0_10px_rgba(34,197,94,0.4)]">99%</div>
      </div>
      <span class="text-[10px] font-bold">Result: 1</span>
    </div>
  </section>

  <section class="flex flex-col items-center bg-white/5 rounded-xl p-4 border border-white/10 shadow-2xl">
    <h3 class="text-[10px] font-black text-purple-400 mb-4 uppercase tracking-widest font-mono text-center">2 Qubits</h3>
    <div class="mb-4 flex gap-2">
      <div v-for="i in 2" :key="i" class="w-8 h-8 rounded-full bg-purple-600 shadow-[0_0_15px_rgba(168,85,247,0.6)] border border-purple-400/50 flex items-center justify-center">
        <span class="text-[8px] italic font-black text-white">0/1</span>
      </div>
    </div>
    <div class="flex flex-col items-center gap-1.5">
      <span class="text-[10px] font-bold">Initial (4 States)</span>
      <div class="grid grid-cols-4 gap-0.5">
        <div v-for="i in 4" :key="i" class="w-7 h-10 border border-purple-400/30 bg-purple-400/5 rounded flex items-center justify-center text-[8px] font-mono">25%</div>
      </div>
    </div>
    <div class="my-3 text-purple-400/30 text-lg">↓</div>
    <div class="w-full py-2 border border-purple-500/50 bg-purple-400/10 rounded-lg text-center text-[9px] font-bold uppercase tracking-tighter">Calculation</div>
    <div class="my-3 text-purple-400/30 text-lg">↓</div>
    <div class="flex flex-col items-center gap-1.5">
      <div class="grid grid-cols-4 gap-0.5">
        <div v-for="i in 3" :key="i" class="w-7 h-10 border border-white/5 bg-white/5 rounded flex items-center justify-center text-[8px] font-mono opacity-30">1%</div>
        <div v-for="i in 1" :key="i" class="w-7 h-10 border-2 border-green-500 bg-green-500/20 rounded flex items-center justify-center text-[8px] font-mono font-bold shadow-[0_0_10px_rgba(34,197,94,0.4)]">97%</div>
      </div>
      <span class="text-[10px] font-bold">Result: 11</span>
    </div>
  </section>

  <section class="flex flex-col items-center bg-white/10 rounded-xl p-4 border border-white/20 shadow-2xl relative overflow-hidden">
  <h3 class="text-[10px] font-black text-green-400 mb-4 uppercase tracking-widest font-mono text-center">16 Qubits</h3>
  
  <div class="mb-4 grid grid-cols-8 gap-1">
    <div v-for="i in 16" :key="i" class="w-4 h-4 rounded-full bg-green-500/40 shadow-[0_0_5px_rgba(34,197,94,0.4)] border border-green-400/30"></div>
  </div>

  <div class="flex flex-col items-center gap-1.5">
    <span class="text-[10px] font-bold text-center leading-none">Initial (65,536 States)</span>
    <div class="flex flex-col items-center gap-1.5 w-full">
  <div class="flex gap-0.5 justify-center items-center w-full overflow-hidden">
    <div v-for="i in 2" :key="'init-fade-'+i" class="w-6 h-10 border border-white/5 bg-white/5 rounded flex items-center justify-center text-[5px] font-mono opacity-10">0.001%</div>
    <div v-for="i in 3" :key="'init-mid-'+i" class="w-8 h-10 border border-white/10 bg-white/5 rounded flex items-center justify-center text-[5px] font-mono opacity-40 text-white/60">0.001%</div>
    <div v-for="i in 2" :key="'init-fade-r-'+i" class="w-6 h-10 border border-white/5 bg-white/5 rounded flex items-center justify-center text-[5px] font-mono opacity-10">0.001%</div>
  </div>
</div>
  </div>

  <div class="my-3 text-green-400/30 text-lg">↓</div>
  <div class="w-full py-2 border border-green-500/50 bg-green-400/10 rounded-lg text-center text-[9px] font-bold uppercase">Calculation</div>
  <div class="my-3 text-green-400/30 text-lg">↓</div>

  <div class="flex flex-col items-center gap-1.5 w-full">
    <div class="flex gap-0.5 justify-center items-center w-full opacity-80">
      <div v-for="i in 2" :key="'pre'+i" class="w-6 h-10 border border-white/5 bg-white/5 rounded flex items-center justify-center text-[6px] font-mono opacity-20">1%</div>
      <div class="w-8 h-10 border-2 border-green-500 bg-green-500/20 rounded flex flex-col items-center justify-center shadow-[0_0_15px_rgba(34,197,94,0.5)]">
        <span class="text-[8px] font-bold text-white">35%</span>
      </div>
      <div v-for="i in 2" :key="'post'+i" class="w-6 h-10 border border-white/5 bg-white/5 rounded flex items-center justify-center text-[6px] font-mono opacity-20">1%</div>
      </div>
      <span class="text-[10px] font-bold">Result: 1010011010001101</span>
  </div>
</section>

</div>

---
transition: fade-out
---

# Why so Fast?

<script setup>
import { ref } from 'vue'
const currentIndex = ref(0)
const isChecking = ref(false)
const trials = [
  '0010110110101011', 
  '1100101001110100', 
  '0111001011010110'
]

const nextTrial = () => {
  isChecking.value = true
  currentIndex.value = (currentIndex.value + 1) % trials.length
  setTimeout(() => { isChecking.value = false }, 150)
}
</script>

<div class="grid grid-cols-[0.9fr_1.1fr] gap-4 h-[85%] pt-1">

  <section class="bg-red-500/5 border border-red-500/20 rounded-xl p-3 flex flex-col items-center relative overflow-hidden">
    <h4 class="text-[10px] font-black text-red-400 mb-2 uppercase font-mono">
	Classical: One-by-One</h4>
    <div class="flex flex-col items-center justify-between flex-1 w-full">
      <div class="relative w-full h-20 flex items-center justify-center cursor-pointer" @click="nextTrial">
        <div class="z-20 bg-gray-900 border-2 border-red-400/50 p-3 rounded-lg shadow-xl hover:scale-105 transition-transform">
          <div class="text-[6px] text-red-400 uppercase font-bold mb-0.5">Checking...</div>
          <div class="font-mono text-[11px] text-white tracking-tight">{{ trials[currentIndex] }}</div>
        </div>
      </div>
      <div class="text-red-400 text-[10px] leading-none">▼</div>
      <div class="w-24 py-1.5 bg-red-400/10 border border-red-400/30 rounded text-center">
        <span class="text-[11px] font-black text-red-200 font-mono italic">Calc</span>
      </div>
      <div class="text-red-400 text-[10px] leading-none">▼</div>
      <div class="w-12 h-12 border-4 border-gray-700 bg-gray-950 flex items-center justify-center font-black text-xl transition-all duration-75 shadow-inner">
  <span v-if="!isChecking" class="text-gray-600">0</span>
  <span v-else class="text-transparent">0</span>
</div>
      <div class="w-full mt-2 p-2 bg-red-900/20 border border-red-400/10 rounded text-center">
        <p class="text-[15px] text-red-200 leading-tight">Worst Case: <b class="text-white text-[20px]">65,536 tries</b></p>
      </div>
    </div>
  </section>

  <section class="bg-blue-500/5 border border-blue-400/30 rounded-xl p-3 flex flex-col items-center shadow-2xl">
    <h4 class="text-[10px] font-black text-blue-400 mb-2 uppercase font-mono">
	Quantum: All-at-once</h4>
    <div class="flex flex-col items-center w-full flex-1 justify-between">
      <div class="bg-gray-900 border-2 border-blue-400/50 p-2 rounded-lg w-full flex flex-wrap gap-2 justify-center shadow-xl">
	  <span class="text-blue-400/40 font-black text-[10px]">...</span>
  <div v-for="s in trials" :key="s" class="flex flex-col items-center bg-white/5 px-2 py-1 rounded border border-white/5">
    <div class="font-mono text-[11px] text-white tracking-tight">{{ s }}</div>
    <div class="text-[6px] text-blue-400 uppercase font-bold mt-0.5">1/65,536</div>
  </div>
  <span class="text-blue-400/40 font-black text-[10px]">...</span>
</div>
      <div class="text-blue-400 text-[10px] leading-none">▼</div>
      <div class="w-full py-3 bg-blue-600/20 border border-blue-400 rounded flex items-center justify-center">
        <span class="text-[9px] font-black text-blue-100 uppercase font-mono italic">
		Calc</span>
      </div>
      <div class="text-blue-400 text-[10px] leading-none">▼</div>
      <div class="border-1 p-2 rounded-lg w-full flex flex-wrap gap-2 justify-center items-center shadow-2xl relative overflow-hidden">
  <div class="absolute inset-0"></div>
  
  <span class="text-gray-500 font-black text-[10px] opacity-30">...</span>

  <div v-for="(s, i) in trials" :key="'out-'+i" 
       :class="i === 2 ? 'border-2 border-green-500 bg-green-500/20 shadow-[0_0_15px_rgba(34,197,94,0.4)] scale-105 z-10' : 'opacity-30 border border-white/5'"
       class="flex flex-col items-center px-2 py-1 rounded">
    <div :class="i === 2 ? 'text-white font-bold' : 'text-gray-400'" class="font-mono text-[11px] tracking-tight">
      {{ s }}
    </div>
    <div :class="i === 2 ? 'text-green-400' : 'text-gray-600'" class="text-[6px] uppercase font-bold mt-0.5">
      {{ i === 2 ? '35%' : '0.01%' }}
    </div>
  </div>

  <span class="text-gray-500 font-black text-[10px] opacity-30">...</span>
</div>
<div class="w-full mt-2 p-2 bg-green-900/20 border border-green-400/20 rounded text-center shadow-[0_0_10px_rgba(34,197,94,0.1)]">
  <p class="text-[15px] text-green-200 leading-tight">
    Result: <b class="text-white text-[20px]">~35/100 shots</b> will be the Correct Answer <br>
  </p>
</div>
    </div>
  </section>

</div>

---
transition: fade-out
---

# What is happening inside the Calculation?

<div class="px-8 pt-4">
  <div class="p-3 bg-blue-500/5 border-l-4 border-blue-400 rounded-r-xl">
    <h2 class="text-xs font-black text-blue-400 mb-1 uppercase font-mono">Each State holds TWO Hidden Values</h2>
    <p class="text-[12px] leading-relaxed text-gray-200">
      To perform quantum calculations, a qubit doesn't just store "0 or 1." <br>
      Every possible state holds <b class="text-blue-300">Probability</b> and an additional parameter: <b class="text-green-300">Angle</b>.
    </p>
  </div>
</div>

<div class="flex items-center justify-between px-12 mt-9 pb-10">

  <div class="flex flex-col items-center gap-2">
    <span class="text-[9px] font-black uppercase tracking-widest">1. Initial</span>
    <div class="space-y-1 p-3 bg-white/5 rounded-xl border border-white/10 w-28">
      <div v-for="s in ['00','01','10','11']" :key="s" class="flex flex-col items-center border-b border-white/5 pb-0.5 last:border-0">
        <span class="text-[12px] font-mono text-blue-300">{{s}}</span>
        <div class="text-[9px] text-white font-mono">Prob: <span class="text-blue-200">25%</span></div>
        <div class="text-[8px] font-mono italic">Angle: 0°</div>
      </div>
    </div>
  </div>

  <div class="text-xl self-center mt-6">➔</div>

  <div class="flex flex-col items-center gap-2">
    <span class="text-[9px] font-black text-purple-400 uppercase tracking-widest animate-pulse">2. Manipulating...</span>
    <div class="space-y-1 p-3 bg-purple-500/10 rounded-xl border border-purple-400/30 w-28 shadow-lg">
      <div v-for="val in [{s:'00', p:10, a:45}, {s:'01', p:30, a:180}, {s:'10', p:50, a:90}, {s:'11', p:10, a:270}]" 
       :key="val.s" 
       class="flex flex-col items-center border-b border-purple-400/10 pb-0.5 last:border-0">
    <span class="text-[12px] font-mono text-purple-300">{{val.s}}</span>
    <div class="text-[9px] text-white font-mono">
      Prob: <span class="text-purple-200">{{val.p}}%</span>
    </div>
    <div class="text-[8px] text-purple-400 font-mono italic">
      Angle: {{val.a}}°
    </div>
  </div>
    </div>
  </div>

  <div class="text-xl self-center mt-6">➔</div>

  <div class="flex flex-col items-center gap-2">
    <span class="text-[9px] font-black text-green-400 uppercase tracking-widest">3. Final Result</span>
    <div class="space-y-1 p-3 bg-green-500/5 rounded-xl border border-green-500/20 w-28">
      <div v-for="(val, i) in [{p:1, a:0, s:'00'}, {p:1, a:0, s:'01'}, {p:97, a:0, s:'10'}, {p:1, a:0, s:'11'}]" :key="i" class="flex flex-col items-center border-b border-white/5 pb-0.5 last:border-0">
        <span :class="val.p > 50 ? 'text-green-400 font-bold' : 'text-gray-100'" class="text-[12px] font-mono">{{val.s}}</span>
        <div :class="val.p > 50 ? 'text-white font-bold' : 'text-gray-100'" class="text-[9px] font-mono">Prob: {{val.p}}%</div>
        <div class="text-[8px] text-gray-100 font-mono italic">Angle: 0°</div>
      </div>
    </div>
  </div>

</div>

---
transition: fade-out
---

# Visualizing the State: Circle Notation

<div class="px-8 pt-2">
  <div class="p-3 bg-purple-500/5 border-l-4 border-purple-400 rounded-r-xl mb-4">
    <p class="text-[13px] leading-relaxed text-gray-200">
      To keep track of <b class="text-blue-300">Probability</b> and <b class="text-green-300">Angle</b> during manipulation, we use <b>Circle Notation</b>.
    </p>
    <div class="flex gap-6 mt-2">
      <div class="flex items-center gap-2">
        <div class="w-3 h-3 rounded-full bg-blue-400"></div>
        <span class="text-[11px] text-gray-300"><b>Probability:</b> Area of the circle (called <i class="text-blue-300">Amplitude</i>)</span>
      </div>
      <div class="flex items-center gap-2">
        <div class="w-3 h-[1px] bg-white rotate-45"></div>
        <span class="text-[11px] text-gray-300"><b>Angle:</b> Phase measured clockwise from 12 o'clock</span>
      </div>
    </div>
  </div>
</div>

<div class="grid grid-cols-3 gap-6 px-10 mt-6 relative">
  <div class="absolute top-1/2 left-[30%] -translate-y-1/2 text-white/20 text-xl">➔</div>
  <div class="absolute top-1/2 left-[64%] -translate-y-1/2 text-white/20 text-xl">➔</div>

  <div class="flex flex-col items-center gap-3">
    <div class="bg-gray-800/50 p-4 rounded-xl border border-white/10 w-full h-40 flex flex-col items-center justify-center">
      <div class="flex gap-4">
        <div class="w-12 h-12 rounded-full border-2 border-dashed border-white/20"></div>
        <div class="w-12 h-12 rounded-full border-2 border-dashed border-white/20"></div>
      </div>
      <div class="mt-4 flex gap-8 text-[10px] font-mono text-gray-500">
        <span>0</span><span>1</span>
      </div>
    </div>
    <div class="text-center">
      <span class="text-[10px] font-black text-purple-400 uppercase">Step 1</span>
      <p class="text-[10px] text-gray-400 leading-tight">Prepare empty outlines for<br>each possible state.</p>
    </div>
  </div>

  <div class="flex flex-col items-center gap-3">
    <div class="bg-gray-800/50 p-4 rounded-xl border border-white/10 w-full h-40 flex flex-col items-center justify-center">
      <div class="flex gap-4">
        <div class="w-12 h-12 rounded-full border-2 border-dashed border-white/20 flex items-center justify-center">
          <div class="w-6 h-6 rounded-full bg-blue-400/60"></div>
        </div>
        <div class="w-12 h-12 rounded-full border-2 border-dashed border-white/20 flex items-center justify-center">
          <div class="w-10 h-10 rounded-full bg-blue-400/60"></div>
        </div>
      </div>
      <div class="mt-4 flex gap-8 text-[10px] font-mono text-blue-300">
        <span>25%</span><span>75%</span>
      </div>
    </div>
    <div class="text-center">
      <span class="text-[10px] font-black text-purple-400 uppercase">Step 2</span>
      <p class="text-[10px] text-gray-400 leading-tight">Draw circles with areas<br>matching the probability.</p>
    </div>
  </div>

  <div class="flex flex-col items-center gap-3">
    <div class="bg-gray-800/50 p-4 rounded-xl border border-white/10 w-full h-40 flex flex-col items-center justify-center">
      <div class="flex gap-4">
        <div class="w-12 h-12 rounded-full border-2 border-dashed border-white/20 flex items-center justify-center relative">
          <div class="w-6 h-6 rounded-full bg-blue-400/60"></div>
          <div class="absolute w-0.5 h-6 bg-white origin-bottom bottom-1/2 rotate-[45deg]"></div>
        </div>
        <div class="w-12 h-12 rounded-full border-2 border-dashed border-white/20 flex items-center justify-center relative">
          <div class="w-10 h-10 rounded-full bg-blue-400/60"></div>
          <div class="absolute w-0.5 h-6 bg-white origin-bottom bottom-1/2 rotate-[180deg]"></div>
        </div>
      </div>
      <div class="mt-4 flex gap-6 text-[10px] font-mono text-green-300">
        <span>315°</span><span>180°</span>
      </div>
    </div>
    <div class="text-center">
      <span class="text-[10px] font-black text-purple-400 uppercase">Step 3</span>
      <p class="text-[10px] text-gray-400 leading-tight">Add the "Phase Line"<br>starting from 12 o'clock.</p>
    </div>
  </div>
</div>

---
transition: fade-out
---

# Control the Quantum State

<script setup>
import { ref, computed } from 'vue'

const R = 50
const p0 = ref(0.3) 
const angle1 = ref(0)
const angle2 = ref(90)

const r1 = computed(() => R * Math.sqrt(p0.value))
const r2 = computed(() => R * Math.sqrt(1 - p0.value))

const prob0Label = computed(() => (p0.value * 100).toFixed(0))
const prob1Label = computed(() => ((1 - p0.value) * 100).toFixed(0))

const updateP0 = (val) => { p0.value = val }
const updateP1 = (val) => { p0.value = 1 - val }
</script>

<div class="grid grid-cols-[1.2fr_0.8fr] gap-8 h-full items-center pb-10">

  <div class="bg-white/5 border border-white/10 rounded-3xl p-6 shadow-2xl relative">
    <div class="absolute -top-3 left-6 px-3 py-0.5 bg-blue-600 rounded-full text-[9px] font-black uppercase tracking-widest">
      Live State Demo
    </div>
    <div class="flex gap-10 justify-center items-center">
      <div class="flex flex-col items-center">
        <div :style="{ width: `${R * 2}px`, height: `${R * 2}px` }" 
             class="relative flex items-center justify-center rounded-full border-2 border-white/20 bg-black/40 shadow-inner overflow-hidden">
          <div class="absolute w-[2px] bg-white transition-transform duration-100 ease-linear" 
               :style="{ 
                 height: `${R}px`, 
                 top: '0',
                 transformOrigin: 'bottom center',
                 transform: `rotate(${-angle1}deg)` 
               }"></div>
          <div class="rounded-full bg-blue-500/40 transition-all duration-300" 
               :style="{ width: `${r1 * 2}px`, height: `${r1 * 2}px` }"></div>
        </div>
        <div class="mt-4 text-center font-mono">
          <span class="text-blue-300 font-bold block text-sm">|0⟩: {{ prob0Label }}%</span>
          <div class="flex flex-col gap-1 mt-2">
            <span class="text-[8px] text-gray-500 uppercase">Size</span>
            <input type="range" min="0" max="1" step="0.01" :value="p0" @input="e => updateP0(parseFloat(e.target.value))" class="accent-blue-400 w-24 h-1" />
            <span class="text-[8px] text-gray-500 uppercase mt-1">Angle</span>
            <input type="range" min="0" max="360" v-model.number="angle1" class="w-24 accent-white opacity-40 h-1" />
          </div>
        </div>
      </div>
      <div class="text-2xl font-thin opacity-20">＋</div>
      <div class="flex flex-col items-center">
        <div :style="{ width: `${R * 2}px`, height: `${R * 2}px` }" 
             class="relative flex items-center justify-center rounded-full border-2 border-white/20 bg-black/40 shadow-inner overflow-hidden">
          <div class="absolute w-[2px] bg-white transition-transform duration-100 ease-linear" 
               :style="{ 
                 height: `${R}px`, 
                 top: '0',
                 transformOrigin: 'bottom center',
                 transform: `rotate(${-angle2}deg)` 
               }"></div>
          <div class="rounded-full bg-green-500/40 transition-all duration-300" 
               :style="{ width: `${r2 * 2}px`, height: `${r2 * 2}px` }"></div>
        </div>
        <div class="mt-4 text-center font-mono">
          <span class="text-green-300 font-bold block text-sm">|1⟩: {{ prob1Label }}%</span>
          <div class="flex flex-col gap-1 mt-2">
            <span class="text-[8px] text-gray-500 uppercase">Size</span>
            <input type="range" min="0" max="1" step="0.01" :value="1 - p0" @input="e => updateP1(parseFloat(e.target.value))" class="accent-green-400 w-24 h-1" />
            <span class="text-[8px] text-gray-500 uppercase mt-1">Angle</span>
            <input type="range" min="0" max="360" v-model.number="angle2" class="w-24 accent-white opacity-40 h-1" />
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="flex flex-col gap-4">
    <div class="p-4 bg-blue-500/10 border border-blue-400/30 rounded-2xl">
      <h3 class="text-xs font-black text-blue-400 uppercase mb-2">1. Conservation</h3>
      <p class="text-[13px] text-gray-200 leading-snug">
        Total probability is always <b class="text-white text-lg">100%</b>. <br>
        <span class="text-[10px] text-gray-400 italic">If one grows, the other must shrink.</span>
      </p>
    </div>
    <div class="p-4 bg-purple-500/10 border border-purple-400/30 rounded-2xl">
      <h3 class="text-xs font-black text-purple-400 uppercase mb-2">2. Independence</h3>
      <p class="text-[13px] text-gray-200 leading-snug">
        <b class="text-white">Angle (Phase)</b> is independent of probability. <br>
        <span class="text-[10px] text-gray-400 italic">Changing the angle doesn't change the circle's size.</span>
      </p>
    </div>
  </div>

</div>

---
transition: slide-left
---

# Circle Notation: 2-Qubit Example

<div class="px-8 pt-2">
  <div class="p-3 bg-blue-500/5 border-l-4 border-blue-400 rounded-r-xl mb-6">
    <p class="text-[13px] leading-relaxed text-gray-200">
      With <b class="text-blue-300">2 Qubits</b>, we represent <b class="text-white font-bold">4 Basis States</b> simultaneously. <br>
      Each circle independently holds its own <span class="text-blue-300">Probability (Area)</span> and <span class="text-green-300">Phase (Angle)</span>.
    </p>
  </div>
</div>

<div class="flex flex-col items-center justify-center mt-4">
  <div class="grid grid-cols-4 gap-8 p-8 bg-white/5 rounded-3xl border border-white/10 shadow-2xl relative">
    <div class="flex flex-col items-center gap-4">
      <div class="w-20 h-20 rounded-full border-2 border-dashed border-white/20 flex items-center justify-center relative shadow-inner">
        <div class="w-12 h-12 rounded-full bg-blue-400/60 shadow-[0_0_20px_rgba(96,165,250,0.3)]"></div>
        <div class="absolute w-0.5 h-10 bg-white origin-bottom bottom-1/2 rotate-[0deg] shadow-lg"></div>
      </div>
      <div class="text-center font-mono">
        <div class="text-blue-300 text-sm font-bold">00</div>
        <div class="text-[10px] text-gray-400">Prob: 40%</div>
        <div class="text-[10px] text-green-400 italic">Phase: 0°</div>
      </div>
    </div>
    <div class="flex flex-col items-center gap-4">
      <div class="w-20 h-20 rounded-full border-2 border-dashed border-white/20 flex items-center justify-center relative">
        <div class="w-6 h-6 rounded-full bg-blue-400/60"></div>
        <div class="absolute w-0.5 h-10 bg-white origin-bottom bottom-1/2 rotate-[90deg]"></div>
      </div>
      <div class="text-center font-mono">
        <div class="text-blue-300 text-sm font-bold">01</div>
        <div class="text-[10px] text-gray-400">Prob: 10%</div>
        <div class="text-[10px] text-green-400 italic">Phase: 270°</div>
      </div>
    </div>
    <div class="flex flex-col items-center gap-4">
      <div class="w-20 h-20 rounded-full border-2 border-dashed border-white/20 flex items-center justify-center relative">
        <div class="w-14 h-14 rounded-full bg-blue-400/60"></div>
        <div class="absolute w-0.5 h-10 bg-white origin-bottom bottom-1/2 rotate-[180deg]"></div>
      </div>
      <div class="text-center font-mono">
        <div class="text-blue-300 text-sm font-bold">10</div>
        <div class="text-[10px] text-gray-400">Prob: 45%</div>
        <div class="text-[10px] text-green-400 italic">Phase: 180°</div>
      </div>
    </div>
    <div class="flex flex-col items-center gap-4">
      <div class="w-20 h-20 rounded-full border-2 border-dashed border-white/20 flex items-center justify-center relative">
        <div class="w-4 h-4 rounded-full bg-blue-400/60 opacity-50"></div>
        <div class="absolute w-0.5 h-10 bg-white origin-bottom bottom-1/2 rotate-[270deg]"></div>
      </div>
      <div class="text-center font-mono">
        <div class="text-blue-300 text-sm font-bold">11</div>
        <div class="text-[10px] text-gray-400">Prob: 5%</div>
        <div class="text-[10px] text-green-400 italic">Phase: 90°</div>
      </div>
    </div>

  </div>
</div>

<div class="mt-8 text-center">
  <p class="text-[11px] text-gray-400 italic">
    Total Probability (Sum of Areas) <b class="text-white">= 1.00 (100%)</b>
  </p>
</div>

---
transition: fade-out
---

# Part 2: Lecture + Hands-on

<div class="flex justify-center mt-4">
  <div class="flex w-full max-w-5xl h-[400px] bg-[#222222] rounded-2xl overflow-hidden shadow-2xl border border-gray-600">

  <div class="flex flex-col justify-between p-12 flex-1">
      <div>
        <h3 class="text-4xl font-bold text-white mb-6">Computation</h3>
        <p class="text-xl text-gray-300 leading-relaxed">
          In Part 1, we reviewed the overall flow of quantum computing: encoding, computation, and decoding. Here, we will focus on the computation phase and explore how quantum calculations are actually performed.
        </p>
        <p class="text-lg text-gray-400 mt-8 font-medium">Instructors: Togo & Sasuke</p>
      </div>
    </div> <div class="flex w-[500px] h-full shrink-0 border-l border-gray-700">
      <img src="/images/Urayama.jpg" alt="Urayama" class="w-1/2 h-full object-cover object-[40%_center] border-r border-gray-700" />
      <img src="/images/Kimata.JPG" alt="Kimata" class="w-1/2 h-full object-cover object-[50%_center]" />
    </div>

  </div> </div>

---
transition: fade-out
---

# Quantum Circuit

<div class="mt-1 px-8">
  
  <p class="text-lg text-gray-300 leading-snug mb-3">
    We build <b>'quantum circuits'</b> to perform actual quantum computations. A quantum circuit is made up of a collection of <b>'quantum gates,'</b> which change the state of the qubits.
  </p>

  <div class="flex flex-col items-center justify-center mb-3">
    <img src="/images/Unknown.png" 
         alt="Quantum Circuit Diagram" 
         class="rounded-xl shadow-lg h-64 object-contain border border-gray-700 bg-white p-4" />
  </div>

  <div class="bg-[#111111] px-6 py-3 rounded-lg border border-cyan-500 shadow-[0_0_15px_rgba(6,182,212,0.3)]">
  <p class="text-sm text-cyan-100 italic leading-relaxed">
    <span class="font-bold text-cyan-400">Note:</span> The quantum circuit above implements Grover's algorithm, which we will cover on Day 2. To help you understand this circuit we will now introduce the individual quantum gates one by one.
  </p>
</div>
</div>

---
transition: fade-out
---

# Quantum Gates

<div class="mt-1 px-8">
  
  <p class="text-lg text-gray-300 leading-snug mb-3">
   <b>Quantum gates</b> are the <b>'building blocks'</b> of a quantum circuit. They perform specific operations on an input quantum state and output a qubit in a new state.
  </p>

  <div class="flex flex-col items-center justify-center mb-3">
    <img src="/images/Gemini_Generated_Image_sr2obssr2obssr2o.png" 
         alt="Quantum Gate Operation" 
         class="rounded-xl shadow-lg h-64 object-contain border border-gray-700" />
  </div>

  <div class="bg-gray-800 px-6 py-0.1 rounded-lg border-l-4 border-blue-500">
    <p class="text-sm text-gray-300 italic leading-tight">
      "We will now look at specific quantum gates for 1-qubit and 2-qubit systems. These operations are essential for understanding the algorithms in Day 2. We will also cover the basics of using "Qiskit."
    </p>
  </div>
</div>

---
transition: slide-up
level: 2
---
# Single Qubit Calculation

<div class="flex items-center gap-5 border-b border-white/10 pb-2 mb-3">
  <div class="inline-flex items-center px-6 py-1 bg-blue-500/10 border border-blue-500/50 rounded-full shadow-[0_0_15px_rgba(59,130,246,0.2)]">
    <span class="text-xl font-black text-blue-400 tracking-wider uppercase">X Gate</span>
  </div>
  <div class="text-base font-mono text-blue-400">Swap the left and right circles</div>
</div>

<script setup>
import { ref, watch } from 'vue'

const R = 60  // Radius of the large circle

// === Left Box (Qubit) ===
const rLeft0 = ref(R)
const rLeft1 = ref(0)
const angleL0 = ref(0)
const angleL1 = ref(0)

// Update to keep area constant
function updateRLeft0() {
  rLeft1.value = Math.sqrt(Math.max(R ** 2 - rLeft0.value ** 2, 0))
}
function updateRLeft1() {
  rLeft0.value = Math.sqrt(Math.max(R ** 2 - rLeft1.value ** 2, 0))
}

// === Right Box (After X Gate) ===
// Swap circles based on left side
const rRight0 = ref(rLeft1.value) 
const rRight1 = ref(rLeft0.value) 
const angleR0 = ref(angleL1.value)
const angleR1 = ref(angleL0.value)

// Watch left side and reflect on right
watch([rLeft0, rLeft1, angleL0, angleL1], () => {
  rRight0.value = rLeft1.value
  rRight1.value = rLeft0.value
  angleR0.value = angleL1.value
  angleR1.value = angleL0.value
})
</script>

<div class="flex gap-8 justify-center items-stretch text-white">
  
  <div class="p-4 border border-white/20 rounded-2xl bg-black/40 shadow-lg">
    <p class="font-semibold mb-3 text-center text-gray-200">Before Gate</p>
    <div class="flex gap-8">
      
  <div class="flex flex-col items-center">
        <div class="relative rounded-full border-2 border-white/60 flex justify-center items-center mb-2"
             :style="{width: `${R*2}px`, height: `${R*2}px`}">
          <div v-if="rLeft0 > 0" class="absolute bg-white origin-bottom"
               :style="{width:'2px', height:`${R}px`, bottom:'50%', transform:`rotate(${-angleL0}deg)`}"></div>
          <div class="rounded-full bg-blue-500/40 transition-all"
               :style="{width:`${rLeft0*2}px`, height:`${rLeft0*2}px`}"></div>
        </div>
        <p class="mb-3 font-mono">|0⟩</p>
        
  <div class="bg-white/5 p-2.5 rounded-lg flex flex-col gap-2.5 w-full border border-white/10">
          <div class="flex items-center justify-between gap-3">
            <span class="text-[10px] text-blue-300 font-mono font-bold tracking-widest">AMP</span>
            <input type="range" :min="0" :max="R" v-model.number="rLeft0" @input="updateRLeft0" class="accent-blue-400 w-20 h-1.5 cursor-pointer"/>
          </div>
          <div class="flex items-center justify-between gap-3">
            <span class="text-[10px] text-gray-300 font-mono font-bold tracking-widest">PHS</span>
            <input type="range" :min="0" :max="360" v-model.number="angleL0" class="accent-white w-20 h-1.5 cursor-pointer"/>
          </div>
        </div>
      </div>

  <div class="flex flex-col items-center">
        <div class="relative rounded-full border-2 border-white/60 flex justify-center items-center mb-2"
             :style="{width: `${R*2}px`, height: `${R*2}px`}">
          <div v-if="rLeft1 > 0" class="absolute bg-white origin-bottom"
               :style="{width:'2px', height:`${R}px`, bottom:'50%', transform:`rotate(${-angleL1}deg)`}"></div>
          <div class="rounded-full bg-green-500/40 transition-all"
               :style="{width:`${rLeft1*2}px`, height:`${rLeft1*2}px`}"></div>
        </div>
        <p class="mb-3 font-mono">|1⟩</p>
        
  <div class="bg-white/5 p-2.5 rounded-lg flex flex-col gap-2.5 w-full border border-white/10">
          <div class="flex items-center justify-between gap-3">
            <span class="text-[10px] text-green-300 font-mono font-bold tracking-widest">AMP</span>
            <input type="range" :min="0" :max="R" v-model.number="rLeft1" @input="updateRLeft1" class="accent-green-400 w-20 h-1.5 cursor-pointer"/>
          </div>
          <div class="flex items-center justify-between gap-3">
            <span class="text-[10px] text-gray-300 font-mono font-bold tracking-widest">PHS</span>
            <input type="range" :min="0" :max="360" v-model.number="angleL1" class="accent-white w-20 h-1.5 cursor-pointer"/>
          </div>
        </div>
      </div>

  </div>
  </div>

  <div class="p-4 border border-white/20 rounded-2xl bg-black/40 shadow-lg">
    <p class="font-semibold mb-3 text-center text-gray-200">After X Gate</p>
    <div class="flex gap-8 h-full">
      
  <div class="flex flex-col items-center">
        <div class="relative rounded-full border-2 border-white/60 flex justify-center items-center mb-2"
             :style="{width: `${R*2}px`, height: `${R*2}px`}">
          <div v-if="rRight0 > 0" class="absolute bg-white origin-bottom"
               :style="{width:'2px', height:`${R}px`, bottom:'50%', transform:`rotate(${-angleR0}deg)`}"></div>
          <div class="rounded-full bg-blue-500/40 transition-all"
               :style="{width:`${rRight0*2}px`, height:`${rRight0*2}px`}"></div>
        </div>
        <p class="mb-3 font-mono">|0⟩</p>
      </div>

  <div class="flex flex-col items-center">
        <div class="relative rounded-full border-2 border-white/60 flex justify-center items-center mb-2"
             :style="{width: `${R*2}px`, height: `${R*2}px`}">
          <div v-if="rRight1 > 0" class="absolute bg-white origin-bottom"
               :style="{width:'2px', height:`${R}px`, bottom:'50%', transform:`rotate(${-angleR1}deg)`}"></div>
          <div class="rounded-full bg-green-500/40 transition-all"
               :style="{width:`${rRight1*2}px`, height:`${rRight1*2}px`}"></div>
        </div>
        <p class="mb-3 font-mono">|1⟩</p>
      </div>

  </div>
  </div>
</div>
---
transition: slide-up
level: 2
---
# Single Qubit Calculation

<div class="flex items-center gap-5 border-b border-white/10 pb-2 mb-3">
  <div class="inline-flex items-center px-6 py-1 bg-blue-500/10 border border-blue-500/50 rounded-full shadow-[0_0_15px_rgba(59,130,246,0.2)]">
    <span class="text-xl font-black text-blue-400 tracking-wider uppercase">Y Gate</span>
  </div>
  <div class="text-base font-mono text-blue-400">Interchange the circles and rotate their phases by 90°</div>
</div>

<script setup>
import { ref, watch } from 'vue'

const R = 60  // Radius of the large circle

// === Left Box (Qubit) ===
const rLeft0 = ref(R)
const rLeft1 = ref(0)
const angleL0 = ref(0)
const angleL1 = ref(0)

// Update to keep area constant
function updateRLeft0() {
  rLeft1.value = Math.sqrt(Math.max(R ** 2 - rLeft0.value ** 2, 0))
}
function updateRLeft1() {
  rLeft0.value = Math.sqrt(Math.max(R ** 2 - rLeft1.value ** 2, 0))
}

// === Right Box (After Y Gate) ===
// Swap circles, add ±90° phase
const rRight0 = ref(rLeft1.value) // Left 1 -> Right 0
const rRight1 = ref(rLeft0.value) // Left 0 -> Right 1
const angleR0 = ref(angleL1.value + 90) // +90° rotation
const angleR1 = ref(angleL0.value - 90) // -90° rotation

// Watch left side and reflect on right
watch([rLeft0, rLeft1, angleL0, angleL1], () => {
  rRight0.value = rLeft1.value
  rRight1.value = rLeft0.value
  angleR0.value = angleL1.value - 90
  angleR1.value = angleL0.value + 90
})
</script>

<div class="flex gap-8 justify-center items-stretch text-white">
  
  <div class="p-4 border border-white/20 rounded-2xl bg-black/40 shadow-lg">
    <p class="font-semibold mb-3 text-center text-gray-200">Before Gate</p>
    <div class="flex gap-8">
      
  <div class="flex flex-col items-center">
        <div class="relative rounded-full border-2 border-white/60 flex justify-center items-center mb-2"
             :style="{width: `${R*2}px`, height: `${R*2}px`}">
          <div v-if="rLeft0 > 0" class="absolute bg-white origin-bottom"
               :style="{width:'2px', height:`${R}px`, bottom:'50%', transform:`rotate(${-angleL0}deg)`}"></div>
          <div class="rounded-full bg-blue-500/40 transition-all"
               :style="{width:`${rLeft0*2}px`, height:`${rLeft0*2}px`}"></div>
        </div>
        <p class="mb-3 font-mono">|0⟩</p>
        
  <div class="bg-white/5 p-2.5 rounded-lg flex flex-col gap-2.5 w-full border border-white/10">
          <div class="flex items-center justify-between gap-3">
            <span class="text-[10px] text-blue-300 font-mono font-bold tracking-widest">AMP</span>
            <input type="range" :min="0" :max="R" v-model.number="rLeft0" @input="updateRLeft0" class="accent-blue-400 w-20 h-1.5 cursor-pointer"/>
          </div>
          <div class="flex items-center justify-between gap-3">
            <span class="text-[10px] text-gray-300 font-mono font-bold tracking-widest">PHS</span>
            <input type="range" :min="0" :max="360" v-model.number="angleL0" class="accent-white w-20 h-1.5 cursor-pointer"/>
          </div>
        </div>
      </div>

  <div class="flex flex-col items-center">
        <div class="relative rounded-full border-2 border-white/60 flex justify-center items-center mb-2"
             :style="{width: `${R*2}px`, height: `${R*2}px`}">
          <div v-if="rLeft1 > 0" class="absolute bg-white origin-bottom"
               :style="{width:'2px', height:`${R}px`, bottom:'50%', transform:`rotate(${-angleL1}deg)`}"></div>
          <div class="rounded-full bg-green-500/40 transition-all"
               :style="{width:`${rLeft1*2}px`, height:`${rLeft1*2}px`}"></div>
        </div>
        <p class="mb-3 font-mono">|1⟩</p>
        
  <div class="bg-white/5 p-2.5 rounded-lg flex flex-col gap-2.5 w-full border border-white/10">
          <div class="flex items-center justify-between gap-3">
            <span class="text-[10px] text-green-300 font-mono font-bold tracking-widest">AMP</span>
            <input type="range" :min="0" :max="R" v-model.number="rLeft1" @input="updateRLeft1" class="accent-green-400 w-20 h-1.5 cursor-pointer"/>
          </div>
          <div class="flex items-center justify-between gap-3">
            <span class="text-[10px] text-gray-300 font-mono font-bold tracking-widest">PHS</span>
            <input type="range" :min="0" :max="360" v-model.number="angleL1" class="accent-white w-20 h-1.5 cursor-pointer"/>
          </div>
        </div>
      </div>

  </div>
  </div>

  <div class="p-4 border border-white/20 rounded-2xl bg-black/40 shadow-lg">
    <p class="font-semibold mb-3 text-center text-gray-200">After Y Gate</p>
    <div class="flex gap-8 h-full">
      
  <div class="flex flex-col items-center">
        <div class="relative rounded-full border-2 border-white/60 flex justify-center items-center mb-2"
             :style="{width: `${R*2}px`, height: `${R*2}px`}">
          <div v-if="rRight0 > 0" class="absolute bg-white origin-bottom"
               :style="{width:'2px', height:`${R}px`, bottom:'50%', transform:`rotate(${-angleR0}deg)`}"></div>
          <div class="rounded-full bg-blue-500/40 transition-all"
               :style="{width:`${rRight0*2}px`, height:`${rRight0*2}px`}"></div>
        </div>
        <p class="mb-3 font-mono">|0⟩</p>
      </div>

  <div class="flex flex-col items-center">
        <div class="relative rounded-full border-2 border-white/60 flex justify-center items-center mb-2"
             :style="{width: `${R*2}px`, height: `${R*2}px`}">
          <div v-if="rRight1 > 0" class="absolute bg-white origin-bottom"
               :style="{width:'2px', height:`${R}px`, bottom:'50%', transform:`rotate(${-angleR1}deg)`}"></div>
          <div class="rounded-full bg-green-500/40 transition-all"
               :style="{width:`${rRight1*2}px`, height:`${rRight1*2}px`}"></div>
        </div>
        <p class="mb-3 font-mono">|1⟩</p>
      </div>

  </div>
  </div>
</div>

---
transition: slide-up
level: 2
---
# Single Qubit Calculation

<div class="flex items-center gap-5 border-b border-white/10 pb-2 mb-3">
  <div class="inline-flex items-center px-6 py-1 bg-blue-500/10 border border-blue-500/50 rounded-full shadow-[0_0_15px_rgba(59,130,246,0.2)]">
    <span class="text-xl font-black text-blue-400 tracking-wider uppercase">Z Gate</span>
  </div>
  <div class="text-base font-mono text-blue-400">Flips the phase of the ∣1⟩ state while leaving ∣0⟩ unchanged</div>
</div>

<script setup>
import { ref, watch } from 'vue'

const R = 60  // Radius of the large circle

// === Left Box (Qubit) ===
const rLeft0 = ref(R)
const rLeft1 = ref(0)
const angleL0 = ref(0)
const angleL1 = ref(0)

// Update to keep area constant
function updateRLeft0() {
  rLeft1.value = Math.sqrt(Math.max(R ** 2 - rLeft0.value ** 2, 0))
}
function updateRLeft1() {
  rLeft0.value = Math.sqrt(Math.max(R ** 2 - rLeft1.value ** 2, 0))
}

// === Right Box (After Z Gate) ===
// Area stays same, rotate phase of |1⟩ by 180°
const rRight0 = ref(rLeft0.value)
const rRight1 = ref(rLeft1.value)
const angleR0 = ref(angleL0.value)
const angleR1 = ref(angleL1.value + 180)

// Watch left and reflect on right
watch([rLeft0, rLeft1, angleL0, angleL1], () => {
  rRight0.value = rLeft0.value
  rRight1.value = rLeft1.value
  angleR0.value = angleL0.value
  angleR1.value = angleL1.value + 180
})
</script>

<div class="flex gap-8 justify-center items-stretch text-white">
  
  <div class="p-4 border border-white/20 rounded-2xl bg-black/40 shadow-lg">
    <p class="font-semibold mb-3 text-center text-gray-200">Before Gate</p>
    <div class="flex gap-8">
      
  <div class="flex flex-col items-center">
        <div class="relative rounded-full border-2 border-white/60 flex justify-center items-center mb-2"
             :style="{width: `${R*2}px`, height: `${R*2}px`}">
          <div v-if="rLeft0 > 0" class="absolute bg-white origin-bottom"
               :style="{width:'2px', height:`${R}px`, bottom:'50%', transform:`rotate(${-angleL0}deg)`}"></div>
          <div class="rounded-full bg-blue-500/40 transition-all"
               :style="{width:`${rLeft0*2}px`, height:`${rLeft0*2}px`}"></div>
        </div>
        <p class="mb-3 font-mono">|0⟩</p>
        
  <div class="bg-white/5 p-2.5 rounded-lg flex flex-col gap-2.5 w-full border border-white/10">
          <div class="flex items-center justify-between gap-3">
            <span class="text-[10px] text-blue-300 font-mono font-bold tracking-widest">AMP</span>
            <input type="range" :min="0" :max="R" v-model.number="rLeft0" @input="updateRLeft0" class="accent-blue-400 w-20 h-1.5 cursor-pointer"/>
          </div>
          <div class="flex items-center justify-between gap-3">
            <span class="text-[10px] text-gray-300 font-mono font-bold tracking-widest">PHS</span>
            <input type="range" :min="0" :max="360" v-model.number="angleL0" class="accent-white w-20 h-1.5 cursor-pointer"/>
          </div>
        </div>
      </div>

  <div class="flex flex-col items-center">
        <div class="relative rounded-full border-2 border-white/60 flex justify-center items-center mb-2"
             :style="{width: `${R*2}px`, height: `${R*2}px`}">
          <div v-if="rLeft1 > 0" class="absolute bg-white origin-bottom"
               :style="{width:'2px', height:`${R}px`, bottom:'50%', transform:`rotate(${-angleL1}deg)`}"></div>
          <div class="rounded-full bg-green-500/40 transition-all"
               :style="{width:`${rLeft1*2}px`, height:`${rLeft1*2}px`}"></div>
        </div>
        <p class="mb-3 font-mono">|1⟩</p>
        
  <div class="bg-white/5 p-2.5 rounded-lg flex flex-col gap-2.5 w-full border border-white/10">
          <div class="flex items-center justify-between gap-3">
            <span class="text-[10px] text-green-300 font-mono font-bold tracking-widest">AMP</span>
            <input type="range" :min="0" :max="R" v-model.number="rLeft1" @input="updateRLeft1" class="accent-green-400 w-20 h-1.5 cursor-pointer"/>
          </div>
          <div class="flex items-center justify-between gap-3">
            <span class="text-[10px] text-gray-300 font-mono font-bold tracking-widest">PHS</span>
            <input type="range" :min="0" :max="360" v-model.number="angleL1" class="accent-white w-20 h-1.5 cursor-pointer"/>
          </div>
        </div>
      </div>

  </div>
  </div>

  <div class="p-4 border border-white/20 rounded-2xl bg-black/40 shadow-lg">
    <p class="font-semibold mb-3 text-center text-gray-200">After Z Gate</p>
    <div class="flex gap-8 h-full">
      
  <div class="flex flex-col items-center">
        <div class="relative rounded-full border-2 border-white/60 flex justify-center items-center mb-2"
             :style="{width: `${R*2}px`, height: `${R*2}px`}">
          <div v-if="rRight0 > 0" class="absolute bg-white origin-bottom"
               :style="{width:'2px', height:`${R}px`, bottom:'50%', transform:`rotate(${-angleR0}deg)`}"></div>
          <div class="rounded-full bg-blue-500/40 transition-all"
               :style="{width:`${rRight0*2}px`, height:`${rRight0*2}px`}"></div>
        </div>
        <p class="mb-3 font-mono">|0⟩</p>
      </div>

  <div class="flex flex-col items-center">
        <div class="relative rounded-full border-2 border-white/60 flex justify-center items-center mb-2"
             :style="{width: `${R*2}px`, height: `${R*2}px`}">
          <div v-if="rRight1 > 0" class="absolute bg-white origin-bottom"
               :style="{width:'2px', height:`${R}px`, bottom:'50%', transform:`rotate(${-angleR1}deg)`}"></div>
          <div class="rounded-full bg-green-500/40 transition-all"
               :style="{width:`${rRight1*2}px`, height:`${rRight1*2}px`}"></div>
        </div>
        <p class="mb-3 font-mono">|1⟩</p>
      </div>

  </div>
  </div>
</div>

---
transition: slide-up
level: 2
---
# Single Qubit Calculation

<div class="flex items-center gap-5 border-b border-white/10 pb-2 mb-3">
  <div class="inline-flex items-center px-6 py-1 bg-blue-500/10 border border-blue-500/50 rounded-full shadow-[0_0_15px_rgba(59,130,246,0.2)]">
    <span class="text-xl font-black text-blue-400 tracking-wider uppercase">H Gate</span>
  </div>
  <div class="text-base font-mono text-blue-400">Creates a superposition state by mixing amplitudes</div>
</div>

<script setup>
import { ref, computed } from 'vue'

const R = 60  // 半径の最大値

// === Before Gate (Input) ===
const rLeft0 = ref(R)
const rLeft1 = ref(0)
const angleL0 = ref(0)
const angleL1 = ref(0)

// 確率の合計を1に保つ（面積の合計を一定にする）
function updateRLeft0() {
  rLeft1.value = Math.sqrt(Math.max(R ** 2 - rLeft0.value ** 2, 0))
}
function updateRLeft1() {
  rLeft0.value = Math.sqrt(Math.max(R ** 2 - rLeft1.value ** 2, 0))
}

// === After H Gate (Calculation) ===
// H |0> = (|0> + |1>) / sqrt(2)
// H |1> = (|0> - |1>) / sqrt(2)
const afterH = computed(() => {
  const toRad = (deg) => (deg * Math.PI) / 180
  const toDeg = (rad) => (rad * 180) / Math.PI

  // 複素数 (実部と虚部) への変換
  const z0 = {
    re: rLeft0.value * Math.cos(toRad(angleL0.value)),
    im: rLeft0.value * Math.sin(toRad(angleL0.value))
  }
  const z1 = {
    re: rLeft1.value * Math.cos(toRad(angleL1.value)),
    im: rLeft1.value * Math.sin(toRad(angleL1.value))
  }

  // アダマール変換行列の適用
  const sqrt2 = Math.sqrt(2)
  const res0 = {
    re: (z0.re + z1.re) / sqrt2,
    im: (z0.im + z1.im) / sqrt2
  }
  const res1 = {
    re: (z0.re - z1.re) / sqrt2,
    im: (z0.im - z1.im) / sqrt2
  }

  // 再び極座標（半径と角度）に戻す
  return {
    r0: Math.sqrt(res0.re ** 2 + res0.im ** 2),
    angle0: toDeg(Math.atan2(res0.im, res0.re)),
    r1: Math.sqrt(res1.re ** 2 + res1.im ** 2),
    angle1: toDeg(Math.atan2(res1.im, res1.re))
  }
})
</script>

<div class="flex gap-8 justify-center items-stretch text-white">
  
  <div class="p-4 border border-white/20 rounded-2xl bg-black/40 shadow-lg">
    <p class="font-semibold mb-3 text-center text-gray-200">Before Gate</p>
    <div class="flex gap-8">
      
  <div class="flex flex-col items-center">
        <div class="relative rounded-full border-2 border-white/60 flex justify-center items-center mb-2"
             :style="{width: `${R*2}px`, height: `${R*2}px`}">
          <div v-if="rLeft0 > 0" class="absolute bg-white origin-bottom"
               :style="{width:'2px', height:`${R}px`, bottom:'50%', transform:`rotate(${-angleL0}deg)`}"></div>
          <div class="rounded-full bg-blue-500/40 transition-all"
               :style="{width:`${rLeft0*2}px`, height:`${rLeft0*2}px`}"></div>
        </div>
        <p class="mb-3 font-mono">|0⟩</p>
        
  <div class="bg-white/5 p-2.5 rounded-lg flex flex-col gap-2.5 w-full border border-white/10">
          <div class="flex items-center justify-between gap-3">
            <span class="text-[10px] text-blue-300 font-mono font-bold tracking-widest">AMP</span>
            <input type="range" :min="0" :max="R" v-model.number="rLeft0" @input="updateRLeft0" class="accent-blue-400 w-20 h-1.5 cursor-pointer"/>
          </div>
          <div class="flex items-center justify-between gap-3">
            <span class="text-[10px] text-gray-300 font-mono font-bold tracking-widest">PHS</span>
            <input type="range" :min="0" :max="360" v-model.number="angleL0" class="accent-white w-20 h-1.5 cursor-pointer"/>
          </div>
        </div>
      </div>

  <div class="flex flex-col items-center">
        <div class="relative rounded-full border-2 border-white/60 flex justify-center items-center mb-2"
             :style="{width: `${R*2}px`, height: `${R*2}px`}">
          <div v-if="rLeft1 > 0" class="absolute bg-white origin-bottom"
               :style="{width:'2px', height:`${R}px`, bottom:'50%', transform:`rotate(${-angleL1}deg)`}"></div>
          <div class="rounded-full bg-green-500/40 transition-all"
               :style="{width:`${rLeft1*2}px`, height:`${rLeft1*2}px`}"></div>
        </div>
        <p class="mb-3 font-mono">|1⟩</p>
        
  <div class="bg-white/5 p-2.5 rounded-lg flex flex-col gap-2.5 w-full border border-white/10">
          <div class="flex items-center justify-between gap-3">
            <span class="text-[10px] text-green-300 font-mono font-bold tracking-widest">AMP</span>
            <input type="range" :min="0" :max="R" v-model.number="rLeft1" @input="updateRLeft1" class="accent-green-400 w-20 h-1.5 cursor-pointer"/>
          </div>
          <div class="flex items-center justify-between gap-3">
            <span class="text-[10px] text-gray-300 font-mono font-bold tracking-widest">PHS</span>
            <input type="range" :min="0" :max="360" v-model.number="angleL1" class="accent-white w-20 h-1.5 cursor-pointer"/>
          </div>
        </div>
      </div>

  </div>
  </div>

  <div class="p-4 border border-white/20 rounded-2xl bg-black/40 shadow-lg">
    <p class="font-semibold mb-3 text-center text-gray-200">After H Gate</p>
    <div class="flex gap-8 h-full">
      
  <div class="flex flex-col items-center">
        <div class="relative rounded-full border-2 border-white/60 flex justify-center items-center mb-2"
             :style="{width: `${R*2}px`, height: `${R*2}px`}">
          <div v-if="afterH.r0 > 0.1" class="absolute bg-white origin-bottom"
               :style="{width:'2px', height:`${R}px`, bottom:'50%', transform:`rotate(${-afterH.angle0}deg)`}"></div>
          <div class="rounded-full bg-blue-500/40 transition-all duration-300"
               :style="{width:`${afterH.r0*2}px`, height:`${afterH.r0*2}px`}"></div>
        </div>
        <p class="mb-3 font-mono">|0⟩</p>
      </div>

  <div class="flex flex-col items-center">
        <div class="relative rounded-full border-2 border-white/60 flex justify-center items-center mb-2"
             :style="{width: `${R*2}px`, height: `${R*2}px`}">
          <div v-if="afterH.r1 > 0.1" class="absolute bg-white origin-bottom"
               :style="{width:'2px', height:`${R}px`, bottom:'50%', transform:`rotate(${-afterH.angle1}deg)`}"></div>
          <div class="rounded-full bg-green-500/40 transition-all duration-300"
               :style="{width:`${afterH.r1*2}px`, height:`${afterH.r1*2}px`}"></div>
        </div>
        <p class="mb-3 font-mono">|1⟩</p>
      </div>

  </div>
  </div>
</div>

---
transition: fade-out
---
# Single-qubit operation example
Visualizing quantum gate operations with circle notation
<div style="position:relative;padding-bottom:56.25%;">
    <iframe
        style="width:80%;height:80%;position:absolute;left:0px;top:0px;"
        frameborder="0"
        width="100%"
        height="100%"
        allowfullscreen
        allow="autoplay"
        src="OneQubit.html">
    </iframe>
</div>

---
transition: fade-out
---
# Programming Exercise 1
Explaining what Quantum Computing is.

Quantum Programming $\approx$ Creating Quantum Circuits = Applying Matrices.

Why $\approx$?
- Optimization for efficient operation of the created circuit.
- Necessary operations to embed the created circuit into real quantum hardware.
- And so on...

Additional operations are required. We will see how these actually work in the code.

Here we will explain:
- Installing packages in Python and gate operations for a single qubit.

<div class="flex justify-center mt-8">
  <a href="https://colab.research.google.com/drive/1VvDoc-MyGpXBViZbSH2sfs8x3AsK0ood?usp=sharing"
     target="_blank" rel="noopener"
     class="inline-flex items-center gap-3 px-4 py-2 rounded-lg bg-[#4285F4] hover:bg-[#357ae8] text-white font-medium shadow-md">
    <svg width="20" height="20" viewBox="0 0 24 24" fill="none" aria-hidden>
      <path d="M12 2L22 7v10l-10 5-10-5V7z" fill="white" opacity="0.12"/>
      <path d="M12 2l10 5-10 5-10-5z" fill="white"/>
    </svg>
    Open in Colab
  </a>
 </div>

---
transition: none
---

# Quantum Circuit

<div class="mt-1 px-8">

  <div class="flex flex-col items-center justify-center mb-3">
    <img src="/images/Unknown.png" 
         alt="Quantum Circuit Diagram" 
         class="rounded-xl shadow-lg h-64 object-contain border border-gray-700 bg-white p-4" />
  </div>

  <p class="text-lg text-gray-300 leading-snug mb-3">
    So far, we've learned how gates acting on a single qubit work. Now, what else do we need to fully understand this quantum circuit...?
  </p>
</div>

---
transition: fade-out
---

# Quantum Circuit

<div class="mt-1 px-8">

  <div class="flex flex-col items-center justify-center mb-3">
    <img src="/images/Unknown-1.jpg" 
         alt="Quantum Circuit Diagram" 
         class="rounded-xl shadow-lg h-64 object-contain border border-gray-700 bg-white p-4" />
  </div>

  <p class="text-lg text-gray-300 leading-snug mb-3">
    So far, we've learned how gates acting on a single qubit work. Now, what else do we need to fully understand this quantum circuit...?
  </p>

  <div class="flex justify-center mb-4">
  <div class="bg-red-900/40 border-2 border-red-400 rounded-xl px-8 py-3 shadow-[0_0_20px_rgba(96,165,250,0.4)]">
    <p class="text-center text-2xl text-white font-bold tracking-wide m-0">
      Understanding the gates that span across these two qubits!
    </p>
  </div>
</div>
</div>



---
transition: fade-out
---
# Two Qubit Calculation

<div class="mt-10 text-xl text-gray-100">
  In a 2-qubit system, the following four states can be defined:
</div>

<div class="my-8 text-2xl">

$$
\ket{00},\quad \ket{01},\quad \ket{10},\quad \ket{11}
$$

</div>

<div class="mt-10 text-xl text-gray-100">
  In this case,
</div>

<div class="my-8 text-2xl">

$$
\ket{\underbrace{0}_{1st\ Qubit}\quad \underbrace{0}_{0th\ Qubit}}
$$

</div>

<div class="mt-10 text-xl text-gray-100">
  By doing this, we can apply specific gates only to the 0th or 1st qubit.
</div>

---
transition: fade-out
---
# Two-qubit operation example 1 
Understanding operations via Circle Notation.

<div style="position:relative;padding-bottom:56.25%;">
    <iframe
        style="width:80%;height:80%;position:absolute;left:0px;top:0px;"
        frameborder="0"
        width="100%"
        height="100%"
        allowfullscreen
        allow="autoplay"
        src="TwoQubit.html">
    </iframe>
</div>

---
transition: fade-out
---
# Two Qubit Calculation


<div class="mt-8 text-xl text-gray-100 leading-relaxed">

<span class="font-bold text-2xl text-white border-b-2 border-yellow-400 pb-1">There are operations that span two qubits, not just individual operations.</span>

<div class="mt-8 text-xl text-gray-100">
The most important of these is the <strong class="text-blue-400">CX Gate</strong>.
</div>

</div> <div class="mt-8 p-6 bg-gray-800/50 border border-gray-600 rounded-xl shadow-lg">

<h3 class="text-2xl font-bold text-white mb-3 mt-0">CX (also called CNOT)</h3>

This gate applies an $X$ gate to the $q_1$-th bit if the $q_0$-th qubit is 1.

Here, $q_0$ is called the **Control Qubit** and $q_1$ is called the **Target Qubit**.

<div class="mt-6 mb-2 text-xl">

$$
\mathrm{CX}\ket{00} = \ket{00}, \quad \mathrm{CX}\ket{01} = \ket{11}, \quad \mathrm{CX}\ket{10} = \ket{10}, \quad \mathrm{CX}\ket{11} = \ket{01}
$$

</div>

</div>

---
transition: fade-out
---
# Two-qubit operation example 2
Understanding operations via Circle Notation.

<div style="position:relative;padding-bottom:56.25%;">
    <iframe
        style="width:80%;height:80%;position:absolute;left:0px;top:0px;"
        frameborder="0"
        width="100%"
        height="100%"
        allowfullscreen
        allow="autoplay"
        src="TwoQubit_cx1.html">
    </iframe>
</div>
---
transition: fade-out
---
# Two-qubit operation example 3
Understanding operations via Circle Notation.

<div style="position:relative;padding-bottom:56.25%;">
    <iframe
        style="width:80%;height:80%;position:absolute;left:0px;top:0px;"
        frameborder="0"
        width="100%"
        height="100%"
        allowfullscreen
        allow="autoplay"
        src="TwoQubit_cx2.html">
    </iframe>
</div>

---
transition: fade-out
---

# Programming Exercise 2
Hands-on exercise using the provided materials.

Based on the knowledge we've learned so far, we will learn about 2-qubit operations.

<div class="flex justify-center mt-8">
  <a href="https://colab.research.google.com/drive/1VvDoc-MyGpXBViZbSH2sfs8x3AsK0ood?usp=sharing"
     target="_blank" rel="noopener"
     class="inline-flex items-center gap-3 px-4 py-2 rounded-lg bg-[#4285F4] hover:bg-[#357ae8] text-white font-medium shadow-md">
    <svg width="20" height="20" viewBox="0 0 24 24" fill="none" aria-hidden>
      <path d="M12 2L22 7v10l-10 5-10-5V7z" fill="white" opacity="0.12"/>
      <path d="M12 2l10 5-10 5-10-5z" fill="white"/>
    </svg>
    Open in Colab
  </a>
</div>

---
transition: fade-out
---
# Summary of Part 2

<div class="mt-8 grid grid-cols-2 gap-6">

  <div class="p-5 bg-gray-800/50 border border-gray-600 rounded-xl shadow-lg border-t-4 border-t-blue-500">
    <h3 class="text-xl font-bold text-blue-400 mb-3 mt-0">Computing with Quantum means:</h3>
    <div class="text-lg text-gray-100 mt-4">
      <span class="font-bold border-b-2 border-blue-400 pb-1">Applying gates to encoded qubits.</span>
    </div>
  </div>

  <div class="p-5 bg-gray-800/50 border border-gray-600 rounded-xl shadow-lg border-t-4 border-t-purple-500">
    <h3 class="text-xl font-bold text-purple-400 mb-2 mt-0">What is Qiskit?</h3>
    <div class="text-base text-gray-200 leading-relaxed">
      A tool that not only creates quantum circuits but also provides everything needed to <strong class="text-white">simulate and connect to actual quantum computers</strong>.
    </div>
  </div>

</div>

<div class="mt-10 p-5 bg-gradient-to-r from-blue-900/50 to-purple-900/50 border border-blue-500/50 rounded-lg text-center shadow-[0_0_20px_rgba(59,130,246,0.3)]">
  
  <div class="text-xl text-white font-bold tracking-wide">
    On Day 2, we will use what we learned today to explain actual <span class="text-yellow-400 text-2xl">Quantum Algorithms!!</span>
  </div>
  
  <div class="text-base text-gray-300 mt-2">
    We hope to see you there!! 🎉
  </div>

</div>

---
transition: slide-left
---

# Part ３: Invited Talk

<div class="flex justify-center mt-4">
  <div class="w-full max-w-5xl h-[400px] bg-[#222222] rounded-2xl overflow-hidden shadow-2xl border border-gray-600">
    <div class="h-full flex flex-col justify-between p-12">
      <div>
        <h3 class="text-4xl font-bold text-white mb-6">Dr. Juha Vartiainen</h3>
        <p class="text-xl text-gray-300 leading-relaxed">
          Dr. Juha Vartiainen, a co-founder of IQM Quantum Computers, will share a message for everyone who hopes to apply quantum technologies to real-world problems and everyday life.
        </p>
        <p class="text-lg text-gray-400 mt-8 font-medium">Moderator: Taiga Suzuki</p>
      </div>
    </div>
  </div>
</div>

---
transition: slide-left
---
# Part 4: Group work

1. Please gather with the same group members. The group members will be fixed during three days.

2. (Introductions) Let’s introduce ourselves first!
-> Share your university, major/field, where you’re from, etc.

3. (Small talk) Let’s chat—what’s something interesting or funny that happened to you recently?

4. (Reflection) Did you have any takeaways or discoveries from today’s lecture or hands-on session?

5. (Teaser for Day 2 and beyond) Have you had any annoying coordination or scheduling issues lately—something that was a hassle to arrange?