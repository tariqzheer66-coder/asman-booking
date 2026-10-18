# asman-booking
Asman Booking — Find and book hotels in Sulaymaniyah, Kurdistan, Iraq.
<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="theme-color" content="#155eef">
<title>Asman Booking</title>

<style>
/* ================= BASE ================= */
*{box-sizing:border-box;margin:0;padding:0}
:root{
 --blue:#155eef;--blue-dark:#1048c7;--green:#18a57b;
 --dark:#14213d;--muted:#667085;--bg:#f5f7fb;
 --border:#dce2eb;--white:#fff;--card:#fff;
 --soft:#eef3ff;--shadow:0 4px 18px #15294b0b;
}
body.dark-theme{
 --blue:#79a4ff;--blue-dark:#5285ef;--green:#45d4a7;
 --dark:#edf2fa;--muted:#aab6c8;--bg:#101521;
 --border:#303b4e;--white:#1b2433;--card:#1b2433;
 --soft:#263247;--shadow:0 4px 18px #0003;
 color-scheme:dark;
}
html{scroll-behavior:smooth;-webkit-text-size-adjust:100%}
body{
 font-family:Arial,sans-serif;background:var(--bg);color:var(--dark);
 line-height:1.55;min-width:320px;transition:background .25s,color .25s;
}
img{max-width:100%}
button,input,select{font:inherit}
button{cursor:pointer;border:0;-webkit-tap-highlight-color:transparent}
input,select{min-width:0;max-width:100%}
button:focus-visible,input:focus-visible,select:focus-visible{
 outline:3px solid #9bbcff;outline-offset:2px
}
[hidden]{display:none!important}

