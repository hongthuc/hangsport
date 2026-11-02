<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
  <title>Hằng Sport - Thiết Bị Thể Thao, Pickleball &amp; Dụng Cụ Hồ Bơi Đà Nẵng | hangsport.com</title>
  <meta name="description" content="Hằng Sport (hangsport.com) chuyên cung cấp Vợt Pickleball chính hãng, Giày thể thao, Quần áo thể thao, Dụng cụ & Hoá chất hồ bơi tại Liên Chiểu, Đà Nẵng. Hotline: 0972.143.287" />

  <!-- Open Graph Thumbnail Logo khi gửi link trang web (Zalo, Facebook, Messenger) -->
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://hangsport.com/" />
  <meta property="og:site_name" content="HẰNG SPORT - hangsport.com" />
  <meta property="og:title" content="Hằng Sport - Thiết Bị Thể Thao &amp; Pickleball Chính Hãng Đà Nẵng" />
  <meta property="og:description" content="CS1: K7/5 Phan Văn Định - CS2: 920 Tôn Đức Thắng, Hòa Khánh Bắc, Liên Chiểu, Đà Nẵng. Hotline/Zalo: 0972.143.287" />
  <meta property="og:image" content="https://drive.google.com/thumbnail?id=1uBzqaXUo7B3pT9zKqA0kYAecZl_RUpHe&sz=w1200" />
  <meta property="og:image:width" content="1200" />
  <meta property="og:image:height" content="630" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=1uBzqaXUo7B3pT9zKqA0kYAecZl_RUpHe&sz=w1200" />

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Font Inter & Montserrat chuẩn Flatsome -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Montserrat:ital,wght@0,700;0,800;0,900;1,800&display=swap" rel="stylesheet" />
  <!-- FontAwesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" />

  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
            display: ['Montserrat', 'sans-serif'],
          },
          colors: {
            brand: {
              blue: '#0b4f9f',
              darkBlue: '#07356e',
              red: '#e31837',
              orange: '#ff5722',
              light: '#f4f7fb'
            }
          }
        }
      }
    };
  </script>

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
      overflow-x: hidden !important;
      font-family: 'Inter', sans-serif;
      background-color: #f8fafc;
      color: #1e293b;
      scroll-behavior: smooth;
    }

    /* Container chuẩn Flatsome 1230px */
    .flatsome-container {
      width: 100%;
      max-width: 1230px;
      margin-left: auto;
      margin-right: auto;
      padding-left: 12px;
      padding-right: 12px;
    }

    /* Tiêu đề Section chuẩn Flatsome (Section Title Normal / Center) */
    .section-title-container {
      margin-bottom: 1.25rem;
    }
    .section-title-normal {
      display: flex;
      align-items: center;
      justify-content: space-between;
      border-bottom: 2px solid #e2e8f0;
      padding-bottom: 10px;
      gap: 12px;
      flex-wrap: wrap;
    }
    .section-title-main {
      font-family: 'Montserrat', sans-serif;
      font-weight: 800;
      text-transform: uppercase;
      color: #0b4f9f;
      position: relative;
      display: inline-flex;
      align-items: center;
      gap: 8px;
    }
    .section-title-main::after {
      content: '';
      position: absolute;
      bottom: -12px;
      left: 0;
      width: 100%;
      height: 3px;
      background: linear-gradient(90deg, #e31837, #0b4f9f);
      border-radius: 2px;
    }

    /* Khung Banner đồng bộ kích thước dựa theo ảnh mẫu */
    .banner-aspect-box {
      position: relative;
      width: 100%;
      aspect-ratio: 16 / 6.4;
      min-height: 185px;
      max-height: 480px;
      overflow: hidden;
      background: #07356e;
    }
    @media (max-width: 768px) {
      .banner-aspect-box {
        aspect-ratio: 16 / 8.2;
        min-height: 170px;
      }
    }

    /* Card sản phẩm chuẩn Flatsome */
    .product-small {
      background: #ffffff;
      border: 1px solid #e2e8f0;
      border-radius: 10px;
      overflow: hidden;
      transition: transform 0.25s ease, box-shadow 0.25s ease, border-color 0.25s ease;
      display: flex;
      flex-direction: column;
      height: 100%;
    }
    .product-small:hover {
      transform: translateY(-4px);
      box-shadow: 0 12px 24px -6px rgba(11, 79, 159, 0.14);
      border-color: #93c5fd;
    }
    .product-small .box-image {
      position: relative;
      width: 100%;
      aspect-ratio: 1 / 1;
      overflow: hidden;
      background-color: #f1f5f9;
    }
    .product-small .box-image img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      transition: transform 0.4s ease;
    }
    .product-small:hover .box-image img {
      transform: scale(1.06);
    }

    /* Thanh cuộn ngang mượt cho danh mục trên mobile */
    .no-scrollbar::-webkit-scrollbar {
      display: none;
    }
    .no-scrollbar {
      -ms-overflow-style: none;
      scrollbar-width: none;
    }

    /* Hiệu ứng rung & sóng toả cho nút nổi Zalo / Facebook / Hotline */
    @keyframes pulseRing {
      0% { transform: scale(0.95); opacity: 0.8; }
      70% { transform: scale(1.35); opacity: 0; }
      100% { transform: scale(1.35); opacity: 0; }
    }
    .floating-btn-ring::before {
      content: '';
      position: absolute;
      inset: -4px;
      border-radius: 9999px;
      background: inherit;
      z-index: -1;
      animation: pulseRing 2s infinite;
    }
  </style>
