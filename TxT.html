```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TXT Song Vault & Prompt Lab</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Font Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        txtBlue: '#1da1f2',
                        txtCyan: '#00f2fe',
                        txtPurple: '#7b2cbf',
                        txtDark: '#0d1117',
                        txtCard: '#161b22',
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <style>
        body {
            background-color: #0b0f17;
            color: #f0f6fc;
        }
        .glow-effect {
            box-shadow: 0 0 25px rgba(0, 242, 254, 0.2);
        }
        .glow-effect:hover {
            box-shadow: 0 0 35px rgba(0, 242, 254, 0.35);
        }
        .custom-scrollbar::-webkit-scrollbar {
            width: 6px;
        }
        .custom-scrollbar::-webkit-scrollbar-track {
            background: #161b22;
        }
        .custom-scrollbar::-webkit-scrollbar-thumb {
            background: #30363d;
            border-radius: 4px;
        }
        .custom-scrollbar::-webkit-scrollbar-thumb:hover {
            background: #00f2fe;
        }
        .audio-bar {
            animation: bounce 1.2s infinite ease-in-out alternate;
        }
        @keyframes bounce {
            0% { height: 4px; }
            100% { height: 18px; }
        }
    </style>
</head>
<body class="min-h-screen flex flex-col font-sans">

    <!-- Header / Navbar -->
    <header class="border-b border-gray-800 bg-txtDark/90 backdrop-blur-md sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-16 flex items-center justify-between">
            <div class="flex items-center space-x-3">
                <div class="w-9 h-9 rounded-xl bg-gradient-to-tr from-cyan-500 to-purple-600 flex items-center justify-center text-white font-bold text-xl shadow-lg">
                    +
                </div>
                <div>
                    <h1 class="text-lg font-bold bg-gradient-to-r from-cyan-400 to-purple-400 bg-clip-text text-transparent">TXT Song Hub & Prompt Lab</h1>
                    <p class="text-xs text-gray-400 hidden sm:block">Explore Tomorrow X Together Songs, Lore & Creative Prompts</p>
                </div>
            </div>
            
            <div class="flex items-center space-x-3">
                <div id="playingStatus" class="hidden sm:flex items-center space-x-2 text-xs bg-gray-800/80 px-3 py-1.5 rounded-full border border-gray-700 text-cyan-400">
                    <span class="flex items-end space-x-0.5 h-4">
                        <span class="audio-bar w-1 bg-cyan-400 rounded-full" style="animation-delay: 0.1s"></span>
                        <span class="audio-bar w-1 bg-cyan-400 rounded-full" style="animation-delay: 0.3s"></span>
                        <span class="audio-bar w-1 bg-cyan-400 rounded-full" style="animation-delay: 0.2s"></span>
                    </span>
                    <span id="playingTrackName" class="font-medium truncate max-w-[120px]">Select a Song</span>
                </div>
                <div class="flex items-center space-x-2 text-xs bg-cyan-950/60 text-cyan-400 border border-cyan-800/80 px-3 py-1.5 rounded-full">
                    <i class="fa-solid fa-sparkles"></i>
                    <span class="font-medium">Interactive Vault</span>
                </div>
            </div>
        </div>
    </header>

    <!-- Main Content Area -->
    <main class="flex-1 max-w-7xl w-full mx-auto p-4 sm:p-6 lg:p-8 grid grid-cols-1 lg:grid-cols-12 gap-8">
        
        <!-- Sidebar / Song Selection -->
        <section class="lg:col-span-4 flex flex-col space-y-4">
            <div class="bg-txtCard p-5 rounded-2xl border border-gray-800 shadow-xl">
                <h2 class="text-base font-bold text-gray-200 mb-3 flex items-center gap-2">
                    <i class="fa-solid fa-compact-disc text-cyan-400"></i>
                    Filter TXT Discography
                </h2>
                
                <!-- Era Selector -->
                <select id="eraSelect" class="w-full bg-gray-900 border border-gray-700 text-gray-200 rounded-xl p-3 text-sm focus:outline-none focus:border-cyan-400 transition-colors cursor-pointer mb-3">
                    <option value="all">All Albums & Eras</option>
                    <option value="star">The Dream Chapter: STAR</option>
                    <option value="magic">The Dream Chapter: MAGIC</option>
                    <option value="eternity">The Dream Chapter: ETERNITY</option>
                    <option value="blue_hour">minisode 1: Blue Hour</option>
                    <option value="freeze">The Chaos Chapter: FREEZE</option>
                    <option value="fight_escape">The Chaos Chapter: FIGHT OR ESCAPE</option>
                    <option value="thursday_child">minisode 2: Thursday's Child</option>
                    <option value="temptation">The Name Chapter: TEMPTATION</option>
                    <option value="freefall">The Name Chapter: FREEFALL</option>
                    <option value="tomorrow">minisode 3: TOMORROW</option>
                    <option value="sanctuary">The Name Chapter: SANCTUARY</option>
                </select>

                <!-- Search Input -->
                <div class="relative mb-4">
                    <i class="fa-solid fa-magnifying-glass absolute left-3.5 top-3.5 text-gray-500 text-sm"></i>
                    <input type="text" id="searchInput" placeholder="Search song title or album..." class="w-full bg-gray-900 border border-gray-700 text-gray-200 pl-10 pr-4 py-2.5 rounded-xl text-sm focus:outline-none focus:border-cyan-400 transition-colors">
                </div>

                <div class="flex justify-between items-center mb-2">
                    <span class="text-xs font-semibold text-gray-400 uppercase tracking-wider">Tracks</span>
                    <span id="songCount" class="text-xs text-cyan-400 font-medium">0 songs</span>
                </div>

                <!-- Song List Container -->
                <div id="songList" class="custom-scrollbar space-y-2 max-h-[500px] overflow-y-auto pr-1">
                    <!-- Dynamic Song Items Rendered Here -->
                </div>
            </div>
        </section>

        <!-- Main Display / Track Details & Prompt Generator -->
        <section class="lg:col-span-8 flex flex-col space-y-6">
            
            <!-- Song Header Banner -->
            <div id="songBanner" class="bg-gradient-to-r from-gray-900 via-txtCard to-gray-900 border border-gray-800 rounded-2xl p-6 relative overflow-hidden shadow-2xl">
                <div class="absolute -right-10 -bottom-10 opacity-10 text-gray-100 pointer-events-none">
                    <i class="fa-solid fa-music text-[180px]"></i>
                </div>
                
                <div id="bannerContent" class="relative z-10 flex flex-col md:flex-row md:items-center justify-between gap-4">
                    <div class="flex-1">
                        <div class="flex flex-wrap items-center gap-2 mb-2">
                            <span id="albumTag" class="px-2.5 py-0.5 rounded-full text-xs font-semibold bg-cyan-950 text-cyan-400 border border-cyan-800">Album</span>
                            <span id="genreTag" class="px-2.5 py-0.5 rounded-full text-xs font-semibold bg-purple-950 text-purple-400 border border-purple-800">Genre</span>
                            <span id="yearTag" class="px-2.5 py-0.5 rounded-full text-xs font-semibold bg-gray-800 text-gray-300 border border-gray-700">Release Year</span>
                        </div>
                        <h2 id="songTitle" class="text-2xl sm:text-3xl font-extrabold text-white tracking-tight">Select a Song</h2>
                        <p id="songDescription" class="text-sm text-gray-400 mt-2 max-w-2xl leading-relaxed">Choose any TXT track from the sidebar to view song details, lore themes, and tailored creative prompts for story writing, visual art, AI image prompts, and fan theories.</p>
                    </div>

                    <!-- Audio Simulation Controls -->
                    <div class="flex flex-col items-center justify-center bg-gray-900/90 border border-gray-800 p-4 rounded-xl min-w-[140px] text-center">
                        <button id="playBtn" onclick="togglePlayTrack()" class="w-12 h-12 rounded-full bg-cyan-500 hover:bg-cyan-400 text-gray-950 flex items-center justify-center text-xl transition-all shadow-lg hover:scale-105 mb-2">
                            <i id="playIcon" class="fa-solid fa-play ml-0.5"></i>
                        </button>
                        <span id="playStatusText" class="text-xs text-gray-400 font-medium">Preview Mood</span>
                    </div>
                </div>
            </div>

            <!-- Prompt Category Tabs -->
            <div class="flex border-b border-gray-800 space-x-2 sm:space-x-4 overflow-x-auto pb-2">
                <button onclick="switchTab('visual')" id="tab-visual" class="tab-btn px-4 py-2 text-sm font-medium rounded-xl transition-all duration-200 flex items-center gap-2 bg-cyan-500/10 text-cyan-400 border border-cyan-500/30">
                    <i class="fa-solid fa-palette"></i> Visual & Concept Art
                </button>
                <button onclick="switchTab('story')" id="tab-story" class="tab-btn px-4 py-2 text-sm font-medium rounded-xl transition-all duration-200 flex items-center gap-2 text-gray-400 hover:text-gray-200 hover:bg-gray-800">
                    <i class="fa-solid fa-book-bookmark"></i> Fiction / Lore Story
                </button>
                <button onclick="switchTab('lyric')" id="tab-lyric" class="tab-btn px-4 py-2 text-sm font-medium rounded-xl transition-all duration-200 flex items-center gap-2 text-gray-400 hover:text-gray-200 hover:bg-gray-800">
                    <i class="fa-solid fa-pen-nib"></i> Lyrical Direction
                </button>
                <button onclick="switchTab('mv')" id="tab-mv" class="tab-btn px-4 py-2 text-sm font-medium rounded-xl transition-all duration-200 flex items-center gap-2 text-gray-400 hover:text-gray-200 hover:bg-gray-800">
                    <i class="fa-solid fa-clapperboard"></i> MV & Stage Concept
                </button>
            </div>

            <!-- Prompt Display Cards -->
            <div id="promptCardsContainer" class="space-y-4">
                <!-- Prompt cards will be dynamically inserted here -->
            </div>

            <!-- AI Prompt Refiner Box -->
            <div class="bg-txtCard border border-purple-900/40 rounded-2xl p-5 shadow-lg bg-gradient-to-br from-txtCard via-gray-900 to-purple-950/30">
                <div class="flex items-center justify-between mb-3">
                    <div class="flex items-center gap-2">
                        <i class="fa-solid fa-wand-magic-sparkles text-purple-400"></i>
                        <h3 class="text-sm font-bold text-gray-200">Custom Prompt Modifier</h3>
                    </div>
                    <span class="text-xs text-purple-300/70">Inject your own themes & style</span>
                </div>
                <div class="flex flex-col sm:flex-row gap-2">
                    <input type="text" id="customKeyword" placeholder="Add custom elements (e.g., 'cyberpunk theme', 'winter night', 'angst')..." class="flex-1 bg-gray-900 border border-gray-700 text-gray-200 px-4 py-2.5 rounded-xl text-sm focus:outline-none focus:border-purple-400">
                    <button onclick="refinePrompt()" class="bg-purple-600 hover:bg-purple-500 text-white text-sm font-semibold px-5 py-2.5 rounded-xl transition-all flex items-center justify-center gap-2 shadow-md hover:shadow-purple-500/25">
                        <i class="fa-solid fa-sliders"></i> Customize
                    </button>
                </div>
            </div>

        </section>

    </main>

    <!-- Notification Toast -->
    <div id="toast" class="fixed bottom-5 right-5 bg-cyan-400 text-gray-950 px-4 py-3 rounded-xl font-semibold shadow-2xl transition-all duration-300 transform translate-y-20 opacity-0 flex items-center gap-2 z-50">
        <i class="fa-solid fa-check-circle"></i>
        <span id="toastMessage">Copied to clipboard!</span>
    </div>

    <!-- Application Script -->
    <script>
        // Database of TXT Songs with extended details & prompts
        const songDatabase = [
            {
                id: "0x1_lovesong",
                title: "0X1=LOVESONG (I Know I Love You)",
                album: "The Chaos Chapter: FREEZE",
                era: "freeze",
                year: "2021",
                genre: "Pop Rock / Hybrid Emo",
                description: "A chaotic yet desperate love song expressing the total devotion of someone who believes in love amidst a crumbling, freezing world.",
                prompts: {
                    visual: "High-contrast editorial photo shoot, TXT members standing on an icy highway under a fiery sunset, wearing distressed grunge denim and leather jackets, cinematic lighting, dramatic fog, 8k resolution, raw emotion, sharp focus.",
                    story: "Write a story set in a dystopian world where the environment is gradually freezing over. Two lost teenagers make a promise to escape the ruined city together on a vintage motorcycle before nightfall.",
                    lyric: "Write a song chorus inspired by the line 'I know I love you'. Theme: Finding a singular light or purpose in a world filled with chaos, uncertainty, and noise.",
                    mv: "A music video concept combining handheld camera footage, sudden neon light flashes in ruined suburban rooms, and an explosive outdoor band performance during a meteor shower."
                }
            },
            {
                id: "losers_lover",
                title: "LO$ER=LO\u2113\u1000ER",
                album: "The Chaos Chapter: FIGHT OR ESCAPE",
                era: "fight_escape",
                year: "2021",
                genre: "Pop Punk",
                description: "An energetic pop-punk anthem celebrating youth rebellion, financial struggles, and wanting to run away with someone special.",
                prompts: {
                    visual: "Y2K pop-punk visual style, a vintage convertible driving down a desert highway filled with cash floating in the air, retro film grain, saturated neon blues and vibrant pinks, rebellious teenage aesthetic.",
                    story: "Write a coming-of-age story about two best friends who decide to leave their boring hometown with nothing but a trunk full of old cassette tapes and fifty dollars.",
                    lyric: "Draft lyrics focusing on the irony of being labeled a 'loser' by society while feeling like a winner when you're with the person you care about.",
                    mv: "A rebellious stage setup featuring a truck bed loaded with guitar amplifiers, fast zooming camera transitions, skater park aesthetics, and colorful smoke bombs."
                }
            },
            {
                id: "run_away",
                title: "9 and 3 Quarters (Run Away)",
                album: "The Dream Chapter: MAGIC",
                era: "magic",
                year: "2019",
                genre: "Synth Pop / New Wave",
                description: "A magical and nostalgic track about wanting to escape reality to a secret hidden platform or magical world where no one gets hurt.",
                prompts: {
                    visual: "Enchanted high school hallway lit by glowing magical runes, floating books, starry night sky leaking through the ceiling, rich royal blues and golden hues, magical realism photo.",
                    story: "A group of five friends discover a hidden door behind the school locker room that leads to a dimension where time stands still and summer never ends.",
                    lyric: "Write lyrics centered on magical escapes, secret handshakes, and hiding away from the pressure of growing up.",
                    mv: "Visual effects of swimming pool water turning into a gateway to a starry nebula, illuminated glowing footsteps, and running down endless corridors."
                }
            },
            {
                id: "blue_hour",
                title: "Blue Hour (\u5594\u2013\u1106\u1161\u1100\u1173\u1107\u1161\u11b7\u110b\u1173\u1102\u1173\u11ab \u110a\u1170\u110b\u1175\u110b\u1165)",
                album: "minisode 1: Blue Hour",
                era: "blue_hour",
                year: "2020",
                genre: "Dance Pop / Disco",
                description: "A bright yet bittersweet disco-pop track about the magical, fleeting moment of twilight at 5:53 PM when day turns into night.",
                prompts: {
                    visual: "A vibrant amusement park at twilight (5:53 PM), giant Ferris wheel glowing in pastel orange, lavender, and sky blue, pastel oversized coats, dreamy soft-focus aesthetic.",
                    story: "An emotional scene taking place during the final 10 minutes of sunset at a carnival, where two childhood friends must say goodbye before one moves across the globe.",
                    lyric: "Write upbeat disco-pop lyrics about wanting to freeze time at twilight so a happy moment never has to end.",
                    mv: "Choreography with long flowing trench coats and pastel hats, set against a shifting CGI sky transitioning from golden orange to deep purple-blue."
                }
            },
            {
                id: "sugar_rush_ride",
                title: "Sugar Rush Ride",
                album: "The Name Chapter: TEMPTATION",
                era: "temptation",
                year: "2023",
                genre: "Alternative Pop / Funk",
                description: "An intoxicating track detailing the sweet yet dangerous temptation that leads someone away from responsibility and growth.",
                prompts: {
                    visual: "Mystical tropical island surrounded by glowing blue flora, enchanted mist, whimsical fairytale forest, luxurious sheer garments, ethereal lighting, fantasy art style.",
                    story: "A traveler lands on an uncharted island inhabited by forest spirits who offer sweet treats that make you forget all your worldly worries and ambitions.",
                    lyric: "Write lyrics utilizing metaphors of sweets, whispers, and vertigo to describe a temptation that is impossible to resist.",
                    mv: "Traditional storytelling mixed with modern dance, featuring barefoot choreography on moss-covered forest ground under moonlight."
                }
            },
            {
                id: "dejavu",
                title: "Deja Vu",
                album: "minisode 3: TOMORROW",
                era: "tomorrow",
                year: "2024",
                genre: "Rage / Anemoia Pop Rock",
                description: "A poignant track expressing the nostalgic yearning to reunite with someone promised in the past, under a shared sky.",
                prompts: {
                    visual: "Dramatic rain falling on a desolate field of anemone flowers, five figures holding hands under a tear in the sky, moody cinematic lighting, deep red and dark grey palette.",
                    story: "A protagonist continuously experiences vivid dreams of a ruined tower and a forgotten promise, only to meet someone in real life who knows the exact same dream.",
                    lyric: "Draft lyrics exploring the feeling of 'deja vu'—believing you have loved and searched for someone across multiple lifetimes.",
                    mv: "A cinematic film trailer feel, combining high-speed tracking shots through rainstorms with quiet, intimate close-ups."
                }
            },
            {
                id: "over_the_moon",
                title: "Over The Moon",
                album: "The Name Chapter: SANCTUARY",
                era: "sanctuary",
                year: "2024",
                genre: "Pop / R&B",
                description: "A heartwarming song celebrating a tender, bright future and the blissful sanctuary found in true affection.",
                prompts: {
                    visual: "A glowing modern bedroom filled with floating star lanterns, warm amber lights, plush textures, romantic aesthetic, golden hour sunlight streaming through giant glass windows.",
                    story: "After a long journey through stormy lands, a group of travelers builds a sanctuary house on a hill where the moon always shines bright and peaceful.",
                    lyric: "Write gentle, sweet R&B-pop lyrics about feeling completely safe and elevated when you are around the person who feels like home.",
                    mv: "Cozy indoor set designs with warm color grading, synchronous elegant choreography using silky ribbons or light props."
                }
            },
            {
                id: "crown",
                title: "CROWN (\u110b\u1165\u1100\u1173\u1100\u1171\u1100\u1161 \u1107\u1161\u110c\u1161\u1102\u1173\u11ab \u1100\u1161\u110a\u1173\u1100\u1161 \u1103\u1160\u110b\u1161)",
                album: "The Dream Chapter: STAR",
                era: "star",
                year: "2019",
                genre: "Synth Pop",
                description: "TXT's iconic debut song about growing horns (symbolizing flaws or growing pains) and finding someone who sees them as a crown.",
                prompts: {
                    visual: "Vibrant graphic art style with neon green and white line doodles overlaid on energetic photo portraits, playful horn silhouettes, Y2K retro digital aesthetic.",
                    story: "A teenager wakes up with physical animal features (horns) and hides from the world until meeting another outcast with wings.",
                    lyric: "Write lyrics using metaphors of physical transformations to describe the awkwardness of growing up and self-acceptance.",
                    mv: "Bright white studio background filled with interactive 2D motion graphics and fast, energetic formation dance routines."
                }
            },
            {
                id: "chasing_that_feeling",
                title: "Chasing That Feeling",
                album: "The Name Chapter: FREEFALL",
                era: "freefall",
                year: "2023",
                genre: "80s New Wave / Synthwave",
                description: "A fast-paced 80s-inspired track about facing harsh reality head-on instead of staying in a sweet dream.",
                prompts: {
                    visual: "Cyberpunk skyscraper rooftops under night rainfall, glowing neon street signs reflecting off wet pavement, retro synthwave aesthetics, midnight blue and magenta color grading.",
                    story: "A young hero leaps off the illusionary dream sky and crashes into a gritty, real-world metropolis, determined to forge their own path.",
                    lyric: "Write energetic 80s synth-pop lyrics about leaving comforting illusions behind to embrace the painful truth of real life.",
                    mv: "High-speed night racing, rooftop parkour sequences, and glowing neon backdrops."
                }
            },
            {
                id: "good_boy_gone_bad",
                title: "Good Boy Gone Bad",
                album: "minisode 2: Thursday's Child",
                era: "thursday_child",
                year: "2022",
                genre: "Hardcore Hip-Hop / Rock",
                description: "A dark, intense song detailing the raw heartbreak, anger, and loss of innocence after a first relationship ends.",
                prompts: {
                    visual: "Eerie alleyway at midnight filled with broken mirrors, dark roses, black leather fashion, dark red rim lighting, dramatic shadows, moody gothic rock aesthetic.",
                    story: "A model student undergoes a dark transformation after experiencing his first major betrayal, embracing his darker impulses.",
                    lyric: "Write fierce, dark lyrics about burning old love letters and allowing sadness to turn into fiery anger.",
                    mv: "Gothic alley set design with red roses bursting into black flames, dramatic mirror shattering scenes, and intense dark choreography."
                }
            }
        ];

        // State Management
        let currentSelectedSong = songDatabase[0];
        let currentTab = 'visual';
        let isPlaying = false;

        // DOM Elements
        const songListEl = document.getElementById('songList');
        const eraSelectEl = document.getElementById('eraSelect');
        const searchInputEl = document.getElementById('searchInput');
        const songCountEl = document.getElementById('songCount');

        const songTitleEl = document.getElementById('songTitle');
        const albumTagEl = document.getElementById('albumTag');
        const genreTagEl = document.getElementById('genreTag');
        const yearTagEl = document.getElementById('yearTag');
        const songDescriptionEl = document.getElementById('songDescription');
        const promptCardsContainerEl = document.getElementById('promptCardsContainer');

        const playBtnEl = document.getElementById('playBtn');
        const playIconEl = document.getElementById('playIcon');
        const playStatusTextEl = document.getElementById('playStatusText');
        const playingStatusEl = document.getElementById('playingStatus');
        const playingTrackNameEl = document.getElementById('playingTrackName');

        // Render Song List in Sidebar
        function renderSongList() {
            const eraFilter = eraSelectEl.value;
            const searchQuery = searchInputEl.value.toLowerCase().trim();

            const filteredSongs = songDatabase.filter(song => {
                const matchesEra = eraFilter === 'all' || song.era === eraFilter;
                const matchesSearch = song.title.toLowerCase().includes(searchQuery) || 
                                     song.album.toLowerCase().includes(searchQuery);
                return matchesEra && matchesSearch;
            });

            songCountEl.textContent = `${filteredSongs.length} song${filteredSongs.length !== 1 ? 's' : ''}`;
            songListEl.innerHTML = '';

            if (filteredSongs.length === 0) {
                songListEl.innerHTML = `
                    <div class="text-center py-8 text-gray-500 text-xs">
                        <i class="fa-solid fa-compact-disc text-2xl mb-2 block"></i>
                        No TXT songs match your search.
                    </div>
                `;
                return;
            }

            filteredSongs.forEach(song => {
                const isSelected = song.id === currentSelectedSong.id;
                const item = document.createElement('div');
                item.className = `p-3 rounded-xl border transition-all cursor-pointer flex items-center justify-between ${
                    isSelected 
                        ? 'bg-cyan-950/40 border-cyan-500/60 text-white glow-effect' 
                        : 'bg-gray-900/60 border-gray-800 text-gray-300 hover:border-gray-700 hover:bg-gray-800/50'
                }`;
                item.onclick = () => selectSong(song);

                item.innerHTML = `
                    <div class="overflow-hidden pr-2">
                        <h4 class="text-sm font-semibold truncate ${isSelected ? 'text-cyan-400' : 'text-gray-200'}">${song.title}</h4>
                        <p class="text-xs text-gray-500 truncate">${song.album} (${song.year})</p>
                    </div>
                    <i class="fa-solid fa-chevron-right text-xs ${isSelected ? 'text-cyan-400' : 'text-gray-600'}"></i>
                `;
                songListEl.appendChild(item);
            });
        }

        // Select a Song
        function selectSong(song) {
            currentSelectedSong = song;
            renderSongList();
            updateBanner();
            renderPrompts();
            if (isPlaying) {
                playingTrackNameEl.textContent = song.title;
            }
        }

        // Update Header Banner
        function updateBanner() {
            songTitleEl.textContent = currentSelectedSong.title;
            albumTagEl.textContent = currentSelectedSong.album;
            genreTagEl.textContent = currentSelectedSong.genre;
            yearTagEl.textContent = currentSelectedSong.year;
            songDescriptionEl.textContent = currentSelectedSong.description;
        }

        // Toggle Audio Player Simulation
        function togglePlayTrack() {
            isPlaying = !isPlaying;
            if (isPlaying) {
                playIconEl.className = 'fa-solid fa-pause';
                playStatusTextEl.textContent = 'Playing Mood';
                playingStatusEl.classList.remove('hidden');
                playingStatusEl.classList.add('flex');
                playingTrackNameEl.textContent = currentSelectedSong.title;
                showToast(`Playing preview mood for ${currentSelectedSong.title}`);
            } else {
                playIconEl.className = 'fa-solid fa-play ml-0.5';
                playStatusTextEl.textContent = 'Preview Mood';
                playingStatusEl.classList.add('hidden');
                playingStatusEl.classList.remove('flex');
            }
        }

        // Switch Prompt Tabs
        function switchTab(tabKey) {
            currentTab = tabKey;
            document.querySelectorAll('.tab-btn').forEach(btn => {
                btn.className = 'tab-btn px-4 py-2 text-sm font-medium rounded-xl transition-all duration-200 flex items-center gap-2 text-gray-400 hover:text-gray-200 hover:bg-gray-800';
            });

            const activeBtn = document.getElementById(`tab-${tabKey}`);
            if (activeBtn) {
                activeBtn.className = 'tab-btn px-4 py-2 text-sm font-medium rounded-xl transition-all duration-200 flex items-center gap-2 bg-cyan-500/10 text-cyan-400 border border-cyan-500/30';
            }

            renderPrompts();
        }

        // Render Prompts for Current Selected Song & Tab
        function renderPrompts() {
            promptCardsContainerEl.innerHTML = '';
            const promptText = currentSelectedSong.prompts[currentTab];

            const titles = {
                visual: "AI Image & Visual Concept Art Prompt",
                story: "Creative Writing / Lore Fiction Prompt",
                lyric: "Songwriting & Lyric Direction",
                mv: "Music Video & Stage Performance Concept"
            };

            const icons = {
                visual: "fa-palette",
                story: "fa-book-bookmark",
                lyric: "fa-pen-nib",
                mv: "fa-clapperboard"
            };

            const card = document.createElement('div');
            card.className = "bg-txtCard border border-gray-800 rounded-2xl p-6 shadow-xl relative overflow-hidden transition-all hover:border-gray-700";
            
            card.innerHTML = `
                <div class="flex items-center justify-between mb-4">
                    <div class="flex items-center gap-2.5">
                        <div class="w-8 h-8 rounded-lg bg-cyan-950 border border-cyan-800 flex items-center justify-center text-cyan-400">
                            <i class="fa-solid ${icons[currentTab]} text-sm"></i>
                        </div>
                        <h3 class="text-base font-bold text-gray-200">${titles[currentTab]}</h3>
                    </div>
                    <button onclick="copyToClipboard('${escapeQuotes(promptText)}')" class="text-xs bg-gray-800 hover:bg-gray-700 text-cyan-400 font-semibold px-3 py-1.5 rounded-lg border border-gray-700 transition-colors flex items-center gap-1.5">
                        <i class="fa-regular fa-copy"></i> Copy Prompt
                    </button>
                </div>
                
                <div class="bg-gray-900/80 border border-gray-800 rounded-xl p-4 text-gray-300 text-sm leading-relaxed font-mono relative group">
                    <p id="activePromptText">${promptText}</p>
                </div>

                <div class="mt-4 flex flex-wrap items-center justify-between gap-3 text-xs text-gray-500 pt-3 border-t border-gray-800/60">
                    <div class="flex items-center gap-2">
                        <span class="inline-block w-2 h-2 rounded-full bg-cyan-400"></span>
                        <span>Inspired by <strong>${currentSelectedSong.title}</strong></span>
                    </div>
                    <span>Click 'Customize' below to inject custom keywords.</span>
                </div>
            `;

            promptCardsContainerEl.appendChild(card);
        }

        // Helper to escape quotes for JS function call string
        function escapeQuotes(str) {
            return str.replace(/'/g, "\\'").replace(/"/g, '&quot;');
        }

        // Copy Text to Clipboard
        function copyToClipboard(text) {
            const textarea = document.createElement('textarea');
            textarea.value = text;
            document.body.appendChild(textarea);
            textarea.select();
            document.execCommand('copy');
            document.body.removeChild(textarea);

            showToast("Copied prompt to clipboard!");
        }

        // Customize Prompt with Keyword
        function refinePrompt() {
            const keyword = document.getElementById('customKeyword').value.trim();
            if (!keyword) {
                showToast("Please enter a custom keyword first!");
                return;
            }

            const basePrompt = currentSelectedSong.prompts[currentTab];
            const refinedText = `${basePrompt} Incorporate the following elements into the theme: [${keyword}], retaining the mood and vibe of TXT's '${currentSelectedSong.title}'.`;

            document.getElementById('activePromptText').textContent = refinedText;
            showToast("Prompt refined with your keyword!");
        }

        // Toast Notification
        function showToast(message) {
            const toast = document.getElementById('toast');
            const toastMessage = document.getElementById('toastMessage');
            toastMessage.textContent = message;
            
            toast.classList.remove('translate-y-20', 'opacity-0');
            toast.classList.add('translate-y-0', 'opacity-100');

            setTimeout(() => {
                toast.classList.remove('translate-y-0', 'opacity-100');
                toast.classList.add('translate-y-20', 'opacity-0');
            }, 3000);
        }

        // Event Listeners
        eraSelectEl.addEventListener('change', renderSongList);
        searchInputEl.addEventListener('input', renderSongList);

        // Initialize App
        window.onload = function() {
            renderSongList();
            selectSong(songDatabase[0]);
        };
    </script>
</body>
</html>
```
