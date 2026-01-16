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
</style>

<div class="text-center px-6 md:px-12 relative">

  <!-- QR icon above title -->
  <div class="mb-6">
    <svg 
      class="w-24 h-24 md:w-32 md:h-32 mx-auto text-purple-400 opacity-90"
      viewBox="0 0 24 24" 
      fill="none" 
      stroke="currentColor" 
      stroke-width="1.8"
    >
      <path d="M3 3h6v6H3zM15 3h6v6h-6zM3 15h6v6H3zM15 15h2v2h-2zM19 15h2v2h-2zM15 19h2v2h-2zM19 19h2v2h-2z"/>
      <path d="M7 7h2v2H7zM17 17h2v2h-2z"/>
    </svg>
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

<!-- Rest of your slides remain the same -->

<div class="flex flex-col items-center justify-center h-full">
  <div class="w-full max-w-5xl bg-black/30 backdrop-blur-sm rounded-2xl p-6 border border-white/10 shadow-2xl">
    <iframe 
      src="/drawio.html" 
      class="w-full aspect-[16/9] border-0 rounded-xl"
    ></iframe>
  </div>

</div>

---

<div class="flex items-center justify-center h-full">
  <div class="w-full max-w-5xl bg-black/30 backdrop-blur-sm rounded-2xl p-6 border border-white/10 shadow-2xl">
    <img 
      src="/fullpicture.png" 
      class="w-full rounded-xl border border-white/5 shadow-lg"
    />
  </div>
</div>

---

<div class="abs-br m-8 text-sm opacity-60">
  Raman • QR Payments • January 2026
</div>
