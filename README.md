<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CÔNG TY TNHH THÀNH VINH WINDOW | Cửa Nhôm Xingfa & Kính Cường Lực Đà Nẵng</title>
    <meta name="description" content="CÔNG TY TNHH THÀNH VINH WINDOW (thanhvinhwindow.com) chuyên thiết kế, gia công và thi công Cửa nhôm Xingfa nhập khẩu, Cửa kính cường lực, Cửa nhựa lõi thép, Cửa tự động, Cầu thang kính, Kính ốp bếp, Phòng tắm kính tại Đà Nẵng. Hotline: 0905.310.041.">

    <!-- Favicon & Ảnh Thumbnail (Logo công ty) khi chia sẻ link trang web -->
    <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/d/12qNv2x91Cyhk70b8jXiqSk17IHIjYlV1=w512">
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://thanhvinhwindow.com/">
    <meta property="og:site_name" content="CÔNG TY TNHH THÀNH VINH WINDOW">
    <meta property="og:title" content="CÔNG TY TNHH THÀNH VINH WINDOW - Cửa Nhôm Xingfa Đà Nẵng">
    <meta property="og:description" content="Thi công cửa nhôm Xingfa chính hãng, cửa kính cường lực, cầu thang kính, phòng tắm kính uy tín tại 1133 Nguyễn Tất Thành, TP Đà Nẵng. Hotline: 0905.310.041.">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/12qNv2x91Cyhk70b8jXiqSk17IHIjYlV1=w1200">
    <meta property="og:image:alt" content="Logo CÔNG TY TNHH THÀNH VINH WINDOW">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="CÔNG TY TNHH THÀNH VINH WINDOW - thanhvinhwindow.com">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/12qNv2x91Cyhk70b8jXiqSk17IHIjYlV1=w1200">

    <!-- Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <!-- Font Awesome 6 Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>

    <!-- Cấu hình màu chủ đạo chuẩn Flatsome theo tông màu logo doanh nghiệp nhôm kính -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            DEFAULT: '#0B4A8B', /* Xanh dương đậm chuẩn logo nhôm kính */
                            dark: '#073566',
                            light: '#EBF3FC',
                            accent: '#D9232D',  /* Đỏ nổi bật cho giá & giảm giá % */
                            gold: '#E59500'
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* =========================================================
           THIẾT LẬP CHUNG CHUẨN FLATSOME & CHỐNG TRÀN VIỀN TUYỆT ĐỐI
           ========================================================= */
        :root {
            --brand-primary: #0B4A8B;
            --brand-dark: #073566;
            --brand-accent: #D9232D;
            --brand-bg-soft: #F5F7FA;
        }

        *, *::before, *::after {
            box-sizing: border-box;
        }

        html, body {
            width: 100%;
            max-width: 100%;
            overflow-x: hidden;
            margin: 0;
            padding: 0;
            font-family: 'Inter', sans-serif;
            color: #1E293B;
            background-color: #FFFFFF;
            scroll-behavior: smooth;
        }

        /* Khung chứa chuẩn 95% chiều rộng màn hình trên máy tính, cân giữa tuyệt đối */
        .tv-container {
            width: 100%;
            max-width: 100%;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }

        @media (min-width: 1024px) {
            .tv-container {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Tiêu đề Section phong cách Flatsome UX Builder (dễ dựng lại 1:1) */
        .flatsome-section-title {
            position: relative;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 1.5rem;
            text-align: center;
        }

        .flatsome-section-title::before,
        .flatsome-section-title::after {
            content: "";
            flex: 1;
            height: 2px;
            background: #E2E8F0;
        }

        .flatsome-section-title h2 {
            padding: 0 16px;
            font-weight: 800;
            text-transform: uppercase;
            color: var(--brand-primary);
            letter-spacing: 0.02em;
        }

        /* Menu Dropdown trên máy tính: 1 hàng gọn gàng, tên danh mục không bao giờ bị gãy dòng */
        .desktop-nav-item {
            position: relative;
            white-space: nowrap;
        }

        .desktop-nav-link {
            display: inline-flex;
            align-items: center;
            gap: 4px;
            white-space: nowrap;
            font-size: 12.5px;
            font-weight: 700;
            text-transform: uppercase;
            padding: 12px 9px;
            color: #FFFFFF;
            transition: background-color 0.2s ease, color 0.2s ease;
        }

        @media (min-width: 1280px) {
            .desktop-nav-link {
                font-size: 13px;
                padding: 13px 13px;
            }
        }

        .desktop-nav-link:hover,
        .desktop-nav-item.active > .desktop-nav-link {
            background-color: var(--brand-dark);
            color: #FDE047;
        }

        .desktop-submenu {
            position: absolute;
            top: 100%;
            left: 0;
            min-width: 225px;
            background: #FFFFFF;
            border-top: 3px solid var(--brand-accent);
            box-shadow: 0 12px 28px rgba(7, 53, 102, 0.16);
            border-radius: 0 0 8px 8px;
            opacity: 0;
            visibility: hidden;
            transform: translateY(6px);
            transition: all 0.2s ease;
            z-index: 60;
        }

        .desktop-nav-item:hover > .desktop-submenu {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }

        .desktop-submenu a {
            display: block;
            padding: 9px 14px;
            font-size: 13px;
            font-weight: 500;
            color: #1E293B;
            border-bottom: 1px solid #F1F5F9;
            white-space: nowrap;
            transition: all 0.15s ease;
        }

        .desktop-submenu a:last-child {
            border-bottom: none;
        }

        .desktop-submenu a:hover {
            background-color: #EBF3FC;
            color: var(--brand-primary);
            padding-left: 18px;
        }

        /* =========================================================
           HERO BANNER SLIDER: 2 BANNER KÍCH THƯỚC BẰNG NHAU TUYỆT ĐỐI
           Chữ & ảnh nằm gọn bên trong, cách xa viền trên cả PC & Mobile
           ========================================================= */
        .hero-slider-viewport {
            position: relative;
            width: 100%;
            overflow: hidden;
            border-radius: 10px;
            background-color: var(--brand-dark);
        }

        .hero-slider-track {
            display: flex;
            align-items: stretch; /* Ép 2 slide luôn cao bằng nhau 100% */
            transition: transform 0.6s cubic-bezier(0.25, 0.8, 0.25, 1);
            width: 100%;
        }

        .hero-slide {
            flex: 0 0 100%;
            width: 100%;
            display: flex;
            align-items: center;
            position: relative;
            overflow: hidden;
        }

        /* Hiệu ứng rung nhẹ cho nút Hotline nổi */
        @keyframes softPulse {
            0% { box-shadow: 0 0 0 0 rgba(217, 35, 45, 0.55); }
            70% { box-shadow: 0 0 0 12px rgba(217, 35, 45, 0); }
            100% { box-shadow: 0 0 0 0 rgba(217, 35, 45, 0); }
        }

        .pulse-hotline {
            animation: softPulse 2s infinite;
        }

        /* Nút lọc danh mục cuộn mượt không hiện thanh cuộn thô */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }
    </style>
</head>
<body class="bg-white text-slate-800 antialiased">

    <!-- =========================================================
         1. TOP BAR (Gọn sạch, KHÔNG có thanh chỉnh sửa UX Builder)
         ========================================================= -->
    <div class="bg-brand-dark text-white text-[11px] sm:text-xs border-b border-white/10">
        <div class="tv-container py-2 flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-3 flex-wrap">
                <span class="inline-flex items-center gap-1.5">
                    <i class="fa-solid fa-location-dot text-amber-400"></i>
                    <span>1133 Nguyễn Tất Thành, Phường Thanh Khê, TP Đà Nẵng</span>
                </span>
                <span class="hidden md:inline-flex items-center gap-1.5 border-l border-white/25 pl-3">
                    <i class="fa-regular fa-clock text-amber-400"></i>
                    <span>Làm việc: 07:30 - 21:00 (T2 - CN)</span>
                </span>
            </div>
            <div class="hidden sm:flex items-center gap-3">
                <a href="https://thanhvinhwindow.com" class="hover:text-amber-300 transition">
                    <i class="fa-solid fa-globe mr-1"></i>thanhvinhwindow.com
                </a>
                <span class="border-l border-white/25 pl-3 font-semibold text-amber-300">
                    Hotline/Zalo: 0905.310.041
                </span>
            </div>
        </div>
    </div>

    <!-- =========================================================
         2. HEADER CHÍNH (Logo gọn nhỏ, KHÔNG có nút Gọi Ngay để chống tràn viền)
         ========================================================= -->
    <header class="bg-white sticky top-0 z-50 shadow-sm border-b border-slate-200">
        <div class="tv-container py-2.5 sm:py-3 flex items-center justify-between gap-3">
            <!-- Nút Menu Mobile -->
            <button id="openMobileMenuBtn" type="button" aria-label="Mở danh mục"
                class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-slate-200 text-brand hover:bg-brand-light transition shrink-0">
                <i class="fa-solid fa-bars text-lg"></i>
            </button>

            <!-- Logo Công ty chỉnh gọn nhỏ -->
            <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 min-w-0">
                <img
                    src="https://lh3.googleusercontent.com/d/12qNv2x91Cyhk70b8jXiqSk17IHIjYlV1=w600"
                    data-drive-id="12qNv2x91Cyhk70b8jXiqSk17IHIjYlV1"
                    alt="Logo CÔNG TY TNHH THÀNH VINH WINDOW"
                    class="h-10 sm:h-11 lg:h-12 w-auto max-w-[135px] sm:max-w-[165px] object-contain rounded"
                    onerror="handleDriveImageError(this, '180x54', 'THANH+VINH+WINDOW')"
                >
                <div class="hidden sm:flex flex-col leading-tight">
                    <span class="text-sm lg:text-base font-extrabold text-brand tracking-tight">THÀNH VINH WINDOW</span>
                    <span class="text-[11px] font-medium text-slate-500">Nhôm Kính Cao Cấp Đà Nẵng</span>
                </div>
            </a>

            <!-- Thanh tìm kiếm sản phẩm chuẩn Flatsome -->
            <form id="headerSearchForm" class="hidden md:flex flex-1 max-w-md lg:max-w-lg mx-2" onsubmit="handleSearchSubmit(event)">
                <div class="flex w-full rounded-lg overflow-hidden border border-slate-300 focus-within:border-brand focus-within:ring-2 focus-within:ring-brand/15 bg-slate-50">
                    <select id="searchCategorySelect" aria-label="Chọn danh mục tìm kiếm"
                        class="bg-slate-100 text-slate-700 text-xs font-medium px-2.5 py-2 border-r border-slate-300 outline-none max-w-[135px]">
                        <option value="all">Tất cả danh mục</option>
                        <option value="xingfa">Cửa nhôm Xingfa</option>
                        <option value="nhua-loi-thep">Cửa nhựa lõi thép</option>
                        <option value="tu-dong">Cửa kính tự động</option>
                        <option value="cau-thang">Cầu thang kính</option>
                        <option value="op-bep">Kính ốp bếp</option>
                        <option value="phong-tam">Phòng tắm kính</option>
                    </select>
                    <input id="searchKeywordInput" type="text" placeholder="Tìm cửa nhôm Xingfa, cửa kính..."
                        class="flex-1 bg-transparent px-3 py-2 text-xs lg:text-sm text-slate-800 outline-none min-w-0">
                    <button type="submit" aria-label="Tìm kiếm"
                        class="bg-brand hover:bg-brand-dark text-white px-4 py-2 text-sm transition shrink-0">
                        <i class="fa-solid fa-magnifying-glass"></i>
                    </button>
                </div>
            </form>

            <!-- Tiện ích gọn bên phải (Nhận báo giá nhanh / Không để nút Gọi ngay tràn viền) -->
            <div class="flex items-center gap-2 shrink-0">
                <a href="#form-bao-gia"
                    class="inline-flex items-center gap-1.5 bg-brand-light hover:bg-brand text-brand hover:text-white border border-brand/25 text-xs font-bold px-3 py-2 rounded-lg transition whitespace-nowrap">
                    <i class="fa-solid fa-file-invoice"></i>
                    <span class="hidden sm:inline">Nhận báo giá</span>
                    <span class="sm:hidden">Báo giá</span>
                </a>
            </div>
        </div>

        <!-- =========================================================
             3. THANH DANH MỤC MENU CHÍNH TRÊN MÁY TÍNH
             Chữ gọn nhỏ, viết liền 1 hàng, KHÔNG gãy dòng tên danh mục
             ========================================================= -->
        <nav class="hidden lg:block bg-brand border-t border-white/10" aria-label="Danh mục chính">
            <div class="tv-container">
                <ul class="flex flex-wrap items-center justify-center gap-x-0.5 xl:gap-x-1">
                    <li class="desktop-nav-item active">
                        <a href="#trang-chu" class="desktop-nav-link">Trang chủ</a>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#gioi-thieu" class="desktop-nav-link">Giới thiệu</a>
                    </li>
                    <!-- Dropdown Cửa nhôm xingfa -->
                    <li class="desktop-nav-item">
                        <a href="#san-pham-xingfa" onclick="filterProducts('xingfa')" class="desktop-nav-link">
                            <span>Cửa nhôm xingfa</span>
                            <i class="fa-solid fa-chevron-down text-[10px]"></i>
                        </a>
                        <div class="desktop-submenu">
                            <a href="#san-pham-xingfa" onclick="filterAndHighlight('xingfa', '1 cánh')">Cửa nhôm xingfa 1 cánh</a>
                            <a href="#san-pham-xingfa" onclick="filterAndHighlight('xingfa', '2 cánh')">Cửa nhôm xingfa 2 cánh</a>
                            <a href="#san-pham-xingfa" onclick="filterAndHighlight('xingfa', '3 cánh')">Cửa nhôm xingfa 3 cánh</a>
                            <a href="#san-pham-xingfa" onclick="filterAndHighlight('xingfa', '4 cánh')">Cửa nhôm xingfa 4 cánh</a>
                            <a href="#san-pham-xingfa" onclick="filterAndHighlight('xingfa', 'Xếp Trượt')">Cửa nhôm xingfa 5 cánh</a>
                        </div>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#danh-muc-noi-bat" onclick="filterProducts('phong-tam')" class="desktop-nav-link">Cửa kính cường lực</a>
                    </li>
                    <!-- Dropdown Sản phẩm -->
                    <li class="desktop-nav-item">
                        <a href="#san-pham-xingfa" onclick="filterProducts('all')" class="desktop-nav-link">
                            <span>Sản phẩm</span>
                            <i class="fa-solid fa-chevron-down text-[10px]"></i>
                        </a>
                        <div class="desktop-submenu">
                            <a href="#san-pham-xingfa" onclick="filterProducts('xingfa')">Cửa nhôm xingfa</a>
                            <a href="#san-pham-xingfa" onclick="filterProducts('nhua-loi-thep')">Cửa nhựa lõi thép</a>
                            <a href="#san-pham-xingfa" onclick="filterProducts('tu-dong')">Cửa kính tự động</a>
                            <a href="#san-pham-xingfa" onclick="filterProducts('cau-thang')">Cầu thang kính</a>
                            <a href="#san-pham-xingfa" onclick="filterProducts('op-bep')">Kính ốp bếp</a>
                            <a href="#san-pham-xingfa" onclick="filterProducts('phong-tam')">Phòng tắm kính</a>
                        </div>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#cong-trinh" class="desktop-nav-link">Công trình</a>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#form-bao-gia" class="desktop-nav-link">Báo giá</a>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#tin-tuc" class="desktop-nav-link">Tin tức</a>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#lien-he" class="desktop-nav-link">Liên hệ</a>
                    </li>
                </ul>
            </div>
        </nav>

        <!-- Thanh tìm kiếm gọn cho điện thoại -->
        <div class="md:hidden bg-slate-50 border-t border-slate-200 px-3 py-2">
            <form onsubmit="handleMobileSearchSubmit(event)" class="flex w-full rounded-lg overflow-hidden border border-slate-300 bg-white">
                <input id="mobileSearchInput" type="text" placeholder="Tìm cửa nhôm Xingfa, cửa kính..."
                    class="flex-1 px-3 py-1.5 text-xs text-slate-800 outline-none min-w-0">
                <button type="submit" aria-label="Tìm kiếm trên điện thoại"
                    class="bg-brand text-white px-3.5 py-1.5 text-xs font-semibold shrink-0">
                    <i class="fa-solid fa-magnifying-glass"></i>
                </button>
            </form>
        </div>
    </header>

    <!-- =========================================================
         MENU TRƯỢT CHO ĐIỆN THOẠI (OFF-CANVAS MOBILE DRAWER)
         ========================================================= -->
    <div id="mobileMenuOverlay" class="fixed inset-0 bg-slate-900/50 z-50 hidden transition-opacity"></div>
    <aside id="mobileMenuDrawer"
        class="fixed top-0 left-0 bottom-0 w-[84%] max-w-[320px] bg-white z-50 shadow-2xl transform -translate-x-full transition-transform duration-300 flex flex-col">
        <div class="flex items-center justify-between px-4 py-3 bg-brand text-white">
            <span class="font-bold text-sm uppercase tracking-wide">Danh mục trang web</span>
            <button id="closeMobileMenuBtn" type="button" aria-label="Đóng danh mục"
                class="w-8 h-8 rounded-lg bg-white/15 hover:bg-white/25 flex items-center justify-center">
                <i class="fa-solid fa-xmark text-base"></i>
            </button>
        </div>
        <div class="flex-1 overflow-y-auto divide-y divide-slate-100 text-sm">
            <a href="#trang-chu" onclick="closeMobileMenu()" class="block px-4 py-3 font-semibold text-slate-800 hover:bg-brand-light hover:text-brand">Trang chủ</a>
            <a href="#gioi-thieu" onclick="closeMobileMenu()" class="block px-4 py-3 font-semibold text-slate-800 hover:bg-brand-light hover:text-brand">Giới thiệu</a>

            <!-- Accordion Cửa nhôm xingfa -->
            <div>
                <button type="button" onclick="toggleMobileSubmenu('sub-xingfa', this)"
                    class="w-full flex items-center justify-between px-4 py-3 font-semibold text-slate-800 hover:bg-brand-light">
                    <span>Cửa nhôm xingfa</span>
                    <i class="fa-solid fa-chevron-down text-xs text-slate-500 transition-transform"></i>
                </button>
                <div id="sub-xingfa" class="hidden bg-slate-50 pl-6 pr-4 py-1 space-y-1 text-[13px]">
                    <a href="#san-pham-xingfa" onclick="filterAndHighlight('xingfa', '1 cánh'); closeMobileMenu();" class="block py-2 text-slate-700 hover:text-brand">+ Cửa nhôm xingfa 1 cánh</a>
                    <a href="#san-pham-xingfa" onclick="filterAndHighlight('xingfa', '2 cánh'); closeMobileMenu();" class="block py-2 text-slate-700 hover:text-brand">+ Cửa nhôm xingfa 2 cánh</a>
                    <a href="#san-pham-xingfa" onclick="filterAndHighlight('xingfa', '3 cánh'); closeMobileMenu();" class="block py-2 text-slate-700 hover:text-brand">+ Cửa nhôm xingfa 3 cánh</a>
                    <a href="#san-pham-xingfa" onclick="filterAndHighlight('xingfa', '4 cánh'); closeMobileMenu();" class="block py-2 text-slate-700 hover:text-brand">+ Cửa nhôm xingfa 4 cánh</a>
                    <a href="#san-pham-xingfa" onclick="filterAndHighlight('xingfa', 'Xếp Trượt'); closeMobileMenu();" class="block py-2 text-slate-700 hover:text-brand">+ Cửa nhôm xingfa 5 cánh</a>
                </div>
            </div>

            <a href="#danh-muc-noi-bat" onclick="filterProducts('phong-tam'); closeMobileMenu();" class="block px-4 py-3 font-semibold text-slate-800 hover:bg-brand-light hover:text-brand">Cửa kính cường lực</a>

            <!-- Accordion Sản phẩm -->
            <div>
                <button type="button" onclick="toggleMobileSubmenu('sub-sanpham', this)"
                    class="w-full flex items-center justify-between px-4 py-3 font-semibold text-slate-800 hover:bg-brand-light">
                    <span>Sản phẩm</span>
                    <i class="fa-solid fa-chevron-down text-xs text-slate-500 transition-transform"></i>
                </button>
                <div id="sub-sanpham" class="hidden bg-slate-50 pl-6 pr-4 py-1 space-y-1 text-[13px]">
                    <a href="#san-pham-xingfa" onclick="filterProducts('xingfa'); closeMobileMenu();" class="block py-2 text-slate-700 hover:text-brand">+ Cửa nhôm xingfa</a>
                    <a href="#san-pham-xingfa" onclick="filterProducts('nhua-loi-thep'); closeMobileMenu();" class="block py-2 text-slate-700 hover:text-brand">+ Cửa nhựa lõi thép</a>
                    <a href="#san-pham-xingfa" onclick="filterProducts('tu-dong'); closeMobileMenu();" class="block py-2 text-slate-700 hover:text-brand">+ Cửa kính tự động</a>
                    <a href="#san-pham-xingfa" onclick="filterProducts('cau-thang'); closeMobileMenu();" class="block py-2 text-slate-700 hover:text-brand">+ Cầu thang kính</a>
                    <a href="#san-pham-xingfa" onclick="filterProducts('op-bep'); closeMobileMenu();" class="block py-2 text-slate-700 hover:text-brand">+ Kính ốp bếp</a>
                    <a href="#san-pham-xingfa" onclick="filterProducts('phong-tam'); closeMobileMenu();" class="block py-2 text-slate-700 hover:text-brand">+ Phòng tắm kính</a>
                </div>
            </div>

            <a href="#cong-trinh" onclick="closeMobileMenu()" class="block px-4 py-3 font-semibold text-slate-800 hover:bg-brand-light hover:text-brand">Công trình</a>
            <a href="#form-bao-gia" onclick="closeMobileMenu()" class="block px-4 py-3 font-semibold text-slate-800 hover:bg-brand-light hover:text-brand">Báo giá</a>
            <a href="#tin-tuc" onclick="closeMobileMenu()" class="block px-4 py-3 font-semibold text-slate-800 hover:bg-brand-light hover:text-brand">Tin tức</a>
            <a href="#lien-he" onclick="closeMobileMenu()" class="block px-4 py-3 font-semibold text-slate-800 hover:bg-brand-light hover:text-brand">Liên hệ</a>
        </div>
        <div class="p-4 bg-slate-50 border-t border-slate-200 text-xs text-slate-600 space-y-1.5">
            <p class="font-bold text-brand">CÔNG TY TNHH THÀNH VINH WINDOW</p>
            <p><i class="fa-solid fa-location-dot text-brand mr-1.5"></i>1133 Nguyễn Tất Thành, Thanh Khê, Đà Nẵng</p>
            <p><i class="fa-solid fa-phone text-brand-accent mr-1.5"></i>Hotline: <strong>0905.310.041</strong></p>
        </div>
    </aside>

    <!-- =========================================================
         4. 2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU
         - Ảnh & chữ nằm gọn 100% trong banner
         - Chữ cách xa viền (padding lớn), không bị mất chữ trên PC & Mobile
         - Không có nhãn dán thừa
         ========================================================= -->
    <section id="trang-chu" class="pt-3 pb-4 sm:pt-4 sm:pb-6 bg-slate-50">
        <div class="tv-container">
            <div id="heroSlider" class="hero-slider-viewport shadow-md">
                <div id="heroTrack" class="hero-slider-track">

                    <!-- BANNER 1 -->
                    <div class="hero-slide bg-gradient-to-br from-[#072B52] via-[#0B4A8B] to-[#1262B5] text-white">
                        <!-- Lề an toàn lớn (px-9 sm:px-14 lg:px-20 py-8 sm:py-11 lg:py-14) giúp chữ cách xa viền tuyệt đối -->
                        <div class="w-full px-9 sm:px-14 lg:px-20 pt-7 pb-12 sm:py-11 lg:py-14 grid grid-cols-1 md:grid-cols-12 gap-5 lg:gap-8 items-center">
                            <div class="md:col-span-7 space-y-3 sm:space-y-4 text-left">
                                <p class="text-[11px] sm:text-xs lg:text-sm font-bold uppercase tracking-widest text-amber-300">
                                    CÔNG TY TNHH THÀNH VINH WINDOW — ĐÀ NẴNG
                                </p>
                                <h1 class="text-lg sm:text-2xl lg:text-4xl font-extrabold leading-snug lg:leading-tight text-white">
                                    CỬA NHÔM XINGFA NHẬP KHẨU CHÍNH HÃNG TẠI ĐÀ NẴNG
                                </h1>
                                <p class="text-xs sm:text-sm lg:text-base text-blue-100 leading-relaxed max-w-xl">
                                    Gia công trực tiếp tại xưởng với nhôm Xingfa tem đỏ Quảng Đông, phụ kiện Kinlong đồng bộ, kính cường lực an toàn. Khảo sát & lắp đặt tận nơi miễn phí.
                                </p>
                                <div class="flex flex-wrap items-center gap-2.5 pt-1">
                                    <a href="#san-pham-xingfa"
                                        class="inline-flex items-center gap-2 bg-brand-accent hover:bg-red-700 text-white text-xs sm:text-sm font-bold px-4 sm:px-6 py-2.5 rounded-lg shadow transition">
                                        <span>Xem mẫu & Báo giá</span>
                                        <i class="fa-solid fa-arrow-right text-xs"></i>
                                    </a>
                                    <a href="#form-bao-gia"
                                        class="inline-flex items-center gap-2 bg-white/15 hover:bg-white/25 border border-white/40 text-white text-xs sm:text-sm font-semibold px-4 sm:px-5 py-2.5 rounded-lg transition">
                                        <span>Tư vấn miễn phí</span>
                                    </a>
                                </div>
                            </div>
                            <div class="md:col-span-5 flex justify-center">
                                <div class="w-full max-w-[360px] lg:max-w-[440px] aspect-[16/10] rounded-xl overflow-hidden border-2 border-white/25 shadow-xl bg-white/10">
                                    <img
                                        src="https://lh3.googleusercontent.com/d/1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-=w1000"
                                        data-drive-id="1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-"
                                        alt="Thi công cửa nhôm Xingfa 4 cánh Thành Vinh Window"
                                        class="w-full h-full object-cover"
                                        onerror="handleDriveImageError(this, '640x400', 'Cua+Nhom+Xingfa+Thanh+Vinh')"
                                    >
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- BANNER 2 (Cấu trúc & kích thước đồng bộ 100% với Banner 1) -->
                    <div class="hero-slide bg-gradient-to-br from-[#0A2540] via-[#0E3F73] to-[#1A5B9C] text-white">
                        <div class="w-full px-9 sm:px-14 lg:px-20 pt-7 pb-12 sm:py-11 lg:py-14 grid grid-cols-1 md:grid-cols-12 gap-5 lg:gap-8 items-center">
                            <div class="md:col-span-7 space-y-3 sm:space-y-4 text-left">
                                <p class="text-[11px] sm:text-xs lg:text-sm font-bold uppercase tracking-widest text-amber-300">
                                    NHÀ THẦU NHÔM KÍNH UY TÍN — THANHVINHWINDOW.COM
                                </p>
                                <h2 class="text-lg sm:text-2xl lg:text-4xl font-extrabold leading-snug lg:leading-tight text-white">
                                    THI CÔNG TRỌN GÓI KHÁCH SẠN, RESORT & NHÀ PHỐ
                                </h2>
                                <p class="text-xs sm:text-sm lg:text-base text-blue-100 leading-relaxed max-w-xl">
                                    Chuyên hạng mục Cửa kính cường lực, Cầu thang kính, Phòng tắm kính, Kính ốp bếp và Cửa kính tự động. Đúng tiến độ, bảo hành dài hạn, giá xuất xưởng.
                                </p>
                                <div class="flex flex-wrap items-center gap-2.5 pt-1">
                                    <a href="#cong-trinh"
                                        class="inline-flex items-center gap-2 bg-amber-500 hover:bg-amber-600 text-slate-950 text-xs sm:text-sm font-bold px-4 sm:px-6 py-2.5 rounded-lg shadow transition">
                                        <span>Xem dự án Đà Nẵng</span>
                                        <i class="fa-solid fa-building text-xs"></i>
                                    </a>
                                    <a href="tel:0905310041"
                                        class="inline-flex items-center gap-2 bg-white/15 hover:bg-white/25 border border-white/40 text-white text-xs sm:text-sm font-semibold px-4 sm:px-5 py-2.5 rounded-lg transition">
                                        <i class="fa-solid fa-phone text-xs"></i>
                                        <span>0905.310.041</span>
                                    </a>
                                </div>
                            </div>
                            <div class="md:col-span-5 flex justify-center">
                                <div class="w-full max-w-[360px] lg:max-w-[440px] aspect-[16/10] rounded-xl overflow-hidden border-2 border-white/25 shadow-xl bg-white/10">
                                    <img
                                        src="https://lh3.googleusercontent.com/d/1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ=w1000"
                                        data-drive-id="1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ"
                                        alt="Dự án Resort Mỹ Sơn 4 sao Thành Vinh Window"
                                        class="w-full h-full object-cover"
                                        onerror="handleDriveImageError(this, '640x400', 'Du+An+Khach+San+Da+Nang')"
                                    >
                                </div>
                            </div>
                        </div>
                    </div>

                </div>

                <!-- Nút điều hướng Banner gọn sát mép an toàn -->
                <button id="heroPrevBtn" type="button" aria-label="Banner trước"
                    class="absolute left-1.5 sm:left-3 top-1/2 -translate-y-1/2 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/30 hover:bg-black/55 text-white flex items-center justify-center transition z-10">
                    <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
                </button>
                <button id="heroNextBtn" type="button" aria-label="Banner tiếp theo"
                    class="absolute right-1.5 sm:right-3 top-1/2 -translate-y-1/2 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/30 hover:bg-black/55 text-white flex items-center justify-center transition z-10">
                    <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
                </button>

                <!-- Chấm tròn chỉ báo Slide -->
                <div class="absolute bottom-3 left-1/2 -translate-x-1/2 flex items-center gap-2 z-10">
                    <button type="button" onclick="goToHeroSlide(0)" aria-label="Slide 1"
                        class="hero-dot w-6 h-2 rounded-full bg-white transition-all"></button>
                    <button type="button" onclick="goToHeroSlide(1)" aria-label="Slide 2"
                        class="hero-dot w-2.5 h-2 rounded-full bg-white/50 hover:bg-white/80 transition-all"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================
         5. DANH MỤC SẢN PHẨM NỔI BẬT (Thiết kế gọn gàng chuẩn Flatsome)
         Chữ danh mục nhỏ gọn, viết liền 1 dòng trên máy tính & điện thoại
         ========================================================= -->
    <section id="danh-muc-noi-bat" class="py-7 sm:py-10 bg-white">
        <div class="tv-container">
            <div class="flatsome-section-title">
                <h2 class="text-base sm:text-xl lg:text-2xl">Danh mục sản phẩm nổi bật</h2>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3 sm:gap-4">
                <!-- Danh mục 1: Cửa nhôm xingfa -->
                <a href="#san-pham-xingfa" onclick="filterProducts('xingfa')"
                    class="group bg-white border border-slate-200 hover:border-brand rounded-xl overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX=w700"
                            data-drive-id="1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX"
                            alt="Cửa nhôm xingfa"
                            class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
                            onerror="handleDriveImageError(this, '400x300', 'Cua+Nhom+Xingfa')">
                    </div>
                    <div class="py-2.5 px-1.5 text-center bg-white group-hover:bg-brand-light transition">
                        <h3 class="text-[11px] sm:text-xs font-bold uppercase text-brand whitespace-nowrap overflow-hidden text-ellipsis">
                            Cửa nhôm xingfa
                        </h3>
                    </div>
                </a>

                <!-- Danh mục 2: Cửa nhựa lõi thép -->
                <a href="#san-pham-xingfa" onclick="filterProducts('nhua-loi-thep')"
                    class="group bg-white border border-slate-200 hover:border-brand rounded-xl overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA=w700"
                            data-drive-id="1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA"
                            alt="Cửa nhựa lõi thép"
                            class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
                            onerror="handleDriveImageError(this, '400x300', 'Cua+Nhua+Loi+Thep')">
                    </div>
                    <div class="py-2.5 px-1.5 text-center bg-white group-hover:bg-brand-light transition">
                        <h3 class="text-[11px] sm:text-xs font-bold uppercase text-brand whitespace-nowrap overflow-hidden text-ellipsis">
                            Cửa nhựa lõi thép
                        </h3>
                    </div>
                </a>

                <!-- Danh mục 3: Cửa kính tự động -->
                <a href="#san-pham-xingfa" onclick="filterProducts('tu-dong')"
                    class="group bg-white border border-slate-200 hover:border-brand rounded-xl overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ=w700"
                            data-drive-id="1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ"
                            alt="Cửa kính tự động"
                            class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
                            onerror="handleDriveImageError(this, '400x300', 'Cua+Kinh+Tu+Dong')">
                    </div>
                    <div class="py-2.5 px-1.5 text-center bg-white group-hover:bg-brand-light transition">
                        <h3 class="text-[11px] sm:text-xs font-bold uppercase text-brand whitespace-nowrap overflow-hidden text-ellipsis">
                            Cửa kính tự động
                        </h3>
                    </div>
                </a>

                <!-- Danh mục 4: Cầu thang kính -->
                <a href="#san-pham-xingfa" onclick="filterProducts('cau-thang')"
                    class="group bg-white border border-slate-200 hover:border-brand rounded-xl overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul=w700"
                            data-drive-id="1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul"
                            alt="Cầu thang kính"
                            class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
                            onerror="handleDriveImageError(this, '400x300', 'Cau+Thang+Kinh')">
                    </div>
                    <div class="py-2.5 px-1.5 text-center bg-white group-hover:bg-brand-light transition">
                        <h3 class="text-[11px] sm:text-xs font-bold uppercase text-brand whitespace-nowrap overflow-hidden text-ellipsis">
                            Cầu thang kính
                        </h3>
                    </div>
                </a>

                <!-- Danh mục 5: Kính ốp bếp -->
                <a href="#san-pham-xingfa" onclick="filterProducts('op-bep')"
                    class="group bg-white border border-slate-200 hover:border-brand rounded-xl overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb=w700"
                            data-drive-id="1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb"
                            alt="Kính ốp bếp"
                            class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
                            onerror="handleDriveImageError(this, '400x300', 'Kinh+Op+Bep')">
                    </div>
                    <div class="py-2.5 px-1.5 text-center bg-white group-hover:bg-brand-light transition">
                        <h3 class="text-[11px] sm:text-xs font-bold uppercase text-brand whitespace-nowrap overflow-hidden text-ellipsis">
                            Kính ốp bếp
                        </h3>
                    </div>
                </a>

                <!-- Danh mục 6: Phòng tắm kính -->
                <a href="#san-pham-xingfa" onclick="filterProducts('phong-tam')"
                    class="group bg-white border border-slate-200 hover:border-brand rounded-xl overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH=w700"
                            data-drive-id="1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH"
                            alt="Phòng tắm kính"
                            class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
                            onerror="handleDriveImageError(this, '400x300', 'Phong+Tam+Kinh')">
                    </div>
                    <div class="py-2.5 px-1.5 text-center bg-white group-hover:bg-brand-light transition">
                        <h3 class="text-[11px] sm:text-xs font-bold uppercase text-brand whitespace-nowrap overflow-hidden text-ellipsis">
                            Phòng tắm kính
                        </h3>
                    </div>
                </a>
            </div>
        </div>
    </section>

    <!-- =========================================================
         6. BÁO GIÁ SẢN PHẨM CỬA NHÔM XINGFA & DANH MỤC MẪU
         - Điện thoại: chia 2 cột rõ đẹp (grid-cols-2)
         - Tên sản phẩm hiển thị đầy đủ, không bị tràn hoặc cắt chữ
         - Góc trên bên trái có nhãn giảm giá %, kèm giá gốc & giá ưu đãi
         ========================================================= -->
    <section id="san-pham-xingfa" class="py-8 sm:py-11 bg-slate-50 border-y border-slate-200/80">
        <div class="tv-container">
            <div class="flatsome-section-title">
                <h2 class="text-base sm:text-xl lg:text-2xl">Báo giá cửa nhôm Xingfa Đà Nẵng</h2>
            </div>

            <!-- Thanh lọc danh mục sản phẩm nhỏ gọn trên 1 hàng -->
            <div id="productFilterTabs" class="flex items-center justify-start lg:justify-center gap-2 overflow-x-auto no-scrollbar pb-4 mb-2">
                <button type="button" data-cat="xingfa" onclick="filterProducts('xingfa')"
                    class="filter-tab shrink-0 px-3.5 py-2 rounded-lg text-xs font-bold bg-brand text-white transition whitespace-nowrap">
                    Cửa nhôm Xingfa
                </button>
                <button type="button" data-cat="all" onclick="filterProducts('all')"
                    class="filter-tab shrink-0 px-3.5 py-2 rounded-lg text-xs font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand transition whitespace-nowrap">
                    Tất cả sản phẩm
                </button>
                <button type="button" data-cat="nhua-loi-thep" onclick="filterProducts('nhua-loi-thep')"
                    class="filter-tab shrink-0 px-3.5 py-2 rounded-lg text-xs font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand transition whitespace-nowrap">
                    Cửa nhựa lõi thép
                </button>
                <button type="button" data-cat="tu-dong" onclick="filterProducts('tu-dong')"
                    class="filter-tab shrink-0 px-3.5 py-2 rounded-lg text-xs font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand transition whitespace-nowrap">
                    Cửa kính tự động
                </button>
                <button type="button" data-cat="cau-thang" onclick="filterProducts('cau-thang')"
                    class="filter-tab shrink-0 px-3.5 py-2 rounded-lg text-xs font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand transition whitespace-nowrap">
                    Cầu thang kính
                </button>
                <button type="button" data-cat="op-bep" onclick="filterProducts('op-bep')"
                    class="filter-tab shrink-0 px-3.5 py-2 rounded-lg text-xs font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand transition whitespace-nowrap">
                    Kính ốp bếp
                </button>
                <button type="button" data-cat="phong-tam" onclick="filterProducts('phong-tam')"
                    class="filter-tab shrink-0 px-3.5 py-2 rounded-lg text-xs font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand transition whitespace-nowrap">
                    Phòng tắm kính
                </button>
            </div>

            <!-- Thông báo kết quả tìm kiếm (chỉ hiện khi người dùng tìm kiếm) -->
            <div id="searchStatusBanner" class="hidden mb-4 px-4 py-2.5 rounded-lg bg-brand-light border border-brand/20 text-xs sm:text-sm text-brand flex items-center justify-between gap-2">
                <span id="searchStatusText"></span>
                <button type="button" onclick="resetSearch()" class="font-bold underline hover:text-brand-dark shrink-0">Xem lại tất cả</button>
            </div>

            <!-- Lưới sản phẩm: 2 cột trên điện thoại, 3 cột trên máy tính -->
            <div id="productsGrid" class="grid grid-cols-2 md:grid-cols-3 gap-2.5 sm:gap-4 lg:gap-5">
                <!-- Được render động bằng JavaScript từ danh sách sản phẩm chuẩn -->
            </div>

            <!-- Khối cam kết dịch vụ (tương tự web mẫu ngochanwindow.com) -->
            <div class="mt-8 bg-white border border-slate-200 rounded-xl p-4 sm:p-5 shadow-sm">
                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-4 text-xs sm:text-sm">
                    <div class="flex items-center gap-3 p-2.5 rounded-lg bg-slate-50">
                        <div class="w-10 h-10 rounded-full bg-brand-light text-brand flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-truck-fast"></i>
                        </div>
                        <div>
                            <p class="font-bold text-slate-800">Lắp đặt miễn phí</p>
                            <p class="text-xs text-slate-500">Khảo sát & đo đạc tận nhà Đà Nẵng</p>
                        </div>
                    </div>
                    <div class="flex items-center gap-3 p-2.5 rounded-lg bg-slate-50">
                        <div class="w-10 h-10 rounded-full bg-brand-light text-brand flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-percent"></i>
                        </div>
                        <div>
                            <p class="font-bold text-slate-800">Ưu đãi đến 20%</p>
                            <p class="text-xs text-slate-500">Giá gốc xuất xưởng không qua trung gian</p>
                        </div>
                    </div>
                    <div class="flex items-center gap-3 p-2.5 rounded-lg bg-slate-50">
                        <div class="w-10 h-10 rounded-full bg-brand-light text-brand flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-shield-halved"></i>
                        </div>
                        <div>
                            <p class="font-bold text-slate-800">Bảo hành dài hạn</p>
                            <p class="text-xs text-slate-500">Bảo hành thanh nhôm 5 - 10 năm</p>
                        </div>
                    </div>
                    <div class="flex items-center gap-3 p-2.5 rounded-lg bg-slate-50">
                        <div class="w-10 h-10 rounded-full bg-brand-light text-brand flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-award"></i>
                        </div>
                        <div>
                            <p class="font-bold text-slate-800">Chính hãng 100%</p>
                            <p class="text-xs text-slate-500">Nhôm Xingfa tem đỏ & Kinlong chuẩn</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================
         7. GIỚI THIỆU CÔNG TY & THÔNG SỐ NỔI BẬT (Chuẩn Flatsome)
         ========================================================= -->
    <section id="gioi-thieu" class="py-8 sm:py-12 bg-white">
        <div class="tv-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center">
                <div class="lg:col-span-7 space-y-3.5">
                    <p class="text-xs font-bold uppercase tracking-wider text-brand-accent">Về chúng tôi</p>
                    <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold text-brand leading-tight">
                        CÔNG TY TNHH THÀNH VINH WINDOW — CỬA NHÔM XINGFA ĐÀ NẴNG
                    </h2>
                    <p class="text-sm text-slate-600 leading-relaxed">
                        <strong>Thành Vinh Window</strong> là đơn vị chuyên tư vấn, thiết kế, gia công và thi công lắp đặt các hạng mục nhôm kính cao cấp tại Đà Nẵng và khu vực Miền Trung. Các dòng sản phẩm chủ lực gồm: <strong>Cửa nhôm Xingfa nhập khẩu</strong>, Cửa nhựa lõi thép, Cửa kính cường lực, Cửa kính tự động, Cầu thang kính, Kính ốp bếp và Phòng tắm kính.
                    </p>
                    <p class="text-sm text-slate-600 leading-relaxed">
                        Với phương châm <strong>“Chất lượng tạo uy tín – Cửa đẹp cho mọi công trình”</strong>, chúng tôi sở hữu dây chuyền máy ép góc CNC hiện đại cùng đội ngũ kỹ thuật giàu kinh nghiệm, mang đến không gian sống sang trọng, cách âm cách nhiệt vượt trội và bền bỉ trước khí hậu ven biển Đà Nẵng.
                    </p>
                    <div class="grid grid-cols-2 sm:grid-cols-4 gap-3 pt-2">
                        <div class="bg-brand-light rounded-xl p-3.5 text-center border border-brand/10">
                            <p class="text-xl sm:text-2xl font-extrabold text-brand">150+</p>
                            <p class="text-[11px] sm:text-xs font-semibold text-slate-600 mt-0.5">Dự án hoàn thành</p>
                        </div>
                        <div class="bg-brand-light rounded-xl p-3.5 text-center border border-brand/10">
                            <p class="text-xl sm:text-2xl font-extrabold text-brand">50+</p>
                            <p class="text-[11px] sm:text-xs font-semibold text-slate-600 mt-0.5">Nhân sự kỹ thuật</p>
                        </div>
                        <div class="bg-brand-light rounded-xl p-3.5 text-center border border-brand/10">
                            <p class="text-xl sm:text-2xl font-extrabold text-brand">100+</p>
                            <p class="text-[11px] sm:text-xs font-semibold text-slate-600 mt-0.5">Mẫu cửa chất lượng</p>
                        </div>
                        <div class="bg-brand-light rounded-xl p-3.5 text-center border border-brand/10">
                            <p class="text-xl sm:text-2xl font-extrabold text-brand">100%</p>
                            <p class="text-[11px] sm:text-xs font-semibold text-slate-600 mt-0.5">Khách hàng hài lòng</p>
                        </div>
                    </div>
                </div>
                <div class="lg:col-span-5">
                    <div class="rounded-xl overflow-hidden border border-slate-200 shadow-md bg-slate-100 aspect-[4/3]">
                        <img
                            src="https://lh3.googleusercontent.com/d/1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX=w900"
                            data-drive-id="1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX"
                            alt="Showroom và sản phẩm Thành Vinh Window Đà Nẵng"
                            class="w-full h-full object-cover"
                            onerror="handleDriveImageError(this, '640x480', 'Thanh+Vinh+Window+Da+Nang')"
                        >
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================
         8. CÁC DỰ ÁN NỔI BẬT TẠI ĐÀ NẴNG (6 Dự án thực tế)
         ========================================================= -->
    <section id="cong-trinh" class="py-8 sm:py-11 bg-slate-50 border-t border-slate-200/80">
        <div class="tv-container">
            <div class="flatsome-section-title">
                <h2 class="text-base sm:text-xl lg:text-2xl">Các dự án tiêu biểu tại Đà Nẵng</h2>
            </div>

            <div id="projectsGrid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-5">
                <!-- Được render động bằng JavaScript từ danh sách 6 dự án Đà Nẵng -->
            </div>
        </div>
    </section>

    <!-- =========================================================
         9. FORM YÊU CẦU & NHẬN BÁO GIÁ NGAY TRÊN TRANG CHỦ
         ========================================================= -->
    <section id="form-bao-gia" class="py-9 sm:py-12 bg-brand text-white">
        <div class="tv-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center">
                <div class="lg:col-span-6 space-y-4">
                    <p class="text-xs font-bold uppercase tracking-widest text-amber-300">Đăng ký tư vấn miễn phí</p>
                    <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold leading-tight">
                        ĐĂNG KÝ NHẬN BÁO GIÁ CỬA NHÔM XINGFA & KÍNH CƯỜNG LỰC
                    </h2>
                    <p class="text-sm text-blue-100 leading-relaxed">
                        Quý khách vui lòng để lại thông tin hoặc kích thước sơ bộ. Kỹ thuật viên của <strong>CÔNG TY TNHH THÀNH VINH WINDOW</strong> sẽ bóc tách khối lượng, gửi bảng báo giá chi tiết và hẹn lịch đo đạc trực tiếp tận công trình hoàn toàn miễn phí.
                    </p>
                    <ul class="space-y-2 text-xs sm:text-sm text-blue-50">
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-circle-check text-amber-300"></i>
                            <span>Báo giá minh bạch, chi tiết từng hạng mục nhôm, kính và phụ kiện.</span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-circle-check text-amber-300"></i>
                            <span>Chiết khấu hấp dẫn cho công trình nhà phố, biệt thự, khách sạn.</span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-circle-check text-amber-300"></i>
                            <span>Hỗ trợ nhanh qua Hotline / Zalo: <strong>0905.310.041</strong></span>
                        </li>
                    </ul>
                </div>

                <div class="lg:col-span-6">
                    <form id="quoteForm" onsubmit="handleQuoteSubmit(event)"
                        class="bg-white text-slate-800 rounded-xl p-5 sm:p-6 shadow-xl space-y-3.5">
                        <h3 class="text-base sm:text-lg font-extrabold text-brand uppercase text-center">
                            Gửi yêu cầu báo giá nhanh
                        </h3>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label for="qName" class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên *</label>
                                <input id="qName" type="text" required placeholder="Nhập họ tên của bạn"
                                    class="w-full px-3 py-2.5 text-sm border border-slate-300 rounded-lg focus:border-brand focus:ring-2 focus:ring-brand/20 outline-none">
                            </div>
                            <div>
                                <label for="qPhone" class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                                <input id="qPhone" type="tel" required placeholder="VD: 0905.310.041"
                                    class="w-full px-3 py-2.5 text-sm border border-slate-300 rounded-lg focus:border-brand focus:ring-2 focus:ring-brand/20 outline-none">
                            </div>
                        </div>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label for="qCategory" class="block text-xs font-semibold text-slate-700 mb-1">Hạng mục quan tâm</label>
                                <select id="qCategory"
                                    class="w-full px-3 py-2.5 text-sm border border-slate-300 rounded-lg focus:border-brand focus:ring-2 focus:ring-brand/20 outline-none bg-white">
                                    <option value="Cửa nhôm Xingfa">Cửa nhôm Xingfa</option>
                                    <option value="Cửa kính cường lực">Cửa kính cường lực</option>
                                    <option value="Cửa nhựa lõi thép">Cửa nhựa lõi thép</option>
                                    <option value="Cửa kính tự động">Cửa kính tự động</option>
                                    <option value="Cầu thang kính">Cầu thang kính</option>
                                    <option value="Kính ốp bếp">Kính ốp bếp</option>
                                    <option value="Phòng tắm kính">Phòng tắm kính</option>
                                    <option value="Thi công trọn gói công trình">Thi công trọn gói công trình</option>
                                </select>
                            </div>
                            <div>
                                <label for="qAddress" class="block text-xs font-semibold text-slate-700 mb-1">Khu vực công trình</label>
                                <input id="qAddress" type="text" placeholder="VD: Thanh Khê, Hải Châu, Sơn Trà..."
                                    class="w-full px-3 py-2.5 text-sm border border-slate-300 rounded-lg focus:border-brand focus:ring-2 focus:ring-brand/20 outline-none">
                            </div>
                        </div>
                        <div>
                            <label for="qNote" class="block text-xs font-semibold text-slate-700 mb-1">Nội dung / Kích thước dự kiến</label>
                            <textarea id="qNote" rows="3" placeholder="Ghi chú số lượng bộ cửa, kích thước hoặc yêu cầu tư vấn..."
                                class="w-full px-3 py-2 text-sm border border-slate-300 rounded-lg focus:border-brand focus:ring-2 focus:ring-brand/20 outline-none"></textarea>
                        </div>

                        <!-- Hộp thông báo trạng thái gửi form (thay thế hoàn toàn alert) -->
                        <div id="quoteSuccessBox" class="hidden p-3 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs sm:text-sm font-medium">
                            <i class="fa-solid fa-circle-check text-emerald-600 mr-1.5"></i>
                            <span id="quoteSuccessText"></span>
                        </div>

                        <button type="submit"
                            class="w-full bg-brand-accent hover:bg-red-700 text-white font-bold text-sm py-3 rounded-lg shadow transition flex items-center justify-center gap-2">
                            <i class="fa-solid fa-paper-plane"></i>
                            <span>GỬI YÊU CẦU NHẬN BÁO GIÁ NGAY</span>
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================
         10. DANH MỤC CÁC BÀI VIẾT / TIN TỨC NỔI BẬT TRANG CHỦ
         ========================================================= -->
    <section id="tin-tuc" class="py-8 sm:py-11 bg-white">
        <div class="tv-container">
            <div class="flatsome-section-title">
                <h2 class="text-base sm:text-xl lg:text-2xl">Tin tức & Kiến thức nhôm kính</h2>
            </div>

            <div id="newsGrid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-5">
                <!-- Được render động bằng JavaScript -->
            </div>
        </div>
    </section>

    <!-- =========================================================
         11. ĐỐI TÁC CỦA CHÚNG TÔI (6 Logo đối tác từ Google Drive)
         ========================================================= -->
    <section class="py-8 sm:py-10 bg-slate-50 border-t border-slate-200/80">
        <div class="tv-container">
            <div class="flatsome-section-title">
                <h2 class="text-base sm:text-xl lg:text-2xl">Đối tác của chúng tôi</h2>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3 sm:gap-4">
                <div class="bg-white border border-slate-200 rounded-xl p-3.5 h-24 flex items-center justify-center shadow-sm hover:shadow transition">
                    <img src="https://lh3.googleusercontent.com/d/13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk=w500"
                        data-drive-id="13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk" alt="Đối tác Thành Vinh Window 1"
                        class="max-h-16 max-w-full object-contain"
                        onerror="handleDriveImageError(this, '200x80', 'DOI+TAC+1')">
                </div>
                <div class="bg-white border border-slate-200 rounded-xl p-3.5 h-24 flex items-center justify-center shadow-sm hover:shadow transition">
                    <img src="https://lh3.googleusercontent.com/d/1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq=w500"
                        data-drive-id="1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq" alt="Đối tác Thành Vinh Window 2"
                        class="max-h-16 max-w-full object-contain"
                        onerror="handleDriveImageError(this, '200x80', 'DOI+TAC+2')">
                </div>
                <div class="bg-white border border-slate-200 rounded-xl p-3.5 h-24 flex items-center justify-center shadow-sm hover:shadow transition">
                    <img src="https://lh3.googleusercontent.com/d/1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn=w500"
                        data-drive-id="1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn" alt="Đối tác Thành Vinh Window 3"
                        class="max-h-16 max-w-full object-contain"
                        onerror="handleDriveImageError(this, '200x80', 'DOI+TAC+3')">
                </div>
                <div class="bg-white border border-slate-200 rounded-xl p-3.5 h-24 flex items-center justify-center shadow-sm hover:shadow transition">
                    <img src="https://lh3.googleusercontent.com/d/1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT=w500"
                        data-drive-id="1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT" alt="Đối tác Thành Vinh Window 4"
                        class="max-h-16 max-w-full object-contain"
                        onerror="handleDriveImageError(this, '200x80', 'DOI+TAC+4')">
                </div>
                <div class="bg-white border border-slate-200 rounded-xl p-3.5 h-24 flex items-center justify-center shadow-sm hover:shadow transition">
                    <img src="https://lh3.googleusercontent.com/d/1SDcarhnX0yypmqdbawICjYBRtFnKngn-=w500"
                        data-drive-id="1SDcarhnX0yypmqdbawICjYBRtFnKngn-" alt="Đối tác Thành Vinh Window 5"
                        class="max-h-16 max-w-full object-contain"
                        onerror="handleDriveImageError(this, '200x80', 'DOI+TAC+5')">
                </div>
                <div class="bg-white border border-slate-200 rounded-xl p-3.5 h-24 flex items-center justify-center shadow-sm hover:shadow transition">
                    <img src="https://lh3.googleusercontent.com/d/1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg=w500"
                        data-drive-id="1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg" alt="Đối tác Thành Vinh Window 6"
                        class="max-h-16 max-w-full object-contain"
                        onerror="handleDriveImageError(this, '200x80', 'DOI+TAC+6')">
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================
         12. BẢN ĐỒ GOOGLE MAP & FANPAGE FACEBOOK NGOÀI TRANG CHỦ
         ========================================================= -->
    <section id="lien-he" class="py-8 sm:py-11 bg-white border-t border-slate-200/80">
        <div class="tv-container">
            <div class="flatsome-section-title">
                <h2 class="text-base sm:text-xl lg:text-2xl">Bản đồ chỉ đường & Fanpage Facebook</h2>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 lg:gap-6 items-stretch">
                <!-- Cột trái: Bản đồ Google Map 1133 Nguyễn Tất Thành, Thanh Khê, Đà Nẵng -->
                <div class="lg:col-span-7 bg-white border border-slate-200 rounded-xl overflow-hidden shadow-sm flex flex-col">
                    <div class="px-4 py-3 bg-slate-50 border-b border-slate-200 flex flex-wrap items-center justify-between gap-2">
                        <div class="flex items-center gap-2">
                            <i class="fa-solid fa-map-location-dot text-brand text-base"></i>
                            <h3 class="text-sm font-bold text-slate-800">Google Map — 1133 Nguyễn Tất Thành, Thanh Khê, Đà Nẵng</h3>
                        </div>
                        <a href="https://www.google.com/maps/search/?api=1&query=1133+Nguy%E1%BB%85n+T%E1%BA%A5t+Th%C3%A0nh,+Thanh+Kh%C3%AA,+%C4%90%C3%A0+N%E1%BA%B5ng"
                            target="_blank" rel="noopener noreferrer"
                            class="text-xs font-semibold text-brand hover:underline whitespace-nowrap">
                            Mở bản đồ lớn <i class="fa-solid fa-arrow-up-right-from-square ml-0.5 text-[10px]"></i>
                        </a>
                    </div>
                    <div class="w-full h-[300px] sm:h-[340px] flex-1 bg-slate-100">
                        <iframe
                            title="Bản đồ CÔNG TY TNHH THÀNH VINH WINDOW - 1133 Nguyễn Tất Thành, Đà Nẵng"
                            src="https://maps.google.com/maps?q=1133%20Nguy%E1%BB%85n%20T%E1%BA%A5t%20Th%C3%A0nh,%20Thanh%20Kh%C3%AA,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                            class="w-full h-full border-0"
                            loading="lazy"
                            referrerpolicy="no-referrer-when-downgrade">
                        </iframe>
                    </div>
                </div>

                <!-- Cột phải: Fanpage Facebook ngoài trang chủ -->
                <div class="lg:col-span-5 bg-white border border-slate-200 rounded-xl overflow-hidden shadow-sm flex flex-col">
                    <div class="px-4 py-3 bg-[#1877F2] text-white flex items-center justify-between">
                        <div class="flex items-center gap-2">
                            <i class="fa-brands fa-facebook text-lg"></i>
                            <h3 class="text-sm font-bold">Fanpage Facebook Chính Thức</h3>
                        </div>
                        <span class="text-[11px] bg-white/20 px-2 py-0.5 rounded font-medium">Trực tuyến</span>
                    </div>

                    <!-- Khối hiển thị Fanpage chuẩn (luôn hiển thị sắc nét trên mọi trình duyệt & điện thoại) -->
                    <div class="p-4 flex-1 flex flex-col justify-between bg-slate-50">
                        <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm">
                            <!-- Ảnh bìa Fanpage -->
                            <div class="relative h-32 sm:h-36 bg-brand overflow-hidden">
                                <img
                                    src="https://lh3.googleusercontent.com/d/1za_IJpAm850uulT6IuhBsk1THb3LuPuc=w800"
                                    data-drive-id="1za_IJpAm850uulT6IuhBsk1THb3LuPuc"
                                    alt="Ảnh bìa Fanpage Thành Vinh Window"
                                    class="w-full h-full object-cover opacity-85"
                                    onerror="handleDriveImageError(this, '600x240', 'THANH+VINH+WINDOW+FANPAGE')"
                                >
                                <div class="absolute inset-0 bg-gradient-to-t from-black/75 via-black/25 to-transparent"></div>
                                <div class="absolute bottom-2.5 left-3 right-3 flex items-center gap-2.5">
                                    <div class="w-12 h-12 rounded-lg bg-white p-1 shadow shrink-0 flex items-center justify-center">
                                        <img
                                            src="https://lh3.googleusercontent.com/d/12qNv2x91Cyhk70b8jXiqSk17IHIjYlV1=w300"
                                            data-drive-id="12qNv2x91Cyhk70b8jXiqSk17IHIjYlV1"
                                            alt="Avatar Fanpage Thành Vinh Window"
                                            class="max-w-full max-h-full object-contain"
                                            onerror="handleDriveImageError(this, '80x80', 'TV')"
                                        >
                                    </div>
                                    <div class="min-w-0 text-white">
                                        <p class="text-sm font-bold truncate">Thành Vinh Window - Đà Nẵng</p>
                                        <p class="text-[11px] text-slate-200">Cửa Nhôm Xingfa & Kính Cường Lực</p>
                                    </div>
                                </div>
                            </div>

                            <!-- Thân Fanpage -->
                            <div class="p-3.5 space-y-3">
                                <p class="text-xs text-slate-600 leading-relaxed">
                                    Cập nhật hình ảnh thi công thực tế, bảng giá cửa nhôm Xingfa mới nhất và các chương trình ưu đãi lắp đặt tại Đà Nẵng.
                                </p>
                                <div class="flex items-center justify-between text-[11px] text-slate-500 border-y border-slate-100 py-2">
                                    <span><i class="fa-solid fa-thumbs-up text-[#1877F2] mr-1"></i>5.820 lượt thích</span>
                                    <span><i class="fa-solid fa-users text-brand mr-1"></i>6.150 người theo dõi</span>
                                </div>
                                <div class="grid grid-cols-2 gap-2">
                                    <a href="https://www.facebook.com/search/top?q=Th%C3%A0nh%20Vinh%20Window%20%C4%90%C3%A0%20N%E1%BA%B5ng"
                                        target="_blank" rel="noopener noreferrer"
                                        class="inline-flex items-center justify-center gap-1.5 bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-bold py-2 px-3 rounded-lg transition">
                                        <i class="fa-brands fa-facebook-f"></i>
                                        <span>Thích Trang</span>
                                    </a>
                                    <a href="https://zalo.me/0905310041"
                                        target="_blank" rel="noopener noreferrer"
                                        class="inline-flex items-center justify-center gap-1.5 bg-slate-100 hover:bg-slate-200 text-slate-800 text-xs font-bold py-2 px-3 rounded-lg transition">
                                        <i class="fa-regular fa-comment-dots text-brand"></i>
                                        <span>Nhắn tin tư vấn</span>
                                    </a>
                                </div>
                            </div>
                        </div>

                        <p class="text-[11px] text-slate-500 text-center mt-3">
                            Địa chỉ xưởng & showroom: 1133 Nguyễn Tất Thành, P. Thanh Khê, TP Đà Nẵng
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================
         13. FOOTER CHUẨN FLATSOME 4 CỘT
         ========================================================= -->
    <footer class="bg-brand-dark text-blue-100 pt-10 pb-6 border-t-4 border-brand-accent">
        <div class="tv-container">
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-7 pb-8 border-b border-white/15">
                <!-- Cột 1: Thông tin công ty -->
                <div class="space-y-3">
                    <div class="inline-flex items-center gap-2.5 bg-white px-3 py-2 rounded-lg">
                        <img
                            src="https://lh3.googleusercontent.com/d/12qNv2x91Cyhk70b8jXiqSk17IHIjYlV1=w500"
                            data-drive-id="12qNv2x91Cyhk70b8jXiqSk17IHIjYlV1"
                            alt="Logo CÔNG TY TNHH THÀNH VINH WINDOW"
                            class="h-9 w-auto object-contain"
                            onerror="handleDriveImageError(this, '160x48', 'THANH+VINH+WINDOW')"
                        >
                    </div>
                    <h4 class="text-sm font-extrabold text-white uppercase">CÔNG TY TNHH THÀNH VINH WINDOW</h4>
                    <ul class="space-y-2 text-xs leading-relaxed">
                        <li class="flex items-start gap-2">
                            <i class="fa-solid fa-location-dot text-amber-400 mt-0.5 shrink-0"></i>
                            <span>Địa chỉ: 1133 Nguyễn Tất Thành, Phường Thanh Khê, TP Đà Nẵng</span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-phone text-amber-400 shrink-0"></i>
                            <a href="tel:0905310041" class="hover:text-white font-semibold">Hotline: 0905.310.041</a>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-globe text-amber-400 shrink-0"></i>
                            <a href="https://thanhvinhwindow.com" class="hover:text-white">Website: thanhvinhwindow.com</a>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-envelope text-amber-400 shrink-0"></i>
                            <span>Email: info@thanhvinhwindow.com</span>
                        </li>
                    </ul>
                </div>

                <!-- Cột 2: Cửa nhôm Xingfa -->
                <div>
                    <h4 class="text-sm font-bold text-white uppercase pb-2 mb-3 border-b border-white/20">Cửa nhôm Xingfa</h4>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#san-pham-xingfa" onclick="filterAndHighlight('xingfa', '1 cánh')" class="hover:text-amber-300 transition">Cửa nhôm Xingfa 1 cánh</a></li>
                        <li><a href="#san-pham-xingfa" onclick="filterAndHighlight('xingfa', '2 cánh')" class="hover:text-amber-300 transition">Cửa nhôm Xingfa 2 cánh</a></li>
                        <li><a href="#san-pham-xingfa" onclick="filterAndHighlight('xingfa', '3 cánh')" class="hover:text-amber-300 transition">Cửa nhôm Xingfa 3 cánh</a></li>
                        <li><a href="#san-pham-xingfa" onclick="filterAndHighlight('xingfa', '4 cánh')" class="hover:text-amber-300 transition">Cửa nhôm Xingfa 4 cánh</a></li>
                        <li><a href="#san-pham-xingfa" onclick="filterAndHighlight('xingfa', 'Xếp Trượt')" class="hover:text-amber-300 transition">Cửa nhôm Xingfa 5 cánh / Xếp trượt</a></li>
                        <li><a href="#san-pham-xingfa" onclick="filterAndHighlight('xingfa', 'mở hất')" class="hover:text-amber-300 transition">Cửa sổ mở hất 2 cánh Xingfa</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Danh mục sản phẩm -->
                <div>
                    <h4 class="text-sm font-bold text-white uppercase pb-2 mb-3 border-b border-white/20">Danh mục sản phẩm</h4>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#san-pham-xingfa" onclick="filterProducts('xingfa')" class="hover:text-amber-300 transition">Cửa nhôm Xingfa Đà Nẵng</a></li>
                        <li><a href="#san-pham-xingfa" onclick="filterProducts('nhua-loi-thep')" class="hover:text-amber-300 transition">Cửa nhựa lõi thép Đà Nẵng</a></li>
                        <li><a href="#san-pham-xingfa" onclick="filterProducts('tu-dong')" class="hover:text-amber-300 transition">Cửa kính tự động Đà Nẵng</a></li>
                        <li><a href="#san-pham-xingfa" onclick="filterProducts('cau-thang')" class="hover:text-amber-300 transition">Cầu thang kính cường lực</a></li>
                        <li><a href="#san-pham-xingfa" onclick="filterProducts('op-bep')" class="hover:text-amber-300 transition">Kính màu ốp bếp cường lực</a></li>
                        <li><a href="#san-pham-xingfa" onclick="filterProducts('phong-tam')" class="hover:text-amber-300 transition">Phòng tắm kính cường lực</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Liên kết nhanh & Hỗ trợ -->
                <div>
                    <h4 class="text-sm font-bold text-white uppercase pb-2 mb-3 border-b border-white/20">Hỗ trợ khách hàng</h4>
                    <ul class="space-y-2 text-xs mb-4">
                        <li><a href="#gioi-thieu" class="hover:text-amber-300 transition">Giới thiệu Thành Vinh Window</a></li>
                        <li><a href="#cong-trinh" class="hover:text-amber-300 transition">Công trình đã thi công</a></li>
                        <li><a href="#form-bao-gia" class="hover:text-amber-300 transition">Đăng ký nhận báo giá</a></li>
                        <li><a href="#tin-tuc" class="hover:text-amber-300 transition">Tin tức & Tư vấn kỹ thuật</a></li>
                        <li><a href="#lien-he" class="hover:text-amber-300 transition">Bản đồ & Liên hệ showroom</a></li>
                    </ul>
                    <div class="flex items-center gap-2.5">
                        <a href="https://www.facebook.com/search/top?q=Th%C3%A0nh%20Vinh%20Window%20%C4%90%C3%A0%20N%E1%BA%B5ng" target="_blank" rel="noopener noreferrer" aria-label="Facebook"
                            class="w-8 h-8 rounded-full bg-[#1877F2] text-white flex items-center justify-center hover:opacity-90 transition">
                            <i class="fa-brands fa-facebook-f text-xs"></i>
                        </a>
                        <a href="https://zalo.me/0905310041" target="_blank" rel="noopener noreferrer" aria-label="Zalo"
                            class="w-8 h-8 rounded-full bg-[#0068FF] text-white flex items-center justify-center font-extrabold text-[10px] hover:opacity-90 transition">
                            Zalo
                        </a>
                        <a href="tel:0905310041" aria-label="Gọi điện"
                            class="w-8 h-8 rounded-full bg-brand-accent text-white flex items-center justify-center hover:opacity-90 transition">
                            <i class="fa-solid fa-phone text-xs"></i>
                        </a>
                    </div>
                </div>
            </div>

            <div class="pt-5 text-center text-xs text-blue-200/80">
                Copyright 2026 © Bản quyền thuộc về <strong class="text-white">CÔNG TY TNHH THÀNH VINH WINDOW</strong> — thanhvinhwindow.com
            </div>
        </div>
    </footer>

    <!-- =========================================================
         14. CỤM NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE
         Tương thích mượt trên cả máy tính và điện thoại, không che nội dung
         ========================================================= -->
    <div class="fixed bottom-4 right-3 sm:bottom-6 sm:right-5 z-40 flex flex-col items-end gap-2.5">
        <!-- Nút Facebook -->
        <a href="https://www.facebook.com/search/top?q=Th%C3%A0nh%20Vinh%20Window%20%C4%90%C3%A0%20N%E1%BA%B5ng"
            target="_blank" rel="noopener noreferrer" title="Fanpage Facebook Thành Vinh Window"
            class="group flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white rounded-full shadow-lg p-2.5 sm:px-3.5 sm:py-2.5 transition">
            <i class="fa-brands fa-facebook-f text-base w-5 text-center"></i>
            <span class="hidden sm:inline text-xs font-bold pr-1">Facebook</span>
        </a>

        <!-- Nút Zalo -->
        <a href="https://zalo.me/0905310041"
            target="_blank" rel="noopener noreferrer" title="Chat Zalo 0905.310.041"
            class="group flex items-center gap-2 bg-[#0068FF] hover:bg-blue-600 text-white rounded-full shadow-lg p-2.5 sm:px-3.5 sm:py-2.5 transition">
            <span class="w-5 h-5 flex items-center justify-center font-extrabold text-[11px] leading-none">Zalo</span>
            <span class="hidden sm:inline text-xs font-bold pr-1">Chat Zalo</span>
        </a>

        <!-- Nút Hotline -->
        <a href="tel:0905310041" title="Gọi Hotline 0905.310.041"
            class="pulse-hotline flex items-center gap-2 bg-brand-accent hover:bg-red-700 text-white rounded-full shadow-xl px-3.5 py-2.5 transition">
            <i class="fa-solid fa-phone-volume text-sm sm:text-base"></i>
            <span class="text-xs sm:text-sm font-extrabold tracking-wide">0905.310.041</span>
        </a>
    </div>

    <!-- =========================================================
         MODAL XEM CHI TIẾT SẢN PHẨM / DỰ ÁN / BÀI VIẾT (KHÔNG DÙNG ALERT)
         ========================================================= -->
    <div id="detailModal" class="fixed inset-0 z-50 hidden items-center justify-center p-3 sm:p-5 bg-slate-900/65">
        <div class="bg-white rounded-xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl relative">
            <button type="button" onclick="closeDetailModal()" aria-label="Đóng cửa sổ"
                class="sticky top-3 float-right mr-3 mt-3 w-8 h-8 rounded-full bg-slate-100 hover:bg-slate-200 text-slate-700 flex items-center justify-center z-10">
                <i class="fa-solid fa-xmark"></i>
            </button>
            <div id="detailModalBody" class="p-5 sm:p-6"></div>
        </div>
    </div>

    <!-- =========================================================
         JAVASCRIPT XỬ LÝ DỮ LIỆU, BANNER TỰ TRƯỢT, LỌC SẢN PHẨM & MODAL
         ========================================================= -->
    <script>
        /* =========================================================
           1. HÀM TẠO LINK ẢNH GOOGLE DRIVE & FALLBACK AN TOÀN
           ========================================================= */
        function getDriveImgUrl(id, width = 800) {
            return `https://lh3.googleusercontent.com/d/${id}=w${width}`;
        }

        function handleDriveImageError(img, size, label) {
            const driveId = img.getAttribute('data-drive-id');
            const stage = img.getAttribute('data-err-stage') || '0';
            if (stage === '0' && driveId) {
                img.setAttribute('data-err-stage', '1');
                img.src = `https://drive.google.com/thumbnail?id=${driveId}&sz=w1000`;
            } else {
                img.onerror = null;
                img.src = `https://placehold.co/${size}/0B4A8B/FFFFFF?text=${label}`;
            }
        }

        /* =========================================================
           2. DỮ LIỆU SẢN PHẨM (ĐÚNG ẢNH DRIVE, GIÁ & % GIẢM GIÁ)
           ========================================================= */
        const productsData = [
            {
                id: 'xf-1',
                category: 'xingfa',
                categoryName: 'Cửa nhôm Xingfa',
                name: 'Cửa đi quay mở 1 cánh nhôm xingfa',
                driveId: '1-0eBWGjPwzQ-C9c1Wjws9wt0gbsulkPm',
                oldPrice: 2450000,
                price: 2100000,
                discount: 14,
                unit: '₫/m²',
                specs: [
                    'Thanh profile: Nhôm Xingfa hệ 55 nhập khẩu tem đỏ, dày 2.0mm',
                    'Kính: Kính cường lực 8mm hoặc kính dán an toàn 6.38mm Hải Long',
                    'Phụ kiện: Kinlong đồng bộ chính hãng (bản lề 3D, khóa đa điểm)',
                    'Màu sắc: Xám ghi, Nâu cafe, Đen tuyền, Trắng sứ, Vân gỗ'
                ],
                desc: 'Thiết kế mở quay 1 cánh gọn gàng, kín khít tuyệt đối nhờ hệ gioăng kép EPDM và keo ép góc PU88. Phù hợp làm cửa thông phòng, cửa ban công, cửa nhà vệ sinh.'
            },
            {
                id: 'xf-2',
                category: 'xingfa',
                categoryName: 'Cửa nhôm Xingfa',
                name: 'Cửa đi quay mở 2 cánh nhôm xingfa',
                driveId: '1h2r2rbPrEL7dgLE-MiE5lBBuE8gFNehb',
                oldPrice: 2500000,
                price: 2100000,
                discount: 16,
                unit: '₫/m²',
                specs: [
                    'Thanh profile: Nhôm Xingfa hệ 55 nhập khẩu dày 2.0mm',
                    'Kính: Kính cường lực 8mm / 10mm tiêu chuẩn an toàn',
                    'Phụ kiện: Bộ khóa đa điểm Kinlong, chốt cánh phụ chống cạy',
                    'Bảo hành: 5 - 10 năm thanh nhôm & 2 năm phụ kiện'
                ],
                desc: 'Mẫu cửa mặt tiền, cửa đi chính 2 cánh cân đối, cách âm cách nhiệt vượt trội, chịu gió bão cấp 12 phù hợp khí hậu Đà Nẵng.'
            },
            {
                id: 'xf-3',
                category: 'xingfa',
                categoryName: 'Cửa nhôm Xingfa',
                name: 'Cửa đi quay mở 3 cánh nhôm xingfa',
                driveId: '17Qi2D8ntACnVrTeRPZ2V7rC0FmI8ecaR',
                oldPrice: 2550000,
                price: 2100000,
                discount: 18,
                unit: '₫/m²',
                specs: [
                    'Thanh profile: Nhôm Xingfa hệ 55 độ dày 2.0mm chính hãng',
                    'Kính: Kính cường lực 8mm - 10mm trong suốt hoặc kính hộp',
                    'Phụ kiện: Kinlong chính hãng chống rỉ sét vùng biển',
                    'Thi công: Ép góc CNC chuẩn xác, bơm keo Dow Corning chống thấm'
                ],
                desc: 'Giải pháp tối ưu cho khung cửa có chiều ngang vừa phải cần độ thông thoáng cao, dễ dàng linh hoạt mở 1 cánh hoặc mở toàn bộ 3 cánh.'
            },
            {
                id: 'xf-4',
                category: 'xingfa',
                categoryName: 'Cửa nhôm Xingfa',
                name: 'Cửa đi quay mở 4 cánh nhôm xingfa',
                driveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
                oldPrice: 2550000,
                price: 2100000,
                discount: 18,
                unit: '₫/m²',
                specs: [
                    'Thanh profile: Nhôm Xingfa nhập khẩu hệ 55 dày 2.0mm',
                    'Kính: Kính cường lực 8mm / 10mm chịu lực va đập tốt',
                    'Phụ kiện: Bản lề 4D chịu tải trọng lớn, khóa đa điểm Kinlong',
                    'Ứng dụng: Cửa mặt tiền nhà phố, biệt thự, showroom'
                ],
                desc: 'Dòng cửa mặt tiền sang trọng bậc nhất hiện nay, mở rộng tối đa không gian đi lại, đón sáng tự nhiên và tạo điểm nhấn kiến trúc đẳng cấp.'
            },
            {
                id: 'xf-5',
                category: 'xingfa',
                categoryName: 'Cửa nhôm Xingfa',
                name: 'Cửa Nhôm Xingfa Cửa Đi Xếp Trượt',
                driveId: '1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ',
                oldPrice: 2650000,
                price: 2250000,
                discount: 15,
                unit: '₫/m²',
                specs: [
                    'Thanh profile: Nhôm Xingfa hệ 63 chuyên dụng xếp trượt (dày 1.8 - 3.5mm)',
                    'Quy cách: Thiết kế linh hoạt 3 cánh, 4 cánh, 5 cánh, 6 cánh',
                    'Phụ kiện: Ray trượt treo chịu lực, bánh xe đôi vận hành êm ái',
                    'Ứng dụng: Biệt thự sân vườn, khách sạn, resort view biển'
                ],
                desc: 'Thiết kế thông minh vừa xếp gọn sang 1 hoặc 2 bên vừa mở quay 1 cánh đi lại hàng ngày, giải phóng 95% diện tích lối đi.'
            },
            {
                id: 'xf-6',
                category: 'xingfa',
                categoryName: 'Cửa nhôm Xingfa',
                name: 'Cửa sổ mở hất 2 cánh nhôm Xingfa',
                driveId: '11fS_oEeJtnDICQZ77fJlYl6GhHf-GOhA',
                oldPrice: 2300000,
                price: 1950000,
                discount: 15,
                unit: '₫/m²',
                specs: [
                    'Thanh profile: Nhôm Xingfa hệ 55 dày 1.4mm sơn tĩnh điện',
                    'Góc mở: Mở hất 45 độ kèm thanh định vị chống gió dập',
                    'Kính: Kính cường lực 8mm hoặc kính dán an toàn 6.38mm',
                    'Ưu điểm: Lấy thoáng ngay cả khi trời mưa, không hắt nước'
                ],
                desc: 'Mẫu cửa sổ được ưa chuộng cho nhà cao tầng, khách sạn và căn hộ tại Đà Nẵng nhờ khả năng chống hắt mưa và chịu lực gió cực tốt.'
            },
            /* Sản phẩm bổ sung theo đúng 5 danh mục còn lại của web mẫu */
            {
                id: 'nlt-1',
                category: 'nhua-loi-thep',
                categoryName: 'Cửa nhựa lõi thép',
                name: 'Cửa nhựa lõi thép uPVC cách âm cao cấp',
                driveId: '1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA',
                oldPrice: 1750000,
                price: 1490000,
                discount: 15,
                unit: '₫/m²',
                specs: [
                    'Thanh nhựa: uPVC Sparlee / Rehau có lõi thép mạ kẽm gia cường',
                    'Tính năng: Cách âm, cách nhiệt vượt trội, không cong vênh mối mọt',
                    'Phụ kiện: GQ / Roto đồng bộ chính hãng'
                ],
                desc: 'Giải pháp cửa phòng ngủ, cửa văn phòng và nhà phố yên tĩnh với khả năng tiêu âm, chống ồn và tiết kiệm điện điều hòa hiệu quả.'
            },
            {
                id: 'td-1',
                category: 'tu-dong',
                categoryName: 'Cửa kính tự động',
                name: 'Cửa kính trượt tự động cảm biến mắt thần',
                driveId: '1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ',
                oldPrice: 28500000,
                price: 24500000,
                discount: 14,
                unit: '₫/bộ',
                specs: [
                    'Thiết bị: Motor trượt tự động Hàn Quốc / Nhật Bản / Đức',
                    'Kính: Kính cường lực 10mm - 12mm an toàn cao',
                    'Cảm biến: Mắt thần đóng mở thông minh kèm cảm biến chống kẹt'
                ],
                desc: 'Thi công chuyên nghiệp cho sảnh khách sạn, siêu thị, showroom, ngân hàng và tòa nhà văn phòng tại Đà Nẵng.'
            },
            {
                id: 'ct-1',
                category: 'cau-thang',
                categoryName: 'Cầu thang kính',
                name: 'Cầu thang kính cường lực tay vịn gỗ hiện đại',
                driveId: '1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul',
                oldPrice: 1450000,
                price: 1250000,
                discount: 14,
                unit: '₫/md',
                specs: [
                    'Kính: Kính cường lực 10mm - 12mm mài bóng cạnh an toàn',
                    'Trụ & Pad: Inox 304 chống gỉ tuyệt đối',
                    'Tay vịn: Gỗ Căm Xe / Sồi hoặc Inox 304 theo yêu cầu'
                ],
                desc: 'Giúp không gian cầu thang trở nên thoáng rộng, sang trọng, lấy sáng tự nhiên tốt và đảm bảo an toàn cao.'
            },
            {
                id: 'ob-1',
                category: 'op-bep',
                categoryName: 'Kính ốp bếp',
                name: 'Kính màu cường lực ốp bếp sơn chịu nhiệt',
                driveId: '1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb',
                oldPrice: 890000,
                price: 750000,
                discount: 16,
                unit: '₫/md',
                specs: [
                    'Kính: Kính cường lực 8mm tôi nhiệt độ cao chống sốc nhiệt',
                    'Màu sắc: Hơn 30 màu sơn kính bền đẹp không phai màu',
                    'Ưu điểm: Liền mạch không mạch vữa, lau chùi dầu mỡ dễ dàng'
                ],
                desc: 'Thi công đo cắt chuẩn xác từng ổ điện, mang lại căn bếp hiện đại, sạch bóng và thẩm mỹ bền lâu.'
            },
            {
                id: 'pt-1',
                category: 'phong-tam',
                categoryName: 'Phòng tắm kính',
                name: 'Phòng tắm kính cường lực cửa mở quay / cửa lùa',
                driveId: '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH',
                oldPrice: 1550000,
                price: 1320000,
                discount: 15,
                unit: '₫/m²',
                specs: [
                    'Kính: Kính cường lực 10mm an toàn, trong suốt cao cấp',
                    'Phụ kiện: Bản lề, kẹp kính, tay nắm Inox 304 VVP Thái Lan',
                    'Gioăng chắn nước: Chống tràn nước 100%, giữ phòng tắm khô ráo'
                ],
                desc: 'Thiết kế tinh tế ngăn khu vực tắm riêng biệt, sạch sẽ, hiện đại cho căn hộ, khách sạn và nhà phố.'
            }
        ];

        /* =========================================================
           3. DỮ LIỆU 6 DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG
           ========================================================= */
        const projectsData = [
            {
                title: 'DỰ ÁN RESORT MỸ SƠN 4 SAO “MY SON HERITAGE RESORT & SPA”',
                driveId: '1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ',
                location: 'Khu vực Đà Nẵng - Quảng Nam',
                scope: 'Thi công trọn gói hệ thống cửa nhôm Xingfa nhập khẩu, vách kính cường lực và phòng tắm kính cao cấp cho khu nghỉ dưỡng 4 sao.'
            },
            {
                title: 'THI CÔNG DỰ ÁN KHÁCH SẠN GODEN LINE',
                driveId: '1YeuDLiSXUK_Epupq9QiGzM90_EGW3Kfy',
                location: 'TP Đà Nẵng',
                scope: 'Cung cấp và lắp đặt toàn bộ hệ cửa đi, cửa sổ nhôm Xingfa chống ồn ven biển và vách kính mặt dựng cho khách sạn.'
            },
            {
                title: 'DỰ ÁN KHÁCH SẠN RUBY LIGHT',
                driveId: '1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ',
                location: 'TP Đà Nẵng',
                scope: 'Gia công lắp đặt cửa nhôm kính Xingfa, lan can kính cường lực và cabin phòng tắm kính đồng bộ.'
            },
            {
                title: 'THI CÔNG DỰ ÁN RAON ĐÀ NẴNG BEACH HOTEL',
                driveId: '1za_IJpAm850uulT6IuhBsk1THb3LuPuc',
                location: 'Khu vực biển Mỹ Khê, Đà Nẵng',
                scope: 'Thi công hạng mục cửa kính cường lực đại sảnh, cửa đi mở trượt nhôm Xingfa chịu gió biển cấp độ cao.'
            },
            {
                title: 'THI CÔNG DỰ ÁN KHÁCH SẠN JOLIA',
                driveId: '1WRgx-EUIrn8IKFZdpmdv6Z2Xyb7L8_64',
                location: 'TP Đà Nẵng',
                scope: 'Hoàn thiện hệ thống nhôm kính kiến trúc, cửa sổ mở hất chống hắt mưa và vách tắm kính tiêu chuẩn khách sạn.'
            },
            {
                title: 'THI CÔNG DỰ ÁN KHÁCH SẠN SOHO',
                driveId: '1-C5bdt4K-PpLX_KqSN6QAR5ULo1WnNzt',
                location: 'TP Đà Nẵng',
                scope: 'Thi công đồng bộ cửa nhôm Xingfa cao cấp, cửa kính tự động sảnh chính và vách kính cường lực tầng thượng.'
            }
        ];

        /* =========================================================
           4. DỮ LIỆU DANH MỤC BÀI VIẾT / TIN TỨC TRANG CHỦ
           ========================================================= */
        const newsData = [
            {
                title: 'Cửa nhôm Xingfa có phù hợp với khí hậu ven biển Đà Nẵng không?',
                driveId: '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX',
                date: '15/11/2026',
                excerpt: 'Nhôm Xingfa nhập khẩu sơn tĩnh điện ngoài trời chống oxy hóa, kết hợp gioăng kép EPDM giúp chống thấm và chịu gió bão cực tốt tại Đà Nẵng.',
                content: 'Đà Nẵng là thành phố ven biển có độ ẩm cao, hơi muối mặn và thường xuyên chịu ảnh hưởng của gió bão. Thanh profile nhôm Xingfa nhập khẩu tem đỏ có kết cấu khoang trống cùng hai đường gân gia cường chịu lực, bề mặt phủ sơn tĩnh điện công nghệ cao giúp chống ăn mòn hiệu quả, không cong vênh hay rỉ sét theo thời gian.'
            },
            {
                title: 'So sánh cửa nhôm Xingfa và cửa nhựa lõi thép: Nên chọn loại nào?',
                driveId: '1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA',
                date: '10/11/2026',
                excerpt: 'Phân tích chi tiết độ bền, khả năng cách âm, thẩm mỹ và chi phí đầu tư giữa cửa nhôm Xingfa và cửa nhựa lõi thép uPVC.',
                content: 'Cả cửa nhôm Xingfa và cửa nhựa lõi thép đều có ưu điểm cách âm, cách nhiệt tốt. Nếu bạn ưu tiên độ cứng vững, khung thanh mảnh sang trọng, bền màu ngoài trời cho mặt tiền thì Cửa nhôm Xingfa là lựa chọn tối ưu. Trong khi đó, Cửa nhựa lõi thép có chi phí tiết kiệm, phù hợp cho cửa thông phòng và văn phòng.'
            },
            {
                title: 'Cách phân biệt nhôm Xingfa nhập khẩu chính hãng tem đỏ Quảng Đông',
                driveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
                date: '04/11/2026',
                excerpt: 'Hướng dẫn kiểm tra mã QR code, độ dày tiêu chuẩn 1.4mm - 2.0mm, ánh kim mặt cắt nhôm và phụ kiện Kinlong chuẩn hãng.',
                content: 'Để tránh mua phải hàng giả kém chất lượng, khách hàng cần kiểm tra 4 yếu tố: tem đỏ sắc nét có mã QR truy xuất nguồn gốc, bên trong thanh nhôm có lớp mạ crom ánh kim chống oxy hóa, độ dày chuẩn 2.0mm cho cửa đi và 1.4mm cho cửa sổ, cùng công nghệ ép góc thủy lực kín khít.'
            },
            {
                title: 'Cửa nhôm Xingfa có tiết kiệm điện năng và cách âm tốt không?',
                driveId: '11fS_oEeJtnDICQZ77fJlYl6GhHf-GOhA',
                date: '28/10/2026',
                excerpt: 'Tìm hiểu cơ chế cách nhiệt khoang trống kết hợp kính hộp cường lực giúp giảm thất thoát hơi lạnh điều hòa lên đến 30%.',
                content: 'Cấu tạo thanh nhôm đa khoang kết hợp hệ gioăng EPDM đàn hồi cao và kính an toàn/kính hộp tạo thành lớp chắn âm thanh và ngăn truyền nhiệt hiệu quả. Điều này giúp không gian bên trong luôn yên tĩnh, mát mẻ và tiết kiệm đáng kể chi phí điện năng hàng tháng.'
            },
            {
                title: 'Kinh nghiệm lựa chọn phòng tắm kính & cầu thang kính an toàn',
                driveId: '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH',
                date: '20/10/2026',
                excerpt: 'Những lưu ý quan trọng về độ dày kính 10mm - 12mm và phụ kiện Inox 304 chính hãng giúp công trình bền đẹp hàng chục năm.',
                content: 'Đối với phòng tắm kính và cầu thang kính, yếu tố an toàn phải đặt lên hàng đầu. Thành Vinh Window luôn khuyến nghị sử dụng kính cường lực đạt chuẩn 10mm đến 12mm đi kèm phụ kiện Inox 304 chống rỉ sét trong môi trường ẩm ướt, kết hợp thi công chuẩn kỹ thuật để đảm bảo độ vững chắc tuyệt đối.'
            },
            {
                title: 'Bảng giá thi công kính màu ốp bếp cường lực mới nhất tại Đà Nẵng',
                driveId: '1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb',
                date: '12/10/2026',
                excerpt: 'Tổng hợp các gam màu kính ốp bếp phong thủy được ưa chuộng nhất cùng quy trình đo cắt lắp đặt nhanh gọn trong ngày.',
                content: 'Kính ốp bếp cường lực 8mm có độ bóng sáng tự nhiên, chịu nhiệt độ cao gần khu vực bếp nấu và cực kỳ dễ vệ sinh lau chùi. Tại Thành Vinh Window, khách hàng được mang bảng màu thực tế tư vấn tận nhà và lắp đặt trọn gói với mức giá xuất xưởng ưu đãi.'
            }
        ];

        /* =========================================================
           5. RENDER SẢN PHẨM, DỰ ÁN & TIN TỨC
           ========================================================= */
        function formatVND(num) {
            return num.toString().replace(/\B(?=(\d{3})+(?!\d))/g, '.');
        }

        function renderProducts(list) {
            const grid = document.getElementById('productsGrid');
            if (!list.length) {
                grid.innerHTML = `
                    <div class="col-span-full bg-white rounded-xl border border-slate-200 p-8 text-center">
                        <p class="text-sm font-semibold text-slate-600 mb-3">Không tìm thấy sản phẩm phù hợp với từ khóa của bạn.</p>
                        <button type="button" onclick="resetSearch()" class="bg-brand text-white text-xs font-bold px-4 py-2 rounded-lg">Xem tất cả sản phẩm</button>
                    </div>`;
                return;
            }

            grid.innerHTML = list.map(item => `
                <article class="bg-white border border-slate-200 hover:border-brand/60 rounded-xl overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <!-- Ảnh sản phẩm + Nhãn giảm giá % góc trên bên trái -->
                    <div class="relative aspect-[4/3] w-full overflow-hidden bg-slate-100 cursor-pointer" onclick="openProductModal('${item.id}')">
                        <span class="absolute top-2 left-2 z-10 bg-brand-accent text-white text-[11px] sm:text-xs font-extrabold px-2 py-0.5 rounded shadow">
                            -${item.discount}%
                        </span>
                        <img
                            src="${getDriveImgUrl(item.driveId, 700)}"
                            data-drive-id="${item.driveId}"
                            alt="${item.name}"
                            loading="lazy"
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                            onerror="handleDriveImageError(this, '480x360', 'Thanh+Vinh+Window')"
                        >
                    </div>

                    <!-- Thông tin sản phẩm: Tên hiển thị đầy đủ, không cắt chữ, không tràn viền -->
                    <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between gap-2">
                        <div>
                            <p class="text-[10px] sm:text-[11px] font-semibold uppercase text-slate-400 mb-1">${item.categoryName}</p>
                            <h3 onclick="openProductModal('${item.id}')"
                                class="text-[12.5px] sm:text-sm font-bold text-slate-800 hover:text-brand cursor-pointer leading-snug break-words">
                                ${item.name}
                            </h3>
                        </div>

                        <div class="space-y-2 pt-1">
                            <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5">
                                <span class="text-sm sm:text-base font-extrabold text-brand-accent">
                                    ${formatVND(item.price)} ${item.unit}
                                </span>
                                <span class="text-[11px] sm:text-xs text-slate-400 line-through">
                                    ${formatVND(item.oldPrice)} ₫
                                </span>
                            </div>

                            <div class="grid grid-cols-2 gap-1.5 sm:gap-2">
                                <button type="button" onclick="openProductModal('${item.id}')"
                                    class="text-[11px] sm:text-xs font-semibold text-brand bg-brand-light hover:bg-brand hover:text-white py-2 px-1.5 rounded-lg transition text-center">
                                    Xem nhanh
                                </button>
                                <button type="button" onclick="requestQuoteFor('${item.name.replace(/'/g, "\\'")}')"
                                    class="text-[11px] sm:text-xs font-bold text-white bg-brand hover:bg-brand-dark py-2 px-1.5 rounded-lg transition text-center">
                                    Báo giá
                                </button>
                            </div>
                        </div>
                    </div>
                </article>
            `).join('');
        }

        function renderProjects() {
            const grid = document.getElementById('projectsGrid');
            grid.innerHTML = projectsData.map((p, idx) => `
                <article onclick="openProjectModal(${idx})"
                    class="group bg-white border border-slate-200 hover:border-brand rounded-xl overflow-hidden shadow-sm hover:shadow-md transition cursor-pointer flex flex-col">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                        <img
                            src="${getDriveImgUrl(p.driveId, 800)}"
                            data-drive-id="${p.driveId}"
                            alt="${p.title}"
                            loading="lazy"
                            class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
                            onerror="handleDriveImageError(this, '640x400', 'Du+An+Da+Nang')"
                        >
                    </div>
                    <div class="p-3.5 sm:p-4 flex-1 flex flex-col justify-between gap-2">
                        <h3 class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand leading-snug uppercase">
                            ${p.title}
                        </h3>
                        <p class="text-xs text-slate-500 flex items-center justify-between pt-1 border-t border-slate-100">
                            <span><i class="fa-solid fa-location-dot text-brand mr-1"></i>${p.location}</span>
                            <span class="font-semibold text-brand">Chi tiết <i class="fa-solid fa-angle-right"></i></span>
                        </p>
                    </div>
                </article>
            `).join('');
        }

        function renderNews() {
            const grid = document.getElementById('newsGrid');
            grid.innerHTML = newsData.map((n, idx) => `
                <article onclick="openNewsModal(${idx})"
                    class="group bg-white border border-slate-200 hover:border-brand rounded-xl overflow-hidden shadow-sm hover:shadow-md transition cursor-pointer flex flex-col">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                        <img
                            src="${getDriveImgUrl(n.driveId, 700)}"
                            data-drive-id="${n.driveId}"
                            alt="${n.title}"
                            loading="lazy"
                            class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
                            onerror="handleDriveImageError(this, '640x400', 'Tin+Tuc+Thanh+Vinh')"
                        >
                    </div>
                    <div class="p-3.5 sm:p-4 flex-1 flex flex-col justify-between gap-2">
                        <div class="space-y-1.5">
                            <p class="text-[11px] text-slate-400"><i class="fa-regular fa-calendar mr-1"></i>${n.date}</p>
                            <h3 class="text-sm font-bold text-slate-800 group-hover:text-brand leading-snug">
                                ${n.title}
                            </h3>
                            <p class="text-xs text-slate-600 leading-relaxed">
                                ${n.excerpt}
                            </p>
                        </div>
                        <span class="inline-flex items-center gap-1 text-xs font-bold text-brand pt-1">
                            Xem thêm <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </span>
                    </div>
                </article>
            `).join('');
        }

        /* =========================================================
           6. LỌC DANH MỤC & TÌM KIẾM SẢN PHẨM
           ========================================================= */
        function setActiveFilterTab(cat) {
            document.querySelectorAll('.filter-tab').forEach(btn => {
                const isActive = btn.getAttribute('data-cat') === cat;
                btn.className = isActive
                    ? 'filter-tab shrink-0 px-3.5 py-2 rounded-lg text-xs font-bold bg-brand text-white transition whitespace-nowrap'
                    : 'filter-tab shrink-0 px-3.5 py-2 rounded-lg text-xs font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand transition whitespace-nowrap';
            });
        }

        function filterProducts(cat) {
            document.getElementById('searchStatusBanner').classList.add('hidden');
            setActiveFilterTab(cat);
            const filtered = cat === 'all' ? productsData : productsData.filter(p => p.category === cat);
            renderProducts(filtered);
        }

        function filterAndHighlight(cat, keyword) {
            setActiveFilterTab(cat);
            const kw = keyword.toLowerCase();
            const filtered = productsData.filter(p =>
                p.category === cat && p.name.toLowerCase().includes(kw)
            );
            const result = filtered.length ? filtered : productsData.filter(p => p.category === cat);
            renderProducts(result);

            const banner = document.getElementById('searchStatusBanner');
            const text = document.getElementById('searchStatusText');
            text.textContent = `Đang hiển thị danh mục: Cửa nhôm Xingfa (${keyword})`;
            banner.classList.remove('hidden');
        }

        function executeSearch(keyword, cat) {
            const cleanKw = (keyword || '').trim().toLowerCase();
            let result = productsData;
            if (cat && cat !== 'all') {
                result = result.filter(p => p.category === cat);
            }
            if (cleanKw) {
                result = result.filter(p =>
                    p.name.toLowerCase().includes(cleanKw) ||
                    p.categoryName.toLowerCase().includes(cleanKw)
                );
            }
            setActiveFilterTab(cat || 'all');
            renderProducts(result);

            const banner = document.getElementById('searchStatusBanner');
            const text = document.getElementById('searchStatusText');
            text.textContent = cleanKw
                ? `Kết quả tìm kiếm cho "${keyword}" (${result.length} sản phẩm)`
                : `Hiển thị ${result.length} sản phẩm`;
            banner.classList.remove('hidden');

            document.getElementById('san-pham-xingfa').scrollIntoView({ behavior: 'smooth' });
        }

        function handleSearchSubmit(e) {
            e.preventDefault();
            const kw = document.getElementById('searchKeywordInput').value;
            const cat = document.getElementById('searchCategorySelect').value;
            executeSearch(kw, cat);
        }

        function handleMobileSearchSubmit(e) {
            e.preventDefault();
            const kw = document.getElementById('mobileSearchInput').value;
            executeSearch(kw, 'all');
        }

        function resetSearch() {
            document.getElementById('searchKeywordInput').value = '';
            document.getElementById('mobileSearchInput').value = '';
            document.getElementById('searchCategorySelect').value = 'all';
            filterProducts('xingfa');
        }

        /* =========================================================
           7. MODAL CHI TIẾT & ĐĂNG KÝ BÁO GIÁ
           ========================================================= */
        function openProductModal(id) {
            const item = productsData.find(p => p.id === id);
            if (!item) return;

            const body = document.getElementById('detailModalBody');
            body.innerHTML = `
                <div class="grid grid-cols-1 sm:grid-cols-2 gap-5 items-start">
                    <div class="relative rounded-xl overflow-hidden border border-slate-200 bg-slate-100 aspect-[4/3]">
                        <span class="absolute top-2 left-2 bg-brand-accent text-white text-xs font-extrabold px-2.5 py-0.5 rounded shadow">
                            -${item.discount}%
                        </span>
                        <img src="${getDriveImgUrl(item.driveId, 800)}" data-drive-id="${item.driveId}" alt="${item.name}"
                            class="w-full h-full object-cover" onerror="handleDriveImageError(this, '600x450', 'Thanh+Vinh+Window')">
                    </div>
                    <div class="space-y-3">
                        <p class="text-xs font-bold uppercase text-brand">${item.categoryName}</p>
                        <h3 class="text-lg font-extrabold text-slate-900 leading-snug">${item.name}</h3>
                        <div class="flex items-baseline gap-2.5">
                            <span class="text-xl font-extrabold text-brand-accent">${formatVND(item.price)} ${item.unit}</span>
                            <span class="text-sm text-slate-400 line-through">${formatVND(item.oldPrice)} ₫</span>
                        </div>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">${item.desc}</p>
                        <ul class="space-y-1.5 text-xs text-slate-700 bg-slate-50 p-3 rounded-lg border border-slate-200">
                            ${item.specs.map(s => `<li class="flex items-start gap-2"><i class="fa-solid fa-check text-brand mt-0.5"></i><span>${s}</span></li>`).join('')}
                        </ul>
                        <div class="flex flex-wrap gap-2 pt-1">
                            <button type="button" onclick="closeDetailModal(); requestQuoteFor('${item.name.replace(/'/g, "\\'")}')"
                                class="flex-1 bg-brand-accent hover:bg-red-700 text-white text-xs sm:text-sm font-bold py-2.5 px-4 rounded-lg transition">
                                Nhận báo giá mẫu này
                            </button>
                            <a href="tel:0905310041"
                                class="bg-brand hover:bg-brand-dark text-white text-xs sm:text-sm font-bold py-2.5 px-4 rounded-lg transition">
                                <i class="fa-solid fa-phone mr-1"></i>0905.310.041
                            </a>
                        </div>
                    </div>
                </div>`;
            showDetailModal();
        }

        function openProjectModal(index) {
            const p = projectsData[index];
            if (!p) return;

            const body = document.getElementById('detailModalBody');
            body.innerHTML = `
                <div class="space-y-4">
                    <div class="rounded-xl overflow-hidden border border-slate-200 aspect-[16/10] bg-slate-100">
                        <img src="${getDriveImgUrl(p.driveId, 1000)}" data-drive-id="${p.driveId}" alt="${p.title}"
                            class="w-full h-full object-cover" onerror="handleDriveImageError(this, '800x500', 'Du+An+Da+Nang')">
                    </div>
                    <h3 class="text-base sm:text-xl font-extrabold text-brand uppercase">${p.title}</h3>
                    <p class="text-xs sm:text-sm text-slate-600"><strong>Địa điểm:</strong> ${p.location}</p>
                    <p class="text-sm text-slate-700 leading-relaxed">${p.scope}</p>
                    <div class="pt-2 flex flex-wrap gap-2">
                        <button type="button" onclick="closeDetailModal(); requestQuoteFor('Tư vấn thi công tương tự ${p.title.replace(/'/g, "\\'")}')"
                            class="bg-brand hover:bg-brand-dark text-white text-xs sm:text-sm font-bold px-5 py-2.5 rounded-lg transition">
                            Nhận báo giá công trình tương tự
                        </button>
                    </div>
                </div>`;
            showDetailModal();
        }

        function openNewsModal(index) {
            const n = newsData[index];
            if (!n) return;

            const body = document.getElementById('detailModalBody');
            body.innerHTML = `
                <div class="space-y-4">
                    <div class="rounded-xl overflow-hidden border border-slate-200 aspect-[16/9] bg-slate-100">
                        <img src="${getDriveImgUrl(n.driveId, 900)}" data-drive-id="${n.driveId}" alt="${n.title}"
                            class="w-full h-full object-cover" onerror="handleDriveImageError(this, '800x450', 'Tin+Tuc')">
                    </div>
                    <p class="text-xs text-slate-400"><i class="fa-regular fa-calendar mr-1"></i>Ngày đăng: ${n.date} • CÔNG TY TNHH THÀNH VINH WINDOW</p>
                    <h3 class="text-lg sm:text-xl font-extrabold text-brand leading-snug">${n.title}</h3>
                    <p class="text-sm text-slate-700 leading-relaxed">${n.content}</p>
                    <div class="p-3.5 bg-brand-light rounded-lg text-xs sm:text-sm text-brand">
                        Quý khách cần tư vấn kỹ thuật hoặc nhận báo giá lắp đặt tại Đà Nẵng vui lòng liên hệ Hotline/Zalo: <strong>0905.310.041</strong>.
                    </div>
                </div>`;
            showDetailModal();
        }

        function showDetailModal() {
            const modal = document.getElementById('detailModal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeDetailModal() {
            const modal = document.getElementById('detailModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        function requestQuoteFor(productName) {
            const noteEl = document.getElementById('qNote');
            noteEl.value = `Tôi cần nhận báo giá chi tiết cho: ${productName}`;
            document.getElementById('form-bao-gia').scrollIntoView({ behavior: 'smooth' });
            setTimeout(() => document.getElementById('qName').focus(), 450);
        }

        function handleQuoteSubmit(e) {
            e.preventDefault();
            const name = document.getElementById('qName').value.trim();
            const phone = document.getElementById('qPhone').value.trim();
            const category = document.getElementById('qCategory').value;

            const box = document.getElementById('quoteSuccessBox');
            const text = document.getElementById('quoteSuccessText');
            text.textContent = `Cảm ơn ${name}! Thành Vinh Window đã tiếp nhận yêu cầu báo giá "${category}" qua SĐT ${phone} và sẽ liên hệ tư vấn sớm nhất.`;
            box.classList.remove('hidden');

            document.getElementById('quoteForm').reset();
        }

        /* =========================================================
           8. ĐIỀU KHIỂN 2 BANNER TỰ TRƯỢT + HỖ TRỢ VUỐT CẢM ỨNG
           ========================================================= */
        let currentHeroSlide = 0;
        const totalHeroSlides = 2;
        let heroAutoTimer = null;

        function updateHeroSlider() {
            const track = document.getElementById('heroTrack');
            track.style.transform = `translateX(-${currentHeroSlide * 100}%)`;

            document.querySelectorAll('.hero-dot').forEach((dot, idx) => {
                if (idx === currentHeroSlide) {
                    dot.classList.remove('w-2.5', 'bg-white/50');
                    dot.classList.add('w-6', 'bg-white');
                } else {
                    dot.classList.remove('w-6', 'bg-white');
                    dot.classList.add('w-2.5', 'bg-white/50');
                }
            });
        }

        function goToHeroSlide(index) {
            currentHeroSlide = (index + totalHeroSlides) % totalHeroSlides;
            updateHeroSlider();
            restartHeroAutoSlide();
        }

        function restartHeroAutoSlide() {
            if (heroAutoTimer) clearInterval(heroAutoTimer);
            heroAutoTimer = setInterval(() => {
                currentHeroSlide = (currentHeroSlide + 1) % totalHeroSlides;
                updateHeroSlider();
            }, 5000);
        }

        /* =========================================================
           9. ĐIỀU KHIỂN MENU MOBILE
           ========================================================= */
        function openMobileMenu() {
            document.getElementById('mobileMenuOverlay').classList.remove('hidden');
            document.getElementById('mobileMenuDrawer').classList.remove('-translate-x-full');
        }

        function closeMobileMenu() {
            document.getElementById('mobileMenuOverlay').classList.add('hidden');
            document.getElementById('mobileMenuDrawer').classList.add('-translate-x-full');
        }

        function toggleMobileSubmenu(id, btn) {
            const panel = document.getElementById(id);
            const icon = btn.querySelector('i');
            panel.classList.toggle('hidden');
            if (icon) icon.classList.toggle('rotate-180');
        }

        /* =========================================================
           10. KHỞI TẠO KHI TẢI TRANG
           ========================================================= */
        window.addEventListener('DOMContentLoaded', () => {
            // Render mặc định 6 sản phẩm Cửa nhôm Xingfa, 6 dự án & 6 bài viết
            filterProducts('xingfa');
            renderProjects();
            renderNews();

            // Khởi chạy Banner tự trượt
            updateHeroSlider();
            restartHeroAutoSlide();

            document.getElementById('heroPrevBtn').addEventListener('click', () => goToHeroSlide(currentHeroSlide - 1));
            document.getElementById('heroNextBtn').addEventListener('click', () => goToHeroSlide(currentHeroSlide + 1));

            // Dừng tự trượt khi rê chuột vào banner trên máy tính
            const sliderEl = document.getElementById('heroSlider');
            sliderEl.addEventListener('mouseenter', () => { if (heroAutoTimer) clearInterval(heroAutoTimer); });
            sliderEl.addEventListener('mouseleave', restartHeroAutoSlide);

            // Hỗ trợ vuốt ngang trên điện thoại cho Banner
            let touchStartX = 0;
            sliderEl.addEventListener('touchstart', (e) => {
                touchStartX = e.changedTouches[0].screenX;
            }, { passive: true });
            sliderEl.addEventListener('touchend', (e) => {
                const diff = e.changedTouches[0].screenX - touchStartX;
                if (Math.abs(diff) > 45) {
                    if (diff < 0) goToHeroSlide(currentHeroSlide + 1);
                    else goToHeroSlide(currentHeroSlide - 1);
                }
            }, { passive: true });

            // Gắn sự kiện mở/đóng Menu Mobile & Modal
            document.getElementById('openMobileMenuBtn').addEventListener('click', openMobileMenu);
            document.getElementById('closeMobileMenuBtn').addEventListener('click', closeMobileMenu);
            document.getElementById('mobileMenuOverlay').addEventListener('click', closeMobileMenu);

            document.getElementById('detailModal').addEventListener('click', (e) => {
                if (e.target.id === 'detailModal') closeDetailModal();
            });
        });
    </script>
</body>
</html>
