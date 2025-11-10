<!doctype html>

<html lang="bn">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>GitHub Profile — siamgit7777</title>
  <!-- Tailwind CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Font Awesome for icons (free) -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" integrity="sha512-pc6Y6X6Ygq2Kq9qjG1s5k3q1J7Zz0jXq3JY3p3lK1Z9c6e4zY4p3s2b1c0a9d8f7" crossorigin="anonymous" referrerpolicy="no-referrer" />
  <style>
    /* small custom styles */
    .glass { background: rgba(255,255,255,0.06); backdrop-filter: blur(6px); }
  </style>
</head>
<body class="min-h-screen bg-gradient-to-br from-gray-900 via-slate-900 to-gray-800 text-gray-100">
  <main class="max-w-3xl mx-auto p-6">
    <section class="glass rounded-2xl p-6 shadow-2xl border border-gray-800">
      <div class="flex items-center gap-4">
        <img src="https://avatars.githubusercontent.com/u/9919?s=200&v=4" alt="avatar" class="w-28 h-28 rounded-full ring-2 ring-indigo-500 object-cover" />
        <div>
          <h1 class="text-2xl font-bold"> Md Siam <span class="text-indigo-400">(GitHub Handle)</span></h1>
          <p class="mt-1 text-sm text-gray-300">I am Frontend Developer — HTML, CSS, Tailwind CSS, JavaScript । MS Word ও MS Excel-this is efficient।</p>
          <div class="mt-3 flex gap-2">
            <a href="#" class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-indigo-600/20 border border-indigo-600 hover:bg-indigo-600/30 transition"> <i class="fab fa-github"></i> GitHub</a>
            <a href="#" class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-sky-600/10 border border-sky-600 hover:bg-sky-600/20 transition"> <i class="fab fa-linkedin"></i> LinkedIn</a>
            <a href="#" class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-rose-600/10 border border-rose-600 hover:bg-rose-600/20 transition"> <i class="fas fa-envelope"></i> Email</a>
          </div>
        </div>
        <div class="ml-auto text-right">
          <button id="copyBtn" class="text-xs px-3 py-1 bg-gray-800/60 border border-gray-700 rounded-md">Copy markdown</button>
        </div>
      </div><!-- Skills -->
  <div class="mt-6">
    <h2 class="text-sm text-gray-300 uppercase">Skills</h2>
    <div class="mt-3 grid grid-cols-3 sm:grid-cols-6 gap-3">
      <div class="flex flex-col items-center p-3 bg-gray-800/30 rounded-lg">
        <i class="fab fa-html5 fa-2x text-orange-500"></i>
        <span class="text-xs mt-2">HTML</span>
      </div>
      <div class="flex flex-col items-center p-3 bg-gray-800/30 rounded-lg">
        <i class="fab fa-css3-alt fa-2x text-sky-400"></i>
        <span class="text-xs mt-2">CSS</span>
      </div>
      <div class="flex flex-col items-center p-3 bg-gray-800/30 rounded-lg">
        <i class="fab fa-js-square fa-2x text-yellow-400"></i>
        <span class="text-xs mt-2">JavaScript</span>
      </div>
      <div class="flex flex-col items-center p-3 bg-gray-800/30 rounded-lg">
        <svg xmlns="http://www.w3.org/2000/svg" class="w-9 h-9" viewBox="0 0 24 24" fill="none" stroke="currentColor"><path d="M3 12h18M3 6h18M3 18h18"/></svg>
        <span class="text-xs mt-2">Tailwind</span>
      </div>
      <div class="flex flex-col items-center p-3 bg-gray-800/30 rounded-lg">
        <i class="fas fa-file-word fa-2x"></i>
        <span class="text-xs mt-2">MS Word</span>
      </div>
      <div class="flex flex-col items-center p-3 bg-gray-800/30 rounded-lg">
        <i class="fas fa-file-excel fa-2x"></i>
        <span class="text-xs mt-2">MS Excel</span>
      </div>
    </div>
  </div>

 

 
</section>

  </main>  <script>
    // small helpers
    document.getElementById('year').textContent = new Date().getFullYear();

    const copyBtn = document.getElementById('copyBtn');
    copyBtn.addEventListener('click', () => {
      const md = # আপনার নাম (GitHub Handle)\n\nShort bio — HTML, CSS, Tailwind, JavaScript\n\n- 🔭 I’m currently working on: Project One\n- 🌱 I’m learning: Advanced Tailwind UI\n- 📫 How to reach me: you@example.com;
      navigator.clipboard.writeText(md).then(() => {
        copyBtn.textContent = 'Copied!';
        setTimeout(() => copyBtn.textContent = 'Copy markdown', 1500);
      }).catch(() => alert('Copy failed.'));
    });
  </script></body>
</html>
