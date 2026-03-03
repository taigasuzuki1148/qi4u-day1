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
/* Headings */
h1{ letter-spacing:-.02em; }
h2{ opacity:.9; margin-top:.35rem; }

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

<div class="lead">
On Day 2, you will identify a real-world problem, build an oracle using our oracle-building tool, and run it on both a simulator and IQM hardware. 

On Day 3, your group will give a short presentation (about 6 minutes).
</div>

<div class="spacer"></div>

<style>
.lead{
  max-width: 980px;
  margin: 0 auto;
  font-size: 1.35rem;
  line-height: 1.35;
  opacity: .95;
}
.spacer{
  height: 22vh; /* big bottom whitespace */
}
</style>
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
  width: min(980px, 92vw);
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
  width: min(1100px, 94vw);
  margin-left:auto;
  margin-right:auto;
  display:grid;
  grid-template-columns: repeat(5, minmax(0, 1fr));
  gap: .85rem;
}

.card{
  padding: .9rem .9rem;
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


2. Please do not share the materials URL with third parties.  
- It may include special access links (e.g., to quantum hardware).

3. Please be respectful of one another.  
- Participants come from diverse nationalities and backgrounds. If anything makes you uncomfortable, please contact the organizers.

4. Please be an active learner.  
- Keep in mind that over these three days you will work on developing your own application ideas, so listen with that goal in mind.

5. About Q&A  
- We are student organizers, not professors. We may not be able to answer very deep theoretical questions in quantum mechanics, but we can recommend appropriate resources and support your learning.


---
transition: slide-left
---
# Group work

1. (自己紹介)　まずはお互いのことを自己紹介しよう！
-> 大学・専攻・出身などなど

2. (雑談)　最近身の回りで起きた面白かったことなどを言い合おう！

3. (振り返り)　今日のレクチャーやハンズオンで何か発見はあった？

4. (Day2以降の伏線)　最近，身の回りで面倒な調整ごととかあった？