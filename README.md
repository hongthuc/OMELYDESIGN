<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>CÔNG TY CỔ PHẦN TƯ VẤN XÂY DỰNG OMELY DESIGN - Thiết Kế & Thi Công Nhà Đẹp Đà Nẵng</title>
    <meta name="description" content="CÔNG TY CỔ PHẦN TƯ VẤN XÂY DỰNG OMELY DESIGN (omelydesign.com.com) chuyên tư vấn thiết kế kiến trúc, thi công xây dựng dân dụng trọn gói tại Đà Nẵng. Địa chỉ: H04/41 kiệt 161 Mẹ Suốt, Phường Hòa Khánh, TP. Đà Nẵng. Hotline: 0901.171.182.">

    <!-- Cấu hình Thumbnail là Logo trang web khi gửi link qua Zalo, Facebook, Messenger -->
    <meta property="og:type" content="website">
    <meta property="og:site_name" content="OMELY DESIGN - omelydesign.com.com">
    <meta property="og:url" content="https://omelydesign.com.com/">
    <meta property="og:title" content="CÔNG TY CỔ PHẦN TƯ VẤN XÂY DỰNG OMELY DESIGN | Thiết Kế & Xây Dựng Đà Nẵng">
    <meta property="og:description" content="Tư vấn thiết kế kiến trúc, thi công xây dựng dân dụng trọn gói tại Đà Nẵng. Địa chỉ: H04/41 kiệt 161 Mẹ Suốt, Phường Hòa Khánh, TP. Đà Nẵng - SĐT: 0901.171.182">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/1ZzW9J40JmP6e9PkvNZHnN1YqpimPKLJh">
    <meta property="og:image:secure_url" content="https://lh3.googleusercontent.com/d/1ZzW9J40JmP6e9PkvNZHnN1YqpimPKLJh">
    <meta property="og:image:width" content="800">
    <meta property="og:image:height" content="800">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="CÔNG TY CỔ PHẦN TƯ VẤN XÂY DỰNG OMELY DESIGN">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1ZzW9J40JmP6e9PkvNZHnN1YqpimPKLJh">
    <link rel="icon" href="https://lh3.googleusercontent.com/d/1ZzW9J40JmP6e9PkvNZHnN1YqpimPKLJh" type="image/png">
    <link rel="apple-touch-icon" href="https://lh3.googleusercontent.com/d/1ZzW9J40JmP6e9PkvNZHnN1YqpimPKLJh">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>

    <!-- Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <style>
        /* Chống tràn viền và chống lệch phải tuyệt đối trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden;
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
            scroll-behavior: smooth;
            background-color: #f8fafc;
            color: #1e293b;
        }

        /* Chuẩn khung Container Flatsome (1200px) căn giữa không lệch */
        .ux-container {
            width: 100%;
            max-width: 1200px;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 640px) {
            .ux-container {
                padding-left: 20px;
                padding-right: 20px;
            }
        }

        /* Tiêu đề Section phong cách Flatsome đơn giản */
        .ux-section-title {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 12px;
            margin-bottom: 8px;
        }
        .ux-section-title::before,
        .ux-section-title::after {
            content: "";
            flex: 1;
            max-width: 60px;
            height: 2px;
            background-color: #cbd5e1;
        }

        /* Hiệu ứng mượt cho ảnh sản phẩm / dự án */
        .ux-box-image {
            overflow: hidden;
            background-color: #e2e8f0;
        }
        .ux-box-image img {
            transition: transform 0.45s ease;
        }
        .ux-card:hover .ux-box-image img {
            transform: scale(1.04);
        }

        /* Hiệu ứng nút liên hệ nổi (Zalo, Facebook, Hotline) */
        @keyframes pulseRing {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(220, 38, 38, 0.6); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(220, 38, 38, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(220, 38, 38, 0); }
        }
        @keyframes pulseZalo {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(0, 104, 255, 0.6); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(0, 104, 255, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(0, 104, 255, 0); }
        }
        .floating-hotline {
            animation: pulseRing 2s infinite;
        }
        .floating-zalo {
            animation: pulseZalo 2.2s infinite;
        }
    </style>