</head>
<body class="antialiased selection:bg-brand-blue selection:text-white">

  <!-- =====================================================================
       1. TOPBAR FLATSOME (Hiển thị địa chỉ CS1, CS2 & Fanpage - Không tràn viền)
       ===================================================================== -->
  <div class="bg-brand-darkBlue text-white text-xs py-2 border-b border-blue-800/60">
    <div class="flatsome-container flex flex-col lg:flex-row items-center justify-between gap-1.5">
      <div class="flex flex-wrap items-center justify-center lg:justify-start gap-x-4 gap-y-1 text-center lg:text-left">
        <span class="inline-flex items-center gap-1.5 font-medium text-blue-100">
          <i class="fa-solid fa-location-dot text-red-400"></i>
          <strong>CS 1:</strong> K7/5 Phan Văn Định, Hòa Khánh Bắc, Liên Chiểu, Đà Nẵng
        </span>
        <span class="hidden sm:inline text-blue-400">|</span>
        <span class="inline-flex items-center gap-1.5 font-medium text-blue-100">
          <i class="fa-solid fa-store text-amber-400"></i>
          <strong>CS 2:</strong> 920 Tôn Đức Thắng, Hòa Khánh Bắc, Liên Chiểu, Đà Nẵng
        </span>
      </div>
      <div class="flex items-center gap-4 text-[11px] sm:text-xs text-blue-100">
        <a href="https://www.facebook.com/duy.hang.357" target="_blank" rel="noopener" class="hover:text-white inline-flex items-center gap-1">
          <i class="fa-brands fa-facebook text-blue-300"></i> Fanpage Hằng Sport
        </a>
        <span class="text-blue-400">|</span>
        <a href="#form-bao-gia" class="hover:text-white inline-flex items-center gap-1 font-semibold text-amber-300">
          <i class="fa-solid fa-file-invoice-dollar"></i> Nhận Báo Giá Sỉ &amp; Lẻ
        </a>
      </div>
    </div>
  </div>

  <!-- =====================================================================
       2. HEADER CHÍNH FLATSOME (Không để nút gọi ngay trên Header để tránh tràn viền)
       ===================================================================== -->
  <header class="bg-white sticky top-0 z-40 shadow-sm border-b border-slate-200">
    <div class="flatsome-container py-2.5 md:py-3.5">
      <div class="flex items-center justify-between gap-2.5 md:gap-6">
        
        <!-- Nút mở Menu Danh Mục trên Điện Thoại -->
        <button id="mobileMenuBtn" type="button" aria-label="Mở danh mục" class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg bg-slate-100 text-brand-blue hover:bg-blue-50 shrink-0">
          <i class="fa-solid fa-bars text-lg"></i>
        </button>

        <!-- LOGO MỚI HẰNG SPORT (SVG sắc nét + chuẩn nhận diện hangsport.com) -->
        <a href="#" class="flex items-center gap-2.5 shrink-0 group focus:outline-none">
          <div class="w-11 h-11 md:w-12 md:h-12 rounded-xl bg-gradient-to-br from-brand-blue via-blue-700 to-brand-red p-0.5 shadow-md shrink-0">
            <div class="w-full h-full bg-white rounded-[10px] flex items-center justify-center relative overflow-hidden">
              <svg viewBox="0 0 64 64" class="w-9 h-9 md:w-10 md:h-10" fill="none" xmlns="http://www.w3.org/2000/svg">
                <!-- Biểu tượng chữ H thể thao kết hợp vợt Pickleball & cánh năng động -->
                <path d="M12 14L22 14L18 30L32 30L36 14L46 14L38 50L28 50L31 37L17 37L14 50L6 50L12 14Z" fill="#0b4f9f"/>
                <path d="M36 14L54 14C56.5 14 58 16.5 57 19L51 31C49.5 34 46.5 35 43 35L32 35L36 14Z" fill="#e31837" fill-opacity="0.92"/>
                <circle cx="48" cy="23" r="4.5" fill="#ffffff"/>
                <circle cx="48" cy="23" r="1.5" fill="#e31837"/>
              </svg>
            </div>
          </div>
          <div class="leading-tight">
            <div class="font-display font-black text-lg sm:text-xl md:text-2xl tracking-tight flex items-center">
              <span class="text-brand-blue">HẰNG</span>
              <span class="text-brand-red ml-1">SPORT</span>
            </div>
            <div class="text-[10px] sm:text-[11px] font-semibold text-slate-500 tracking-wider uppercase">
              hangsport.com • Đà Nẵng
            </div>
          </div>
        </a>

        <!-- Thanh Tìm Kiếm Sản Phẩm (Desktop) -->
        <div class="hidden md:flex flex-1 max-w-xl mx-auto">
          <form id="desktopSearchForm" class="w-full flex items-center bg-slate-100 border border-slate-300 rounded-full overflow-hidden focus-within:border-brand-blue focus-within:bg-white focus-within:ring-2 focus-within:ring-blue-100 transition">
            <input
              id="desktopSearchInput"
              type="text"
              placeholder="Tìm vợt Pickleball, giày thể thao, dụng cụ hồ bơi, chlorine..."
              class="w-full px-4 py-2.5 text-sm bg-transparent focus:outline-none text-slate-800"
            />
            <button type="submit" class="bg-brand-blue hover:bg-brand-darkBlue text-white px-5 py-2.5 text-sm font-semibold transition shrink-0">
              <i class="fa-solid fa-magnifying-glass mr-1"></i> Tìm
            </button>
          </form>
        </div>

        <!-- Cụm nút bên phải Header: Tư vấn Báo giá & Giỏ hàng (Không để nút gọi ngay tránh tràn viền) -->
        <div class="flex items-center gap-2 shrink-0">
          <a href="#he-thong-cua-hang" class="hidden xl:inline-flex items-center gap-2 px-3.5 py-2 rounded-lg bg-slate-100 hover:bg-blue-50 text-slate-700 hover:text-brand-blue text-xs font-semibold transition">
            <i class="fa-solid fa-map-location-dot text-brand-blue text-sm"></i>
            <span>2 Cơ sở Liên Chiểu</span>
          </a>

          <button id="cartOpenBtn" type="button" class="inline-flex items-center gap-2 px-3 py-2 rounded-lg border border-slate-200 hover:border-brand-blue bg-white text-slate-700 hover:text-brand-blue text-xs sm:text-sm font-semibold transition">
            <div class="relative">
              <i class="fa-solid fa-cart-shopping text-brand-blue text-base"></i>
              <span id="cartCountBadge" class="absolute -top-2 -right-2.5 w-4 h-4 rounded-full bg-brand-red text-white text-[10px] font-bold flex items-center justify-center">0</span>
            </div>
            <span class="hidden sm:inline">Giỏ hàng</span>
          </button>
        </div>
      </div>

      <!-- Thanh tìm kiếm trên Điện Thoại (Gọn gàng bên dưới Logo, không tràn viền) -->
      <div class="mt-2.5 md:hidden">
        <form id="mobileSearchForm" class="w-full flex items-center bg-slate-100 border border-slate-200 rounded-lg overflow-hidden">
          <input
            id="mobileSearchInput"
            type="text"
            placeholder="Tìm vợt Pickleball, giày, đồ thể thao, hồ bơi..."
            class="w-full px-3 py-2 text-xs bg-transparent focus:outline-none text-slate-800"
          />
          <button type="submit" class="bg-brand-blue text-white px-3.5 py-2 text-xs font-semibold shrink-0">
            <i class="fa-solid fa-magnifying-glass"></i>
          </button>
        </form>
      </div>
    </div>

    <!-- =====================================================================
         3. THANH MENU DANH MỤC TRÊN MÁY TÍNH (Chuẩn Flatsome Header Bottom)
         Lấy danh mục từ web mẫu kimsshop.vn, tối ưu hiển thị đẹp trên PC
         ===================================================================== -->
    <div class="hidden lg:block bg-brand-blue text-white border-t border-blue-800">
      <div class="flatsome-container flex items-center justify-between">
        
        <!-- Mega Menu Dropdown Danh Mục Sản Phẩm -->
        <div class="relative group">
          <button type="button" class="bg-brand-red hover:bg-red-700 text-white font-display font-bold text-xs uppercase tracking-wider px-5 py-3.5 inline-flex items-center gap-2.5 transition">
            <i class="fa-solid fa-bars-staggered text-sm"></i>
            <span>DANH MỤC SẢN PHẨM</span>
            <i class="fa-solid fa-chevron-down text-[10px] ml-1"></i>
          </button>
          <!-- Dropdown Danh mục khi rê chuột trên máy tính -->
          <div class="absolute left-0 top-full w-72 bg-white text-slate-800 shadow-2xl rounded-b-xl border border-slate-200 py-2 opacity-0 invisible group-hover:opacity-100 group-hover:visible transition-all duration-200 z-50">
            <a href="#san-pham-section" data-cat="pickleball" class="cat-filter-trigger flex items-center justify-between px-4 py-2.5 hover:bg-blue-50 hover:text-brand-blue text-sm font-medium border-b border-slate-100">
              <span class="flex items-center gap-2.5"><i class="fa-solid fa-table-tennis-paddle-ball text-brand-red w-4"></i> Vợt Pickleball Chính Hãng</span>
              <span class="text-xs text-slate-400">40 SP</span>
            </a>
            <a href="#san-pham-section" data-cat="giay-the-thao" class="cat-filter-trigger flex items-center justify-between px-4 py-2.5 hover:bg-blue-50 hover:text-brand-blue text-sm font-medium border-b border-slate-100">
              <span class="flex items-center gap-2.5"><i class="fa-solid fa-shoe-prints text-brand-blue w-4"></i> Giày Thể Thao &amp; Pickleball</span>
              <span class="text-xs text-slate-400">16 SP</span>
            </a>
            <a href="#san-pham-section" data-cat="quan-ao-the-thao" class="cat-filter-trigger flex items-center justify-between px-4 py-2.5 hover:bg-blue-50 hover:text-brand-blue text-sm font-medium border-b border-slate-100">
              <span class="flex items-center gap-2.5"><i class="fa-solid fa-shirt text-emerald-600 w-4"></i> Áo Thể Thao &amp; Đồ Tập Yoga</span>
              <span class="text-xs text-slate-400">24 SP</span>
            </a>
            <a href="#san-pham-section" data-cat="dung-cu-the-thao" class="cat-filter-trigger flex items-center justify-between px-4 py-2.5 hover:bg-blue-50 hover:text-brand-blue text-sm font-medium border-b border-slate-100">
              <span class="flex items-center gap-2.5"><i class="fa-solid fa-futbol text-amber-500 w-4"></i> Bóng Đá, Bóng Rổ &amp; Dụng Cụ</span>
              <span class="text-xs text-slate-400">18 SP</span>
            </a>
            <a href="#san-pham-section" data-cat="dung-cu-ho-boi" class="cat-filter-trigger flex items-center justify-between px-4 py-2.5 hover:bg-blue-50 hover:text-brand-blue text-sm font-medium border-b border-slate-100">
              <span class="flex items-center gap-2.5"><i class="fa-solid fa-water-ladder text-cyan-600 w-4"></i> Dụng Cụ Vệ Sinh Hồ Bơi</span>
              <span class="text-xs text-slate-400">12 SP</span>
            </a>
            <a href="#san-pham-section" data-cat="hoa-chat-ho-boi" class="cat-filter-trigger flex items-center justify-between px-4 py-2.5 hover:bg-blue-50 hover:text-brand-blue text-sm font-medium border-b border-slate-100">
              <span class="flex items-center gap-2.5"><i class="fa-solid fa-flask-vial text-purple-600 w-4"></i> Chlorin Xử Lý Nước Hồ Bơi</span>
              <span class="text-xs text-slate-400">13 SP</span>
            </a>
            <a href="#san-pham-section" data-cat="phao-boi" class="cat-filter-trigger flex items-center justify-between px-4 py-2.5 hover:bg-blue-50 hover:text-brand-blue text-sm font-medium border-b border-slate-100">
              <span class="flex items-center gap-2.5"><i class="fa-solid fa-life-ring text-orange-500 w-4"></i> Phao Bơi &amp; Đồ Bơi Cứu Hộ</span>
              <span class="text-xs text-slate-400">14 SP</span>
            </a>
            <a href="#san-pham-section" data-cat="phu-kien-the-thao" class="cat-filter-trigger flex items-center justify-between px-4 py-2.5 hover:bg-blue-50 hover:text-brand-blue text-sm font-medium">
              <span class="flex items-center gap-2.5"><i class="fa-solid fa-bag-shopping text-pink-600 w-4"></i> Phụ Kiện &amp; Balo Thể Thao</span>
              <span class="text-xs text-slate-400">15 SP</span>
            </a>
          </div>
        </div>

        <!-- Menu ngang trên máy tính -->
        <nav class="flex items-center gap-1 xl:gap-2 text-xs xl:text-sm font-semibold">
          <a href="#san-pham-section" data-cat="all" class="cat-filter-trigger px-3 py-3.5 hover:bg-white/10 rounded transition">Trang Chủ</a>
          <a href="#san-pham-section" data-cat="pickleball" class="cat-filter-trigger px-3 py-3.5 hover:bg-white/10 rounded transition flex items-center gap-1.5">
            <span>Pickleball Chính Hãng</span>
          </a>
          <a href="#san-pham-section" data-cat="giay-the-thao" class="cat-filter-trigger px-3 py-3.5 hover:bg-white/10 rounded transition">Giày Thể Thao</a>
          <a href="#san-pham-section" data-cat="quan-ao-the-thao" class="cat-filter-trigger px-3 py-3.5 hover:bg-white/10 rounded transition">Quần Áo Thể Thao</a>
          <a href="#san-pham-section" data-cat="dung-cu-ho-boi" class="cat-filter-trigger px-3 py-3.5 hover:bg-white/10 rounded transition">Dụng Cụ Bể Bơi</a>
          <a href="#san-pham-section" data-cat="hoa-chat-ho-boi" class="cat-filter-trigger px-3 py-3.5 hover:bg-white/10 rounded transition">Hoá Chất Chlorine</a>
          <a href="#bai-viet-section" class="px-3 py-3.5 hover:bg-white/10 rounded transition">Tin Tức</a>
          <a href="#form-bao-gia" class="px-3 py-3.5 hover:bg-white/10 rounded transition text-amber-300">Báo Giá</a>
          <a href="#he-thong-cua-hang" class="px-3 py-3.5 hover:bg-white/10 rounded transition">Bản Đồ &amp; Fanpage</a>
        </nav>
      </div>
    </div>

    <!-- Thanh cuộn nhanh Danh Mục trên Điện Thoại (Tối ưu xem trên điện thoại đẹp & không tràn viền) -->
    <div class="lg:hidden bg-brand-blue text-white border-t border-blue-800">
      <div class="flatsome-container py-2 overflow-x-auto no-scrollbar flex items-center gap-2">
        <button type="button" data-cat="all" class="cat-filter-trigger shrink-0 px-3 py-1.5 rounded-full bg-brand-red text-white text-xs font-semibold">Tất cả</button>
        <button type="button" data-cat="pickleball" class="cat-filter-trigger shrink-0 px-3 py-1.5 rounded-full bg-white/15 hover:bg-white/25 text-white text-xs font-medium">Vợt Pickleball</button>
        <button type="button" data-cat="giay-the-thao" class="cat-filter-trigger shrink-0 px-3 py-1.5 rounded-full bg-white/15 hover:bg-white/25 text-white text-xs font-medium">Giày Thể Thao</button>
        <button type="button" data-cat="quan-ao-the-thao" class="cat-filter-trigger shrink-0 px-3 py-1.5 rounded-full bg-white/15 hover:bg-white/25 text-white text-xs font-medium">Áo Thể Thao &amp; Yoga</button>
        <button type="button" data-cat="dung-cu-the-thao" class="cat-filter-trigger shrink-0 px-3 py-1.5 rounded-full bg-white/15 hover:bg-white/25 text-white text-xs font-medium">Dụng Cụ Thể Thao</button>
        <button type="button" data-cat="dung-cu-ho-boi" class="cat-filter-trigger shrink-0 px-3 py-1.5 rounded-full bg-white/15 hover:bg-white/25 text-white text-xs font-medium">Dụng Cụ Hồ Bơi</button>
        <button type="button" data-cat="hoa-chat-ho-boi" class="cat-filter-trigger shrink-0 px-3 py-1.5 rounded-full bg-white/15 hover:bg-white/25 text-white text-xs font-medium">Chlorin Hồ Bơi</button>
        <button type="button" data-cat="phao-boi" class="cat-filter-trigger shrink-0 px-3 py-1.5 rounded-full bg-white/15 hover:bg-white/25 text-white text-xs font-medium">Phao Bơi</button>
      </div>
    </div>
  </header>

  <!-- =====================================================================
       4. UX SECTION: SLIDER 2 BANNER TỰ TRƯỢT ĐỒNG KÍCH THƯỚC
       Dựa vào kích thước ảnh mẫu: 1uBzqaXUo7B3pT9zKqA0kYAecZl_RUpHe
       ===================================================================== -->
  <section class="py-3 md:py-5 bg-white border-b border-slate-200">
    <div class="flatsome-container">
      <div class="relative rounded-2xl overflow-hidden shadow-md border border-slate-200 banner-aspect-box" id="heroBannerContainer">
        
        <!-- SLIDE 1: Ảnh Banner gốc 1uBzqaXUo7B3pT9zKqA0kYAecZl_RUpHe kết hợp thông tin Hằng Sport -->
        <div class="hero-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-100 z-10" data-slide="0">
          <img
            id="referenceBannerImg"
            data-drive-id="1uBzqaXUo7B3pT9zKqA0kYAecZl_RUpHe"
            src="https://drive.google.com/thumbnail?id=1uBzqaXUo7B3pT9zKqA0kYAecZl_RUpHe&sz=w1600"
            alt="Banner Hằng Sport hangsport.com Slide 1"
            class="w-full h-full object-cover object-center"
          />
          <div class="absolute inset-0 bg-gradient-to-r from-slate-950/80 via-slate-900/45 to-transparent flex items-center">
            <div class="px-5 sm:px-10 md:px-14 max-w-2xl text-white">
              <p class="text-xs sm:text-sm font-bold uppercase tracking-widest text-amber-300 mb-1">
                HỆ THỐNG THỂ THAO HẰNG SPORT • HANGSPORT.COM
              </p>
              <h1 class="font-display font-black text-lg sm:text-3xl md:text-4xl leading-tight mb-2 sm:mb-3">
                CHUYÊN VỢT PICKLEBALL, GIÀY &amp; DỤNG CỤ THỂ THAO ĐÀ NẴNG
              </h1>
              <p class="text-xs sm:text-sm text-slate-100 mb-3 sm:mb-5 line-clamp-2">
                Cung cấp sỉ &amp; lẻ trang phục thể thao, vợt Pickleball chính hãng, phụ kiện thể thao và thiết bị vệ sinh hồ bơi tại Liên Chiểu, Đà Nẵng.
              </p>
              <div class="flex flex-wrap items-center gap-2.5">
                <a href="#san-pham-section" class="px-4 sm:px-6 py-2 sm:py-2.5 rounded-lg bg-brand-red hover:bg-red-700 text-white font-bold text-xs sm:text-sm transition shadow">
                  Xem Sản Phẩm Ngay
                </a>
                <a href="#form-bao-gia" class="px-4 sm:px-5 py-2 sm:py-2.5 rounded-lg bg-white/95 hover:bg-white text-brand-blue font-bold text-xs sm:text-sm transition">
                  Nhận Báo Giá Sỉ/Lẻ
                </a>
              </div>
            </div>
          </div>
        </div>

        <!-- SLIDE 2: Thiết kế đồng kích thước 100% với Slide 1, kết hợp ảnh thực tế tại cửa hàng -->
        <div class="hero-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-0 z-0 pointer-events-none" data-slide="1">
          <img
            data-drive-id="1uBzqaXUo7B3pT9zKqA0kYAecZl_RUpHe"
            src="https://drive.google.com/thumbnail?id=1uBzqaXUo7B3pT9zKqA0kYAecZl_RUpHe&sz=w1600"
            alt="Banner Hằng Sport hangsport.com Slide 2"
            class="w-full h-full object-cover object-center scale-105 filter brightness-50"
          />
          <div class="absolute inset-0 bg-gradient-to-r from-brand-darkBlue/95 via-brand-blue/85 to-slate-900/60 flex items-center justify-between px-5 sm:px-10 md:px-14">
            <div class="max-w-xl text-white">
              <p class="text-xs sm:text-sm font-bold uppercase tracking-widest text-cyan-300 mb-1">
                2 CƠ SỞ TẠI LIÊN CHIỂU - ĐÀ NẴNG • HOTLINE: 0972.143.287
              </p>
              <h2 class="font-display font-black text-lg sm:text-3xl md:text-4xl leading-tight mb-2 sm:mb-3">
                ĐỒ THỂ THAO, DỤNG CỤ TRƯỜNG HỌC &amp; THIẾT BỊ HỒ BƠI
              </h2>
              <p class="text-xs sm:text-sm text-blue-100 mb-3 sm:mb-5 line-clamp-2">
                CS1: K7/5 Phan Văn Định • CS2: 920 Tôn Đức Thắng, Hòa Khánh Bắc, Liên Chiểu, Đà Nẵng. Cam kết chính hãng, giá ưu đãi tốt nhất!
              </p>
              <div class="flex flex-wrap items-center gap-2.5">
                <a href="#he-thong-cua-hang" class="px-4 sm:px-6 py-2 sm:py-2.5 rounded-lg bg-amber-400 hover:bg-amber-300 text-slate-900 font-bold text-xs sm:text-sm transition shadow">
                  Xem Bản Đồ 2 Cơ Sở
                </a>
                <a href="https://www.facebook.com/duy.hang.357" target="_blank" rel="noopener" class="px-4 sm:px-5 py-2 sm:py-2.5 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/30 font-semibold text-xs sm:text-sm transition">
                  Fanpage Hằng Sport
                </a>
              </div>
            </div>
            <!-- Cụm 3 ảnh thực tế cửa hàng trên Banner 2 (Desktop) -->
            <div class="hidden lg:grid grid-cols-3 gap-3 w-5/12">
              <div class="rounded-xl overflow-hidden border-2 border-white/80 shadow-lg aspect-square bg-slate-800">
                <img data-drive-id="1Om7yPcguqire3orOjyaPTpq2EEePI3JA" src="https://drive.google.com/thumbnail?id=1Om7yPcguqire3orOjyaPTpq2EEePI3JA&sz=w600" alt="Ảnh thực tế Hằng Sport 1" class="w-full h-full object-cover" />
              </div>
              <div class="rounded-xl overflow-hidden border-2 border-white/80 shadow-lg aspect-square bg-slate-800">
                <img data-drive-id="1uTK01kF8p08fEqbXejedGQm77gJzZpoZ" src="https://drive.google.com/thumbnail?id=1uTK01kF8p08fEqbXejedGQm77gJzZpoZ&sz=w600" alt="Ảnh thực tế Hằng Sport 2" class="w-full h-full object-cover" />
              </div>
              <div class="rounded-xl overflow-hidden border-2 border-white/80 shadow-lg aspect-square bg-slate-800">
                <img data-drive-id="1hlKEOiR3vfugBdGYEXpVEoIzexInAfEE" src="https://drive.google.com/thumbnail?id=1hlKEOiR3vfugBdGYEXpVEoIzexInAfEE&sz=w600" alt="Ảnh thực tế Hằng Sport 3" class="w-full h-full object-cover" />
              </div>
            </div>
          </div>
        </div>

        <!-- Nút điều hướng Banner -->
        <button id="prevBannerBtn" type="button" aria-label="Slide trước" class="absolute left-2.5 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition">
          <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
        </button>
        <button id="nextBannerBtn" type="button" aria-label="Slide tiếp" class="absolute right-2.5 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition">
          <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
        </button>

        <!-- Chấm chỉ báo Slide -->
        <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
          <button type="button" data-go-slide="0" class="banner-dot w-6 h-2 rounded-full bg-white transition-all"></button>
          <button type="button" data-go-slide="1" class="banner-dot w-2 h-2 rounded-full bg-white/50 transition-all"></button>
        </div>
      </div>

      <!-- 4 Ô Cam Kết Dịch Vụ Chuẩn Flatsome (Giống kimsshop.vn) -->
      <div class="grid grid-cols-2 lg:grid-cols-4 gap-2.5 sm:gap-4 mt-3 sm:mt-4">
        <div class="bg-slate-50 border border-slate-200/80 rounded-xl p-3 flex items-center gap-3">
          <div class="w-10 h-10 rounded-lg bg-blue-100 text-brand-blue flex items-center justify-center shrink-0">
            <i class="fa-solid fa-truck-fast text-lg"></i>
          </div>
          <div>
            <div class="font-bold text-xs sm:text-sm text-slate-800">Giao hàng toàn quốc</div>
            <div class="text-[11px] text-slate-500">Giao nhanh Đà Nẵng trong 2h</div>
          </div>
        </div>
        <div class="bg-slate-50 border border-slate-200/80 rounded-xl p-3 flex items-center gap-3">
          <div class="w-10 h-10 rounded-lg bg-red-100 text-brand-red flex items-center justify-center shrink-0">
            <i class="fa-solid fa-medal text-lg"></i>
          </div>
          <div>
            <div class="font-bold text-xs sm:text-sm text-slate-800">Sản phẩm đa dạng</div>
            <div class="text-[11px] text-slate-500">Mẫu mã thể thao mới nhất</div>
          </div>
        </div>
        <div class="bg-slate-50 border border-slate-200/80 rounded-xl p-3 flex items-center gap-3">
          <div class="w-10 h-10 rounded-lg bg-emerald-100 text-emerald-700 flex items-center justify-center shrink-0">
            <i class="fa-solid fa-shield-halved text-lg"></i>
          </div>
          <div>
            <div class="font-bold text-xs sm:text-sm text-slate-800">Chế độ bảo hành</div>
            <div class="text-[11px] text-slate-500">Đổi trả uy tín, tận tâm</div>
          </div>
        </div>
        <div class="bg-slate-50 border border-slate-200/80 rounded-xl p-3 flex items-center gap-3">
          <div class="w-10 h-10 rounded-lg bg-amber-100 text-amber-600 flex items-center justify-center shrink-0">
            <i class="fa-solid fa-thumbs-up text-lg"></i>
          </div>
          <div>
            <div class="font-bold text-xs sm:text-sm text-slate-800">Uy tín chất lượng</div>
            <div class="text-[11px] text-slate-500">Giá sỉ &amp; lẻ tốt nhất Đà Nẵng</div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       5. UX SECTION: DANH MỤC SẢN PHẨM (Lấy từ web mẫu kimsshop.vn)
       Tối ưu hiển thị đẹp trên cả Máy Tính (8 cột) và Điện Thoại (4 cột gọn gàng)
       Sử dụng ảnh thực tế từ Google Drive
       ===================================================================== -->
  <section class="py-6 md:py-8 bg-slate-50" id="danh-muc-section">
    <div class="flatsome-container">
      <div class="section-title-container">
        <div class="section-title-normal">
          <h2 class="section-title-main text-base sm:text-xl">
            <i class="fa-solid fa-layer-group text-brand-red"></i>
            <span>DANH MỤC SẢN PHẨM</span>
          </h2>
          <span class="text-xs text-slate-500">Chọn danh mục để lọc nhanh sản phẩm</span>
        </div>
      </div>

      <!-- Lưới danh mục tối ưu: Điện thoại 4 cột gọn đẹp, Máy tính 8 cột đồng bộ -->
      <div class="grid grid-cols-4 sm:grid-cols-4 lg:grid-cols-8 gap-2.5 sm:gap-4" id="categoryVisualGrid">
        
        <button type="button" data-cat="pickleball" class="cat-filter-trigger group bg-white hover:bg-blue-50/60 border border-slate-200 hover:border-brand-blue rounded-xl p-2 sm:p-3 flex flex-col items-center text-center transition shadow-sm">
          <div class="w-14 h-14 sm:w-20 sm:h-20 rounded-full overflow-hidden border-2 border-blue-100 group-hover:border-brand-blue mb-2 bg-slate-100 shrink-0">
            <img data-drive-id="1Om7yPcguqire3orOjyaPTpq2EEePI3JA" src="https://drive.google.com/thumbnail?id=1Om7yPcguqire3orOjyaPTpq2EEePI3JA&sz=w400" alt="Vợt Pickleball" class="w-full h-full object-cover group-hover:scale-110 transition duration-300" />
          </div>
          <span class="font-bold text-[11px] sm:text-xs text-slate-800 group-hover:text-brand-blue line-clamp-2 leading-snug">Vợt Pickleball</span>
          <span class="text-[10px] text-slate-400 mt-0.5 hidden sm:inline">40 Sản phẩm</span>
        </button>

        <button type="button" data-cat="giay-the-thao" class="cat-filter-trigger group bg-white hover:bg-blue-50/60 border border-slate-200 hover:border-brand-blue rounded-xl p-2 sm:p-3 flex flex-col items-center text-center transition shadow-sm">
          <div class="w-14 h-14 sm:w-20 sm:h-20 rounded-full overflow-hidden border-2 border-blue-100 group-hover:border-brand-blue mb-2 bg-slate-100 shrink-0">
            <img data-drive-id="1uTK01kF8p08fEqbXejedGQm77gJzZpoZ" src="https://drive.google.com/thumbnail?id=1uTK01kF8p08fEqbXejedGQm77gJzZpoZ&sz=w400" alt="Giày thể thao" class="w-full h-full object-cover group-hover:scale-110 transition duration-300" />
          </div>
          <span class="font-bold text-[11px] sm:text-xs text-slate-800 group-hover:text-brand-blue line-clamp-2 leading-snug">Giày Thể Thao</span>
          <span class="text-[10px] text-slate-400 mt-0.5 hidden sm:inline">16 Sản phẩm</span>
        </button>

        <button type="button" data-cat="quan-ao-the-thao" class="cat-filter-trigger group bg-white hover:bg-blue-50/60 border border-slate-200 hover:border-brand-blue rounded-xl p-2 sm:p-3 flex flex-col items-center text-center transition shadow-sm">
          <div class="w-14 h-14 sm:w-20 sm:h-20 rounded-full overflow-hidden border-2 border-blue-100 group-hover:border-brand-blue mb-2 bg-slate-100 shrink-0">
            <img data-drive-id="1hlKEOiR3vfugBdGYEXpVEoIzexInAfEE" src="https://drive.google.com/thumbnail?id=1hlKEOiR3vfugBdGYEXpVEoIzexInAfEE&sz=w400" alt="Áo thể thao & Yoga" class="w-full h-full object-cover group-hover:scale-110 transition duration-300" />
          </div>
          <span class="font-bold text-[11px] sm:text-xs text-slate-800 group-hover:text-brand-blue line-clamp-2 leading-snug">Áo Thể Thao &amp; Yoga</span>
          <span class="text-[10px] text-slate-400 mt-0.5 hidden sm:inline">24 Sản phẩm</span>
        </button>

        <button type="button" data-cat="dung-cu-the-thao" class="cat-filter-trigger group bg-white hover:bg-blue-50/60 border border-slate-200 hover:border-brand-blue rounded-xl p-2 sm:p-3 flex flex-col items-center text-center transition shadow-sm">
          <div class="w-14 h-14 sm:w-20 sm:h-20 rounded-full overflow-hidden border-2 border-blue-100 group-hover:border-brand-blue mb-2 bg-slate-100 shrink-0">
            <img data-drive-id="16e_CFTuNfMFeCwssNtMgK6SCnPo_KXfb" src="https://drive.google.com/thumbnail?id=16e_CFTuNfMFeCwssNtMgK6SCnPo_KXfb&sz=w400" alt="Bóng đá & Bóng rổ" class="w-full h-full object-cover group-hover:scale-110 transition duration-300" />
          </div>
          <span class="font-bold text-[11px] sm:text-xs text-slate-800 group-hover:text-brand-blue line-clamp-2 leading-snug">Bóng Đá &amp; Bóng Rổ</span>
          <span class="text-[10px] text-slate-400 mt-0.5 hidden sm:inline">18 Sản phẩm</span>
        </button>

        <button type="button" data-cat="dung-cu-ho-boi" class="cat-filter-trigger group bg-white hover:bg-blue-50/60 border border-slate-200 hover:border-brand-blue rounded-xl p-2 sm:p-3 flex flex-col items-center text-center transition shadow-sm">
          <div class="w-14 h-14 sm:w-20 sm:h-20 rounded-full overflow-hidden border-2 border-blue-100 group-hover:border-brand-blue mb-2 bg-slate-100 shrink-0">
            <img data-drive-id="1gg82tfmnzVBuspaU5SzLcXhmRifwmvEV" src="https://drive.google.com/thumbnail?id=1gg82tfmnzVBuspaU5SzLcXhmRifwmvEV&sz=w400" alt="Dụng cụ hồ bơi" class="w-full h-full object-cover group-hover:scale-110 transition duration-300" />
          </div>
          <span class="font-bold text-[11px] sm:text-xs text-slate-800 group-hover:text-brand-blue line-clamp-2 leading-snug">Dụng Cụ Hồ Bơi</span>
          <span class="text-[10px] text-slate-400 mt-0.5 hidden sm:inline">12 Sản phẩm</span>
        </button>

        <button type="button" data-cat="hoa-chat-ho-boi" class="cat-filter-trigger group bg-white hover:bg-blue-50/60 border border-slate-200 hover:border-brand-blue rounded-xl p-2 sm:p-3 flex flex-col items-center text-center transition shadow-sm">
          <div class="w-14 h-14 sm:w-20 sm:h-20 rounded-full overflow-hidden border-2 border-blue-100 group-hover:border-brand-blue mb-2 bg-slate-100 shrink-0">
            <img data-drive-id="1QlBugiGee33QXnZJl6gCDft2576RSxqJ" src="https://drive.google.com/thumbnail?id=1QlBugiGee33QXnZJl6gCDft2576RSxqJ&sz=w400" alt="Chlorin xử lí nước" class="w-full h-full object-cover group-hover:scale-110 transition duration-300" />
          </div>
          <span class="font-bold text-[11px] sm:text-xs text-slate-800 group-hover:text-brand-blue line-clamp-2 leading-snug">Chlorin Hồ Bơi</span>
          <span class="text-[10px] text-slate-400 mt-0.5 hidden sm:inline">13 Sản phẩm</span>
        </button>

        <button type="button" data-cat="phao-boi" class="cat-filter-trigger group bg-white hover:bg-blue-50/60 border border-slate-200 hover:border-brand-blue rounded-xl p-2 sm:p-3 flex flex-col items-center text-center transition shadow-sm">
          <div class="w-14 h-14 sm:w-20 sm:h-20 rounded-full overflow-hidden border-2 border-blue-100 group-hover:border-brand-blue mb-2 bg-slate-100 shrink-0">
            <img data-drive-id="1U3mvpPaxc_eJjsiqoXwgRp6ZUgL8MKXm" src="https://drive.google.com/thumbnail?id=1U3mvpPaxc_eJjsiqoXwgRp6ZUgL8MKXm&sz=w400" alt="Phao bơi cứu hộ" class="w-full h-full object-cover group-hover:scale-110 transition duration-300" />
          </div>
          <span class="font-bold text-[11px] sm:text-xs text-slate-800 group-hover:text-brand-blue line-clamp-2 leading-snug">Phao Bơi &amp; Đồ Bơi</span>
          <span class="text-[10px] text-slate-400 mt-0.5 hidden sm:inline">14 Sản phẩm</span>
        </button>

        <button type="button" data-cat="phu-kien-the-thao" class="cat-filter-trigger group bg-white hover:bg-blue-50/60 border border-slate-200 hover:border-brand-blue rounded-xl p-2 sm:p-3 flex flex-col items-center text-center transition shadow-sm">
          <div class="w-14 h-14 sm:w-20 sm:h-20 rounded-full overflow-hidden border-2 border-blue-100 group-hover:border-brand-blue mb-2 bg-slate-100 shrink-0">
            <img data-drive-id="17LOsACaJMoqibajt3ds7-hGmNirfzpf-" src="https://drive.google.com/thumbnail?id=17LOsACaJMoqibajt3ds7-hGmNirfzpf-&sz=w400" alt="Phụ kiện thể thao" class="w-full h-full object-cover group-hover:scale-110 transition duration-300" />
          </div>
          <span class="font-bold text-[11px] sm:text-xs text-slate-800 group-hover:text-brand-blue line-clamp-2 leading-snug">Phụ Kiện Thể Thao</span>
          <span class="text-[10px] text-slate-400 mt-0.5 hidden sm:inline">15 Sản phẩm</span>
        </button>

      </div>
    </div>
  </section>

  <!-- =====================================================================
       6. UX SECTION: DANH SÁCH SẢN PHẨM THỰC TẾ (14 ẢNH GOOGLE DRIVE)
       - Chia 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4)
       - Có giá gốc gạch ngang, giá giảm và % giảm giá giống Flatsome
       - KHÔNG để các nhãn dán đè lên ảnh ở trang chủ theo đúng yêu cầu
       ===================================================================== -->
  <section class="py-6 md:py-10 bg-white" id="san-pham-section">
    <div class="flatsome-container">
      <div class="section-title-container">
        <div class="section-title-normal">
          <h2 class="section-title-main text-base sm:text-xl" id="activeCategoryHeading">
            <i class="fa-solid fa-fire text-brand-red"></i>
            <span>SẢN PHẨM NỔI BẬT TẠI HẰNG SPORT</span>
          </h2>

          <!-- Bộ lọc danh mục nhanh trên máy tính & điện thoại -->
          <div class="flex items-center gap-1.5 overflow-x-auto no-scrollbar py-1 max-w-full">
            <button type="button" data-cat="all" class="cat-pill-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-brand-blue text-white shrink-0 transition">Tất cả (14)</button>
            <button type="button" data-cat="pickleball" class="cat-pill-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-blue-50 shrink-0 transition">Vợt Pickleball</button>
            <button type="button" data-cat="giay-the-thao" class="cat-pill-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-blue-50 shrink-0 transition">Giày Thể Thao</button>
            <button type="button" data-cat="quan-ao-the-thao" class="cat-pill-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-blue-50 shrink-0 transition">Áo &amp; Đồ Tập</button>
            <button type="button" data-cat="dung-cu-ho-boi" class="cat-pill-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-blue-50 shrink-0 transition">Hồ Bơi &amp; Chlorine</button>
          </div>
        </div>
      </div>

      <!-- Lưới sản phẩm: 2 cột trên điện thoại (grid-cols-2), 3 cột tablet, 4 cột máy tính -->
      <div id="productGridContainer" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5">
        <!-- Được render tự động từ 14 ảnh Google Drive thực tế của Hằng Sport -->
      </div>
    </div>
  </section>

  <!-- =====================================================================
       7. UX SECTION: CHUYÊN MỤC VỢT PICKLEBALL & DỤNG CỤ HỒ BƠI (Giống kimsshop.vn)
       ===================================================================== -->
  <section class="py-6 md:py-10 bg-slate-50 border-t border-slate-200">
    <div class="flatsome-container">
      <div class="section-title-container">
        <div class="section-title-normal">
          <h2 class="section-title-main text-base sm:text-xl">
            <i class="fa-solid fa-water-ladder text-brand-blue"></i>
            <span>DỤNG CỤ VỆ SINH HỒ BƠI &amp; HOÁ CHẤT XỬ LÝ NƯỚC</span>
          </h2>
          <a href="#form-bao-gia" class="text-xs font-bold text-brand-blue hover:text-brand-red inline-flex items-center gap-1">
            <span>Nhận báo giá sỉ công trình</span>
            <i class="fa-solid fa-arrow-right"></i>
          </a>
        </div>
      </div>
      <p class="text-xs sm:text-sm text-slate-600 mb-4 leading-relaxed">
        Hằng Sport cung cấp đầy đủ các loại dụng cụ vệ sinh bể bơi (bàn hút đáy 8 bánh, chổi cọ thành hồ, vợt vớt rác, sào nhôm, ống mềm hút cặn, hộp test nước PH) và hoá chất xử lý nước Chlorine 70%, PAC trợ lắng phục vụ gia đình, trường học, khách sạn và resort tại Đà Nẵng.
      </p>

      <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
      <div id="poolProductsGrid" class="grid grid-cols-2 md:grid-cols-4 gap-3 sm:gap-5">
        <!-- Render từ nhóm sản phẩm hồ bơi & dụng cụ thực tế -->
      </div>
    </div>
  </section>

  <!-- =====================================================================
       8. UX SECTION: FORM YÊU CẦU TƯ VẤN & NHẬN BÁO GIÁ TRANG CHỦ
       ===================================================================== -->
  <section class="py-8 md:py-12 bg-white border-t border-slate-200" id="form-bao-gia">
    <div class="flatsome-container">
      <div class="bg-gradient-to-br from-brand-darkBlue via-brand-blue to-blue-900 rounded-2xl p-5 sm:p-8 md:p-10 text-white shadow-xl">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 md:gap-8 items-center">
          
          <!-- Cột thông tin ưu đãi báo giá -->
          <div class="lg:col-span-5 space-y-4">
            <div class="inline-flex items-center gap-2 text-amber-300 font-bold text-xs uppercase tracking-wider">
              <i class="fa-solid fa-file-signature"></i>
              <span>BÁO GIÁ NHANH TRONG 5 PHÚT</span>
            </div>
            <h2 class="font-display font-black text-xl sm:text-2xl md:text-3xl leading-tight">
              ĐĂNG KÝ YÊU CẦU TƯ VẤN &amp; NHẬN BÁO GIÁ SỈ / LẺ
            </h2>
            <p class="text-xs sm:text-sm text-blue-100 leading-relaxed">
              Quý khách hàng cá nhân, CLB Pickleball, trường học, phòng tập, khách sạn tại Đà Nẵng cần báo giá đồng phục thể thao, vợt Pickleball, dụng cụ thể thao hoặc hoá chất hồ bơi vui lòng để lại thông tin.
            </p>
            <div class="space-y-2.5 pt-1 text-xs sm:text-sm">
              <div class="flex items-start gap-2.5">
                <i class="fa-solid fa-location-dot text-amber-400 mt-1 shrink-0"></i>
                <span><strong>CS 1:</strong> K7/5 Phan Văn Định, Hòa Khánh Bắc, Liên Chiểu, Đà Nẵng</span>
              </div>
              <div class="flex items-start gap-2.5">
                <i class="fa-solid fa-location-dot text-amber-400 mt-1 shrink-0"></i>
                <span><strong>CS 2:</strong> 920 Tôn Đức Thắng, Hòa Khánh Bắc, Liên Chiểu, Đà Nẵng</span>
              </div>
              <div class="flex items-center gap-2.5">
                <i class="fa-solid fa-phone-volume text-emerald-400 shrink-0"></i>
                <span><strong>Hotline / Zalo:</strong> <a href="tel:0972143287" class="underline font-bold text-amber-300">0972.143.287</a></span>
              </div>
            </div>
          </div>

          <!-- Cột Form Báo Giá chuẩn Flatsome -->
          <div class="lg:col-span-7">
            <form id="quoteRequestForm" class="bg-white text-slate-800 rounded-xl p-4 sm:p-6 shadow-lg space-y-3.5">
              <h3 class="font-display font-bold text-base sm:text-lg text-brand-blue border-b border-slate-100 pb-2">
                Gửi Yêu Cầu Báo Giá Đến Hằng Sport
              </h3>
              <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                <div>
                  <label class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên quý khách *</label>
                  <input type="text" id="quoteName" required placeholder="Nhập họ và tên..." class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-blue focus:outline-none" />
                </div>
                <div>
                  <label class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                  <input type="tel" id="quotePhone" required placeholder="Ví dụ: 0972143287" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-blue focus:outline-none" />
                </div>
              </div>

              <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                <div>
                  <label class="block text-xs font-semibold text-slate-700 mb-1">Danh mục sản phẩm quan tâm</label>
                  <select id="quoteCategory" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-blue focus:outline-none bg-white">
                    <option value="Vợt & Phụ kiện Pickleball chính hãng">Vợt &amp; Phụ kiện Pickleball chính hãng</option>
                    <option value="Giày thể thao / Giày Pickleball">Giày thể thao / Giày Pickleball</option>
                    <option value="Quần áo thể thao / Đặt in đồng phục đội">Quần áo thể thao / Đặt in đồng phục đội</option>
                    <option value="Dụng cụ thể thao trường học / Bóng đá / Bóng rổ">Dụng cụ thể thao trường học / Bóng đá / Bóng rổ</option>
                    <option value="Dụng cụ vệ sinh hồ bơi & Hoá chất Chlorine">Dụng cụ vệ sinh hồ bơi &amp; Hoá chất Chlorine</option>
                    <option value="Phao bơi cứu hộ & Phụ kiện bơi lội">Phao bơi cứu hộ &amp; Phụ kiện bơi lội</option>
                  </select>
                </div>
                <div>
                  <label class="block text-xs font-semibold text-slate-700 mb-1">Cơ sở giao dịch thuận tiện</label>
                  <select id="quoteBranch" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-blue focus:outline-none bg-white">
                    <option value="CS 1: K7/5 Phan Văn Định, Liên Chiểu">CS 1: K7/5 Phan Văn Định, Liên Chiểu</option>
                    <option value="CS 2: 920 Tôn Đức Thắng, Liên Chiểu">CS 2: 920 Tôn Đức Thắng, Liên Chiểu</option>
                    <option value="Giao hàng tận nơi tại Đà Nẵng / Toàn quốc">Giao hàng tận nơi tại Đà Nẵng / Toàn quốc</option>
                  </select>
                </div>
              </div>

              <div>
                <label class="block text-xs font-semibold text-slate-700 mb-1">Nội dung yêu cầu &amp; Số lượng cần báo giá</label>
                <textarea id="quoteNote" rows="3" placeholder="Nhập tên sản phẩm, size, số lượng hoặc yêu cầu tư vấn chi tiết..." class="w-full px-3.5 py-2 text-sm rounded-lg border border-slate-300 focus:border-brand-blue focus:outline-none"></textarea>
              </div>

              <div class="flex flex-col sm:flex-row items-stretch sm:items-center justify-between gap-2.5 pt-1">
                <button type="submit" class="bg-brand-red hover:bg-red-700 text-white font-display font-bold text-xs sm:text-sm uppercase px-6 py-3 rounded-lg shadow transition flex items-center justify-center gap-2">
                  <i class="fa-solid fa-paper-plane"></i>
                  <span>Gửi Yêu Cầu Báo Giá Ngay</span>
                </button>
                <a href="https://zalo.me/0972143287" target="_blank" rel="noopener" class="bg-blue-50 hover:bg-blue-100 text-brand-blue font-semibold text-xs px-4 py-3 rounded-lg text-center transition">
                  <i class="fa-solid fa-comment-dots mr-1"></i> Chat Zalo 0972.143.287
                </a>
              </div>
              <div id="quoteSuccessMsg" class="hidden p-3 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs font-medium"></div>
            </form>
          </div>

        </div>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       9. UX SECTION: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (Tin Tức & Kinh Nghiệm)
       ===================================================================== -->
  <section class="py-8 md:py-10 bg-slate-50 border-t border-slate-200" id="bai-viet-section">
    <div class="flatsome-container">
      <div class="section-title-container">
        <div class="section-title-normal">
          <h2 class="section-title-main text-base sm:text-xl">
            <i class="fa-solid fa-newspaper text-brand-blue"></i>
            <span>CHUYÊN MỤC BÀI VIẾT &amp; KINH NGHIỆM THỂ THAO</span>
          </h2>
          <!-- Danh mục bài viết -->
          <div class="flex items-center gap-1.5 overflow-x-auto no-scrollbar">
            <button type="button" data-blog-cat="all" class="blog-cat-btn px-3 py-1 rounded-full text-xs font-semibold bg-brand-blue text-white shrink-0">Tất cả bài viết</button>
            <button type="button" data-blog-cat="pickleball" class="blog-cat-btn px-3 py-1 rounded-full text-xs font-medium bg-white border border-slate-200 text-slate-700 shrink-0">Tư vấn Pickleball</button>
            <button type="button" data-blog-cat="trang-phuc" class="blog-cat-btn px-3 py-1 rounded-full text-xs font-medium bg-white border border-slate-200 text-slate-700 shrink-0">Giày &amp; Trang phục</button>
            <button type="button" data-blog-cat="ho-boi" class="blog-cat-btn px-3 py-1 rounded-full text-xs font-medium bg-white border border-slate-200 text-slate-700 shrink-0">Kỹ thuật Hồ bơi</button>
          </div>
        </div>
      </div>

      <!-- Lưới bài viết chuẩn Blog Flatsome -->
      <div id="blogGridContainer" class="grid grid-cols-1 md:grid-cols-3 gap-4 sm:gap-6">
        <!-- Render động từ danh sách bài viết sử dụng ảnh Google Drive thực tế -->
      </div>
    </div>
  </section>

  <!-- =====================================================================
       10. UX SECTION: ĐƯA GOOGLE MAP 2 CƠ SỞ & FANPAGE FACEBOOK RA NGOÀI TRANG CHỦ
       ===================================================================== -->
  <section class="py-8 md:py-12 bg-white border-t border-slate-200" id="he-thong-cua-hang">
    <div class="flatsome-container">
      <div class="section-title-container">
        <div class="section-title-normal">
          <h2 class="section-title-main text-base sm:text-xl">
            <i class="fa-solid fa-map-location-dot text-brand-red"></i>
            <span>BẢN ĐỒ GOOGLE MAPS &amp; FANPAGE HẰNG SPORT</span>
          </h2>
          <span class="text-xs font-semibold text-brand-blue">Hotline hỗ trợ chỉ đường: 0972.143.287</span>
        </div>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-start">
        
        <!-- Cột trái (7/12): Bản đồ Google Maps 2 cơ sở trực tiếp ngoài trang chủ -->
        <div class="lg:col-span-7 bg-slate-50 border border-slate-200 rounded-2xl p-3 sm:p-5 shadow-sm">
          <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-2 mb-3">
            <div>
              <h3 class="font-display font-bold text-sm sm:text-base text-slate-800">
                Hệ Thống 2 Cơ Sở Hằng Sport Tại Liên Chiểu, Đà Nẵng
              </h3>
              <p class="text-xs text-slate-500">Nhấn chọn cơ sở bên dưới để xem vị trí chính xác trên Google Maps</p>
            </div>
            <div class="flex items-center gap-2">
              <button type="button" id="mapBtnCS1" class="px-3 py-1.5 rounded-lg text-xs font-bold bg-brand-blue text-white transition">
                Xem Bản Đồ CS 1
              </button>
              <button type="button" id="mapBtnCS2" class="px-3 py-1.5 rounded-lg text-xs font-bold bg-white border border-slate-300 text-slate-700 hover:border-brand-blue transition">
                Xem Bản Đồ CS 2
              </button>
            </div>
          </div>

          <!-- Thông tin 2 địa chỉ rõ ràng -->
          <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5 mb-3">
            <div class="p-3 rounded-xl bg-white border border-blue-200">
              <div class="font-bold text-xs text-brand-blue uppercase mb-0.5">
                <i class="fa-solid fa-location-dot text-brand-red mr-1"></i> Cơ sở 1 - Phan Văn Định
              </div>
              <div class="text-xs text-slate-700 font-medium">K7/5 Phan Văn Định, Hòa Khánh Bắc, Liên Chiểu, Đà Nẵng</div>
              <a href="https://www.google.com/maps/search/?api=1&query=K7%2F5+Phan+V%C4%83n+%C4%90%E1%BB%8Bnh%2C+H%C3%B2a+Kh%C3%A1nh+B%E1%BA%AFc%2C+Li%C3%AAn+Chi%E1%BB%83u%2C+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener" class="inline-block mt-1.5 text-[11px] font-bold text-brand-blue hover:underline">
                Mở ứng dụng Google Maps <i class="fa-solid fa-arrow-up-right-from-square text-[10px]"></i>
              </a>
            </div>
            <div class="p-3 rounded-xl bg-white border border-slate-200">
              <div class="font-bold text-xs text-brand-blue uppercase mb-0.5">
                <i class="fa-solid fa-store text-amber-500 mr-1"></i> Cơ sở 2 - Tôn Đức Thắng
              </div>
              <div class="text-xs text-slate-700 font-medium">920 Tôn Đức Thắng, Hòa Khánh Bắc, Liên Chiểu, Đà Nẵng</div>
              <a href="https://www.google.com/maps/search/?api=1&query=920+T%C3%B4n+%C4%90%E1%BB%A9c+Th%E1%BA%AFng%2C+H%C3%B2a+Kh%C3%A1nh+B%E1%BA%AFc%2C+Li%C3%AAn+Chi%E1%BB%83u%2C+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener" class="inline-block mt-1.5 text-[11px] font-bold text-brand-blue hover:underline">
                Mở ứng dụng Google Maps <i class="fa-solid fa-arrow-up-right-from-square text-[10px]"></i>
              </a>
            </div>
          </div>

          <!-- Khung Google Maps trực tiếp ngoài trang chủ -->
          <div class="w-full h-64 sm:h-80 rounded-xl overflow-hidden border border-slate-300 bg-slate-200">
            <iframe
              id="googleMapIframe"
              title="Bản đồ Google Map Hằng Sport Đà Nẵng"
              src="https://maps.google.com/maps?q=K7/5%20Phan%20V%C4%83n%20%C4%90%E1%BB%8Bnh,%20H%C3%B2a%20Kh%C3%A1nh%20B%E1%BA%AFc,%20Li%C3%AAn%20Chi%E1%BB%83u,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
              class="w-full h-full border-0"
              loading="lazy"
              referrerpolicy="no-referrer-when-downgrade"
            ></iframe>
          </div>
        </div>

        <!-- Cột phải (5/12): Đưa Fanpage Facebook ra ngoài trang chủ (https://www.facebook.com/duy.hang.357) -->
        <div class="lg:col-span-5 bg-slate-50 border border-slate-200 rounded-2xl p-4 sm:p-5 shadow-sm">
          <div class="flex items-center justify-between mb-3">
            <h3 class="font-display font-bold text-sm sm:text-base text-slate-800 flex items-center gap-2">
              <i class="fa-brands fa-facebook text-[#1877F2] text-lg"></i>
              <span>Kết Nối Fanpage Hằng Sport</span>
            </h3>
            <a href="https://www.facebook.com/duy.hang.357" target="_blank" rel="noopener" class="text-xs font-bold text-[#1877F2] hover:underline">
              Theo dõi ngay
            </a>
          </div>

          <!-- Khung hiển thị Fanpage trực quan ngoài trang chủ -->
          <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm">
            <!-- Ảnh bìa thực tế từ Google Drive -->
            <div class="relative h-36 bg-brand-darkBlue overflow-hidden">
              <img
                data-drive-id="1uBzqaXUo7B3pT9zKqA0kYAecZl_RUpHe"
                src="https://drive.google.com/thumbnail?id=1uBzqaXUo7B3pT9zKqA0kYAecZl_RUpHe&sz=w800"
                alt="Ảnh bìa Facebook Hằng Sport"
                class="w-full h-full object-cover opacity-85"
              />
              <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/30 to-transparent"></div>
              <div class="absolute bottom-3 left-3 right-3 flex items-end justify-between gap-2">
                <div class="flex items-center gap-3">
                  <div class="w-14 h-14 rounded-full border-2 border-white overflow-hidden bg-white shrink-0 shadow">
                    <img
                      data-drive-id="1Om7yPcguqire3orOjyaPTpq2EEePI3JA"
                      src="https://drive.google.com/thumbnail?id=1Om7yPcguqire3orOjyaPTpq2EEePI3JA&sz=w300"
                      alt="Avatar Duy Hằng - Hằng Sport"
                      class="w-full h-full object-cover"
                    />
                  </div>
                  <div class="text-white">
                    <a href="https://www.facebook.com/duy.hang.357" target="_blank" rel="noopener" class="font-bold text-sm sm:text-base hover:underline flex items-center gap-1">
                      <span>Hằng Sport - Duy Hằng</span>
                      <i class="fa-solid fa-circle-check text-blue-400 text-xs"></i>
                    </a>
                    <p class="text-[11px] text-slate-200">facebook.com/duy.hang.357 • Thể thao Đà Nẵng</p>
                  </div>
                </div>
              </div>
            </div>

            <!-- Nội dung giới thiệu & Hình ảnh thực tế trên Fanpage -->
            <div class="p-3.5 space-y-3">
              <p class="text-xs text-slate-600 leading-relaxed">
                Cập nhật mẫu vợt Pickleball, quần áo thể thao, giày bóng đá, dụng cụ thể thao &amp; thiết bị bể bơi mới về hàng ngày tại Hằng Sport Liên Chiểu, Đà Nẵng.
              </p>

              <!-- Album ảnh thực tế từ link Google Drive -->
              <div class="grid grid-cols-4 gap-1.5">
                <a href="https://www.facebook.com/duy.hang.357" target="_blank" rel="noopener" class="aspect-square rounded-lg overflow-hidden bg-slate-100 block">
                  <img data-drive-id="1CJ15aKlk2iSknSqf4uebCriw2bc53Ena" src="https://drive.google.com/thumbnail?id=1CJ15aKlk2iSknSqf4uebCriw2bc53Ena&sz=w300" alt="Ảnh Fanpage 1" class="w-full h-full object-cover hover:scale-105 transition" />
                </a>
                <a href="https://www.facebook.com/duy.hang.357" target="_blank" rel="noopener" class="aspect-square rounded-lg overflow-hidden bg-slate-100 block">
                  <img data-drive-id="1w_9XBgOmCHPnseCx25-X3D_vaxeXsatI" src="https://drive.google.com/thumbnail?id=1w_9XBgOmCHPnseCx25-X3D_vaxeXsatI&sz=w300" alt="Ảnh Fanpage 2" class="w-full h-full object-cover hover:scale-105 transition" />
                </a>
                <a href="https://www.facebook.com/duy.hang.357" target="_blank" rel="noopener" class="aspect-square rounded-lg overflow-hidden bg-slate-100 block">
                  <img data-drive-id="1AtWd3TOWw-c8DKwndMouIMW4Y7R3lpoj" src="https://drive.google.com/thumbnail?id=1AtWd3TOWw-c8DKwndMouIMW4Y7R3lpoj&sz=w300" alt="Ảnh Fanpage 3" class="w-full h-full object-cover hover:scale-105 transition" />
                </a>
                <a href="https://www.facebook.com/duy.hang.357" target="_blank" rel="noopener" class="aspect-square rounded-lg overflow-hidden bg-slate-100 block">
                  <img data-drive-id="1dCRcgARamrvNws-PqdyaVhGMydih09Ep" src="https://drive.google.com/thumbnail?id=1dCRcgARamrvNws-PqdyaVhGMydih09Ep&sz=w300" alt="Ảnh Fanpage 4" class="w-full h-full object-cover hover:scale-105 transition" />
                </a>
              </div>

              <div class="grid grid-cols-2 gap-2 pt-1">
                <a href="https://www.facebook.com/duy.hang.357" target="_blank" rel="noopener" class="w-full py-2.5 px-3 rounded-lg bg-[#1877F2] hover:bg-blue-700 text-white font-semibold text-xs flex items-center justify-center gap-1.5 transition">
                  <i class="fa-brands fa-facebook"></i>
                  <span>Truy Cập Fanpage</span>
                </a>
                <a href="https://zalo.me/0972143287" target="_blank" rel="noopener" class="w-full py-2.5 px-3 rounded-lg bg-slate-100 hover:bg-slate-200 text-slate-800 font-semibold text-xs flex items-center justify-center gap-1.5 transition">
                  <i class="fa-brands fa-facebook-messenger text-[#1877F2]"></i>
                  <span>Nhắn Tin Tư Vấn</span>
                </a>
              </div>
            </div>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- =====================================================================
       11. FOOTER CHUẨN FLATSOME (Cấu trúc 4 cột đơn giản dễ chỉnh sửa UX Builder)
       ===================================================================== -->
  <footer class="bg-slate-900 text-slate-300 pt-10 pb-24 md:pb-10 border-t border-slate-800">
    <div class="flatsome-container">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 pb-8 border-b border-slate-800">
        
        <!-- Cột 1: Thông tin Hằng Sport -->
        <div class="space-y-3">
          <div class="font-display font-black text-xl text-white tracking-tight">
            HẰNG <span class="text-brand-red">SPORT</span>
          </div>
          <p class="text-xs text-slate-400 leading-relaxed">
            CÔNG TY TNHH TM&amp;DV HẰNG SPORT – Chuyên cung cấp thiết bị thể thao, vợt Pickleball chính hãng, trang phục thể thao, dụng cụ &amp; hoá chất xử lý nước bể bơi uy tín tại Đà Nẵng.
          </p>
          <div class="text-xs space-y-1.5 text-slate-300">
            <div><strong class="text-white">Website:</strong> hangsport.com</div>
            <div><strong class="text-white">Hotline / Zalo:</strong> <a href="tel:0972143287" class="text-amber-400 font-bold">0972.143.287</a></div>
            <div><strong class="text-white">Fanpage:</strong> <a href="https://www.facebook.com/duy.hang.357" target="_blank" rel="noopener" class="text-blue-400 hover:underline">facebook.com/duy.hang.357</a></div>
          </div>
        </div>

        <!-- Cột 2: Hệ thống cửa hàng -->
        <div class="space-y-3">
          <h4 class="font-display font-bold text-sm uppercase text-white tracking-wider">HỆ THỐNG CỬA HÀNG</h4>
          <ul class="space-y-2.5 text-xs text-slate-300">
            <li class="flex items-start gap-2">
              <i class="fa-solid fa-location-dot text-brand-red mt-1 shrink-0"></i>
              <span><strong class="text-white">Cơ sở 1:</strong> K7/5 Phan Văn Định, Hòa Khánh Bắc, Liên Chiểu, Đà Nẵng</span>
            </li>
            <li class="flex items-start gap-2">
              <i class="fa-solid fa-location-dot text-amber-400 mt-1 shrink-0"></i>
              <span><strong class="text-white">Cơ sở 2:</strong> 920 Tôn Đức Thắng, Hòa Khánh Bắc, Liên Chiểu, Đà Nẵng</span>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-solid fa-clock text-emerald-400 shrink-0"></i>
              <span>Giờ mở cửa: 07:30 – 21:30 (Tất cả các ngày)</span>
            </li>
          </ul>
        </div>

        <!-- Cột 3: Danh mục sản phẩm (Từ kimsshop.vn) -->
        <div class="space-y-3">
          <h4 class="font-display font-bold text-sm uppercase text-white tracking-wider">DANH MỤC SẢN PHẨM</h4>
          <ul class="space-y-2 text-xs">
            <li><a href="#san-pham-section" data-cat="pickleball" class="cat-filter-trigger hover:text-white transition">• Vợt Pickleball &amp; Bóng Pickleball</a></li>
            <li><a href="#san-pham-section" data-cat="giay-the-thao" class="cat-filter-trigger hover:text-white transition">• Giày Thể Thao &amp; Giày Pickleball</a></li>
            <li><a href="#san-pham-section" data-cat="quan-ao-the-thao" class="cat-filter-trigger hover:text-white transition">• Áo Thể Thao, Đồ Tập Yoga, Đồ Bơi</a></li>
            <li><a href="#san-pham-section" data-cat="dung-cu-ho-boi" class="cat-filter-trigger hover:text-white transition">• Dụng Cụ Vệ Sinh Hồ Bơi Chuyên Dụng</a></li>
            <li><a href="#san-pham-section" data-cat="hoa-chat-ho-boi" class="cat-filter-trigger hover:text-white transition">• Chlorin Xử Lý Nước Hồ Bơi</a></li>
            <li><a href="#san-pham-section" data-cat="phao-boi" class="cat-filter-trigger hover:text-white transition">• Phao Bơi Cứu Hộ &amp; Phụ Kiện Thể Thao</a></li>
          </ul>
        </div>

        <!-- Cột 4: Chính sách khách hàng -->
        <div class="space-y-3">
          <h4 class="font-display font-bold text-sm uppercase text-white tracking-wider">HỖ TRỢ KHÁCH HÀNG</h4>
          <ul class="space-y-2 text-xs">
            <li><a href="#form-bao-gia" class="hover:text-white transition">• Chính sách báo giá sỉ CLB &amp; Trường học</a></li>
            <li><a href="#form-bao-gia" class="hover:text-white transition">• Chính sách bảo hành &amp; Đổi trả hàng</a></li>
            <li><a href="#form-bao-gia" class="hover:text-white transition">• Chính sách giao hàng nhanh tại Đà Nẵng</a></li>
            <li><a href="#he-thong-cua-hang" class="hover:text-white transition">• Hướng dẫn chỉ đường Google Maps</a></li>
          </ul>
        </div>

      </div>

      <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400">
        <div>Copyright 2026 © <strong class="text-white">hangsport.com</strong> - Thiết kế chuẩn Flatsome UX Builder.</div>
        <div>Hotline/Zalo: <strong class="text-amber-400">0972.143.287</strong></div>
      </div>
    </div>
  </footer>

  <!-- =====================================================================
       12. CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE 0972.143.287)
       ===================================================================== -->
  <div class="fixed right-3 sm:right-5 bottom-4 sm:bottom-6 z-50 flex flex-col items-end gap-3">
    
    <!-- Nút Zalo Nổi Bật -->
    <a
      href="https://zalo.me/0972143287"
      target="_blank"
      rel="noopener"
      aria-label="Chat Zalo 0972.143.287"
      class="group flex items-center gap-2.5 bg-[#0068ff] hover:bg-blue-700 text-white rounded-full p-1.5 pr-3.5 shadow-xl transition transform hover:scale-105"
    >
      <div class="relative w-10 h-10 rounded-full bg-white text-[#0068ff] font-display font-black text-xs flex items-center justify-center shrink-0 floating-btn-ring">
        Zalo
      </div>
      <div class="leading-tight text-left">
        <div class="text-[10px] text-blue-100">Tư vấn 24/7</div>
        <div class="text-xs font-bold">Chat Zalo</div>
      </div>
    </a>

    <!-- Nút Facebook Fanpage Nổi Bật -->
    <a
      href="https://www.facebook.com/duy.hang.357"
      target="_blank"
      rel="noopener"
      aria-label="Fanpage Facebook Hằng Sport"
      class="group flex items-center gap-2.5 bg-[#1877F2] hover:bg-blue-800 text-white rounded-full p-1.5 pr-3.5 shadow-xl transition transform hover:scale-105"
    >
      <div class="relative w-10 h-10 rounded-full bg-white text-[#1877F2] flex items-center justify-center shrink-0 floating-btn-ring">
        <i class="fa-brands fa-facebook-f text-lg"></i>
      </div>
      <div class="leading-tight text-left">
        <div class="text-[10px] text-blue-100">Fanpage</div>
        <div class="text-xs font-bold">Hằng Sport</div>
      </div>
    </a>

    <!-- Nút Hotline Gọi Ngay Nổi Bật -->
    <a
      href="tel:0972143287"
      aria-label="Gọi Hotline 0972.143.287"
      class="group flex items-center gap-2.5 bg-brand-red hover:bg-red-700 text-white rounded-full p-1.5 pr-4 shadow-xl transition transform hover:scale-105"
    >
      <div class="relative w-10 h-10 rounded-full bg-white text-brand-red flex items-center justify-center shrink-0 floating-btn-ring">
        <i class="fa-solid fa-phone-volume text-base"></i>
      </div>
      <div class="leading-tight text-left">
        <div class="text-[10px] text-red-100">Hotline Gọi Ngay</div>
        <div class="text-xs sm:text-sm font-extrabold">0972.143.287</div>
      </div>
    </a>

  </div>

  <!-- =====================================================================
       13. DRAWER MENU DANH MỤC TRÊN ĐIỆN THOẠI & MODAL XEM NHANH / GIỎ HÀNG
       ===================================================================== -->
  <div id="mobileMenuDrawer" class="fixed inset-0 z-50 hidden">
    <div id="mobileMenuBackdrop" class="absolute inset-0 bg-slate-900/60 backdrop-blur-xs"></div>
    <div class="relative w-72 max-w-[85vw] h-full bg-white shadow-2xl flex flex-col justify-between overflow-y-auto">
      <div>
        <div class="p-4 bg-brand-blue text-white flex items-center justify-between">
          <div class="font-display font-black text-base">HẰNG SPORT MENU</div>
          <button id="closeMobileMenuBtn" type="button" class="w-8 h-8 rounded-lg bg-white/15 text-white flex items-center justify-center">
            <i class="fa-solid fa-xmark"></i>
          </button>
        </div>
        <div class="p-3 border-b border-slate-100 text-xs font-bold text-slate-400 uppercase tracking-wider">
          Danh mục sản phẩm
        </div>
        <div class="divide-y divide-slate-100 text-sm font-medium text-slate-700">
          <a href="#san-pham-section" data-cat="all" class="mobile-cat-link flex items-center justify-between px-4 py-3 hover:bg-blue-50">
            <span>Tất cả sản phẩm</span>
            <i class="fa-solid fa-chevron-right text-xs text-slate-400"></i>
          </a>
          <a href="#san-pham-section" data-cat="pickleball" class="mobile-cat-link flex items-center justify-between px-4 py-3 hover:bg-blue-50">
            <span>Vợt Pickleball Chính Hãng</span>
            <i class="fa-solid fa-chevron-right text-xs text-slate-400"></i>
          </a>
          <a href="#san-pham-section" data-cat="giay-the-thao" class="mobile-cat-link flex items-center justify-between px-4 py-3 hover:bg-blue-50">
            <span>Giày Thể Thao &amp; Pickleball</span>
            <i class="fa-solid fa-chevron-right text-xs text-slate-400"></i>
          </a>
          <a href="#san-pham-section" data-cat="quan-ao-the-thao" class="mobile-cat-link flex items-center justify-between px-4 py-3 hover:bg-blue-50">
            <span>Áo Thể Thao &amp; Đồ Tập Yoga</span>
            <i class="fa-solid fa-chevron-right text-xs text-slate-400"></i>
          </a>
          <a href="#san-pham-section" data-cat="dung-cu-the-thao" class="mobile-cat-link flex items-center justify-between px-4 py-3 hover:bg-blue-50">
            <span>Bóng Đá, Bóng Rổ &amp; Dụng Cụ</span>
            <i class="fa-solid fa-chevron-right text-xs text-slate-400"></i>
          </a>
          <a href="#san-pham-section" data-cat="dung-cu-ho-boi" class="mobile-cat-link flex items-center justify-between px-4 py-3 hover:bg-blue-50">
            <span>Dụng Cụ Vệ Sinh Hồ Bơi</span>
            <i class="fa-solid fa-chevron-right text-xs text-slate-400"></i>
          </a>
          <a href="#san-pham-section" data-cat="hoa-chat-ho-boi" class="mobile-cat-link flex items-center justify-between px-4 py-3 hover:bg-blue-50">
            <span>Chlorin Xử Lý Nước Hồ Bơi</span>
            <i class="fa-solid fa-chevron-right text-xs text-slate-400"></i>
          </a>
          <a href="#san-pham-section" data-cat="phao-boi" class="mobile-cat-link flex items-center justify-between px-4 py-3 hover:bg-blue-50">
            <span>Phao Bơi &amp; Đồ Bơi Cứu Hộ</span>
            <i class="fa-solid fa-chevron-right text-xs text-slate-400"></i>
          </a>
          <a href="#san-pham-section" data-cat="phu-kien-the-thao" class="mobile-cat-link flex items-center justify-between px-4 py-3 hover:bg-blue-50">
            <span>Phụ Kiện &amp; Balo Thể Thao</span>
            <i class="fa-solid fa-chevron-right text-xs text-slate-400"></i>
          </a>
        </div>
      </div>

      <div class="p-4 bg-slate-50 border-t border-slate-200 text-xs space-y-2">
        <div class="font-bold text-brand-blue">HẰNG SPORT ĐÀ NẴNG</div>
        <div><strong>CS 1:</strong> K7/5 Phan Văn Định, Liên Chiểu</div>
        <div><strong>CS 2:</strong> 920 Tôn Đức Thắng, Liên Chiểu</div>
        <div><strong>SĐT:</strong> <a href="tel:0972143287" class="text-brand-red font-bold">0972.143.287</a></div>
      </div>
    </div>
  </div>

  <!-- Modal Giỏ Hàng / Đặt Hàng Nhanh -->
  <div id="cartModal" class="fixed inset-0 z-50 hidden items-center justify-center p-3 bg-slate-900/60 backdrop-blur-xs">
    <div class="bg-white rounded-2xl max-w-md w-full p-5 shadow-2xl border border-slate-200">
      <div class="flex items-center justify-between border-b border-slate-100 pb-3 mb-3">
        <h3 class="font-display font-bold text-base text-brand-blue flex items-center gap-2">
          <i class="fa-solid fa-cart-shopping"></i>
          <span>Giỏ Hàng Của Bạn</span>
        </h3>
        <button id="closeCartModalBtn" type="button" class="w-8 h-8 rounded-lg bg-slate-100 text-slate-600 flex items-center justify-center">
          <i class="fa-solid fa-xmark"></i>
        </button>
      </div>
      <div id="cartItemsList" class="max-h-64 overflow-y-auto divide-y divide-slate-100 text-xs space-y-2 mb-4"></div>
      <div class="flex items-center justify-between font-bold text-sm border-t border-slate-200 pt-3 mb-4">
        <span>Tổng tạm tính:</span>
        <span id="cartTotalPrice" class="text-brand-red text-base">0₫</span>
      </div>
      <div class="grid grid-cols-2 gap-2">
        <a href="#form-bao-gia" id="checkoutToQuoteBtn" class="py-2.5 px-4 rounded-lg bg-brand-red hover:bg-red-700 text-white font-bold text-xs text-center transition">
          Gửi Đơn Đặt Hàng
        </a>
        <a href="https://zalo.me/0972143287" target="_blank" rel="noopener" class="py-2.5 px-4 rounded-lg bg-brand-blue hover:bg-brand-darkBlue text-white font-bold text-xs text-center transition">
          Đặt Qua Zalo Ngay
        </a>
      </div>
    </div>
  </div>

  <!-- =====================================================================
       14. JAVASCRIPT XỬ LÝ DỮ LIỆU 14 ẢNH THỰC TẾ, GIÁ GIẢM % FLATSOME & SLIDER
       ===================================================================== -->
  <script>
    // Danh sách 14 sản phẩm thực tế gắn với đúng 14 ID ảnh Google Drive của khách hàng cung cấp
    const PRODUCTS_DATA = [
      {
        id: 1,
        driveId: '1Om7yPcguqire3orOjyaPTpq2EEePI3JA',
        category: 'pickleball',
        categoryLabel: 'Vợt Pickleball',
        name: 'Vợt Pickleball Carbon Pro Series Chính Hãng Hằng Sport',
        oldPrice: 1450000,
        price: 1190000
      },
      {
        id: 2,
        driveId: '1uTK01kF8p08fEqbXejedGQm77gJzZpoZ',
        category: 'giay-the-thao',
        categoryLabel: 'Giày thể thao',
        name: 'Giày Thể Thao & Pickleball Chống Trượt Cao Cấp',
        oldPrice: 890000,
        price: 720000
      },
      {
        id: 3,
        driveId: '1hlKEOiR3vfugBdGYEXpVEoIzexInAfEE',
        category: 'quan-ao-the-thao',
        categoryLabel: 'Áo thể thao',
        name: 'Bộ Quần Áo Thể Thao Nam Nữ Co Giãn Thoáng Khí',
        oldPrice: 350000,
        price: 265000
      },
      {
        id: 4,
        driveId: '16e_CFTuNfMFeCwssNtMgK6SCnPo_KXfb',
        category: 'dung-cu-the-thao',
        categoryLabel: 'Dụng cụ thể thao',
        name: 'Bóng Thi Đấu Thể Thao & Phụ Kiện Tập Luyện Chuẩn',
        oldPrice: 420000,
        price: 330000
      },
      {
        id: 5,
        driveId: '1gg82tfmnzVBuspaU5SzLcXhmRifwmvEV',
        category: 'dung-cu-ho-boi',
        categoryLabel: 'Dụng cụ hồ bơi',
        name: 'Bàn Hút Vệ Sinh Hồ Bơi Cầm Tay Có Bánh Xe Chuyên Dụng',
        oldPrice: 350000,
        price: 220000
      },
      {
        id: 6,
        driveId: '1QlBugiGee33QXnZJl6gCDft2576RSxqJ',
        category: 'hoa-chat-ho-boi',
        categoryLabel: 'Chlorin xử lí nước hồ bơi',
        name: 'Hoá Chất K-Chlorine 70% Khử Trùng & Làm Trong Nước Hồ Bơi',
        oldPrice: 1250000,
        price: 980000
      },
      {
        id: 7,
        driveId: '1U3mvpPaxc_eJjsiqoXwgRp6ZUgL8MKXm',
        category: 'phao-boi',
        categoryLabel: 'Phao bơi',
        name: 'Áo Phao Bơi Cứu Hộ Người Lớn & Trẻ Em An Toàn',
        oldPrice: 165000,
        price: 128000
      },
      {
        id: 8,
        driveId: '17LOsACaJMoqibajt3ds7-hGmNirfzpf-',
        category: 'phu-kien-the-thao',
        categoryLabel: 'Phụ Kiện Thể Thao',
        name: 'Balo & Túi Đựng Vợt Pickleball Thể Thao Chống Thấm',
        oldPrice: 480000,
        price: 379000
      },
      {
        id: 9,
        driveId: '1CJ15aKlk2iSknSqf4uebCriw2bc53Ena',
        category: 'pickleball',
        categoryLabel: 'Vợt Pickleball',
        name: 'Vợt Pickleball T700 Mặt Nhám Kiểm Soát Bóng Tối Ưu',
        oldPrice: 1690000,
        price: 1390000
      },
      {
        id: 10,
        driveId: '1w_9XBgOmCHPnseCx25-X3D_vaxeXsatI',
        category: 'quan-ao-the-thao',
        categoryLabel: 'Áo thể thao',
        name: 'Áo Polo Thể Thao Thi Đấu CLB & Đội Nhóm Đà Nẵng',
        oldPrice: 290000,
        price: 225000
      },
      {
        id: 11,
        driveId: '1AtWd3TOWw-c8DKwndMouIMW4Y7R3lpoj',
        category: 'giay-the-thao',
        categoryLabel: 'Giày thể thao',
        name: 'Giày Cầu Lông & Bóng Chuyền Đế Kép Bám Sân Cực Tốt',
        oldPrice: 790000,
        price: 640000
      },
      {
        id: 12,
        driveId: '1dCRcgARamrvNws-PqdyaVhGMydih09Ep',
        category: 'dung-cu-ho-boi',
        categoryLabel: 'Dụng cụ hồ bơi',
        name: 'Chổi Cọ & Vợt Rác Vệ Sinh Bể Bơi Kèm Sào Nhôm',
        oldPrice: 250000,
        price: 185000
      },
      {
        id: 13,
        driveId: '1Cyluyr7ZBwXVEpnam9wO6XitI7M_9ya1',
        category: 'dung-cu-the-thao',
        categoryLabel: 'Dụng cụ thể thao',
        name: 'Bộ Dụng Cụ Tập Thể Lực, Thảm Tập Yoga & Dã Ngoại',
        oldPrice: 340000,
        price: 270000
      },
      {
        id: 14,
        driveId: '1QWcPYuAQqjFN4f69UeFaurNqSWwCJtss',
        category: 'pickleball',
        categoryLabel: 'Bóng Pickleball chính hãng',
        name: 'Hộp Bóng Thi Đấu Pickleball 40 Lỗ Chuẩn Outdoor',
        oldPrice: 260000,
        price: 195000
      }
    ];

    // Danh sách bài viết trang chủ (Dùng ảnh thực tế từ Google Drive)
    const BLOG_POSTS = [
      {
        id: 1,
        cat: 'pickleball',
        catName: 'Tư vấn Pickleball',
        date: '02/11/2026',
        driveId: '1Om7yPcguqire3orOjyaPTpq2EEePI3JA',
        title: 'Kinh nghiệm chọn mua Vợt Pickleball chính hãng phù hợp cho người mới tại Đà Nẵng',
        excerpt: 'Hướng dẫn cách chọn trọng lượng vợt, độ dày lõi 14mm hay 16mm và địa chỉ trải nghiệm trực tiếp tại Hằng Sport Liên Chiểu.'
      },
      {
        id: 2,
        cat: 'trang-phuc',
        catName: 'Giày & Trang phục',
        date: '28/10/2026',
        driveId: '1uTK01kF8p08fEqbXejedGQm77gJzZpoZ',
        title: 'Bí quyết chọn giày Pickleball và quần áo thể thao thoáng khí, chống chấn thương cổ chân',
        excerpt: 'Tại sao người chơi Pickleball và cầu lông cần sử dụng giày đế bằng chuyên dụng thay vì giày chạy bộ thông thường?'
      },
      {
        id: 3,
        cat: 'ho-boi',
        catName: 'Kỹ thuật Hồ bơi',
        date: '22/10/2026',
        driveId: '1gg82tfmnzVBuspaU5SzLcXhmRifwmvEV',
        title: 'Quy trình vệ sinh hồ bơi và sử dụng hoá chất Chlorine 70% an toàn, nước trong xanh',
        excerpt: 'Trọn bộ hướng dẫn kết hợp bàn hút đáy, sào nhôm, vợt rác và liều lượng Chlorine chuẩn cho hồ bơi gia đình, trường học.'
      }
    ];

    // Định dạng tiền tệ VNĐ
    function formatVND(amount) {
      return amount.toString().replace(/\B(?=(\d{3})+(?!\d))/g, '.') + '₫';
    }

    // Tính % giảm giá giống Flatsome
    function calcDiscountPercent(oldPrice, newPrice) {
      if (!oldPrice || oldPrice <= newPrice) return 0;
      return Math.round(((oldPrice - newPrice) / oldPrice) * 100);
    }

    // Tạo thẻ sản phẩm chuẩn Flatsome (Không để nhãn dán đè lên ảnh, hiển thị giá gốc + giá giảm + % giảm giá ở khu vực giá)
    function createProductCardHTML(product) {
      const percent = calcDiscountPercent(product.oldPrice, product.price);
      const imgUrl = `https://drive.google.com/thumbnail?id=${product.driveId}&sz=w700`;

      return `
        <div class="product-small">
          <div class="box-image">
            <img
              data-drive-id="${product.driveId}"
              src="${imgUrl}"
              alt="${product.name}"
              loading="lazy"
            />
          </div>
          <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
            <div>
              <div class="text-[10px] sm:text-[11px] uppercase tracking-wide text-slate-400 font-semibold mb-1 truncate">
                ${product.categoryLabel}
              </div>
              <h3 class="text-xs sm:text-sm font-bold text-slate-800 hover:text-brand-blue line-clamp-2 leading-snug min-h-[2.5rem]">
                ${product.name}
              </h3>
            </div>

            <div class="mt-2.5 pt-2 border-t border-slate-100">
              <!-- Khu vực giá gốc, giá giảm & % giảm giá chuẩn Flatsome -->
              <div class="price-wrapper flex flex-wrap items-baseline gap-x-1.5 gap-y-1">
                <del class="text-[11px] sm:text-xs text-slate-400 font-normal">${formatVND(product.oldPrice)}</del>
                <ins class="text-xs sm:text-base font-extrabold text-brand-red no-underline">${formatVND(product.price)}</ins>
                <span class="text-[10px] sm:text-[11px] font-bold text-brand-red bg-red-50 border border-red-200 px-1.5 py-0.5 rounded">
                  -${percent}%
                </span>
              </div>

              <div class="mt-2.5 grid grid-cols-2 gap-1.5">
                <button
                  type="button"
                  onclick="addToCart(${product.id})"
                  class="py-1.5 px-2 rounded-lg bg-brand-blue hover:bg-brand-darkBlue text-white font-semibold text-[11px] sm:text-xs transition flex items-center justify-center gap-1"
                >
                  <i class="fa-solid fa-cart-plus"></i>
                  <span>Thêm giỏ</span>
                </button>
                <a
                  href="#form-bao-gia"
                  onclick="prefillQuoteProduct('${product.name.replace(/'/g, "\\'")}')"
                  class="py-1.5 px-2 rounded-lg bg-slate-100 hover:bg-amber-100 text-slate-700 hover:text-slate-900 font-semibold text-[11px] sm:text-xs text-center transition"
                >
                  Báo giá
                </a>
              </div>
            </div>
          </div>
        </div>
      `;
    }

    // Cơ chế tự động chuyển đổi link dự phòng Google Drive nếu trình duyệt chặn thumbnail
    function attachDriveImageFallbacks() {
      const imgs = document.querySelectorAll('img[data-drive-id]');
      imgs.forEach((img) => {
        img.onerror = function () {
          const id = img.getAttribute('data-drive-id');
          const step = parseInt(img.getAttribute('data-fallback-step') || '0', 10);
          if (step === 0) {
            img.setAttribute('data-fallback-step', '1');
            img.src = `https://lh3.googleusercontent.com/d/${id}=w1000`;
          } else if (step === 1) {
            img.setAttribute('data-fallback-step', '2');
            img.src = `https://drive.google.com/uc?export=view&id=${id}`;
          } else {
            img.onerror = null;
          }
        };
      });
    }

    // Render lưới sản phẩm chính
    function renderMainProducts(filterCat = 'all', searchKeyword = '') {
      const container = document.getElementById('productGridContainer');
      const kw = searchKeyword.trim().toLowerCase();

      const filtered = PRODUCTS_DATA.filter((item) => {
        const matchCat =
          filterCat === 'all' ||
          item.category === filterCat ||
          (filterCat === 'dung-cu-ho-boi' &&
            (item.category === 'dung-cu-ho-boi' || item.category === 'hoa-chat-ho-boi' || item.category === 'phao-boi'));
        const matchKw = !kw || item.name.toLowerCase().includes(kw) || item.categoryLabel.toLowerCase().includes(kw);
        return matchCat && matchKw;
      });

      if (filtered.length === 0) {
        container.innerHTML = `
          <div class="col-span-2 md:col-span-3 lg:col-span-4 py-10 text-center text-slate-500 text-sm">
            Không tìm thấy sản phẩm phù hợp. Quý khách vui lòng liên hệ Hotline/Zalo <strong>0972.143.287</strong> để được tư vấn mẫu mới nhất!
          </div>
        `;
        return;
      }

      container.innerHTML = filtered.map(createProductCardHTML).join('');
      attachDriveImageFallbacks();
    }

    // Render khu vực Dụng cụ hồ bơi & Hoá chất
    function renderPoolSection() {
      const poolContainer = document.getElementById('poolProductsGrid');
      const poolItems = PRODUCTS_DATA.filter(
        (p) => p.category === 'dung-cu-ho-boi' || p.category === 'hoa-chat-ho-boi' || p.category === 'phao-boi'
      );
      poolContainer.innerHTML = poolItems.map(createProductCardHTML).join('');
      attachDriveImageFallbacks();
    }

    // Render danh mục bài viết trang chủ
    function renderBlogPosts(cat = 'all') {
      const container = document.getElementById('blogGridContainer');
      const list = cat === 'all' ? BLOG_POSTS : BLOG_POSTS.filter((b) => b.cat === cat);

      container.innerHTML = list
        .map(
          (post) => `
          <article class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-xs hover:shadow-md transition flex flex-col">
            <div class="aspect-video bg-slate-100 overflow-hidden">
              <img
                data-drive-id="${post.driveId}"
                src="https://drive.google.com/thumbnail?id=${post.driveId}&sz=w700"
                alt="${post.title}"
                class="w-full h-full object-cover hover:scale-105 transition duration-300"
              />
            </div>
            <div class="p-4 flex-1 flex flex-col justify-between">
              <div>
                <div class="flex items-center justify-between text-[11px] text-slate-400 mb-1.5">
                  <span class="font-semibold text-brand-blue">${post.catName}</span>
                  <span><i class="fa-regular fa-calendar mr-1"></i>${post.date}</span>
                </div>
                <h3 class="font-bold text-sm sm:text-base text-slate-800 hover:text-brand-blue line-clamp-2 mb-2">
                  ${post.title}
                </h3>
                <p class="text-xs text-slate-600 line-clamp-3 leading-relaxed">
                  ${post.excerpt}
                </p>
              </div>
              <div class="mt-3 pt-2.5 border-t border-slate-100 flex items-center justify-between">
                <a href="#form-bao-gia" class="text-xs font-bold text-brand-red hover:underline">
                  Tư vấn chi tiết →
                </a>
                <span class="text-[11px] text-slate-400">hangsport.com</span>
              </div>
            </div>
          </article>
        `
        )
        .join('');
      attachDriveImageFallbacks();
    }

    // Đồng bộ tỉ lệ khung hình 2 Banner tự trượt dựa vào kích thước thật của ảnh mẫu 1uBzqaXUo7B3pT9zKqA0kYAecZl_RUpHe
    const refImg = document.getElementById('referenceBannerImg');
    const bannerBox = document.getElementById('heroBannerContainer');
    if (refImg && bannerBox) {
      refImg.addEventListener('load', function () {
        if (refImg.naturalWidth > 0 && refImg.naturalHeight > 0 && window.innerWidth >= 768) {
          const ratio = refImg.naturalWidth / refImg.naturalHeight;
          const clampedRatio = Math.min(Math.max(ratio, 2.0), 3.2);
          bannerBox.style.aspectRatio = `${clampedRatio} / 1`;
        }
      });
    }

    // Điều khiển Slider 2 Banner tự trượt
    let currentBannerIndex = 0;
    const slides = document.querySelectorAll('.hero-slide');
    const dots = document.querySelectorAll('.banner-dot');

    function showBannerSlide(index) {
      currentBannerIndex = (index + slides.length) % slides.length;
      slides.forEach((s, idx) => {
        if (idx === currentBannerIndex) {
          s.classList.remove('opacity-0', 'z-0', 'pointer-events-none');
          s.classList.add('opacity-100', 'z-10');
        } else {
          s.classList.remove('opacity-100', 'z-10');
          s.classList.add('opacity-0', 'z-0', 'pointer-events-none');
        }
      });
      dots.forEach((d, idx) => {
        if (idx === currentBannerIndex) {
          d.className = 'banner-dot w-6 h-2 rounded-full bg-white transition-all';
        } else {
          d.className = 'banner-dot w-2 h-2 rounded-full bg-white/50 transition-all';
        }
      });
    }

    let bannerInterval = setInterval(() => {
      showBannerSlide(currentBannerIndex + 1);
    }, 4500);

    function resetBannerTimer() {
      clearInterval(bannerInterval);
      bannerInterval = setInterval(() => {
        showBannerSlide(currentBannerIndex + 1);
      }, 4500);
    }

    document.getElementById('prevBannerBtn').addEventListener('click', () => {
      showBannerSlide(currentBannerIndex - 1);
      resetBannerTimer();
    });
    document.getElementById('nextBannerBtn').addEventListener('click', () => {
      showBannerSlide(currentBannerIndex + 1);
      resetBannerTimer();
    });
    dots.forEach((dot) => {
      dot.addEventListener('click', () => {
        showBannerSlide(parseInt(dot.getAttribute('data-go-slide'), 10));
        resetBannerTimer();
      });
    });

    // Giỏ hàng đơn giản
    let cart = [];
    function addToCart(productId) {
      const prod = PRODUCTS_DATA.find((p) => p.id === productId);
      if (!prod) return;
      const existing = cart.find((item) => item.id === productId);
      if (existing) {
        existing.qty += 1;
      } else {
        cart.push({ ...prod, qty: 1 });
      }
      updateCartUI();
      openCartModal();
    }

    function updateCartUI() {
      const totalCount = cart.reduce((sum, item) => sum + item.qty, 0);
      const totalPrice = cart.reduce((sum, item) => sum + item.price * item.qty, 0);
      document.getElementById('cartCountBadge').textContent = totalCount;
      document.getElementById('cartTotalPrice').textContent = formatVND(totalPrice);

      const listEl = document.getElementById('cartItemsList');
      if (cart.length === 0) {
        listEl.innerHTML = `<div class="py-6 text-center text-slate-400">Chưa có sản phẩm trong giỏ hàng.</div>`;
        return;
      }
      listEl.innerHTML = cart
        .map(
          (item) => `
          <div class="py-2 flex items-center justify-between gap-2">
            <div class="flex-1">
              <div class="font-bold text-slate-800 line-clamp-1">${item.name}</div>
              <div class="text-slate-500">${formatVND(item.price)} x ${item.qty}</div>
            </div>
            <button type="button" onclick="removeCartItem(${item.id})" class="text-red-500 hover:text-red-700 px-2 py-1">
              <i class="fa-solid fa-trash-can"></i>
            </button>
          </div>
        `
        )
        .join('');
    }

    function removeCartItem(productId) {
      cart = cart.filter((item) => item.id !== productId);
      updateCartUI();
    }

    function openCartModal() {
      const modal = document.getElementById('cartModal');
      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }
    function closeCartModal() {
      const modal = document.getElementById('cartModal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
    }

    document.getElementById('cartOpenBtn').addEventListener('click', openCartModal);
    document.getElementById('closeCartModalBtn').addEventListener('click', closeCartModal);
    document.getElementById('checkoutToQuoteBtn').addEventListener('click', () => {
      closeCartModal();
      const summary = cart.map((c) => `${c.name} (SL: ${c.qty})`).join(', ');
      if (summary) {
        document.getElementById('quoteNote').value = `Đặt hàng: ${summary}`;
      }
    });

    // Điền nhanh tên sản phẩm vào Form Báo Giá
    function prefillQuoteProduct(productName) {
      const noteEl = document.getElementById('quoteNote');
      noteEl.value = `Tôi cần tư vấn & báo giá sản phẩm: ${productName}`;
    }

    // Lọc danh mục sản phẩm khi nhấn vào bất kỳ nút danh mục nào
    function activateCategoryFilter(cat) {
      renderMainProducts(cat);
      document.querySelectorAll('.cat-pill-btn').forEach((btn) => {
        if (btn.getAttribute('data-cat') === cat) {
          btn.className = 'cat-pill-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-brand-blue text-white shrink-0 transition';
        } else {
          btn.className = 'cat-pill-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-blue-50 shrink-0 transition';
        }
      });
    }

    document.querySelectorAll('.cat-filter-trigger, .cat-pill-btn').forEach((el) => {
      el.addEventListener('click', () => {
        const cat = el.getAttribute('data-cat') || 'all';
        activateCategoryFilter(cat);
      });
    });

    // Lọc danh mục bài viết
    document.querySelectorAll('.blog-cat-btn').forEach((btn) => {
      btn.addEventListener('click', () => {
        const cat = btn.getAttribute('data-blog-cat') || 'all';
        renderBlogPosts(cat);
        document.querySelectorAll('.blog-cat-btn').forEach((b) => {
          b.className =
            b === btn
              ? 'blog-cat-btn px-3 py-1 rounded-full text-xs font-semibold bg-brand-blue text-white shrink-0'
              : 'blog-cat-btn px-3 py-1 rounded-full text-xs font-medium bg-white border border-slate-200 text-slate-700 shrink-0';
        });
      });
    });

    // Tìm kiếm trên máy tính & điện thoại
    document.getElementById('desktopSearchForm').addEventListener('submit', (e) => {
      e.preventDefault();
      const kw = document.getElementById('desktopSearchInput').value;
      renderMainProducts('all', kw);
      document.getElementById('san-pham-section').scrollIntoView({ behavior: 'smooth' });
    });
    document.getElementById('mobileSearchForm').addEventListener('submit', (e) => {
      e.preventDefault();
      const kw = document.getElementById('mobileSearchInput').value;
      renderMainProducts('all', kw);
      document.getElementById('san-pham-section').scrollIntoView({ behavior: 'smooth' });
    });

    // Chuyển đổi Google Map giữa CS1 và CS2 ngoài trang chủ
    const mapIframe = document.getElementById('googleMapIframe');
    const mapBtnCS1 = document.getElementById('mapBtnCS1');
    const mapBtnCS2 = document.getElementById('mapBtnCS2');

    mapBtnCS1.addEventListener('click', () => {
      mapIframe.src =
        'https://maps.google.com/maps?q=K7/5%20Phan%20V%C4%83n%20%C4%90%E1%BB%8Bnh,%20H%C3%B2a%20Kh%C3%A1nh%20B%E1%BA%AFc,%20Li%C3%AAn%20Chi%E1%BB%83u,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed';
      mapBtnCS1.className = 'px-3 py-1.5 rounded-lg text-xs font-bold bg-brand-blue text-white transition';
      mapBtnCS2.className = 'px-3 py-1.5 rounded-lg text-xs font-bold bg-white border border-slate-300 text-slate-700 hover:border-brand-blue transition';
    });

    mapBtnCS2.addEventListener('click', () => {
      mapIframe.src =
        'https://maps.google.com/maps?q=920%20T%C3%B4n%20%C4%90%E1%BB%A9c%20Th%E1%BA%AFng,%20H%C3%B2a%20Kh%C3%A1nh%20B%E1%BA%AFc,%20Li%C3%AAn%20Chi%E1%BB%83u,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed';
      mapBtnCS2.className = 'px-3 py-1.5 rounded-lg text-xs font-bold bg-brand-blue text-white transition';
      mapBtnCS1.className = 'px-3 py-1.5 rounded-lg text-xs font-bold bg-white border border-slate-300 text-slate-700 hover:border-brand-blue transition';
    });

    // Xử lý gửi Form Yêu Cầu & Báo Giá
    document.getElementById('quoteRequestForm').addEventListener('submit', (e) => {
      e.preventDefault();
      const name = document.getElementById('quoteName').value.trim();
      const phone = document.getElementById('quotePhone').value.trim();
      const category = document.getElementById('quoteCategory').value;
      const branch = document.getElementById('quoteBranch').value;
      const msgBox = document.getElementById('quoteSuccessMsg');

      msgBox.classList.remove('hidden');
      msgBox.innerHTML = `<i class="fa-solid fa-circle-check text-emerald-600 mr-1"></i> Cảm ơn <strong>${name}</strong> (${phone})! Yêu cầu báo giá mục <strong>${category}</strong> tại <strong>${branch}</strong> đã được ghi nhận. Bộ phận tư vấn Hằng Sport (<strong>0972.143.287</strong>) sẽ liên hệ ngay!`;
      e.target.reset();
    });

    // Đóng/mở Drawer Menu trên điện thoại
    const mobileDrawer = document.getElementById('mobileMenuDrawer');
    document.getElementById('mobileMenuBtn').addEventListener('click', () => {
      mobileDrawer.classList.remove('hidden');
    });
    document.getElementById('closeMobileMenuBtn').addEventListener('click', () => {
      mobileDrawer.classList.add('hidden');
    });
    document.getElementById('mobileMenuBackdrop').addEventListener('click', () => {
      mobileDrawer.classList.add('hidden');
    });
    document.querySelectorAll('.mobile-cat-link').forEach((link) => {
      link.addEventListener('click', () => {
        const cat = link.getAttribute('data-cat') || 'all';
        activateCategoryFilter(cat);
        mobileDrawer.classList.add('hidden');
      });
    });

    // Khởi chạy trang
    window.addEventListener('DOMContentLoaded', () => {
      renderMainProducts('all');
      renderPoolSection();
      renderBlogPosts('all');
      updateCartUI();
      attachDriveImageFallbacks();
    });
  </script>
</body>
</html>
