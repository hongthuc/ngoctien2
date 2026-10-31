<html lang="vi" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ngọc Tiên Travel - Cho Thuê Xe Du Lịch Đà Nẵng - Hội An - Huế | ngoctientravel.com</title>
    <meta name="description" content="Cho thuê xe du lịch Ngọc Tiên (ngoctientravel.com) - Xe du lịch riêng có tài xế 4 chỗ, 7 chỗ, 16 chỗ tại Hội An, Đà Nẵng, Huế. Đón tận nơi, giá tốt chỉ từ 120K, phục vụ 24/7. Hotline/Zalo: 0777.977.676">
    
    <!-- THUMBNAIL KHI GỬI LINK TRANG WEB (OPEN GRAPH ZALO / FACEBOOK) -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://ngoctientravel.com/">
    <meta property="og:site_name" content="ngoctientravel.com - Xe Du Lịch Ngọc Tiên">
    <meta property="og:title" content="NGỌC TIÊN TRAVEL - Xe Du Lịch Có Tài Xế Đà Nẵng - Hội An - Huế Giá Rẻ 24/7">
    <meta property="og:description" content="Xe riêng đời mới 4 - 7 - 16 chỗ có tài xế đưa đón tận nơi. Sân bay Đà Nẵng 120K, Đà Nẵng - Hội An 250K, Bà Nà Hills 300K. Gọi ngay: 0777.977.676">
    <meta property="og:image" content="https://images.unsplash.com/photo-1559592413-7cec4d0cae2b?auto=format&fit=crop&w=1200&q=85">
    <meta property="og:image:width" content="1200">
    <meta property="og:image:height" content="630">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Ngọc Tiên Travel - Thuê Xe Đà Nẵng Hội An Huế Giá Tốt 0777.977.676">
    <meta name="twitter:image" content="https://images.unsplash.com/photo-1559592413-7cec4d0cae2b?auto=format&fit=crop&w=1200&q=85">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <!-- Google Font Inter & Montserrat chuẩn Flatsome -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Montserrat:wght@600;700;800;900&display=swap" rel="stylesheet">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        heading: ['Montserrat', 'sans-serif'],
                    },
                    colors: {
                        gold: {
                            DEFAULT: '#D4AF37',
                            light: '#F3E5AB',
                            dark: '#AA7C11',
                            accent: '#EAB308'
                        },
                        brand: {
                            dark: '#111827',
                            darker: '#0B0F19',
                            primary: '#B45309',
                            red: '#DC2626'
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Chuẩn bố cục Flatsome đơn giản dễ dựng lại bằng UX Builder */
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f1f5f9;
            color: #1e293b;
            overflow-x: hidden;
            margin: 0;
            padding: 0;
        }
        /* Khung trang vừa vặn, cân đối 2 bên trên máy tính, không bị tràn sát mép màn hình */
        .ngoctien-fullwidth-wrapper {
            width: 100%;
            max-width: 1320px;
            margin: 0 auto;
            background-color: #ffffff;
            box-shadow: 0 4px 25px rgba(0, 0, 0, 0.07);
            overflow-x: hidden;
        }
        .ngoctien-fullwidth-wrapper table {
            width: 100% !important;
            margin: 0 !important;
            border-collapse: collapse !important;
        }
        /* Reset CSS mặc định của WordPress tránh làm vỡ menu và thẻ ảnh */
        .ngoctien-fullwidth-wrapper ul,
        .ngoctien-fullwidth-wrapper ol {
            list-style: none !important;
            margin: 0 !important;
            padding: 0 !important;
        }
        .ngoctien-fullwidth-wrapper li {
            margin: 0 !important;
        }
        .ngoctien-fullwidth-wrapper img {
            margin: 0 !important;
        }
        .ngoctien-fullwidth-wrapper a {
            text-decoration: none !important;
        }
        .font-heading {
            font-family: 'Montserrat', sans-serif;
        }
        /* Hiệu ứng Nút Xem Nhanh (Quick View) chuẩn Flatsome */
        .flatsome-product-box .quick-view-btn {
            transform: translateY(100%);
            transition: transform 0.28s cubic-bezier(0.4, 0, 0.2, 1), opacity 0.28s ease;
            opacity: 0;
        }
        .flatsome-product-box:hover .quick-view-btn {
            transform: translateY(0);
            opacity: 1;
        }
        /* Trên điện thoại hiển thị sẵn thanh Xem Nhanh gọn gàng */
        @media (max-width: 768px) {
            .flatsome-product-box .quick-view-btn {
                transform: translateY(0);
                opacity: 0.95;
            }
        }
        /* Hiệu ứng phóng nhẹ ảnh sản phẩm giống Flatsome */
        .flatsome-product-box .product-img {
            transition: transform 0.45s ease;
        }
        .flatsome-product-box:hover .product-img {
            transform: scale(1.06);
        }
        /* Hiệu ứng sóng lan tỏa cho nút Hotline / Zalo / Facebook */
        @keyframes pulse-ring {
            0% { transform: scale(0.9); opacity: 0.8; }
            70% { transform: scale(1.38); opacity: 0; }
            100% { transform: scale(1.38); opacity: 0; }
        }
        .pulse-ring::before {
            content: '';
            position: absolute;
            inset: 0;
            border-radius: 9999px;
            background: inherit;
            animation: pulse-ring 1.8s infinite;
            z-index: -1;
        }
        /* Gradient Vàng Kim Hoàng Gia từ ảnh gốc Ngọc Tiên */
        .gold-gradient-text {
            background: linear-gradient(180deg, #FFF3B0 0%, #E5B842 50%, #B37D14 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .gold-gradient-bg {
            background: linear-gradient(135deg, #F59E0B 0%, #D97706 50%, #B45309 100%);
        }
        /* Tùy chỉnh thanh cuộn ngang danh mục trên mobile */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }
    </style>
</head>
<body class="w-full min-h-screen flex flex-col">
<div class="ngoctien-fullwidth-wrapper">

    <!-- ==========================================
         TOP BAR CHUẨN FLATSOME (Đơn giản, Không có thanh công cụ thừa)
    =========================================== -->
    <div class="w-full bg-brand-darker text-gray-200 border-b border-yellow-600/30 text-[11px] sm:text-xs lg:text-sm">
        <div class="w-full max-w-[1280px] mx-auto px-3 sm:px-6 lg:px-8 py-2 flex flex-wrap items-center justify-between gap-1.5">
            <div class="flex items-center gap-3 flex-wrap">
                <span class="flex items-center gap-1.5 text-yellow-400 font-semibold">
                    <i class="fa-solid fa-car-side shrink-0"></i>
                    <span class="truncate">NGỌC TIÊN TRAVEL - XE DU LỊCH CÓ TÀI XẾ 24/7</span>
                </span>
                <span class="hidden md:flex items-center gap-1.5 text-gray-300">
                    <i class="fa-solid fa-location-dot text-yellow-400"></i>
                    <span>Địa chỉ: Hội An, Đà Nẵng</span>
                </span>
            </div>
            <div class="flex items-center gap-3 ml-auto">
                <a href="tel:0777977676" class="flex items-center gap-1 text-yellow-400 font-bold hover:text-yellow-300 transition whitespace-nowrap">
                    <i class="fa-solid fa-phone-volume animate-bounce"></i>
                    <span>Hotline/Zalo: 0777.977.676</span>
                </a>
                <span class="hidden sm:inline text-gray-500">|</span>
                <span class="hidden sm:inline text-gray-300 whitespace-nowrap">Website: <strong class="text-white">ngoctientravel.com</strong></span>
            </div>
        </div>
    </div>

    <!-- ==========================================
         HEADER & LOGO + DANH MỤC TRÊN MÁY TÍNH VÀ ĐIỆN THOẠI
    =========================================== -->
    <header class="w-full bg-white shadow-md sticky top-0 z-40 border-b border-gray-100">
        <!-- Main Header Row (Tối ưu gọn gàng không bị tràn nút trên điện thoại) -->
        <div class="w-full max-w-[1280px] mx-auto px-2.5 sm:px-6 lg:px-8 py-2.5 sm:py-3 flex items-center justify-between gap-2 sm:gap-4">
            
            <!-- Nút mở Menu Danh Mục trên Điện Thoại -->
            <button onclick="toggleMobileMenu()" class="lg:hidden w-9 h-9 sm:w-10 sm:h-10 rounded-lg bg-amber-50 text-amber-800 border border-amber-200 hover:bg-amber-100 transition flex items-center justify-center shrink-0" aria-label="Menu danh mục">
                <i class="fa-solid fa-bars text-base sm:text-xl"></i>
            </button>

            <!-- THIẾT KẾ LOGO NGỌC TIÊN TRAVEL (SVG Độc Quyền Lấy Cảm Hứng Từ Ảnh Gốc) -->
            <a href="#" class="flex items-center gap-2 sm:gap-3 group min-w-0 flex-1 lg:flex-initial">
                <div class="w-10 h-10 sm:w-13 sm:h-13 rounded-xl bg-brand-darker border-2 border-yellow-500 flex items-center justify-center shadow-md relative overflow-hidden shrink-0">
                    <!-- Biểu tượng Trái Tim Bắt Tay Vàng Kim + Xe Du Lịch -->
                    <svg class="w-7 h-7 sm:w-9 sm:h-9" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <defs>
                            <linearGradient id="goldGrad" x1="0%" y1="0%" x2="100%" y2="100%">
                                <stop offset="0%" stop-color="#FFF3B0"/>
                                <stop offset="50%" stop-color="#EAB308"/>
                                <stop offset="100%" stop-color="#A16207"/>
                            </linearGradient>
                        </defs>
                        <!-- Trái tim bắt tay biểu tượng uy tín Ngọc Tiên -->
                        <path d="M32 54C32 54 10 40 10 23C10 15.5 16 10 23 10C27.4 10 30.8 12.3 32 15.2C33.2 12.3 36.6 10 41 10C48 10 54 15.5 54 23C54 40 32 54 32 54Z" stroke="url(#goldGrad)" stroke-width="3.5" fill="rgba(234,179,8,0.12)"/>
                        <path d="M21 28L28 22L35 28L43 21" stroke="url(#goldGrad)" stroke-width="3.2" stroke-linecap="round" stroke-linejoin="round"/>
                        <path d="M18 35H46L43 27H21L18 35Z" fill="url(#goldGrad)"/>
                        <circle cx="23" cy="37" r="3" fill="#FFF3B0"/>
                        <circle cx="41" cy="37" r="3" fill="#FFF3B0"/>
                    </svg>
                </div>
                <div class="min-w-0">
                    <div class="flex items-center gap-1 sm:gap-1.5">
                        <span class="font-heading font-black text-base sm:text-2xl tracking-tight text-gray-900 whitespace-nowrap">NGỌC TIÊN</span>
                        <span class="bg-amber-500 text-white text-[9px] sm:text-xs font-extrabold px-1.5 sm:px-2 py-0.5 rounded-md uppercase shrink-0">Travel</span>
                    </div>
                    <p class="text-[10px] sm:text-xs text-amber-700 font-semibold truncate">ngoctientravel.com • Hội An - Đà Nẵng</p>
                </div>
            </a>

            <!-- Thanh Tìm Kiếm Tuyến Xe Nhanh (Chuẩn Flatsome Desktop) -->
            <div class="hidden lg:flex flex-1 max-w-sm xl:max-w-md mx-2">
                <div class="relative w-full">
                    <input id="searchRouteInput" oninput="filterProductsBySearch(this.value)" type="text" placeholder="Tìm tuyến xe: Sân bay, Hội An, Bà Nà..." class="w-full pl-4 pr-10 py-2 text-xs xl:text-sm rounded-full border border-gray-300 focus:border-amber-500 focus:ring-2 focus:ring-amber-200 outline-none transition">
                    <button class="absolute right-1 top-1/2 -translate-y-1/2 w-7 h-7 rounded-full gold-gradient-bg text-white flex items-center justify-center">
                        <i class="fa-solid fa-magnifying-glass text-xs"></i>
                    </button>
                </div>
            </div>

            <!-- Cụm Thông Tin Cam Kết & Nút Gọi Nhanh Trên Header -->
            <div class="flex items-center gap-2 sm:gap-3 shrink-0">
                <div class="hidden md:flex items-center gap-2 bg-amber-50/90 border border-amber-200 px-3 py-1.5 rounded-xl">
                    <div class="w-8 h-8 rounded-full bg-amber-500 text-white flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-headset text-sm"></i>
                    </div>
                    <div class="leading-tight whitespace-nowrap">
                        <span class="text-[10px] text-gray-500 block font-medium">Đặt xe 24/7 (Zalo/WhatsApp)</span>
                        <a href="tel:0777977676" class="text-sm font-extrabold text-red-600 hover:underline">0777.977.676</a>
                    </div>
                </div>

                <a href="#form-bao-gia" class="gold-gradient-bg hover:opacity-95 text-white font-bold text-[11px] sm:text-xs lg:text-sm px-2.5 sm:px-4 py-2 sm:py-2.5 rounded-lg sm:rounded-xl shadow-md flex items-center gap-1.5 whitespace-nowrap shrink-0 transition">
                    <i class="fa-solid fa-paper-plane text-[10px] sm:text-xs"></i>
                    <span>BÁO GIÁ NHANH</span>
                </a>
            </div>
        </div>

        <!-- THANH DANH MỤC TRÊN MÁY TÍNH (Nằm trên 1 hàng ngang duy nhất, không bị rớt dòng) -->
        <nav class="hidden lg:block w-full bg-brand-darker text-white border-t border-gray-800">
            <div class="w-full max-w-[1280px] mx-auto px-4 lg:px-8 flex items-center justify-between overflow-x-auto no-scrollbar">
                <div class="flex items-center whitespace-nowrap">
                    <div class="bg-amber-500 text-gray-950 font-heading font-extrabold text-xs uppercase tracking-wider px-4 py-3 flex items-center gap-2 shrink-0">
                        <i class="fa-solid fa-list-ul text-sm"></i>
                        <span>DANH MỤC THUÊ XE</span>
                    </div>
                    <ul class="flex items-center text-xs xl:text-[13px] font-semibold whitespace-nowrap">
                        <li>
                            <button onclick="filterCategory('all')" class="nav-cat-btn px-3 xl:px-4 py-3 hover:bg-white/10 text-amber-400 transition flex items-center gap-1.5 whitespace-nowrap" data-cat="all">
                                <i class="fa-solid fa-house text-xs"></i> Trang Chủ
                            </button>
                        </li>
                        <li>
                            <button onclick="filterCategory('san-bay')" class="nav-cat-btn px-3 xl:px-4 py-3 hover:bg-white/10 hover:text-amber-400 transition flex items-center gap-1.5 whitespace-nowrap" data-cat="san-bay">
                                <i class="fa-solid fa-plane-arrival text-amber-400 text-xs"></i> Xe Đưa Đón Sân Bay
                            </button>
                        </li>
                        <li>
                            <button onclick="filterCategory('hoi-an')" class="nav-cat-btn px-3 xl:px-4 py-3 hover:bg-white/10 hover:text-amber-400 transition flex items-center gap-1.5 whitespace-nowrap" data-cat="hoi-an">
                                <i class="fa-solid fa-car-side text-amber-400 text-xs"></i> Xe Đà Nẵng ⇄ Hội An
                            </button>
                        </li>
                        <li>
                            <button onclick="filterCategory('tham-quan')" class="nav-cat-btn px-3 xl:px-4 py-3 hover:bg-white/10 hover:text-amber-400 transition flex items-center gap-1.5 whitespace-nowrap" data-cat="tham-quan">
                                <i class="fa-solid fa-mountain-sun text-amber-400 text-xs"></i> Bà Nà • Núi Thần Tài • Vinpearl
                            </button>
                        </li>
                        <li>
                            <button onclick="filterCategory('city-tour')" class="nav-cat-btn px-3 xl:px-4 py-3 hover:bg-white/10 hover:text-amber-400 transition flex items-center gap-1.5 whitespace-nowrap" data-cat="city-tour">
                                <i class="fa-solid fa-route text-amber-400 text-xs"></i> City Tour • Đi Huế
                            </button>
                        </li>
                        <li>
                            <a href="#bang-gia-goc" class="px-3 xl:px-4 py-3 hover:bg-white/10 hover:text-amber-400 transition flex items-center gap-1.5 whitespace-nowrap">
                                <i class="fa-solid fa-table-list text-amber-400 text-xs"></i> Bảng Giá Niêm Yết
                            </a>
                        </li>
                        <li>
                            <a href="#tin-tuc" class="px-3 xl:px-4 py-3 hover:bg-white/10 hover:text-amber-400 transition flex items-center gap-1.5 whitespace-nowrap">
                                <i class="fa-solid fa-newspaper text-amber-400 text-xs"></i> Kinh Nghiệm Du Lịch
                            </a>
                        </li>
                        <li>
                            <a href="#ban-do-lien-he" class="px-3 xl:px-4 py-3 hover:bg-white/10 hover:text-amber-400 transition flex items-center gap-1.5 whitespace-nowrap">
                                <i class="fa-solid fa-map-location-dot text-amber-400 text-xs"></i> Bản Đồ Hội An
                            </a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>

    <!-- DRAWER MENU DANH MỤC TRÊN ĐIỆN THOẠI (Chuẩn Off-Canvas Flatsome) -->
    <div id="mobileMenuOverlay" onclick="toggleMobileMenu()" class="fixed inset-0 bg-black/60 z-50 hidden backdrop-blur-xs"></div>
    <aside id="mobileMenuDrawer" class="fixed top-0 left-0 bottom-0 w-80 max-w-[85vw] bg-white z-50 -translate-x-full transition-transform duration-300 shadow-2xl flex flex-col">
        <div class="p-4 bg-brand-darker text-white flex items-center justify-between border-b border-yellow-500/30">
            <div class="flex items-center gap-2.5">
                <span class="w-8 h-8 rounded-lg bg-amber-500 text-gray-950 font-black flex items-center justify-center">NT</span>
                <div>
                    <p class="font-heading font-bold text-sm text-amber-400">NGỌC TIÊN TRAVEL</p>
                    <p class="text-[11px] text-gray-300">ngoctientravel.com</p>
                </div>
            </div>
            <button onclick="toggleMobileMenu()" class="w-8 h-8 rounded-lg bg-white/10 text-white flex items-center justify-center">
                <i class="fa-solid fa-xmark"></i>
            </button>
        </div>

        <!-- Tìm kiếm trong menu mobile -->
        <div class="p-3 bg-gray-50 border-b">
            <div class="relative">
                <input oninput="filterProductsBySearch(this.value)" type="text" placeholder="Tìm nhanh lộ trình thuê xe..." class="w-full pl-3.5 pr-9 py-2 text-xs rounded-lg border border-gray-300 focus:border-amber-500 outline-none">
                <i class="fa-solid fa-magnifying-glass absolute right-3 top-1/2 -translate-y-1/2 text-gray-400 text-xs"></i>
            </div>
        </div>

        <!-- Danh sách danh mục trên điện thoại -->
        <div class="p-3 flex-1 overflow-y-auto divide-y divide-gray-100 text-sm font-semibold text-gray-800">
            <button onclick="filterCategory('all'); toggleMobileMenu()" class="w-full py-3 px-2 flex items-center justify-between hover:text-amber-600">
                <span class="flex items-center gap-2.5"><i class="fa-solid fa-border-all text-amber-500 w-5"></i> Tất Cả Lộ Trình Xe</span>
                <i class="fa-solid fa-chevron-right text-xs text-gray-400"></i>
            </button>
            <button onclick="filterCategory('san-bay'); toggleMobileMenu()" class="w-full py-3 px-2 flex items-center justify-between hover:text-amber-600">
                <span class="flex items-center gap-2.5"><i class="fa-solid fa-plane-departure text-amber-500 w-5"></i> Xe Đón Tiễn Sân Bay Đà Nẵng</span>
                <span class="text-xs bg-amber-100 text-amber-800 px-2 py-0.5 rounded-full">Từ 120K</span>
            </button>
            <button onclick="filterCategory('hoi-an'); toggleMobileMenu()" class="w-full py-3 px-2 flex items-center justify-between hover:text-amber-600">
                <span class="flex items-center gap-2.5"><i class="fa-solid fa-torii-gate text-amber-500 w-5"></i> Xe Đà Nẵng ⇄ Hội An 24/7</span>
                <span class="text-xs bg-amber-100 text-amber-800 px-2 py-0.5 rounded-full">Từ 250K</span>
            </button>
            <button onclick="filterCategory('tham-quan'); toggleMobileMenu()" class="w-full py-3 px-2 flex items-center justify-between hover:text-amber-600">
                <span class="flex items-center gap-2.5"><i class="fa-solid fa-cable-car text-amber-500 w-5"></i> Xe Đi Bà Nà Hills / Núi Thần Tài</span>
                <span class="text-xs bg-amber-100 text-amber-800 px-2 py-0.5 rounded-full">Từ 300K</span>
            </button>
            <button onclick="filterCategory('city-tour'); toggleMobileMenu()" class="w-full py-3 px-2 flex items-center justify-between hover:text-amber-600">
                <span class="flex items-center gap-2.5"><i class="fa-solid fa-van-shuttle text-amber-500 w-5"></i> City Tour & Đi Cố Đô Huế</span>
                <span class="text-xs bg-amber-100 text-amber-800 px-2 py-0.5 rounded-full">Trọn gói</span>
            </button>
            <a href="#bang-gia-goc" onclick="toggleMobileMenu()" class="w-full py-3 px-2 flex items-center justify-between hover:text-amber-600">
                <span class="flex items-center gap-2.5"><i class="fa-solid fa-table text-amber-500 w-5"></i> Bảng Giá Thuê Xe Có Tài Xế</span>
                <i class="fa-solid fa-chevron-right text-xs text-gray-400"></i>
            </a>
            <a href="#form-bao-gia" onclick="toggleMobileMenu()" class="w-full py-3 px-2 flex items-center justify-between hover:text-amber-600">
                <span class="flex items-center gap-2.5"><i class="fa-solid fa-file-signature text-amber-500 w-5"></i> Yêu Cầu Báo Giá Nhanh</span>
                <i class="fa-solid fa-chevron-right text-xs text-gray-400"></i>
            </a>
            <a href="#tin-tuc" onclick="toggleMobileMenu()" class="w-full py-3 px-2 flex items-center justify-between hover:text-amber-600">
                <span class="flex items-center gap-2.5"><i class="fa-solid fa-newspaper text-amber-500 w-5"></i> Kinh Nghiệm Du Lịch</span>
                <i class="fa-solid fa-chevron-right text-xs text-gray-400"></i>
            </a>
            <a href="#ban-do-lien-he" onclick="toggleMobileMenu()" class="w-full py-3 px-2 flex items-center justify-between hover:text-amber-600">
                <span class="flex items-center gap-2.5"><i class="fa-solid fa-location-dot text-amber-500 w-5"></i> Bản Đồ Google Map Hội An</span>
                <i class="fa-solid fa-chevron-right text-xs text-gray-400"></i>
            </a>
        </div>

        <div class="p-4 bg-amber-50 border-t border-amber-200">
            <p class="text-xs text-gray-600 mb-2">Đặt xe nhanh qua Hotline / Zalo / WhatsApp:</p>
            <a href="tel:0777977676" class="w-full py-2.5 rounded-xl bg-red-600 text-white font-bold text-center block shadow">
                <i class="fa-solid fa-phone mr-1.5"></i> 0777.977.676
            </a>
        </div>
    </aside>

    <!-- ==========================================
         2 ẢNH BANNER TỰ TRƯỢT (HIỂN THỊ ĐẦY ĐỦ 100% THÔNG TIN TRÊN ĐIỆN THOẠI & MÁY TÍNH)
    =========================================== -->
    <section class="w-full relative overflow-hidden bg-brand-darker select-none">
        <div id="heroSlider" class="relative w-full min-h-[420px] sm:min-h-[460px] lg:min-h-[540px]">
            
            <!-- SLIDE 1: Thiết kế chuẩn theo Poster Ngọc Tiên (Đà Nẵng - Hội An - Huế) -->
            <div class="hero-slide absolute inset-0 transition-opacity duration-700 opacity-100 z-10 flex items-center">
                <img src="https://images.unsplash.com/photo-1559592413-7cec4d0cae2b?auto=format&fit=crop&w=1920&q=85" 
                     alt="Cầu Rồng Đà Nẵng - Phố Cổ Hội An Ngọc Tiên Travel" 
                     class="absolute inset-0 w-full h-full object-cover object-center brightness-[0.30]"
                     onerror="this.src='https://placehold.co/1920x600/111827/D4AF37?text=NGOC+TIEN+TRAVEL+-+0777.977.676'">
                <div class="absolute inset-0 bg-gradient-to-r from-black/90 via-black/70 to-black/40"></div>
                
                <div class="relative z-10 w-full max-w-[1280px] mx-auto px-4 sm:px-8 lg:px-10 py-8 sm:py-12 flex items-center">
                    <div class="max-w-3xl text-white space-y-2.5 sm:space-y-4">
                        <div class="inline-flex items-center gap-1.5 px-3 py-1 rounded-full bg-amber-500/20 border border-amber-400/50 text-amber-300 text-[11px] sm:text-sm font-semibold">
                            <i class="fa-solid fa-handshake"></i>
                            <span>XE RIÊNG CÓ TÀI XẾ – ĐÓN TẬN NƠI – PHỤC VỤ 24/7</span>
                        </div>
                        <h1 class="font-heading font-black text-2xl sm:text-5xl lg:text-6xl leading-tight tracking-tight gold-gradient-text">
                            NGỌC TIÊN TRAVEL
                        </h1>
                        <p class="font-heading font-extrabold text-base sm:text-2xl lg:text-3xl text-white tracking-wide">
                            CHUYÊN TUYẾN: ĐÀ NẴNG - HỘI AN - HUẾ
                        </p>
                        <p class="text-xs sm:text-base text-gray-200 max-w-2xl leading-relaxed">
                            Hệ thống xe 4 chỗ, 7 chỗ, 16 chỗ đời mới sạch sẽ – máy lạnh – Wifi miễn phí. Đưa đón tận nơi, miễn phí chờ sân bay, hỗ trợ đặt vé Bà Nà Hills & VinWonders giá tốt.
                        </p>
                        <!-- Tóm tắt giá nhanh ngay trên Banner Mobile & Desktop -->
                        <div class="grid grid-cols-3 gap-1.5 sm:gap-3 max-w-md pt-1">
                            <div class="bg-white/10 border border-amber-400/40 rounded-lg px-2.5 py-1.5 text-center">
                                <span class="block text-[10px] text-gray-300">Đón Sân Bay</span>
                                <strong class="text-amber-400 text-xs sm:text-sm font-extrabold">Từ 120K</strong>
                            </div>
                            <div class="bg-white/10 border border-amber-400/40 rounded-lg px-2.5 py-1.5 text-center">
                                <span class="block text-[10px] text-gray-300">Đi Hội An</span>
                                <strong class="text-amber-400 text-xs sm:text-sm font-extrabold">Từ 250K</strong>
                            </div>
                            <div class="bg-white/10 border border-amber-400/40 rounded-lg px-2.5 py-1.5 text-center">
                                <span class="block text-[10px] text-gray-300">Đi Bà Nà</span>
                                <strong class="text-amber-400 text-xs sm:text-sm font-extrabold">Từ 300K</strong>
                            </div>
                        </div>
                        <div class="pt-2 flex flex-wrap items-center gap-2.5 sm:gap-3">
                            <a href="tel:0777977676" class="gold-gradient-bg hover:brightness-110 text-gray-950 font-heading font-black text-xs sm:text-base px-4 sm:px-6 py-2.5 sm:py-3.5 rounded-xl shadow-lg flex items-center gap-2 transition">
                                <i class="fa-solid fa-phone-volume"></i>
                                <span>GỌI ĐẶT XE: 0777.977.676</span>
                            </a>
                            <a href="https://zalo.me/0777977676" target="_blank" rel="noopener noreferrer" class="bg-blue-600 hover:bg-blue-500 text-white font-bold text-xs sm:text-base px-4 sm:px-5 py-2.5 sm:py-3.5 rounded-xl shadow-lg flex items-center gap-2 transition">
                                <i class="fa-solid fa-comment-dots"></i>
                                <span>Chat Zalo / WhatsApp</span>
                            </a>
                        </div>
                    </div>
                </div>
            </div>

            <!-- SLIDE 2: Ưu Đãi Đưa Đón Sân Bay & Tham Quan Đà Nẵng - Hội An Trọn Gói -->
            <div class="hero-slide absolute inset-0 transition-opacity duration-700 opacity-0 z-0 flex items-center">
                <img src="https://images.unsplash.com/photo-1583417319070-4a69db38a482?auto=format&fit=crop&w=1920&q=85" 
                     alt="Phố Cổ Hội An Cầu Vàng Bà Nà Hills Ngọc Tiên Travel" 
                     class="absolute inset-0 w-full h-full object-cover object-center brightness-[0.32]"
                     onerror="this.src='https://placehold.co/1920x600/0f172a/EAB308?text=XE+DU+LICH+HOI+AN+DA+NANG'">
                <div class="absolute inset-0 bg-gradient-to-r from-black/90 via-black/70 to-black/40"></div>
                
                <div class="relative z-10 w-full max-w-[1280px] mx-auto px-4 sm:px-8 lg:px-10 py-8 sm:py-12 flex items-center">
                    <div class="max-w-3xl text-white space-y-2.5 sm:space-y-4">
                        <div class="inline-flex items-center gap-1.5 px-3 py-1 rounded-full bg-red-600/90 text-white text-[11px] sm:text-sm font-bold">
                            <i class="fa-solid fa-bolt"></i>
                            <span>BẢNG GIÁ TRỌN GÓI KHÔNG PHÁT SINH – CÓ HÓA ĐƠN VAT</span>
                        </div>
                        <h2 class="font-heading font-black text-xl sm:text-4xl lg:text-5xl leading-tight text-amber-400">
                            ĐÓN SÂN BAY 120K • ĐÀ NẴNG - HỘI AN 250K
                        </h2>
                        <p class="text-xs sm:text-lg text-gray-100 font-semibold">
                            Bà Nà Hills: 300K • Cù Lao Chàm: 300K • Núi Thần Tài: 350K • Vinpearl Nam Hội An: 400K
                        </p>
                        <p class="text-xs sm:text-base text-gray-300 max-w-2xl leading-relaxed">
                            Cam kết xe riêng 100% không ghép khách, đón đúng giờ tại Sân bay Đà Nẵng, Khách sạn hoặc Phố cổ Hội An. Tài xế lịch sự, phục vụ tận tâm 24/7.
                        </p>
                        <div class="pt-2 flex flex-wrap items-center gap-2.5 sm:gap-3">
                            <a href="#form-bao-gia" class="gold-gradient-bg text-gray-950 font-heading font-black text-xs sm:text-base px-4 sm:px-6 py-2.5 sm:py-3.5 rounded-xl shadow-lg flex items-center gap-2">
                                <i class="fa-solid fa-calculator"></i>
                                <span>NHẬN BÁO GIÁ TỰ ĐỘNG</span>
                            </a>
                            <a href="#bang-gia-goc" class="bg-white/15 hover:bg-white/25 backdrop-blur-xs border border-white/30 text-white font-bold text-xs sm:text-base px-4 sm:px-5 py-2.5 sm:py-3.5 rounded-xl flex items-center gap-2 transition">
                                <i class="fa-solid fa-table-list"></i>
                                <span>Xem Bảng Giá Chi Tiết</span>
                            </a>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Nút điều hướng 2 Banner tự trượt (Đặt gọn ở góc dưới bên phải trên điện thoại để không che chữ) -->
            <button onclick="prevSlide()" aria-label="Slide trước" class="hidden sm:flex absolute left-4 top-1/2 -translate-y-1/2 z-20 w-10 h-10 rounded-full bg-black/40 hover:bg-amber-500 text-white hover:text-gray-950 border border-white/20 items-center justify-center transition">
                <i class="fa-solid fa-chevron-left"></i>
            </button>
            <button onclick="nextSlide()" aria-label="Slide tiếp" class="hidden sm:flex absolute right-4 top-1/2 -translate-y-1/2 z-20 w-10 h-10 rounded-full bg-black/40 hover:bg-amber-500 text-white hover:text-gray-950 border border-white/20 items-center justify-center transition">
                <i class="fa-solid fa-chevron-right"></i>
            </button>

            <!-- Dots chỉ báo Banner -->
            <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2.5">
                <button onclick="goToSlide(0)" id="sliderDot0" class="w-8 h-2.5 rounded-full bg-amber-400 transition-all"></button>
                <button onclick="goToSlide(1)" id="sliderDot1" class="w-2.5 h-2.5 rounded-full bg-white/50 hover:bg-white transition-all"></button>
            </div>
        </div>
    </section>

    <!-- ==========================================
         4 CAM KẾT VÀNG TỪ ẢNH GỐC NGỌC TIÊN (Tối ưu hiển thị đẹp trên cả Điện Thoại & Máy Tính)
    =========================================== -->
    <section class="w-full bg-white border-b border-gray-200 py-4 sm:py-7">
        <div class="w-full max-w-[1280px] mx-auto px-3 sm:px-6 lg:px-8">
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-2.5 sm:gap-5">
                <!-- Cam kết 1 -->
                <div class="flex flex-col sm:flex-row items-start sm:items-center gap-2 sm:gap-3.5 p-3 sm:p-4 rounded-2xl bg-amber-50/60 border border-amber-200/80">
                    <div class="w-9 h-9 sm:w-12 sm:h-12 rounded-xl bg-brand-darker text-amber-400 flex items-center justify-center text-sm sm:text-xl shrink-0">
                        <i class="fa-solid fa-star"></i>
                    </div>
                    <div class="min-w-0">
                        <h3 class="font-heading font-bold text-xs sm:text-sm text-gray-900 uppercase">HỖ TRỢ ĐẶT VÉ</h3>
                        <p class="text-[11px] sm:text-xs text-gray-600 mt-0.5 leading-snug">Bà Nà Hills, VinWonders, Sun World</p>
                    </div>
                </div>
                <!-- Cam kết 2 -->
                <div class="flex flex-col sm:flex-row items-start sm:items-center gap-2 sm:gap-3.5 p-3 sm:p-4 rounded-2xl bg-amber-50/60 border border-amber-200/80">
                    <div class="w-9 h-9 sm:w-12 sm:h-12 rounded-xl bg-brand-darker text-amber-400 flex items-center justify-center text-sm sm:text-xl shrink-0">
                        <i class="fa-solid fa-user-tie"></i>
                    </div>
                    <div class="min-w-0">
                        <h3 class="font-heading font-bold text-xs sm:text-sm text-gray-900 uppercase">TÀI XẾ THÂN THIỆN</h3>
                        <p class="text-[11px] sm:text-xs text-gray-600 mt-0.5 leading-snug">Đúng giờ – An toàn – Chu đáo</p>
                    </div>
                </div>
                <!-- Cam kết 3 -->
                <div class="flex flex-col sm:flex-row items-start sm:items-center gap-2 sm:gap-3.5 p-3 sm:p-4 rounded-2xl bg-amber-50/60 border border-amber-200/80">
                    <div class="w-9 h-9 sm:w-12 sm:h-12 rounded-xl bg-brand-darker text-amber-400 flex items-center justify-center text-sm sm:text-xl shrink-0">
                        <i class="fa-solid fa-shield-halved"></i>
                    </div>
                    <div class="min-w-0">
                        <h3 class="font-heading font-bold text-xs sm:text-sm text-gray-900 uppercase">XE ĐỜI MỚI</h3>
                        <p class="text-[11px] sm:text-xs text-gray-600 mt-0.5 leading-snug">Sạch sẽ – Máy lạnh – Wifi</p>
                    </div>
                </div>
                <!-- Cam kết 4 -->
                <div class="flex flex-col sm:flex-row items-start sm:items-center gap-2 sm:gap-3.5 p-3 sm:p-4 rounded-2xl bg-amber-50/60 border border-amber-200/80">
                    <div class="w-9 h-9 sm:w-12 sm:h-12 rounded-xl bg-brand-darker text-amber-400 flex items-center justify-center text-sm sm:text-xl shrink-0">
                        <i class="fa-solid fa-clock-rotate-left"></i>
                    </div>
                    <div class="min-w-0">
                        <h3 class="font-heading font-bold text-xs sm:text-sm text-gray-900 uppercase">PHỤC VỤ 24/7</h3>
                        <p class="text-[11px] sm:text-xs text-gray-600 mt-0.5 leading-snug">Đưa đón tận nơi – Miễn phí chờ</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC SẢN PHẨM TRỰC QUAN (Đẹp trên cả Máy Tính & Điện Thoại)
    =========================================== -->
    <section class="w-full py-6 sm:py-9 bg-gray-50">
        <div class="w-full max-w-[1280px] mx-auto px-3 sm:px-6 lg:px-8">
            <!-- Tiêu đề Section chuẩn Flatsome -->
            <div class="flex flex-col sm:flex-row sm:items-end justify-between mb-5 gap-2 border-b-2 border-gray-200 pb-3">
                <div>
                    <span class="text-xs font-extrabold uppercase tracking-wider text-amber-600">DANH MỤC DỊCH VỤ THUÊ XE</span>
                    <h2 class="font-heading font-extrabold text-xl sm:text-2xl lg:text-3xl text-gray-900">
                        CHỌN DÒNG XE & LỘ TRÌNH PHÙ HỢP
                    </h2>
                </div>
                <p class="text-xs sm:text-sm text-gray-600">
                    Bấm vào từng danh mục để lọc nhanh bảng giá xe 4 chỗ, 7 chỗ, 16 chỗ
                </p>
            </div>

            <!-- Grid Danh Mục Tối Ưu Cho Cả Mobile (2-3 cột) & Desktop (5 cột Full Màn Hình) -->
            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 gap-2.5 sm:gap-4">
                <button onclick="filterCategory('all')" id="catCard-all" class="cat-card group p-3.5 sm:p-4 rounded-2xl bg-brand-darker text-white border-2 border-amber-500 shadow-md flex items-center gap-3 text-left transition">
                    <div class="w-11 h-11 rounded-xl bg-amber-500 text-gray-950 flex items-center justify-center text-lg shrink-0 font-bold">
                        <i class="fa-solid fa-layer-group"></i>
                    </div>
                    <div>
                        <h3 class="font-heading font-bold text-xs sm:text-sm">Tất Cả Lộ Trình</h3>
                        <p class="text-[11px] text-amber-300">12 tuyến phổ biến</p>
                    </div>
                </button>

                <button onclick="filterCategory('san-bay')" id="catCard-san-bay" class="cat-card group p-3.5 sm:p-4 rounded-2xl bg-white hover:bg-amber-50 text-gray-900 border border-gray-200 hover:border-amber-400 shadow-xs flex items-center gap-3 text-left transition">
                    <div class="w-11 h-11 rounded-xl bg-amber-100 text-amber-700 group-hover:bg-amber-500 group-hover:text-white flex items-center justify-center text-lg shrink-0 transition">
                        <i class="fa-solid fa-plane-arrival"></i>
                    </div>
                    <div>
                        <h3 class="font-heading font-bold text-xs sm:text-sm">Đón Tiễn Sân Bay</h3>
                        <p class="text-[11px] text-gray-500">Chỉ từ 120.000đ</p>
                    </div>
                </button>

                <button onclick="filterCategory('hoi-an')" id="catCard-hoi-an" class="cat-card group p-3.5 sm:p-4 rounded-2xl bg-white hover:bg-amber-50 text-gray-900 border border-gray-200 hover:border-amber-400 shadow-xs flex items-center gap-3 text-left transition">
                    <div class="w-11 h-11 rounded-xl bg-amber-100 text-amber-700 group-hover:bg-amber-500 group-hover:text-white flex items-center justify-center text-lg shrink-0 transition">
                        <i class="fa-solid fa-car-rear"></i>
                    </div>
                    <div>
                        <h3 class="font-heading font-bold text-xs sm:text-sm">Đà Nẵng ⇄ Hội An</h3>
                        <p class="text-[11px] text-gray-500">Chỉ từ 250.000đ</p>
                    </div>
                </button>

                <button onclick="filterCategory('tham-quan')" id="catCard-tham-quan" class="cat-card group p-3.5 sm:p-4 rounded-2xl bg-white hover:bg-amber-50 text-gray-900 border border-gray-200 hover:border-amber-400 shadow-xs flex items-center gap-3 text-left transition">
                    <div class="w-11 h-11 rounded-xl bg-amber-100 text-amber-700 group-hover:bg-amber-500 group-hover:text-white flex items-center justify-center text-lg shrink-0 transition">
                        <i class="fa-solid fa-mountain-city"></i>
                    </div>
                    <div>
                        <h3 class="font-heading font-bold text-xs sm:text-sm">Bà Nà • Thần Tài</h3>
                        <p class="text-[11px] text-gray-500">Chỉ từ 300.000đ</p>
                    </div>
                </button>

                <button onclick="filterCategory('city-tour')" id="catCard-city-tour" class="cat-card col-span-2 sm:col-span-1 group p-3.5 sm:p-4 rounded-2xl bg-white hover:bg-amber-50 text-gray-900 border border-gray-200 hover:border-amber-400 shadow-xs flex items-center gap-3 text-left transition">
                    <div class="w-11 h-11 rounded-xl bg-amber-100 text-amber-700 group-hover:bg-amber-500 group-hover:text-white flex items-center justify-center text-lg shrink-0 transition">
                        <i class="fa-solid fa-van-shuttle"></i>
                    </div>
                    <div>
                        <h3 class="font-heading font-bold text-xs sm:text-sm">City Tour & Đi Huế</h3>
                        <p class="text-[11px] text-gray-500">Xe 4 - 7 - 16 chỗ</p>
                    </div>
                </button>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH SÁCH SẢN PHẨM DỊCH VỤ THUÊ XE (CHUẨN FLATSOME)
         - Điện thoại: Chia 2 cột (grid-cols-2)
         - Máy tính: Chia 4 cột Full màn hình 2 bên (lg:grid-cols-4)
         - Có giá gốc gạch ngang + Giá giảm + % giảm giá giống Flatsome
         - Có nút XEM NHANH (Quick View) chuẩn Flatsome
    =========================================== -->
    <section id="danh-sach-xe" class="w-full py-6 sm:py-10 bg-white">
        <div class="w-full max-w-[1280px] mx-auto px-3 sm:px-6 lg:px-8">
            
            <!-- Header Section -->
            <div class="flex flex-wrap items-center justify-between gap-3 mb-6 pb-3 border-b-2 border-amber-500">
                <div class="flex items-center gap-2.5">
                    <span class="w-2 h-7 rounded-full bg-amber-500"></span>
                    <h2 id="productSectionTitle" class="font-heading font-extrabold text-lg sm:text-2xl lg:text-3xl text-gray-900 uppercase">
                        DỊCH VỤ THUÊ XE CÓ TÀI XẾ NGỌC TIÊN
                    </h2>
                </div>
                <div class="flex items-center gap-2 text-xs sm:text-sm text-gray-600 font-medium">
                    <span>Hotline đặt nhanh:</span>
                    <a href="tel:0777977676" class="text-red-600 font-extrabold hover:underline">0777.977.676</a>
                </div>
            </div>

            <!-- GRID SẢN PHẨM: 2 CỘT TRÊN ĐIỆN THOẠI (grid-cols-2) & 4 CỘT TRÊN MÁY TÍNH -->
            <div id="productGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-5 lg:gap-6">
                <!-- Các thẻ sản phẩm được render tự động từ dữ liệu bảng giá Ngọc Tiên + mẫu xedananghoiangiare.com -->
            </div>
        </div>
    </section>

    <!-- ==========================================
         BẢNG GIÁ THUÊ XE CÓ TÀI XẾ NIÊM YẾT (CHUẨN 100% TỪ ẢNH GỐC NGỌC TIÊN)
    =========================================== -->
    <section id="bang-gia-goc" class="w-full py-10 sm:py-14 bg-brand-darker text-white relative overflow-hidden">
        <div class="w-full max-w-[1280px] mx-auto px-3 sm:px-6 lg:px-8 relative z-10">
            
            <div class="text-center max-w-3xl mx-auto mb-7 sm:mb-9">
                <span class="inline-block px-3.5 py-1 rounded-full bg-amber-500/20 border border-amber-400/40 text-amber-300 text-xs font-bold uppercase tracking-wider mb-2">
                    BẢNG GIÁ NIÊM YẾT CÔNG KHAI
                </span>
                <h2 class="font-heading font-black text-2xl sm:text-4xl gold-gradient-text uppercase">
                    BẢNG GIÁ THUÊ XE CÓ TÀI XẾ NGỌC TIÊN
                </h2>
                <p class="text-xs sm:text-sm text-gray-300 mt-2">
                    Đưa đón tận nơi tại Đà Nẵng – Hội An – Huế • Miễn phí chờ đón sân bay • Có xuất hóa đơn VAT
                </p>
            </div>

            <!-- Bảng giá viền vàng kim, chữ tên dịch vụ màu đen rõ nét -->
            <div class="overflow-x-auto rounded-2xl border-2 border-amber-500 shadow-2xl bg-white">
                <table class="w-full text-left border-collapse" style="width: 100% !important; margin: 0 !important;">
                    <thead>
                        <tr class="gold-gradient-bg text-gray-950 font-heading font-black text-xs sm:text-base uppercase">
                            <th class="py-3.5 sm:py-4 px-3 sm:px-6 border-r border-amber-700/30" style="color: #000000 !important;">THUÊ XE CÓ TÀI XẾ (LỘ TRÌNH)</th>
                            <th class="py-3.5 sm:py-4 px-2 sm:px-5 text-center border-r border-amber-700/30" style="color: #000000 !important;">XE 4 CHỖ</th>
                            <th class="py-3.5 sm:py-4 px-2 sm:px-5 text-center border-r border-amber-700/30" style="color: #000000 !important;">XE 7 CHỖ</th>
                            <th class="py-3.5 sm:py-4 px-2 sm:px-5 text-center border-r border-amber-700/30" style="color: #000000 !important;">XE 16 CHỖ</th>
                            <th class="py-3.5 sm:py-4 px-3 sm:px-5 text-center hidden sm:table-cell" style="color: #000000 !important;">ĐẶT NHANH</th>
                        </tr>
                    </thead>
                    <tbody class="divide-y divide-gray-200 text-xs sm:text-base font-semibold bg-white">
                        <tr class="bg-white hover:bg-amber-50/70 transition">
                            <td class="py-3.5 px-3 sm:px-6 font-extrabold text-black" style="color: #000000 !important;">SÂN BAY - KHÁCH SẠN ĐÀ NẴNG</td>
                            <td class="py-3.5 px-2 sm:px-5 text-center text-amber-600 font-extrabold">120K</td>
                            <td class="py-3.5 px-2 sm:px-5 text-center text-amber-600 font-extrabold">150K</td>
                            <td class="py-3.5 px-2 sm:px-5 text-center text-amber-600 font-extrabold">300K</td>
                            <td class="py-3.5 px-3 sm:px-5 text-center hidden sm:table-cell">
                                <button onclick="selectRouteForQuote('Sân bay - Khách sạn Đà Nẵng', 120000)" class="px-3.5 py-1.5 rounded-lg bg-amber-500 hover:bg-amber-400 text-gray-950 font-bold text-xs shadow-xs">Chọn tuyến</button>
                            </td>
                        </tr>
                        <tr class="bg-gray-50/80 hover:bg-amber-50/70 transition">
                            <td class="py-3.5 px-3 sm:px-6 font-extrabold text-black" style="color: #000000 !important;">ĐÀ NẴNG - HỘI AN</td>
                            <td class="py-3.5 px-2 sm:px-5 text-center text-amber-600 font-extrabold">250K</td>
                            <td class="py-3.5 px-2 sm:px-5 text-center text-amber-600 font-extrabold">300K</td>
                            <td class="py-3.5 px-2 sm:px-5 text-center text-amber-600 font-extrabold">450K</td>
                            <td class="py-3.5 px-3 sm:px-5 text-center hidden sm:table-cell">
                                <button onclick="selectRouteForQuote('Đà Nẵng - Hội An', 250000)" class="px-3.5 py-1.5 rounded-lg bg-amber-500 hover:bg-amber-400 text-gray-950 font-bold text-xs shadow-xs">Chọn tuyến</button>
                            </td>
                        </tr>
                        <tr class="bg-white hover:bg-amber-50/70 transition">
                            <td class="py-3.5 px-3 sm:px-6 font-extrabold text-black" style="color: #000000 !important;">ĐÀ NẴNG - BÀ NÀ HILLS</td>
                            <td class="py-3.5 px-2 sm:px-5 text-center text-amber-600 font-extrabold">300K</td>
                            <td class="py-3.5 px-2 sm:px-5 text-center text-amber-600 font-extrabold">350K</td>
                            <td class="py-3.5 px-2 sm:px-5 text-center text-amber-600 font-extrabold">500K</td>
                            <td class="py-3.5 px-3 sm:px-5 text-center hidden sm:table-cell">
                                <button onclick="selectRouteForQuote('Đà Nẵng - Bà Nà Hills', 300000)" class="px-3.5 py-1.5 rounded-lg bg-amber-500 hover:bg-amber-400 text-gray-950 font-bold text-xs shadow-xs">Chọn tuyến</button>
                            </td>
                        </tr>
                        <tr class="bg-gray-50/80 hover:bg-amber-50/70 transition">
                            <td class="py-3.5 px-3 sm:px-6 font-extrabold text-black" style="color: #000000 !important;">ĐÀ NẴNG - CÙ LAO CHÀM</td>
                            <td class="py-3.5 px-2 sm:px-5 text-center text-amber-600 font-extrabold">300K</td>
                            <td class="py-3.5 px-2 sm:px-5 text-center text-amber-600 font-extrabold">350K</td>
                            <td class="py-3.5 px-2 sm:px-5 text-center text-amber-600 font-extrabold">450K</td>
                            <td class="py-3.5 px-3 sm:px-5 text-center hidden sm:table-cell">
                                <button onclick="selectRouteForQuote('Đà Nẵng - Cù Lao Chàm', 300000)" class="px-3.5 py-1.5 rounded-lg bg-amber-500 hover:bg-amber-400 text-gray-950 font-bold text-xs shadow-xs">Chọn tuyến</button>
                            </td>
                        </tr>
                        <tr class="bg-white hover:bg-amber-50/70 transition">
                            <td class="py-3.5 px-3 sm:px-6 font-extrabold text-black" style="color: #000000 !important;">ĐÀ NẴNG - NÚI THẦN TÀI</td>
                            <td class="py-3.5 px-2 sm:px-5 text-center text-amber-600 font-extrabold">350K</td>
                            <td class="py-3.5 px-2 sm:px-5 text-center text-amber-600 font-extrabold">400K</td>
                            <td class="py-3.5 px-2 sm:px-5 text-center text-amber-600 font-extrabold">600K</td>
                            <td class="py-3.5 px-3 sm:px-5 text-center hidden sm:table-cell">
                                <button onclick="selectRouteForQuote('Đà Nẵng - Núi Thần Tài', 350000)" class="px-3.5 py-1.5 rounded-lg bg-amber-500 hover:bg-amber-400 text-gray-950 font-bold text-xs shadow-xs">Chọn tuyến</button>
                            </td>
                        </tr>
                        <tr class="bg-gray-50/80 hover:bg-amber-50/70 transition">
                            <td class="py-3.5 px-3 sm:px-6 font-extrabold text-black" style="color: #000000 !important;">ĐÀ NẴNG - VINPEARL NAM HỘI AN</td>
                            <td class="py-3.5 px-2 sm:px-5 text-center text-amber-600 font-extrabold">400K</td>
                            <td class="py-3.5 px-2 sm:px-5 text-center text-amber-600 font-extrabold">450K</td>
                            <td class="py-3.5 px-2 sm:px-5 text-center text-amber-600 font-extrabold">650K</td>
                            <td class="py-3.5 px-3 sm:px-5 text-center hidden sm:table-cell">
                                <button onclick="selectRouteForQuote('Đà Nẵng - Vinpearl Nam Hội An', 400000)" class="px-3.5 py-1.5 rounded-lg bg-amber-500 hover:bg-amber-400 text-gray-950 font-bold text-xs shadow-xs">Chọn tuyến</button>
                            </td>
                        </tr>
                        <tr class="bg-white hover:bg-amber-50/70 transition">
                            <td class="py-3.5 px-3 sm:px-6 font-extrabold text-black" style="color: #000000 !important;">ĐÓN & TIỄN BAY + ĂN</td>
                            <td class="py-3.5 px-2 sm:px-5 text-center text-amber-600 font-extrabold">200K</td>
                            <td class="py-3.5 px-2 sm:px-5 text-center text-amber-600 font-extrabold">250K</td>
                            <td class="py-3.5 px-2 sm:px-5 text-center text-amber-600 font-extrabold">500K</td>
                            <td class="py-3.5 px-3 sm:px-5 text-center hidden sm:table-cell">
                                <button onclick="selectRouteForQuote('Đón & Tiễn Bay + Ăn', 200000)" class="px-3.5 py-1.5 rounded-lg bg-amber-500 hover:bg-amber-400 text-gray-950 font-bold text-xs shadow-xs">Chọn tuyến</button>
                            </td>
                        </tr>
                        <tr class="bg-gray-50/80 hover:bg-amber-50/70 transition">
                            <td class="py-3.5 px-3 sm:px-6 font-extrabold text-black" style="color: #000000 !important;">CITY TOUR ĐÀ NẴNG / HỘI AN</td>
                            <td class="py-3.5 px-2 sm:px-5 text-center text-amber-600 font-extrabold">1000K</td>
                            <td class="py-3.5 px-2 sm:px-5 text-center text-amber-600 font-extrabold">1200K</td>
                            <td class="py-3.5 px-2 sm:px-5 text-center text-amber-600 font-extrabold">1500K</td>
                            <td class="py-3.5 px-3 sm:px-5 text-center hidden sm:table-cell">
                                <button onclick="selectRouteForQuote('City Tour Đà Nẵng - Hội An', 1000000)" class="px-3.5 py-1.5 rounded-lg bg-amber-500 hover:bg-amber-400 text-gray-950 font-bold text-xs shadow-xs">Chọn tuyến</button>
                            </td>
                        </tr>
                    </tbody>
                </table>
            </div>

            <p class="text-center text-xs sm:text-sm text-amber-300/90 italic mt-4">
                – Giá trên áp dụng 1 chiều – Liên hệ Hotline/Zalo <strong>0777.977.676</strong> để nhận báo giá khứ hồi 2 chiều ưu đãi – Có xuất hóa đơn VAT –
            </p>
        </div>
    </section>

    <!-- ==========================================
         FORM YÊU CẦU VÀ BÁO GIÁ TRANG CHỦ (TỰ ĐỘNG TÍNH GIÁ & GỬI ZALO)
    =========================================== -->
    <section id="form-bao-gia" class="w-full py-10 sm:py-14 bg-amber-50/70 border-b border-gray-200">
        <div class="w-full max-w-[1280px] mx-auto px-3 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center">
                
                <!-- Cột Trái: Thông tin các dòng xe 4 - 7 - 16 chỗ -->
                <div class="lg:col-span-5 space-y-4">
                    <span class="text-xs font-extrabold uppercase tracking-wider text-amber-700 bg-amber-200/70 px-3 py-1 rounded-full">
                        ĐẶT XE & BÁO GIÁ TRỰC TUYẾN 24/7
                    </span>
                    <h2 class="font-heading font-extrabold text-2xl sm:text-3xl text-gray-900 leading-tight">
                        YÊU CẦU ĐẶT XE & NHẬN BÁO GIÁ NGAY
                    </h2>
                    <p class="text-xs sm:text-sm text-gray-600 leading-relaxed">
                        Quý khách chỉ cần chọn tuyến đường, loại xe (4 chỗ, 7 chỗ, 16 chỗ) và thời gian đón. Hệ thống của <strong>Ngọc Tiên Travel (ngoctientravel.com)</strong> sẽ tính giá dự kiến tức thì và phản hồi ngay trong 1 phút!
                    </p>

                    <div class="space-y-3 pt-2">
                        <div class="p-3.5 rounded-xl bg-white border border-gray-200 shadow-xs flex items-center gap-3.5">
                            <div class="w-12 h-12 rounded-xl bg-amber-100 text-amber-700 flex items-center justify-center text-xl shrink-0">
                                <i class="fa-solid fa-car"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-sm text-gray-900">Xe 4 Chỗ Sedan Đời Mới</h4>
                                <p class="text-xs text-gray-600">Toyota Vios, Accent, Mazda 3, Cerato (Phù hợp 1 - 3 khách + hành lý)</p>
                            </div>
                        </div>
                        <div class="p-3.5 rounded-xl bg-white border border-gray-200 shadow-xs flex items-center gap-3.5">
                            <div class="w-12 h-12 rounded-xl bg-amber-100 text-amber-700 flex items-center justify-center text-xl shrink-0">
                                <i class="fa-solid fa-truck-pickup"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-sm text-gray-900">Xe 7 Chỗ SUV Rộng Rãi</h4>
                                <p class="text-xs text-gray-600">Mitsubishi Xpander, Toyota Cross, Innova, Fortuner (Phù hợp 4 - 6 khách)</p>
                            </div>
                        </div>
                        <div class="p-3.5 rounded-xl bg-white border border-gray-200 shadow-xs flex items-center gap-3.5">
                            <div class="w-12 h-12 rounded-xl bg-amber-100 text-amber-700 flex items-center justify-center text-xl shrink-0">
                                <i class="fa-solid fa-van-shuttle"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-sm text-gray-900">Xe 16 Chỗ Du Lịch Đoàn</h4>
                                <p class="text-xs text-gray-600">Ford Transit, Hyundai Solati đời mới cao cấp (Phù hợp 7 - 15 khách)</p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Cột Phải: Form Yêu Cầu Và Báo Giá Trang Chủ Chuẩn Flatsome -->
                <div class="lg:col-span-7">
                    <div class="bg-white rounded-2xl shadow-xl border-2 border-amber-400 p-5 sm:p-8">
                        <div class="flex items-center justify-between border-b border-gray-100 pb-4 mb-5">
                            <div>
                                <h3 class="font-heading font-extrabold text-lg sm:text-xl text-gray-900">FORM YÊU CẦU & BÁO GIÁ TỰ ĐỘNG</h3>
                                <p class="text-xs text-gray-500">Miễn phí chờ sân bay • Đón tận nơi Hội An - Đà Nẵng - Huế</p>
                            </div>
                            <span class="bg-red-100 text-red-700 text-xs font-extrabold px-3 py-1 rounded-full">Giảm tới 20%</span>
                        </div>

                        <form id="quoteForm" onsubmit="submitQuoteForm(event)" class="space-y-4">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                <div>
                                    <label class="block text-xs font-bold text-gray-700 uppercase mb-1">Họ và tên quý khách *</label>
                                    <input id="qName" type="text" required placeholder="Nhập họ tên của bạn..." class="w-full px-3.5 py-2.5 rounded-xl border border-gray-300 focus:border-amber-500 focus:ring-2 focus:ring-amber-200 outline-none text-sm">
                                </div>
                                <div>
                                    <label class="block text-xs font-bold text-gray-700 uppercase mb-1">Số điện thoại / Zalo *</label>
                                    <input id="qPhone" type="tel" required placeholder="Ví dụ: 0905xxxxxx" class="w-full px-3.5 py-2.5 rounded-xl border border-gray-300 focus:border-amber-500 focus:ring-2 focus:ring-amber-200 outline-none text-sm">
                                </div>
                            </div>

                            <div class="grid grid-cols-1 sm:grid-cols-3 gap-4">
                                <div>
                                    <label class="block text-xs font-bold text-gray-700 uppercase mb-1">Chọn tuyến hành trình *</label>
                                    <select id="qRoute" onchange="calculateEstimatedQuote()" class="w-full px-3.5 py-2.5 rounded-xl border border-gray-300 focus:border-amber-500 outline-none text-sm bg-white">
                                        <option value="san-bay">Sân Bay ⇄ Khách Sạn Đà Nẵng</option>
                                        <option value="hoi-an" selected>Đà Nẵng ⇄ Phố Cổ Hội An</option>
                                        <option value="ba-na">Đà Nẵng ⇄ Bà Nà Hills</option>
                                        <option value="cu-lao">Đà Nẵng ⇄ Cù Lao Chàm</option>
                                        <option value="than-tai">Đà Nẵng ⇄ Núi Thần Tài</option>
                                        <option value="vinpearl">Đà Nẵng ⇄ Vinpearl Nam Hội An</option>
                                        <option value="bay-an">Đón & Tiễn Bay + Ăn</option>
                                        <option value="city-tour">City Tour Đà Nẵng - Hội An</option>
                                        <option value="di-hue">Đà Nẵng / Hội An ⇄ Cố Đô Huế</option>
                                    </select>
                                </div>
                                <div>
                                    <label class="block text-xs font-bold text-gray-700 uppercase mb-1">Loại xe yêu cầu *</label>
                                    <select id="qCarType" onchange="calculateEstimatedQuote()" class="w-full px-3.5 py-2.5 rounded-xl border border-gray-300 focus:border-amber-500 outline-none text-sm bg-white">
                                        <option value="4">Xe 4 Chỗ Có Tài Xế</option>
                                        <option value="7">Xe 7 Chỗ Có Tài Xế</option>
                                        <option value="16">Xe 16 Chỗ Có Tài Xế</option>
                                    </select>
                                </div>
                                <div>
                                    <label class="block text-xs font-bold text-gray-700 uppercase mb-1">Chiều đi *</label>
                                    <select id="qDirection" onchange="calculateEstimatedQuote()" class="w-full px-3.5 py-2.5 rounded-xl border border-gray-300 focus:border-amber-500 outline-none text-sm bg-white">
                                        <option value="1">Đi 1 Chiều</option>
                                        <option value="2">Khứ Hồi 2 Chiều (Ưu đãi)</option>
                                    </select>
                                </div>
                            </div>

                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                <div>
                                    <label class="block text-xs font-bold text-gray-700 uppercase mb-1">Điểm đón & Điểm trả chi tiết</label>
                                    <input id="qAddress" type="text" placeholder="Số hiệu chuyến bay / Tên khách sạn Hội An, Đà Nẵng..." class="w-full px-3.5 py-2.5 rounded-xl border border-gray-300 focus:border-amber-500 outline-none text-sm">
                                </div>
                                <div>
                                    <label class="block text-xs font-bold text-gray-700 uppercase mb-1">Ngày & Giờ đón</label>
                                    <input id="qDate" type="text" placeholder="Ví dụ: 14:30 hôm nay hoặc ngày mai..." class="w-full px-3.5 py-2.5 rounded-xl border border-gray-300 focus:border-amber-500 outline-none text-sm">
                                </div>
                            </div>

                            <!-- Hộp Hiển Thị Báo Giá Dự Kiến Tự Động -->
                            <div class="p-4 rounded-xl bg-amber-50 border border-amber-300 flex flex-wrap items-center justify-between gap-2">
                                <div>
                                    <span class="text-xs text-gray-600 block">Báo giá trọn gói dự kiến (Đã giảm giá):</span>
                                    <span id="qEstimatedPrice" class="font-heading font-black text-xl sm:text-2xl text-red-600">250.000đ</span>
                                    <del id="qOriginalPrice" class="text-xs text-gray-400 ml-2">310.000đ</del>
                                </div>
                                <span class="text-xs font-semibold text-emerald-700 bg-emerald-100 px-2.5 py-1 rounded-lg">
                                    <i class="fa-solid fa-check-circle mr-1"></i> Bao gồm cầu đường, bến bãi
                                </span>
                            </div>

                            <div class="flex flex-col sm:flex-row gap-3 pt-1">
                                <button type="submit" class="flex-1 gold-gradient-bg hover:brightness-105 text-gray-950 font-heading font-black text-sm sm:text-base py-3.5 px-6 rounded-xl shadow-md flex items-center justify-center gap-2 transition cursor-pointer">
                                    <i class="fa-solid fa-paper-plane"></i>
                                    <span>GỬI YÊU CẦU BÁO GIÁ NGAY</span>
                                </button>
                                <a href="tel:0777977676" class="sm:w-auto bg-red-600 hover:bg-red-500 text-white font-bold text-sm sm:text-base py-3.5 px-5 rounded-xl shadow-md flex items-center justify-center gap-2 transition">
                                    <i class="fa-solid fa-phone"></i>
                                    <span>0777.977.676</span>
                                </a>
                            </div>
                        </form>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (BLOG / CẨM NANG DU LỊCH CHUẨN FLATSOME)
    =========================================== -->
    <section id="tin-tuc" class="w-full py-10 sm:py-14 bg-white border-b border-gray-200">
        <div class="w-full max-w-[1280px] mx-auto px-3 sm:px-6 lg:px-8">
            
            <!-- Header + Nút lọc danh mục bài viết -->
            <div class="flex flex-col md:flex-row md:items-end justify-between mb-6 pb-3 border-b-2 border-gray-200 gap-3">
                <div>
                    <span class="text-xs font-extrabold uppercase tracking-wider text-amber-600">CHUYÊN MỤC TIN TỨC & CẨM NANG</span>
                    <h2 class="font-heading font-extrabold text-xl sm:text-2xl lg:text-3xl text-gray-900 uppercase">
                        KINH NGHIỆM THUÊ XE & DU LỊCH ĐÀ NẴNG - HỘI AN
                    </h2>
                </div>
                <!-- Tab danh mục bài viết -->
                <div class="flex flex-wrap items-center gap-2">
                    <button onclick="filterPosts('all')" class="post-tab-btn px-3.5 py-1.5 rounded-full text-xs font-bold bg-amber-500 text-gray-950 transition" data-postcat="all">Tất cả bài viết</button>
                    <button onclick="filterPosts('kinh-nghiem')" class="post-tab-btn px-3.5 py-1.5 rounded-full text-xs font-bold bg-gray-100 text-gray-700 hover:bg-amber-100 transition" data-postcat="kinh-nghiem">Kinh nghiệm thuê xe</button>
                    <button onclick="filterPosts('cam-nang')" class="post-tab-btn px-3.5 py-1.5 rounded-full text-xs font-bold bg-gray-100 text-gray-700 hover:bg-amber-100 transition" data-postcat="cam-nang">Điểm đến Hội An - Đà Nẵng</button>
                    <button onclick="filterPosts('bang-ve')" class="post-tab-btn px-3.5 py-1.5 rounded-full text-xs font-bold bg-gray-100 text-gray-700 hover:bg-amber-100 transition" data-postcat="bang-ve">Giá vé Bà Nà & VinWonders</button>
                </div>
            </div>

            <!-- Danh sách bài viết (Chia 2 cột trên điện thoại, 4 cột trên máy tính) -->
            <div id="blogGrid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-6">
                <!-- Render tự động từ dữ liệu bài viết -->
            </div>
        </div>
    </section>

    <!-- ==========================================
         ĐƯA ẢNH & BẢN ĐỒ GOOGLE MAP RA NGOÀI TRANG CHỦ (HỘI AN, ĐÀ NẴNG)
    =========================================== -->
    <section id="ban-do-lien-he" class="w-full py-10 sm:py-14 bg-gray-50">
        <div class="w-full max-w-[1280px] mx-auto px-3 sm:px-6 lg:px-8">
            
            <div class="flex flex-col sm:flex-row sm:items-end justify-between mb-6 gap-2">
                <div>
<!-- ... existing code code -->
    <!-- ==========================================
         FOOTER CHUẨN FLATSOME FULL MÀN HÌNH 2 BÊN
    =========================================== -->
    <footer class="w-full bg-brand-darker text-gray-300 border-t-4 border-amber-500 pt-10 pb-24 md:pb-10">
        <div class="w-full max-w-[1280px] mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 pb-8 border-b border-gray-800">
                <!-- Cột 1 -->
                <div class="space-y-3">
                    <h3 class="font-heading font-black text-xl gold-gradient-text">NGỌC TIÊN TRAVEL</h3>
                    <p class="text-xs sm:text-sm text-gray-400 leading-relaxed">
                        Chuyên dịch vụ cho thuê xe du lịch riêng có tài xế 4 chỗ, 7 chỗ, 16 chỗ đời mới tại Hội An – Đà Nẵng – Huế. Đưa đón sân bay tận nơi, đúng giờ, uy tín hàng đầu.
                    </p>
                    <p class="text-xs text-amber-400 font-semibold">
                        Website: ngoctientravel.com
                    </p>
                </div>

                <!-- Cột 2 -->
                <div class="space-y-3">
                    <h4 class="font-heading font-bold text-sm uppercase text-white tracking-wider">DỊCH VỤ NỔI BẬT</h4>
                    <ul class="space-y-2 text-xs sm:text-sm text-gray-400">
                        <li><a href="#danh-sach-xe" class="hover:text-amber-400 transition">• Xe Đón Tiễn Sân Bay Đà Nẵng (120K)</a></li>
                        <li><a href="#danh-sach-xe" class="hover:text-amber-400 transition">• Thuê Xe Đà Nẵng Đi Hội An (250K)</a></li>
                        <li><a href="#danh-sach-xe" class="hover:text-amber-400 transition">• Thuê Xe Đi Bà Nà Hills (300K)</a></li>
                        <li><a href="#danh-sach-xe" class="hover:text-amber-400 transition">• Thuê Xe Đi Cù Lao Chàm & Núi Thần Tài</a></li>
                        <li><a href="#danh-sach-xe" class="hover:text-amber-400 transition">• Thuê Xe Đi Vinpearl Nam Hội An & Huế</a></li>
                    </ul>
                </div>

                <!-- Cột 3 -->
                <div class="space-y-3">
                    <h4 class="font-heading font-bold text-sm uppercase text-white tracking-wider">CAM KẾT KHÁCH HÀNG</h4>
                    <ul class="space-y-2 text-xs sm:text-sm text-gray-400">
                        <li>✓ Xe riêng đời mới 100%, sạch sẽ, có Wifi</li>
                        <li>✓ Miễn phí chờ đón tại Sân bay Đà Nẵng</li>
                        <li>✓ Giá trọn gói niêm yết, không phí ẩn</li>
                        <li>✓ Hỗ trợ đặt vé Bà Nà Hills, VinWonders</li>
                        <li>✓ Có xuất hóa đơn VAT theo yêu cầu</li>
                    </ul>
                </div>

                <!-- Cột 4 -->
                <div class="space-y-3">
                    <h4 class="font-heading font-bold text-sm uppercase text-white tracking-wider">THÔNG TIN LIÊN HỆ</h4>
                    <p class="text-xs sm:text-sm text-gray-400">
                        <strong class="text-white">Địa chỉ:</strong> Hội An, Đà Nẵng
                    </p>
                    <p class="text-xs sm:text-sm text-gray-400">
                        <strong class="text-white">Hotline / Zalo / WhatsApp:</strong>
                        <a href="tel:0777977676" class="text-amber-400 font-extrabold text-base block mt-0.5">0777.977.676</a>
                    </p>
                </div>
            </div>

            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between text-xs text-gray-500 gap-2">
                <p>© Bản quyền thuộc về <strong class="text-amber-400">Cho Thuê Xe Du Lịch Ngọc Tiên (ngoctientravel.com)</strong>. Thiết kế chuẩn giao diện Flatsome.</p>
                <p>Hotline 24/7: <strong class="text-gray-300">0777.977.676</strong></p>
            </div>
        </div>
    </footer>

    <!-- ==========================================
         CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE (Góc màn hình + Thanh dưới Mobile)
    =========================================== -->
    <div class="fixed right-3 sm:right-5 bottom-20 md:bottom-6 z-40 flex flex-col items-end gap-3">
        <!-- Nút Facebook -->
        <a href="https://m.me/" target="_blank" rel="noopener noreferrer" title="Chat Facebook Messenger" class="relative w-12 h-12 sm:w-13 sm:h-13 rounded-full bg-[#1877F2] text-white shadow-xl flex items-center justify-center hover:scale-110 transition pulse-ring">
            <i class="fa-brands fa-facebook-messenger text-xl sm:text-2xl"></i>
        </a>

        <!-- Nút Zalo Nổi Bật -->
        <a href="https://zalo.me/0777977676" target="_blank" rel="noopener noreferrer" title="Chat Zalo 0777.977.676" class="relative w-12 h-12 sm:w-13 sm:h-13 rounded-full bg-[#0068FF] text-white shadow-xl flex items-center justify-center font-heading font-black text-xs sm:text-sm tracking-tighter hover:scale-110 transition pulse-ring">
            Zalo
        </a>

        <!-- Nút Hotline Nổi Bật -->
        <a href="tel:0777977676" title="Gọi Hotline 0777.977.676" class="relative flex items-center gap-2 bg-red-600 hover:bg-red-500 text-white font-heading font-extrabold px-4 py-3 rounded-full shadow-2xl transition hover:scale-105 pulse-ring">
            <i class="fa-solid fa-phone-volume text-lg animate-bounce"></i>
            <span class="hidden sm:inline text-sm">0777.977.676</span>
        </a>
    </div>

    <!-- Thanh Liên Hệ Dính Đáy Màn Hình Điện Thoại -->
    <div class="md:hidden fixed bottom-0 left-0 right-0 z-40 bg-white border-t border-gray-200 shadow-2xl grid grid-cols-3 divide-x divide-gray-200 py-2">
        <a href="tel:0777977676" class="flex flex-col items-center justify-center text-red-600 font-bold text-xs py-1">
            <i class="fa-solid fa-phone-volume text-base mb-0.5"></i>
            <span>Gọi 0777.977.676</span>
        </a>
        <a href="https://zalo.me/0777977676" target="_blank" rel="noopener noreferrer" class="flex flex-col items-center justify-center text-blue-600 font-bold text-xs py-1">
            <i class="fa-solid fa-comment-dots text-base mb-0.5"></i>
            <span>Chat Zalo</span>
        </a>
        <a href="#form-bao-gia" class="flex flex-col items-center justify-center text-amber-700 font-bold text-xs py-1">
            <i class="fa-solid fa-calculator text-base mb-0.5"></i>
            <span>Báo Giá Nhanh</span>
        </a>
    </div>

    <!-- ==========================================
         MODAL XEM NHANH SẢN PHẨM (QUICK VIEW LIGHTBOX GIỐNG FLATSOME)
    =========================================== -->
    <div id="quickViewModal" class="fixed inset-0 bg-black/70 z-50 hidden items-center justify-center p-3 sm:p-6 backdrop-blur-xs">
        <div class="bg-white rounded-2xl max-w-3xl w-full overflow-hidden shadow-2xl relative animate-fadeIn">
            <button onclick="closeQuickView()" class="absolute top-3 right-3 z-10 w-9 h-9 rounded-full bg-gray-900/80 hover:bg-red-600 text-white flex items-center justify-center transition">
                <i class="fa-solid fa-xmark"></i>
            </button>

            <div class="grid grid-cols-1 md:grid-cols-2">
                <!-- Ảnh Xem Nhanh -->
                <div class="relative bg-gray-100 h-60 md:h-auto">
                    <img id="qvImage" src="" alt="Xem nhanh xe Ngọc Tiên" class="w-full h-full object-cover">
                    <span id="qvDiscount" class="absolute top-3 left-3 bg-red-600 text-white font-extrabold text-xs px-3 py-1 rounded-full shadow">
                        -20%
                    </span>
                </div>

                <!-- Chi tiết Xem Nhanh -->
                <div class="p-5 sm:p-6 flex flex-col justify-between space-y-4">
                    <div>
                        <span id="qvCategory" class="text-[11px] font-bold uppercase tracking-wider text-amber-600">DỊCH VỤ XE CÓ TÀI XẾ</span>
                        <h3 id="qvTitle" class="font-heading font-extrabold text-lg sm:text-xl text-gray-900 mt-1"></h3>
                        
                        <div class="flex items-baseline gap-2.5 mt-2">
                            <span id="qvPrice4" class="font-heading font-black text-2xl text-red-600"></span>
                            <del id="qvOldPrice" class="text-sm text-gray-400"></del>
                        </div>

                        <p id="qvDesc" class="text-xs sm:text-sm text-gray-600 mt-3 leading-relaxed"></p>

                        <!-- Bảng giá 4 - 7 - 16 chỗ trong Quick View -->
                        <div class="mt-4 bg-amber-50/90 border border-amber-200 rounded-xl p-3 space-y-1.5 text-xs sm:text-sm">
                            <div class="flex justify-between font-semibold">
                                <span>• Xe 4 Chỗ riêng có tài xế:</span>
                                <strong id="qvP4" class="text-red-600"></strong>
                            </div>
                            <div class="flex justify-between font-semibold">
                                <span>• Xe 7 Chỗ riêng có tài xế:</span>
                                <strong id="qvP7" class="text-red-600"></strong>
                            </div>
                            <div class="flex justify-between font-semibold">
                                <span>• Xe 16 Chỗ riêng có tài xế:</span>
                                <strong id="qvP16" class="text-red-600"></strong>
                            </div>
                        </div>
                    </div>

                    <div class="pt-2 flex flex-col sm:flex-row gap-2.5">
                        <a href="tel:0777977676" class="flex-1 py-3 px-4 rounded-xl bg-red-600 hover:bg-red-500 text-white font-bold text-xs sm:text-sm text-center flex items-center justify-center gap-2">
                            <i class="fa-solid fa-phone"></i> Gọi Đặt: 0777.977.676
                        </a>
                        <button onclick="bookFromQuickView()" class="flex-1 py-3 px-4 rounded-xl gold-gradient-bg text-gray-950 font-bold text-xs sm:text-sm text-center flex items-center justify-center gap-2">
                            <i class="fa-solid fa-check"></i> Chọn Báo Giá Tuyến Này
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- MODAL ĐỌC BÀI VIẾT TRANG CHỦ & THÔNG BÁO -->
    <div id="infoModal" class="fixed inset-0 bg-black/70 z-50 hidden items-center justify-center p-4 backdrop-blur-xs">
        <div class="bg-white rounded-2xl max-w-xl w-full p-5 sm:p-6 shadow-2xl relative">
            <button onclick="closeInfoModal()" class="absolute top-3 right-3 w-8 h-8 rounded-full bg-gray-100 hover:bg-gray-200 text-gray-700 flex items-center justify-center">
                <i class="fa-solid fa-xmark"></i>
            </button>
            <div id="infoModalContent"></div>
        </div>
    </div>

    <!-- ==========================================
         JAVASCRIPT XỬ LÝ DỮ LIỆU SẢN PHẨM, SLIDER, BÁO GIÁ & QUICK VIEW
    =========================================== -->
    <script>
        // Danh sách 12 sản phẩm dịch vụ thuê xe kết hợp từ bảng giá ảnh gốc Ngọc Tiên & mẫu xedananghoiangiare.com
        const productsData = [
            {
                id: 1,
                title: "Xe Đón Sân Bay - Khách Sạn Đà Nẵng",
                category: "san-bay",
                categoryLabel: "Đưa Đón Sân Bay",
                price4: 120000,
                price7: 150000,
                price16: 300000,
                oldPrice: 150000,
                discountPercent: 20,
                image: "https://images.unsplash.com/photo-1549317661-bd32c8ce0db2?auto=format&fit=crop&w=700&q=80",
                desc: "Xe riêng đời mới đón tận sảnh Sân bay Quốc tế Đà Nẵng về khách sạn trung tâm Đà Nẵng hoặc ngược lại. Tài xế cầm bảng tên đón, miễn phí chờ khi delay chuyến bay."
            },
            {
                id: 2,
                title: "Thuê Xe Đà Nẵng ⇄ Hội An (1 Chiều)",
                category: "hoi-an",
                categoryLabel: "Xe Đà Nẵng - Hội An",
                price4: 250000,
                price7: 300000,
                price16: 450000,
                oldPrice: 320000,
                discountPercent: 22,
                image: "https://images.unsplash.com/photo-1559592413-7cec4d0cae2b?auto=format&fit=crop&w=700&q=80",
                desc: "Dịch vụ xe du lịch có tài xế đưa đón tận nơi từ Sân bay, Ga tàu, Khách sạn Đà Nẵng đi Phố cổ Hội An hoặc từ Hội An ra Đà Nẵng. Phục vụ 24/7 kể cả ban đêm."
            },
            {
                id: 3,
                title: "Thuê Xe Đà Nẵng ⇄ Bà Nà Hills",
                category: "tham-quan",
                categoryLabel: "Xe Tham Quan Du Lịch",
                price4: 300000,
                price7: 350000,
                price16: 500000,
                oldPrice: 380000,
                discountPercent: 21,
                image: "https://images.unsplash.com/photo-1583417319070-4a69db38a482?auto=format&fit=crop&w=700&q=80",
                desc: "Xe riêng đưa đón tận khách sạn Đà Nẵng đi khu du lịch Sun World Bà Nà Hills (Cầu Vàng). Hỗ trợ đặt vé cáp treo Bà Nà Hills nhanh chóng không cần xếp hàng."
            },
            {
                id: 4,
                title: "Thuê Xe Đà Nẵng ⇄ Cù Lao Chàm (Cảng Cửa Đại)",
                category: "tham-quan",
                categoryLabel: "Xe Tham Quan Du Lịch",
                price4: 300000,
                price7: 350000,
                price16: 450000,
                oldPrice: 370000,
                discountPercent: 19,
                image: "https://images.unsplash.com/photo-1507525428034-b723cf961d3e?auto=format&fit=crop&w=700&q=80",
                desc: "Xe du lịch riêng đón tại Đà Nẵng đi thẳng đến Cảng Cửa Đại (Hội An) để đi cano ra đảo Cù Lao Chàm. Hỗ trợ tư vấn vé tour Cù Lao Chàm giá gốc."
            },
            {
                id: 5,
                title: "Thuê Xe Đà Nẵng ⇄ Núi Thần Tài",
                category: "tham-quan",
                categoryLabel: "Xe Tham Quan Du Lịch",
                price4: 350000,
                price7: 400000,
                price16: 600000,
                oldPrice: 440000,
                discountPercent: 20,
                image: "https://images.unsplash.com/photo-1544620347-c4fd4a3d5957?auto=format&fit=crop&w=700&q=80",
                desc: "Xe 4 - 7 - 16 chỗ đưa đón tận nơi tham quan Công viên suối khoáng nóng Núi Thần Tài. Hỗ trợ mua vé tắm khoáng, tắm bùn và buffet trưa chiết khấu cao."
            },
            {
                id: 6,
                title: "Thuê Xe Đà Nẵng ⇄ Vinpearl Nam Hội An",
                category: "tham-quan",
                categoryLabel: "Xe Tham Quan Du Lịch",
                price4: 400000,
                price7: 450000,
                price16: 650000,
                oldPrice: 500000,
                discountPercent: 20,
                image: "https://images.unsplash.com/photo-1533473359331-0135ef1b58bf?auto=format&fit=crop&w=700&q=80",
                desc: "Đưa đón tận nơi từ Đà Nẵng đi khu vui chơi giải trí VinWonders Nam Hội An. Tài xế chu đáo, hỗ trợ đặt vé VinWonders ưu đãi cho gia đình và đoàn khách."
            },
            {
                id: 7,
                title: "Combo Xe Đón & Tiễn Sân Bay + Ăn Đặc Sản",
                category: "san-bay",
                categoryLabel: "Đưa Đón Sân Bay",
                price4: 200000,
                price7: 250000,
                price16: 500000,
                oldPrice: 260000,
                discountPercent: 23,
                image: "https://images.unsplash.com/photo-1552519507-da3b142c6e3d?auto=format&fit=crop&w=700&q=80",
                desc: "Gói tiện lợi đón hoặc tiễn Sân bay Đà Nẵng kết hợp ghé nhà hàng thưởng thức đặc sản Đà Nẵng (Mì Quảng, Bánh tráng thịt heo, Hải sản) và mua quà miền Trung."
            },
            {
                id: 8,
                title: "Thuê Xe City Tour Đà Nẵng - Hội An Trọn Ngày",
                category: "city-tour",
                categoryLabel: "City Tour & Đi Huế",
                price4: 1000000,
                price7: 1200000,
                price16: 1500000,
                oldPrice: 1250000,
                discountPercent: 20,
                image: "https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=700&q=80",
                desc: "Thuê xe riêng có tài xế phục vụ City Tour trọn gói tham quan Bán đảo Sơn Trà (Chùa Linh Ứng), Ngũ Hành Sơn, Phố cổ Hội An, Rừng dừa Bảy Mẫu trong ngày."
            },
            {
                id: 9,
                title: "Thuê Xe Hội An ⇄ Vinpearl Nam Hội An",
                category: "hoi-an",
                categoryLabel: "Xe Đà Nẵng - Hội An",
                price4: 200000,
                price7: 250000,
                price16: 350000,
                oldPrice: 250000,
                discountPercent: 20,
                image: "https://images.unsplash.com/photo-1617788138017-80ad40651399?auto=format&fit=crop&w=700&q=80",
                desc: "Đón tại khách sạn, homestay khu vực Hội An đi VinWonders Nam Hội An hoặc ngược lại. Xe 4 - 7 - 16 chỗ có mặt chỉ sau 5 - 10 phút gọi."
            },
            {
                id: 10,
                title: "Thuê Xe Hội An ⇄ Bà Nà Hills (Đón Tại Hội An)",
                category: "hoi-an",
                categoryLabel: "Xe Đà Nẵng - Hội An",
                price4: 500000,
                price7: 600000,
                price16: 800000,
                oldPrice: 620000,
                discountPercent: 19,
                image: "https://images.unsplash.com/photo-1494976388531-d1058494cdd8?auto=format&fit=crop&w=700&q=80",
                desc: "Xe riêng đón tận khách sạn tại Phố cổ Hội An đi thẳng lên Bà Nà Hills 1 chiều hoặc khứ hồi 2 chiều trong ngày với mức giá tiết kiệm nhất."
            },
            {
                id: 11,
                title: "Thuê Xe Đà Nẵng / Hội An ⇄ Cố Đô Huế",
                category: "city-tour",
                categoryLabel: "City Tour & Đi Huế",
                price4: 1100000,
                price7: 1300000,
                price16: 1700000,
                oldPrice: 1400000,
                discountPercent: 21,
                image: "https://images.unsplash.com/photo-1580273916550-e323be2ae537?auto=format&fit=crop&w=700&q=80",
                desc: "Hành trình Đà Nẵng - Hội An đi Huế qua Đèo Hải Vân, Vịnh Lăng Cô, Đại Nội Huế, Chùa Thiên Mụ, Lăng Khải Định bằng xe riêng đời mới."
            },
            {
                id: 12,
                title: "Xe Đón Sân Bay Chu Lai ⇄ Phố Cổ Hội An",
                category: "san-bay",
                categoryLabel: "Đưa Đón Sân Bay",
                price4: 750000,
                price7: 850000,
                price16: 1200000,
                oldPrice: 950000,
                discountPercent: 21,
                image: "https://images.unsplash.com/photo-1511919884226-fd3cad34687c?auto=format&fit=crop&w=700&q=80",
                desc: "Xe riêng có tài xế đón tiễn Sân bay Chu Lai hoặc Sân bay Đà Nẵng về thẳng Hội An, Nam Hội An Hoiana Resort 24/7."
            }
        ];

        // Dữ liệu các bài viết trang chủ (Kinh nghiệm du lịch)
        const blogPostsData = [
            {
                id: 101,
                cat: "kinh-nghiem",
                catName: "Kinh Nghiệm Thuê Xe",
                title: "Kinh nghiệm thuê xe Đà Nẵng đi Hội An giá rẻ, tránh phát sinh chi phí",
                date: "Cập nhật mới nhất",
                image: "https://images.unsplash.com/photo-1559592413-7cec4d0cae2b?auto=format&fit=crop&w=600&q=80",
                excerpt: "Tổng hợp bảng giá xe 4 chỗ, 7 chỗ, 16 chỗ từ Sân bay Đà Nẵng về Phố cổ Hội An và mẹo đặt xe riêng có tài xế tiết kiệm tới 25% so với taxi truyền thống."
            },
            {
                id: 102,
                cat: "bang-ve",
                catName: "Giá Vé Tham Quan",
                title: "Bảng giá vé cáp treo Bà Nà Hills & combo xe đưa đón tận nơi ưu đãi",
                date: "Cẩm nang Bà Nà",
                image: "https://images.unsplash.com/photo-1583417319070-4a69db38a482?auto=format&fit=crop&w=600&q=80",
                excerpt: "Ngọc Tiên Travel hỗ trợ đặt vé cáp treo Sun World Bà Nà Hills, vé buffet trưa và xe riêng đưa đón khứ hồi từ Đà Nẵng - Hội An không lo xếp hàng."
            },
            {
                id: 103,
                cat: "cam-nang",
                catName: "Điểm Đến Hội An - Đà Nẵng",
                title: "Lịch trình City Tour Đà Nẵng - Hội An 1 ngày bằng xe riêng 4 - 7 chỗ",
                date: "Gợi ý lịch trình",
                image: "https://images.unsplash.com/photo-1507525428034-b723cf961d3e?auto=format&fit=crop&w=600&q=80",
                excerpt: "Khám phá trọn vẹn Chùa Linh Ứng, Ngũ Hành Sơn, Rừng dừa Bảy Mẫu và Phố cổ Hội An về đêm chỉ trong 1 ngày với tài xế bản địa thân thiện."
            },
            {
                id: 104,
                cat: "bang-ve",
                catName: "Giá Vé Tham Quan",
                title: "Kinh nghiệm đi VinWonders Nam Hội An & Núi Thần Tài cho gia đình có trẻ nhỏ",
                date: "Cẩm nang gia đình",
                image: "https://images.unsplash.com/photo-1544620347-c4fd4a3d5957?auto=format&fit=crop&w=600&q=80",
                excerpt: "Hướng dẫn giờ mở cửa, show diễn nhạc nước tại Vinpearl Nam Hội An và lý do gia đình nên thuê xe riêng có tài xế chờ đón tận cổng."
            }
        ];

        let currentQuickViewProduct = null;

        function formatVND(num) {
            return num.toLocaleString('vi-VN') + 'đ';
        }

        // Render lưới sản phẩm chuẩn Flatsome (2 cột trên điện thoại, 4 cột trên máy tính)
        function renderProducts(list) {
            const grid = document.getElementById('productGrid');
            if (!list.length) {
                grid.innerHTML = `<div class="col-span-full text-center py-10 text-gray-500">Không tìm thấy lộ trình phù hợp. Quý khách vui lòng gọi <strong>0777.977.676</strong> để được báo giá ngay!</div>`;
                return;
            }

            grid.innerHTML = list.map(item => `
                <div class="flatsome-product-box bg-white rounded-xl sm:rounded-2xl border border-gray-200 hover:border-amber-400 shadow-xs hover:shadow-xl transition-all duration-300 flex flex-col overflow-hidden group">
                    <!-- Box Image chuẩn Flatsome -->
                    <div class="relative aspect-[4/3] w-full overflow-hidden bg-gray-100">
                        <img src="${item.image}" alt="${item.title}" class="product-img w-full h-full object-cover" onerror="this.src='https://placehold.co/600x450/111827/D4AF37?text=Ngoc+Tien+Travel'">
                        
                        <!-- Huy hiệu % Giảm Giá chuẩn Flatsome -->
                        <div class="absolute top-2 left-2 z-10 w-10 h-10 sm:w-11 sm:h-11 rounded-full bg-red-600 text-white font-heading font-extrabold text-[11px] sm:text-xs flex items-center justify-center shadow-md">
                            -${item.discountPercent}%
                        </div>

                        <!-- Nút XEM NHANH (Quick View) trượt từ dưới ảnh lên giống hệt Flatsome -->
                        <button onclick="openQuickView(${item.id})" class="quick-view-btn absolute bottom-0 inset-x-0 bg-brand-darker/90 hover:bg-amber-500 text-white hover:text-gray-950 font-heading font-bold text-[11px] sm:text-xs uppercase tracking-wider py-2 sm:py-2.5 text-center flex items-center justify-center gap-1.5 cursor-pointer">
                            <i class="fa-solid fa-eye"></i>
                            <span>XEM NHANH</span>
                        </button>
                    </div>

                    <!-- Box Text chuẩn Flatsome -->
                    <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[10px] sm:text-xs font-semibold text-gray-400 uppercase tracking-wide truncate">${item.categoryLabel}</p>
                            <h3 onclick="openQuickView(${item.id})" class="font-heading font-bold text-xs sm:text-base text-gray-900 group-hover:text-amber-600 transition line-clamp-2 mt-0.5 cursor-pointer min-h-[2.4rem] sm:min-h-[2.8rem]">
                                ${item.title}
                            </h3>

                            <!-- Giá giảm giá & Giá gốc gạch ngang giống Flatsome -->
                            <div class="mt-1.5 sm:mt-2 flex flex-wrap items-baseline gap-1.5">
                                <del class="text-[11px] sm:text-xs text-gray-400">${formatVND(item.oldPrice)}</del>
                                <ins class="no-underline font-heading font-black text-sm sm:text-lg text-red-600">${formatVND(item.price4)}</ins>
                            </div>

                            <!-- Bảng tóm tắt 4 - 7 - 16 chỗ ngay trên thẻ sản phẩm -->
                            <div class="mt-2 pt-2 border-t border-dashed border-gray-200 text-[10px] sm:text-xs text-gray-600 space-y-0.5">
                                <div class="flex justify-between"><span>4 chỗ:</span><strong class="text-gray-900">${item.price4/1000}K</strong></div>
                                <div class="flex justify-between"><span>7 chỗ:</span><strong class="text-gray-900">${item.price7/1000}K</strong></div>
                                <div class="flex justify-between"><span>16 chỗ:</span><strong class="text-gray-900">${item.price16/1000}K</strong></div>
                            </div>
                        </div>

                        <div class="mt-3 grid grid-cols-2 gap-1.5">
                            <a href="tel:0777977676" class="py-1.5 sm:py-2 px-2 rounded-lg bg-red-600 hover:bg-red-500 text-white font-bold text-[11px] sm:text-xs text-center flex items-center justify-center gap-1 transition">
                                <i class="fa-solid fa-phone"></i> <span>Đặt Xe</span>
                            </a>
                            <button onclick="openQuickView(${item.id})" class="py-1.5 sm:py-2 px-2 rounded-lg bg-amber-100 hover:bg-amber-500 text-amber-900 hover:text-gray-950 font-bold text-[11px] sm:text-xs text-center transition">
                                Chi Tiết
                            </button>
                        </div>
                    </div>
                </div>
            `).join('');
        }

        // Lọc theo Danh Mục
        function filterCategory(cat) {
            // Đổi màu thẻ danh mục
            document.querySelectorAll('.cat-card').forEach(btn => {
                btn.className = "cat-card group p-3.5 sm:p-4 rounded-2xl bg-white hover:bg-amber-50 text-gray-900 border border-gray-200 hover:border-amber-400 shadow-xs flex items-center gap-3 text-left transition";
            });
            const activeCard = document.getElementById('catCard-' + cat);
            if (activeCard) {
                activeCard.className = "cat-card group p-3.5 sm:p-4 rounded-2xl bg-brand-darker text-white border-2 border-amber-500 shadow-md flex items-center gap-3 text-left transition";
            }

            if (cat === 'all') {
                renderProducts(productsData);
            } else {
                renderProducts(productsData.filter(p => p.category === cat));
            }
        }

        // Tìm kiếm trực tiếp
        function filterProductsBySearch(keyword) {
            const q = keyword.trim().toLowerCase();
            if (!q) {
                renderProducts(productsData);
                return;
            }
            const filtered = productsData.filter(p => 
                p.title.toLowerCase().includes(q) || 
                p.desc.toLowerCase().includes(q) ||
                p.categoryLabel.toLowerCase().includes(q)
            );
            renderProducts(filtered);
        }

        // Mở Modal Xem Nhanh (Quick View) giống Flatsome
        function openQuickView(id) {
            const item = productsData.find(p => p.id === id);
            if (!item) return;
            currentQuickViewProduct = item;

            document.getElementById('qvImage').src = item.image;
            document.getElementById('qvDiscount').textContent = `-${item.discountPercent}%`;
            document.getElementById('qvCategory').textContent = item.categoryLabel;
            document.getElementById('qvTitle').textContent = item.title;
            document.getElementById('qvPrice4').textContent = formatVND(item.price4);
            document.getElementById('qvOldPrice').textContent = formatVND(item.oldPrice);
            document.getElementById('qvDesc').textContent = item.desc;
            document.getElementById('qvP4').textContent = formatVND(item.price4);
            document.getElementById('qvP7').textContent = formatVND(item.price7);
            document.getElementById('qvP16').textContent = formatVND(item.price16);

            const modal = document.getElementById('quickViewModal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeQuickView() {
            const modal = document.getElementById('quickViewModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        function bookFromQuickView() {
            closeQuickView();
            if (currentQuickViewProduct) {
                selectRouteForQuote(currentQuickViewProduct.title, currentQuickViewProduct.price4);
            }
        }

        // Chọn tuyến đưa xuống Form Báo Giá
        function selectRouteForQuote(routeName, price) {
            const addressInput = document.getElementById('qAddress');
            addressInput.value = `Tuyến yêu cầu: ${routeName}`;
            document.getElementById('qEstimatedPrice').textContent = formatVND(price);
            document.getElementById('qOriginalPrice').textContent = formatVND(Math.round(price * 1.25));
            document.getElementById('form-bao-gia').scrollIntoView({ behavior: 'smooth' });
        }

        // Tự động tính giá dự kiến trong Form Báo Giá Trang Chủ
        const routePricingMatrix = {
            'san-bay':  { 4: 120000, 7: 150000, 16: 300000 },
            'hoi-an':   { 4: 250000, 7: 300000, 16: 450000 },
            'ba-na':    { 4: 300000, 7: 350000, 16: 500000 },
            'cu-lao':   { 4: 300000, 7: 350000, 16: 450000 },
            'than-tai': { 4: 350000, 7: 400000, 16: 600000 },
            'vinpearl': { 4: 400000, 7: 450000, 16: 650000 },
            'bay-an':   { 4: 200000, 7: 250000, 16: 500000 },
            'city-tour':{ 4: 1000000, 7: 1200000, 16: 1500000 },
            'di-hue':   { 4: 1100000, 7: 1300000, 16: 1700000 }
        };

        function calculateEstimatedQuote() {
            const route = document.getElementById('qRoute').value;
            const car = document.getElementById('qCarType').value;
            const dir = parseInt(document.getElementById('qDirection').value, 10);

            const base = (routePricingMatrix[route] && routePricingMatrix[route][car]) ? routePricingMatrix[route][car] : 250000;
            const finalPrice = dir === 2 ? Math.round(base * 1.85) : base;
            const oldPrice = Math.round(finalPrice * 1.25);

            document.getElementById('qEstimatedPrice').textContent = formatVND(finalPrice);
            document.getElementById('qOriginalPrice').textContent = formatVND(oldPrice);
        }

        // Gửi Form Báo Giá Trang Chủ
        function submitQuoteForm(e) {
            e.preventDefault();
            const name = document.getElementById('qName').value;
            const phone = document.getElementById('qPhone').value;
            const routeSelect = document.getElementById('qRoute');
            const routeText = routeSelect.options[routeSelect.selectedIndex].text;
            const carSelect = document.getElementById('qCarType');
            const carText = carSelect.options[carSelect.selectedIndex].text;
            const price = document.getElementById('qEstimatedPrice').textContent;

            const content = `
                <div class="text-center space-y-3">
                    <div class="w-14 h-14 rounded-full bg-emerald-100 text-emerald-600 flex items-center justify-center text-2xl mx-auto">
                        <i class="fa-solid fa-check"></i>
                    </div>
                    <h3 class="font-heading font-extrabold text-xl text-gray-900">ĐÃ TIẾP NHẬN YÊU CẦU BÁO GIÁ!</h3>
                    <p class="text-sm text-gray-600">
                        Cảm ơn <strong>${name}</strong> (${phone}). Ngọc Tiên Travel đã nhận thông tin đặt <strong>${carText}</strong> tuyến <strong>${routeText}</strong> (Giá dự kiến: <strong class="text-red-600">${price}</strong>).
                    </p>
                    <div class="p-3.5 rounded-xl bg-amber-50 border border-amber-200 text-xs text-gray-700">
                        Điều hành xe Ngọc Tiên sẽ liên hệ xác nhận ngay qua SĐT/Zalo của quý khách hoặc quý khách có thể bấm nút bên dưới để kết nối Zalo tức thì.
                    </div>
                    <div class="pt-2 flex gap-2.5 justify-center">
                        <a href="https://zalo.me/0777977676" target="_blank" rel="noopener noreferrer" class="px-5 py-2.5 rounded-xl bg-blue-600 text-white font-bold text-xs sm:text-sm">
                            Mở Zalo 0777.977.676
                        </a>
                        <button onclick="closeInfoModal()" class="px-5 py-2.5 rounded-xl bg-gray-200 text-gray-800 font-bold text-xs sm:text-sm">
                            Đóng
                        </button>
                    </div>
                </div>
            `;
            openInfoModal(content);
        }

        // Render danh sách bài viết trang chủ
        function renderPosts(list) {
            const blogGrid = document.getElementById('blogGrid');
            blogGrid.innerHTML = list.map(post => `
                <article onclick="openBlogPost(${post.id})" class="bg-white rounded-xl sm:rounded-2xl border border-gray-200 hover:border-amber-400 shadow-xs hover:shadow-lg transition overflow-hidden flex flex-col cursor-pointer group">
                    <div class="relative aspect-[16/10] overflow-hidden bg-gray-100">
                        <img src="${post.image}" alt="${post.title}" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                        <span class="absolute top-2 left-2 bg-brand-darker/85 text-amber-400 text-[10px] font-bold px-2.5 py-1 rounded-md">
                            ${post.catName}
                        </span>
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-heading font-bold text-xs sm:text-base text-gray-900 group-hover:text-amber-600 transition line-clamp-2">
                                ${post.title}
                            </h3>
                            <p class="text-[11px] sm:text-xs text-gray-500 mt-1.5 line-clamp-3 leading-relaxed">
                                ${post.excerpt}
                            </p>
                        </div>
                        <div class="mt-3 pt-2 border-t border-gray-100 flex items-center justify-between text-[11px] text-amber-700 font-bold">
                            <span>${post.date}</span>
                            <span>Xem chi tiết <i class="fa-solid fa-arrow-right ml-0.5"></i></span>
                        </div>
                    </div>
                </article>
            `).join('');
        }

        function filterPosts(cat) {
            document.querySelectorAll('.post-tab-btn').forEach(btn => {
                if (btn.dataset.postcat === cat) {
                    btn.className = "post-tab-btn px-3.5 py-1.5 rounded-full text-xs font-bold bg-amber-500 text-gray-950 transition";
                } else {
                    btn.className = "post-tab-btn px-3.5 py-1.5 rounded-full text-xs font-bold bg-gray-100 text-gray-700 hover:bg-amber-100 transition";
                }
            });
            if (cat === 'all') {
                renderPosts(blogPostsData);
            } else {
                renderPosts(blogPostsData.filter(b => b.cat === cat));
            }
        }

        function openBlogPost(id) {
            const post = blogPostsData.find(b => b.id === id);
            if (!post) return;
            openInfoModal(`
                <div class="space-y-3">
                    <span class="text-xs font-bold uppercase text-amber-600">${post.catName}</span>
                    <h3 class="font-heading font-extrabold text-lg sm:text-xl text-gray-900">${post.title}</h3>
                    <img src="${post.image}" alt="${post.title}" class="w-full h-48 object-cover rounded-xl">
                    <p class="text-xs sm:text-sm text-gray-600 leading-relaxed">${post.excerpt}</p>
                    <p class="text-xs sm:text-sm text-gray-600 leading-relaxed">
                        Quý khách cần đặt xe riêng có tài xế 4 chỗ, 7 chỗ, 16 chỗ hoặc hỗ trợ mua vé tham quan Bà Nà Hills, VinWonders Nam Hội An, Núi Thần Tài giá tốt nhất vui lòng liên hệ trực tiếp <strong>Ngọc Tiên Travel (0777.977.676)</strong> để được phục vụ 24/7.
                    </p>
                    <div class="pt-2 flex justify-end">
                        <a href="tel:0777977676" class="px-4 py-2 rounded-xl bg-red-600 text-white font-bold text-xs">Gọi 0777.977.676</a>
                    </div>
                </div>
            `);
        }

        function openInfoModal(html) {
            document.getElementById('infoModalContent').innerHTML = html;
            const modal = document.getElementById('infoModal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeInfoModal() {
            const modal = document.getElementById('infoModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        // Điều khiển Drawer Menu trên Điện Thoại
        function toggleMobileMenu() {
            const drawer = document.getElementById('mobileMenuDrawer');
            const overlay = document.getElementById('mobileMenuOverlay');
            const isHidden = drawer.classList.contains('-translate-x-full');
            if (isHidden) {
                drawer.classList.remove('-translate-x-full');
                overlay.classList.remove('hidden');
            } else {
                drawer.classList.add('-translate-x-full');
                overlay.classList.add('hidden');
            }
        }

        // Điều khiển 2 Ảnh Banner Tự Trượt (Auto Slider)
        let currentSlideIndex = 0;
        const slides = document.querySelectorAll('.hero-slide');
        let slideInterval = null;

        function showSlide(index) {
            slides.forEach((slide, i) => {
                if (i === index) {
                    slide.classList.remove('opacity-0', 'z-0');
                    slide.classList.add('opacity-100', 'z-10');
                } else {
                    slide.classList.remove('opacity-100', 'z-10');
                    slide.classList.add('opacity-0', 'z-0');
                }
            });

            const dot0 = document.getElementById('sliderDot0');
            const dot1 = document.getElementById('sliderDot1');
            if (index === 0) {
                dot0.className = "w-8 h-2.5 rounded-full bg-amber-400 transition-all";
                dot1.className = "w-2.5 h-2.5 rounded-full bg-white/50 hover:bg-white transition-all";
            } else {
                dot1.className = "w-8 h-2.5 rounded-full bg-amber-400 transition-all";
                dot0.className = "w-2.5 h-2.5 rounded-full bg-white/50 hover:bg-white transition-all";
            }
            currentSlideIndex = index;
        }

        function nextSlide() {
            showSlide((currentSlideIndex + 1) % slides.length);
            resetSliderTimer();
        }

        function prevSlide() {
            showSlide((currentSlideIndex - 1 + slides.length) % slides.length);
            resetSliderTimer();
        }

        function goToSlide(index) {
            showSlide(index);
            resetSliderTimer();
        }

        function resetSliderTimer() {
            if (slideInterval) clearInterval(slideInterval);
            slideInterval = setInterval(() => {
                showSlide((currentSlideIndex + 1) % slides.length);
            }, 5000);
        }

        // Khởi chạy khi tải trang
        window.onload = function() {
            renderProducts(productsData);
            renderPosts(blogPostsData);
            calculateEstimatedQuote();
            resetSliderTimer();
        };
    </script>
</div>
</body>
</html>
