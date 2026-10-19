<!DOCTYPE html>
<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Modul Pembelajaran Interaktif - Pendidikan Pancasila XI</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Plus Jakarta Sans', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            red: '#E53E3E',
                            darkRed: '#9B1C1C',
                            gold: '#D97706',
                            navy: '#0F172A',
                            slate: '#1E293B'
                        }
                    }
                }
            }
        }
    </script>
    <style>
        .glass-card {
            background: rgba(255, 255, 255, 0.9);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(226, 232, 240, 0.8);
        }
        .gradient-header {
            background: linear-gradient(135deg, #0F172A 0%, #1E293B 50%, #9B1C1C 100%);
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 font-sans antialiased selection:bg-red-500 selection:text-white min-h-screen flex flex-col">

    <!-- Navigation / Top Header -->
    <header class="sticky top-0 z-50 bg-white/80 backdrop-blur-md border-b border-slate-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-16 flex items-center justify-between">
            <div class="flex items-center space-x-3">
                <div class="w-10 h-10 rounded-xl bg-red-600 flex items-center justify-center text-white shadow-md shadow-red-200">
                    <i class="fa-solid me-0 fa-shield-halved text-xl"></i>
                </div>
                <div>
                    <span class="text-xs font-bold uppercase tracking-wider text-red-600 block">Modul Digital</span>
                    <h1 class="text-base font-bold text-slate-900 leading-tight">Pendidikan Pancasila</h1>
                </div>
            </div>
            <div class="flex items-center gap-2">
                <span class="inline-flex items-center px-3 py-1 rounded-full text-xs font-semibold bg-red-100 text-red-700 border border-red-200">
                    <i class="fa-solid fa-graduation-cap mr-1.5"></i> Kelas XI / Ganjil
                </span>
            </div>
        </div>
    </header>

    <main class="flex-grow max-w-7xl w-full mx-auto px-4 sm:px-6 lg:px-8 py-8 space-y-12">

        <!-- Hero Section -->
        <section class="gradient-header rounded-3xl p-6 sm:p-10 text-white shadow-2xl relative overflow-hidden">
            <div class="absolute -right-10 -bottom-10 opacity-10 pointer-events-none">
                <i class="fa-solid fa-award text-[280px]"></i>
            </div>
            <div class="relative z-10 max-w-3xl">
                <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-white/10 backdrop-blur-md text-amber-300 text-xs font-medium mb-4 border border-white/10">
                    <i class="fa-solid fa-earth-americas"></i> Unit Pembelajaran 2
                </div>
                <h2 class="text-2xl sm:text-4xl font-extrabold tracking-tight leading-tight text-white mb-4">
                    Pancasila sebagai Identitas Nasional di Era Global
                </h2>
                <p class="text-slate-300 text-sm sm:text-base leading-relaxed mb-6">
                    Menelusuri bagaimana nilai-nilai luhur bangsa tetap menjadi jangkar dan jati diri warga negara Indonesia di tengah derasnya arus globalisasi dan pertukaran budaya dunia.
                </p>
                <div class="flex flex-wrap gap-4 text-xs font-medium text-slate-200">
                    <div class="flex items-center gap-2 bg-white/10 px-3.5 py-2 rounded-xl backdrop-blur-sm">
                        <i class="fa-regular fa-clock text-amber-400"></i> Alokasi: 2x Pertemuan
                    </div>
                    <div class="flex items-center gap-2 bg-white/10 px-3.5 py-2 rounded-xl backdrop-blur-sm">
                        <i class="fa-solid fa-users text-amber-400"></i> Aktivitas: Kolaboratif Kelompok
                    </div>
                </div>
            </div>
        </section>

        <!-- Tujuan Pembelajaran -->
        <section class="space-y-4">
            <div class="flex items-center gap-3">
                <div class="w-2 h-8 bg-red-600 rounded-full"></div>
                <h3 class="text-xl font-bold text-slate-900">Tujuan Pembelajaran</h3>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                <div class="glass-card p-5 rounded-2xl border border-slate-200 shadow-sm hover:shadow-md transition-shadow flex gap-4 items-start">
                    <div class="w-10 h-10 rounded-xl bg-blue-50 text-blue-600 flex items-center justify-center shrink-0 font-bold">1</div>
                    <div>
                        <h4 class="font-bold text-slate-900 mb-1">Pemahaman & Analisis</h4>
                        <p class="text-sm text-slate-600 leading-relaxed">
                            Siswa mampu memahami konsep Pancasila sebagai identitas nasional dan menganalisis studi kasus benturan budaya secara kritis.
                        </p>
                    </div>
                </div>
                <div class="glass-card p-5 rounded-2xl border border-slate-200 shadow-sm hover:shadow-md transition-shadow flex gap-4 items-start">
                    <div class="w-10 h-10 rounded-xl bg-emerald-50 text-emerald-600 flex items-center justify-center shrink-0 font-bold">2</div>
                    <div>
                        <h4 class="font-bold text-slate-900 mb-1">Penerapan & Unjuk Gagasan</h4>
                        <p class="text-sm text-slate-600 leading-relaxed">
                            Siswa mampu menerapkan dan mengemukakan gagasan tentang bagaimana nilai-nilai Pancasila dapat dihidupkan dalam pergaulan global.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Pertanyaan Pemantik 1 -->
        <section class="bg-gradient-to-r from-amber-50 to-orange-50 rounded-2xl p-6 border border-amber-200 shadow-sm relative">
            <div class="flex items-start gap-4">
                <div class="w-12 h-12 rounded-2xl bg-amber-500 text-white flex items-center justify-center shrink-0 shadow-lg shadow-amber-200">
                    <i class="fa-solid fa-lightbulb text-xl"></i>
                </div>
                <div class="space-y-2">
                    <span class="text-xs font-bold uppercase tracking-wider text-amber-800">Pertanyaan Pemantik</span>
                    <h4 class="text-lg font-bold text-amber-950 leading-snug">
                        "Bagaimana kita, sebagai pelajar, bisa 'mengekspor' nilai Pancasila ke dunia internasional?"
                    </h4>
                    <p class="text-sm text-amber-800">
                        Pikirkan sejenak sebelum membaca materi ringkas di bawah. Apakah nilai lokal kita mampu bersaing dan memberi warna positif bagi dunia?
                    </p>
                </div>
            </div>
        </section>

        <!-- Materi Ringkas (Cards Interaktif) -->
        <section class="space-y-6">
            <div class="flex items-center justify-between">
                <div class="flex items-center gap-3">
                    <div class="w-2 h-8 bg-red-600 rounded-full"></div>
                    <h3 class="text-xl font-bold text-slate-900">Materi Ringkas</h3>
                </div>
                <span class="text-xs text-slate-500 font-medium"><i class="fa-regular fa-hand-pointer mr-1"></i> Klik kartu untuk membaca selengkapnya</span>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
                <!-- Card 1 -->
                <div class="bg-white rounded-2xl p-5 border border-slate-200 shadow-sm hover:shadow-md transition-all space-y-3 flex flex-col justify-between">
                    <div class="space-y-3">
                        <div class="w-10 h-10 rounded-xl bg-purple-100 text-purple-600 flex items-center justify-center">
                            <i class="fa-solid fa-passport text-lg"></i>
                        </div>
                        <h4 class="font-bold text-slate-900">1. Identitas Nasional</h4>
                        <p class="text-xs text-slate-600 leading-relaxed">
                            Jati diri unik yang membedakan Indonesia dengan bangsa lain. Berakar dari sejarah, kebudayaan, dan konsensus luhur Pancasila.
                        </p>
                    </div>
                    <button onclick="openModal('materi1')" class="w-full py-2 px-3 bg-slate-100 hover:bg-slate-200 text-slate-700 text-xs font-semibold rounded-xl transition-colors text-center">
                        Baca Rincian <i class="fa-solid fa-arrow-right ml-1"></i>
                    </button>
                </div>

                <!-- Card 2 -->
                <div class="bg-white rounded-2xl p-5 border border-slate-200 shadow-sm hover:shadow-md transition-all space-y-3 flex flex-col justify-between">
                    <div class="space-y-3">
                        <div class="w-10 h-10 rounded-xl bg-blue-100 text-blue-600 flex items-center justify-center">
                            <i class="fa-solid fa-globe text-lg"></i>
                        </div>
                        <h4 class="font-bold text-slate-900">2. Era Globalisasi</h4>
                        <p class="text-xs text-slate-600 leading-relaxed">
                            Dunia tanpa sekat di mana arus informasi, budaya, dan teknologi masuk secara masif. Membuka peluang sekaligus potensi disrupsi budaya lokal.
                        </p>
                    </div>
                    <button onclick="openModal('materi2')" class="w-full py-2 px-3 bg-slate-100 hover:bg-slate-200 text-slate-700 text-xs font-semibold rounded-xl transition-colors text-center">
                        Baca Rincian <i class="fa-solid fa-arrow-right ml-1"></i>
                    </button>
                </div>

                <!-- Card 3 -->
                <div class="bg-white rounded-2xl p-5 border border-slate-200 shadow-sm hover:shadow-md transition-all space-y-3 flex flex-col justify-between">
                    <div class="space-y-3">
                        <div class="w-10 h-10 rounded-xl bg-emerald-100 text-emerald-600 flex items-center justify-center">
                            <i class="fa-solid fa-filter text-lg"></i>
                        </div>
                        <h4 class="font-bold text-slate-900">3. Pancasila Filter</h4>
                        <p class="text-xs text-slate-600 leading-relaxed">
                            Pancasila berfungsi sebagai penyaring aktif: menerima budaya luar yang membangun (kemajuan IPTEK) dan menolak budaya yang bertentangan.
                        </p>
                    </div>
                    <button onclick="openModal('materi3')" class="w-full py-2 px-3 bg-slate-100 hover:bg-slate-200 text-slate-700 text-xs font-semibold rounded-xl transition-colors text-center">
                        Baca Rincian <i class="fa-solid fa-arrow-right ml-1"></i>
                    </button>
                </div>

                <!-- Card 4 -->
                <div class="bg-white rounded-2xl p-5 border border-slate-200 shadow-sm hover:shadow-md transition-all space-y-3 flex flex-col justify-between">
                    <div class="space-y-3">
                        <div class="w-10 h-10 rounded-xl bg-rose-100 text-rose-600 flex items-center justify-center">
                            <i class="fa-solid fa-paper-plane text-lg"></i>
                        </div>
                        <h4 class="font-bold text-slate-900">4. Warga Global</h4>
                        <p class="text-xs text-slate-600 leading-relaxed">
                            Generasi muda aktif berperan di kancah dunia (berpikir global) tanpa kehilangan akar kebudayaan nasionalnya (bertindak lokal).
                        </p>
                    </div>
                    <button onclick="openModal('materi4')" class="w-full py-2 px-3 bg-slate-100 hover:bg-slate-200 text-slate-700 text-xs font-semibold rounded-xl transition-colors text-center">
                        Baca Rincian <i class="fa-solid fa-arrow-right ml-1"></i>
                    </button>
                </div>
            </div>
        </section>

        <!-- Modals for Materials -->
        <div id="materiModal" class="fixed inset-0 bg-slate-900/60 backdrop-blur-sm z-50 hidden flex items-center justify-center p-4">
            <div class="bg-white rounded-3xl max-w-lg w-full p-6 space-y-4 shadow-2xl relative animate-fade-in">
                <button onclick="closeModal()" class="absolute top-4 right-4 w-8 h-8 rounded-full bg-slate-100 hover:bg-slate-200 text-slate-600 flex items-center justify-center">
                    <i class="fa-solid fa-xmark"></i>
                </button>
                <div id="modalContent"></div>
            </div>
        </div>

        <!-- Media Pembelajaran (YouTube Embed & Refleksi) -->
        <section class="space-y-6">
            <div class="flex items-center gap-3">
                <div class="w-2 h-8 bg-red-600 rounded-full"></div>
                <h3 class="text-xl font-bold text-slate-900">Media Pembelajaran</h3>
            </div>

            <div class="bg-white rounded-3xl p-4 sm:p-6 border border-slate-200 shadow-sm space-y-6">
                <!-- YouTube Video Responsive Embed -->
                <div class="relative w-full aspect-video rounded-2xl overflow-hidden bg-slate-900 shadow-md">
                    <iframe 
                        class="absolute top-0 left-0 w-full h-full border-0" 
                        src="https://www.youtube.com/embed/IA40qv8tSJY?si=fxD7jmqrJOKnkrQb" 
                        title="Pancasila sebagai Identitas Nasional di Era Global" 
                        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
                        referrerpolicy="strict-origin-when-cross-origin"
                        allowfullscreen>
                    </iframe>
                </div>

                <!-- Pertanyaan Refleksi Setelah Video -->
                <div class="bg-slate-900 text-white p-6 rounded-2xl space-y-4 relative overflow-hidden">
                    <div class="flex items-start gap-3">
                        <i class="fa-solid fa-circle-question text-red-500 text-2xl shrink-0 mt-0.5"></i>
                        <div class="space-y-2">
                            <h4 class="font-bold text-base text-slate-100">Pertanyaan Diskusi Reflektif Video:</h4>
                            <p class="text-sm text-slate-300 leading-relaxed">
                                "Suka budaya luar itu wajar, tapi kapan batasnya hingga kita kehilangan identitas sebagai orang Indonesia? Bagaimana Pancasila berfungsi sebagai penyaring (filter) budaya?"
                            </p>
                        </div>
                    </div>

                    <!-- Interactive Quick Note Widget -->
                    <div class="bg-slate-800/80 p-4 rounded-xl space-y-3 border border-slate-700">
                        <label class="block text-xs font-medium text-slate-300">Tuliskan Opini Singkatmu (Opsional):</label>
                        <textarea id="reflectionNote" rows="2" placeholder="Ketik pendapatmu di sini untuk didiskusikan bersama kelompok..." class="w-full bg-slate-900 border border-slate-700 rounded-lg p-3 text-xs text-white placeholder-slate-500 focus:outline-none focus:border-red-500 transition-colors"></textarea>
                        <div class="flex justify-between items-center">
                            <span id="saveStatus" class="text-[11px] text-emerald-400 opacity-0 transition-opacity"><i class="fa-solid fa-check mr-1"></i> Tersimpan di perangkat</span>
                            <button onclick="saveNote()" class="px-3 py-1.5 bg-red-600 hover:bg-red-700 text-white text-xs font-semibold rounded-lg transition-colors">
                                Simpan Catatan
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Langkah-Langkah Aktivitas Kelompok -->
        <section class="space-y-6">
            <div class="flex items-center justify-between">
                <div class="flex items-center gap-3">
                    <div class="w-2 h-8 bg-red-600 rounded-full"></div>
                    <h3 class="text-xl font-bold text-slate-900">Langkah Aktivitas Kelompok</h3>
                </div>
                <span class="inline-flex items-center px-3 py-1 rounded-full text-xs font-semibold bg-amber-100 text-amber-800">
                    <i class="fa-solid fa-users-viewfinder mr-1.5"></i> 4-5 Siswa / Kelompok
                </span>
            </div>

            <!-- Stepper Interactive Workflow -->
            <div class="bg-white rounded-3xl p-6 border border-slate-200 shadow-sm space-y-8">
                
                <!-- Step 1 -->
                <div class="flex flex-col sm:flex-row items-start gap-4 pb-6 border-b border-slate-100">
                    <div class="w-12 h-12 rounded-2xl bg-red-100 text-red-600 flex items-center justify-center font-bold text-lg shrink-0">
                        01
                    </div>
                    <div class="space-y-2 flex-grow">
                        <div class="flex items-center gap-2">
                            <span class="text-xs font-bold uppercase tracking-wider text-red-600">Langkah Pertama</span>
                            <span class="text-slate-300">•</span>
                            <span class="text-xs font-medium text-slate-500">Pencarian Kasus</span>
                        </div>
                        <h4 class="text-base font-bold text-slate-900">Penentuan Studi Kasus Interaksi Budaya</h4>
                        <p class="text-sm text-slate-600 leading-relaxed">
                            Cari <strong>satu studi kasus nyata</strong> yang berbeda antar kelompok terkait interaksi nilai lokal dan global (contoh: maraknya gaya hidup hedonisme/individualisme, tren K-Pop/cosplay vs budaya tradisional, isu kebebasan berpendapat di media sosial global).
                        </p>
                    </div>
                </div>

                <!-- Step 2 -->
                <div class="flex flex-col sm:flex-row items-start gap-4 pb-6 border-b border-slate-100">
                    <div class="w-12 h-12 rounded-2xl bg-amber-100 text-amber-700 flex items-center justify-center font-bold text-lg shrink-0">
                        02
                    </div>
                    <div class="space-y-2 flex-grow">
                        <div class="flex items-center gap-2">
                            <span class="text-xs font-bold uppercase tracking-wider text-amber-700">Langkah Kedua</span>
                            <span class="text-slate-300">•</span>
                            <span class="text-xs font-medium text-slate-500">Pembedahan 5 Sila</span>
                        </div>
                        <h4 class="text-base font-bold text-slate-900">Analisis Kacamata Pancasila</h4>
                        <p class="text-sm text-slate-600 leading-relaxed mb-3">
                            Bedah kasus tersebut dengan menganalisis dua hal utama:
                        </p>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3 text-xs">
                            <div class="bg-red-50 p-3 rounded-xl border border-red-100 text-red-900">
                                <strong><i class="fa-solid fa-triangle-exclamation mr-1 text-red-600"></i> Sila mana yang terancam luntur?</strong>
                                <p class="mt-1 text-slate-600">Identifikasi nilai sila mana yang terdegradasi akibat pengaruh kasus tersebut.</p>
                            </div>
                            <div class="bg-emerald-50 p-3 rounded-xl border border-emerald-100 text-emerald-900">
                                <strong><i class="fa-solid fa-shield-check mr-1 text-emerald-600"></i> Sila mana yang jadi solusi/filter?</strong>
                                <p class="mt-1 text-slate-600">Rumuskan sila yang menjadi fondasi jawaban dan penyaring dampak buruk.</p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Step 3 -->
                <div class="flex flex-col sm:flex-row items-start gap-4">
                    <div class="w-12 h-12 rounded-2xl bg-blue-100 text-blue-600 flex items-center justify-center font-bold text-lg shrink-0">
                        03
                    </div>
                    <div class="space-y-2 flex-grow">
                        <div class="flex items-center gap-2">
                            <span class="text-xs font-bold uppercase tracking-wider text-blue-600">Langkah Ketiga</span>
                            <span class="text-slate-300">•</span>
                            <span class="text-xs font-medium text-slate-500">Kreasi Konten Kampanye</span>
                        </div>
                        <h4 class="text-base font-bold text-slate-900">Pembuatan Produk Kampanye Digital</h4>
                        <p class="text-sm text-slate-600 leading-relaxed mb-3">
                            Buat satu produk kampanye digital sesuai minat kelompok yang menjawab tantangan: 
                            <span class="font-semibold text-slate-800 italic">"Bagaimana nilai-nilai Pancasila membentuk identitasmu sebagai warga negara global yang bangga akan Indonesia?"</span>
                        </p>
                        
                        <!-- Pilihan Format -->
                        <div class="grid grid-cols-1 md:grid-cols-3 gap-3 pt-2">
                            <div class="p-4 rounded-xl bg-slate-50 border border-slate-200 space-y-1">
                                <div class="flex items-center gap-2 text-rose-600 font-bold text-xs">
                                    <i class="fa-solid fa-video text-base"></i> Video Pendek
                                </div>
                                <p class="text-xs font-semibold text-slate-800">Reels / TikTok (Maks. 2 Menit)</p>
                                <p class="text-[11px] text-slate-500">Tingkat Kesulitan: Tinggi</p>
                            </div>

                            <div class="p-4 rounded-xl bg-slate-50 border border-slate-200 space-y-1">
                                <div class="flex items-center gap-2 text-blue-600 font-bold text-xs">
                                    <i class="fa-solid fa-newspaper text-base"></i> Esai Opini
                                </div>
                                <p class="text-xs font-semibold text-slate-800">Mading / Blog Sekolah</p>
                                <p class="text-[11px] text-slate-500">Tingkat Kesulitan: Sedang</p>
                            </div>

                            <div class="p-4 rounded-xl bg-slate-50 border border-slate-200 space-y-1">
                                <div class="flex items-center gap-2 text-emerald-600 font-bold text-xs">
                                    <i class="fa-solid fa-images text-base"></i> Infografis / Carousel
                                </div>
                                <p class="text-xs font-semibold text-slate-800">Post Instagram (Multi-slide)</p>
                                <p class="text-[11px] text-slate-500">Tingkat Kesulitan: Mudah</p>
                            </div>
                        </div>
                    </div>
                </div>

            </div>
        </section>

        <!-- Rubrik Penilaian -->
        <section class="space-y-6">
            <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-4">
                <div class="flex items-center gap-3">
                    <div class="w-2 h-8 bg-red-600 rounded-full"></div>
                    <div>
                        <h3 class="text-xl font-bold text-slate-900">Rubrik Penilaian Kelompok</h3>
                        <p class="text-xs text-slate-500">Pilih tab jenis karya untuk melihat kriteria rinci</p>
                    </div>
                </div>

                <!-- Tab Buttons -->
                <div class="flex rounded-xl bg-slate-200/80 p-1 space-x-1 self-start sm:self-auto text-xs font-bold">
                    <button onclick="switchTab('video')" id="tab-video" class="px-3 py-2 rounded-lg bg-white text-slate-900 shadow-sm transition-all">
                        Video Pendek
                    </button>
                    <button onclick="switchTab('esai')" id="tab-esai" class="px-3 py-2 rounded-lg text-slate-600 hover:text-slate-900 transition-all">
                        Esai Opini
                    </button>
                    <button onclick="switchTab('infografis')" id="tab-infografis" class="px-3 py-2 rounded-lg text-slate-600 hover:text-slate-900 transition-all">
                        Infografis / Carousel
                    </button>
                </div>
            </div>

            <!-- Tab 1: Video Pendek -->
            <div id="content-video" class="bg-white rounded-3xl border border-slate-200 shadow-sm overflow-hidden transition-all">
                <div class="p-5 bg-gradient-to-r from-rose-50 to-pink-50 border-b border-slate-200 flex items-center justify-between">
                    <div>
                        <span class="inline-block px-2.5 py-0.5 rounded-full text-[10px] font-bold bg-rose-200 text-rose-800 uppercase tracking-wider mb-1">Tingkat Tinggi</span>
                        <h4 class="font-bold text-slate-900">Rubrik Video Pendek (Reels / TikTok)</h4>
                    </div>
                    <i class="fa-solid fa-video text-2xl text-rose-500"></i>
                </div>
                <div class="overflow-x-auto">
                    <table class="w-full text-left text-xs">
                        <thead class="bg-slate-50 text-slate-700 uppercase font-bold border-b border-slate-200">
                            <tr>
                                <th class="p-4 w-1/4">Aspek</th>
                                <th class="p-4">Kriteria Kinerja (Skor 85 - 100)</th>
                                <th class="p-4 w-20 text-center">Bobot</th>
                            </tr>
                        </thead>
                        <tbody class="divide-y divide-slate-100 text-slate-600">
                            <tr class="hover:bg-slate-50">
                                <td class="p-4 font-bold text-slate-900">Kedalaman Materi</td>
                                <td class="p-4 leading-relaxed">Menyajikan analisis tajam bagaimana Pancasila menjadi identitas di era global. Menyertakan contoh konkret dan menyebutkan minimal 2 Sila yang relevan.</td>
                                <td class="p-4 text-center font-bold text-red-600">40%</td>
                            </tr>
                            <tr class="hover:bg-slate-50">
                                <td class="p-4 font-bold text-slate-900">Penyampaian (Public Speaking)</td>
                                <td class="p-4 leading-relaxed">Intonasi suara jelas, ekspresi meyakinkan, percaya diri, dan mampu mempersuasi audiens dengan bahasa tubuh yang baik.</td>
                                <td class="p-4 text-center font-bold text-red-600">25%</td>
                            </tr>
                            <tr class="hover:bg-slate-50">
                                <td class="p-4 font-bold text-slate-900">Kualitas Visual & Audio</td>
                                <td class="p-4 leading-relaxed">Pencahayaan baik, suara (audio) terdengar jernih (tidak bocor), editing rapi (transisi, penambahan teks penjelas/caption yang relevan).</td>
                                <td class="p-4 text-center font-bold text-red-600">20%</td>
                            </tr>
                            <tr class="hover:bg-slate-50">
                                <td class="p-4 font-bold text-slate-900">Orisinalitas & Kreativitas</td>
                                <td class="p-4 leading-relaxed">Konsep video sangat unik (misal: parodi tren global, storytelling yang emosional, atau roleplay).</td>
                                <td class="p-4 text-center font-bold text-red-600">15%</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
            </div>

            <!-- Tab 2: Esai Opini -->
            <div id="content-esai" class="bg-white rounded-3xl border border-slate-200 shadow-sm overflow-hidden hidden transition-all">
                <div class="p-5 bg-gradient-to-r from-blue-50 to-indigo-50 border-b border-slate-200 flex items-center justify-between">
                    <div>
                        <span class="inline-block px-2.5 py-0.5 rounded-full text-[10px] font-bold bg-blue-200 text-blue-800 uppercase tracking-wider mb-1">Tingkat Sedang</span>
                        <h4 class="font-bold text-slate-900">Rubrik Esai Opini (Mading / Blog)</h4>
                    </div>
                    <i class="fa-solid fa-newspaper text-2xl text-blue-500"></i>
                </div>
                <div class="overflow-x-auto">
                    <table class="w-full text-left text-xs">
                        <thead class="bg-slate-50 text-slate-700 uppercase font-bold border-b border-slate-200">
                            <tr>
                                <th class="p-4 w-1/4">Aspek</th>
                                <th class="p-4">Kriteria Kinerja (Skor 85 - 100)</th>
                                <th class="p-4 w-20 text-center">Bobot</th>
                            </tr>
                        </thead>
                        <tbody class="divide-y divide-slate-100 text-slate-600">
                            <tr class="hover:bg-slate-50">
                                <td class="p-4 font-bold text-slate-900">Kedalaman Materi & Argumen</td>
                                <td class="p-4 leading-relaxed">Argumen sangat kuat, kritis, dan logis. Menghubungkan teori Pancasila dengan realitas disrupsi global secara komprehensif.</td>
                                <td class="p-4 text-center font-bold text-blue-600">40%</td>
                            </tr>
                            <tr class="hover:bg-slate-50">
                                <td class="p-4 font-bold text-slate-900">
                                    Refleksi Personal
                                    <span class="inline-block bg-amber-100 text-amber-800 text-[10px] font-bold px-2 py-0.5 rounded mt-1">Anti-AI</span>
                                </td>
                                <td class="p-4 leading-relaxed"><strong>Wajib ada:</strong> Menceritakan pengalaman/kegelisahan pribadi siswa atau fenomena spesifik di lingkungan sekitarnya (sekolah/daerahnya) terkait budaya global.</td>
                                <td class="p-4 text-center font-bold text-blue-600">25%</td>
                            </tr>
                            <tr class="hover:bg-slate-50">
                                <td class="p-4 font-bold text-slate-900">Struktur & Sistematika</td>
                                <td class="p-4 leading-relaxed">Memiliki pendahuluan yang menarik, isi yang terstruktur rapi (per paragraf 1 ide pokok), dan kesimpulan yang kuat.</td>
                                <td class="p-4 text-center font-bold text-blue-600">20%</td>
                            </tr>
                            <tr class="hover:bg-slate-50">
                                <td class="p-4 font-bold text-slate-900">Tata Bahasa</td>
                                <td class="p-4 leading-relaxed">Menggunakan PUEBI dengan baik (jika formal) atau gaya bahasa populer yang tetap sopan, efektif, dan minim typo.</td>
                                <td class="p-4 text-center font-bold text-blue-600">15%</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
            </div>

            <!-- Tab 3: Infografis / Carousel -->
            <div id="content-infografis" class="bg-white rounded-3xl border border-slate-200 shadow-sm overflow-hidden hidden transition-all">
                <div class="p-5 bg-gradient-to-r from-emerald-50 to-teal-50 border-b border-slate-200 flex items-center justify-between">
                    <div>
                        <span class="inline-block px-2.5 py-0.5 rounded-full text-[10px] font-bold bg-emerald-200 text-emerald-800 uppercase tracking-wider mb-1">Tingkat Mudah</span>
                        <h4 class="font-bold text-slate-900">Rubrik Infografis / Carousel Instagram</h4>
                    </div>
                    <i class="fa-solid fa-images text-2xl text-emerald-500"></i>
                </div>

                <!-- Peringatan Guru Anti-AI -->
                <div class="mx-5 my-4 p-3.5 bg-red-50 border border-red-200 rounded-2xl flex items-center gap-3 text-red-800 text-xs font-semibold">
                    <i class="fa-solid fa-triangle-exclamation text-red-600 text-base shrink-0"></i>
                    <span>Catatan Guru: Siswa yang terdeteksi hanya "copy-paste" teks dari AI tanpa disaring ulang, nilai aspek orisinalitasnya langsung 0.</span>
                </div>

                <div class="overflow-x-auto">
                    <table class="w-full text-left text-xs">
                        <thead class="bg-slate-50 text-slate-700 uppercase font-bold border-b border-slate-200">
                            <tr>
                                <th class="p-4 w-1/4">Aspek</th>
                                <th class="p-4">Kriteria Kinerja (Skor 85 - 100)</th>
                                <th class="p-4 w-20 text-center">Bobot</th>
                            </tr>
                        </thead>
                        <tbody class="divide-y divide-slate-100 text-slate-600">
                            <tr class="hover:bg-slate-50">
                                <td class="p-4 font-bold text-slate-900">Kedalaman & Kepadatan Materi</td>
                                <td class="p-4 leading-relaxed">Informasi padat, tidak bertele-tele (bukan paragraf panjang, melainkan poin-poin). Analisis Pancasila vs Globalisasi tepat sasaran.</td>
                                <td class="p-4 text-center font-bold text-emerald-600">40%</td>
                            </tr>
                            <tr class="hover:bg-slate-50">
                                <td class="p-4 font-bold text-slate-900">Desain & Layout</td>
                                <td class="p-4 leading-relaxed">Hierarki visual jelas (judul besar, teks terbaca). Pemilihan warna tidak menyakitkan mata. Elemen desain mendukung informasi (bukan sekadar hiasan).</td>
                                <td class="p-4 text-center font-bold text-emerald-600">25%</td>
                            </tr>
                            <tr class="hover:bg-slate-50">
                                <td class="p-4 font-bold text-slate-900">
                                    Orisinalitas Visual
                                    <span class="inline-block bg-amber-100 text-amber-800 text-[10px] font-bold px-2 py-0.5 rounded mt-1">Anti-AI</span>
                                </td>
                                <td class="p-4 leading-relaxed"><strong>Wajib ada:</strong> Memodifikasi template secara signifikan, BUKAN sekadar ganti teks. Terdapat minimal 1 elemen visual asli/foto jepretan siswa sendiri yang mendukung konteks materi.</td>
                                <td class="p-4 text-center font-bold text-emerald-600">20%</td>
                            </tr>
                            <tr class="hover:bg-slate-50">
                                <td class="p-4 font-bold text-slate-900">Daya Persuasi & CTA</td>
                                <td class="p-4 leading-relaxed">Kalimat/slogan di dalam infografis sangat catchy (mudah diingat) dan berhasil mengajak pembaca mempertahankan identitas nasional.</td>
                                <td class="p-4 text-center font-bold text-emerald-600">15%</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
            </div>

            <!-- Skala Penilaian Umum 1-4 -->
            <div class="bg-white rounded-2xl p-5 border border-slate-200 space-y-3">
                <h4 class="text-xs font-bold uppercase tracking-wider text-slate-500">Panduan Konversi Skor Kuantiatif (1 - 4)</h4>
                <div class="grid grid-cols-2 sm:grid-cols-4 gap-3 text-xs">
                    <div class="p-3 rounded-xl bg-slate-50 border border-slate-100">
                        <span class="font-bold text-slate-900 block">Skor 4 (Sangat Baik)</span>
                        <span class="text-slate-500 text-[11px]">Nilai: 85 - 100</span>
                    </div>
                    <div class="p-3 rounded-xl bg-slate-50 border border-slate-100">
                        <span class="font-bold text-slate-900 block">Skor 3 (Baik)</span>
                        <span class="text-slate-500 text-[11px]">Nilai: 75 - 84</span>
                    </div>
                    <div class="p-3 rounded-xl bg-slate-50 border border-slate-100">
                        <span class="font-bold text-slate-900 block">Skor 2 (Cukup)</span>
                        <span class="text-slate-500 text-[11px]">Nilai: 65 - 74</span>
                    </div>
                    <div class="p-3 rounded-xl bg-slate-50 border border-slate-100">
                        <span class="font-bold text-slate-900 block">Skor 1 (Perlu Bimbingan)</span>
                        <span class="text-slate-500 text-[11px]">Nilai: &lt; 65</span>
                    </div>
                </div>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="bg-slate-900 text-slate-400 border-t border-slate-800 py-8 mt-12 text-center text-xs">
        <div class="max-w-7xl mx-auto px-4 space-y-2">
            <p class="font-semibold text-slate-300">Modul Pembelajaran Pendidikan Pancasila • Kelas XI Ganjil</p>
            <p class="text-slate-500">Dirancang untuk pembelajaran interaktif dan penguatan Profil Pelajar Pancasila.</p>
        </div>
    </footer>

    <script>
        // Modal Material Content Data
        const materiData = {
            materi1: {
                title: "1. Konsep Identitas Nasional",
                content: `
                    <p class="text-xs text-slate-600 leading-relaxed mb-3">
                        Identitas nasional adalah manifes nilai-nilai budaya yang tumbuh dan berkembang dalam aspek kehidupan suatu bangsa dengan ciri-ciri khas, yang membuatnya berbeda dengan bangsa lain.
                    </p>
                    <ul class="list-disc list-inside text-xs text-slate-600 space-y-1">
                        <li><strong>Unsur Pembentuk:</strong> Suku bangsa, agama, kebudayaan, dan bahasa daerah yang dipersatukan.</li>
                        <li><strong>Jangkar Identitas:</strong> Pancasila sebagai weltanschauung (pandangan hidup bangsa) dan dasar negara.</li>
                    </ul>
                `
            },
            materi2: {
                title: "2. Tantangan Era Globalisasi",
                content: `
                    <p class="text-xs text-slate-600 leading-relaxed mb-3">
                        Globalisasi membawa disrupsi berupa konsumerisme, individualisme, serta westernisasi yang berpotensi melunturkan nilai gotong royong dan kebersamaan.
                    </p>
                    <ul class="list-disc list-inside text-xs text-slate-600 space-y-1">
                        <li><strong>Peluang:</strong> Akses ilmu pengetahuan global dan kolaborasi internasional.</li>
                        <li><strong>Ancaman:</strong> Penyeragaman budaya (homogenisasi) yang menggerus keanekaragaman lokal.</li>
                    </ul>
                `
            },
            materi3: {
                title: "3. Pancasila sebagai Filter Budaya",
                content: `
                    <p class="text-xs text-slate-600 leading-relaxed mb-3">
                        Sebagai filter (penyaring), Pancasila bersifat terbuka namun kritis. Artinya, kita tidak menutup diri dari kemajuan luar, melainkan menyaringnya dengan 5 nilai Sila:
                    </p>
                    <ol class="list-decimal list-inside text-xs text-slate-600 space-y-1">
                        <li>Sila 1: Menolak budaya yang bertentangan dengan nilai keagamaan.</li>
                        <li>Sila 2: Menerima budaya humanis dan menghargai HAM.</li>
                        <li>Sila 3: Menjaga persatuan dan kebanggaan nasional.</li>
                        <li>Sila 4: Mengedepankan musyawarah dan keterbukaan rasional.</li>
                        <li>Sila 5: Memastikan keadilan sosial dan tidak konsumtif.</li>
                    </ol>
                `
            },
            materi4: {
                title: "4. Berperan sebagai Warga Global",
                content: `
                    <p class="text-xs text-slate-600 leading-relaxed mb-3">
                        Menjadi warga global (global citizen) bukan berarti meniru sepenuhnya gaya hidup barat/luar, melainkan membawa identitas dan nilai luhur Pancasila ke panggung dunia.
                    </p>
                    <ul class="list-disc list-inside text-xs text-slate-600 space-y-1">
                        <li><strong>Glocal (Global + Lokal):</strong> Berpikir secara luas dengan standar kualitas internasional, bertindak dengan etika lokal Pancasila.</li>
                    </ul>
                `
            }
        };

        // Open Modal Function
        function openModal(key) {
            const modal = document.getElementById('materiModal');
            const content = document.getElementById('modalContent');
            const data = materiData[key];

            content.innerHTML = `
                <h3 class="text-lg font-bold text-slate-900 mb-2">${data.title}</h3>
                ${data.content}
            `;
            modal.classList.remove('hidden');
        }

        // Close Modal Function
        function closeModal() {
            document.getElementById('materiModal').classList.add('hidden');
        }

        // Close modal on click outside
        window.onclick = function(event) {
            const modal = document.getElementById('materiModal');
            if (event.target === modal) {
                closeModal();
            }
        };

        // Rubric Tab Switcher Function
        function switchTab(type) {
            const tabs = ['video', 'esai', 'infografis'];
            tabs.forEach(t => {
                const btn = document.getElementById(`tab-${t}`);
                const content = document.getElementById(`content-${t}`);
                
                if (t === type) {
                    btn.className = "px-3 py-2 rounded-lg bg-white text-slate-900 shadow-sm transition-all font-bold";
                    content.classList.remove('hidden');
                } else {
                    btn.className = "px-3 py-2 rounded-lg text-slate-600 hover:text-slate-900 transition-all font-normal";
                    content.classList.add('hidden');
                }
            });
        }

        // Save Note Function
        function saveNote() {
            const text = document.getElementById('reflectionNote').value;
            const status = document.getElementById('saveStatus');
            
            if (text.trim() === '') return;

            // Temporary visual feedback
            status.classList.remove('opacity-0');
            setTimeout(() => {
                status.classList.add('opacity-0');
            }, 2500);
        }
    </script>
</body>
</html>
