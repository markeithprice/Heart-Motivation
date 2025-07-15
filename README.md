# Heart-Motivation
<!DOCTYPE html>
<html lang="en" class="light"> <!-- Start with a default class -->
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Heart Motivation</title>
    
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        // Configure Tailwind CSS to use the 'class' strategy for dark mode.
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {}
            }
        }
    </script>
    
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
    <style>
        html {
            transition: font-size 0.2s ease-in-out;
        }
        body {
            font-family: 'Inter', sans-serif;
        }
    </style>
</head>
<body class="bg-gray-100 dark:bg-slate-900 transition-colors duration-300">

    <!-- Menu Bar -->
    <nav class="bg-white dark:bg-slate-800 shadow-md p-2 sticky top-0 z-50 flex justify-end items-center transition-colors duration-300">
        <div class="flex items-center space-x-2">
            <button id="theme-toggle" class="w-10 h-10 rounded-full flex items-center justify-center bg-gray-200 hover:bg-gray-300 dark:bg-slate-700 dark:text-gray-200 dark:hover:bg-slate-600 transition-colors duration-300" aria-label="Toggle theme">
                <i class="fas fa-moon"></i>
            </button>
            <button id="font-decrease" class="w-10 h-10 rounded-full flex items-center justify-center bg-gray-200 hover:bg-gray-300 dark:bg-slate-700 dark:text-gray-200 dark:hover:bg-slate-600 transition-colors duration-300" aria-label="Decrease font size">
                <i class="fas fa-font" style="font-size: 0.8rem;"></i>
            </button>
            <button id="font-increase" class="w-10 h-10 rounded-full flex items-center justify-center bg-gray-200 hover:bg-gray-300 dark:bg-slate-700 dark:text-gray-200 dark:hover:bg-slate-600 transition-colors duration-300" aria-label="Increase font size">
                <i class="fas fa-font" style="font-size: 1.2rem;"></i>
            </button>
            <button id="voice-over-toggle" class="w-10 h-10 rounded-full flex items-center justify-center bg-gray-200 hover:bg-gray-300 dark:bg-slate-700 dark:text-gray-200 dark:hover:bg-slate-600 transition-colors duration-300" aria-label="Toggle voice over">
                <i class="fas fa-microphone"></i>
            </button>
        </div>
    </nav>

    <div class="container mx-auto p-4 md:p-8">
        
        <header class="text-center mb-10">
            <h1 class="text-4xl md:text-5xl font-bold text-gray-800 dark:text-gray-100 transition-colors duration-300">Heart Motivation</h1>
            <p class="text-lg text-gray-600 dark:text-gray-300 mt-2 transition-colors duration-300">Your daily dose of inspiration and motivation.</p>
            <p class="text-md text-gray-500 dark:text-gray-400 mt-4 transition-colors duration-300">By Heart Motivation & Markeith Price</p>
        </header>

        <main class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
            
             <!-- Cards -->
            <a href="https://markeithprice.github.io/Heart-Movement/" target="_blank" class="card bg-white dark:bg-slate-800 rounded-lg shadow-lg hover:shadow-xl hover:-translate-y-1 transition-all duration-300 p-6 flex flex-col items-center text-center">
                <i class="fas fa-heartbeat text-4xl text-red-500 mb-4"></i>
                <h2 class="text-xl font-semibold text-gray-800 dark:text-gray-100 transition-colors duration-300">Heart Movement</h2>
                <p class="text-gray-500 dark:text-gray-400 mt-2 transition-colors duration-300">Get your body and mind in motion.</p>
            </a>
            <a href="https://markeithprice.github.io/Momentum-Journal/" target="_blank" class="card bg-white dark:bg-slate-800 rounded-lg shadow-lg hover:shadow-xl hover:-translate-y-1 transition-all duration-300 p-6 flex flex-col items-center text-center">
                <i class="fas fa-book-open text-4xl text-blue-500 mb-4"></i>
                <h2 class="text-xl font-semibold text-gray-800 dark:text-gray-100 transition-colors duration-300">Momentum Journal</h2>
                <p class="text-gray-500 dark:text-gray-400 mt-2 transition-colors duration-300">Track your progress and build momentum.</p>
            </a>
            <a href="https://markeithprice.github.io/Heart-Of-A-Dish/" target="_blank" class="card bg-white dark:bg-slate-800 rounded-lg shadow-lg hover:shadow-xl hover:-translate-y-1 transition-all duration-300 p-6 flex flex-col items-center text-center">
                <i class="fas fa-utensils text-4xl text-green-500 mb-4"></i>
                <h2 class="text-xl font-semibold text-gray-800 dark:text-gray-100 transition-colors duration-300">Heart Of A Dish</h2>
                <p class="text-gray-500 dark:text-gray-400 mt-2 transition-colors duration-300">Nourish your body with healthy recipes.</p>
            </a>
            <a href="https://coff.ee/markeith" target="_blank" class="card bg-white dark:bg-slate-800 rounded-lg shadow-lg hover:shadow-xl hover:-translate-y-1 transition-all duration-300 p-6 flex flex-col items-center text-center">
                <i class="fas fa-coffee text-4xl text-yellow-500 mb-4"></i>
                <h2 class="text-xl font-semibold text-gray-800 dark:text-gray-100 transition-colors duration-300">Coffee Corner</h2>
                <p class="text-gray-500 dark:text-gray-400 mt-2 transition-colors duration-300">Connect and chat over a virtual coffee.</p>
            </a>
            <a href="https://www.youtube.com/@MarkeithPriceOfficial/shorts" target="_blank" class="card bg-white dark:bg-slate-800 rounded-lg shadow-lg hover:shadow-xl hover:-translate-y-1 transition-all duration-300 p-6 flex flex-col items-center text-center">
                <i class="fab fa-youtube text-4xl text-red-600 mb-4"></i>
                <h2 class="text-xl font-semibold text-gray-800 dark:text-gray-100 transition-colors duration-300">YouTube</h2>
                <p class="text-gray-500 dark:text-gray-400 mt-2 transition-colors duration-300">Watch motivational shorts and videos.</p>
            </a>
            <a href="https://www.linkedin.com/in/markeith-price-ply-5251775a/" target="_blank" class="card bg-white dark:bg-slate-800 rounded-lg shadow-lg hover:shadow-xl hover:-translate-y-1 transition-all duration-300 p-6 flex flex-col items-center text-center">
                <i class="fab fa-linkedin text-4xl text-blue-700 mb-4"></i>
                <h2 class="text-xl font-semibold text-gray-800 dark:text-gray-100 transition-colors duration-300">LinkedIn</h2>
                <p class="text-gray-500 dark:text-gray-400 mt-2 transition-colors duration-300">Connect professionally.</p>
            </a>
            <a href="https://instagram.com/markeithprice?r=nametag" target="_blank" class="card bg-white dark:bg-slate-800 rounded-lg shadow-lg hover:shadow-xl hover:-translate-y-1 transition-all duration-300 p-6 flex flex-col items-center text-center">
                <i class="fab fa-instagram text-4xl text-pink-500 mb-4"></i>
                <h2 class="text-xl font-semibold text-gray-800 dark:text-gray-100 transition-colors duration-300">Instagram</h2>
                <p class="text-gray-500 dark:text-gray-400 mt-2 transition-colors duration-300">Follow for daily inspiration.</p>
            </a>
            <a href="https://www.tiktok.com/@markeithprice?_t=ZP-8y3TM5lxZCp&_r=1" target="_blank" class="card bg-white dark:bg-slate-800 rounded-lg shadow-lg hover:shadow-xl hover:-translate-y-1 transition-all duration-300 p-6 flex flex-col items-center text-center">
                <i class="fab fa-tiktok text-4xl text-black mb-4"></i>
                <h2 class="text-xl font-semibold text-gray-800 dark:text-gray-100 transition-colors duration-300">TikTok</h2>
                <p class="text-gray-500 dark:text-gray-400 mt-2 transition-colors duration-300">Watch short, impactful videos.</p>
            </a>

        </main>

    </div>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            // --- DOM Elements ---
            const themeToggleBtn = document.getElementById('theme-toggle');
            const fontIncreaseBtn = document.getElementById('font-increase');
            const fontDecreaseBtn = document.getElementById('font-decrease');
            const voiceOverBtn = document.getElementById('voice-over-toggle');
            const htmlElement = document.documentElement;
            const themeIcon = themeToggleBtn.querySelector('i');
            const voiceIcon = voiceOverBtn.querySelector('i');

            // --- State Variables ---
            const FONT_STEP = 1;
            const MIN_FONT_SIZE = 12;
            const MAX_FONT_SIZE = 24;
            const DEFAULT_FONT_SIZE = 16;
            let isSpeaking = false;

            // --- Functions ---

            /**
             * Updates the theme icon based on the current theme.
             */
            function updateThemeIcon() {
                if (htmlElement.classList.contains('dark')) {
                    themeIcon.classList.remove('fa-moon');
                    themeIcon.classList.add('fa-sun');
                } else {
                    themeIcon.classList.remove('fa-sun');
                    themeIcon.classList.add('fa-moon');
                }
            }
            
            /**
             * Applies the correct theme class to the <html> element based on stored preference or system settings.
             */
            function applyInitialTheme() {
                const storedTheme = localStorage.getItem('theme');
                const systemPrefersDark = window.matchMedia('(prefers-color-scheme: dark)').matches;

                if (storedTheme === 'dark' || (!storedTheme && systemPrefersDark)) {
                    htmlElement.classList.add('dark');
                } else {
                    htmlElement.classList.remove('dark');
                }
                updateThemeIcon();
            }

            /**
             * Toggles the theme and saves the preference.
             */
            function toggleTheme() {
                if (isSpeaking) {
                    window.speechSynthesis.cancel();
                }
                htmlElement.classList.toggle('dark');
                
                if (htmlElement.classList.contains('dark')) {
                    localStorage.setItem('theme', 'dark');
                } else {
                    localStorage.setItem('theme', 'light');
                }
                updateThemeIcon();
            }

            /**
             * Applies a specific font size.
             */
            function applyFontSize(size) {
                htmlElement.style.fontSize = `${size}px`;
            }

            /**
             * Changes the font size based on user action.
             */
            function changeFontSize(change) {
                let currentSize = parseFloat(getComputedStyle(htmlElement).fontSize) || DEFAULT_FONT_SIZE;
                let newSize = currentSize + change;
                newSize = Math.max(MIN_FONT_SIZE, Math.min(newSize, MAX_FONT_SIZE));
                localStorage.setItem('fontSize', newSize);
                applyFontSize(newSize);
            }

            /**
             * Toggles text-to-speech.
             */
            function toggleVoiceOver() {
                if (!('speechSynthesis' in window)) {
                    console.error("Browser does not support text-to-speech.");
                    return;
                }

                if (isSpeaking) {
                    window.speechSynthesis.cancel();
                } else {
                    const header = document.querySelector('header');
                    const cards = document.querySelectorAll('.card');
                    let textToSpeak = header.innerText.replace(/\s+/g, ' ').trim() + '. ';

                    cards.forEach(card => {
                        const title = card.querySelector('h2').innerText;
                        const description = card.querySelector('p').innerText;
                        textToSpeak += `${title}. ${description}. `;
                    });

                    const utterance = new SpeechSynthesisUtterance(textToSpeak);
                    
                    utterance.onstart = () => {
                        isSpeaking = true;
                        voiceIcon.classList.replace('fa-microphone', 'fa-stop-circle');
                    };
                    utterance.onend = () => {
                        isSpeaking = false;
                        voiceIcon.classList.replace('fa-stop-circle', 'fa-microphone');
                    };
                    utterance.onerror = () => {
                        isSpeaking = false;
                        voiceIcon.classList.replace('fa-stop-circle', 'fa-microphone');
                    };

                    window.speechSynthesis.speak(utterance);
                }
            }

            // --- Initialization ---
            
            // 1. Set the initial theme as soon as the DOM is ready.
            applyInitialTheme();

            // 2. Set the initial font size.
            const savedFontSize = localStorage.getItem('fontSize');
            if (savedFontSize) {
                applyFontSize(parseFloat(savedFontSize));
            } else {
                applyFontSize(DEFAULT_FONT_SIZE);
            }

            // 3. Attach all event listeners.
            themeToggleBtn.addEventListener('click', toggleTheme);
            fontIncreaseBtn.addEventListener('click', () => changeFontSize(FONT_STEP));
            fontDecreaseBtn.addEventListener('click', () => changeFontSize(-FONT_STEP));
            voiceOverBtn.addEventListener('click', toggleVoiceOver);
            
            window.addEventListener('beforeunload', () => {
                if(isSpeaking) {
                    window.speechSynthesis.cancel();
                }
            });
        });
    </script>
</body>
</html>