/* ================= HEADER ================= */
header{
 background:var(--white);padding:14px 5%;display:flex;
 align-items:center;justify-content:space-between;gap:14px;
 box-shadow:0 2px 12px #0000000b;position:sticky;top:0;z-index:10;
 transition:background .25s;
}
.logo{font-size:25px;font-weight:800;color:var(--blue);white-space:nowrap}
.logo span{color:var(--green)}
.nav-right{display:flex;align-items:center;gap:12px}
#languageSelect{
 padding:9px;border:1px solid var(--border);border-radius:9px;
 background:var(--white);color:var(--dark);max-width:130px
}
.btn{
 display:inline-flex;align-items:center;justify-content:center;
 gap:7px;padding:11px 16px;border-radius:9px;background:var(--blue);
 color:#fff;font-weight:bold;text-align:center;text-decoration:none;
 transition:background .2s,transform .2s;
}
.btn:hover{background:var(--blue-dark);color:#fff}
.btn:active{transform:scale(.98)}
.btn.secondary{background:var(--soft);color:var(--blue)}
.wide{width:100%}

/* ================= HERO AND SEARCH ================= */
.hero{
 padding:50px 5% 42px;color:#fff;
 background:linear-gradient(120deg,#102b60,#155eef);
}
.hero h1{font-size:clamp(29px,5vw,46px);line-height:1.25;margin-bottom:12px}
.hero p{font-size:16px;line-height:1.8;max-width:680px}
.search{
 display:grid;grid-template-columns:minmax(160px,2fr) repeat(3,minmax(105px,1fr)) auto;
 gap:10px;background:#fff;color:#14213d;padding:14px;border-radius:14px;
 margin-top:25px;max-width:1150px;box-shadow:0 8px 25px #081d4515;
}
.field{display:flex;flex-direction:column;gap:7px;min-width:0}
.field label{font-size:12px;color:#667085;font-weight:bold}
.field input,.field select{
 width:100%;padding:11px;border:1px solid #dce2eb;border-radius:8px;
 background:#fff;color:#14213d;
}
.search .btn{align-self:end;white-space:nowrap}

/* ================= HOTEL GRID ================= */
.container{padding:35px 5%;max-width:1450px;margin:auto}
.section-head{
 display:flex;justify-content:space-between;align-items:center;
 gap:12px;flex-wrap:wrap;margin-bottom:20px
}
.section-head h2{font-size:25px}
#resultCount{color:var(--muted);font-size:14px}
.hotel-grid{
 display:grid;grid-template-columns:repeat(4,minmax(0,1fr));gap:20px
}
.hotel-card{
 background:var(--card);border:1px solid var(--border);border-radius:15px;
 overflow:hidden;box-shadow:var(--shadow);min-width:0;
 transition:background .25s,transform .2s;
}
.hotel-card:hover{transform:translateY(-3px)}
.hotel-card>img{
 display:block;width:100%;height:190px;object-fit:cover;background:#e4e9f1
}
.hotel-info{padding:16px}
.hotel-info h3{font-size:18px;margin-bottom:9px;overflow-wrap:anywhere}
.location{font-size:13px;color:var(--muted);margin-bottom:10px}
.rating{
 display:inline-block;background:#e8f1ff;color:#164db5;
 padding:5px 8px;border-radius:6px;font-size:13px;font-weight:bold;
 margin-bottom:12px
}
.amenity-preview{font-size:13px;color:var(--muted);line-height:1.8;min-height:42px}
.price-row{
 display:flex;justify-content:space-between;align-items:center;
 flex-wrap:wrap;gap:9px;margin-top:14px
}
.price{font-size:18px;font-weight:bold}
.price small{font-size:12px;color:var(--muted);font-weight:normal}
.empty{
 grid-column:1/-1;text-align:center;padding:40px;background:var(--card);
 border-radius:12px;color:var(--muted)
}
footer{text-align:center;padding:25px;color:var(--muted);font-size:13px}

/* ================= MODALS ================= */
.modal{
 display:none;position:fixed;inset:0;background:#0b173bb5;z-index:30;
 overflow-y:auto;padding:16px;align-items:center;justify-content:center;
}
.modal.show{display:flex}
.modal-box{
 width:100%;max-width:850px;background:var(--white);color:var(--dark);
 border:1px solid var(--border);border-radius:16px;position:relative;
 padding:25px;max-height:92vh;overflow-y:auto;
}
.modal-box.small{max-width:520px}
.close{
 position:absolute;top:12px;right:14px;width:36px;height:36px;
 border-radius:50%;background:var(--soft);color:var(--dark);
 font-size:24px;display:flex;align-items:center;justify-content:center
}
[dir="rtl"] .close{right:auto;left:14px}
.modal-box h2{font-size:24px;margin:4px 42px 18px 0;overflow-wrap:anywhere}
[dir="rtl"] .modal-box h2{margin:4px 0 18px 42px}
.gallery{display:grid;grid-template-columns:2fr 1fr;gap:9px;margin-bottom:20px}
.gallery img{
 width:100%;height:230px;object-fit:cover;border-radius:10px;background:#e4e9f1
}
.detail-description{color:var(--muted);line-height:1.8;margin-bottom:18px}
.amenities{
 display:grid;grid-template-columns:repeat(3,minmax(0,1fr));
 gap:10px;margin:14px 0 25px
}
.amenity{padding:11px;background:var(--bg);border-radius:9px;font-size:14px}
.room-list{
 display:grid;grid-template-columns:repeat(3,minmax(0,1fr));
 gap:12px;margin-top:15px
}
.room{
 border:1px solid var(--border);border-radius:12px;overflow:hidden;
 min-width:0;background:var(--card)
}
.room img{display:block;width:100%;height:140px;object-fit:cover;background:#e4e9f1}
.room-content{padding:12px}
.room-content h4{margin-bottom:7px}
.room-content p{font-size:13px;color:var(--muted);margin-bottom:10px;line-height:1.6}
.room-content .price{display:block;margin-bottom:10px}
.form-grid{
 display:grid;grid-template-columns:repeat(2,minmax(0,1fr));
 gap:14px;margin:15px 0
}
.form-grid .field.full{grid-column:1/-1}
.total-box{background:var(--soft);padding:15px;border-radius:10px;margin:15px 0;line-height:1.9}
.total-line{display:flex;justify-content:space-between;gap:12px;flex-wrap:wrap}
.notice{font-size:13px;line-height:1.7;color:var(--muted);margin:12px 0}
hr{border:0;border-top:1px solid var(--border);margin:15px 0}

/* ================= DARK MODE DETAILS ================= */
body.dark-theme .hero{
 background:linear-gradient(120deg,#101a30,#243e70)
}
body.dark-theme .field input,body.dark-theme .field select{
 background:#141c2a;color:#edf2fa;border-color:var(--border)
}
body.dark-theme .rating{background:#263b60;color:#d8e5ff}
body.dark-theme .modal{background:#000b}
body.dark-theme .btn.secondary{background:#263b60;color:#d8e5ff}
body.dark-theme .close{background:#263247;color:#edf2fa}
body.dark-theme .total-box{background:#263247}
body.dark-theme hr{border-color:var(--border)}

/* ================= DAY / NIGHT SWITCH ================= */
.theme-control{display:flex;align-items:center;gap:8px}
.theme-label{font-size:12px;color:var(--muted);white-space:nowrap}
.switch{
 position:relative;display:inline-block;width:60px;height:34px;flex:0 0 60px
}
.switch #themeToggle{opacity:0;width:1px;height:1px;position:absolute}
.switch .slider{
 position:absolute;cursor:pointer;inset:0;background:#2196f3;
 transition:.4s;z-index:0;overflow:hidden
}
.sun-moon{
 position:absolute;height:26px;width:26px;left:4px;bottom:4px;
 background:#ffeb3b;transition:.4s;border-radius:50%
}
#themeToggle:checked+.slider{background:#111827}
#themeToggle:focus-visible+.slider{outline:3px solid #9bbcff;outline-offset:3px}
#themeToggle:checked+.slider .sun-moon{
 transform:translateX(26px);background:#fff;animation:rotate-center .6s
}
.moon-dot{opacity:0;transition:.4s;fill:gray}
#themeToggle:checked+.slider .moon-dot{opacity:1}
.slider.round{border-radius:34px}
#moon-dot-1{position:absolute;left:10px;top:3px;width:6px;height:6px}
#moon-dot-2{position:absolute;left:2px;top:10px;width:10px;height:10px}
#moon-dot-3{position:absolute;left:16px;top:18px;width:3px;height:3px}
#light-ray-1,#light-ray-2,#light-ray-3{
 position:absolute;fill:white;opacity:.1;pointer-events:none
}
#light-ray-1{left:-8px;top:-8px;width:43px;height:43px}
#light-ray-2{left:-50%;top:-50%;width:55px;height:55px}
#light-ray-3{left:-18px;top:-18px;width:60px;height:60px}
.cloud-light,.cloud-dark{position:absolute;animation:cloud-move 6s infinite}
.cloud-light{fill:#eee}
.cloud-dark{fill:#ccc;animation-delay:1s}
#cloud-1{left:30px;top:15px;width:40px}
#cloud-2{left:44px;top:10px;width:20px}
#cloud-3{left:18px;top:24px;width:30px}
#cloud-4{left:36px;top:18px;width:40px}
#cloud-5{left:48px;top:14px;width:20px}
#cloud-6{left:22px;top:26px;width:30px}
@keyframes cloud-move{
 0%,100%{transform:translateX(0)}
 40%{transform:translateX(4px)}
 80%{transform:translateX(-4px)}
}
.stars{position:absolute;inset:0;transform:translateY(-32px);opacity:0;transition:.4s}
#themeToggle:checked+.slider .stars{transform:translateY(0);opacity:1}
.star{fill:white;position:absolute;animation:star-twinkle 2s infinite}
#star-1{width:20px;top:2px;left:3px;animation-delay:.3s}
#star-2{width:6px;top:16px;left:3px}
#star-3{width:12px;top:20px;left:10px;animation-delay:.6s}
#star-4{width:18px;top:0;left:18px;animation-delay:1.3s}
@keyframes star-twinkle{
 0%,100%{transform:scale(1)}
 40%{transform:scale(1.2)}
 80%{transform:scale(.8)}
}
@keyframes rotate-center{to{transform:translateX(26px) rotate(360deg)}}

/* ================= RESPONSIVE ================= */
[dir="rtl"] body{text-align:right}
[dir="rtl"] .search,[dir="rtl"] .form-grid{direction:rtl}
@media(max-width:1050px){
 .hotel-grid{grid-template-columns:repeat(2,minmax(0,1fr))}
 .search{grid-template-columns:repeat(2,minmax(0,1fr))}
 .room-list{grid-template-columns:repeat(2,minmax(0,1fr))}
}
@media(max-width:600px){
 header{padding:12px 4%;gap:8px}
 .logo{font-size:20px}
 .nav-right{gap:7px}
 #languageSelect{max-width:92px;font-size:12px;padding:8px 4px}
 .theme-label{display:none}
 .nav-right>.btn{padding:9px;font-size:12px}
 .hero{padding:35px 4%}
 .container{padding:25px 4%}
 .hotel-grid{grid-template-columns:1fr;gap:16px}
 .hotel-card>img{height:210px}
 .search{padding:10px;gap:9px}
 .search .field:first-child,.search .btn{grid-column:1/-1}
 .search .btn{width:100%}
 .field input,.field select{padding:10px 8px;font-size:14px}
 .room-list{grid-template-columns:1fr}
 .room{display:grid;grid-template-columns:minmax(105px,38%) minmax(0,1fr)}
 .room img{height:100%;min-height:160px}
 .room-content{min-width:0;padding:10px}
 .amenities{grid-template-columns:repeat(2,minmax(0,1fr))}
 .modal{padding:9px;align-items:flex-start}
 .modal-box{padding:18px;margin:auto 0;max-height:94dvh}
 .gallery{grid-template-columns:repeat(2,minmax(0,1fr))}
 .gallery img{height:145px}
 .form-grid{grid-template-columns:1fr}
 .form-grid .field.full{grid-column:auto}
}
@media(max-width:380px){
 header{flex-wrap:wrap}
 .nav-right{width:100%;justify-content:space-between}
 .search{grid-template-columns:1fr}
 .search .field:first-child,.search .btn{grid-column:auto}
 .room{grid-template-columns:100px minmax(0,1fr)}
 .amenities{grid-template-columns:1fr}
 .gallery img{height:120px}
}
@media(prefers-reduced-motion:reduce){
 *,*::before,*::after{animation-duration:.01ms!important;transition-duration:.01ms!important;scroll-behavior:auto!important}
}
</style>
</head>

<body>
<header>
 <div class="logo">Asman<span>booking</span></div>
 <div class="nav-right">
  <div class="theme-control">
   <span class="theme-label" id="themeLabel">Day / Night</span>
   <label class="switch" title="Toggle day and night mode">
    <input id="themeToggle" type="checkbox" aria-label="Toggle dark mode">
    <span class="slider round">
     <span class="sun-moon">
      <svg id="moon-dot-1" class="moon-dot" viewBox="0 0 100 100"><circle cx="50" cy="50" r="50"/></svg>
      <svg id="moon-dot-2" class="moon-dot" viewBox="0 0 100 100"><circle cx="50" cy="50" r="50"/></svg>
      <svg id="moon-dot-3" class="moon-dot" viewBox="0 0 100 100"><circle cx="50" cy="50" r="50"/></svg>
      <svg id="light-ray-1" viewBox="0 0 100 100"><circle cx="50" cy="50" r="50"/></svg>
      <svg id="light-ray-2" viewBox="0 0 100 100"><circle cx="50" cy="50" r="50"/></svg>
      <svg id="light-ray-3" viewBox="0 0 100 100"><circle cx="50" cy="50" r="50"/></svg>
      <svg id="cloud-1" class="cloud-dark" viewBox="0 0 100 100"><circle cx="50" cy="50" r="50"/></svg>
      <svg id="cloud-2" class="cloud-dark" viewBox="0 0 100 100"><circle cx="50" cy="50" r="50"/></svg>
      <svg id="cloud-3" class="cloud-dark" viewBox="0 0 100 100"><circle cx="50" cy="50" r="50"/></svg>
      <svg id="cloud-4" class="cloud-light" viewBox="0 0 100 100"><circle cx="50" cy="50" r="50"/></svg>
      <svg id="cloud-5" class="cloud-light" viewBox="0 0 100 100"><circle cx="50" cy="50" r="50"/></svg>
      <svg id="cloud-6" class="cloud-light" viewBox="0 0 100 100"><circle cx="50" cy="50" r="50"/></svg>
     </span>
     <span class="stars">
      <svg id="star-1" class="star" viewBox="0 0 20 20"><path d="M10 0 12 8 20 10 12 12 10 20 8 12 0 10 8 8Z"/></svg>
      <svg id="star-2" class="star" viewBox="0 0 20 20"><path d="M10 0 12 8 20 10 12 12 10 20 8 12 0 10 8 8Z"/></svg>
      <svg id="star-3" class="star" viewBox="0 0 20 20"><path d="M10 0 12 8 20 10 12 12 10 20 8 12 0 10 8 8Z"/></svg>
      <svg id="star-4" class="star" viewBox="0 0 20 20"><path d="M10 0 12 8 20 10 12 12 10 20 8 12 0 10 8 8Z"/></svg>
     </span>
    </span>
   </label>
  </div>
  <select id="languageSelect" aria-label="Select language">
   <option value="en">English</option>
   <option value="ku">کوردی</option>
   <option value="ar">العربية</option>
  </select>
  <button class="btn" id="loginButton" onclick="openLogin()">Login</button>
 </div>
</header>

<section class="hero">
 <h1 id="heroTitle">Find your next stay</h1>
 <p id="heroSubtitle">Discover hotels, compare rooms and plan your stay in Sulaymaniyah.</p>
 <div class="search">
  <div class="field">
   <label id="destinationLabel" for="destination">Destination or hotel</label>
   <input id="destination" type="search" placeholder="Where do you want to stay?">
  </div>
  <div class="field">
   <label id="checkinLabel" for="checkin">Check-in</label>
   <input id="checkin" type="date">
  </div>
  <div class="field">
   <label id="checkoutLabel" for="checkout">Check-out</label>
   <input id="checkout" type="date">
  </div>
  <div class="field">
   <label id="guestsLabel" for="guests">Guests</label>
   <select id="guests">
    <option value="1">1</option><option value="2" selected>2</option>
    <option value="3">3</option><option value="4">4</option><option value="5">5+</option>
   </select>
  </div>
  <button class="btn" id="searchButton" onclick="searchHotels()">Search</button>
 </div>
</section>

<main class="container">
 <div class="section-head">
  <h2 id="hotelsTitle">Hotels in Sulaymaniyah</h2>
  <span id="resultCount"></span>
 </div>
 <div class="hotel-grid" id="hotelGrid"></div>
</main>
<footer id="footerText">Asmanbooking · Find a place to stay</footer>

<div class="modal" id="hotelModal" onclick="outsideClose(event,'hotelModal')">
 <div class="modal-box">
  <button class="close" onclick="closeModal('hotelModal')" aria-label="Close">×</button>
  <div id="hotelDetails"></div>
 </div>
</div>

<div class="modal" id="bookingModal" onclick="outsideClose(event,'bookingModal')">
 <div class="modal-box small">
  <button class="close" onclick="closeModal('bookingModal')" aria-label="Close">×</button>
  <h2 id="bookingTitle">Your booking</h2>
  <div id="bookingHotelName"></div>
  <div class="form-grid">
   <div class="field">
    <label id="bookCheckinLabel" for="bookCheckin">Check-in</label>
    <input type="date" id="bookCheckin">
   </div>
   <div class="field">
    <label id="bookCheckoutLabel" for="bookCheckout">Check-out</label>
    <input type="date" id="bookCheckout">
   </div>
   <div class="field full">
    <label id="bookGuestsLabel" for="bookGuests">Guests</label>
    <select id="bookGuests">
     <option value="1">1</option><option value="2" selected>2</option>
     <option value="3">3</option><option value="4">4</option><option value="5">5+</option>
    </select>
   </div>
  </div>
  <div class="total-box" id="bookingTotal"></div>
  <button class="btn wide" id="continuePaymentButton" onclick="goToPayment()">Continue to payment</button>
  <p class="notice" id="bookingNotice">Demo only: this page does not create a real reservation.</p>
 </div>
</div>

<div class="modal" id="paymentModal" onclick="outsideClose(event,'paymentModal')">
 <div class="modal-box small">
  <button class="close" onclick="closeModal('paymentModal')" aria-label="Close">×</button>
  <h2 id="paymentTitle">Payment</h2>
  <div id="paymentSummary" class="total-box"></div>
  <p class="notice" id="paymentNotice">Demo only. No money will be charged and no real booking will be made. Do not enter real card details.</p>
  <button class="btn wide" id="demoConfirmButton" onclick="demoConfirm()">Confirm demo booking</button>
 </div>
</div>

<div class="modal" id="loginModal" onclick="outsideClose(event,'loginModal')">
 <div class="modal-box small">
  <button class="close" onclick="closeModal('loginModal')" aria-label="Close">×</button>
  <h2 id="loginTitle">Welcome</h2>
  <div class="field" style="margin:14px 0">
   <label id="emailLabel" for="loginEmail">Email</label>
   <input type="email" id="loginEmail" placeholder="name@example.com">
  </div>
  <p class="notice" id="loginNotice">Login is a visual demo and is not connected to an account system.</p>
  <button class="btn wide" id="loginDemoButton" onclick="demoLogin()">Continue</button>
 </div>
</div>

<script>
/* ================= TRANSLATIONS ================= */
const translations={
en:{
login:"Login",heroTitle:"Find your next stay",
heroSubtitle:"Discover hotels, compare rooms and plan your stay in Sulaymaniyah.",
destination:"Destination or hotel",destinationPlaceholder:"Where do you want to stay?",
checkin:"Check-in",checkout:"Check-out",guests:"Guests",search:"Search",
hotelsTitle:"Hotels in Sulaymaniyah",perNight:"/ night",
viewDetails:"View details",noResults:"No hotels found. Try another search.",
location:"Sulaymaniyah, Kurdistan Region",facilities:"Facilities",
rooms:"Choose your room",details:"Hotel details",
description:"Explore the facilities and room options at this hotel.",
parking:"Parking",restaurant:"Restaurant",gym:"Gym",garden:"Green areas",
quiet:"Quiet environment",wifi:"Wi-Fi",roomStandard:"Standard Room",
roomDeluxe:"Deluxe Room",roomSuite:"Suite",
roomDesc:"Example room option. Confirm details with the hotel.",
selectRoom:"Choose room",bookingTitle:"Your booking",
continuePayment:"Continue to payment",nights:"Nights",roomPrice:"Room price",
total:"Estimated total",invalidDates:"Please choose a check-out date after check-in.",
bookingNotice:"Demo only: this page does not create a real reservation.",
paymentTitle:"Payment",
paymentNotice:"Demo only. No money will be charged and no real booking will be made. Do not enter real card details.",
demoConfirm:"Confirm demo booking",
demoSuccess:"Demo complete. No reservation or payment was made.",
loginTitle:"Welcome",email:"Email",
loginNotice:"Login is a visual demo and is not connected to an account system.",
continue:"Continue",footer:"Asmanbooking · Find a place to stay",
dateRequired:"Please choose valid check-in and check-out dates.",
rating:"Guest rating",priceFrom:"From",theme:"Day / Night"
},
ku:{
login:"چوونەژوورەوە",heroTitle:"شوێنی مانەوەی داهاتووت بدۆزەوە",
heroSubtitle:"هۆتێلەکان ببینە، ژوورەکان بەراورد بکە و مانەوەکەت لە سلێمانی پلاندانان بکە.",
destination:"شوێن یان ناوی هۆتێل",destinationPlaceholder:"لە کوێ دەتەوێت بمێنیتەوە؟",
checkin:"بەرواری چوونەژوورەوە",checkout:"بەرواری دەرچوون",
guests:"ژمارەی میوانان",search:"گەڕان",hotelsTitle:"هۆتێلەکانی سلێمانی",
perNight:"/ شەو",viewDetails:"بینینی وردەکاری",
noResults:"هیچ هۆتێلێک نەدۆزرایەوە. دووبارە بگەڕێ.",
location:"سلێمانی، هەرێمی کوردستان",facilities:"خزمەتگوزارییەکان",
rooms:"ژوورەکان هەڵبژێرە",details:"وردەکاری هۆتێل",
description:"خزمەتگوزاری و جۆرەکانی ژووری ئەم هۆتێلە ببینە.",
parking:"پارکینگ",restaurant:"چێشتخانە",gym:"یاریگای وەرزشی",
garden:"شوێنی سەوز",quiet:"ژینگەی ئارام",wifi:"وایفای",
roomStandard:"ژووری ستاندارد",roomDeluxe:"ژووری دێلوکس",roomSuite:"سوئیت",
roomDesc:"ئەمە نموونەیەکە بۆ جۆری ژوور. وردەکارییەکان لەگەڵ هۆتێل پشتڕاست بکەرەوە.",
selectRoom:"هەڵبژاردنی ژوور",bookingTitle:"زانیاری حجز",
continuePayment:"بەردەوامبوون بۆ پارەدان",nights:"ژمارەی شەوەکان",
roomPrice:"نرخی ژوور",total:"کۆی نرخی خەمڵێنراو",
invalidDates:"تکایە بەرواری دەرچوون دوای بەرواری چوونەژوورەوە هەڵبژێرە.",
bookingNotice:"تەنها نموونەیە؛ ئەم پەڕەیە حجزێکی ڕاستەقینە ئەنجام نادات.",
paymentTitle:"پارەدان",
paymentNotice:"ئەمە تەنها نموونەیە. هیچ پارەیەک دەردەکرێت و حجزێکی ڕاستەقینە ناکرێت. زانیاری کارتی ڕاستەقینە مەنووسە.",
demoConfirm:"پشتڕاستکردنەوەی نموونە",
demoSuccess:"تەواو بوو. هیچ حجز یان پارەدانێکی ڕاستەقینە ئەنجام نەدرا.",
loginTitle:"بەخێربێیت",email:"ئیمەیڵ",
loginNotice:"چوونەژوورەوە تەنها نموونەیە و بە سیستەمی هەژمارەوە پەیوەست نییە.",
continue:"بەردەوامبوون",footer:"Asmanbooking · شوێنی مانەوە بدۆزەوە",
dateRequired:"تکایە بەرواری دروستی چوونەژوورەوە و دەرچوون هەڵبژێرە.",
rating:"هەڵسەنگاندنی میوانان",priceFrom:"لە",theme:"ڕۆژ / شەو"
},
ar:{
login:"تسجيل الدخول",heroTitle:"اعثر على إقامتك القادمة",
heroSubtitle:"اكتشف الفنادق وقارن الغرف وخطط لإقامتك في السليمانية.",
destination:"الوجهة أو الفندق",destinationPlaceholder:"أين تريد الإقامة؟",
checkin:"تسجيل الوصول",checkout:"تسجيل المغادرة",guests:"الضيوف",search:"بحث",
hotelsTitle:"فنادق السليمانية",perNight:"/ ليلة",viewDetails:"عرض التفاصيل",
noResults:"لم يتم العثور على فنادق. جرّب بحثاً آخر.",
location:"السليمانية، إقليم كردستان",facilities:"المرافق",rooms:"اختر غرفتك",
details:"تفاصيل الفندق",description:"استكشف مرافق الفندق وخيارات الغرف المتاحة.",
parking:"موقف سيارات",restaurant:"مطعم",gym:"نادي رياضي",
garden:"مساحات خضراء",quiet:"بيئة هادئة",wifi:"واي فاي",
roomStandard:"غرفة عادية",roomDeluxe:"غرفة ديلوكس",roomSuite:"جناح",
roomDesc:"هذا خيار تجريبي للغرفة. يرجى تأكيد التفاصيل مع الفندق.",
selectRoom:"اختر الغرفة",bookingTitle:"حجزك",
continuePayment:"المتابعة إلى الدفع",nights:"عدد الليالي",roomPrice:"سعر الغرفة",
total:"الإجمالي التقديري",invalidDates:"يرجى اختيار تاريخ مغادرة بعد تاريخ الوصول.",
bookingNotice:"للتجربة فقط؛ هذه الصفحة لا تنشئ حجزاً حقيقياً.",
paymentTitle:"الدفع",
paymentNotice:"هذه تجربة فقط. لن يتم خصم أي مبلغ ولن يتم إنشاء حجز حقيقي. لا تدخل بيانات بطاقة حقيقية.",
demoConfirm:"تأكيد الحجز التجريبي",
demoSuccess:"اكتملت التجربة. لم يتم إجراء حجز أو دفع حقيقي.",
loginTitle:"مرحباً",email:"البريد الإلكتروني",
loginNotice:"تسجيل الدخول تجريبي وغير متصل بنظام حسابات.",
continue:"متابعة",footer:"Asmanbooking · اعثر على مكان للإقامة",
dateRequired:"يرجى اختيار تاريخي وصول ومغادرة صحيحين.",
rating:"تقييم الضيوف",priceFrom:"ابتداءً من",theme:"نهار / ليل"
}
};

/* ================= HOTEL AND ROOM DATA ================= */
const hotelsData=[
{
id:1,name:"Grand Millennium Hotel",location:"Sulaymaniyah",rating:"9.2",price:136,
image:"https://farukinvestmentstorage.blob.core.windows.net/root/root/images/11562024_gm.jpg",
image2:"https://cf.bstatic.com/xdata/images/hotel/max1024x768/62091634.jpg?k=91b313d11accd033d4efeed0d7e577cb3483f78111c4ff7bc1d6c6f54b12f743&o=",
image3:"https://cf.bstatic.com/xdata/images/hotel/max1024x768/62092893.jpg?k=ec38a2a0633143e2c402723490dbe214c6396b2cad03a185770206c49c843c08&o=",
rooms:[
{type:"roomStandard",price:136,image:"https://images.unsplash.com/photo-1631049307264-da0ec9d70304?auto=format&fit=crop&w=1200&q=85"},
{type:"roomDeluxe",price:175,image:"https://images.unsplash.com/photo-1611892440504-42a792e24d32?auto=format&fit=crop&w=1200&q=85"},
{type:"roomSuite",price:240,image:"https://images.unsplash.com/photo-1616486338812-3dadae4b4ace?auto=format&fit=crop&w=1200&q=85"}
]},
{
id:2,name:"Copthorne Hotel Baranan",location:"Sulaymaniyah",rating:"8.9",price:80,
image:"https://cf.bstatic.com/xdata/images/hotel/max1024x768/19522904.jpg?k=36b26575d217864e996b7187fdd1d298aeebd58ebe39d85854124f2f1ea69ae1&o=",
image2:"https://cf.bstatic.com/xdata/images/hotel/max1024x768/19523138.jpg?k=dc8bbb2d55cff94135ec17cb35e4ef9b29a40e7f66bff915067a821a97409bd5&o=",
image3:"https://cf.bstatic.com/xdata/images/hotel/max1024x768/19522702.jpg?k=c37b62fec7dcb091b4f1389e5adca1a106a3249a2fda3e302e61010275e3504a&o=",
rooms:[
{type:"roomStandard",price:80,image:"https://images.unsplash.com/photo-1590490360182-c33d57733427?auto=format&fit=crop&w=1200&q=85"},
{type:"roomDeluxe",price:110,image:"https://images.unsplash.com/photo-1566665797739-1674de7a421a?auto=format&fit=crop&w=1200&q=85"},
{type:"roomSuite",price:160,image:"https://images.unsplash.com/photo-1601918774946-25832a4be0d6?auto=format&fit=crop&w=1200&q=85"}
]},
{
id:3,name:"Slemani Rotana",location:"Sulaymaniyah",rating:"9.0",price:111,
image:"https://cf.bstatic.com/xdata/images/hotel/max1024x768/657733518.jpg?k=e88f38dca3f9c75d5442d8e450e6598322af4c9ceb13e4d48949a45183542441&o=",
image2:"https://cf.bstatic.com/xdata/images/hotel/max1024x768/365451838.jpg?k=b8a036a53eed867b0efe7ee5f8a5826127fe057a7bdb9eb1a6f43608ae921fa9&o=",
image3:"https://cf.bstatic.com/xdata/images/hotel/max1024x768/656727593.jpg?k=3b7994e16962f10dd3e8559f98903478be4378280fb8ebda00fac9f2430b591a&o=",
rooms:[
{type:"roomStandard",price:111,image:"https://images.unsplash.com/photo-1595576508898-0ad5c879a061?auto=format&fit=crop&w=1200&q=85"},
{type:"roomDeluxe",price:155,image:"https://images.unsplash.com/photo-1591088398332-8a7791972843?auto=format&fit=crop&w=1200&q=85"},
{type:"roomSuite",price:220,image:"https://images.unsplash.com/photo-1600210492486-724fe5c67fb0?auto=format&fit=crop&w=1200&q=85"}
]},
{
id:4,name:"Titanic Hotel & Spa",location:"Sulaymaniyah",rating:"8.7",price:154,
image:"https://cf.bstatic.com/xdata/images/hotel/max1024x768/365515494.jpg?k=eab898ea8fe23e291a060fe964073e6ba70f247dcef3db0712a5e307f5805fab&o=",
image2:"https://cf.bstatic.com/xdata/images/hotel/max1024x768/365521948.jpg?k=f8e11e15b330cbd9cf9c1ec37727073c1c592ddfa44e59799ddcf9c881f0ecdf&o=",
image3:"https://cf.bstatic.com/xdata/images/hotel/max1024x768/365522123.jpg?k=218a2836011e72f84745162a703a829a5e9cd605e32dd468ca41f49b885a74e6&o=",
rooms:[
{type:"roomStandard",price:154,image:"https://images.unsplash.com/photo-1564078516393-cf04bd966897?auto=format&fit=crop&w=1200&q=85"},
{type:"roomDeluxe",price:195,image:"https://images.unsplash.com/photo-1611892440504-42a792e24d32?auto=format&fit=crop&w=1200&q=85"},
{type:"roomSuite",price:280,image:"https://images.unsplash.com/photo-1600607687939-ce8a6c25118c?auto=format&fit=crop&w=1200&q=85"}
]}
];

let currentLang="en",activeHotel=null,activeRoom=null;
const $=id=>document.getElementById(id);
const tr=key=>translations[currentLang]?.[key]||translations.en[key]||key;
const money=value=>"$"+Number(value).toLocaleString("en-US");
const safeImageError="this.onerror=null;this.style.visibility='hidden';";

/* ================= DAY / NIGHT MODE ================= */
function applyTheme(isDark,save=true){
 document.body.classList.toggle("dark-theme",isDark);
 const toggle=$("themeToggle");
 if(toggle){
  toggle.checked=isDark;
  toggle.setAttribute("aria-checked",String(isDark));
 }
 if(save){
  try{localStorage.setItem("asmanBookingTheme",isDark?"dark":"light")}catch(e){}
 }
 const meta=document.querySelector('meta[name="theme-color"]');
 if(meta)meta.content=isDark?"#101521":"#155eef";
}
let savedTheme=null;
try{savedTheme=localStorage.getItem("asmanBookingTheme")}catch(e){}
applyTheme(savedTheme==="dark",false);
$("themeToggle").addEventListener("change",e=>applyTheme(e.target.checked));

/* ================= LANGUAGE ================= */
function applyLanguage(lang){
 currentLang=translations[lang]?lang:"en";
 document.documentElement.lang=currentLang;
 document.documentElement.dir=currentLang==="en"?"ltr":"rtl";
 $("languageSelect").value=currentLang;

 const map={
 loginButton:"login",heroTitle:"heroTitle",heroSubtitle:"heroSubtitle",
 destinationLabel:"destination",checkinLabel:"checkin",checkoutLabel:"checkout",
 guestsLabel:"guests",searchButton:"search",hotelsTitle:"hotelsTitle",
 footerText:"footer",bookingTitle:"bookingTitle",
 bookCheckinLabel:"checkin",bookCheckoutLabel:"checkout",
 bookGuestsLabel:"guests",continuePaymentButton:"continuePayment",
 bookingNotice:"bookingNotice",paymentTitle:"paymentTitle",
 paymentNotice:"paymentNotice",demoConfirmButton:"demoConfirm",
 loginTitle:"loginTitle",emailLabel:"email",loginNotice:"loginNotice",
 loginDemoButton:"continue",themeLabel:"theme"
 };
 Object.entries(map).forEach(([id,key])=>{if($(id))$(id).textContent=tr(key)});
 $("destination").placeholder=tr("destinationPlaceholder");
 renderHotels();
 if(activeHotel)renderHotelDetails(activeHotel);
 if($("bookingModal").classList.contains("show"))updateTotal();
 if($("paymentModal").classList.contains("show"))renderPaymentSummary();
}
$("languageSelect").addEventListener("change",e=>applyLanguage(e.target.value));

/* ================= HOTEL CARDS ================= */
function renderHotels(list=hotelsData){
 const grid=$("hotelGrid");
 $("resultCount").textContent=list.length;
 if(!list.length){grid.innerHTML=`<div class="empty">${tr("noResults")}</div>`;return}
 grid.innerHTML=list.map(h=>`
 <article class="hotel-card">
  <img src="${h.image}" alt="${h.name}" loading="lazy" onerror="${safeImageError}">
  <div class="hotel-info">
   <h3>${h.name}</h3>
   <div class="location">📍 ${tr("location")}</div>
   <div class="rating">★ ${h.rating} · ${tr("rating")}</div>
   <div class="amenity-preview">${tr("parking")} · ${tr("restaurant")} · ${tr("wifi")}</div>
   <div class="price-row">
    <div class="price">${tr("priceFrom")} ${money(h.price)} <small>${tr("perNight")}</small></div>
    <button class="btn" onclick="openHotel(${h.id})">${tr("viewDetails")}</button>
   </div>
  </div>
 </article>`).join("");
}

/* ================= SEARCH ================= */
function searchHotels(){
 const query=$("destination").value.trim().toLowerCase();
 const filtered=hotelsData.filter(h=>{
  if(!query)return true;
  return [h.name,h.location,"sulaymaniyah","slemani","sulaymani","سلێمانی","السليمانية"]
   .join(" ").toLowerCase().includes(query);
 });
 renderHotels(filtered);
 if($("checkin").value)$("bookCheckin").value=$("checkin").value;
 if($("checkout").value)$("bookCheckout").value=$("checkout").value;
 $("bookGuests").value=$("guests").value;
}
$("destination").addEventListener("keydown",e=>{if(e.key==="Enter")searchHotels()});

/* ================= HOTEL DETAILS ================= */
function openHotel(id){
 activeHotel=hotelsData.find(h=>h.id===Number(id));
 if(!activeHotel)return;
 renderHotelDetails(activeHotel);showModal("hotelModal");
}
function renderHotelDetails(h){
 $("hotelDetails").innerHTML=`
 <h2>${h.name}</h2>
 <div class="location">📍 ${tr("location")} · ★ ${h.rating}</div>
 <div class="gallery">
  <img src="${h.image}" alt="${h.name}" onerror="${safeImageError}">
  <img src="${h.image2||h.image3||h.image}" alt="${h.name}" onerror="${safeImageError}">
 </div>
 <p class="detail-description">${tr("description")}</p>
 <h3>${tr("facilities")}</h3>
 <div class="amenities">
  <div class="amenity">🅿️ ${tr("parking")}</div>
  <div class="amenity">🍽️ ${tr("restaurant")}</div>
  <div class="amenity">🏋️ ${tr("gym")}</div>
  <div class="amenity">🌳 ${tr("garden")}</div>
  <div class="amenity">🤫 ${tr("quiet")}</div>
  <div class="amenity">📶 ${tr("wifi")}</div>
 </div>
 <h3>${tr("rooms")}</h3>
 <div class="room-list">
 ${h.rooms.map((r,i)=>`
  <div class="room">
   <img src="${r.image}" alt="${tr(r.type)}" loading="lazy" onerror="${safeImageError}">
   <div class="room-content">
    <h4>${tr(r.type)}</h4>
    <p>${tr("roomDesc")}</p>
    <span class="price">${money(r.price)} <small>${tr("perNight")}</small></span>
    <button class="btn wide" onclick="chooseRoom(${h.id},${i})">${tr("selectRoom")}</button>
   </div>
  </div>`).join("")}
 </div>
 <p class="notice">${tr("roomDesc")}</p>`;
}

/* ================= ROOM SELECTION ================= */
function chooseRoom(hotelId,index){
 activeHotel=hotelsData.find(h=>h.id===Number(hotelId));
 if(!activeHotel)return;
 activeRoom=activeHotel.rooms[index];
 if(!activeRoom)return;

 closeModal("hotelModal");
 $("bookCheckin").value=$("checkin").value||$("bookCheckin").value;
 $("bookCheckout").value=$("checkout").value||$("bookCheckout").value;
 $("bookGuests").value=$("guests").value;
 $("bookingHotelName").innerHTML=`
 <p><strong>${activeHotel.name}</strong></p>
 <p class="notice">${tr(activeRoom.type)} · ${money(activeRoom.price)} ${tr("perNight")}</p>`;
 updateTotal();showModal("bookingModal");
}

/* ================= DATE HELPERS ================= */
function dateValue(d){
 return `${d.getFullYear()}-${String(d.getMonth()+1).padStart(2,"0")}-${String(d.getDate()).padStart(2,"0")}`;
}
function addDays(value,n){
 const d=new Date(value+"T12:00:00");d.setDate(d.getDate()+n);return dateValue(d);
}
function countNights(){
 const a=$("bookCheckin").value,b=$("bookCheckout").value;
 if(!a||!b)return 0;
 const n=Math.round((new Date(b+"T12:00:00")-new Date(a+"T12:00:00"))/86400000);
 return n>0?n:0;
}
function setupDateInputs(){
 const today=new Date(),tomorrow=new Date(today),after=new Date(today);
 tomorrow.setDate(today.getDate()+1);after.setDate(today.getDate()+2);
 const t=dateValue(today),tm=dateValue(tomorrow),aft=dateValue(after);
 $("checkin").min=t;$("checkin").value=tm;
 $("checkout").min=tm;$("checkout").value=aft;
 $("bookCheckin").min=t;$("bookCheckin").value=tm;
 $("bookCheckout").min=tm;$("bookCheckout").value=aft;

 $("checkin").addEventListener("change",()=>{
  if(!$("checkin").value)return;
  const min=addDays($("checkin").value,1);
  $("checkout").min=min;
  if(!$("checkout").value||$("checkout").value<min)$("checkout").value=min;
 });
 $("checkout").addEventListener("change",()=>{
  if($("checkout").value&&$("checkout").value<=$("checkin").value)
   $("checkout").value=addDays($("checkin").value,1);
 });
 $("bookCheckin").addEventListener("change",()=>{
  if(!$("bookCheckin").value)return;
  const min=addDays($("bookCheckin").value,1);
  $("bookCheckout").min=min;
  if(!$("bookCheckout").value||$("bookCheckout").value<min)$("bookCheckout").value=min;
  updateTotal();
 });
 $("bookCheckout").addEventListener("change",updateTotal);
 $("bookGuests").addEventListener("change",updateTotal);
}

/* ================= TOTAL ================= */
function updateTotal(){
 if(!activeHotel||!activeRoom)return;
 const nights=countNights(),guests=Number($("bookGuests").value||1);
 $("bookingTotal").innerHTML=`
  <div class="total-line"><span>${tr("nights")}</span><strong>${nights}</strong></div>
  <div class="total-line"><span>${tr("guests")}</span><strong>${guests}</strong></div>
  <div class="total-line"><span>${tr("roomPrice")}</span><strong>${money(activeRoom.price)} ${tr("perNight")}</strong></div>
  <hr>
  <div class="total-line"><strong>${tr("total")}</strong><strong>${money(nights*activeRoom.price)}</strong></div>
  ${nights===0?`<p class="notice">${tr("invalidDates")}</p>`:""}`;
}

/* ================= DEMO PAYMENT ================= */
function goToPayment(){
 if(!activeHotel||!activeRoom)return;
 if(countNights()<1){alert(tr("dateRequired"));return}
 closeModal("bookingModal");renderPaymentSummary();showModal("paymentModal");
}
function renderPaymentSummary(){
 if(!activeHotel||!activeRoom)return;
 const n=countNights();
 $("paymentSummary").innerHTML=`
 <strong>${activeHotel.name}</strong><br>
 ${tr(activeRoom.type)}<br>${tr("nights")}: ${n}<br>
 ${tr("total")}: <strong>${money(n*activeRoom.price)}</strong>`;
}
function demoConfirm(){closeModal("paymentModal");alert(tr("demoSuccess"))}

/* ================= DEMO LOGIN ================= */
function openLogin(){showModal("loginModal")}
function demoLogin(){
 const email=$("loginEmail").value.trim();
 if(!email||!/^[^\s@]+@[^\s@]+\.[^\s@]+$/.test(email)){
  alert(currentLang==="ku"?"تکایە ئیمەیڵێکی دروست بنووسە.":"Please enter a valid email address.");return;
 }
 closeModal("loginModal");alert(tr("loginNotice"));
}

/* ================= MODALS ================= */
function showModal(id){
 const el=$(id);if(!el)return;
 el.classList.add("show");document.body.style.overflow="hidden";
}
function closeModal(id){
 const el=$(id);if(!el)return;
 el.classList.remove("show");
 if(!document.querySelector(".modal.show"))document.body.style.overflow="";
}
function outsideClose(event,id){if(event.target.id===id)closeModal(id)}
document.addEventListener("keydown",e=>{
 if(e.key==="Escape"){
  document.querySelectorAll(".modal.show").forEach(m=>closeModal(m.id));
 }
});

/* ================= START ================= */
setupDateInputs();
renderHotels();
applyLanguage("en");
</script>
</body>
</html>
