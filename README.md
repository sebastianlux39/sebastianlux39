<!DOCTYPE html>

<html class="light" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Dynamic Presentation Page</title>
<!-- Google Fonts -->
<link href="https://fonts.googleapis.com" rel="preconnect"/>
<link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect"/>
<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&amp;display=swap" rel="stylesheet"/>
<!-- Material Symbols -->
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<!-- Tailwind CSS -->
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<!-- Theme Configuration -->
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
            extend: {
                colors: {
                "primary": "#135bec",
                "background-light": "#f6f6f8",
                "background-dark": "#101622",
                },
                fontFamily: {
                "display": ["Plus Jakarta Sans", "sans-serif"]
                },
                borderRadius: {"DEFAULT": "1rem", "lg": "2rem", "xl": "3rem", "full": "9999px"},
                animation: {
                    'pulse-slow': 'pulse 3s cubic-bezier(0.4, 0, 0.6, 1) infinite',
                }
            },
            },
        }
    </script>
<style>
        /* Custom scrollbar hiding for clean UI */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }
        .glass-panel {
            background: rgba(255, 255, 255, 0.7);
            backdrop-filter: blur(12px);
            -webkit-backdrop-filter: blur(12px);
            border: 1px solid rgba(255, 255, 255, 0.5);
        }
        .dark .glass-panel {
            background: rgba(16, 22, 34, 0.7);
            border: 1px solid rgba(255, 255, 255, 0.05);
        }
    </style>
<style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
  </head>
