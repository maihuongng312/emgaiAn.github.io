# emgaiAn.github.io
<!doctype html>
<html lang="vi">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Happy Wedding — Invitation</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700;900&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
<style>
:root{
--bg:#fff8f3;
--accent:#b94f6c;
--muted:#6b6b6b;
--card:#ffffff;
--glass: rgba(255,255,255,0.6);
--max-width:1100px;
}
*{box-sizing:border-box}
body{font-family:Inter,system-ui,Segoe UI,Roboto,Arial;line-height:1.5;margin:0;background:linear-gradient(180deg,var(--bg),#fff);color:#222}
.container{max-width:var(--max-width);margin:0 auto;padding:24px}


/* Header / Hero */
.hero{display:grid;grid-template-columns:1fr;gap:20px;align-items:center;padding:48px 16px;background-image:linear-gradient(180deg, rgba(255,255,255,0.6), rgba(255,250,250,0.8));border-radius:18px;margin-top:24px;box-shadow:0 6px 30px rgba(0,0,0,0.06)}
.hero-inner{display:flex;flex-direction:column;align-items:center;text-align:center;padding:24px}
.couple-name{font-family:'Playfair Display',serif;font-size:38px;font-weight:700;color:var(--accent);letter-spacing:1px;margin:4px 0}
.subtitle{color:var(--muted);margin-bottom:12px}
.date{font-weight:600;color:#444}


.photo-wrap{width:260px;height:260px;border-radius:50%;overflow:hidden;box-shadow:0 8px 40px rgba(0,0,0,0.08);border:10px solid rgba(255,255,255,0.5);background:linear-gradient(135deg,#fff,#fff0)}
.photo-wrap img{width:100%;height:100%;object-fit:cover;display:block}


.cta{margin-top:16px}
.btn{display:inline-block;background:var(--accent);color:white;padding:10px 18px;border-radius:999px;text-decoration:none;font-weight:600;box-shadow:0 6px 18px rgba(185,79,108,0.18)}


/* Sections */
section{margin:40px 0}
.card{background:var(--card);padding:20px;border-radius:14px;box-shadow:0 6px 20px rgba(20,20,20,0.04)}


/* Countdown */
.countdown{display:flex;gap:12px;justify-content:center}
.countdown .item{min-width:70px;background:var(--glass);backdrop-filter:blur(6px);padding:12px;border-radius:10px;text-align:center}
.countdown .num{font-family:'Playfair Display',serif;font-size:22px;font-weight:700}
.countdown .label{font-size:12px;color:var(--muted)}


/* Program */
.program-list{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:12px}
.program-item{padding:12px;border-radius:10px;border-left:4px solid var(--accent);background:linear-gradient(180deg,#fff,#fffefc)}


/* Gallery */
.gallery-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(140px,1fr));gap:8px}
.gallery-grid img{width:100%;height:140px;object-fit:cover;border-radius:8px;cursor:pointer}


/* RSVP */
.rsvp-form{display:grid;grid-template-columns:1fr;gap:8px}
input,textarea,select{padding:10px;border-radius:8px;border:1px solid #e6e6e6;font-size:14px}
.row{display:flex;gap:8px}
@media(min-width:900px){
.hero{grid-template-columns:1fr 360px}
.hero-inner{text-align:left;align-items:flex-start}
}


/* Footer */
footer{padding:30px 0;text-align:center;color:var(--muted);font-size:14px}


/* Smooth scroll */
html{scroll-behavior:smooth}


/* Lightbox */
.lightbox{position:fixed;inset:0;display:none;align-items:center;justify-content:center;background:rgba(0,0,0,0.7);z-index:90}
.lightbox img{max-width:92%;max-height:86%;border-radius:8px}


/* small helpers */
.muted{color:var(--muted)}
</style>
</head>
<body>
<div class="container">
<header class="hero">
<div class="hero-inner">
<p class="muted">Lời mời trân trọng</p>
<h1 class="couple-name">Ngọc &amp; Thành</h1>
<p class="subtitle">Chúng tôi hân hạnh mời bạn tới chung vui trong ngày trọng đại</p>
<p class="date">Thứ Bảy, 20 Tháng 12, 2025 — 10:00 AM</p>
<div class="cta">
<a href="#rsvp" class="btn">Xác nhận tham dự</a>
</div>


<div style="margin-top:20px;" class="card" aria-hidden>
<div style="display:flex;gap:12px;align-items:center">
<div style="flex:1">
<strong>Địa điểm</strong>
<div class="muted">Nhà hàng Hoa Sen — 123 Đường Hạnh Phúc, Hà Nội</div>
</div>
<div style="text-align:right">
</html>
