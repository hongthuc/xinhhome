<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>XINH HOME - Thiết Kế & Thi Công Nội Thất, Tủ Bếp Trọn Gói Đà Nẵng | xinhhome.com</title>
    <meta name="description" content="CÔNG TY TNHH XINH HOME INTERIOR (xinhhome.com) - Chuyên thiết kế, thi công nội thất trọn gói, tủ bếp cao cấp và cung cấp thiết bị bếp chính hãng tại 51 Trần Đại Nghĩa, Ngũ Hành Sơn, Đà Nẵng. Hotline: 0905.060.839">

    <!-- Thumbnail là ảnh Logo trang web khi gửi link chia sẻ (Open Graph / Zalo / Facebook) -->
    <meta property="og:type" content="website">
    <meta property="og:site_name" content="XINH HOME - xinhhome.com">
    <meta property="og:url" content="https://xinhhome.com">
    <meta property="og:title" content="XINH HOME - Thiết Kế & Thi Công Nội Thất, Tủ Bếp Trọn Gói Đà Nẵng">
    <meta property="og:description" content="Giải pháp thiết kế thi công nội thất chung cư, nhà phố, biệt thự, tủ bếp & thiết bị bếp trọn gói giá gốc tại xưởng. Đ/c: 51 Trần Đại Nghĩa, Ngũ Hành Sơn, Đà Nẵng - ĐT: 0905.060.839">
    <meta property="og:image" content="https://drive.google.com/thumbnail?id=1a-o52YR4IejHhCbw3tlOOED55z1Iyp9K&sz=w1200">
    <meta property="og:image:alt" content="Logo XINH HOME - xinhhome.com">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=1a-o52YR4IejHhCbw3tlOOED55z1Iyp9K&sz=w1200">
    <link rel="icon" href="https://drive.google.com/thumbnail?id=1a-o52YR4IejHhCbw3tlOOED55z1Iyp9K&sz=w200">

    <!-- Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            light: '#FDFBF9',
                            cream: '#F5EFE8',
                            gold: '#B68349',
                            primary: '#8C5A2B',
                            dark: '#5E3A18',
                            charcoal: '#22252A'
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Chống tràn viền và chống lệch phải tuyệt đối trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100%;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
            font-family: 'Inter', sans-serif;
            background-color: #FAF8F5;
            color: #22252A;
            scroll-behavior: smooth;
        }

        /* Khung giao diện chuẩn Flatsome: 95% kích thước màn hình trên máy tính */
        .flatsome-container {
            width: 100%;
            max-width: 100%;
            padding-left: 12px;
            padding-right: 12px;
            margin-left: auto;
            margin-right: auto;
        }
        @media (min-width: 1024px) {
            .flatsome-container {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Tối ưu tên danh mục: chữ nhỏ gọn, viết liền trên 1 hàng, tuyệt đối không xuống dòng bên trong tên danh mục */
        .nav-cat-item {
            white-space: nowrap;
            display: inline-flex;
            align-items: center;
            font-size: 12.5px;
            font-weight: 600;
            line-height: 1.2;
            padding: 7px 10px;
            border-radius: 6px;
            transition: all 0.2s ease;
            flex-shrink: 0;
        }
        @media (min-width: 1280px) {
            .nav-cat-item {
                font-size: 13px;
                padding: 8px 12px;
            }
        }

        /* Danh mục lọc ở trang chủ: chữ nhỏ gọn, viết liền không tự ngắt chữ, có thể nằm trên 1 hàng hoặc xuống hàng 2 nguyên cụm */
        .cat-pill {
            white-space: nowrap;
            display: inline-flex;
            align-items: center;
            justify-content: center;
            font-size: 12px;
            font-weight: 600;
            padding: 6px 12px;
            border-radius: 6px;
            transition: all 0.2s ease;
            cursor: pointer;
            border: 1px solid #E5DEC9;
            background: #FFFFFF;
            color: #374151;
        }
        .cat-pill:hover, .cat-pill.active {
            background: #8C5A2B;
            color: #FFFFFF;
            border-color: #8C5A2B;
        }

        /* Tiêu đề Section chuẩn Flatsome UX Builder (Section Title Center) */
        .section-title-container {
            margin-bottom: 1.25rem;
        }
        .section-title-main {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 12px;
            text-align: center;
        }
        .section-title-main::before,
        .section-title-main::after {
            content: "";
            flex: 1;
            height: 2px;
            background-color: #E5DEC9;
            max-width: 140px;
        }

        /* Tên sản phẩm: hiển thị đầy đủ, tự xuống dòng mượt, không bị cắt chữ hay tràn ra ngoài */
        .product-title-full {
            white-space: normal;
            word-wrap: break-word;
            overflow-wrap: break-word;
            word-break: break-word;
            line-height: 1.4;
            display: block;
            width: 100%;
        }

        /* Banner 2 ảnh kích thước bằng nhau tuyệt đối */
        .banner-wrapper {
            position: relative;
            width: 100%;
            height: 260px;
            overflow: hidden;
            border-radius: 10px;
            background-color: #22252A;
        }
        @media (min-width: 640px) {
            .banner-wrapper {
                height: 340px;
            }
        }
        @media (min-width: 1024px) {
            .banner-wrapper {
                height: 430px;
            }
        }
        .banner-slide {
            position: absolute;
            inset: 0;
            width: 100%;
            height: 100%;
            opacity: 0;
            visibility: hidden;
            transition: opacity 0.7s ease-in-out, visibility 0.7s ease-in-out;
        }
        .banner-slide.active {
            opacity: 1;
            visibility: visible;
            z-index: 10;
        }

        /* Hiệu ứng rung nhẹ cho nút Hotline/Zalo nổi */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(140, 90, 43, 0.7); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(140, 90, 43, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(140, 90, 43, 0); }
        }
        .pulse-btn {
            animation: pulse-ring 2s infinite;
        }
    </style>
</head>
<body class="antialiased selection:bg-brand-primary selection:text-white">

    <!-- ==========================================
         TOP BAR THÔNG TIN (Đơn giản, chuẩn Flatsome)
         ========================================== -->
    <div class="bg-brand-charcoal text-gray-200 text-xs py-2 border-b border-stone-700">
        <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-3 sm:gap-5 flex-wrap">
                <span class="inline-flex items-center gap-1.5 font-medium text-amber-400">
                    <i class="fa-solid fa-building"></i>
                    <span>XINH HOME INTERIOR - xinhhome.com</span>
                </span>
                <span class="hidden md:inline-flex items-center gap-1.5 text-gray-300">
                    <i class="fa-solid fa-location-dot text-amber-400"></i>
                    <span>51 Trần Đại Nghĩa, Ngũ Hành Sơn, Đà Nẵng</span>
                </span>
            </div>
            <div class="flex items-center gap-3 sm:gap-4 text-gray-300">
                <span class="inline-flex items-center gap-1">
                    <i class="fa-regular fa-clock text-amber-400"></i>
                    <span>7:30 - 17:30 (T2 - T7)</span>
                </span>
                <a href="https://www.facebook.com/profile.php?id=61578493040326" target="_blank" rel="noopener noreferrer" class="hover:text-amber-400 transition-colors inline-flex items-center gap-1">
                    <i class="fa-brands fa-facebook"></i>
                    <span>Fanpage</span>
                </a>
            </div>
        </div>
    </div>

    <!-- ==========================================
         HEADER CHÍNH (Logo nhỏ gọn, Danh mục trên 1 hàng, KHÔNG để nút gọi ngay trên Header để tránh tràn viền)
         ========================================== -->
    <header class="bg-white sticky top-0 z-40 shadow-sm border-b border-stone-200">
        <div class="flatsome-container">
            <div class="flex items-center justify-between py-2.5 gap-2">
                <!-- Logo chỉnh gọn nhỏ lại -->
                <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group">
                    <img 
                        src="https://drive.google.com/thumbnail?id=1a-o52YR4IejHhCbw3tlOOED55z1Iyp9K&sz=w400" 
                        onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1a-o52YR4IejHhCbw3tlOOED55z1Iyp9K';" 
                        alt="Logo XINH HOME" 
                        class="h-9 sm:h-10 w-auto object-contain rounded border border-stone-200 p-0.5 bg-white"
                    >
                    <div class="leading-tight">
                        <span class="block text-sm sm:text-base font-extrabold tracking-tight text-brand-primary">XINH HOME</span>
                        <span class="block text-[10px] sm:text-[11px] font-medium text-stone-500">xinhhome.com</span>
                    </div>
                </a>

                <!-- Menu Danh Mục Máy Tính: Chữ nhỏ gọn, viết liền trên 1 hàng, không xuống dòng chữ -->
                <nav class="hidden lg:flex items-center justify-center flex-wrap gap-x-0.5 xl:gap-x-1">
                    <a href="#trang-chu" class="nav-cat-item text-brand-primary bg-amber-50/80 hover:bg-brand-primary hover:text-white">Trang chủ</a>
                    <a href="#gioi-thieu" class="nav-cat-item text-stone-700 hover:bg-brand-primary hover:text-white">Giới thiệu</a>
                    <a href="#thi-cong-noi-that" class="nav-cat-item text-stone-700 hover:bg-brand-primary hover:text-white">Thi công nội thất</a>
                    <a href="#thiet-ke-noi-that" class="nav-cat-item text-stone-700 hover:bg-brand-primary hover:text-white">Thiết kế nội thất</a>
                    <a href="#tu-bep-thiet-bi" class="nav-cat-item text-stone-700 hover:bg-brand-primary hover:text-white">Tủ bếp & Thiết bị bếp</a>
                    <a href="#du-an-da-nang" class="nav-cat-item text-stone-700 hover:bg-brand-primary hover:text-white">Dự án Đà Nẵng</a>
                    <a href="#doi-tac" class="nav-cat-item text-stone-700 hover:bg-brand-primary hover:text-white">Đối tác</a>
                    <a href="#tin-tuc" class="nav-cat-item text-stone-700 hover:bg-brand-primary hover:text-white">Bài viết</a>
                    <a href="#bao-gia-lien-he" class="nav-cat-item text-stone-700 hover:bg-brand-primary hover:text-white">Báo giá & Liên hệ</a>
                </nav>

                <!-- Nút mở Menu trên Điện Thoại (Không để nút gọi ngay để tránh tràn viền) -->
                <button id="mobile-menu-btn" type="button" aria-label="Mở danh mục" class="lg:hidden inline-flex items-center justify-center p-2 rounded-lg text-stone-700 hover:bg-stone-100 border border-stone-200">
                    <i class="fa-solid fa-bars text-base"></i>
                    <span class="ml-1.5 text-xs font-semibold">Danh mục</span>
                </button>
            </div>

            <!-- Thanh Danh Mục Phụ Máy Tính (Lấy danh mục từ web mẫu noithattvt.vn - nằm gọn trên 1 hàng, chữ nhỏ gọn không xuống dòng tên danh mục) -->
            <div class="hidden lg:flex items-center justify-center gap-1.5 py-1.5 border-t border-stone-100 text-xs">
                <button onclick="filterServiceCategory('all')" class="nav-cat-item text-[11.5px] py-1 px-2.5 text-stone-600 hover:text-brand-primary hover:bg-stone-100">
                    <i class="fa-solid fa-layer-group mr-1 text-brand-gold"></i>Tất cả hạng mục
                </button>
                <button onclick="filterServiceCategory('chung-cu')" class="nav-cat-item text-[11.5px] py-1 px-2.5 text-stone-600 hover:text-brand-primary hover:bg-stone-100">
                    <i class="fa-solid fa-building mr-1 text-brand-gold"></i>Nội thất chung cư
                </button>
                <button onclick="filterServiceCategory('nha-pho')" class="nav-cat-item text-[11.5px] py-1 px-2.5 text-stone-600 hover:text-brand-primary hover:bg-stone-100">
                    <i class="fa-solid fa-house-chimney mr-1 text-brand-gold"></i>Nội thất nhà phố
                </button>
                <button onclick="filterServiceCategory('biet-thu')" class="nav-cat-item text-[11.5px] py-1 px-2.5 text-stone-600 hover:text-brand-primary hover:bg-stone-100">
                    <i class="fa-solid fa-crown mr-1 text-brand-gold"></i>Nội thất biệt thự - Villa
                </button>
                <button onclick="filterServiceCategory('tu-bep')" class="nav-cat-item text-[11.5px] py-1 px-2.5 text-stone-600 hover:text-brand-primary hover:bg-stone-100">
                    <i class="fa-solid fa-kitchen-set mr-1 text-brand-gold"></i>Tủ bếp & Phụ kiện bếp
                </button>
                <button onclick="filterServiceCategory('van-phong')" class="nav-cat-item text-[11.5px] py-1 px-2.5 text-stone-600 hover:text-brand-primary hover:bg-stone-100">
                    <i class="fa-solid fa-briefcase mr-1 text-brand-gold"></i>Nội thất văn phòng
                </button>
                <button onclick="filterServiceCategory('cua-hang')" class="nav-cat-item text-[11.5px] py-1 px-2.5 text-stone-600 hover:text-brand-primary hover:bg-stone-100">
                    <i class="fa-solid fa-store mr-1 text-brand-gold"></i>Nội thất cửa hàng
                </button>
            </div>
        </div>

        <!-- Menu Điện Thoại (Gọn đẹp, chia ô dễ bấm) -->
        <div id="mobile-menu-panel" class="hidden lg:hidden bg-white border-t border-stone-200 px-3 py-3 shadow-inner">
            <div class="grid grid-cols-2 sm:grid-cols-3 gap-2">
                <a href="#trang-chu" class="mobile-nav-link px-3 py-2 rounded-md bg-stone-50 hover:bg-brand-primary hover:text-white text-xs font-semibold text-stone-800 whitespace-nowrap">
                    <i class="fa-solid fa-house mr-1.5 text-brand-gold"></i>Trang chủ
                </a>
                <a href="#gioi-thieu" class="mobile-nav-link px-3 py-2 rounded-md bg-stone-50 hover:bg-brand-primary hover:text-white text-xs font-semibold text-stone-800 whitespace-nowrap">
                    <i class="fa-solid fa-circle-info mr-1.5 text-brand-gold"></i>Giới thiệu
                </a>
                <a href="#thi-cong-noi-that" class="mobile-nav-link px-3 py-2 rounded-md bg-stone-50 hover:bg-brand-primary hover:text-white text-xs font-semibold text-stone-800 whitespace-nowrap">
                    <i class="fa-solid fa-hammer mr-1.5 text-brand-gold"></i>Thi công nội thất
                </a>
                <a href="#thiet-ke-noi-that" class="mobile-nav-link px-3 py-2 rounded-md bg-stone-50 hover:bg-brand-primary hover:text-white text-xs font-semibold text-stone-800 whitespace-nowrap">
                    <i class="fa-solid fa-compass-drafting mr-1.5 text-brand-gold"></i>Thiết kế nội thất
                </a>
                <a href="#tu-bep-thiet-bi" class="mobile-nav-link px-3 py-2 rounded-md bg-stone-50 hover:bg-brand-primary hover:text-white text-xs font-semibold text-stone-800 whitespace-nowrap">
                    <i class="fa-solid fa-kitchen-set mr-1.5 text-brand-gold"></i>Tủ bếp & Thiết bị
                </a>
                <a href="#du-an-da-nang" class="mobile-nav-link px-3 py-2 rounded-md bg-stone-50 hover:bg-brand-primary hover:text-white text-xs font-semibold text-stone-800 whitespace-nowrap">
                    <i class="fa-solid fa-city mr-1.5 text-brand-gold"></i>Dự án Đà Nẵng
                </a>
                <a href="#doi-tac" class="mobile-nav-link px-3 py-2 rounded-md bg-stone-50 hover:bg-brand-primary hover:text-white text-xs font-semibold text-stone-800 whitespace-nowrap">
                    <i class="fa-solid fa-handshake mr-1.5 text-brand-gold"></i>Đối tác
                </a>
                <a href="#tin-tuc" class="mobile-nav-link px-3 py-2 rounded-md bg-stone-50 hover:bg-brand-primary hover:text-white text-xs font-semibold text-stone-800 whitespace-nowrap">
                    <i class="fa-solid fa-newspaper mr-1.5 text-brand-gold"></i>Bài viết
                </a>
                <a href="#bao-gia-lien-he" class="mobile-nav-link col-span-2 sm:col-span-1 px-3 py-2 rounded-md bg-brand-primary text-white text-xs font-semibold text-center whitespace-nowrap">
                    <i class="fa-solid fa-file-signature mr-1.5"></i>Yêu cầu báo giá
                </a>
            </div>
        </div>
    </header>

    <!-- ==========================================
         SECTION 1: 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU
         (Hình ảnh & chữ nằm trọn trong banner, chữ cách xa viền, không bị thiếu chữ trên điện thoại & máy tính)
         ========================================== -->
    <section id="trang-chu" class="py-3 sm:py-5">
        <div class="flatsome-container">
            <div class="banner-wrapper shadow-md">
                <!-- SLIDE 1 -->
                <div class="banner-slide active" data-slide="0">
                    <img 
                        src="https://drive.google.com/thumbnail?id=1wfdSeT3hpDvWut50-hNxVHFS6O5hCZ23&sz=w1600" 
                        onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1wfdSeT3hpDvWut50-hNxVHFS6O5hCZ23';"
                        alt="Banner 1 - Thiết kế thi công nội thất trọn gói Xinh Home Đà Nẵng" 
                        class="w-full h-full object-cover object-center"
                    >
                    <!-- Lớp phủ tối giúp chữ nổi bật -->
                    <div class="absolute inset-0 bg-gradient-to-r from-black/80 via-black/60 to-black/35"></div>
                    <!-- Nội dung chữ cách xa viền ảnh banner (px-8 sm:px-14 md:px-20 py-6 sm:py-12) -->
                    <div class="absolute inset-0 flex items-center justify-start px-8 sm:px-14 md:px-20 py-6 sm:py-10">
                        <div class="max-w-xl text-white space-y-2 sm:space-y-3">
                            <p class="text-[11px] sm:text-xs md:text-sm uppercase tracking-widest text-amber-300 font-semibold">
                                NỘI THẤT & THIẾT BỊ BẾP XINH HOME - XINHHOME.COM
                            </p>
                            <h1 class="text-base sm:text-2xl md:text-4xl font-extrabold leading-snug sm:leading-tight text-white">
                                Thiết Kế & Thi Công Nội Thất Trọn Gói Tại Đà Nẵng
                            </h1>
                            <p class="text-xs sm:text-sm md:text-base text-gray-200 leading-relaxed">
                                Giải pháp không gian đồng bộ cho Căn hộ, Nhà phố, Biệt thự & Văn phòng. Sản xuất trực tiếp giá tận xưởng – Cam kết chuẩn bản vẽ 3D.
                            </p>
                            <div class="pt-1 sm:pt-2 flex flex-wrap items-center gap-2.5">
                                <a href="#bao-gia-lien-he" class="px-3.5 py-2 sm:px-5 sm:py-2.5 rounded-lg bg-brand-primary hover:bg-brand-dark text-white font-semibold text-xs sm:text-sm transition shadow">
                                    Nhận Báo Giá Tại Xưởng
                                </a>
                                <a href="#du-an-da-nang" class="px-3.5 py-2 sm:px-5 sm:py-2.5 rounded-lg bg-white/15 hover:bg-white/25 backdrop-blur text-white font-semibold text-xs sm:text-sm border border-white/30 transition">
                                    Xem Công Trình Thực Tế
                                </a>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- SLIDE 2 (Kích thước bằng nhau 100% với Slide 1) -->
                <div class="banner-slide" data-slide="1">
                    <img 
                        src="https://drive.google.com/thumbnail?id=18qvT6MOXQMH0UMaNBSrESDQOBTg4f-CC&sz=w1600" 
                        onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/18qvT6MOXQMH0UMaNBSrESDQOBTg4f-CC';"
                        alt="Banner 2 - Thi công tủ bếp và thiết bị bếp Xinh Home 51 Trần Đại Nghĩa" 
                        class="w-full h-full object-cover object-center"
                    >
                    <div class="absolute inset-0 bg-gradient-to-r from-black/80 via-black/60 to-black/35"></div>
                    <!-- Nội dung chữ cách xa viền ảnh banner -->
                    <div class="absolute inset-0 flex items-center justify-start px-8 sm:px-14 md:px-20 py-6 sm:py-10">
                        <div class="max-w-xl text-white space-y-2 sm:space-y-3">
                            <p class="text-[11px] sm:text-xs md:text-sm uppercase tracking-widest text-amber-300 font-semibold">
                                CHUYÊN GIA TỦ BẾP & THIẾT BỊ BẾP ĐÀ NẴNG
                            </p>
                            <h2 class="text-base sm:text-2xl md:text-4xl font-extrabold leading-snug sm:leading-tight text-white">
                                Thi Công Tủ Bếp Cao Cấp & Phụ Kiện Thông Minh
                            </h2>
                            <p class="text-xs sm:text-sm md:text-base text-gray-200 leading-relaxed">
                                Tủ bếp MDF lõi xanh An Cường, Acrylic bóng gương, Nhựa Picomat & Cánh kính. Showroom: 51 Trần Đại Nghĩa, Ngũ Hành Sơn, Đà Nẵng.
                            </p>
                            <div class="pt-1 sm:pt-2 flex flex-wrap items-center gap-2.5">
                                <a href="#tu-bep-thiet-bi" class="px-3.5 py-2 sm:px-5 sm:py-2.5 rounded-lg bg-brand-primary hover:bg-brand-dark text-white font-semibold text-xs sm:text-sm transition shadow">
                                    Khám Phá Mẫu Tủ Bếp
                                </a>
                                <a href="tel:0905060839" class="px-3.5 py-2 sm:px-5 sm:py-2.5 rounded-lg bg-white/15 hover:bg-white/25 backdrop-blur text-white font-semibold text-xs sm:text-sm border border-white/30 transition">
                                    Tư Vấn: 0905.060.839
                                </a>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng trái/phải nằm gọn trong banner -->
                <button onclick="prevBanner()" aria-label="Slide trước" class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/40 hover:bg-brand-primary text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
                </button>
                <button onclick="nextBanner()" aria-label="Slide tiếp theo" class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/40 hover:bg-brand-primary text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
                </button>

                <!-- Chấm chỉ báo Slide -->
                <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button onclick="goToBanner(0)" id="dot-0" class="w-6 h-2 rounded-full bg-amber-400 transition-all"></button>
                    <button onclick="goToBanner(1)" id="dot-1" class="w-2.5 h-2 rounded-full bg-white/60 transition-all"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         SECTION 2: CAM KẾT DỊCH VỤ & THÀNH TỰU (Giống cấu trúc mẫu noithattvt.vn)
         ========================================== -->
    <section id="gioi-thieu" class="py-5 sm:py-7">
        <div class="flatsome-container">
            <!-- 4 ô cam kết chuẩn Flatsome Icon Box -->
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-4 mb-6">
                <div class="bg-white p-3.5 sm:p-4 rounded-xl border border-stone-200 shadow-sm flex items-start gap-3">
                    <div class="w-10 h-10 rounded-lg bg-brand-cream text-brand-primary flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-compass-drafting text-lg"></i>
                    </div>
                    <div>
                        <h3 class="text-xs sm:text-sm font-bold text-stone-800">MIỄN PHÍ KHẢO SÁT & 3D</h3>
                        <p class="text-[11px] sm:text-xs text-stone-600 mt-0.5">Đo đạc tận nơi, miễn phí 100% thiết kế 2D & 3D khi thi công trọn gói.</p>
                    </div>
                </div>
                <div class="bg-white p-3.5 sm:p-4 rounded-xl border border-stone-200 shadow-sm flex items-start gap-3">
                    <div class="w-10 h-10 rounded-lg bg-brand-cream text-brand-primary flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-industry text-lg"></i>
                    </div>
                    <div>
                        <h3 class="text-xs sm:text-sm font-bold text-stone-800">GIÁ GỐC TẬN XƯỞNG</h3>
                        <p class="text-[11px] sm:text-xs text-stone-600 mt-0.5">Gia công CNC hiện đại trực tiếp, tối ưu chi phí không qua trung gian.</p>
                    </div>
                </div>
                <div class="bg-white p-3.5 sm:p-4 rounded-xl border border-stone-200 shadow-sm flex items-start gap-3">
                    <div class="w-10 h-10 rounded-lg bg-brand-cream text-brand-primary flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-medal text-lg"></i>
                    </div>
                    <div>
                        <h3 class="text-xs sm:text-sm font-bold text-stone-800">VẬT LIỆU CHÍNH HÃNG</h3>
                        <p class="text-[11px] sm:text-xs text-stone-600 mt-0.5">Cam kết gỗ MDF chống ẩm An Cường, nhựa Picomat, phụ kiện inox 304.</p>
                    </div>
                </div>
                <div class="bg-white p-3.5 sm:p-4 rounded-xl border border-stone-200 shadow-sm flex items-start gap-3">
                    <div class="w-10 h-10 rounded-lg bg-brand-cream text-brand-primary flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-shield-halved text-lg"></i>
                    </div>
                    <div>
                        <h3 class="text-xs sm:text-sm font-bold text-stone-800">BẢO HÀNH CHU ĐÁO</h3>
                        <p class="text-[11px] sm:text-xs text-stone-600 mt-0.5">Hợp đồng minh bạch, không phát sinh chi phí, bảo hành & bảo trì dài hạn.</p>
                    </div>
                </div>
            </div>

            <!-- Giới thiệu XINH HOME theo bố cục 2 cột Flatsome -->
            <div class="bg-white rounded-xl border border-stone-200 p-4 sm:p-6 shadow-sm">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-center">
                    <div class="lg:col-span-7 space-y-3">
                        <p class="text-xs font-bold uppercase tracking-wider text-brand-primary">VỀ CHÚNG TÔI — CÔNG TY TNHH XINH HOME INTERIOR</p>
                        <h2 class="text-lg sm:text-2xl font-extrabold text-stone-900">
                            Đơn Vị Thiết Kế & Thi Công Nội Thất – Tủ Bếp Uy Tín Tại Đà Nẵng
                        </h2>
                        <p class="text-xs sm:text-sm text-stone-600 leading-relaxed">
                            Tọa lạc tại <strong>51 Trần Đại Nghĩa, Quận Ngũ Hành Sơn, TP. Đà Nẵng</strong>, <strong>XINH HOME (xinhhome.com)</strong> chuyên tư vấn, thiết kế và thi công nội thất trọn gói cho căn hộ chung cư, nhà phố, biệt thự, văn phòng cùng giải pháp <strong>Tủ bếp & Thiết bị nhà bếp đồng bộ 2 trong 1</strong>.
                        </p>
                        <p class="text-xs sm:text-sm text-stone-600 leading-relaxed">
                            Thế mạnh cốt lõi của XINH HOME là khả năng “đo ni đóng giày” linh hoạt theo ngân sách của từng gia chủ, tận dụng tối đa diện tích với hệ tủ kịch trần, hóa giải góc chết thông minh và cam kết đồng nhất giữa bản vẽ phối cảnh 3D với thực tế thi công.
                        </p>
                        <div class="grid grid-cols-3 gap-2 pt-2 border-t border-stone-100 text-center">
                            <div class="p-2 rounded-lg bg-brand-light">
                                <span class="block text-base sm:text-xl font-extrabold text-brand-primary">1000m²</span>
                                <span class="text-[11px] text-stone-600">Hệ thống xưởng & Showroom</span>
                            </div>
                            <div class="p-2 rounded-lg bg-brand-light">
                                <span class="block text-base sm:text-xl font-extrabold text-brand-primary">350+</span>
                                <span class="text-[11px] text-stone-600">Công trình bàn giao tại ĐN</span>
                            </div>
                            <div class="p-2 rounded-lg bg-brand-light">
                                <span class="block text-base sm:text-xl font-extrabold text-brand-primary">5.0 ★</span>
                                <span class="text-[11px] text-stone-600">Đánh giá hài lòng Google Maps</span>
                            </div>
                        </div>
                    </div>
                    <div class="lg:col-span-5 grid grid-cols-2 gap-2.5">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1rqvNo5_Ie-OCQrzkL1azMr_LqRK2cZgd&sz=w800" 
                            onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1rqvNo5_Ie-OCQrzkL1azMr_LqRK2cZgd';"
                            alt="Không gian nội thất thực tế Xinh Home 1" 
                            class="w-full h-40 sm:h-48 object-cover rounded-lg border border-stone-200 cursor-pointer"
                            onclick="openImageModal(this.src, 'Thi Công Nội Thất Trọn Gói XINH HOME Đà Nẵng')"
                        >
                        <img 
                            src="https://drive.google.com/thumbnail?id=1JhhcEEaaXtyMjrTWf5Zk-djWl00iUIjo&sz=w800" 
                            onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1JhhcEEaaXtyMjrTWf5Zk-djWl00iUIjo';"
                            alt="Không gian nội thất thực tế Xinh Home 2" 
                            class="w-full h-40 sm:h-48 object-cover rounded-lg border border-stone-200 cursor-pointer"
                            onclick="openImageModal(this.src, 'Thi Công Tủ Bếp & Phòng Khách XINH HOME Đà Nẵng')"
                        >
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         SECTION 3: DANH MỤC SẢN PHẨM & HẠNG MỤC THI CÔNG NỘI THẤT (Lấy từ web mẫu noithattvt.vn + 11 ảnh thực tế Drive)
         - Điện thoại: chia 2 cột (grid-cols-2)
         - Tên sản phẩm: không bị tràn hoặc thiếu chữ
         - Không để các nhãn dán ở trang chủ
         ========================================== -->
    <section id="thi-cong-noi-that" class="py-5 sm:py-7">
        <div class="flatsome-container">
            <div class="section-title-container">
                <h2 class="section-title-main text-base sm:text-xl font-extrabold uppercase tracking-wide text-stone-800">
                    <span>DANH MỤC SẢN PHẨM & THI CÔNG NỘI THẤT</span>
                </h2>
                <p class="text-center text-xs sm:text-sm text-stone-500 mt-1">
                    Hình ảnh thực tế sản xuất và lắp đặt hoàn thiện bởi đội ngũ XINH HOME Đà Nẵng
                </p>
            </div>

            <!-- Thanh danh mục lọc ở trang chủ: chữ nhỏ gọn, viết liền trên 1 hàng hoặc xuống hàng 2 nguyên cụm, không bao giờ ngắt dòng tên danh mục -->
            <div class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-5">
                <button onclick="filterServiceCategory('all')" data-cat-btn="all" class="cat-pill active">Tất cả sản phẩm</button>
                <button onclick="filterServiceCategory('tu-bep')" data-cat-btn="tu-bep" class="cat-pill">Tủ bếp & Phòng bếp</button>
                <button onclick="filterServiceCategory('chung-cu')" data-cat-btn="chung-cu" class="cat-pill">Thi công nội thất chung cư</button>
                <button onclick="filterServiceCategory('nha-pho')" data-cat-btn="nha-pho" class="cat-pill">Thi công nội thất nhà phố</button>
                <button onclick="filterServiceCategory('biet-thu')" data-cat-btn="biet-thu" class="cat-pill">Thi công nội thất biệt thự, villa</button>
                <button onclick="filterServiceCategory('van-phong')" data-cat-btn="van-phong" class="cat-pill">Thi công nội thất văn phòng</button>
                <button onclick="filterServiceCategory('cua-hang')" data-cat-btn="cua-hang" class="cat-pill">Thi công nội thất cửa hàng</button>
            </div>

            <!-- Lưới sản phẩm: 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4), KHÔNG nhãn dán -->
            <div id="product-grid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4">
                <!-- Sản phẩm 1 (File Drive 1) -->
                <div class="product-card bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="tu-bep chung-cu">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100 cursor-pointer" onclick="openImageModal('https://drive.google.com/thumbnail?id=1wfdSeT3hpDvWut50-hNxVHFS6O5hCZ23&sz=w1200', 'Thi Công Tủ Bếp Chữ L Kịch Trần Phủ Acrylic Bóng Gương Hiện Đại')">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1wfdSeT3hpDvWut50-hNxVHFS6O5hCZ23&sz=w800" 
                            onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1wfdSeT3hpDvWut50-hNxVHFS6O5hCZ23';"
                            alt="Thi Công Tủ Bếp Chữ L Kịch Trần Phủ Acrylic Bóng Gương Hiện Đại" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-stone-800">
                                Thi Công Tủ Bếp Chữ L Kịch Trần Phủ Acrylic Bóng Gương Hiện Đại
                            </h3>
                            <p class="text-[11px] sm:text-xs text-stone-500 mt-1">
                                Cốt MDF lõi xanh chống ẩm An Cường, phụ kiện giảm chấn inox 304
                            </p>
                        </div>
                        <div class="mt-2.5 pt-2 border-t border-stone-100 flex items-center justify-between gap-1">
                            <span class="text-[11px] sm:text-xs font-bold text-brand-primary">Báo giá tại xưởng</span>
                            <a href="#bao-gia-lien-he" class="text-[11px] sm:text-xs font-semibold text-stone-700 hover:text-brand-primary underline">Tư vấn</a>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 2 (File Drive 2) -->
                <div class="product-card bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="tu-bep nha-pho">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100 cursor-pointer" onclick="openImageModal('https://drive.google.com/thumbnail?id=18qvT6MOXQMH0UMaNBSrESDQOBTg4f-CC&sz=w1200', 'Tủ Bếp MDF Lõi Xanh Phủ Melamine Kết Hợp Hệ Bàn Đảo Tiện Nghi')">
                        <img 
                            src="https://drive.google.com/thumbnail?id=18qvT6MOXQMH0UMaNBSrESDQOBTg4f-CC&sz=w800" 
                            onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/18qvT6MOXQMH0UMaNBSrESDQOBTg4f-CC';"
                            alt="Tủ Bếp MDF Lõi Xanh Phủ Melamine Kết Hợp Hệ Bàn Đảo Tiện Nghi" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-stone-800">
                                Tủ Bếp MDF Lõi Xanh Phủ Melamine Kết Hợp Hệ Bàn Đảo Tiện Nghi
                            </h3>
                            <p class="text-[11px] sm:text-xs text-stone-500 mt-1">
                                Tối ưu tam giác công năng bếp từ - chậu rửa - tủ lạnh chuẩn phong thủy
                            </p>
                        </div>
                        <div class="mt-2.5 pt-2 border-t border-stone-100 flex items-center justify-between gap-1">
                            <span class="text-[11px] sm:text-xs font-bold text-brand-primary">Báo giá tại xưởng</span>
                            <a href="#bao-gia-lien-he" class="text-[11px] sm:text-xs font-semibold text-stone-700 hover:text-brand-primary underline">Tư vấn</a>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 3 (File Drive 3) -->
                <div class="product-card bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="chung-cu nha-pho">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100 cursor-pointer" onclick="openImageModal('https://drive.google.com/thumbnail?id=1rqvNo5_Ie-OCQrzkL1azMr_LqRK2cZgd&sz=w1200', 'Thi Công Nội Thất Phòng Khách Liền Bếp Căn Hộ Chung Cư Đà Nẵng')">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1rqvNo5_Ie-OCQrzkL1azMr_LqRK2cZgd&sz=w800" 
                            onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1rqvNo5_Ie-OCQrzkL1azMr_LqRK2cZgd';"
                            alt="Thi Công Nội Thất Phòng Khách Liền Bếp Căn Hộ Chung Cư Đà Nẵng" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-stone-800">
                                Thi Công Nội Thất Phòng Khách Liền Bếp Căn Hộ Chung Cư Đà Nẵng
                            </h3>
                            <p class="text-[11px] sm:text-xs text-stone-500 mt-1">
                                Không gian mở hiện đại, kệ tivi vách lam sóng và hệ tủ trang trí
                            </p>
                        </div>
                        <div class="mt-2.5 pt-2 border-t border-stone-100 flex items-center justify-between gap-1">
                            <span class="text-[11px] sm:text-xs font-bold text-brand-primary">Trọn gói theo m²</span>
                            <a href="#bao-gia-lien-he" class="text-[11px] sm:text-xs font-semibold text-stone-700 hover:text-brand-primary underline">Tư vấn</a>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 4 (File Drive 4) -->
                <div class="product-card bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="biet-thu nha-pho">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100 cursor-pointer" onclick="openImageModal('https://drive.google.com/thumbnail?id=1JhhcEEaaXtyMjrTWf5Zk-djWl00iUIjo&sz=w1200', 'Thi Công Nội Thất Phòng Ngủ Master Tủ Áo Cánh Kính Khung Nhôm')">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1JhhcEEaaXtyMjrTWf5Zk-djWl00iUIjo&sz=w800" 
                            onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1JhhcEEaaXtyMjrTWf5Zk-djWl00iUIjo';"
                            alt="Thi Công Nội Thất Phòng Ngủ Master Tủ Áo Cánh Kính Khung Nhôm" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-stone-800">
                                Thi Công Nội Thất Phòng Ngủ Master Tủ Áo Cánh Kính Khung Nhôm
                            </h3>
                            <p class="text-[11px] sm:text-xs text-stone-500 mt-1">
                                Giường ngủ bọc nệm cao cấp, bàn trang điểm và tủ quần áo kịch trần
                            </p>
                        </div>
                        <div class="mt-2.5 pt-2 border-t border-stone-100 flex items-center justify-between gap-1">
                            <span class="text-[11px] sm:text-xs font-bold text-brand-primary">Báo giá tại xưởng</span>
                            <a href="#bao-gia-lien-he" class="text-[11px] sm:text-xs font-semibold text-stone-700 hover:text-brand-primary underline">Tư vấn</a>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 5 (File Drive 5) -->
                <div class="product-card bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="tu-bep biet-thu">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100 cursor-pointer" onclick="openImageModal('https://drive.google.com/thumbnail?id=1AphHF3qh_21yaGdu69T3H5RzE2xQLSFD&sz=w1200', 'Hệ Tủ Bếp Nhựa Đặc Picomat Chịu Nước Kết Hợp Cánh Phủ Laminate')">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1AphHF3qh_21yaGdu69T3H5RzE2xQLSFD&sz=w800" 
                            onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1AphHF3qh_21yaGdu69T3H5RzE2xQLSFD';"
                            alt="Hệ Tủ Bếp Nhựa Đặc Picomat Chịu Nước Kết Hợp Cánh Phủ Laminate" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-stone-800">
                                Hệ Tủ Bếp Nhựa Đặc Picomat Chịu Nước Kết Hợp Cánh Phủ Laminate
                            </h3>
                            <p class="text-[11px] sm:text-xs text-stone-500 mt-1">
                                Chống nước tuyệt đối 100%, chống mối mọt, bền bỉ với khí hậu miền Trung
                            </p>
                        </div>
                        <div class="mt-2.5 pt-2 border-t border-stone-100 flex items-center justify-between gap-1">
                            <span class="text-[11px] sm:text-xs font-bold text-brand-primary">Báo giá tại xưởng</span>
                            <a href="#bao-gia-lien-he" class="text-[11px] sm:text-xs font-semibold text-stone-700 hover:text-brand-primary underline">Tư vấn</a>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 6 (File Drive 6) -->
                <div class="product-card bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="nha-pho biet-thu">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100 cursor-pointer" onclick="openImageModal('https://drive.google.com/thumbnail?id=1Bsc64rOlobh8nydD5CFc8KmWck_HY0HP&sz=w1200', 'Thi Công Nội Thất Nhà Phố Trọn Gói Phong Cách Hiện Đại Tối Giản')">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1Bsc64rOlobh8nydD5CFc8KmWck_HY0HP&sz=w800" 
                            onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1Bsc64rOlobh8nydD5CFc8KmWck_HY0HP';"
                            alt="Thi Công Nội Thất Nhà Phố Trọn Gói Phong Cách Hiện Đại Tối Giản" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-stone-800">
                                Thi Công Nội Thất Nhà Phố Trọn Gói Phong Cách Hiện Đại Tối Giản
                            </h3>
                            <p class="text-[11px] sm:text-xs text-stone-500 mt-1">
                                Đồng bộ phòng khách, phòng bếp, phòng ngủ và phòng thờ gia đình
                            </p>
                        </div>
                        <div class="mt-2.5 pt-2 border-t border-stone-100 flex items-center justify-between gap-1">
                            <span class="text-[11px] sm:text-xs font-bold text-brand-primary">Trọn gói tại xưởng</span>
                            <a href="#bao-gia-lien-he" class="text-[11px] sm:text-xs font-semibold text-stone-700 hover:text-brand-primary underline">Tư vấn</a>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 7 (File Drive 7) -->
                <div class="product-card bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="van-phong cua-hang">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100 cursor-pointer" onclick="openImageModal('https://drive.google.com/thumbnail?id=1EBjZM-9DC3mNyTy9zgTDEIFaqgB7-z1M&sz=w1200', 'Thiết Kế Thi Công Nội Thất Văn Phòng Làm Việc & Quầy Lễ Tân')">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1EBjZM-9DC3mNyTy9zgTDEIFaqgB7-z1M&sz=w800" 
                            onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1EBjZM-9DC3mNyTy9zgTDEIFaqgB7-z1M';"
                            alt="Thiết Kế Thi Công Nội Thất Văn Phòng Làm Việc & Quầy Lễ Tân" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-stone-800">
                                Thiết Kế Thi Công Nội Thất Văn Phòng Làm Việc & Quầy Lễ Tân
                            </h3>
                            <p class="text-[11px] sm:text-xs text-stone-500 mt-1">
                                Bàn họp, hệ tủ hồ sơ, vách logo nhận diện thương hiệu chuyên nghiệp
                            </p>
                        </div>
                        <div class="mt-2.5 pt-2 border-t border-stone-100 flex items-center justify-between gap-1">
                            <span class="text-[11px] sm:text-xs font-bold text-brand-primary">Báo giá theo bản vẽ</span>
                            <a href="#bao-gia-lien-he" class="text-[11px] sm:text-xs font-semibold text-stone-700 hover:text-brand-primary underline">Tư vấn</a>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 8 (File Drive 8) -->
                <div class="product-card bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="cua-hang tu-bep">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100 cursor-pointer" onclick="openImageModal('https://drive.google.com/thumbnail?id=1b7ahfi8M4v7zWh8vHJ6Lyd6b56fffCM4&sz=w1200', 'Trọn Bộ Thiết Bị Nhà Bếp Thông Minh & Phụ Kiện Tủ Bếp Inox 304')">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1b7ahfi8M4v7zWh8vHJ6Lyd6b56fffCM4&sz=w800" 
                            onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1b7ahfi8M4v7zWh8vHJ6Lyd6b56fffCM4';"
                            alt="Trọn Bộ Thiết Bị Nhà Bếp Thông Minh & Phụ Kiện Tủ Bếp Inox 304" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-stone-800">
                                Trọn Bộ Thiết Bị Nhà Bếp Thông Minh & Phụ Kiện Tủ Bếp Inox 304
                            </h3>
                            <p class="text-[11px] sm:text-xs text-stone-500 mt-1">
                                Bếp từ âm, máy hút mùi, máy rửa bát, giá bát nâng hạ, kệ gia vị liên hoàn
                            </p>
                        </div>
                        <div class="mt-2.5 pt-2 border-t border-stone-100 flex items-center justify-between gap-1">
                            <span class="text-[11px] sm:text-xs font-bold text-brand-primary">Chiết khấu ưu đãi</span>
                            <a href="#bao-gia-lien-he" class="text-[11px] sm:text-xs font-semibold text-stone-700 hover:text-brand-primary underline">Tư vấn</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         SECTION 4: THIẾT KẾ NỘI THẤT & TỦ BẾP - THIẾT BỊ BẾP (2 cột trên điện thoại, 4 cột máy tính, không nhãn dán)
         ========================================== -->
    <section id="thiet-ke-noi-that" class="py-5 sm:py-7 bg-brand-cream/60 border-y border-stone-200">
        <div class="flatsome-container" id="tu-bep-thiet-bi">
            <div class="section-title-container">
                <h2 class="section-title-main text-base sm:text-xl font-extrabold uppercase tracking-wide text-stone-800">
                    <span>DỊCH VỤ THIẾT KẾ NỘI THẤT & GIẢI PHÁP TỦ BẾP</span>
                </h2>
                <p class="text-center text-xs sm:text-sm text-stone-500 mt-1">
                    Danh mục thiết kế chuẩn công năng – Cá nhân hóa theo ngân sách gia chủ
                </p>
            </div>

            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4">
                <!-- Hạng mục thiết kế 1 -->
                <div class="bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100 cursor-pointer" onclick="openImageModal('https://drive.google.com/thumbnail?id=1FdlWDwvAf1JFe-xF_XIyIXtPty1FKJLC&sz=w1200', 'Thiết Kế Nội Thất Căn Hộ Chung Cư Hiện Đại Tối Ưu Diện Tích')">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1FdlWDwvAf1JFe-xF_XIyIXtPty1FKJLC&sz=w800" 
                            onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1FdlWDwvAf1JFe-xF_XIyIXtPty1FKJLC';"
                            alt="Thiết Kế Nội Thất Căn Hộ Chung Cư Hiện Đại Tối Ưu Diện Tích" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-stone-800">
                                Thiết Kế Nội Thất Căn Hộ Chung Cư Hiện Đại Tối Ưu Diện Tích
                            </h3>
                            <p class="text-[11px] sm:text-xs text-stone-500 mt-1">
                                Bố trí mặt bằng 2D và phối cảnh 3D căn hộ 1PN, 2PN, 3PN tại Đà Nẵng
                            </p>
                        </div>
                        <div class="mt-2 pt-2 border-t border-stone-100 flex items-center justify-between">
                            <span class="text-[11px] sm:text-xs font-bold text-brand-primary">Miễn phí khi thi công</span>
                            <a href="#bao-gia-lien-he" class="text-[11px] sm:text-xs font-semibold text-stone-700 hover:text-brand-primary underline">Đăng ký</a>
                        </div>
                    </div>
                </div>

                <!-- Hạng mục thiết kế 2 -->
                <div class="bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100 cursor-pointer" onclick="openImageModal('https://drive.google.com/thumbnail?id=1SF1EKm9uh-AaVvr_wWY-yrGJA4OmbHEA&sz=w1200', 'Thiết Kế Nội Thất Nhà Phố & Biệt Thự Villa Phong Cách Luxury, Japandi')">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1SF1EKm9uh-AaVvr_wWY-yrGJA4OmbHEA&sz=w800" 
                            onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1SF1EKm9uh-AaVvr_wWY-yrGJA4OmbHEA';"
                            alt="Thiết Kế Nội Thất Nhà Phố & Biệt Thự Villa Phong Cách Luxury, Japandi" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-stone-800">
                                Thiết Kế Nội Thất Nhà Phố & Biệt Thự Villa Phong Cách Luxury, Japandi
                            </h3>
                            <p class="text-[11px] sm:text-xs text-stone-500 mt-1">
                                Giải pháp lấy sáng tự nhiên, thông tầng và vật liệu gỗ cao cấp
                            </p>
                        </div>
                        <div class="mt-2 pt-2 border-t border-stone-100 flex items-center justify-between">
                            <span class="text-[11px] sm:text-xs font-bold text-brand-primary">Miễn phí khi thi công</span>
                            <a href="#bao-gia-lien-he" class="text-[11px] sm:text-xs font-semibold text-stone-700 hover:text-brand-primary underline">Đăng ký</a>
                        </div>
                    </div>
                </div>

                <!-- Hạng mục thiết kế 3 -->
                <div class="bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100 cursor-pointer" onclick="openImageModal('https://drive.google.com/thumbnail?id=1-SlgWBIhU6m6URZNRdQo5x1UK49BMOpf&sz=w1200', 'Thiết Kế & Thi Công Tủ Bếp Cánh Kính Cường Lực Khung Nhôm Anode')">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1-SlgWBIhU6m6URZNRdQo5x1UK49BMOpf&sz=w800" 
                            onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1-SlgWBIhU6m6URZNRdQo5x1UK49BMOpf';"
                            alt="Thiết Kế & Thi Công Tủ Bếp Cánh Kính Cường Lực Khung Nhôm Anode" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-stone-800">
                                Thiết Kế & Thi Công Tủ Bếp Cánh Kính Cường Lực Khung Nhôm Anode
                            </h3>
                            <p class="text-[11px] sm:text-xs text-stone-500 mt-1">
                                Tích hợp đèn LED cảm biến thông minh, chống xước, sang trọng bậc nhất
                            </p>
                        </div>
                        <div class="mt-2 pt-2 border-t border-stone-100 flex items-center justify-between">
                            <span class="text-[11px] sm:text-xs font-bold text-brand-primary">Báo giá theo mét dài</span>
                            <a href="#bao-gia-lien-he" class="text-[11px] sm:text-xs font-semibold text-stone-700 hover:text-brand-primary underline">Đăng ký</a>
                        </div>
                    </div>
                </div>

                <!-- Hạng mục thiết kế 4 -->
                <div class="bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100 cursor-pointer" onclick="openImageModal('https://drive.google.com/thumbnail?id=1wfdSeT3hpDvWut50-hNxVHFS6O5hCZ23&sz=w1200', 'Thiết Kế Nội Thất Văn Phòng Công Ty, Showroom & Cửa Hàng Kinh Doanh')">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1wfdSeT3hpDvWut50-hNxVHFS6O5hCZ23&sz=w800" 
                            onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1wfdSeT3hpDvWut50-hNxVHFS6O5hCZ23';"
                            alt="Thiết Kế Nội Thất Văn Phòng Công Ty, Showroom & Cửa Hàng Kinh Doanh" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-stone-800">
                                Thiết Kế Nội Thất Văn Phòng Công Ty, Showroom & Cửa Hàng Kinh Doanh
                            </h3>
                            <p class="text-[11px] sm:text-xs text-stone-500 mt-1">
                                Tối ưu nhận diện thương hiệu, không gian mở tăng hiệu suất làm việc
                            </p>
                        </div>
                        <div class="mt-2 pt-2 border-t border-stone-100 flex items-center justify-between">
                            <span class="text-[11px] sm:text-xs font-bold text-brand-primary">Miễn phí khảo sát</span>
                            <a href="#bao-gia-lien-he" class="text-[11px] sm:text-xs font-semibold text-stone-700 hover:text-brand-primary underline">Đăng ký</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         SECTION 5: DANH MỤC CÁC DỰ ÁN Ở ĐÀ NẴNG TRÊN TRANG CHỦ
         (Chia 2 cột trên điện thoại, 4 cột trên máy tính, không nhãn dán, tên dự án đầy đủ)
         ========================================== -->
    <section id="du-an-da-nang" class="py-5 sm:py-7">
        <div class="flatsome-container">
            <div class="section-title-container">
                <h2 class="section-title-main text-base sm:text-xl font-extrabold uppercase tracking-wide text-stone-800">
                    <span>CÔNG TRÌNH & DỰ ÁN THỰC TẾ TẠI ĐÀ NẴNG</span>
                </h2>
                <p class="text-center text-xs sm:text-sm text-stone-500 mt-1">
                    Các dự án thiết kế – thi công nội thất và tủ bếp tiêu biểu do XINH HOME thực hiện tại Đà Nẵng
                </p>
            </div>

            <!-- Danh mục lọc Dự Án Đà Nẵng: chữ nhỏ gọn, viết liền không xuống dòng chữ -->
            <div class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-5">
                <button onclick="filterProjectCategory('all')" data-proj-btn="all" class="cat-pill active">Tất cả dự án Đà Nẵng</button>
                <button onclick="filterProjectCategory('can-ho-dn')" data-proj-btn="can-ho-dn" class="cat-pill">Căn hộ Chung cư Đà Nẵng</button>
                <button onclick="filterProjectCategory('nha-pho-dn')" data-proj-btn="nha-pho-dn" class="cat-pill">Nhà phố Đà Nẵng</button>
                <button onclick="filterProjectCategory('biet-thu-dn')" data-proj-btn="biet-thu-dn" class="cat-pill">Biệt thự & Villa Đà Nẵng</button>
                <button onclick="filterProjectCategory('tu-bep-dn')" data-proj-btn="tu-bep-dn" class="cat-pill">Dự án Tủ bếp thực tế</button>
            </div>

            <!-- Lưới Dự Án: 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div id="project-grid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4">
                <!-- Dự án 1 -->
                <div class="project-card bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-proj="can-ho-dn tu-bep-dn">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100 cursor-pointer" onclick="openImageModal('https://drive.google.com/thumbnail?id=1wfdSeT3hpDvWut50-hNxVHFS6O5hCZ23&sz=w1200', 'Thi Công Nội Thất & Tủ Bếp Căn Hộ FPT Plaza 2 - Ngũ Hành Sơn, Đà Nẵng')">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1wfdSeT3hpDvWut50-hNxVHFS6O5hCZ23&sz=w800" 
                            onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1wfdSeT3hpDvWut50-hNxVHFS6O5hCZ23';"
                            alt="Thi Công Nội Thất & Tủ Bếp Căn Hộ FPT Plaza 2 - Ngũ Hành Sơn, Đà Nẵng" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-stone-800">
                            Thi Công Nội Thất & Tủ Bếp Căn Hộ FPT Plaza 2 – Ngũ Hành Sơn, Đà Nẵng
                        </h3>
                        <p class="text-[11px] sm:text-xs text-stone-500 mt-1.5">
                            Hạng mục: Phòng khách, Tủ bếp kịch trần & 2 Phòng ngủ
                        </p>
                    </div>
                </div>

                <!-- Dự án 2 -->
                <div class="project-card bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-proj="can-ho-dn">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100 cursor-pointer" onclick="openImageModal('https://drive.google.com/thumbnail?id=18qvT6MOXQMH0UMaNBSrESDQOBTg4f-CC&sz=w1200', 'Thiết Kế Thi Công Trọn Gói Căn Hộ Sun Ponte Residence Đà Nẵng 3 Phòng Ngủ')">
                        <img 
                            src="https://drive.google.com/thumbnail?id=18qvT6MOXQMH0UMaNBSrESDQOBTg4f-CC&sz=w800" 
                            onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/18qvT6MOXQMH0UMaNBSrESDQOBTg4f-CC';"
                            alt="Thiết Kế Thi Công Trọn Gói Căn Hộ Sun Ponte Residence Đà Nẵng 3 Phòng Ngủ" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-stone-800">
                            Thiết Kế Thi Công Trọn Gói Căn Hộ Sun Ponte Residence Đà Nẵng 3 Phòng Ngủ
                        </h3>
                        <p class="text-[11px] sm:text-xs text-stone-500 mt-1.5">
                            Hạng mục: Nội thất gỗ MDF An Cường & Thiết bị bếp đồng bộ
                        </p>
                    </div>
                </div>

                <!-- Dự án 3 -->
                <div class="project-card bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-proj="nha-pho-dn tu-bep-dn">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100 cursor-pointer" onclick="openImageModal('https://drive.google.com/thumbnail?id=1rqvNo5_Ie-OCQrzkL1azMr_LqRK2cZgd&sz=w1200', 'Thi Công Nội Thất Nhà Phố Khu Đô Thị Hòa Xuân – Cẩm Lệ, Đà Nẵng')">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1rqvNo5_Ie-OCQrzkL1azMr_LqRK2cZgd&sz=w800" 
                            onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1rqvNo5_Ie-OCQrzkL1azMr_LqRK2cZgd';"
                            alt="Thi Công Nội Thất Nhà Phố Khu Đô Thị Hòa Xuân – Cẩm Lệ, Đà Nẵng" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-stone-800">
                            Thi Công Nội Thất Nhà Phố Khu Đô Thị Hòa Xuân – Cẩm Lệ, Đà Nẵng
                        </h3>
                        <p class="text-[11px] sm:text-xs text-stone-500 mt-1.5">
                            Hạng mục: Nội thất nhà phố 3 tầng hiện đại, tủ bếp Acrylic
                        </p>
                    </div>
                </div>

                <!-- Dự án 4 -->
                <div class="project-card bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-proj="biet-thu-dn">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100 cursor-pointer" onclick="openImageModal('https://drive.google.com/thumbnail?id=1JhhcEEaaXtyMjrTWf5Zk-djWl00iUIjo&sz=w1200', 'Hoàn Thiện Nội Thất Biệt Thự Euro Village 2 – Sơn Trà, Đà Nẵng')">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1JhhcEEaaXtyMjrTWf5Zk-djWl00iUIjo&sz=w800" 
                            onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1JhhcEEaaXtyMjrTWf5Zk-djWl00iUIjo';"
                            alt="Hoàn Thiện Nội Thất Biệt Thự Euro Village 2 – Sơn Trà, Đà Nẵng" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-stone-800">
                            Hoàn Thiện Nội Thất Biệt Thự Euro Village 2 – Sơn Trà, Đà Nẵng
                        </h3>
                        <p class="text-[11px] sm:text-xs text-stone-500 mt-1.5">
                            Hạng mục: Phòng khách Luxury, Bếp đảo & Phòng ngủ Master
                        </p>
                    </div>
                </div>

                <!-- Dự án 5 -->
                <div class="project-card bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-proj="can-ho-dn">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100 cursor-pointer" onclick="openImageModal('https://drive.google.com/thumbnail?id=1AphHF3qh_21yaGdu69T3H5RzE2xQLSFD&sz=w1200', 'Thi Công Nội Thất Căn Hộ The Ori Garden Bàu Tràm – Liên Chiểu, Đà Nẵng')">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1AphHF3qh_21yaGdu69T3H5RzE2xQLSFD&sz=w800" 
                            onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1AphHF3qh_21yaGdu69T3H5RzE2xQLSFD';"
                            alt="Thi Công Nội Thất Căn Hộ The Ori Garden Bàu Tràm – Liên Chiểu, Đà Nẵng" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-stone-800">
                            Thi Công Nội Thất Căn Hộ The Ori Garden Bàu Tràm – Liên Chiểu, Đà Nẵng
                        </h3>
                        <p class="text-[11px] sm:text-xs text-stone-500 mt-1.5">
                            Hạng mục: Gói nội thất tiết kiệm tối ưu diện tích căn 2PN
                        </p>
                    </div>
                </div>

                <!-- Dự án 6 -->
                <div class="project-card bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-proj="nha-pho-dn tu-bep-dn">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100 cursor-pointer" onclick="openImageModal('https://drive.google.com/thumbnail?id=1Bsc64rOlobh8nydD5CFc8KmWck_HY0HP&sz=w1200', 'Thi Công Nội Thất Nhà Phố Trần Đại Nghĩa – Ngũ Hành Sơn, Đà Nẵng')">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1Bsc64rOlobh8nydD5CFc8KmWck_HY0HP&sz=w800" 
                            onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1Bsc64rOlobh8nydD5CFc8KmWck_HY0HP';"
                            alt="Thi Công Nội Thất Nhà Phố Trần Đại Nghĩa – Ngũ Hành Sơn, Đà Nẵng" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-stone-800">
                            Thi Công Nội Thất Nhà Phố Trần Đại Nghĩa – Ngũ Hành Sơn, Đà Nẵng
                        </h3>
                        <p class="text-[11px] sm:text-xs text-stone-500 mt-1.5">
                            Hạng mục: Tủ bếp nhựa Picomat cánh phủ Acrylic & Phòng khách
                        </p>
                    </div>
                </div>

                <!-- Dự án 7 -->
                <div class="project-card bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-proj="can-ho-dn">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100 cursor-pointer" onclick="openImageModal('https://drive.google.com/thumbnail?id=1EBjZM-9DC3mNyTy9zgTDEIFaqgB7-z1M&sz=w1200', 'Thi Công Nội Thất Căn Hộ Cho Thuê Khu Phố Tây Phan Tứ – Mỹ An, Đà Nẵng')">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1EBjZM-9DC3mNyTy9zgTDEIFaqgB7-z1M&sz=w800" 
                            onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1EBjZM-9DC3mNyTy9zgTDEIFaqgB7-z1M';"
                            alt="Thi Công Nội Thất Căn Hộ Cho Thuê Khu Phố Tây Phan Tứ – Mỹ An, Đà Nẵng" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-stone-800">
                            Thi Công Nội Thất Căn Hộ Cho Thuê Khu Phố Tây Phan Tứ – Mỹ An, Đà Nẵng
                        </h3>
                        <p class="text-[11px] sm:text-xs text-stone-500 mt-1.5">
                            Hạng mục: Hoàn thiện trọn gói tòa căn hộ dịch vụ 12 phòng
                        </p>
                    </div>
                </div>

                <!-- Dự án 8 -->
                <div class="project-card bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-proj="biet-thu-dn tu-bep-dn">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-stone-100 cursor-pointer" onclick="openImageModal('https://drive.google.com/thumbnail?id=1b7ahfi8M4v7zWh8vHJ6Lyd6b56fffCM4&sz=w1200', 'Thi Công Tủ Bếp Cánh Kính & Nội Thất Villa Khu Đô Thị Nam Việt Á, Đà Nẵng')">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1b7ahfi8M4v7zWh8vHJ6Lyd6b56fffCM4&sz=w800" 
                            onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1b7ahfi8M4v7zWh8vHJ6Lyd6b56fffCM4';"
                            alt="Thi Công Tủ Bếp Cánh Kính & Nội Thất Villa Khu Đô Thị Nam Việt Á, Đà Nẵng" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-stone-800">
                            Thi Công Tủ Bếp Cánh Kính & Nội Thất Villa Khu Đô Thị Nam Việt Á, Đà Nẵng
                        </h3>
                        <p class="text-[11px] sm:text-xs text-stone-500 mt-1.5">
                            Hạng mục: Hệ tủ bếp cánh kính cường lực & Thiết bị bếp Bosch
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         SECTION 6: DANH MỤC CÁC ĐỐI TÁC CHIẾN LƯỢC
         ========================================== -->
    <section id="doi-tac" class="py-5 sm:py-7 bg-white border-y border-stone-200">
        <div class="flatsome-container">
            <div class="section-title-container">
                <h2 class="section-title-main text-base sm:text-xl font-extrabold uppercase tracking-wide text-stone-800">
                    <span>ĐỐI TÁC VẬT LIỆU & THIẾT BỊ BẾP CHÍNH HÃNG</span>
                </h2>
                <p class="text-center text-xs sm:text-sm text-stone-500 mt-1">
                    XINH HOME hợp tác trực tiếp với các thương hiệu vật tư nội thất và thiết bị nhà bếp hàng đầu
                </p>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-5 gap-2.5 sm:gap-3.5">
                <div class="p-3 rounded-lg border border-stone-200 bg-brand-light text-center flex flex-col items-center justify-center">
                    <span class="text-sm sm:text-base font-extrabold text-brand-primary tracking-wide">AN CƯỜNG</span>
                    <span class="text-[11px] text-stone-500 mt-0.5">Gỗ Công Nghiệp Cao Cấp</span>
                </div>
                <div class="p-3 rounded-lg border border-stone-200 bg-brand-light text-center flex flex-col items-center justify-center">
                    <span class="text-sm sm:text-base font-extrabold text-brand-primary tracking-wide">HÄFELE</span>
                    <span class="text-[11px] text-stone-500 mt-0.5">Phụ Kiện Nội Thất Đức</span>
                </div>
                <div class="p-3 rounded-lg border border-stone-200 bg-brand-light text-center flex flex-col items-center justify-center">
                    <span class="text-sm sm:text-base font-extrabold text-brand-primary tracking-wide">BLUM</span>
                    <span class="text-[11px] text-stone-500 mt-0.5">Bản Lề & Ray Trượt Giảm Chấn</span>
                </div>
                <div class="p-3 rounded-lg border border-stone-200 bg-brand-light text-center flex flex-col items-center justify-center">
                    <span class="text-sm sm:text-base font-extrabold text-brand-primary tracking-wide">BOSCH</span>
                    <span class="text-[11px] text-stone-500 mt-0.5">Thiết Bị Bếp Thông Minh</span>
                </div>
                <div class="p-3 rounded-lg border border-stone-200 bg-brand-light text-center flex flex-col items-center justify-center">
                    <span class="text-sm sm:text-base font-extrabold text-brand-primary tracking-wide">EUROGOLD</span>
                    <span class="text-[11px] text-stone-500 mt-0.5">Phụ Kiện Tủ Bếp Inox 304</span>
                </div>
                <div class="p-3 rounded-lg border border-stone-200 bg-brand-light text-center flex flex-col items-center justify-center">
                    <span class="text-sm sm:text-base font-extrabold text-brand-primary tracking-wide">PICOMAT</span>
                    <span class="text-[11px] text-stone-500 mt-0.5">Ván Nhựa Đặc Chịu Nước</span>
                </div>
                <div class="p-3 rounded-lg border border-stone-200 bg-brand-light text-center flex flex-col items-center justify-center">
                    <span class="text-sm sm:text-base font-extrabold text-brand-primary tracking-wide">MALLOCA</span>
                    <span class="text-[11px] text-stone-500 mt-0.5">Thiết Bị Nhà Bếp Cao Cấp</span>
                </div>
                <div class="p-3 rounded-lg border border-stone-200 bg-brand-light text-center flex flex-col items-center justify-center">
                    <span class="text-sm sm:text-base font-extrabold text-brand-primary tracking-wide">KAFF</span>
                    <span class="text-[11px] text-stone-500 mt-0.5">Bếp Điện Từ & Máy Hút Mùi</span>
                </div>
                <div class="p-3 rounded-lg border border-stone-200 bg-brand-light text-center flex flex-col items-center justify-center">
                    <span class="text-sm sm:text-base font-extrabold text-brand-primary tracking-wide">EUROSUN</span>
                    <span class="text-[11px] text-stone-500 mt-0.5">Thiết Bị Bếp Đồng Bộ</span>
                </div>
                <div class="p-3 rounded-lg border border-stone-200 bg-brand-light text-center flex flex-col items-center justify-center">
                    <span class="text-sm sm:text-base font-extrabold text-brand-primary tracking-wide">VICOSTONE</span>
                    <span class="text-[11px] text-stone-500 mt-0.5">Đá Thạch Anh Mặt Bếp</span>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         SECTION 7: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (Tin tức & Kinh nghiệm nội thất)
         ========================================== -->
    <section id="tin-tuc" class="py-5 sm:py-7">
        <div class="flatsome-container">
            <div class="section-title-container">
                <h2 class="section-title-main text-base sm:text-xl font-extrabold uppercase tracking-wide text-stone-800">
                    <span>DANH MỤC BÀI VIẾT & KINH NGHIỆM NỘI THẤT</span>
                </h2>
                <p class="text-center text-xs sm:text-sm text-stone-500 mt-1">
                    Cập nhật bảng báo giá nội thất, kinh nghiệm thi công tủ bếp và xu hướng thiết kế mới nhất
                </p>
            </div>

            <!-- Danh mục bài viết trang chủ (chữ nhỏ gọn, không xuống dòng tên danh mục) -->
            <div class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-5">
                <button onclick="filterBlogCategory('all')" data-blog-btn="all" class="cat-pill active">Tất cả bài viết</button>
                <button onclick="filterBlogCategory('bao-gia')" data-blog-btn="bao-gia" class="cat-pill">Báo giá thi công nội thất</button>
                <button onclick="filterBlogCategory('kinh-nghiem-bep')" data-blog-btn="kinh-nghiem-bep" class="cat-pill">Kinh nghiệm làm tủ bếp</button>
                <button onclick="filterBlogCategory('xu-huong')" data-blog-btn="xu-huong" class="cat-pill">Xu hướng nội thất 2026</button>
                <button onclick="filterBlogCategory('phong-thuy')" data-blog-btn="phong-thuy" class="cat-pill">Phong thủy nhà bếp</button>
            </div>

            <!-- Lưới Bài Viết: 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div id="blog-grid" class="grid grid-cols-2 lg:grid-cols-4 gap-2.5 sm:gap-4">
                <!-- Bài viết 1 -->
                <article class="blog-card bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm flex flex-col" data-blog="bao-gia">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-stone-100">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1FdlWDwvAf1JFe-xF_XIyIXtPty1FKJLC&sz=w800" 
                            onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1FdlWDwvAf1JFe-xF_XIyIXtPty1FKJLC';"
                            alt="Báo giá thi công nội thất chung cư Đà Nẵng trọn gói chất lượng 2026" 
                            class="w-full h-full object-cover"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-stone-800">
                                Báo Giá Thi Công Nội Thất Chung Cư Đà Nẵng Trọn Gói Chất Lượng 2026
                            </h3>
                            <p class="text-[11px] sm:text-xs text-stone-500 mt-1.5">
                                Chi tiết chi phí hoàn thiện nội thất căn hộ 1PN, 2PN, 3PN với cốt gỗ MDF chống ẩm An Cường...
                            </p>
                        </div>
                        <a href="#bao-gia-lien-he" class="mt-2.5 text-[11px] sm:text-xs font-semibold text-brand-primary hover:underline inline-flex items-center gap-1">
                            <span>Nhận bảng giá chi tiết</span>
                            <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </article>

                <!-- Bài viết 2 -->
                <article class="blog-card bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm flex flex-col" data-blog="kinh-nghiem-bep">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-stone-100">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1SF1EKm9uh-AaVvr_wWY-yrGJA4OmbHEA&sz=w800" 
                            onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1SF1EKm9uh-AaVvr_wWY-yrGJA4OmbHEA';"
                            alt="So sánh tủ bếp Acrylic, Laminate và Melamine: Nên chọn loại nào?" 
                            class="w-full h-full object-cover"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-stone-800">
                                So Sánh Tủ Bếp Acrylic, Laminate Và Melamine: Gia Đình Nên Chọn Loại Nào?
                            </h3>
                            <p class="text-[11px] sm:text-xs text-stone-500 mt-1.5">
                                Phân tích ưu nhược điểm, độ bền chống ẩm và cách kết hợp thùng nhựa Picomat cho khoang chậu rửa...
                            </p>
                        </div>
                        <a href="#bao-gia-lien-he" class="mt-2.5 text-[11px] sm:text-xs font-semibold text-brand-primary hover:underline inline-flex items-center gap-1">
                            <span>Tư vấn chọn vật liệu</span>
                            <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </article>

                <!-- Bài viết 3 -->
                <article class="blog-card bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm flex flex-col" data-blog="xu-huong">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-stone-100">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1-SlgWBIhU6m6URZNRdQo5x1UK49BMOpf&sz=w800" 
                            onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1-SlgWBIhU6m6URZNRdQo5x1UK49BMOpf';"
                            alt="Giải pháp tủ bếp kịch trần và xử lý góc chết thông minh cho nhà phố nhỏ" 
                            class="w-full h-full object-cover"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-stone-800">
                                Giải Pháp Tủ Bếp Kịch Trần & Xử Lý Góc Chết Thông Minh Cho Nhà Phố
                            </h3>
                            <p class="text-[11px] sm:text-xs text-stone-500 mt-1.5">
                                Ứng dụng mâm xoay liên hoàn, kệ nâng hạ và gam màu sáng giúp nhân đôi không gian lưu trữ...
                            </p>
                        </div>
                        <a href="#bao-gia-lien-he" class="mt-2.5 text-[11px] sm:text-xs font-semibold text-brand-primary hover:underline inline-flex items-center gap-1">
                            <span>Xem giải pháp thiết kế</span>
                            <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </article>

                <!-- Bài viết 4 -->
                <article class="blog-card bg-white rounded-lg border border-stone-200 overflow-hidden shadow-sm flex flex-col" data-blog="phong-thuy">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-stone-100">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1AphHF3qh_21yaGdu69T3H5RzE2xQLSFD&sz=w800" 
                            onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1AphHF3qh_21yaGdu69T3H5RzE2xQLSFD';"
                            alt="Kích thước tủ bếp chuẩn thước Lỗ Ban và nguyên tắc tam giác công năng" 
                            class="w-full h-full object-cover"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-stone-800">
                                Kích Thước Tủ Bếp Chuẩn Thước Lỗ Ban & Nguyên Tắc Tam Giác Công Năng
                            </h3>
                            <p class="text-[11px] sm:text-xs text-stone-500 mt-1.5">
                                Hướng dẫn bố trí bếp nấu – bồn rửa – tủ lạnh vừa thuận tiện cho người nội trợ vừa vượng khí...
                            </p>
                        </div>
                        <a href="#bao-gia-lien-he" class="mt-2.5 text-[11px] sm:text-xs font-semibold text-brand-primary hover:underline inline-flex items-center gap-1">
                            <span>Đặt lịch khảo sát</span>
                            <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- ==========================================
         SECTION 8: FORM YÊU CẦU BÁO GIÁ + FANPAGE FACEBOOK + GOOGLE MAPS NGOÀI TRANG CHỦ
         ========================================== -->
    <section id="bao-gia-lien-he" class="py-5 sm:py-8 bg-brand-cream/70 border-t border-stone-200">
        <div class="flatsome-container">
            <div class="section-title-container">
                <h2 class="section-title-main text-base sm:text-xl font-extrabold uppercase tracking-wide text-stone-800">
                    <span> ĐĂNG KÝ TƯ VẤN & NHẬN BÁO GIÁ TẠI XƯỞNG</span>
                </h2>
                <p class="text-center text-xs sm:text-sm text-stone-500 mt-1">
                    Quý khách chỉ cần để lại nhu cầu hoặc mức ngân sách dự kiến, XINH HOME sẽ tư vấn phương án tối ưu nhất
                </p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-start">
                <!-- CỘT 1: FORM YÊU CẦU VÀ BÁO GIÁ TRANG CHỦ (5/12) -->
                <div class="lg:col-span-5 bg-white rounded-xl border border-stone-200 p-4 sm:p-5 shadow-sm">
                    <h3 class="text-sm sm:text-base font-extrabold text-brand-primary uppercase mb-3 flex items-center gap-2">
                        <i class="fa-solid fa-file-invoice-dollar"></i>
                        <span>Form Yêu Cầu Tư Vấn & Báo Giá</span>
                    </h3>
                    <form id="quote-form" onsubmit="submitQuoteForm(event)" class="space-y-3">
                        <div>
                            <label class="block text-xs font-semibold text-stone-700 mb-1">Họ và tên quý khách *</label>
                            <input type="text" id="q-name" required placeholder="Nhập họ và tên..." class="w-full px-3 py-2 text-xs sm:text-sm rounded-lg border border-stone-300 focus:outline-none focus:border-brand-primary">
                        </div>
                        <div>
                            <label class="block text-xs font-semibold text-stone-700 mb-1">Số điện thoại / Zalo *</label>
                            <input type="tel" id="q-phone" required placeholder="Ví dụ: 0905060839" class="w-full px-3 py-2 text-xs sm:text-sm rounded-lg border border-stone-300 focus:outline-none focus:border-brand-primary">
                        </div>
                        <div>
                            <label class="block text-xs font-semibold text-stone-700 mb-1">Hạng mục cần tư vấn báo giá *</label>
                            <select id="q-service" class="w-full px-3 py-2 text-xs sm:text-sm rounded-lg border border-stone-300 focus:outline-none focus:border-brand-primary bg-white">
                                <option value="Thi công Tủ bếp & Thiết bị bếp trọn gói">Thi công Tủ bếp & Thiết bị bếp trọn gói</option>
                                <option value="Thiết kế & Thi công nội thất Chung cư">Thiết kế & Thi công nội thất Chung cư</option>
                                <option value="Thiết kế & Thi công nội thất Nhà phố">Thiết kế & Thi công nội thất Nhà phố</option>
                                <option value="Thiết kế & Thi công nội thất Biệt thự / Villa">Thiết kế & Thi công nội thất Biệt thự / Villa</option>
                                <option value="Thiết kế & Thi công nội thất Văn phòng / Cửa hàng">Thiết kế & Thi công nội thất Văn phòng / Cửa hàng</option>
                            </select>
                        </div>
                        <div class="grid grid-cols-2 gap-2.5">
                            <div>
                                <label class="block text-xs font-semibold text-stone-700 mb-1">Khu vực công trình</label>
                                <input type="text" id="q-address" placeholder="VD: Ngũ Hành Sơn, ĐN" class="w-full px-3 py-2 text-xs sm:text-sm rounded-lg border border-stone-300 focus:outline-none focus:border-brand-primary">
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-stone-700 mb-1">Ngân sách dự kiến</label>
                                <select id="q-budget" class="w-full px-3 py-2 text-xs sm:text-sm rounded-lg border border-stone-300 focus:outline-none focus:border-brand-primary bg-white">
                                    <option value="Tư vấn theo thực tế">Tư vấn theo thực tế</option>
                                    <option value="Dưới 30 triệu">Dưới 30 triệu</option>
                                    <option value="30 - 80 triệu">30 - 80 triệu</option>
                                    <option value="80 - 150 triệu">80 - 150 triệu</option>
                                    <option value="Trên 150 triệu">Trên 150 triệu</option>
                                </select>
                            </div>
                        </div>
                        <div>
                            <label class="block text-xs font-semibold text-stone-700 mb-1">Ghi chú yêu cầu (Vật liệu, kích thước...)</label>
                            <textarea id="q-note" rows="2" placeholder="Nhập yêu cầu chi tiết (nếu có)..." class="w-full px-3 py-2 text-xs sm:text-sm rounded-lg border border-stone-300 focus:outline-none focus:border-brand-primary"></textarea>
                        </div>
                        <button type="submit" class="w-full py-2.5 px-4 rounded-lg bg-brand-primary hover:bg-brand-dark text-white font-bold text-xs sm:text-sm transition shadow">
                            <i class="fa-solid fa-paper-plane mr-1.5"></i>GỬI YÊU CẦU BÁO GIÁ NGAY
                        </button>
                    </form>
                    <div id="quote-success" class="hidden mt-3 p-3 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs leading-relaxed"></div>
                </div>

                <!-- CỘT 2: ĐƯA FANPAGE & GOOGLE MAP RA NGOÀI TRANG CHỦ (7/12) -->
                <div class="lg:col-span-7 space-y-4">
                    <!-- Hộp Fanpage Facebook ngoài trang chủ -->
                    <div class="bg-white rounded-xl border border-stone-200 p-4 shadow-sm">
                        <div class="flex items-center justify-between flex-wrap gap-2 mb-3">
                            <h3 class="text-sm sm:text-base font-extrabold text-stone-800 flex items-center gap-2">
                                <i class="fa-brands fa-facebook text-blue-600 text-lg"></i>
                                <span>FANPAGE NỘI THẤT & THIẾT BỊ BẾP XINH HOME</span>
                            </h3>
                            <a href="https://www.facebook.com/profile.php?id=61578493040326" target="_blank" rel="noopener noreferrer" class="px-3 py-1.5 rounded-lg bg-blue-600 hover:bg-blue-700 text-white text-xs font-semibold inline-flex items-center gap-1.5">
                                <i class="fa-brands fa-facebook-f"></i>
                                <span>Theo dõi Fanpage</span>
                            </a>
                        </div>

                        <!-- Thẻ trực quan Fanpage + Iframe Plugin Facebook -->
                        <div class="grid grid-cols-1 md:grid-cols-12 gap-3 items-center bg-stone-50 p-3 rounded-lg border border-stone-200">
                            <div class="md:col-span-7 flex items-start gap-3">
                                <img 
                                    src="https://drive.google.com/thumbnail?id=1a-o52YR4IejHhCbw3tlOOED55z1Iyp9K&sz=w200" 
                                    onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1a-o52YR4IejHhCbw3tlOOED55z1Iyp9K';"
                                    alt="Logo Fanpage XINH HOME" 
                                    class="w-12 h-12 rounded-lg object-contain bg-white border border-stone-200 p-1 shrink-0"
                                >
                                <div class="text-xs space-y-1">
                                    <a href="https://www.facebook.com/profile.php?id=61578493040326" target="_blank" rel="noopener noreferrer" class="font-bold text-sm text-blue-700 hover:underline block">
                                        Nội Thất & Thiết Bị Bếp Xinh Home
                                    </a>
                                    <p class="text-stone-600">Chuyên thiết kế & thi công nội thất trọn gói, tủ bếp cao cấp, thiết bị nhà bếp chính hãng tại Đà Nẵng.</p>
                                    <p class="text-stone-500"><i class="fa-solid fa-location-dot text-brand-primary mr-1"></i>51 Trần Đại Nghĩa, Ngũ Hành Sơn, Đà Nẵng</p>
                                </div>
                            </div>
                            <div class="md:col-span-5 flex flex-col gap-2">
                                <a href="https://www.facebook.com/profile.php?id=61578493040326" target="_blank" rel="noopener noreferrer" class="w-full py-2 px-3 rounded-lg bg-white hover:bg-blue-50 text-blue-700 border border-blue-200 text-xs font-semibold text-center transition">
                                    <i class="fa-brands fa-facebook-messenger mr-1"></i>Nhắn tin qua Fanpage
                                </a>
                                <a href="https://zalo.me/0905060839" target="_blank" rel="noopener noreferrer" class="w-full py-2 px-3 rounded-lg bg-sky-500 hover:bg-sky-600 text-white text-xs font-semibold text-center transition">
                                    <i class="fa-solid fa-comment-dots mr-1"></i>Chat Zalo: 0905.060.839
                                </a>
                            </div>
                        </div>
                    </div>

                    <!-- Hộp Bản Đồ Google Maps Ngoài Trang Chủ -->
                    <div class="bg-white rounded-xl border border-stone-200 p-4 shadow-sm">
                        <div class="flex items-center justify-between flex-wrap gap-2 mb-3">
                            <div>
                                <h3 class="text-sm sm:text-base font-extrabold text-stone-800 flex items-center gap-2">
                                    <i class="fa-solid fa-map-location-dot text-red-600 text-lg"></i>
                                    <span>BẢN ĐỒ ĐỊA CHỈ SHOWROOM XINH HOME ĐÀ NẴNG</span>
                                </h3>
                                <p class="text-xs text-stone-500 mt-0.5">
                                    Địa chỉ: 51 Trần Đại Nghĩa, Phường Hòa Hải, Quận Ngũ Hành Sơn, TP. Đà Nẵng
                                </p>
                            </div>
                            <a href="https://share.google/smFcyGIks6zzdYzel" target="_blank" rel="noopener noreferrer" class="px-3 py-1.5 rounded-lg bg-emerald-600 hover:bg-emerald-700 text-white text-xs font-semibold inline-flex items-center gap-1.5">
                                <i class="fa-solid fa-diamond-turn-right"></i>
                                <span>Mở Google Maps chỉ đường</span>
                            </a>
                        </div>

                        <!-- Iframe Google Maps trực tiếp ngoài trang chủ -->
                        <div class="w-full h-56 sm:h-64 rounded-lg overflow-hidden border border-stone-200 bg-stone-100">
                            <iframe 
                                title="Bản đồ XINH HOME 51 Trần Đại Nghĩa, Ngũ Hành Sơn, Đà Nẵng"
                                src="https://maps.google.com/maps?q=51%20Tr%E1%BA%A7n%20%C4%90%E1%BA%A1i%20Ngh%C4%A9a,%20Ng%C5%A9%20H%C3%A0nh%20S%C6%A1n,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed" 
                                class="w-full h-full border-0" 
                                allowfullscreen="" 
                                loading="lazy" 
                                referrerpolicy="no-referrer-when-downgrade">
                            </iframe>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         FOOTER CHUẨN FLATSOME (Đầy đủ thông tin doanh nghiệp)
         ========================================== -->
    <footer class="bg-brand-charcoal text-gray-300 pt-8 pb-20 lg:pb-8 border-t border-stone-800 text-xs sm:text-sm">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-6 pb-6 border-b border-stone-700">
                <!-- Cột 1: Thông tin công ty -->
                <div class="lg:col-span-5 space-y-2.5">
                    <div class="flex items-center gap-2.5">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1a-o52YR4IejHhCbw3tlOOED55z1Iyp9K&sz=w200" 
                            onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1a-o52YR4IejHhCbw3tlOOED55z1Iyp9K';"
                            alt="Logo XINH HOME" 
                            class="h-9 w-auto object-contain bg-white rounded p-0.5"
                        >
                        <div>
                            <span class="block text-base font-extrabold text-white">CÔNG TY TNHH XINH HOME INTERIOR</span>
                            <span class="block text-xs text-amber-400">NỘI THẤT & THIẾT BỊ BẾP XINH HOME</span>
                        </div>
                    </div>
                    <p class="text-xs text-gray-400 leading-relaxed">
                        Đơn vị chuyên Thiết kế – Thi công Nội thất trọn gói và Tủ bếp – Thiết bị nhà bếp chính hãng tại Đà Nẵng & miền Trung.
                    </p>
                    <ul class="space-y-1.5 text-xs text-gray-300">
                        <li><i class="fa-solid fa-location-dot text-amber-400 w-4"></i> <strong>Địa chỉ:</strong> 51 Trần Đại Nghĩa, Ngũ Hành Sơn, Đà Nẵng</li>
                        <li><i class="fa-solid fa-phone-volume text-amber-400 w-4"></i> <strong>Hotline / Zalo:</strong> <a href="tel:0905060839" class="text-amber-400 font-bold hover:underline">0905.060.839</a></li>
                        <li><i class="fa-solid fa-globe text-amber-400 w-4"></i> <strong>Website:</strong> <a href="https://xinhhome.com" class="hover:text-white">xinhhome.com</a></li>
                        <li><i class="fa-solid fa-hashtag text-amber-400 w-4"></i> <strong>Mã số thuế:</strong> 0402337719</li>
                    </ul>
                </div>

                <!-- Cột 2: Danh mục dịch vụ -->
                <div class="lg:col-span-4 space-y-2">
                    <h4 class="text-sm font-bold uppercase text-white tracking-wider">Danh Mục Dịch Vụ & Sản Phẩm</h4>
                    <ul class="grid grid-cols-1 sm:grid-cols-2 gap-1.5 text-xs text-gray-300">
                        <li><a href="#thi-cong-noi-that" class="hover:text-amber-400">› Thi công nội thất chung cư</a></li>
                        <li><a href="#thi-cong-noi-that" class="hover:text-amber-400">› Thi công nội thất nhà phố</a></li>
                        <li><a href="#thi-cong-noi-that" class="hover:text-amber-400">› Thi công nội thất biệt thự</a></li>
                        <li><a href="#thi-cong-noi-that" class="hover:text-amber-400">› Thi công nội thất văn phòng</a></li>
                        <li><a href="#tu-bep-thiet-bi" class="hover:text-amber-400">› Tủ bếp Acrylic bóng gương</a></li>
                        <li><a href="#tu-bep-thiet-bi" class="hover:text-amber-400">› Tủ bếp MDF An Cường</a></li>
                        <li><a href="#tu-bep-thiet-bi" class="hover:text-amber-400">› Tủ bếp nhựa Picomat</a></li>
                        <li><a href="#tu-bep-thiet-bi" class="hover:text-amber-400">› Thiết bị & Phụ kiện bếp</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Chính sách & Kết nối -->
                <div class="lg:col-span-3 space-y-2">
                    <h4 class="text-sm font-bold uppercase text-white tracking-wider">Chính Sách Khách Hàng</h4>
                    <ul class="space-y-1.5 text-xs text-gray-300">
                        <li>› Miễn phí khảo sát & đo đạc tận nơi</li>
                        <li>› Miễn phí thiết kế 3D khi thi công</li>
                        <li>› Bảo hành chính hãng & bảo trì tận tâm</li>
                        <li><a href="https://share.google/smFcyGIks6zzdYzel" target="_blank" rel="noopener noreferrer" class="text-amber-400 hover:underline">› Xem vị trí trên Google Maps</a></li>
                        <li><a href="https://www.facebook.com/profile.php?id=61578493040326" target="_blank" rel="noopener noreferrer" class="text-amber-400 hover:underline">› Kết nối Fanpage Facebook</a></li>
                    </ul>
                </div>
            </div>

            <div class="pt-4 text-center text-xs text-gray-400">
                Copyright © 2026 <strong>XINH HOME (xinhhome.com)</strong> – 51 Trần Đại Nghĩa, Ngũ Hành Sơn, Đà Nẵng. Hotline: 0905.060.839.
            </div>
        </div>
    </footer>

    <!-- ==========================================
         CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
         Tương thích hoàn hảo trên cả máy tính và điện thoại, không gây tràn viền
         ========================================== -->
    <div class="fixed bottom-3 right-3 z-50 flex flex-col items-end gap-2.5">
        <!-- Nút Zalo nổi bật -->
        <a href="https://zalo.me/0905060839" target="_blank" rel="noopener noreferrer" class="flex items-center gap-2 px-3 py-2 rounded-full bg-sky-500 hover:bg-sky-600 text-white shadow-lg transition transform hover:-translate-y-0.5">
            <span class="w-7 h-7 rounded-full bg-white text-sky-600 font-extrabold text-xs flex items-center justify-center shrink-0">Zalo</span>
            <span class="text-xs font-bold pr-1">Chat Zalo</span>
        </a>

        <!-- Nút Facebook Fanpage nổi bật -->
        <a href="https://www.facebook.com/profile.php?id=61578493040326" target="_blank" rel="noopener noreferrer" class="flex items-center gap-2 px-3 py-2 rounded-full bg-blue-600 hover:bg-blue-700 text-white shadow-lg transition transform hover:-translate-y-0.5">
            <span class="w-7 h-7 rounded-full bg-white text-blue-600 flex items-center justify-center shrink-0">
                <i class="fa-brands fa-facebook-f text-sm"></i>
            </span>
            <span class="text-xs font-bold pr-1">Facebook</span>
        </a>

        <!-- Nút Hotline nổi bật -->
        <a href="tel:0905060839" class="pulse-btn flex items-center gap-2 px-3.5 py-2 rounded-full bg-brand-primary hover:bg-brand-dark text-white shadow-xl transition">
            <span class="w-7 h-7 rounded-full bg-white text-brand-primary flex items-center justify-center shrink-0">
                <i class="fa-solid fa-phone-volume text-xs"></i>
            </span>
            <span class="text-xs font-extrabold pr-1">0905.060.839</span>
        </a>
    </div>

    <!-- ==========================================
         MODAL PHÓNG TO ẢNH THỰC TẾ KHI CLICK
         ========================================== -->
    <div id="image-modal" class="fixed inset-0 z-50 hidden bg-black/80 backdrop-blur-sm flex items-center justify-center p-4" onclick="closeImageModal()">
        <div class="relative max-w-3xl w-full bg-white rounded-xl overflow-hidden shadow-2xl" onclick="event.stopPropagation()">
            <div class="flex items-center justify-between px-4 py-2.5 bg-brand-charcoal text-white">
                <h4 id="modal-caption" class="text-xs sm:text-sm font-bold">Hình ảnh thực tế XINH HOME</h4>
                <button onclick="closeImageModal()" class="w-7 h-7 rounded-full bg-white/10 hover:bg-white/20 flex items-center justify-center text-white">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div class="p-2 bg-stone-900 flex items-center justify-center">
                <img id="modal-img" src="" alt="Ảnh phóng to" class="max-h-[75vh] w-auto object-contain rounded">
            </div>
        </div>
    </div>

    <!-- ==========================================
         JAVASCRIPT XỬ LÝ SLIDER BANNER, LỌC DANH MỤC & FORM BÁO GIÁ
         ========================================== -->
    <script>
        // 1. Menu Điện Thoại
        const mobileMenuBtn = document.getElementById('mobile-menu-btn');
        const mobileMenuPanel = document.getElementById('mobile-menu-panel');
        if (mobileMenuBtn && mobileMenuPanel) {
            mobileMenuBtn.addEventListener('click', () => {
                mobileMenuPanel.classList.toggle('hidden');
            });
            document.querySelectorAll('.mobile-nav-link').forEach(link => {
                link.addEventListener('click', () => {
                    mobileMenuPanel.classList.add('hidden');
                });
            });
        }

        // 2. Slider 2 Banner tự trượt chuyên nghiệp
        let currentBanner = 0;
        const slides = document.querySelectorAll('.banner-slide');
        const dot0 = document.getElementById('dot-0');
        const dot1 = document.getElementById('dot-1');
        let bannerInterval;

        function showBanner(index) {
            currentBanner = (index + slides.length) % slides.length;
            slides.forEach((slide, idx) => {
                if (idx === currentBanner) {
                    slide.classList.add('active');
                } else {
                    slide.classList.remove('active');
                }
            });
            if (dot0 && dot1) {
                dot0.className = currentBanner === 0 ? 'w-6 h-2 rounded-full bg-amber-400 transition-all' : 'w-2.5 h-2 rounded-full bg-white/60 transition-all';
                dot1.className = currentBanner === 1 ? 'w-6 h-2 rounded-full bg-amber-400 transition-all' : 'w-2.5 h-2 rounded-full bg-white/60 transition-all';
            }
        }

        function nextBanner() {
            showBanner(currentBanner + 1);
            resetBannerTimer();
        }

        function prevBanner() {
            showBanner(currentBanner - 1);
            resetBannerTimer();
        }

        function goToBanner(index) {
            showBanner(index);
            resetBannerTimer();
        }

        function resetBannerTimer() {
            clearInterval(bannerInterval);
            bannerInterval = setInterval(() => {
                showBanner(currentBanner + 1);
            }, 5000);
        }

        // 3. Lọc Danh Mục Sản Phẩm & Thi Công Nội Thất
        function filterServiceCategory(category) {
            const cards = document.querySelectorAll('.product-card');
            const buttons = document.querySelectorAll('[data-cat-btn]');

            buttons.forEach(btn => {
                if (btn.getAttribute('data-cat-btn') === category) {
                    btn.classList.add('active');
                } else {
                    btn.classList.remove('active');
                }
            });

            cards.forEach(card => {
                const cats = card.getAttribute('data-category') || '';
                if (category === 'all' || cats.includes(category)) {
                    card.classList.remove('hidden');
                } else {
                    card.classList.add('hidden');
                }
            });
        }

        // 4. Lọc Danh Mục Dự Án Đà Nẵng
        function filterProjectCategory(projCat) {
            const cards = document.querySelectorAll('.project-card');
            const buttons = document.querySelectorAll('[data-proj-btn]');

            buttons.forEach(btn => {
                if (btn.getAttribute('data-proj-btn') === projCat) {
                    btn.classList.add('active');
                } else {
                    btn.classList.remove('active');
                }
            });

            cards.forEach(card => {
                const cats = card.getAttribute('data-proj') || '';
                if (projCat === 'all' || cats.includes(projCat)) {
                    card.classList.remove('hidden');
                } else {
                    card.classList.add('hidden');
                }
            });
        }

        // 5. Lọc Danh Mục Bài Viết Trang Chủ
        function filterBlogCategory(blogCat) {
            const cards = document.querySelectorAll('.blog-card');
            const buttons = document.querySelectorAll('[data-blog-btn]');

            buttons.forEach(btn => {
                if (btn.getAttribute('data-blog-btn') === blogCat) {
                    btn.classList.add('active');
                } else {
                    btn.classList.remove('active');
                }
            });

            cards.forEach(card => {
                const cats = card.getAttribute('data-blog') || '';
                if (blogCat === 'all' || cats.includes(blogCat)) {
                    card.classList.remove('hidden');
                } else {
                    card.classList.add('hidden');
                }
            });
        }

        // 6. Xử lý gửi Form Yêu Cầu Báo Giá
        function submitQuoteForm(event) {
            event.preventDefault();
            const name = document.getElementById('q-name').value.trim();
            const phone = document.getElementById('q-phone').value.trim();
            const service = document.getElementById('q-service').value;
            const address = document.getElementById('q-address').value.trim() || 'Đà Nẵng';
            const budget = document.getElementById('q-budget').value;
            const successBox = document.getElementById('quote-success');

            if (successBox) {
                successBox.classList.remove('hidden');
                successBox.innerHTML = `
                    <div class="font-bold text-emerald-900 mb-1">
                        <i class="fa-solid fa-circle-check mr-1"></i>Đã tiếp nhận yêu cầu báo giá của quý khách ${name}!
                    </div>
                    <p>Hạng mục: <strong>${service}</strong> (${address} - Ngân sách: ${budget}). Bộ phận kỹ thuật <strong>XINH HOME (0905.060.839)</strong> sẽ liên hệ qua số <strong>${phone}</strong> trong ít phút tới.</p>
                `;
                document.getElementById('quote-form').reset();
            }
        }

        // 7. Xem phóng to ảnh thực tế
        function openImageModal(src, caption) {
            const modal = document.getElementById('image-modal');
            const modalImg = document.getElementById('modal-img');
            const modalCaption = document.getElementById('modal-caption');
            if (modal && modalImg && modalCaption) {
                modalImg.src = src;
                modalCaption.textContent = caption;
                modal.classList.remove('hidden');
            }
        }

        function closeImageModal() {
            const modal = document.getElementById('image-modal');
            if (modal) {
                modal.classList.add('hidden');
            }
        }

        window.onload = function () {
            resetBannerTimer();
        };
    </script>
</body>
</html>
