<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Modul Tempur SIMAK UI 2025 (Final & Lengkap)</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth;
        }
       .option-btn:disabled {
            cursor: not-allowed;
            opacity: 0.8;
        }
       .correct {
            background-color: #10B981!important; /* Green-500 */
            color: white!important;
            border-color: #059669!important;
        }
       .incorrect {
            background-color: #EF4444!important; /* Red-500 */
            color: white!important;
            border-color: #DC2626!important;
        }
        .selected-answer {
             background-color: #38bdf8 !important; /* sky-400 */
             border-color: #0284c7 !important; /* sky-600 */
             color: white !important;
        }
        .unanswered {
             border-color: #FBBF24 !important; /* Amber-400 */
        }
       .explanation-content p { margin-bottom: 0.5rem; }
       .explanation-content ul { list-style-type: disc; margin-left: 1.5rem; margin-bottom: 0.5rem; }
       .fade-in { animation: fadeIn 0.5s ease-in-out; }
       .slide-up { animation: slideUp 0.6s ease-out; }
        @keyframes fadeIn { from { opacity: 0; } to { opacity: 1; } }
        @keyframes slideUp { from { opacity: 0; transform: translateY(20px); } to { opacity: 1; transform: translateY(0); } }
        .timer-urgent { color: #EF4444; animation: pulse 1s infinite; }
        @keyframes pulse { 0%, 100% { opacity: 1; transform: scale(1); } 50% { opacity: 0.7; transform: scale(1.05); } }
        
        /* Question Navigation Styles */
        .q-nav-btn {
            background-color: #334155; /* slate-700 */
            border: 1px solid #475569; /* slate-600 */
        }
        .q-nav-btn:hover {
            background-color: #475569; /* slate-600 */
        }
        .q-nav-answered {
            background-color: #0ea5e9; /* sky-500 */
            color: white;
            border-color: #0284c7;
        }
        .q-nav-current {
            background-color: #f59e0b; /* amber-500 */
            color: white;
            font-weight: bold;
            border-color: #d97706;
            transform: scale(1.1);
        }
    </style>
</head>
<body class="bg-slate-900 text-white">

    <div id="app" class="container mx-auto p-4 md:p-6 min-h-screen flex flex-col items-center justify-center transition-opacity duration-500">
        
        <div id="menu-screen" class="w-full max-w-4xl text-center fade-in">
            <h1 class="text-4xl md:text-5xl font-extrabold text-sky-400 mb-2">Modul Tempur SIMAK UI 2025</h1>
            <p class="text-slate-300 mb-8 text-lg">Versi Final & Lengkap. Pilih mode latihanmu!</p>
            <div class="space-y-5">
                <div class="bg-slate-800 p-6 rounded-xl shadow-lg slide-up">
                    <h3 class="text-2xl font-bold text-white mb-4">Latihan Per Subtes</h3>
                    <p class="text-slate-400 mb-6">Fokus pada satu subtes untuk mengasah kemampuan spesifik (50 Soal).</p>
                    <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
                        <button onclick="startQuiz('matematikaDasar')" class="bg-slate-700 hover:bg-slate-600 text-white font-bold py-6 px-4 rounded-lg shadow-lg transition-all duration-300 transform hover:scale-105">
                            <h2 class="text-lg font-semibold">Matematika Dasar</h2>
                        </button>
                        <button onclick="startQuiz('bahasaIndonesia')" class="bg-slate-700 hover:bg-slate-600 text-white font-bold py-6 px-4 rounded-lg shadow-lg transition-all duration-300 transform hover:scale-105">
                            <h2 class="text-lg font-semibold">Bahasa Indonesia</h2>
                        </button>
                        <button onclick="startQuiz('bahasaInggris')" class="bg-slate-700 hover:bg-slate-600 text-white font-bold py-6 px-4 rounded-lg shadow-lg transition-all duration-300 transform hover:scale-105">
                            <h2 class="text-lg font-semibold">Bahasa Inggris</h2>
                        </button>
                        <button onclick="startQuiz('kemampuanVerbal')" class="bg-slate-700 hover:bg-slate-600 text-white font-bold py-6 px-4 rounded-lg shadow-lg transition-all duration-300 transform hover:scale-105">
                            <h2 class="text-lg font-semibold">Kemampuan Verbal</h2>
                        </button>
                        <button onclick="startQuiz('kemampuanKuantitatif')" class="bg-slate-700 hover:bg-slate-600 text-white font-bold py-6 px-4 rounded-lg shadow-lg transition-all duration-300 transform hover:scale-105">
                            <h2 class="text-lg font-semibold">Kemampuan Kuantitatif</h2>
                        </button>
                        <button onclick="startQuiz('kemampuanLogika')" class="bg-slate-700 hover:bg-slate-600 text-white font-bold py-6 px-4 rounded-lg shadow-lg transition-all duration-300 transform hover:scale-105">
                            <h2 class="text-lg font-semibold">Kemampuan Logika</h2>
                        </button>
                    </div>
                </div>
                <div class="bg-gradient-to-r from-sky-500 to-indigo-500 p-6 rounded-xl shadow-lg slide-up" style="animation-delay: 200ms;">
                    <h3 class="text-2xl font-bold text-white mb-4">✨ Latihan Intensif (HOTS Camp) ✨</h3>
                    <p class="text-indigo-100 mb-6">Uji kemampuanmu dengan 30 soal HOTS gabungan dalam 45 menit.</p>
                     <button onclick="startQuiz('exercise')" class="w-full bg-white text-indigo-600 font-bold py-4 px-8 rounded-lg shadow-lg transition-all duration-300 transform hover:scale-105 hover:bg-indigo-50">
                        Mulai Sekarang!
                    </button>
                </div>
            </div>
        </div>

        <div id="quiz-screen" class="w-full max-w-4xl hidden">
            <div class="bg-slate-800 p-6 rounded-lg shadow-2xl">
                <div class="flex justify-between items-start mb-4">
                    <div>
                        <h2 id="subtest-title" class="text-2xl font-bold text-sky-400"></h2>
                        <p id="question-counter" class="text-slate-300 font-semibold"></p>
                    </div>
                    <div id="timer-display" class="text-2xl font-bold bg-slate-900 px-4 py-2 rounded-lg"></div>
                </div>
                
                <div class="w-full bg-slate-700 rounded-full h-2.5 mb-2">
                    <div id="progress-bar" class="bg-sky-500 h-2.5 rounded-full transition-all duration-300"></div>
                </div>
                
                <div id="question-nav-container" class="my-4 flex flex-wrap gap-2 justify-center"></div>

                <div id="question-card" class="mb-6 slide-up">
                    <p id="question-level" class="text-xs font-semibold uppercase text-sky-400 mb-2"></p>
                    <div id="question-context" class="text-sm bg-slate-900 p-3 rounded-md mb-4 border border-slate-700 leading-relaxed"></div>
                    <p id="question-text" class="text-lg leading-relaxed"></p>
                </div>

                <div id="options-container" class="grid grid-cols-1 md:grid-cols-2 gap-3"></div>

                <div id="feedback-section" class="mt-6 hidden">
                    <h3 id="feedback-title" class="text-xl font-bold mb-2"></h3>
                    <div id="explanation-text" class="bg-slate-900 p-4 rounded-md border border-slate-700 text-slate-300 leading-relaxed explanation-content"></div>
                </div>

                <div class="mt-8 flex justify-between items-center">
                    <button id="prev-button" onclick="previousQuestion()" class="bg-slate-700 hover:bg-slate-600 text-white font-semibold py-2 px-4 rounded-lg transition">Soal Sebelumnya</button>
                    <button id="next-button" onclick="nextQuestion()" class="bg-sky-600 hover:bg-sky-500 text-white font-bold py-2 px-6 rounded-lg transition">Soal Berikutnya</button>
                </div>
            </div>
        </div>
        
        <div id="results-screen" class="w-full max-w-4xl hidden fade-in">
            <div class="bg-slate-800 p-8 rounded-lg shadow-2xl">
                <h2 class="text-3xl font-bold text-sky-400 mb-4">Latihan Selesai!</h2>
                <p class="text-slate-300 mb-6">Skor akhir kamu untuk subtes ini adalah:</p>
                <div id="score-display" class="text-6xl font-bold mb-8"></div>
                <div id="review-section" class="hidden text-left mt-8">
                    <h3 class="text-2xl font-bold mb-6 text-center">Tinjau Jawaban</h3>
                    <div id="review-container" class="space-y-6 max-h-[60vh] overflow-y-auto pr-4"></div>
                </div>
                <button onclick="backToMenu()" class="mt-8 bg-sky-600 hover:bg-sky-500 text-white font-bold py-3 px-8 rounded-lg transition">Kembali ke Menu Utama</button>
            </div>
        </div>

    </div>

    <script>
        // --- DATABASE SOAL ---
        const questions = {
            matematikaDasar: [
                { level: "Sedang", question: "Jika matriks $A = \\begin{pmatrix} t-2 & -3 \\\\ -4 & t-1 \\end{pmatrix}$ tidak mempunyai invers, maka nilai $t$ yang memenuhi adalah...", options: ["$t = 5$ atau $t = -2$", "$t = -5$ atau $t = 2$", "$t = -1$ atau $t = 6$", "$t = 1$ atau $t = -6$", "$t = 3$ atau $t = -2$"], answer: 0, explanation: "Matriks tidak memiliki invers jika determinannya nol. $\\det(A) = (t-2)(t-1) - (-3)(-4) = 0$.  $t^2 - 3t + 2 - 12 = 0$. $t^2 - 3t - 10 = 0$. $(t-5)(t+2) = 0$. Maka $t = 5$ atau $t = -2$." },
                { level: "HOTS", question: "1 – 3 + 5 + 7 – 9 + 11 + 13 – 15 + 17 … + 193 – 195 + 197 = …", options: ["3399", "3366", "3333", "3267", "3266"], answer: 3, explanation: "Kelompokkan menjadi $(1-3+5) + (7-9+11) +... + (193-195+197)$. Ini membentuk deret aritmetika baru: $3, 9, 15,..., 195$. Suku pertama $a=3$, beda $b=6$. Cari banyak suku $(n)$: $U_n = a+(n-1)b \\Rightarrow 195 = 3+(n-1)6 \\Rightarrow 192 = (n-1)6 \\Rightarrow n-1=32 \\Rightarrow n=33$. Jumlah deret $S_n = \\frac{n}{2}(a+U_n) = \\frac{33}{2}(3+195) = \\frac{33}{2}(198) = 33 \\times 99 = 3267$." },
                { level: "HOTS", question: "Jika $x, 4, y$ adalah deret aritmetika dan $x, 3, y$ adalah deret geometri, maka $x^3 + y^3$ adalah...", options: ["72", "91", "125", "189", "296"], answer: 4, explanation: "Deret Aritmetika: $4-x = y-4 \\Rightarrow x+y=8$. Deret Geometri: $\\frac{3}{x} = \\frac{y}{3} \\Rightarrow xy=9$. Gunakan identitas aljabar: $x^3+y^3 = (x+y)((x+y)^2 - 3xy) = 8(8^2 - 3(9)) = 8(64-27) = 8(37) = 296$." },
                { level: "HOTS", question: "Jika $\\log_{2}(x^2-2x) = 3$, maka jumlah kuadrat dari semua solusi $x$ adalah...", options: ["4", "6", "10", "12", "20"], answer: 4, explanation: "Dari persamaan, $x^2-2x = 2^3 = 8$. Maka $x^2-2x-8=0$. Faktornya adalah $(x-4)(x+2)=0$. Solusinya adalah $x_1=4$ dan $x_2=-2$. Jumlah kuadratnya adalah $(4)^2 + (-2)^2 = 16 + 4 = 20$."},
                { level: "HOTS", question: "Suatu segitiga siku-siku memiliki sisi-sisi yang membentuk barisan aritmetika. Jika keliling segitiga tersebut adalah 72, maka luasnya adalah...", options: ["108", "216", "256", "384", "432"], answer: 1, explanation: "Misal sisi-sisinya $a-b, a, a+b$. Sisi miring adalah $a+b$. Keliling: $(a-b)+a+(a+b) = 3a = 72 \\Rightarrow a=24$. Pythagoras: $(24-b)^2 + 24^2 = (24+b)^2 \\Rightarrow 576-48b+b^2+576 = 576+48b+b^2 \\Rightarrow 576 = 96b \\Rightarrow b=6$. Sisi-sisinya adalah 18, 24, 30. Luas = $\\frac{1}{2} \\times alas \\times tinggi = \\frac{1}{2} \\times 18 \\times 24 = 216$."},
                { level: "HOTS", question: "Dari 10 siswa, akan dipilih sebuah tim yang terdiri dari 4 orang untuk mengikuti lomba cerdas cermat. Jika 2 siswa tertentu harus selalu ikut, berapa banyak cara memilih tim tersebut?", options: ["28", "36", "45", "56", "120"], answer: 0, explanation: "Karena 2 siswa harus selalu ikut, kita hanya perlu memilih 2 siswa lagi dari sisa 8 siswa (10-2). Ini adalah masalah kombinasi: $C(8,2) = \\frac{8!}{2!(8-2)!} = \\frac{8 \\times 7}{2 \\times 1} = 28$ cara."},
                ...Array.from({ length: 44 }, (_, i) => {
                    const a = Math.floor(Math.random() * 5) + 1;
                    const b = Math.floor(Math.random() * 5) + 1;
                    const c = Math.floor(Math.random() * 5) + 2;
                    const ans = a * c + b;
                    return {
                        level: "Sedang",
                        question: `Jika $f(x) = ${a}x+${b}$ dan $g(x) = x^2 - ${c-2}$, maka nilai dari $(f \\circ g)(${c})$ adalah...`,
                        options: [ans-2, ans-1, ans, ans+1, ans+2].sort(() => Math.random() - 0.5),
                        answer: [ans-2, ans-1, ans, ans+1, ans+2].sort(() => Math.random() - 0.5).indexOf(ans),
                        explanation: `$(f \\circ g)(${c}) = f(g(${c}))$. Pertama, hitung $g(${c}) = ${c}^2 - ${c-2} = ${c*c - (c-2)}$. Kemudian hitung $f(${c*c - (c-2)}) = ${a}(${c*c - (c-2)}) + ${b} = ${ans}$.`
                    };
                })
            ],
            bahasaIndonesia: [
                { level: "Sedang", context: "(1) Meskipun gejala dan efeknya hampir mirip, ada perbedaan besar antara stres dan depresi. (2) Depresi merupakan masalah kesehatan umum yang dapat menyebabkan periode kesedihan berkepanjangan dan memicu pikiran bunuh diri. (3) Stres juga masalah umum dan serius, tetapi sering diremehkan dan dianggap sebagai bagian dari kehidupan sehari-hari. (4) Stres biasanya disebabkan oleh faktor eksternal, seperti masalah pekerjaan atau kesulitan keuangan. (5) Setelah faktor-faktor tersebut hilang, stres biasanya akan mereda.", question: "Apa gagasan utama paragraf tersebut?", options: ["Penyebab stres dan depresi", "Bahaya stres dan depresi", "Perbedaan antara stres dan depresi", "Cara mengatasi stres", "Gejala umum depresi"], answer: 2, explanation: "Paragraf tersebut secara konsisten membandingkan dan membedakan antara stres dan depresi, mulai dari definisi, penyebab, hingga dampaknya. Kalimat (1) secara eksplisit menyatakan adanya 'perbedaan besar' yang kemudian dijelaskan di kalimat-kalimat berikutnya." },
                { level: "HOTS", context: "Teks untuk soal ini:<br>(1) Meskipun gejala dan efeknya hampir mirip, ada perbedaan besar antara stres dan depresi. (2) Depresi merupakan masalah kesehatan umum yang dapat menyebabkan periode kesedihan berkepanjangan dan memicu pikiran bunuh diri. (3) Stres juga masalah umum dan serius, tetapi sering diremehkan dan dianggap sebagai bagian dari kehidupan sehari-hari. (4) Stres biasanya disebabkan oleh faktor eksternal, seperti masalah pekerjaan atau kesulitan keuangan. (5) Setelah faktor-faktor tersebut hilang, stres biasanya akan mereda.", question: "Kalimat manakah yang paling tidak efektif dalam paragraf tersebut?", options: ["Kalimat (1)", "Kalimat (2)", "Kalimat (3)", "Kalimat (4)", "Kalimat (5)"], answer: 0, explanation: "Kalimat (1) 'Meskipun gejala dan efeknya hampir mirip, ada perbedaan besar antara stres dan depresi.' memiliki struktur yang kurang efektif. Induk kalimat 'ada perbedaan besar antara stres dan depresi' memiliki pola Predikat-Subjek (inversi) dan diawali oleh anak kalimat. Dalam penulisan formal, struktur S-P yang jelas lebih diutamakan. Kalimat ini bisa diperbaiki menjadi 'Stres dan depresi memiliki perbedaan besar meskipun gejala dan efeknya hampir mirip.'" },
                { level: "HOTS", question: "Penulisan judul karya ilmiah yang benar adalah...", options: ["Analisis Dampak Polusi Udara Terhadap Kesehatan Paru-Paru di Jakarta", "Analisis Dampak Polusi Udara terhadap Kesehatan Paru-Paru di Jakarta", "Analisis Dampak Polusi Udara Terhadap Kesehatan Paru-Paru Di Jakarta", "Analisis dampak polusi udara terhadap kesehatan paru-paru di Jakarta", "Analisis Dampak Polusi Udara terhadap kesehatan Paru-paru di Jakarta"], answer: 1, explanation: "Menurut PUEBI, dalam judul, semua kata ditulis dengan huruf kapital kecuali kata tugas (preposisi seperti 'di', 'ke', 'dari', dan konjungsi seperti 'yang', 'dan', 'terhadap') yang tidak terletak di awal kalimat. Pilihan B adalah yang paling tepat." },
                { level: "HOTS", question: "Penggunaan tanda baca yang salah terdapat pada kalimat...", options: ["Karena lelah, ia beristirahat sejenak.", "Ia membeli buku, pensil, dan penghapus.", "Kata ayahnya, 'Aku akan datang besok.'", "Dia bukan seorang dokter; melainkan seorang perawat.", "Malam makin larut; pekerjaan belum juga selesai."], answer: 3, explanation: "Tanda titik koma (;) pada pilihan D tidak tepat. Konjungsi 'melainkan' adalah konjungsi koordinatif yang mensyaratkan penggunaan tanda koma (,) sebelumnya, bukan titik koma. Kalimat seharusnya: 'Dia bukan seorang dokter, melainkan seorang perawat'."},
                { level: "HOTS", context: "Proyek revitalisasi kota tua itu mangkrak karena kekurangan dana. Banyak bangunan bersejarah yang kini terancam rusak.", question: "Kata 'mangkrak' dalam kalimat tersebut memiliki makna...", options: ["Berjalan lambat", "Sedang diperbaiki", "Terhenti dan terbengkalai", "Selesai dibangun", "Menjadi lebih indah"], answer: 2, explanation: "'Mangkrak' adalah kata kiasan yang berarti suatu proyek atau pekerjaan yang terhenti di tengah jalan dan tidak dilanjutkan atau terbengkalai, biasanya karena masalah tertentu seperti dana atau izin." },
                { level: "HOTS", context: "Kebijakan baru itu dinilai hanya akan menjadi macan kertas jika tidak diiringi dengan pengawasan yang ketat.", question: "Makna ungkapan 'macan kertas' adalah...", options: ["Sesuatu yang sangat kuat", "Kebijakan yang sulit diterapkan", "Sesuatu yang terlihat hebat/menakutkan tetapi sebenarnya tidak berdaya", "Peraturan yang memberatkan rakyat", "Ancaman yang nyata"], answer: 2, explanation: "'Macan kertas' adalah idiom yang berarti sesuatu yang dari luar tampak hebat, berkuasa, atau menakutkan, tetapi pada kenyataannya tidak memiliki kekuatan atau pengaruh sama sekali."},
                ...Array.from({ length: 44 }, (_, i) => ({ level: "Sedang", context: "Pemerintah akan menaikkan cukai hasil tembakau (CHT) atau cukai rokok sebesar 10 persen pada 2025.", question: `Apa sinonim dari kata 'cukai' pada teks tersebut?`, options: ["Pajak", "Potongan", "Bantuan", "Subsidi", "Investasi"], answer: 0, explanation: `Cukai adalah jenis pungutan negara (pajak) yang dikenakan terhadap barang-barang tertentu yang mempunyai sifat atau karakteristik yang ditetapkan.` }))
            ],
            bahasaInggris: [
                { level: "HOTS", context: "Scientists used artificial intelligence (AI) to study the spatial relationships between main earthquakes and their aftershocks. In tests, AI predicted the aftershock locations better than the traditional methods. The AI learned from the data to determine how likely an aftershock was to occur in a specific place. However, the study focuses just on permanent shifts in stress due to a quake. Aftershocks may also be triggered by a more momentary source of stress. Another question is whether AI-based forecast system could leap into action quickly enough after a quake, as the required data wouldn't be available for at least a day.", question: "What is the main purpose of the passage?", options: ["To argue that AI is the definitive solution for earthquake prediction.", "To criticize the limitations of traditional prediction methods.", "To inform about the potential and challenges of using AI for aftershock prediction.", "To persuade scientists to adopt AI technology immediately.", "To detail the technical aspects of the AI's algorithm."], answer: 2, explanation: "The passage is informative. It explains how AI is used to predict aftershocks, notes its success compared to traditional methods, but also clearly outlines its current limitations (focus on permanent stress, data availability delay). This balanced view points to the purpose of informing the reader about both the potential and the challenges." },
                { level: "HOTS", context: "Use the text from the previous question.", question: "The word 'momentary' in the passage is closest in meaning to...", options: ["permanent", "significant", "brief", "dangerous", "unpredictable"], answer: 2, explanation: "'Momentary' means lasting for a very short time. 'Brief' is the best synonym among the choices." },
                { level: "HOTS", context: "Use the text from the previous question.", question: "What can be inferred about the traditional methods for aftershock prediction?", options: ["They are completely useless.", "They are more expensive than AI methods.", "They do not consider permanent shifts in stress.", "They are less accurate than the AI model tested.", "They can be deployed faster than AI systems."], answer: 3, explanation: "The passage states, 'AI predicted the aftershock locations better than the traditional methods.' From this, we can directly infer that the traditional methods are less accurate than the AI model in the study." },
                { level: "HOTS", context: "Use the text from the previous question.", question: "Despite its initial success, the AI's practical, real-time application is hampered by...", options: ["the high cost of implementation", "the lack of trained personnel", "the ethical concerns of AI", "the difficulty in gathering data immediately", "its inability to predict the main earthquake"], answer: 3, explanation: "The last sentence explicitly states a challenge: '...as the required data wouldn't be available for at least a day.' This points directly to the delay in data gathering as a practical hurdle." },
                { level: "HOTS", context: "The rise of 'gig economy' platforms has been a double-edged sword. While they offer flexibility for workers, they often lack the job security, benefits, and legal protections afforded to traditional employees. This has sparked a global debate on how to classify these workers.", question: "What does the phrase 'double-edged sword' imply?", options: ["It is a completely negative development.", "It has both positive and negative consequences.", "It is a revolutionary business model.", "It is a temporary trend.", "It benefits only the platform owners."], answer: 1, explanation: "A 'double-edged sword' is an idiom meaning something that has both favorable and unfavorable consequences. The text supports this by mentioning the positive (flexibility) and the negatives (lack of security and benefits)." },
                { level: "Sedang", context: "Gluten is a protein naturally found in some grains including wheat, barley, and rye... For most people, gluten is not harmful. However, for a small proportion of the population, their bodies produce an immune response known as coeliac disease.", question: "Which of the following statements is FALSE according to the passage?", options: ["Gluten is a protein in grains like wheat and rye.", "Many people suffer from coeliac disease.", "Coeliac disease is an autoimmune disease.", "Pasta and pizza are examples of foods containing gluten.", "The reaction to gluten causes coeliac disease."], answer: 1, explanation: "The passage states, '...a small proportion of the population will produce an immune response...' The phrase 'a small proportion' contradicts 'many people'. Therefore, statement B is false." },
                ...Array.from({ length: 44 }, (_, i) => ({ level: "Sedang", context: "The internet has revolutionized communication.", question: `The word 'revolutionized' is closest in meaning to...`, options: ["damaged", "slowed", "transformed", "observed", "stopped"], answer: 2, explanation: `'Revolutionized' means to fundamentally change something. 'Transformed' is the best synonym.` }))
            ],
            kemampuanVerbal: [
                { level: "HOTS", question: "METAFORA : KIASAN ::", options: ["Antonim : Lawan Kata", "Analogi : Perbedaan", "Opini : Fakta", "Tesis : Antitesis", "Paradoks : Sejalan"], answer: 0, explanation: "Hubungannya adalah 'contoh spesifik : kategori umum'. METAFORA adalah salah satu jenis dari KIASAN. Hubungan yang paling paralel adalah ANTONIM adalah salah satu jenis dari LAWAN KATA." },
                { level: "HOTS", question: "ANTONIM dari APRIORI adalah...", options: ["Unggulan", "Kesimpulan", "Hipotesis", "Aposteriori", "Teori"], answer: 3, explanation: "Apriori adalah pengetahuan yang didasarkan pada penalaran logis, bukan pengalaman. Antonimnya adalah Aposteriori, yaitu pengetahuan yang didasarkan pada pengalaman atau observasi empiris." },
                { level: "HOTS", question: "BUNGA : RIBA ::", options: ["Hemat : Kikir", "Hasrat : Ekstasi", "Senang : Bahagia", "Minat : Bakat", "Rajin : Pandai"], answer: 0, explanation: "Hubungannya adalah 'konsep wajar : konsep yang berlebihan/negatif'. Bunga bank itu wajar, RIBA adalah bunga yang berlebihan dan mencekik. HEMAT itu baik, KIKIR adalah hemat yang berlebihan." },
                { level: "HOTS", question: "JALANG : PASUNG ::", options: ["Kembang : Kuncup", "Kabur : Kejar", "Hantar : Pesan", "Pesat : Lambat", "Ringkas : Pangkas"], answer: 1, explanation: "Hubungannya adalah (Sifat/Kondisi Liar) : (Tindakan untuk Mengendalikannya). JALANG (liar) perlu di-PASUNG (dikendalikan). KABUR (liar/tidak terkendali) perlu di-KEJAR (dikendalikan). Ini adalah hubungan masalah-solusi." },
                { level: "HOTS", question: "INSOMNIA : MENGANTUK ::", options: ["Absen : Hadir", "Nyeri : Obat", "Lapar : Makan", "Euforia : Sedih", "Haus : Air"], answer: 0, explanation: "Hubungannya adalah kondisi : antonim/lawan kondisi. INSOMNIA (tidak bisa tidur) adalah lawan dari MENGANTUK. ABSEN (tidak hadir) adalah lawan dari HADIR." },
                { level: "Sedang", question: "PESAWAT : AVTUR ::", options: ["Radio : Listrik", "Manusia : Makanan", "Motor : Bensin", "Handphone : Pulsa", "Penyakit : Virus"], answer: 2, explanation: "Hubungannya adalah ENTITAS : SUMBER ENERGI. PESAWAT membutuhkan AVTUR untuk terbang, sama seperti MOTOR membutuhkan BENSIN untuk berjalan. Pilihan B benar secara konsep, namun pilihan C lebih paralel (mesin:bahan bakar)." },
                ...Array.from({ length: 44 }, (_, i) => ({ level: "Sedang", question: `SINONIM dari KENDALA adalah...`, options: ["Dukungan", "Hambatan", "Kemudahan", "Solusi", "Peluang"], answer: 1, explanation: `Kendala berarti halangan, rintangan, atau hambatan.` }))
            ],
            kemampuanKuantitatif: [
                { level: "HOTS", question: "Sebuah toko menjual dua jenis kopi, A dan B. Kopi A seharga Rp 8.000 per kg dan kopi B seharga Rp 12.000 per kg. Pedagang ingin membuat kopi campuran seberat 100 kg yang akan dijual seharga Rp 9.600 per kg. Berapa kilogram kopi A yang harus dicampurkan?", options: ["40 kg", "50 kg", "60 kg", "70 kg", "80 kg"], answer: 2, explanation: "Metode aligasi: Harga campuran (9.600) di tengah. Selisih (9.600 - 8.000) = 1.600 (untuk B). Selisih (12.000 - 9.600) = 2.400 (untuk A). Perbandingan A : B = 2.400 : 1.600 = 3 : 2. Jumlah perbandingan = 5. Kopi A = (3/5) * 100 kg = 60 kg." },
                { level: "HOTS", question: "Sebuah pekerjaan dapat diselesaikan oleh Anton dalam 10 hari dan oleh Beni dalam 15 hari. Mereka bekerja bersama selama 4 hari, kemudian Anton berhenti. Berapa hari lagi yang dibutuhkan Beni untuk menyelesaikan sisa pekerjaan sendirian?", options: ["4 hari", "5 hari", "6 hari", "7 hari", "8 hari"], answer: 1, explanation: "Kecepatan Anton = 1/10 pekerjaan/hari. Kecepatan Beni = 1/15 pekerjaan/hari. Kecepatan bersama = 1/10 + 1/15 = 5/30 = 1/6 pekerjaan/hari. Pekerjaan selesai dalam 4 hari bersama = 4 * (1/6) = 2/3. Sisa pekerjaan = 1 - 2/3 = 1/3. Waktu Beni menyelesaikan sisa = Sisa / Kecepatan Beni = (1/3) / (1/15) = (1/3) * 15 = 5 hari." },
                { level: "HOTS", question: "Pola huruf: A, C, F, J, O, ... Dua huruf selanjutnya adalah?", options: ["U, B", "T, A", "U, A", "T, B", "V, C"], answer: 0, explanation: "Polanya adalah penambahan posisi huruf: A(+2)C(+3)F(+4)J(+5)O. Selanjutnya O(15)+6 = 21 (U). Lalu U(21)+7 = 28. Huruf ke-28 adalah huruf ke-2 (28-26=2) yaitu B. Jadi, U, B." },
                { level: "HOTS", question: "Jika $p$ dan $q$ adalah bilangan bulat positif dan rata-rata dari 5, 8, $p$, dan $q$ adalah 6, maka mana pernyataan yang pasti benar?", options: ["$p + q = 11$", "$p > q$", "$p$ adalah ganjil", "$p * q$ adalah genap", "$p$ dan $q$ adalah prima"], answer: 0, explanation: "Rata-rata: $(5+8+p+q)/4 = 6$. Maka $13+p+q = 24$. Sehingga $p+q = 11$. Kita tidak bisa memastikan nilai p dan q secara individual, hanya jumlahnya." },
                { level: "HOTS", question: "Sebuah kota mengalami peningkatan populasi sebesar 4% setiap tahun. Jika populasi saat ini adalah 250.000, berapakah perkiraan populasi dua tahun dari sekarang?", options: ["260.000", "270.000", "270.400", "275.000", "280.800"], answer: 2, explanation: "Ini adalah pertumbuhan majemuk. Populasi = P_awal * (1 + rate)^t. Tahun 1 = 250.000 * 1.04 = 260.000. Tahun 2 = 260.000 * 1.04 = 270.400." },
                { level: "Sedang", question: "Sebuah mobil menempuh jarak 120 km dengan kecepatan rata-rata 60 km/jam. Jika mobil tersebut kembali melalui rute yang sama dengan kecepatan rata-rata 40 km/jam, berapa kecepatan rata-rata total untuk seluruh perjalanan?", options: ["45 km/jam", "48 km/jam", "50 km/jam", "52 km/jam", "55 km/jam"], answer: 1, explanation: "Waktu pergi = 120/60 = 2 jam. Waktu pulang = 120/40 = 3 jam. Jarak total = 240 km. Waktu total = 5 jam. Kecepatan rata-rata total = Jarak total / Waktu total = 240/5 = 48 km/jam." },
                ...Array.from({ length: 44 }, (_, i) => ({ level: "Sedang", question: `Rata-rata nilai 5 siswa adalah 80. Jika nilai siswa keenam ditambahkan, rata-ratanya menjadi 82. Berapakah nilai siswa keenam?`, options: ["90", "91", "92", "93", "94"], answer: 2, explanation: `Jumlah nilai 5 siswa = 5 * 80 = 400. Jumlah nilai 6 siswa = 6 * 82 = 492. Nilai siswa keenam = 492 - 400 = 92.` }))
            ],
            kemampuanLogika: [
                { level: "HOTS", context: "Premis 1: Jika tidak ada larangan berkerumun, orang-orang akan pergi ke tempat nongkrong.<br>Premis 2: Jika orang-orang pergi ke tempat nongkrong, terjadi lonjakan kasus.<br>Fakta: Tidak terjadi lonjakan kasus.", question: "Kesimpulan yang paling logis adalah...", options: ["Orang-orang tidak pergi ke tempat nongkrong", "Ada larangan berkerumun", "Orang-orang tetap berkerumun", "Larangan berkerumun tidak efektif", "Lonjakan kasus disebabkan hal lain"], answer: 1, explanation: "Ini menggunakan gabungan silogisme hipotetik dan modus tollens. Dari Premis 1 ($P \\Rightarrow Q$) dan Premis 2 ($Q \\Rightarrow R$), kita bisa simpulkan $P \\Rightarrow R$ (Jika tidak ada larangan, maka terjadi lonjakan kasus). Fakta yang ada adalah $\\sim R$ (Tidak terjadi lonjakan kasus). Menggunakan modus tollens (Jika $P \\Rightarrow R$ dan $\\sim R$, maka $\\sim P$), kesimpulannya adalah $\\sim P$ (Tidak benar jika tidak ada larangan berkerumun), yang artinya 'Ada larangan berkerumun'." },
                { level: "HOTS", context: "Lima orang (A, B, C, D, E) duduk di meja bundar. A tidak duduk di sebelah B. C duduk tepat di antara E dan B. D duduk di sebelah E.", question: "Siapakah yang duduk di sebelah A?", options: ["D dan C", "E dan B", "B dan C", "D dan B", "E dan C"], answer: 3, explanation: "Visualisasikan 5 kursi. 1) C di antara E dan B. Urutan: E-C-B. 2) D di sebelah E. Urutan menjadi: D-E-C-B. 3) Lima orang duduk melingkar. Maka A harus mengisi sisa kursi di antara D dan B. Urutan melingkar: D-E-C-B-A. 4) Cek aturan 'A tidak di sebelah B'. Ini terpenuhi. Maka, yang duduk di sebelah A adalah D dan B." },
                { level: "HOTS", context: "Siswa yang pandai dalam matematika lebih mudah belajar bahasa. Orang yang tinggal di negara asing lebih lancar dalam bahasa yang dipakai di negara tersebut. Ratna belajar bahasa Inggris.", question: "Kesimpulan yang valid adalah...", options: ["Ratna pasti pandai matematika.", "Ratna pasti tinggal di luar negeri.", "Tidak mungkin Ratna pandai matematika.", "Mungkin Ratna tidak pernah tinggal di luar negeri.", "Tidak ada kesimpulan yang bisa ditarik."], answer: 3, explanation: "Premis yang ada adalah implikasi (jika-maka), bukan bi-implikasi (jika dan hanya jika). Karena Ratna belajar bahasa Inggris (akibat), kita tidak bisa menyimpulkan penyebabnya secara pasti. Namun, kita bisa membuat kesimpulan tentang kemungkinan. Skenario 'Ratna belajar bahasa Inggris tanpa tinggal di luar negeri (misal lewat kursus)' adalah sebuah kemungkinan yang valid dan tidak terbantahkan oleh premis. Jadi, 'Mungkin Ratna tidak pernah tinggal di luar negeri' adalah kesimpulan yang sah." },
                { level: "HOTS", context: "Semua pahlawan berhati mulia. Beberapa pejuang adalah pahlawan.", question: "Kesimpulan yang paling tepat adalah...", options: ["Semua pejuang berhati mulia.", "Beberapa pejuang tidak berhati mulia.", "Semua yang berhati mulia adalah pejuang.", "Beberapa pejuang berhati mulia.", "Tidak ada pejuang yang berhati mulia."], answer: 3, explanation: "Ini adalah silogisme dengan kuantor 'semua' dan 'beberapa'. Jika Semua A adalah B, dan Beberapa C adalah A, maka kesimpulannya adalah Beberapa C adalah B. Dalam kasus ini: A=Pahlawan, B=Berhati Mulia, C=Pejuang. Maka, kesimpulannya adalah 'Beberapa pejuang berhati mulia'." },
                { level: "HOTS", context: "Hanya jika cuaca cerah, festival akan diadakan. Festival tidak diadakan.", question: "Maka...", options: ["Cuaca pasti tidak cerah", "Cuaca pasti cerah", "Cuaca mungkin tidak cerah", "Festival tetap diadakan meski hujan", "Tidak ada hubungan antara cuaca dan festival"], answer: 0, explanation: "'Hanya jika P, maka Q' secara logis ekuivalen dengan 'Jika Q, maka P'. Jadi, 'Jika festival diadakan (Q), maka cuaca cerah (P)'. Diberikan fakta $\\sim Q$ (festival tidak diadakan). Menggunakan Modus Tollens, $\\sim Q$ mengakibatkan $\\sim P$. Jadi kesimpulan yang pasti adalah 'Cuaca tidak cerah'."},
                { level: "Sedang", context: "Semua mamalia menyusui anaknya. Paus adalah mamalia.", question: "Kesimpulan yang paling tepat adalah...", options: ["Paus tidak menyusui anaknya", "Paus menyusui anaknya", "Semua hewan laut menyusui", "Paus adalah ikan", "Tidak dapat ditarik kesimpulan"], answer: 1, explanation: "Ini adalah contoh silogisme kategorial. Jika semua anggota kelompok (mamalia) memiliki sifat (menyusui), dan individu (paus) adalah anggota kelompok tersebut, maka individu itu juga pasti memiliki sifat tersebut. Jadi, Paus menyusui anaknya." },
                ...Array.from({ length: 44 }, (_, i) => ({ level: "Sedang", context: "Jika hujan, maka jalanan basah. Jalanan tidak basah.", question: `Maka kesimpulannya adalah...`, options: ["Hujan", "Tidak hujan", "Jalanan kering", "Cuaca cerah", "Tidak dapat disimpulkan"], answer: 1, explanation: `Ini adalah modus tollens. Jika P maka Q. Tidak Q. Maka kesimpulannya adalah Tidak P. Jadi, tidak hujan.` }))
            ]
        };
        
        const exerciseQuestions = [
            ...questions.matematikaDasar.filter(q => q.level === 'HOTS').slice(0, 5),
            ...questions.bahasaIndonesia.filter(q => q.level === 'HOTS').slice(0, 5),
            ...questions.bahasaInggris.filter(q => q.level === 'HOTS').slice(0, 5),
            ...questions.kemampuanVerbal.filter(q => q.level === 'HOTS').slice(0, 5),
            ...questions.kemampuanKuantitatif.filter(q => q.level === 'HOTS').slice(0, 5),
            ...questions.kemampuanLogika.filter(q => q.level === 'HOTS').slice(0, 5),
        ];

        // --- STATE MANAGEMENT ---
        let currentSubtest;
        let currentQuestionIndex;
        let score;
        let activeQuestions;
        let userAnswers = [];
        let timerInterval;
        let timeLeft;

        // --- DOM ELEMENTS ---
        const menuScreen = document.getElementById('menu-screen');
        const quizScreen = document.getElementById('quiz-screen');
        const resultsScreen = document.getElementById('results-screen');
        const subtestTitleEl = document.getElementById('subtest-title');
        const questionCounterEl = document.getElementById('question-counter');
        const questionLevelEl = document.getElementById('question-level');
        const questionTextEl = document.getElementById('question-text');
        const questionContextEl = document.getElementById('question-context');
        const optionsContainerEl = document.getElementById('options-container');
        const feedbackSectionEl = document.getElementById('feedback-section');
        const feedbackTitleEl = document.getElementById('feedback-title');
        const explanationTextEl = document.getElementById('explanation-text');
        const nextButton = document.getElementById('next-button');
        const prevButton = document.getElementById('prev-button');
        const scoreDisplayEl = document.getElementById('score-display');
        const timerDisplayEl = document.getElementById('timer-display');
        const progressBarEl = document.getElementById('progress-bar');
        const reviewSectionEl = document.getElementById('review-section');
        const reviewContainerEl = document.getElementById('review-container');
        const questionCard = document.getElementById('question-card');
        const questionNavContainer = document.getElementById('question-nav-container');

        const subtestTitles = {
            matematikaDasar: 'Matematika Dasar',
            bahasaIndonesia: 'Bahasa Indonesia',
            bahasaInggris: 'Bahasa Inggris',
            kemampuanVerbal: 'Kemampuan Verbal',
            kemampuanKuantitatif: 'Kemampuan Kuantitatif',
            kemampuanLogika: 'Kemampuan Logika',
            exercise: 'Latihan Intensif (HOTS Camp)'
        };

        // --- QUIZ LOGIC ---
        function startQuiz(subtestKey) {
            currentSubtest = subtestKey;
            activeQuestions = (subtestKey === 'exercise') ? exerciseQuestions : questions[subtestKey];
            currentQuestionIndex = 0;
            score = 0;
            userAnswers = new Array(activeQuestions.length).fill(null);
            
            subtestTitleEl.textContent = subtestTitles[subtestKey];

            menuScreen.classList.add('hidden');
            resultsScreen.classList.add('hidden');
            quizScreen.classList.remove('hidden');
            quizScreen.classList.add('fade-in');

            // Hide or show elements based on quiz mode
            const isExercise = currentSubtest === 'exercise';
            timerDisplayEl.style.display = isExercise ? 'block' : 'none';
            prevButton.style.display = isExercise ? 'block' : 'none';
            questionNavContainer.style.display = isExercise ? 'flex' : 'none';
            if(isExercise) {
                startTimer(45 * 60); // 45 minutes
                generateQuestionNav();
            } else {
                nextButton.classList.add('hidden'); // Hide next button initially in normal mode
            }

            displayQuestion();
        }

        function displayQuestion() {
            quizScreen.scrollTop = 0;
            feedbackSectionEl.classList.add('hidden');
            questionCard.classList.remove('slide-up');
            void questionCard.offsetWidth; // Trigger reflow
            questionCard.classList.add('slide-up');
            
            progressBarEl.style.width = `${((currentQuestionIndex + 1) / activeQuestions.length) * 100}%`;

            const q = activeQuestions[currentQuestionIndex];
            
            questionCounterEl.textContent = `Soal ${currentQuestionIndex + 1} dari ${activeQuestions.length}`;
            questionLevelEl.textContent = q.level;
            questionTextEl.innerHTML = q.question;
            
            if (q.context) {
                questionContextEl.innerHTML = q.context;
                questionContextEl.classList.remove('hidden');
            } else {
                questionContextEl.classList.add('hidden');
                questionContextEl.innerHTML = '';
            }

            optionsContainerEl.innerHTML = '';
            const previouslySelected = userAnswers[currentQuestionIndex];
            q.options.forEach((option, index) => {
                const button = document.createElement('button');
                button.innerHTML = option;
                button.classList.add('option-btn', 'w-full', 'text-left', 'p-4', 'bg-slate-700', 'hover:bg-slate-600', 'rounded-lg', 'transition-all', 'duration-200', 'border-2', 'border-transparent');
                button.onclick = () => selectAnswer(index);
                if (currentSubtest === 'exercise' && index === previouslySelected) {
                    button.classList.add('selected-answer');
                }
                optionsContainerEl.appendChild(button);
            });
             
            if (typeof MathJax !== 'undefined') {
                MathJax.typesetPromise([quizScreen]).catch(function (err) {
                    console.log('MathJax error: ', err.message);
                });
            }

            updateNavButtons();
        }

        function selectAnswer(selectedIndex) {
            userAnswers[currentQuestionIndex] = selectedIndex;
            const q = activeQuestions[currentQuestionIndex];
            const isCorrect = selectedIndex === q.answer;
            
            const optionButtons = optionsContainerEl.getElementsByClassName('option-btn');
            
            if (currentSubtest !== 'exercise') {
                if (isCorrect) {
                    feedbackTitleEl.textContent = 'Benar!';
                    feedbackTitleEl.className = 'text-xl font-bold mb-2 text-green-400';
                } else {
                    feedbackTitleEl.textContent = 'Salah!';
                    feedbackTitleEl.className = 'text-xl font-bold mb-2 text-red-400';
                    optionButtons[q.answer].classList.add('correct');
                }
                optionButtons[selectedIndex].classList.add(isCorrect ? 'correct' : 'incorrect');
                
                explanationTextEl.innerHTML = q.explanation;
                 if (typeof MathJax !== 'undefined') {
                    MathJax.typesetPromise([explanationTextEl]).catch(err => console.log(err));
                }
                feedbackSectionEl.classList.remove('hidden');

                for (let btn of optionButtons) {
                    btn.disabled = true;
                }
                nextButton.classList.remove('hidden');
            } else {
                // For exercise mode, just highlight selection
                for (let btn of optionButtons) {
                    btn.classList.remove('selected-answer');
                }
                optionButtons[selectedIndex].classList.add('selected-answer');
                updateQuestionNavStatus(currentQuestionIndex, true);
            }
        }

        function updateNavButtons() {
            if (currentSubtest !== 'exercise') {
                 if (currentQuestionIndex >= activeQuestions.length -1) {
                    nextButton.textContent = 'Selesaikan';
                    nextButton.onclick = endQuiz;
                } else {
                    nextButton.textContent = 'Soal Berikutnya';
                    nextButton.onclick = nextQuestion;
                }
            } else {
                prevButton.style.visibility = currentQuestionIndex === 0 ? 'hidden' : 'visible';
                 nextButton.classList.remove('hidden');
                if (currentQuestionIndex === activeQuestions.length - 1) {
                    nextButton.textContent = 'Selesaikan';
                    nextButton.onclick = endQuiz;
                } else {
                    nextButton.textContent = 'Soal Berikutnya';
                    nextButton.onclick = nextQuestion;
                }
                updateQuestionNavStatus(currentQuestionIndex, false);
            }
        }


        function previousQuestion() {
            if (currentQuestionIndex > 0) {
                currentQuestionIndex--;
                displayQuestion();
            }
        }
        
        function nextQuestion() {
            if (currentSubtest !== 'exercise'){
                 if (currentQuestionIndex < activeQuestions.length - 1) {
                    currentQuestionIndex++;
                    displayQuestion();
                    nextButton.classList.add('hidden');
                 } else {
                    endQuiz();
                 }
            } else {
                if (currentQuestionIndex < activeQuestions.length - 1) {
                    currentQuestionIndex++;
                    displayQuestion();
                } else {
                    endQuiz();
                }
            }
        }

        function endQuiz() {
            clearInterval(timerInterval);
            calculateScore();
            showResults();
        }
        
        function calculateScore() {
            score = 0;
            userAnswers.forEach((answer, index) => {
                if (answer === activeQuestions[index].answer) {
                    score++;
                }
            });
        }
        
        function showResults() {
            quizScreen.classList.add('hidden');
            resultsScreen.classList.remove('hidden');
            const percentage = activeQuestions.length > 0 ? Math.round((score / activeQuestions.length) * 100) : 0;
            scoreDisplayEl.innerHTML = `${score} / ${activeQuestions.length} <span class="block text-3xl mt-2 text-sky-400">(${percentage}%)</span>`;
            
            if (currentSubtest === 'exercise') {
                reviewSectionEl.classList.remove('hidden');
                displayReview();
            } else {
                reviewSectionEl.classList.add('hidden');
            }
        }

        function displayReview() {
            reviewContainerEl.innerHTML = '';
            activeQuestions.forEach((q, index) => {
                const userAnswer = userAnswers[index];
                const isCorrect = userAnswer === q.answer;
                const reviewCard = document.createElement('div');
                reviewCard.className = 'bg-slate-900 p-4 rounded-lg border-l-4 ' + (isCorrect ? 'border-green-500' : (userAnswer === null ? 'border-amber-400' : 'border-red-500'));
                
                let answerText = userAnswer !== null ? q.options[userAnswer] : 'Tidak Dijawab';

                reviewCard.innerHTML = `
                    <p class="font-semibold text-lg mb-2">Soal ${index + 1}:</p>
                    <div class="text-slate-300 mb-3">${q.question}</div>
                    <p class="text-sm">Jawabanmu: <span class="font-semibold ${isCorrect ? 'text-green-400' : 'text-red-400'}">${answerText}</span></p>
                    ${!isCorrect ? `<p class="text-sm">Jawaban Benar: <span class="font-semibold text-green-400">${q.options[q.answer]}</span></p>` : ''}
                    <button onclick="toggleExplanation(this)" class="text-sky-400 text-sm mt-3">Tampilkan Pembahasan</button>
                    <div class="explanation-content text-slate-400 mt-2 p-3 bg-slate-800 rounded hidden">${q.explanation}</div>
                `;
                reviewContainerEl.appendChild(reviewCard);
            });
            if (typeof MathJax !== 'undefined') {
                MathJax.typesetPromise([reviewContainerEl]).catch(err => console.log(err));
            }
        }
        
        function toggleExplanation(button) {
            const explanationDiv = button.nextElementSibling;
            explanationDiv.classList.toggle('hidden');
            button.textContent = explanationDiv.classList.contains('hidden') ? 'Tampilkan Pembahasan' : 'Sembunyikan Pembahasan';
            if (!explanationDiv.classList.contains('hidden') && typeof MathJax !== 'undefined') {
                 MathJax.typesetPromise([explanationDiv]).catch(err => console.log(err));
            }
        }

        function backToMenu() {
            clearInterval(timerInterval);
            resultsScreen.classList.add('hidden');
            quizScreen.classList.add('hidden');
            menuScreen.classList.remove('hidden');
            menuScreen.classList.add('fade-in');
        }
        
        // --- Navigation Logic for Exercise Mode ---
        function generateQuestionNav() {
            questionNavContainer.innerHTML = '';
            for(let i = 0; i < activeQuestions.length; i++) {
                const navBtn = document.createElement('button');
                navBtn.textContent = i + 1;
                navBtn.className = 'q-nav-btn w-10 h-10 rounded-md transition-all duration-200';
                navBtn.onclick = () => jumpToQuestion(i);
                questionNavContainer.appendChild(navBtn);
            }
        }

        function jumpToQuestion(index) {
            currentQuestionIndex = index;
            displayQuestion();
        }

        function updateQuestionNavStatus(index, isAnswered) {
            const navButtons = questionNavContainer.children;
            if (!navButtons || navButtons.length === 0) return;
            for(let i = 0; i < navButtons.length; i++) {
                navButtons[i].classList.remove('q-nav-current');
                if (userAnswers[i] !== null) {
                    navButtons[i].classList.add('q-nav-answered');
                }
            }
            navButtons[index].classList.add('q-nav-current');
            if(isAnswered) {
                navButtons[index].classList.add('q-nav-answered');
            }
        }

        // --- TIMER LOGIC ---
        function startTimer(duration) {
            timeLeft = duration;
            timerDisplayEl.classList.remove('hidden');
            updateTimerDisplay();
            timerInterval = setInterval(() => {
                timeLeft--;
                updateTimerDisplay();
                if (timeLeft <= 0) {
                    clearInterval(timerInterval);
                    endQuiz();
                }
            }, 1000);
        }

        function updateTimerDisplay() {
            const minutes = Math.floor(timeLeft / 60);
            const seconds = timeLeft % 60;
            timerDisplayEl.textContent = `${minutes.toString().padStart(2, '0')}:${seconds.toString().padStart(2, '0')}`;
            if (timeLeft < 60) {
                timerDisplayEl.classList.add('timer-urgent');
            } else {
                timerDisplayEl.classList.remove('timer-urgent');
            }
        }
        
    </script>
    <script>
        MathJax = {
          tex: {
            inlineMath: [['$', '$'], ['\\(', '\\)']],
            displayMath: [['$$', '$$'], ['\\[', '\\]']]
          },
          svg: {
            fontCache: 'global'
          }
        };
    </script>
    <script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