<body class="bg-background-light dark:bg-background-dark text-[#111318] dark:text-white font-display overflow-x-hidden antialiased selection:bg-primary selection:text-white">
<div class="relative flex h-auto min-h-screen w-full flex-col mx-auto max-w-md bg-background-light dark:bg-background-dark shadow-2xl">
<!-- Background Gradient Decor -->
<div class="fixed top-0 left-0 w-full h-[500px] bg-gradient-to-b from-primary/10 to-transparent pointer-events-none z-0"></div>
<!-- Header / Profile Section -->
<div class="relative z-10 pt-12 pb-6 px-4 flex flex-col items-center">
<div class="relative group cursor-pointer">
<!-- Avatar Pulse/Glow Effect -->
<div class="absolute inset-0 rounded-full bg-primary/30 blur-xl group-hover:bg-primary/50 transition-all duration-500 animate-pulse-slow"></div>
<!-- Avatar Image -->
<div class="relative bg-center bg-no-repeat bg-cover rounded-full h-32 w-32 shadow-xl ring-4 ring-white dark:ring-[#101622]" data-alt="Modern geometric avatar with blue gradients" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuCdnTvWBolgqVo52qmL4LwOycv9nn176Vs1i8L_2MI-lplCDPe67HjBYlqKySP-9ISAw4B68OqoYhEidQTDD0HzcAMSEpirXoh2uDonW4oxqZGLQx7IzTqHBtkQkdrgfi8l0c44u9wM3H28lZAH4EocFgoWNz-pmYraZjVhmb7SAIO_A-q3aaa6l0iqca6nNiU7VnmJJdtWTQJ4k42hyUloIeYkBvD3Fsq9Lzc4dnwfJYZhTaqBJ997OtUv5x0OcoKvCH_gjsSnHB8");'>
</div>
<!-- Status Indicator -->
<div class="absolute bottom-2 right-2 h-6 w-6 rounded-full bg-green-500 border-4 border-white dark:border-[#101622] flex items-center justify-center">
<span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-green-400 opacity-75"></span>
</div>
</div>
<div class="mt-5 text-center flex flex-col items-center gap-1">
<div class="flex items-center gap-2">
<h1 class="text-3xl font-extrabold tracking-tight text-[#111318] dark:text-white">Lumina Studio</h1>
<span class="material-symbols-outlined text-blue-500 filled text-[20px]" style="font-variation-settings: 'FILL' 1;">verified</span>
</div>
<p class="text-slate-500 dark:text-slate-400 text-base font-medium">Digital Art &amp; Interactive Experiences</p>
<div class="mt-2 inline-flex items-center gap-1 px-3 py-1 rounded-full bg-slate-100 dark:bg-slate-800 text-xs font-semibold text-slate-600 dark:text-slate-300">
<span class="material-symbols-outlined text-[14px]">location_on</span>
<span>San Francisco, CA</span>
</div>
</div>
</div>
<!-- Social Orbit -->
<div class="relative z-10 px-6 py-4">
<div class="flex items-center justify-center gap-4">
<a class="group flex h-14 w-14 items-center justify-center rounded-full bg-white dark:bg-[#1a2230] shadow-sm hover:shadow-md hover:-translate-y-1 transition-all duration-300 ring-1 ring-slate-100 dark:ring-slate-800" href="#">
<span class="material-symbols-outlined text-2xl text-[#111318] dark:text-white group-hover:text-pink-500 transition-colors">photo_camera</span>
</a>
<a class="group flex h-14 w-14 items-center justify-center rounded-full bg-white dark:bg-[#1a2230] shadow-sm hover:shadow-md hover:-translate-y-1 transition-all duration-300 ring-1 ring-slate-100 dark:ring-slate-800" href="#">
<span class="material-symbols-outlined text-2xl text-[#111318] dark:text-white group-hover:text-black dark:group-hover:text-white transition-colors">music_note</span>
</a>
<a class="group flex h-14 w-14 items-center justify-center rounded-full bg-white dark:bg-[#1a2230] shadow-sm hover:shadow-md hover:-translate-y-1 transition-all duration-300 ring-1 ring-slate-100 dark:ring-slate-800" href="#">
<span class="material-symbols-outlined text-2xl text-[#111318] dark:text-white group-hover:text-red-500 transition-colors">smart_display</span>
</a>
<a class="group flex h-14 w-14 items-center justify-center rounded-full bg-white dark:bg-[#1a2230] shadow-sm hover:shadow-md hover:-translate-y-1 transition-all duration-300 ring-1 ring-slate-100 dark:ring-slate-800" href="#">
<span class="material-symbols-outlined text-2xl text-[#111318] dark:text-white group-hover:text-blue-400 transition-colors">alternate_email</span>
</a>
</div>
</div>
<!-- Beacon Section (Highlights) -->
<div class="relative z-10 flex flex-col gap-4 mt-4 pb-2">
<div class="px-6 flex items-center justify-between">
<h2 class="text-xl font-bold text-[#111318] dark:text-white">Featured Beacons</h2>
<span class="text-primary text-sm font-semibold cursor-pointer">View all</span>
</div>
<!-- Main Interactive Card -->
<div class="px-4">
<div class="group relative overflow-hidden rounded-[2rem] bg-white dark:bg-[#1a2230] shadow-lg hover:shadow-xl transition-all duration-500">
<!-- Image -->
<div class="aspect-[4/3] w-full bg-cover bg-center transition-transform duration-700 group-hover:scale-105" data-alt="Abstract neon blue and purple fluid 3d shapes" style='background-image: linear-gradient(0deg, rgba(0, 0, 0, 0.7) 0%, rgba(0, 0, 0, 0) 60%), url("https://lh3.googleusercontent.com/aida-public/AB6AXuAwGgrMOEr6MH44BvDI78pSAJ2xO_FoBRDIGJ2xlqUf2AV8SfTgznh_XgROd5WUS5MlpuEnG6v8vSaBY8QfXtqgDEIzRAAiptGDQPibvffRAb20abvFOw85gYuaffYx9RWI7BP1gNfJPyZngXHY_-8Fj0dCJcU5tNbEJeFZaernot0G6GjrJsnuBDb2BEdOPmgTaq2XxXWeSHpy2RBfnhKBL1XplTjQgLylIZMSj_ztkuulMJhutSyMBAjmU9t2hoe_6JcD5cLrZx0");'>
</div>
<!-- Content Overlay -->
<div class="absolute bottom-0 left-0 w-full p-6 flex flex-col gap-1 items-start">
<div class="mb-2 flex items-center gap-2 rounded-full bg-white/20 px-3 py-1 backdrop-blur-md">
<span class="block h-2 w-2 rounded-full bg-green-400 animate-pulse"></span>
<span class="text-xs font-bold text-white uppercase tracking-wider">Live Now</span>
</div>
<h3 class="text-2xl font-bold text-white leading-tight">Summer Digital Expo</h3>
<p class="text-white/80 text-sm line-clamp-2">Experience the future of digital art in our immersive online gallery.</p>
<!-- Interactive Button on Card -->
<button class="mt-4 w-full flex items-center justify-between rounded-full bg-white text-[#111318] px-5 py-3 text-sm font-bold shadow-lg active:scale-95 transition-transform">
<span>Enter Experience</span>
<span class="material-symbols-outlined text-[20px]">arrow_forward</span>
</button>
</div>
</div>
</div>
<!-- Stacked Action Buttons -->
<div class="px-4 flex flex-col gap-3">
<!-- Primary Action -->
<button class="relative w-full overflow-hidden rounded-full bg-primary p-[2px] active:scale-[0.98] transition-transform">
<div class="relative flex h-14 w-full items-center justify-center gap-2 rounded-full bg-primary px-6 transition-all hover:bg-primary/90">
<span class="material-symbols-outlined text-white">shopping_bag</span>
<span class="text-base font-bold text-white">Shop Limited Drops</span>
</div>
</button>
<!-- Secondary Action -->
<button class="flex w-full h-14 items-center justify-between rounded-full bg-white dark:bg-[#1a2230] border border-slate-200 dark:border-slate-700 px-6 active:scale-[0.98] transition-transform shadow-sm hover:border-primary/50">
<div class="flex items-center gap-3">
<div class="flex h-8 w-8 items-center justify-center rounded-full bg-purple-100 text-purple-600 dark:bg-purple-900/30 dark:text-purple-300">
<span class="material-symbols-outlined text-[18px]">article</span>
</div>
<span class="font-semibold text-[#111318] dark:text-white">Read our Manifesto</span>
</div>
<span class="material-symbols-outlined text-slate-400">chevron_right</span>
</button>
<!-- Tertiary Action -->
<button class="flex w-full h-14 items-center justify-between rounded-full bg-white dark:bg-[#1a2230] border border-slate-200 dark:border-slate-700 px-6 active:scale-[0.98] transition-transform shadow-sm hover:border-primary/50">
<div class="flex items-center gap-3">
<div class="flex h-8 w-8 items-center justify-center rounded-full bg-orange-100 text-orange-600 dark:bg-orange-900/30 dark:text-orange-300">
<span class="material-symbols-outlined text-[18px]">mail</span>
</div>
<span class="font-semibold text-[#111318] dark:text-white">Subscribe to Newsletter</span>
</div>
<span class="material-symbols-outlined text-slate-400">chevron_right</span>
</button>
</div>
</div>
<!-- Horizontal Media Widget -->
<div class="relative z-10 py-6">
<h3 class="px-6 text-xl font-bold text-[#111318] dark:text-white mb-4">Latest Shots</h3>
<div class="flex overflow-x-auto gap-4 px-6 pb-4 no-scrollbar snap-x snap-mandatory">
<!-- Item 1 -->
<div class="snap-center shrink-0 w-64 rounded-2xl overflow-hidden relative aspect-[3/4] group">
<div class="absolute inset-0 bg-cover bg-center transition-transform duration-500 group-hover:scale-110" data-alt="Fashion model in neon lighting wearing futuristic glasses" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuCqta1W9Ro33KGLPF8LXAZqmFEC9qwwcPpRYnH3bn6bQYDZDlNrWoFBK27wHFLZrgAkpAlggm1ZVciy33JrdjHem90OEUOsrjLez1kAlPz0e9YbPQObe3wPPO-SQyjbO7nj6pmWtrsMiYA1HiDnvF-a9mfhhd8tCbx3AF3Bn4-T1SfatboCpkJTUkU02ezYQaqPGdEolg54CkvlHRFGbW6VscUWzGnt_XGl1INaewbWc_mwKDMYshq5wbbS92Meb-ZFchN0NV0j0g4");'>
</div>
<div class="absolute inset-0 bg-gradient-to-t from-black/80 via-transparent to-transparent opacity-90"></div>
<div class="absolute bottom-4 left-4 right-4">
<span class="text-xs font-medium text-white/80 uppercase">Concept</span>
<p class="text-white font-bold leading-tight">Neon Nights Vol. 2</p>
</div>
</div>
<!-- Item 2 -->
<div class="snap-center shrink-0 w-64 rounded-2xl overflow-hidden relative aspect-[3/4] group">
<div class="absolute inset-0 bg-cover bg-center transition-transform duration-500 group-hover:scale-110" data-alt="Abstract 3D rendered shapes in blue and pink" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuDWcY7leOquMrWe4NHmvbaaiCo2PJA01XOs0EQd_bi7SGyTMqKM76jGewlvVvcmcp6bW5zmmuKeE8nPfEVFvqnRQWflnPXQMbMjPtKbi1F6qlyG7BigHSp7IdYOdEeNqJ_bOKnqkV3cYktaY6ZfhPt-OOBYpF342lZNXeBJuztN9-eSFyskgCJ0jLf6hKB6iVtIMDnO6o-W3K2b7l9ogwbC7fGLH2SoZdcgNSsGO4xPLryU2sjYDtwYxNOx3Xyg2kA2aGJYvG8yeYw");'>
</div>
<div class="absolute inset-0 bg-gradient-to-t from-black/80 via-transparent to-transparent opacity-90"></div>
<div class="absolute bottom-4 left-4 right-4">
<span class="text-xs font-medium text-white/80 uppercase">Design</span>
<p class="text-white font-bold leading-tight">Fluid Dynamics</p>
</div>
</div>
<!-- Item 3 -->
<div class="snap-center shrink-0 w-64 rounded-2xl overflow-hidden relative aspect-[3/4] group">
<div class="absolute inset-0 bg-cover bg-center transition-transform duration-500 group-hover:scale-110" data-alt="Minimalist architectural details with harsh shadows" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuA94TYwbPuMYZ4P-KcozSlQ_PYTsZ6O4LE6szulEWHOpdjmQIAPqBRDTyPQuvsdDDQCP8pBsc24nH0Lqc_9vlqK6VCyYUd0Jgw-RlGx36p40WePS5a6Om62O8RWc6EuV8E6A2gO1FfzfLPhDxhc_9nbujrWl3nhvxrX1i39El_o3NvwOTZTrPmpOo66mc6lzWcyRu38buGPU5TcCgElKkBM5jU8fVKjEVC1XTjVERcltqbUyiWGtU6QpUACnrajpcSpH6wmhYJNjiM");'>
</div>
<div class="absolute inset-0 bg-gradient-to-t from-black/80 via-transparent to-transparent opacity-90"></div>
<div class="absolute bottom-4 left-4 right-4">
<span class="text-xs font-medium text-white/80 uppercase">Architecture</span>
<p class="text-white font-bold leading-tight">Modern Living</p>
</div>
</div>
</div>
</div>
<!-- Footer -->
<div class="h-24 flex items-center justify-center opacity-50 pb-safe">
<p class="text-sm font-medium">Lumina Studio © 2024</p>
</div>
<!-- Floating Action Button (FAB) -->
<div class="fixed bottom-6 right-6 z-50">
<button class="flex h-14 w-14 items-center justify-center rounded-full bg-[#111318] dark:bg-white text-white dark:text-[#111318] shadow-2xl shadow-primary/40 hover:scale-110 active:scale-95 transition-all duration-300">
<span class="material-symbols-outlined text-2xl">ios_share</span>
</button>
</div>
</div>
</body></html>