</head>
<body class="w-full overflow-x-hidden">

    <!-- ==========================================
         TOP BAR: ĐƠN GIẢN, KHÔNG CÓ TÙY CHỌN UXBUILDER
         ========================================== -->
    <div class="bg-slate-900 text-slate-200 text-xs py-2 border-b border-slate-800 w-full">
        <div class="ux-container flex flex-col sm:flex-row items-center justify-between gap-1 text-center sm:text-left">
            <div class="font-medium break-words max-w-full">
                <span>CÔNG TY CỔ PHẦN TƯ VẤN XÂY DỰNG OMELY DESIGN</span>
                <span class="hidden md:inline mx-2 text-slate-600">|</span>
                <span class="hidden md:inline text-amber-400">omelydesign.com.com</span>
            </div>
            <div class="text-slate-300 break-words max-w-full">
                <i class="fa-solid fa-location-dot text-amber-400 mr-1"></i>
                <span>H04/41 kiệt 161 Mẹ Suốt, Phường Hòa Khánh, TP. Đà Nẵng</span>
            </div>
        </div>
    </div>

    <!-- ==========================================
         HEADER FLATSOME: KHÔNG ĐỂ NÚT GỌI NGAY ĐỂ TRÁNH TRÀN VIỀN
         ========================================== -->
    <header id="header" class="bg-white sticky top-0 z-40 shadow-sm border-b border-slate-200 w-full">
        <div class="ux-container h-16 sm:h-20 flex items-center justify-between gap-2">
            <!-- Logo & Tên Công Ty -->
            <a href="#trang-chu" class="flex items-center gap-2.5 min-w-0 max-w-[82%] sm:max-w-none">
                <img 
                    src="https://lh3.googleusercontent.com/d/1ZzW9J40JmP6e9PkvNZHnN1YqpimPKLJh" 
                    data-drive-id="1ZzW9J40JmP6e9PkvNZHnN1YqpimPKLJh"
                    onerror="handleDriveImgError(this, 'OMELY+LOGO')"
                    alt="Logo Công Ty Cổ Phần Tư Vấn Xây Dựng Omely Design" 
                    class="w-11 h-11 sm:w-14 sm:h-14 object-contain rounded-lg border border-slate-100 bg-white shrink-0"
                >
                <div class="min-w-0">
                    <span class="block text-sm sm:text-lg font-extrabold text-slate-900 tracking-tight leading-tight break-words">
                        OMELY DESIGN
                    </span>
                    <span class="block text-[11px] sm:text-xs text-slate-500 font-medium leading-tight break-words">
                        omelydesign.com.com
                    </span>
                </div>
            </a>

            <!-- Menu Máy Tính (Desktop Navigation) -->
            <nav class="hidden lg:flex items-center gap-1 xl:gap-2 text-sm font-semibold text-slate-700">
                <a href="#trang-chu" class="px-3 py-2 rounded-lg hover:bg-slate-100 hover:text-amber-600 transition">Trang Chủ</a>
                <a href="#danh-muc" class="px-3 py-2 rounded-lg hover:bg-slate-100 hover:text-amber-600 transition">Danh Mục Sản Phẩm</a>
                <a href="#dich-vu" class="px-3 py-2 rounded-lg hover:bg-slate-100 hover:text-amber-600 transition">Dịch Vụ</a>
                <a href="#du-an-da-nang" class="px-3 py-2 rounded-lg hover:bg-slate-100 hover:text-amber-600 transition">Dự Án Đà Nẵng</a>
                <a href="#bao-gia" class="px-3 py-2 rounded-lg hover:bg-slate-100 hover:text-amber-600 transition">Báo Giá Thiết Kế</a>
                <a href="#bai-viet" class="px-3 py-2 rounded-lg hover:bg-slate-100 hover:text-amber-600 transition">Kiến Thức Xây Nhà</a>
                <a href="#lien-he-ban-do" class="px-3 py-2 rounded-lg hover:bg-slate-100 hover:text-amber-600 transition">Liên Hệ</a>
            </nav>

            <!-- Nút Mở Menu Điện Thoại (Không để nút gọi ngay trên Header) -->
            <button 
                id="mobile-menu-btn" 
                type="button"
                aria-label="Mở danh mục menu"
                class="lg:hidden p-2.5 rounded-lg text-slate-700 hover:bg-slate-100 border border-slate-200 shrink-0"
            >
                <i id="mobile-menu-icon" class="fa-solid fa-bars text-lg"></i>
            </button>
        </div>

        <!-- Menu Điện Thoại Mở Rộng (Tối ưu gọn gàng, không tràn viền) -->
        <div id="mobile-menu-dropdown" class="hidden lg:hidden bg-white border-t border-slate-200 w-full">
            <div class="ux-container py-3 flex flex-col divide-y divide-slate-100 text-sm font-semibold text-slate-700">
                <a href="#trang-chu" class="mobile-nav-link py-2.5 hover:text-amber-600">Trang Chủ</a>
                <a href="#danh-muc" class="mobile-nav-link py-2.5 hover:text-amber-600">Danh Mục Sản Phẩm (Nhà Cấp 4, 2-4 Tầng, Nhà Vườn)</a>
                <a href="#dich-vu" class="mobile-nav-link py-2.5 hover:text-amber-600">Dịch Vụ Thiết Kế & Thi Công</a>
                <a href="#du-an-da-nang" class="mobile-nav-link py-2.5 hover:text-amber-600">Dự Án Thực Tế Tại Đà Nẵng</a>
                <a href="#bao-gia" class="mobile-nav-link py-2.5 hover:text-amber-600">Form Yêu Cầu & Báo Giá</a>
                <a href="#bai-viet" class="mobile-nav-link py-2.5 hover:text-amber-600">Danh Mục Bài Viết & Kiến Thức</a>
                <a href="#lien-he-ban-do" class="mobile-nav-link py-2.5 hover:text-amber-600">Bản Đồ & Fanpage Liên Hệ</a>
            </div>
        </div>
    </header>

    <!-- ==========================================
         2 ẢNH BANNER NGÀNH XÂY DỰNG DÂN DỤNG TỰ TRƯỢT BẰNG KÍCH THƯỚC
         Tối ưu chữ trên điện thoại không tràn viền
         ========================================== -->
    <section id="trang-chu" class="w-full bg-slate-900 relative overflow-hidden">
        <!-- Khung cố định tỷ lệ và chiều cao bằng nhau tuyệt đối cho cả 2 Banner -->
        <div class="relative w-full h-[270px] sm:h-[380px] md:h-[450px] lg:h-[520px] overflow-hidden">
            
            <!-- SLIDE 1 -->
            <div class="hero-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-100 z-10">
                <img 
                    src="https://lh3.googleusercontent.com/d/1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk" 
                    data-drive-id="1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk"
                    onerror="handleDriveImgError(this, 'BANNER+XAY+DUNG+1')"
                    alt="Banner Thiết Kế Và Thi Công Xây Dựng Dân Dụng Đà Nẵng 01" 
                    class="w-full h-full object-cover object-center"
                >
                <div class="absolute inset-0 bg-gradient-to-r from-slate-950/85 via-slate-900/70 to-slate-900/40"></div>
                <div class="absolute inset-0 flex items-center">
                    <div class="ux-container">
                        <div class="max-w-2xl px-2 sm:px-4">
                            <p class="text-amber-400 text-xs sm:text-sm md:text-base font-bold uppercase tracking-wider mb-1.5 sm:mb-2 break-words">
                                CÔNG TY CỔ PHẦN TƯ VẤN XÂY DỰNG OMELY DESIGN
                            </p>
                            <h1 class="text-white text-lg sm:text-2xl md:text-4xl lg:text-5xl font-extrabold leading-snug sm:leading-tight mb-2 sm:mb-4 break-words">
                                Tư Vấn Thiết Kế & Thi Công Xây Dựng Dân Dụng Đà Nẵng
                            </h1>
                            <p class="text-slate-200 text-xs sm:text-sm md:text-base leading-relaxed mb-4 sm:mb-6 break-words">
                                Giải pháp kiến trúc hiện đại, tối ưu công năng, kết cấu bền vững và dự toán chi phí minh bạch cho mọi công trình nhà phố, biệt thự, nhà vườn tại Đà Nẵng.
                            </p>
                            <div class="flex flex-wrap items-center gap-2 sm:gap-3">
                                <a href="#bao-gia" class="bg-amber-500 hover:bg-amber-600 text-slate-950 font-bold text-xs sm:text-sm px-4 py-2.5 sm:px-6 sm:py-3 rounded-lg transition">
                                    Nhận Báo Giá Ngay
                                </a>
                                <a href="#du-an-da-nang" class="bg-white/15 hover:bg-white/25 text-white border border-white/30 font-semibold text-xs sm:text-sm px-4 py-2.5 sm:px-6 sm:py-3 rounded-lg transition">
                                    Xem Dự Án Thực Tế
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- SLIDE 2 (Cùng kích thước 100% với Slide 1) -->
            <div class="hero-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-0 z-0">
                <img 
                    src="https://lh3.googleusercontent.com/d/1tHGEqsuxKkCkoDofSK_nE70LBMIvGuVW" 
                    data-drive-id="1tHGEqsuxKkCkoDofSK_nE70LBMIvGuVW"
                    onerror="handleDriveImgError(this, 'BANNER+XAY+DUNG+2')"
                    alt="Banner Thi Công Nhà Trọn Gói Chìa Khóa Trao Tay Đà Nẵng 02" 
                    class="w-full h-full object-cover object-center"
                >
                <div class="absolute inset-0 bg-gradient-to-r from-slate-950/85 via-slate-900/70 to-slate-900/40"></div>
                <div class="absolute inset-0 flex items-center">
                    <div class="ux-container">
                        <div class="max-w-2xl px-2 sm:px-4">
                            <p class="text-amber-400 text-xs sm:text-sm md:text-base font-bold uppercase tracking-wider mb-1.5 sm:mb-2 break-words">
                                OMELYDESIGN.COM.COM • HOTLINE: 0901.171.182
                            </p>
                            <h2 class="text-white text-lg sm:text-2xl md:text-4xl lg:text-5xl font-extrabold leading-snug sm:leading-tight mb-2 sm:mb-4 break-words">
                                Xây Nhà Trọn Gói – Cam Kết Tiến Độ & Chất Lượng Công Trình
                            </h2>
                            <p class="text-slate-200 text-xs sm:text-sm md:text-base leading-relaxed mb-4 sm:mb-6 break-words">
                                Đồng hành từ bản vẽ phối cảnh 3D, hồ sơ kỹ thuật thi công đến hoàn thiện thực tế tại Hòa Khánh, Liên Chiểu, Hải Châu, Sơn Trà, Cẩm Lệ, Ngũ Hành Sơn.
                            </p>
                            <div class="flex flex-wrap items-center gap-2 sm:gap-3">
                                <a href="#danh-muc" class="bg-amber-500 hover:bg-amber-600 text-slate-950 font-bold text-xs sm:text-sm px-4 py-2.5 sm:px-6 sm:py-3 rounded-lg transition">
                                    Khám Phá Danh Mục
                                </a>
                                <a href="#lien-he-ban-do" class="bg-white/15 hover:bg-white/25 text-white border border-white/30 font-semibold text-xs sm:text-sm px-4 py-2.5 sm:px-6 sm:py-3 rounded-lg transition">
                                    Địa Chỉ Văn Phòng
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Nút điều hướng chấm tròn dưới Banner -->
            <div class="absolute bottom-3 left-0 right-0 z-20 flex items-center justify-center gap-2">
                <button type="button" onclick="setBannerSlide(0)" aria-label="Banner 1" class="banner-dot w-7 h-2 rounded-full bg-amber-400 transition-all"></button>
                <button type="button" onclick="setBannerSlide(1)" aria-label="Banner 2" class="banner-dot w-2.5 h-2 rounded-full bg-white/60 transition-all"></button>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC SẢN PHẨM (LẤY TỪ WEB MẪU THIETKENHADEPDANANG.COM)
         Tối ưu hiển thị đẹp trên máy tính (6 cột) và điện thoại (2 cột)
         Không để nhãn dán, tên không tràn viền
         ========================================== -->
    <section id="danh-muc" class="py-10 sm:py-14 bg-white border-b border-slate-200 w-full">
        <div class="ux-container">
            <div class="text-center mb-7 sm:mb-10">
                <div class="ux-section-title">
                    <h2 class="text-lg sm:text-2xl md:text-3xl font-extrabold text-slate-900 uppercase tracking-tight">
                        Danh Mục Sản Phẩm Thiết Kế
                    </h2>
                </div>
                <p class="text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto">
                    Hệ thống danh mục mẫu nhà dân dụng tại Đà Nẵng được phân chia khoa học, chọn danh mục để lọc nhanh các công trình thực tế bên dưới.
                </p>
            </div>

            <!-- Grid Danh Mục: 2 cột trên điện thoại, 3 cột trên tablet, 6 cột đều đẹp trên máy tính -->
            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3 sm:gap-4">
                <!-- Danh mục 1: Nhà cấp 4 -->
                <a href="#du-an-da-nang" onclick="filterProjects('Nhà cấp 4')" class="ux-card group bg-slate-50 hover:bg-white rounded-xl border border-slate-200 hover:border-amber-500 hover:shadow-md transition overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1PjtEF4hlMU_42b438GmEQhYZTba75kRJ" 
                            data-drive-id="1PjtEF4hlMU_42b438GmEQhYZTba75kRJ"
                            onerror="handleDriveImgError(this, 'Nha+Cap+4')"
                            alt="Danh mục Nhà cấp 4" 
                            class="w-full h-full object-cover"
                        >
                    </div>
                    <div class="p-3 text-center flex-1 flex flex-col justify-center">
                        <h3 class="text-sm sm:text-base font-bold text-slate-800 group-hover:text-amber-600 whitespace-normal break-words leading-snug">
                            Nhà Cấp 4
                        </h3>
                        <p class="text-xs text-slate-500 mt-1 whitespace-normal break-words">
                            Hiện đại & tối ưu chi phí
                        </p>
                    </div>
                </a>

                <!-- Danh mục 2: Nhà 2 tầng -->
                <a href="#du-an-da-nang" onclick="filterProjects('Nhà 2 tầng')" class="ux-card group bg-slate-50 hover:bg-white rounded-xl border border-slate-200 hover:border-amber-500 hover:shadow-md transition overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1m7VasLcMXKPk2-mSVgIdO3USOnbaZ_KA" 
                            data-drive-id="1m7VasLcMXKPk2-mSVgIdO3USOnbaZ_KA"
                            onerror="handleDriveImgError(this, 'Nha+2+Tang')"
                            alt="Danh mục Nhà 2 tầng" 
                            class="w-full h-full object-cover"
                        >
                    </div>
                    <div class="p-3 text-center flex-1 flex flex-col justify-center">
                        <h3 class="text-sm sm:text-base font-bold text-slate-800 group-hover:text-amber-600 whitespace-normal break-words leading-snug">
                            Nhà 2 Tầng
                        </h3>
                        <p class="text-xs text-slate-500 mt-1 whitespace-normal break-words">
                            Nhà phố trẻ trung, thông thoáng
                        </p>
                    </div>
                </a>

                <!-- Danh mục 3: Nhà 3 tầng -->
                <a href="#du-an-da-nang" onclick="filterProjects('Nhà 3 tầng')" class="ux-card group bg-slate-50 hover:bg-white rounded-xl border border-slate-200 hover:border-amber-500 hover:shadow-md transition overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1ng7_50Be4LsQqNa28KBn8rSCicz40ir9" 
                            data-drive-id="1ng7_50Be4LsQqNa28KBn8rSCicz40ir9"
                            onerror="handleDriveImgError(this, 'Nha+3+Tang')"
                            alt="Danh mục Nhà 3 tầng" 
                            class="w-full h-full object-cover"
                        >
                    </div>
                    <div class="p-3 text-center flex-1 flex flex-col justify-center">
                        <h3 class="text-sm sm:text-base font-bold text-slate-800 group-hover:text-amber-600 whitespace-normal break-words leading-snug">
                            Nhà 3 Tầng
                        </h3>
                        <p class="text-xs text-slate-500 mt-1 whitespace-normal break-words">
                            Đầy đủ tiện nghi gia đình
                        </p>
                    </div>
                </a>

                <!-- Danh mục 4: Nhà 4 tầng -->
                <a href="#du-an-da-nang" onclick="filterProjects('Nhà 4 tầng')" class="ux-card group bg-slate-50 hover:bg-white rounded-xl border border-slate-200 hover:border-amber-500 hover:shadow-md transition overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1m0Hxp_Pf-urM1DxMd9GP-iuahuQfiznS" 
                            data-drive-id="1m0Hxp_Pf-urM1DxMd9GP-iuahuQfiznS"
                            onerror="handleDriveImgError(this, 'Nha+4+Tang')"
                            alt="Danh mục Nhà 4 tầng" 
                            class="w-full h-full object-cover"
                        >
                    </div>
                    <div class="p-3 text-center flex-1 flex flex-col justify-center">
                        <h3 class="text-sm sm:text-base font-bold text-slate-800 group-hover:text-amber-600 whitespace-normal break-words leading-snug">
                            Nhà 4 Tầng
                        </h3>
                        <p class="text-xs text-slate-500 mt-1 whitespace-normal break-words">
                            Nhà ở kết hợp kinh doanh
                        </p>
                    </div>
                </a>

                <!-- Danh mục 5: Nhà vườn -->
                <a href="#du-an-da-nang" onclick="filterProjects('Nhà vườn')" class="ux-card group bg-slate-50 hover:bg-white rounded-xl border border-slate-200 hover:border-amber-500 hover:shadow-md transition overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1stTZuL2puyTkD_2WrDXjg2Yz2NAYyHV3" 
                            data-drive-id="1stTZuL2puyTkD_2WrDXjg2Yz2NAYyHV3"
                            onerror="handleDriveImgError(this, 'Nha+Vuon')"
                            alt="Danh mục Nhà vườn" 
                            class="w-full h-full object-cover"
                        >
                    </div>
                    <div class="p-3 text-center flex-1 flex flex-col justify-center">
                        <h3 class="text-sm sm:text-base font-bold text-slate-800 group-hover:text-amber-600 whitespace-normal break-words leading-snug">
                            Nhà Vườn
                        </h3>
                        <p class="text-xs text-slate-500 mt-1 whitespace-normal break-words">
                            Không gian xanh nghỉ dưỡng
                        </p>
                    </div>
                </a>

                <!-- Danh mục 6: Căn hộ dịch vụ -->
                <a href="#du-an-da-nang" onclick="filterProjects('Căn hộ dịch vụ')" class="ux-card group bg-slate-50 hover:bg-white rounded-xl border border-slate-200 hover:border-amber-500 hover:shadow-md transition overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1-JeFJVOKB9-b8SOJFIxqa-Mk9ctbIraF" 
                            data-drive-id="1-JeFJVOKB9-b8SOJFIxqa-Mk9ctbIraF"
                            onerror="handleDriveImgError(this, 'Can+Ho+Dich+Vu')"
                            alt="Danh mục Căn hộ dịch vụ" 
                            class="w-full h-full object-cover"
                        >
                    </div>
                    <div class="p-3 text-center flex-1 flex flex-col justify-center">
                        <h3 class="text-sm sm:text-base font-bold text-slate-800 group-hover:text-amber-600 whitespace-normal break-words leading-snug">
                            Căn Hộ Dịch Vụ
                        </h3>
                        <p class="text-xs text-slate-500 mt-1 whitespace-normal break-words">
                            Khai thác cho thuê hiệu quả
                        </p>
                    </div>
                </a>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC DỊCH VỤ (LẤY TỪ WEB MẪU - CHIA 2 CỘT TRÊN ĐIỆN THOẠI, 4 CỘT MÁY TÍNH)
         ========================================== -->
    <section id="dich-vu" class="py-10 sm:py-12 bg-slate-50 border-b border-slate-200 w-full">
        <div class="ux-container">
            <div class="text-center mb-7 sm:mb-9">
                <div class="ux-section-title">
                    <h2 class="text-lg sm:text-2xl md:text-3xl font-extrabold text-slate-900 uppercase tracking-tight">
                        Dịch Vụ Tư Vấn & Xây Dựng
                    </h2>
                </div>
                <p class="text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto">
                    Giải pháp đồng bộ từ khâu lên ý tưởng thiết kế kiến trúc đến thi công hoàn thiện công trình thực tế.
                </p>
            </div>

            <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                <div class="bg-white p-4 sm:p-5 rounded-xl border border-slate-200 flex flex-col justify-between">
                    <div>
                        <div class="w-10 h-10 rounded-lg bg-amber-100 text-amber-600 flex items-center justify-center mb-3">
                            <i class="fa-solid fa-compass-drafting text-lg"></i>
                        </div>
                        <h3 class="text-sm sm:text-base font-bold text-slate-900 mb-1.5 whitespace-normal break-words leading-snug">
                            Tư Vấn – Thiết Kế Kiến Trúc & Nội Thất
                        </h3>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed whitespace-normal break-words">
                            Thiết kế mặt bằng công năng, phối cảnh 3D ngoại thất, nội thất và hồ sơ kỹ thuật thi công chi tiết.
                        </p>
                    </div>
                </div>

                <div class="bg-white p-4 sm:p-5 rounded-xl border border-slate-200 flex flex-col justify-between">
                    <div>
                        <div class="w-10 h-10 rounded-lg bg-amber-100 text-amber-600 flex items-center justify-center mb-3">
                            <i class="fa-solid fa-helmet-safety text-lg"></i>
                        </div>
                        <h3 class="text-sm sm:text-base font-bold text-slate-900 mb-1.5 whitespace-normal break-words leading-snug">
                            Thi Công Nhà Trọn Gói Đà Nẵng
                        </h3>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed whitespace-normal break-words">
                            Thi công phần thô và hoàn thiện trọn gói chìa khóa trao tay, kiểm soát chặt chẽ vật tư và tiến độ.
                        </p>
                    </div>
                </div>

                <div class="bg-white p-4 sm:p-5 rounded-xl border border-slate-200 flex flex-col justify-between">
                    <div>
                        <div class="w-10 h-10 rounded-lg bg-amber-100 text-amber-600 flex items-center justify-center mb-3">
                            <i class="fa-solid fa-cubes text-lg"></i>
                        </div>
                        <h3 class="text-sm sm:text-base font-bold text-slate-900 mb-1.5 whitespace-normal break-words leading-snug">
                            Thi Công Nhà Modun Thông Minh
                        </h3>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed whitespace-normal break-words">
                            Giải pháp lắp ghép hiện đại, rút ngắn thời gian thi công, kết cấu linh hoạt và tiết kiệm ngân sách.
                        </p>
                    </div>
                </div>

                <div class="bg-white p-4 sm:p-5 rounded-xl border border-slate-200 flex flex-col justify-between">
                    <div>
                        <div class="w-10 h-10 rounded-lg bg-amber-100 text-amber-600 flex items-center justify-center mb-3">
                            <i class="fa-solid fa-laptop-code text-lg"></i>
                        </div>
                        <h3 class="text-sm sm:text-base font-bold text-slate-900 mb-1.5 whitespace-normal break-words leading-snug">
                            Đào Tạo Thiết Kế Quy Trình SketchUp
                        </h3>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed whitespace-normal break-words">
                            Hướng dẫn dựng hình 3D và triển khai hồ sơ bản vẽ thi công thực chiến theo quy trình chuẩn.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC CÁC DỰ ÁN Ở ĐÀ NẴNG (SỬ DỤNG TOÀN BỘ 19 ẢNH THỰC TẾ)
         - Điện thoại: Chia 2 cột (grid-cols-2)
         - Máy tính: Chia 4 cột (lg:grid-cols-4)
         - Không để nhãn dán ở trang chủ
         - Tên sản phẩm hiển thị đầy đủ, không bị tràn hoặc thiếu chữ
         ========================================== -->
    <section id="du-an-da-nang" class="py-10 sm:py-14 bg-white border-b border-slate-200 w-full">
        <div class="ux-container">
            <div class="text-center mb-6 sm:mb-8">
                <div class="ux-section-title">
                    <h2 class="text-lg sm:text-2xl md:text-3xl font-extrabold text-slate-900 uppercase tracking-tight">
                        Dự Án Thực Tế Tại Đà Nẵng
                    </h2>
                </div>
                <p class="text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto">
                    Tổng hợp 19 hình ảnh công trình thực tế do CÔNG TY CỔ PHẦN TƯ VẤN XÂY DỰNG OMELY DESIGN thiết kế và thi công tại các quận huyện Đà Nẵng.
                </p>
            </div>

            <!-- Thanh lọc danh mục dự án Đà Nẵng (Tối ưu trên cả máy tính và điện thoại) -->
            <div class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-7" id="project-filter-bar">
                <button type="button" onclick="filterProjects('ALL')" data-filter="ALL" class="project-filter-btn bg-slate-900 text-white text-xs sm:text-sm font-semibold px-3.5 py-2 rounded-lg transition">
                    Tất Cả Dự Án (19)
                </button>
                <button type="button" onclick="filterProjects('Nhà cấp 4')" data-filter="Nhà cấp 4" class="project-filter-btn bg-slate-100 hover:bg-slate-200 text-slate-700 text-xs sm:text-sm font-semibold px-3.5 py-2 rounded-lg transition">
                    Nhà Cấp 4
                </button>
                <button type="button" onclick="filterProjects('Nhà 2 tầng')" data-filter="Nhà 2 tầng" class="project-filter-btn bg-slate-100 hover:bg-slate-200 text-slate-700 text-xs sm:text-sm font-semibold px-3.5 py-2 rounded-lg transition">
                    Nhà 2 Tầng
                </button>
                <button type="button" onclick="filterProjects('Nhà 3 tầng')" data-filter="Nhà 3 tầng" class="project-filter-btn bg-slate-100 hover:bg-slate-200 text-slate-700 text-xs sm:text-sm font-semibold px-3.5 py-2 rounded-lg transition">
                    Nhà 3 Tầng
                </button>
                <button type="button" onclick="filterProjects('Nhà 4 tầng')" data-filter="Nhà 4 tầng" class="project-filter-btn bg-slate-100 hover:bg-slate-200 text-slate-700 text-xs sm:text-sm font-semibold px-3.5 py-2 rounded-lg transition">
                    Nhà 4 Tầng
                </button>
                <button type="button" onclick="filterProjects('Nhà vườn')" data-filter="Nhà vườn" class="project-filter-btn bg-slate-100 hover:bg-slate-200 text-slate-700 text-xs sm:text-sm font-semibold px-3.5 py-2 rounded-lg transition">
                    Nhà Vườn
                </button>
                <button type="button" onclick="filterProjects('Căn hộ dịch vụ')" data-filter="Căn hộ dịch vụ" class="project-filter-btn bg-slate-100 hover:bg-slate-200 text-slate-700 text-xs sm:text-sm font-semibold px-3.5 py-2 rounded-lg transition">
                    Căn Hộ Dịch Vụ
                </button>
            </div>

            <!-- Lưới Sản Phẩm / Dự Án: 2 cột trên điện thoại (grid-cols-2), 3 cột tablet, 4 cột máy tính -->
            <div id="projects-grid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5">
                <!-- Đổ dữ liệu 19 công trình thực tế bằng JS để dễ quản lý và lọc nhanh -->
            </div>
        </div>
    </section>

    <!-- ==========================================
         CHỌN DỊCH VỤ THIẾT KẾ NHÀ ĐẸP BẠN NHẬN ĐƯỢC GÌ & QUY TRÌNH 6 BƯỚC (ĐƠN GIẢN HÓA TỪ WEB MẪU)
         ========================================== -->
    <section class="py-10 sm:py-14 bg-slate-50 border-b border-slate-200 w-full">
        <div class="ux-container">
            <div class="text-center mb-7 sm:mb-10">
                <div class="ux-section-title">
                    <h2 class="text-lg sm:text-2xl md:text-3xl font-extrabold text-slate-900 uppercase tracking-tight">
                        Quy Trình Thiết Kế & Thi Công Chuẩn
                    </h2>
                </div>
                <p class="text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto">
                    6 bước làm việc rõ ràng tại OMELY DESIGN giúp khách hàng kiểm soát chất lượng, thẩm mỹ và chi phí xây dựng.
                </p>
            </div>

            <!-- Chia 2 cột trên điện thoại, 3 cột trên máy tính -->
            <div class="grid grid-cols-2 lg:grid-cols-3 gap-3 sm:gap-5">
                <div class="bg-white p-4 sm:p-5 rounded-xl border border-slate-200">
                    <span class="text-xs font-extrabold text-amber-600 uppercase">Bước 01</span>
                    <h3 class="text-sm sm:text-base font-bold text-slate-900 mt-1 mb-1.5 whitespace-normal break-words">
                        Tiếp Nhận Thông Tin
                    </h3>
                    <p class="text-xs sm:text-sm text-slate-600 leading-relaxed whitespace-normal break-words">
                        Khảo sát diện tích thửa đất, hướng nhà, nhu cầu công năng và ngân sách dự kiến tại Đà Nẵng.
                    </p>
                </div>

                <div class="bg-white p-4 sm:p-5 rounded-xl border border-slate-200">
                    <span class="text-xs font-extrabold text-amber-600 uppercase">Bước 02</span>
                    <h3 class="text-sm sm:text-base font-bold text-slate-900 mt-1 mb-1.5 whitespace-normal break-words">
                        Tư Vấn & Báo Giá Thiết Kế
                    </h3>
                    <p class="text-xs sm:text-sm text-slate-600 leading-relaxed whitespace-normal break-words">
                        Định hướng phong cách kiến trúc phù hợp và gửi bảng báo giá chi tiết từng hạng mục.
                    </p>
                </div>

                <div class="bg-white p-4 sm:p-5 rounded-xl border border-slate-200">
                    <span class="text-xs font-extrabold text-amber-600 uppercase">Bước 03</span>
                    <h3 class="text-sm sm:text-base font-bold text-slate-900 mt-1 mb-1.5 whitespace-normal break-words">
                        Ký Hợp Đồng Thiết Kế
                    </h3>
                    <p class="text-xs sm:text-sm text-slate-600 leading-relaxed whitespace-normal break-words">
                        Thống nhất nội dung công việc, tiến độ bàn giao từng giai đoạn và cam kết chất lượng.
                    </p>
                </div>

                <div class="bg-white p-4 sm:p-5 rounded-xl border border-slate-200">
                    <span class="text-xs font-extrabold text-amber-600 uppercase">Bước 04</span>
                    <h3 class="text-sm sm:text-base font-bold text-slate-900 mt-1 mb-1.5 whitespace-normal break-words">
                        Thiết Kế Mặt Bằng & Phối Cảnh 3D
                    </h3>
                    <p class="text-xs sm:text-sm text-slate-600 leading-relaxed whitespace-normal break-words">
                        Lên phương án bố trí công năng tối ưu và dựng phối cảnh 3D ngoại thất, nội thất trực quan.
                    </p>
                </div>

                <div class="bg-white p-4 sm:p-5 rounded-xl border border-slate-200">
                    <span class="text-xs font-extrabold text-amber-600 uppercase">Bước 05</span>
                    <h3 class="text-sm sm:text-base font-bold text-slate-900 mt-1 mb-1.5 whitespace-normal break-words">
                        Triển Khai Hồ Sơ Kỹ Thuật
                    </h3>
                    <p class="text-xs sm:text-sm text-slate-600 leading-relaxed whitespace-normal break-words">
                        Hoàn thiện bản vẽ kết cấu, kiến trúc, hệ thống điện nước (M&E) và dự toán khối lượng vật tư.
                    </p>
                </div>

                <div class="bg-white p-4 sm:p-5 rounded-xl border border-slate-200">
                    <span class="text-xs font-extrabold text-amber-600 uppercase">Bước 06</span>
                    <h3 class="text-sm sm:text-base font-bold text-slate-900 mt-1 mb-1.5 whitespace-normal break-words">
                        Bàn Giao Hồ Sơ & Giám Sát Thi Công
                    </h3>
                    <p class="text-xs sm:text-sm text-slate-600 leading-relaxed whitespace-normal break-words">
                        Bàn giao trọn bộ hồ sơ in ấn, lưu trữ bản mềm và đồng hành giám sát tác giả suốt quá trình xây dựng.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         FORM YÊU CẦU VÀ BÁO GIÁ TRANG CHỦ
         ========================================== -->
    <section id="bao-gia" class="py-10 sm:py-14 bg-white border-b border-slate-200 w-full">
        <div class="ux-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 sm:gap-8 items-start">
                <!-- Cột Thông Tin Báo Giá & Cam Kết (5/12) -->
                <div class="lg:col-span-5 bg-slate-900 text-white p-5 sm:p-7 rounded-2xl">
                    <p class="text-amber-400 text-xs font-bold uppercase tracking-wider mb-1">
                        BÁO GIÁ NHANH CHÓNG & MINH BẠCH
                    </p>
                    <h2 class="text-lg sm:text-2xl font-extrabold leading-snug mb-3 break-words">
                        Đăng Ký Tư Vấn & Nhận Dự Toán Chi Phí Xây Nhà Đà Nẵng
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-300 leading-relaxed mb-5 break-words">
                        Đội ngũ kiến trúc sư và kỹ sư xây dựng của <strong>CÔNG TY CỔ PHẦN TƯ VẤN XÂY DỰNG OMELY DESIGN</strong> sẽ liên hệ tư vấn phương án mặt bằng và báo giá sát thực tế nhất.
                    </p>

                    <div class="space-y-3 text-xs sm:text-sm border-t border-slate-800 pt-4">
                        <div class="flex items-start gap-3">
                            <i class="fa-solid fa-check text-amber-400 mt-1"></i>
                            <span class="break-words">Khảo sát thực tế và tư vấn mặt bằng công năng miễn phí tại Đà Nẵng.</span>
                        </div>
                        <div class="flex items-start gap-3">
                            <i class="fa-solid fa-check text-amber-400 mt-1"></i>
                            <span class="break-words">Dự toán chi tiết từng hạng mục vật tư, cam kết không phát sinh chi phí.</span>
                        </div>
                        <div class="flex items-start gap-3">
                            <i class="fa-solid fa-check text-amber-400 mt-1"></i>
                            <span class="break-words">Hỗ trợ thủ tục xin phép xây dựng và hồ sơ hoàn công trọn gói.</span>
                        </div>
                    </div>

                    <div class="mt-6 pt-4 border-t border-slate-800 space-y-2 text-xs sm:text-sm">
                        <p class="font-semibold text-amber-400 break-words">
                            <i class="fa-solid fa-phone-volume mr-2"></i>Hotline / Zalo: 0901.171.182
                        </p>
                        <p class="text-slate-300 break-words">
                            <i class="fa-solid fa-location-dot mr-2 text-amber-400"></i>Địa chỉ: H04/41 kiệt 161 Mẹ Suốt, Phường Hòa Khánh, Thành phố Đà Nẵng
                        </p>
                        <p class="text-slate-300 break-words">
                            <i class="fa-solid fa-globe mr-2 text-amber-400"></i>Website: omelydesign.com.com
                        </p>
                    </div>
                </div>

                <!-- Cột Form Yêu Cầu & Báo Giá (7/12) -->
                <div class="lg:col-span-7 bg-slate-50 p-5 sm:p-7 rounded-2xl border border-slate-200">
                    <h3 class="text-base sm:text-xl font-extrabold text-slate-900 mb-1 break-words">
                        Form Yêu Cầu Tư Vấn & Báo Giá Thiết Kế - Thi Công
                    </h3>
                    <p class="text-xs sm:text-sm text-slate-500 mb-5 break-words">
                        Quý khách vui lòng điền thông tin công trình bên dưới, chúng tôi sẽ phản hồi ngay trong ngày.
                    </p>

                    <form id="quote-request-form" onsubmit="submitQuoteForm(event)" class="space-y-4">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <div>
                                <label for="customer-name" class="block text-xs sm:text-sm font-semibold text-slate-700 mb-1">
                                    Họ và tên khách hàng <span class="text-red-500">*</span>
                                </label>
                                <input 
                                    id="customer-name" 
                                    type="text" 
                                    required 
                                    placeholder="Nhập họ và tên của bạn" 
                                    class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 bg-white text-sm focus:outline-none focus:border-amber-500"
                                >
                            </div>
                            <div>
                                <label for="customer-phone" class="block text-xs sm:text-sm font-semibold text-slate-700 mb-1">
                                    Số điện thoại / Zalo <span class="text-red-500">*</span>
                                </label>
                                <input 
                                    id="customer-phone" 
                                    type="tel" 
                                    required 
                                    placeholder="Ví dụ: 0901.171.182" 
                                    class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 bg-white text-sm focus:outline-none focus:border-amber-500"
                                >
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <div>
                                <label for="project-category" class="block text-xs sm:text-sm font-semibold text-slate-700 mb-1">
                                    Danh mục công trình quan tâm
                                </label>
                                <select 
                                    id="project-category" 
                                    class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 bg-white text-sm focus:outline-none focus:border-amber-500"
                                >
                                    <option value="Nhà cấp 4">Nhà cấp 4</option>
                                    <option value="Nhà 2 tầng" selected>Nhà phố 2 tầng</option>
                                    <option value="Nhà 3 tầng">Nhà phố 3 tầng</option>
                                    <option value="Nhà 4 tầng">Nhà phố 4 tầng</option>
                                    <option value="Nhà vườn">Biệt thự / Nhà vườn</option>
                                    <option value="Căn hộ dịch vụ">Căn hộ dịch vụ / Nhà trọ</option>
                                    <option value="Thi công nhà Modun thông minh">Thi công nhà Modun thông minh</option>
                                    <option value="Thi công nhà trọn gói">Xây nhà trọn gói chìa khóa trao tay</option>
                                </select>
                            </div>
                            <div>
                                <label for="project-area" class="block text-xs sm:text-sm font-semibold text-slate-700 mb-1">
                                    Diện tích đất & Khu vực tại Đà Nẵng
                                </label>
                                <input 
                                    id="project-area" 
                                    type="text" 
                                    placeholder="VD: 5x20m tại Hòa Khánh, Đà Nẵng" 
                                    class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 bg-white text-sm focus:outline-none focus:border-amber-500"
                                >
                            </div>
                        </div>

                        <div>
                            <label for="project-note" class="block text-xs sm:text-sm font-semibold text-slate-700 mb-1">
                                Yêu cầu công năng & Dự kiến mức đầu tư
                            </label>
                            <textarea 
                                id="project-note" 
                                rows="3" 
                                placeholder="Mô tả số phòng ngủ, phong cách mong muốn hoặc mức kinh phí dự kiến..." 
                                class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 bg-white text-sm focus:outline-none focus:border-amber-500"
                            ></textarea>
                        </div>

                        <button 
                            type="submit" 
                            class="w-full bg-amber-500 hover:bg-amber-600 text-slate-950 font-bold text-sm sm:text-base py-3 px-6 rounded-lg transition shadow-sm"
                        >
                            Gửi Yêu Cầu Tư Vấn & Báo Giá
                        </button>
                    </form>

                    <!-- Hộp thông báo xác nhận gửi form thành công -->
                    <div id="quote-success-box" class="hidden mt-4 p-4 rounded-xl bg-emerald-50 border border-emerald-200 text-emerald-900 text-xs sm:text-sm">
                        <p class="font-bold mb-1">
                            <i class="fa-solid fa-circle-check text-emerald-600 mr-1.5"></i>Đã tiếp nhận yêu cầu báo giá thành công!
                        </p>
                        <p id="quote-success-detail" class="text-emerald-800 break-words"></p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC CÁC BÀI VIẾT & KIẾN THỨC XÂY NHÀ TRANG CHỦ
         - Chia 2 cột trên điện thoại, 4 cột trên máy tính
         - Không để nhãn dán, tên bài viết đầy đủ không tràn viền
         ========================================== -->
    <section id="bai-viet" class="py-10 sm:py-14 bg-slate-50 border-b border-slate-200 w-full">
        <div class="ux-container">
            <div class="text-center mb-6 sm:mb-8">
                <div class="ux-section-title">
                    <h2 class="text-lg sm:text-2xl md:text-3xl font-extrabold text-slate-900 uppercase tracking-tight">
                        Danh Mục Bài Viết & Kiến Thức Xây Nhà
                    </h2>
                </div>
                <p class="text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto">
                    Cẩm nang kinh nghiệm thiết kế nhà đẹp, tối ưu công năng, dự toán chi phí và kiến thức SketchUp thực tế.
                </p>
            </div>

            <!-- Danh mục bài viết (Filter) -->
            <div class="flex flex-wrap items-center justify-center gap-2 mb-7">
                <button type="button" onclick="filterPosts('ALL')" data-post-filter="ALL" class="post-filter-btn bg-slate-900 text-white text-xs sm:text-sm font-semibold px-3.5 py-2 rounded-lg transition">
                    Tất Cả Bài Viết
                </button>
                <button type="button" onclick="filterPosts('Kiến thức xây nhà')" data-post-filter="Kiến thức xây nhà" class="post-filter-btn bg-white hover:bg-slate-200 text-slate-700 border border-slate-200 text-xs sm:text-sm font-semibold px-3.5 py-2 rounded-lg transition">
                    Kiến Thức Xây Nhà
                </button>
                <button type="button" onclick="filterPosts('Nội thất & Công năng')" data-post-filter="Nội thất & Công năng" class="post-filter-btn bg-white hover:bg-slate-200 text-slate-700 border border-slate-200 text-xs sm:text-sm font-semibold px-3.5 py-2 rounded-lg transition">
                    Nội Thất & Công Năng
                </button>
                <button type="button" onclick="filterPosts('Kiến thức SketchUp')" data-post-filter="Kiến thức SketchUp" class="post-filter-btn bg-white hover:bg-slate-200 text-slate-700 border border-slate-200 text-xs sm:text-sm font-semibold px-3.5 py-2 rounded-lg transition">
                    Kiến Thức SketchUp
                </button>
            </div>

            <!-- Grid Bài Viết: 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div id="posts-grid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                <!-- Đổ danh sách bài viết bằng JS -->
            </div>
        </div>
    </section>

    <!-- ==========================================
         BẢN ĐỒ GOOGLE MAP & FANPAGE FACEBOOK NGOÀI TRANG CHỦ
         Địa chỉ: H04/41 kiệt 161 Mẹ Suốt, Phường Hòa Khánh, Thành phố Đà Nẵng
         ========================================== -->
    <section id="lien-he-ban-do" class="py-10 sm:py-14 bg-white border-b border-slate-200 w-full">
        <div class="ux-container">
            <div class="text-center mb-7 sm:mb-10">
                <div class="ux-section-title">
                    <h2 class="text-lg sm:text-2xl md:text-3xl font-extrabold text-slate-900 uppercase tracking-tight">
                        Bản Đồ Chỉ Đường & Fanpage Chính Thức
                    </h2>
                </div>
                <p class="text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto">
                    Kết nối trực tiếp với CÔNG TY CỔ PHẦN TƯ VẤN XÂY DỰNG OMELY DESIGN tại văn phòng Hòa Khánh, Đà Nẵng hoặc qua Fanpage chính thức.
                </p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
                <!-- Cột Google Map ngoài trang chủ (7/12) -->
                <div class="lg:col-span-7 bg-slate-50 rounded-2xl border border-slate-200 overflow-hidden flex flex-col">
                    <div class="p-4 sm:p-5 border-b border-slate-200 bg-white flex flex-col sm:flex-row sm:items-center justify-between gap-2">
                        <div>
                            <h3 class="text-sm sm:text-base font-extrabold text-slate-900 break-words">
                                <i class="fa-solid fa-map-location-dot text-amber-500 mr-1.5"></i>Vị Trí Google Map Văn Phòng OMELY DESIGN
                            </h3>
                            <p class="text-xs sm:text-sm text-slate-600 mt-0.5 break-words">
                                H04/41 kiệt 161 Mẹ Suốt, Phường Hòa Khánh, Thành phố Đà Nẵng
                            </p>
                        </div>
                        <a 
                            href="https://www.google.com/maps/search/?api=1&query=H04%2F41+ki%E1%BB%87t+161+M%E1%BA%B9+Su%E1%BB%91t%2C+H%C3%B2a+Kh%C3%A1nh%2C+%C4%90%C3%A0+N%E1%BA%B5ng" 
                            target="_blank" 
                            rel="noopener noreferrer"
                            class="inline-flex items-center justify-center bg-slate-900 hover:bg-slate-800 text-white text-xs font-semibold px-3.5 py-2 rounded-lg shrink-0 transition"
                        >
                            <i class="fa-solid fa-diamond-turn-right mr-1.5 text-amber-400"></i>Mở Bản Đồ Lớn
                        </a>
                    </div>
                    <div class="w-full h-[280px] sm:h-[340px] bg-slate-200 flex-1">
                        <iframe 
                            title="Google Map CÔNG TY CỔ PHẦN TƯ VẤN XÂY DỰNG OMELY DESIGN"
                            src="https://maps.google.com/maps?q=161%20M%E1%BA%B9%20Su%E1%BB%91t,%20H%C3%B2a%20Kh%C3%A1nh,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed" 
                            class="w-full h-full border-0" 
                            loading="lazy" 
                            referrerpolicy="no-referrer-when-downgrade"
                        ></iframe>
                    </div>
                </div>

                <!-- Cột Fanpage Facebook ngoài trang chủ (5/12) -->
                <div class="lg:col-span-5 bg-slate-50 rounded-2xl border border-slate-200 overflow-hidden flex flex-col justify-between">
                    <div class="p-4 sm:p-5 border-b border-slate-200 bg-white">
                        <h3 class="text-sm sm:text-base font-extrabold text-slate-900 break-words">
                            <i class="fa-brands fa-facebook text-blue-600 mr-1.5"></i>Fanpage Facebook Chính Thức
                        </h3>
                        <p class="text-xs sm:text-sm text-slate-600 mt-0.5 break-words">
                            Theo dõi hình ảnh công trình thi công thực tế cập nhật hàng ngày.
                        </p>
                    </div>

                    <!-- Khung hiển thị Fanpage trực quan ngoài trang chủ -->
                    <div class="p-4 sm:p-5 flex-1 flex flex-col justify-between gap-4">
                        <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm">
                            <!-- Ảnh bìa Fanpage -->
                            <div class="relative h-32 sm:h-36 bg-slate-900 overflow-hidden">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1cmI83UnySYJ5Zt1I8A0kB0n94W4XgXgi" 
                                    data-drive-id="1cmI83UnySYJ5Zt1I8A0kB0n94W4XgXgi"
                                    onerror="handleDriveImgError(this, 'FANPAGE+OMELY+DESIGN')"
                                    alt="Ảnh bìa Fanpage Omely Design" 
                                    class="w-full h-full object-cover opacity-80"
                                >
                                <div class="absolute inset-0 bg-gradient-to-t from-slate-950/90 via-slate-900/40 to-transparent"></div>
                                <div class="absolute bottom-3 left-3 right-3 flex items-center gap-3">
                                    <img 
                                        src="https://lh3.googleusercontent.com/d/1ZzW9J40JmP6e9PkvNZHnN1YqpimPKLJh" 
                                        data-drive-id="1ZzW9J40JmP6e9PkvNZHnN1YqpimPKLJh"
                                        onerror="handleDriveImgError(this, 'LOGO')"
                                        alt="Logo Fanpage Omely Design" 
                                        class="w-12 h-12 rounded-lg bg-white p-1 object-contain border border-white shadow shrink-0"
                                    >
                                    <div class="min-w-0 text-white">
                                        <h4 class="text-xs sm:text-sm font-bold leading-snug break-words">
                                            CÔNG TY CỔ PHẦN TƯ VẤN XÂY DỰNG OMELY DESIGN
                                        </h4>
                                        <p class="text-[11px] text-slate-300">
                                            Thiết kế & Thi công xây dựng Đà Nẵng
                                        </p>
                                    </div>
                                </div>
                            </div>

                            <!-- Nội dung Fanpage -->
                            <div class="p-3.5 sm:p-4 space-y-3 text-xs sm:text-sm">
                                <div class="flex flex-wrap items-center justify-between gap-2">
                                    <span class="text-slate-600">
                                        <i class="fa-solid fa-phone text-amber-500 mr-1"></i>0901.171.182
                                    </span>
                                    <span class="text-slate-600">
                                        <i class="fa-solid fa-globe text-amber-500 mr-1"></i>omelydesign.com.com
                                    </span>
                                </div>
                                <p class="text-xs text-slate-600 leading-relaxed break-words">
                                    Chuyên tư vấn thiết kế nhà phố, biệt thự, nhà cấp 4, nhà vườn, căn hộ dịch vụ và thi công trọn gói tại Đà Nẵng.
                                </p>
                                <div class="grid grid-cols-2 gap-2 pt-1">
                                    <a 
                                        href="https://facebook.com" 
                                        target="_blank" 
                                        rel="noopener noreferrer"
                                        class="bg-blue-600 hover:bg-blue-700 text-white font-semibold text-xs py-2.5 px-3 rounded-lg text-center transition"
                                    >
                                        <i class="fa-brands fa-facebook-f mr-1"></i>Theo Dõi Trang
                                    </a>
                                    <a 
                                        href="https://zalo.me/0901171182" 
                                        target="_blank" 
                                        rel="noopener noreferrer"
                                        class="bg-slate-100 hover:bg-slate-200 text-slate-800 font-semibold text-xs py-2.5 px-3 rounded-lg text-center transition"
                                    >
                                        <i class="fa-solid fa-comment-dots text-blue-600 mr-1"></i>Nhắn Tin Tư Vấn
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         FOOTER CHUẨN FLATSOME ĐƠN GIẢN, RÕ RÀNG
         ========================================== -->
    <footer class="bg-slate-900 text-slate-300 pt-10 pb-24 sm:pb-12 border-t border-slate-800 w-full">
        <div class="ux-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-7 pb-8 border-b border-slate-800">
                <!-- Cột 1: Thông tin công ty -->
                <div>
                    <div class="flex items-center gap-3 mb-3">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1ZzW9J40JmP6e9PkvNZHnN1YqpimPKLJh" 
                            data-drive-id="1ZzW9J40JmP6e9PkvNZHnN1YqpimPKLJh"
                            onerror="handleDriveImgError(this, 'LOGO')"
                            alt="Logo Omely Design" 
                            class="w-12 h-12 rounded-lg bg-white p-1 object-contain shrink-0"
                        >
                        <div>
                            <h3 class="text-sm font-extrabold text-white leading-snug break-words">
                                OMELY DESIGN
                            </h3>
                            <p class="text-xs text-amber-400">omelydesign.com.com</p>
                        </div>
                    </div>
                    <p class="text-xs sm:text-sm font-bold text-white mb-2 break-words">
                        CÔNG TY CỔ PHẦN TƯ VẤN XÂY DỰNG OMELY DESIGN
                    </p>
                    <ul class="space-y-2 text-xs sm:text-sm text-slate-300">
                        <li class="break-words">
                            <i class="fa-solid fa-location-dot text-amber-400 mr-2"></i>Địa chỉ: H04/41 kiệt 161 Mẹ Suốt, Phường Hòa Khánh, Thành phố Đà Nẵng
                        </li>
                        <li class="break-words">
                            <i class="fa-solid fa-phone text-amber-400 mr-2"></i>Số điện thoại: <a href="tel:0901171182" class="text-white font-semibold hover:text-amber-400">0901.171.182</a>
                        </li>
                        <li class="break-words">
                            <i class="fa-solid fa-globe text-amber-400 mr-2"></i>Website: omelydesign.com.com
                        </li>
                    </ul>
                </div>

                <!-- Cột 2: Danh mục sản phẩm -->
                <div>
                    <h4 class="text-sm font-extrabold text-white uppercase tracking-wider mb-3">
                        Danh Mục Sản Phẩm
                    </h4>
                    <ul class="space-y-2 text-xs sm:text-sm">
                        <li><a href="#du-an-da-nang" onclick="filterProjects('Nhà cấp 4')" class="hover:text-amber-400 transition">Thiết kế & Thi công Nhà cấp 4</a></li>
                        <li><a href="#du-an-da-nang" onclick="filterProjects('Nhà 2 tầng')" class="hover:text-amber-400 transition">Thiết kế & Thi công Nhà 2 tầng</a></li>
                        <li><a href="#du-an-da-nang" onclick="filterProjects('Nhà 3 tầng')" class="hover:text-amber-400 transition">Thiết kế & Thi công Nhà 3 tầng</a></li>
                        <li><a href="#du-an-da-nang" onclick="filterProjects('Nhà 4 tầng')" class="hover:text-amber-400 transition">Thiết kế & Thi công Nhà 4 tầng</a></li>
                        <li><a href="#du-an-da-nang" onclick="filterProjects('Nhà vườn')" class="hover:text-amber-400 transition">Thiết kế & Thi công Nhà vườn</a></li>
                        <li><a href="#du-an-da-nang" onclick="filterProjects('Căn hộ dịch vụ')" class="hover:text-amber-400 transition">Thiết kế Căn hộ dịch vụ Đà Nẵng</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Dịch vụ thiết kế & xây dựng -->
                <div>
                    <h4 class="text-sm font-extrabold text-white uppercase tracking-wider mb-3">
                        Dịch Vụ Chính
                    </h4>
                    <ul class="space-y-2 text-xs sm:text-sm">
                        <li><a href="#dich-vu" class="hover:text-amber-400 transition">Tư vấn – Thiết kế kiến trúc</a></li>
                        <li><a href="#dich-vu" class="hover:text-amber-400 transition">Thi công xây nhà trọn gói</a></li>
                        <li><a href="#dich-vu" class="hover:text-amber-400 transition">Thi công nhà Modun thông minh</a></li>
                        <li><a href="#dich-vu" class="hover:text-amber-400 transition">Đào tạo thiết kế quy trình SketchUp</a></li>
                        <li><a href="#bao-gia" class="hover:text-amber-400 transition">Dự toán chi phí xây dựng Đà Nẵng</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Khu vực phục vụ tại Đà Nẵng -->
                <div>
                    <h4 class="text-sm font-extrabold text-white uppercase tracking-wider mb-3">
                        Khu Vực Thi Công Đà Nẵng
                    </h4>
                    <ul class="space-y-2 text-xs sm:text-sm">
                        <li>Thiết kế nhà đẹp Hòa Khánh – Liên Chiểu</li>
                        <li>Thiết kế nhà đẹp Hải Châu</li>
                        <li>Thiết kế nhà đẹp Sơn Trà</li>
                        <li>Thiết kế nhà đẹp Ngũ Hành Sơn</li>
                        <li>Thiết kế nhà đẹp Cẩm Lệ – Hòa Xuân</li>
                        <li>Thiết kế nhà đẹp Thanh Khê</li>
                    </ul>
                </div>
            </div>

            <div class="pt-6 text-center text-xs text-slate-400 break-words">
                © Bản quyền thuộc về <strong>CÔNG TY CỔ PHẦN TƯ VẤN XÂY DỰNG OMELY DESIGN</strong> (omelydesign.com.com) • Địa chỉ: H04/41 kiệt 161 Mẹ Suốt, Phường Hòa Khánh, Thành phố Đà Nẵng • Hotline: 0901.171.182
            </div>
        </div>
    </footer>

    <!-- ==========================================
         CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE 0901.171.182
         Đặt gọn gàng bên trái/phải không gây tràn viền
         ========================================== -->
    <div class="fixed bottom-4 left-3 sm:left-5 z-50 flex flex-col gap-2.5">
        <!-- Nút Zalo nổi bật -->
        <a 
            href="https://zalo.me/0901171182" 
            target="_blank" 
            rel="noopener noreferrer"
            aria-label="Chat Zalo 0901.171.182"
            class="floating-zalo flex items-center gap-2 bg-[#0068ff] hover:bg-blue-700 text-white font-bold text-xs sm:text-sm px-3.5 py-2.5 rounded-full shadow-lg transition"
        >
            <span class="w-6 h-6 rounded-full bg-white text-[#0068ff] flex items-center justify-center font-extrabold text-xs shrink-0">Z</span>
            <span>Chat Zalo</span>
        </a>

        <!-- Nút Facebook nổi bật -->
        <a 
            href="#lien-he-ban-do" 
            aria-label="Fanpage Facebook Omely Design"
            class="flex items-center gap-2 bg-[#1877f2] hover:bg-blue-800 text-white font-bold text-xs sm:text-sm px-3.5 py-2.5 rounded-full shadow-lg transition"
        >
            <i class="fa-brands fa-facebook-f w-6 h-6 rounded-full bg-white text-[#1877f2] flex items-center justify-center text-xs shrink-0"></i>
            <span>Facebook</span>
        </a>

        <!-- Nút Hotline nổi bật -->
        <a 
            href="tel:0901171182" 
            aria-label="Gọi Hotline 0901.171.182"
            class="floating-hotline flex items-center gap-2 bg-red-600 hover:bg-red-700 text-white font-bold text-xs sm:text-sm px-3.5 py-2.5 rounded-full shadow-lg transition"
        >
            <i class="fa-solid fa-phone-volume w-6 h-6 rounded-full bg-white text-red-600 flex items-center justify-center text-xs shrink-0"></i>
            <span>0901.171.182</span>
        </a>
    </div>

    <!-- ==========================================
         MODAL XEM CHI TIẾT ẢNH CÔNG TRÌNH THỰC TẾ
         ========================================== -->
    <div id="project-modal" class="fixed inset-0 z-50 hidden bg-slate-950/80 flex items-center justify-center p-3 sm:p-6">
        <div class="bg-white rounded-2xl max-w-3xl w-full overflow-hidden shadow-2xl border border-slate-200">
            <div class="flex items-center justify-between px-4 py-3 border-b border-slate-200">
                <h3 id="modal-project-title" class="text-sm sm:text-base font-extrabold text-slate-900 break-words pr-2">
                    Chi tiết dự án
                </h3>
                <button type="button" onclick="closeProjectModal()" class="w-8 h-8 rounded-lg bg-slate-100 hover:bg-slate-200 text-slate-700 flex items-center justify-center shrink-0">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div class="bg-slate-900 max-h-[65vh] overflow-hidden flex items-center justify-center">
                <img id="modal-project-img" src="" alt="Ảnh thực tế công trình" class="w-full max-h-[65vh] object-contain">
            </div>
            <div class="p-4 sm:p-5 flex flex-col sm:flex-row sm:items-center justify-between gap-3 bg-white">
                <div class="text-xs sm:text-sm text-slate-600 break-words">
                    <span id="modal-project-meta" class="font-semibold text-slate-800"></span> • Tư vấn & Thi công: <strong>OMELY DESIGN (0901.171.182)</strong>
                </div>
                <a href="#bao-gia" onclick="closeProjectModal()" class="bg-amber-500 hover:bg-amber-600 text-slate-950 font-bold text-xs sm:text-sm px-4 py-2.5 rounded-lg text-center shrink-0 transition">
                    Yêu Cầu Báo Giá Mẫu Này
                </a>
            </div>
        </div>
    </div>

    <!-- ==========================================
         JAVASCRIPT XỬ LÝ DỮ LIỆU 19 ẢNH THỰC TẾ, SLIDER BANNER & LỌC DANH MỤC
         ========================================== -->
    <script>
        // Hàm dự phòng tự động chuyển đổi sang link Thumbnail Google Drive nếu trình duyệt chặn lh3
        function handleDriveImgError(imgEl, fallbackText) {
            const driveId = imgEl.getAttribute('data-drive-id');
            const triedThumb = imgEl.getAttribute('data-tried-thumb');
            if (driveId && !triedThumb) {
                imgEl.setAttribute('data-tried-thumb', 'true');
                imgEl.src = 'https://drive.google.com/thumbnail?id=' + driveId + '&sz=w1200';
            } else {
                imgEl.onerror = null;
                imgEl.src = 'https://placehold.co/800x600/1e293b/f59e0b?text=' + (fallbackText || 'OMELY+DESIGN');
            }
        }

        // Danh sách đầy đủ 19 ảnh thực tế từ Google Drive của khách hàng cung cấp
        const projectsData = [
            {
                id: 1,
                driveId: "1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk",
                title: "Thiết Kế & Thi Công Nhà Phố Hiện Đại Hòa Khánh – Đà Nẵng",
                category: "Nhà 2 tầng",
                location: "Phường Hòa Khánh, TP. Đà Nẵng"
            },
            {
                id: 2,
                driveId: "1tHGEqsuxKkCkoDofSK_nE70LBMIvGuVW",
                title: "Công Trình Nhà Phố 3 Tầng Mặt Tiền Thoáng Đẹp Tại Đà Nẵng",
                category: "Nhà 3 tầng",
                location: "Quận Liên Chiểu, TP. Đà Nẵng"
            },
            {
                id: 3,
                driveId: "1PjtEF4hlMU_42b438GmEQhYZTba75kRJ",
                title: "Mẫu Nhà Cấp 4 Mái Bằng Hiện Đại Tối Ưu Công Năng Gia Đình",
                category: "Nhà cấp 4",
                location: "Hòa Khánh, TP. Đà Nẵng"
            },
            {
                id: 4,
                driveId: "1m7VasLcMXKPk2-mSVgIdO3USOnbaZ_KA",
                title: "Nhà Phố 2 Tầng Tổ Ấm Trẻ Trung Cho Vợ Chồng Trẻ Đà Nẵng",
                category: "Nhà 2 tầng",
                location: "Quận Cẩm Lệ, TP. Đà Nẵng"
            },
            {
                id: 5,
                driveId: "1ng7_50Be4LsQqNa28KBn8rSCicz40ir9",
                title: "Thiết Kế Nhà 3 Tầng Có Gara Ô Tô Hiện Đại Và Sang Trọng",
                category: "Nhà 3 tầng",
                location: "Quận Hải Châu, TP. Đà Nẵng"
            },
            {
                id: 6,
                driveId: "1m0Hxp_Pf-urM1DxMd9GP-iuahuQfiznS",
                title: "Công Trình Nhà Phố 4 Tầng Kết Hợp Kinh Doanh Tại Đà Nẵng",
                category: "Nhà 4 tầng",
                location: "Quận Sơn Trà, TP. Đà Nẵng"
            },
            {
                id: 7,
                driveId: "1stTZuL2puyTkD_2WrDXjg2Yz2NAYyHV3",
                title: "Biệt Thự Nhà Vườn Không Gian Xanh Mát Nghỉ Dưỡng Đà Nẵng",
                category: "Nhà vườn",
                location: "Hòa Xuân, TP. Đà Nẵng"
            },
            {
                id: 8,
                driveId: "1-JeFJVOKB9-b8SOJFIxqa-Mk9ctbIraF",
                title: "Thiết Kế & Thi Công Căn Hộ Dịch Vụ Cho Thuê Hiệu Suất Cao",
                category: "Căn hộ dịch vụ",
                location: "Quận Ngũ Hành Sơn, TP. Đà Nẵng"
            },
            {
                id: 9,
                driveId: "1cmI83UnySYJ5Zt1I8A0kB0n94W4XgXgi",
                title: "Thực Tế Thi Công Nhà Phố 2 Tầng Nhẹ Nhàng Tinh Tế Đà Nẵng",
                category: "Nhà 2 tầng",
                location: "Phường Hòa Khánh, TP. Đà Nẵng"
            },
            {
                id: 10,
                driveId: "1A271daJ-s3V5Ws6LRrcDIJ9-Il34FXLq",
                title: "Nhà Cấp 4 Có Sân Vườn Thoáng Mát Chi Phí Tiết Kiệm",
                category: "Nhà cấp 4",
                location: "Liên Chiểu, TP. Đà Nẵng"
            },
            {
                id: 11,
                driveId: "1G5cVihRDvTKhbx_tNG5uDoSQtvzc0TTt",
                title: "Nhà Phố 3 Tầng Phong Cách Kiến Trúc Nhiệt Đới Đà Nẵng",
                category: "Nhà 3 tầng",
                location: "Quận Thanh Khê, TP. Đà Nẵng"
            },
            {
                id: 12,
                driveId: "1fqJikC677z_7x28XQaAx3VQD7zqWtiUy",
                title: "Công Trình Nhà 2 Tầng 5m Mặt Tiền Đẹp Và Tiện Nghi",
                category: "Nhà 2 tầng",
                location: "Hòa Khánh, TP. Đà Nẵng"
            },
            {
                id: 13,
                driveId: "1ImsuD--QivYj4IV9Nx10yzvXfmuRmZ8x",
                title: "Thiết Kế Nhà 4 Tầng Hiện Đại Tối Ưu Ánh Sáng Tự Nhiên",
                category: "Nhà 4 tầng",
                location: "Quận Hải Châu, TP. Đà Nẵng"
            },
            {
                id: 14,
                driveId: "11oZAhO2AsbGFYm1pdsPS5Vtgkd9IP2yZ",
                title: "Mẫu Nhà Vườn 1 Tầng Đẹp Gần Gũi Thiên Nhiên Tại Đà Nẵng",
                category: "Nhà vườn",
                location: "Hòa Vang, TP. Đà Nẵng"
            },
            {
                id: 15,
                driveId: "1qgl8kz47lsoa_Ju2l7xRZ5Jjt8DLC7yy",
                title: "Khu Căn Hộ Dịch Vụ & Lưu Trú Hiện Đại Cho Sinh Viên, Chuyên Gia",
                category: "Căn hộ dịch vụ",
                location: "Hòa Khánh, TP. Đà Nẵng"
            },
            {
                id: 16,
                driveId: "1ugKZwI_07LD42SRgLweM-PeRQt9-01Lw",
                title: "Hoàn Thiện Nội Ngoại Thất Nhà Phố 3 Tầng Trọn Gói Đà Nẵng",
                category: "Nhà 3 tầng",
                location: "Quận Sơn Trà, TP. Đà Nẵng"
            },
            {
                id: 17,
                driveId: "1QcvBpsk1aY6aHVHIVrZs9ALP17TUWfkK",
                title: "Thiết Kế Nhà Phố 2 Mặt Tiền Hiện Đại Tối Ưu Không Gian Sống",
                category: "Nhà 2 tầng",
                location: "Quận Cẩm Lệ, TP. Đà Nẵng"
            },
            {
                id: 18,
                driveId: "1TWxo6uXoJMty8Qsbu4z8HFR5TeLvWph1",
                title: "Thi Công Thực Tế Nhà Cấp 4 Trọn Gói Chìa Khóa Trao Tay",
                category: "Nhà cấp 4",
                location: "Phường Hòa Khánh, TP. Đà Nẵng"
            },
            {
                id: 19,
                driveId: "1nv_lSxn0mu-71NGKss3abLOuEMcB-bkQ",
                title: "Biệt Thự Phố 3 Tầng Sân Vườn Đẳng Cấp Tại Đà Nẵng",
                category: "Nhà vườn",
                location: "Ngũ Hành Sơn, TP. Đà Nẵng"
            }
        ];

        // Danh sách 8 bài viết kiến thức lấy từ cấu trúc web mẫu
        const postsData = [
            {
                title: "Thiết kế nhà có gara ô tô đẹp, hiện đại và an toàn tại Đà Nẵng",
                category: "Kiến thức xây nhà",
                driveId: "1ng7_50Be4LsQqNa28KBn8rSCicz40ir9",
                excerpt: "Những lưu ý quan trọng về kích thước, độ dốc và thông gió khi bố trí gara ô tô trong nhà phố hiện đại."
            },
            {
                title: "Thiết kế sân vườn nhà phố đẹp, hiện đại và ấn tượng",
                category: "Kiến thức xây nhà",
                driveId: "1stTZuL2puyTkD_2WrDXjg2Yz2NAYyHV3",
                excerpt: "Giải pháp đưa mảng xanh, giếng trời và tiểu cảnh sân vườn vào không gian nhà ống giúp đối lưu không khí."
            },
            {
                title: "Thiết kế bếp nhà ống đẹp, hiện đại và tối ưu không gian",
                category: "Nội thất & Công năng",
                driveId: "1fqJikC677z_7x28XQaAx3VQD7zqWtiUy",
                excerpt: "Cách bố trí tủ bếp chữ I, chữ L kết hợp bàn ăn thông minh giúp phòng bếp nhà phố rộng rãi, tiện nghi."
            },
            {
                title: "Thiết kế phòng ngủ đẹp, hiện đại và tiện nghi cho gia đình",
                category: "Nội thất & Công năng",
                driveId: "1ImsuD--QivYj4IV9Nx10yzvXfmuRmZ8x",
                excerpt: "Bí quyết phối màu ánh sáng, bố trí nội thất phòng ngủ master và phòng ngủ trẻ em hợp phong thủy."
            },
            {
                title: "Thiết kế phòng khách nhà phố đẹp, hiện đại và sang trọng",
                category: "Nội thất & Công năng",
                driveId: "1cmI83UnySYJ5Zt1I8A0kB0n94W4XgXgi",
                excerpt: "Tạo điểm nhấn sang trọng cho mặt tiền và không gian tiếp khách với vật liệu hiện đại, bền đẹp."
            },
            {
                title: "Thiết kế nhà 2 mặt tiền đẹp, hiện đại và tối ưu công năng",
                category: "Kiến thức xây nhà",
                driveId: "1QcvBpsk1aY6aHVHIVrZs9ALP17TUWfkK",
                excerpt: "Khai thác tối đa lợi thế lô góc 2 mặt tiền vừa ở tiện nghi vừa thuận lợi kết hợp kinh doanh."
            },
            {
                title: "Thiết kế nhà ống 5m mặt tiền đẹp, hiện đại tại Đà Nẵng",
                category: "Kiến thức xây nhà",
                driveId: "1m7VasLcMXKPk2-mSVgIdO3USOnbaZ_KA",
                excerpt: "Phương án chia mặt bằng công năng nhà phố ngang 5m từ 2 đến 3 tầng thông thoáng, tiết kiệm chi phí."
            },
            {
                title: "Quy trình dựng hình SketchUp và triển khai hồ sơ bản vẽ thi công",
                category: "Kiến thức SketchUp",
                driveId: "1ugKZwI_07LD42SRgLweM-PeRQt9-01Lw",
                excerpt: "Hướng dẫn tổ chức quản lý nhóm, layer và xuất bản vẽ kỹ thuật chính xác phục vụ thi công thực tế."
            }
        ];

        // Hiển thị danh sách dự án (Không có nhãn dán trên ảnh, tên sản phẩm đầy đủ không cắt chữ)
        function renderProjects(filterCategory = 'ALL') {
            const grid = document.getElementById('projects-grid');
            const filtered = filterCategory === 'ALL'
                ? projectsData
                : projectsData.filter(item => item.category === filterCategory);

            grid.innerHTML = filtered.map(item => `
                <article 
                    onclick="openProjectModal(${item.id})"
                    class="ux-card cursor-pointer bg-white rounded-xl border border-slate-200 hover:border-amber-500 hover:shadow-md transition overflow-hidden flex flex-col"
                >
                    <div class="ux-box-image aspect-[4/3] w-full">
                        <img 
                            src="https://lh3.googleusercontent.com/d/${item.driveId}" 
                            data-drive-id="${item.driveId}"
                            onerror="handleDriveImgError(this, 'DU+AN+${item.id}')"
                            alt="${item.title}" 
                            loading="lazy"
                            class="w-full h-full object-cover"
                        >
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm md:text-base font-bold text-slate-900 leading-snug whitespace-normal break-words mb-1.5">
                                ${item.title}
                            </h3>
                        </div>
                        <p class="text-[11px] sm:text-xs text-slate-500 whitespace-normal break-words pt-1 border-t border-slate-100">
                            ${item.category} • ${item.location}
                        </p>
                    </div>
                </article>
            `).join('');
        }

        function filterProjects(category) {
            renderProjects(category);
            const buttons = document.querySelectorAll('.project-filter-btn');
            buttons.forEach(btn => {
                if (btn.getAttribute('data-filter') === category) {
                    btn.className = 'project-filter-btn bg-slate-900 text-white text-xs sm:text-sm font-semibold px-3.5 py-2 rounded-lg transition';
                } else {
                    btn.className = 'project-filter-btn bg-slate-100 hover:bg-slate-200 text-slate-700 text-xs sm:text-sm font-semibold px-3.5 py-2 rounded-lg transition';
                }
            });
        }

        // Hiển thị danh mục bài viết trang chủ (Không để nhãn dán, tên bài viết đầy đủ không cắt chữ)
        function renderPosts(filterCategory = 'ALL') {
            const grid = document.getElementById('posts-grid');
            const filtered = filterCategory === 'ALL'
                ? postsData
                : postsData.filter(post => post.category === filterCategory);

            grid.innerHTML = filtered.map((post, idx) => `
                <article class="ux-card bg-white rounded-xl border border-slate-200 hover:border-amber-500 hover:shadow-md transition overflow-hidden flex flex-col">
                    <div class="ux-box-image aspect-[16/10] w-full">
                        <img 
                            src="https://lh3.googleusercontent.com/d/${post.driveId}" 
                            data-drive-id="${post.driveId}"
                            onerror="handleDriveImgError(this, 'BAI+VIET+${idx + 1}')"
                            alt="${post.title}" 
                            loading="lazy"
                            class="w-full h-full object-cover"
                        >
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm md:text-base font-bold text-slate-900 leading-snug whitespace-normal break-words mb-1.5">
                                ${post.title}
                            </h3>
                            <p class="text-xs text-slate-600 leading-relaxed whitespace-normal break-words">
                                ${post.excerpt}
                            </p>
                        </div>
                        <span class="text-[11px] sm:text-xs font-semibold text-amber-600 mt-2.5 inline-block whitespace-normal break-words">
                            Chuyên mục: ${post.category}
                        </span>
                    </div>
                </article>
            `).join('');
        }

        function filterPosts(category) {
            renderPosts(category);
            const buttons = document.querySelectorAll('.post-filter-btn');
            buttons.forEach(btn => {
                if (btn.getAttribute('data-post-filter') === category) {
                    btn.className = 'post-filter-btn bg-slate-900 text-white text-xs sm:text-sm font-semibold px-3.5 py-2 rounded-lg transition';
                } else {
                    btn.className = 'post-filter-btn bg-white hover:bg-slate-200 text-slate-700 border border-slate-200 text-xs sm:text-sm font-semibold px-3.5 py-2 rounded-lg transition';
                }
            });
        }

        // Mở / Đóng Modal xem ảnh thực tế
        function openProjectModal(projectId) {
            const item = projectsData.find(p => p.id === projectId);
            if (!item) return;
            const modal = document.getElementById('project-modal');
            const img = document.getElementById('modal-project-img');
            document.getElementById('modal-project-title').textContent = item.title;
            document.getElementById('modal-project-meta').textContent = item.category + ' tại ' + item.location;
            img.setAttribute('data-drive-id', item.driveId);
            img.removeAttribute('data-tried-thumb');
            img.src = 'https://lh3.googleusercontent.com/d/' + item.driveId;
            img.onerror = function() { handleDriveImgError(this, 'OMELY+DESIGN'); };
            modal.classList.remove('hidden');
        }

        function closeProjectModal() {
            document.getElementById('project-modal').classList.add('hidden');
        }

        // Xử lý tự trượt 2 ảnh Banner ngành xây dựng dân dụng
        let currentBannerIndex = 0;
        const bannerSlides = document.querySelectorAll('.hero-slide');
        const bannerDots = document.querySelectorAll('.banner-dot');

        function setBannerSlide(index) {
            currentBannerIndex = index;
            bannerSlides.forEach((slide, i) => {
                if (i === index) {
                    slide.classList.remove('opacity-0', 'z-0');
                    slide.classList.add('opacity-100', 'z-10');
                } else {
                    slide.classList.remove('opacity-100', 'z-10');
                    slide.classList.add('opacity-0', 'z-0');
                }
            });
            bannerDots.forEach((dot, i) => {
                if (i === index) {
                    dot.className = 'banner-dot w-7 h-2 rounded-full bg-amber-400 transition-all';
                } else {
                    dot.className = 'banner-dot w-2.5 h-2 rounded-full bg-white/60 transition-all';
                }
            });
        }

        setInterval(() => {
            const nextIndex = (currentBannerIndex + 1) % bannerSlides.length;
            setBannerSlide(nextIndex);
        }, 5000);

        // Xử lý gửi Form Yêu Cầu & Báo Giá
        function submitQuoteForm(event) {
            event.preventDefault();
            const name = document.getElementById('customer-name').value.trim();
            const phone = document.getElementById('customer-phone').value.trim();
            const category = document.getElementById('project-category').value;
            const area = document.getElementById('project-area').value.trim() || 'Tại Đà Nẵng';

            const box = document.getElementById('quote-success-box');
            const detail = document.getElementById('quote-success-detail');
            detail.textContent = `Cảm ơn anh/chị ${name} (${phone}). Yêu cầu tư vấn hạng mục "${category}" (${area}) đã được gửi đến bộ phận kỹ thuật CÔNG TY CỔ PHẦN TƯ VẤN XÂY DỰNG OMELY DESIGN. Chúng tôi sẽ liên hệ lại sớm nhất qua số 0901.171.182.`;
            box.classList.remove('hidden');
            document.getElementById('quote-request-form').reset();
        }

        // Xử lý đóng/mở Menu trên điện thoại
        const mobileMenuBtn = document.getElementById('mobile-menu-btn');
        const mobileMenuDropdown = document.getElementById('mobile-menu-dropdown');
        const mobileMenuIcon = document.getElementById('mobile-menu-icon');

        mobileMenuBtn.addEventListener('click', () => {
            const isHidden = mobileMenuDropdown.classList.contains('hidden');
            if (isHidden) {
                mobileMenuDropdown.classList.remove('hidden');
                mobileMenuIcon.className = 'fa-solid fa-xmark text-lg';
            } else {
                mobileMenuDropdown.classList.add('hidden');
                mobileMenuIcon.className = 'fa-solid fa-bars text-lg';
            }
        });

        document.querySelectorAll('.mobile-nav-link').forEach(link => {
            link.addEventListener('click', () => {
                mobileMenuDropdown.classList.add('hidden');
                mobileMenuIcon.className = 'fa-solid fa-bars text-lg';
            });
        });

        // Khởi tạo dữ liệu khi tải trang
        window.addEventListener('DOMContentLoaded', () => {
            renderProjects('ALL');
            renderPosts('ALL');
        });
    </script>
</body>
</html>
