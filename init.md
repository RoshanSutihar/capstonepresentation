---
theme: default
class: h-screen flex flex-col items-center justify-center text-white
layout: cover
background: linear-gradient(to bottom, #0a0a1f, #120d2e, #1a133f, #0f0f1a)
---

<style>
html, body, #app, .slidev-layout {
  background: linear-gradient(to bottom, #0a0a1f, #120d2e, #1a133f, #0f0f1a) !important;
  background-attachment: fixed;
  color: #e0e0ff;
}

h1, .text-gradient {
  background: linear-gradient(90deg, #7c3aed, #c084fc, #ec4899, #a78bfa);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  filter: drop-shadow(0 2px 8px rgba(167, 139, 250, 0.5));
}

h1 {
  text-shadow: 0 0 30px rgba(192, 132, 252, 0.4);
}

/* Presenter info - smaller & cleaner */
.presenter-box {
  background: rgba(255,255,255,0.06);
  backdrop-filter: blur(8px);
  border: 1px solid rgba(255,255,255,0.08);
  padding: 0.4rem 0.9rem;
  border-radius: 1rem;
  font-size: 1.1rem;
}

/* Diagram container */
.diagram-container {
  width: 100%;
  height: 70vh;
  border-radius: 0.75rem;
  overflow: hidden;
  background: rgba(0, 0, 0, 0.3);
  border: 1px solid rgba(255, 255, 255, 0.1);
}
</style>

<div class="text-center px-6 md:px-12 relative">

  <!-- QR icon above title -->
  <div class="mb-6">
    <svg xmlns="http://www.w3.org/2000/svg"  class="w-24 h-24 md:w-32 md:h-32 mx-auto text-purple-400 opacity-90"
      viewBox="0 0 24 24" 
      fill="none" ><path fill="currentColor" d="M3 7q-.425 0-.712-.288T2 6V3q0-.425.288-.712T3 2h3q.425 0 .713.288T7 3t-.288.713T6 4H4v2q0 .425-.288.713T3 7m0 15q-.425 0-.712-.288T2 21v-3q0-.425.288-.712T3 17t.713.288T4 18v2h2q.425 0 .713.288T7 21t-.288.713T6 22zm15 0q-.425 0-.712-.288T17 21t.288-.712T18 20h2v-2q0-.425.288-.712T21 17t.713.288T22 18v3q0 .425-.288.713T21 22zm3-15q-.425 0-.712-.288T20 6V4h-2q-.425 0-.712-.288T17 3t.288-.712T18 2h3q.425 0 .713.288T22 3v3q0 .425-.288.713T21 7m-3.5 12v-1.5H19V19zm0-3v-1.5H19V16zM16 17.5V16h1.5v1.5zM14.5 19v-1.5H16V19zM13 17.5V16h1.5v1.5zm3-3V13h1.5v1.5zM14.5 16v-1.5H16V16zM13 14.5V13h1.5v1.5zm1-3.5q-.425 0-.712-.288T13 10V6q0-.425.288-.712T14 5h4q.425 0 .713.288T19 6v4q0 .425-.288.713T18 11zm-8 8q-.425 0-.712-.288T5 18v-4q0-.425.288-.712T6 13h4q.425 0 .713.288T11 14v4q0 .425-.288.713T10 19zm0-8q-.425 0-.712-.288T5 10V6q0-.425.288-.712T6 5h4q.425 0 .713.288T11 6v4q0 .425-.288.713T10 11zm0.5 6.5h3v-3h-3zm0-8h3v-3h-3zm8 0h3v-3h-3z"/></svg>
  </div>

  <h1 class="text-6xl md:text-8xl font-extrabold mb-6 text-gradient">
    QR Payments
  </h1>

  <p class="text-2xl md:text-3xl font-medium text-gray-300/90 mb-10">
    A low-cost payment ecosystem for merchants
  </p>

  <!-- Smaller presenter box -->
  <div class="presenter-box inline-block">
    <p class="text-purple-300/90 font-medium">
      Presented by Roshan Sutihar
    </p>
  </div>
</div>

---

<!-- This slide uses iframe instead -->
<div class="flex items-center justify-center h-full">
  <div class="w-full max-w-5xl bg-black/30 backdrop-blur-sm rounded-2xl p-6 border border-white/10 shadow-2xl">
    <iframe 
      src="/diagram.html" 
      class="w-full aspect-[16/9] border-0 rounded-xl"
      loading="eager"
    ></iframe>
  </div>
</div>

---

<div class="flex items-center justify-center h-full">
  <div class="w-full max-w-5xl bg-black/30 backdrop-blur-sm rounded-2xl p-6 border border-white/10 shadow-2xl">
    <img 
      src="./fullpicture.png" 
      class="w-full rounded-xl border border-white/5 shadow-lg"
    />
  </div>
</div>

---

<div class="abs-br m-8 text-sm opacity-60">
  Raman • QR Payments • January 2026
</div>
