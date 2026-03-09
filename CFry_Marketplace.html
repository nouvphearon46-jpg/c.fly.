<!DOCTYPE html>
<html lang="km">
<head>
  <meta charset="UTF-8"/>
  <meta name="viewport" content="width=device-width,initial-scale=1"/>
  <title>C.Fry — ផ្សារអនឡាញ Khmer Marketplace</title>
  <link href="https://fonts.googleapis.com/css2?family=Kantumruy+Pro:wght@300;400;500;600;700&family=Bebas+Neue&display=swap" rel="stylesheet">
  <style>
    *,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
    :root{
      --bg:#0d0d0d;--surface:#161616;--card:#1e1e1e;--border:#2a2a2a;
      --red:#C0392B;--red2:#E74C3C;--gold:#F39C12;
      --text:#F5F0E8;--muted:#777;--green:#27AE60;--sold:#555;--radius:12px;
    }
    html{scroll-behavior:smooth}
    body{font-family:'Kantumruy Pro',sans-serif;background:var(--bg);color:var(--text);min-height:100vh;overflow-x:hidden}

    /* TOPBAR */
    .topbar{background:#8B0000;padding:7px 0;text-align:center;font-size:12px;color:#fff;letter-spacing:.3px}
    .topbar strong{color:var(--gold)}

    /* NAV */
    nav{background:var(--surface);border-bottom:1px solid var(--border);padding:0 clamp(12px,4vw,48px);display:flex;align-items:center;gap:12px;height:66px;position:sticky;top:0;z-index:200}
    .logo{font-family:'Bebas Neue',sans-serif;font-size:32px;color:var(--red2);letter-spacing:3px;cursor:pointer;flex-shrink:0}
    .logo sup{font-size:10px;color:var(--gold);font-family:'Kantumruy Pro',sans-serif;font-weight:700;letter-spacing:0}
    .search-bar{flex:1;max-width:520px;display:flex;background:var(--card);border:1px solid var(--border);border-radius:40px;overflow:hidden}
    .search-bar input{flex:1;background:transparent;border:none;color:var(--text);padding:11px 18px;font-family:'Kantumruy Pro',sans-serif;font-size:14px;outline:none}
    .search-bar input::placeholder{color:var(--muted)}
    .search-bar button{background:var(--red);color:#fff;border:none;cursor:pointer;padding:0 20px;font-size:15px;transition:background .2s}
    .search-bar button:hover{background:var(--red2)}
    .nav-right{display:flex;gap:8px;margin-left:auto;flex-shrink:0;align-items:center}
    .btn-sell{background:var(--gold);color:#111;border:none;cursor:pointer;padding:10px 20px;border-radius:40px;font-family:'Kantumruy Pro',sans-serif;font-size:13px;font-weight:700;transition:all .2s;white-space:nowrap}
    .btn-sell:hover{background:#e67e22;transform:translateY(-1px)}
    .btn-ghost{background:transparent;color:var(--text);border:1px solid var(--border);cursor:pointer;padding:9px 16px;border-radius:40px;font-family:'Kantumruy Pro',sans-serif;font-size:13px;transition:all .2s;white-space:nowrap}
    .btn-ghost:hover{border-color:var(--red2);color:var(--red2)}
    .user-chip{display:flex;align-items:center;gap:8px;background:var(--card);border:1px solid var(--border);border-radius:40px;padding:5px 14px 5px 5px;cursor:pointer;transition:all .2s}
    .user-chip:hover{border-color:var(--red2)}
    .avatar{width:32px;height:32px;border-radius:50%;background:var(--red);display:flex;align-items:center;justify-content:center;font-size:14px;font-weight:700;color:#fff;flex-shrink:0}
    .uname{font-size:13px;font-weight:600;max-width:100px;overflow:hidden;text-overflow:ellipsis;white-space:nowrap}
    .udrop-wrap{position:relative}
    .udrop{position:absolute;top:calc(100%+8px);right:0;background:var(--surface);border:1px solid var(--border);border-radius:12px;min-width:180px;box-shadow:0 16px 40px rgba(0,0,0,.6);display:none;z-index:300;overflow:hidden}
    .udrop.open{display:block;animation:fadeUp .15s ease}
    .udrop-item{padding:12px 18px;font-size:13px;cursor:pointer;transition:background .15s;display:flex;align-items:center;gap:9px}
    .udrop-item:hover{background:var(--card)}
    .udrop-div{height:1px;background:var(--border)}

    /* HERO */
    .hero{background:linear-gradient(135deg,#1a0505 0%,#2d0808 45%,#130303 100%);border-bottom:1px solid var(--border);padding:52px clamp(16px,5vw,60px) 48px;display:grid;grid-template-columns:1fr auto;gap:28px;align-items:center}
    .hero-eye{font-size:12px;font-weight:700;letter-spacing:2px;color:var(--gold);margin-bottom:10px;text-transform:uppercase}
    .hero-h1{font-family:'Bebas Neue',sans-serif;font-size:clamp(48px,9vw,92px);line-height:.92;letter-spacing:3px;margin-bottom:12px}
    .hero-h1 span{color:var(--red2)}
    .hero-sub{font-size:15px;color:var(--muted);line-height:1.75;max-width:460px;margin-bottom:22px}
    .hero-pills{display:flex;gap:8px;flex-wrap:wrap}
    .pill{background:rgba(255,255,255,.05);border:1px solid var(--border);color:var(--muted);font-size:12px;padding:5px 12px;border-radius:20px}
    .hero-aside{display:flex;flex-direction:column;gap:12px;text-align:center}
    .stat-box{background:rgba(255,255,255,.04);border:1px solid var(--border);border-radius:12px;padding:16px 24px}
    .stat-n{font-family:'Bebas Neue',sans-serif;font-size:36px;color:var(--red2);letter-spacing:2px}
    .stat-l{font-size:11px;color:var(--muted);text-transform:uppercase;letter-spacing:1px}

    /* PROFILE BANNER */
    .pbanner{background:linear-gradient(90deg,#1a0505,#2d0808);border-bottom:1px solid var(--border);padding:18px clamp(12px,4vw,48px);display:flex;align-items:center;gap:16px}
    .pb-av{width:52px;height:52px;border-radius:50%;background:var(--red);display:flex;align-items:center;justify-content:center;font-size:22px;font-weight:700;color:#fff;flex-shrink:0;border:3px solid rgba(192,57,43,.4)}
    .pb-info h3{font-size:17px;font-weight:700;margin-bottom:2px}
    .pb-info p{font-size:13px;color:var(--muted)}
    .pb-stats{margin-left:auto;display:flex;gap:24px;text-align:center}
    .pbs-n{font-family:'Bebas Neue',sans-serif;font-size:26px;color:var(--red2)}
    .pbs-l{font-size:11px;color:var(--muted);text-transform:uppercase;letter-spacing:1px}

    /* CATS */
    .cats-wrap{padding:22px clamp(12px,4vw,48px) 0;overflow-x:auto}
    .cats{display:flex;gap:10px;padding-bottom:6px;min-width:max-content}
    .cat{background:var(--card);border:1px solid var(--border);color:var(--muted);cursor:pointer;padding:9px 18px;border-radius:40px;font-family:'Kantumruy Pro',sans-serif;font-size:13px;transition:all .2s;white-space:nowrap}
    .cat:hover{border-color:var(--red);color:var(--text)}
    .cat.active{background:var(--red);border-color:var(--red);color:#fff}

    /* TYPE TABS */
    .type-bar{display:flex;gap:4px;padding:16px clamp(12px,4vw,48px) 0}
    .ttab{background:transparent;border:1px solid var(--border);color:var(--muted);cursor:pointer;padding:8px 16px;border-radius:8px;font-family:'Kantumruy Pro',sans-serif;font-size:13px;transition:all .2s}
    .ttab:hover{border-color:var(--red2);color:var(--text)}
    .ttab.active{background:var(--red);border-color:var(--red);color:#fff}

    /* SEC HEAD */
    .sec-head{display:flex;align-items:center;justify-content:space-between;padding:22px clamp(12px,4vw,48px) 12px}
    .sec-head h2{font-family:'Bebas Neue',sans-serif;font-size:26px;letter-spacing:2px}
    .sec-head h2 span{color:var(--red2)}
    .res-count{font-size:13px;color:var(--muted)}

    /* GRID */
    .grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(220px,1fr));gap:16px;padding:0 clamp(12px,4vw,48px) 60px}
    .empty{grid-column:1/-1;text-align:center;padding:80px 20px;color:var(--muted)}
    .ring{display:inline-block;width:36px;height:36px;border:3px solid rgba(192,57,43,.2);border-top-color:var(--red);border-radius:50%;animation:spin .7s linear infinite}

    /* CARD */
    .lcard{background:var(--card);border:1px solid var(--border);border-radius:var(--radius);overflow:hidden;cursor:pointer;transition:all .25s;animation:fadeUp .35s ease both;display:flex;flex-direction:column;position:relative}
    .lcard:hover:not(.is-sold){border-color:var(--red);transform:translateY(-4px);box-shadow:0 12px 32px rgba(192,57,43,.2)}
    .lcard.is-sold{opacity:.7;cursor:default}
    .lcard.is-sold .cimg{filter:grayscale(.5)}

    /* SOLD OVERLAY */
    .sold-overlay{position:absolute;top:0;left:0;right:0;bottom:0;background:rgba(0,0,0,.45);display:flex;align-items:center;justify-content:center;z-index:3;border-radius:var(--radius)}
    .sold-stamp{background:#1e1e1e;border:3px solid #555;color:#888;font-family:'Bebas Neue',sans-serif;font-size:28px;letter-spacing:4px;padding:8px 22px;border-radius:8px;transform:rotate(-10deg)}

    .cimg{height:168px;background:var(--surface);display:flex;align-items:center;justify-content:center;font-size:64px;position:relative;overflow:hidden}
    .cimg img{width:100%;height:100%;object-fit:cover}
    .type-badge{position:absolute;top:9px;left:9px;font-size:10px;font-weight:700;letter-spacing:1px;text-transform:uppercase;padding:3px 9px;border-radius:4px;z-index:2}
    .tb-sell   {background:rgba(192,57,43,.9);color:#fff}
    .tb-wanted {background:rgba(243,156,18,.9);color:#111}
    .tb-service{background:rgba(39,174,96,.9);color:#fff}
    .cond-tag{position:absolute;top:9px;right:9px;font-size:10px;padding:3px 8px;border-radius:4px;background:rgba(0,0,0,.75);color:var(--muted);z-index:2}

    .cbody{padding:13px;flex:1;display:flex;flex-direction:column}
    .ccat{font-size:10px;font-weight:700;text-transform:uppercase;letter-spacing:1px;color:var(--red2);margin-bottom:4px}
    .ctitle{font-size:14px;font-weight:600;line-height:1.35;margin-bottom:3px;display:-webkit-box;-webkit-line-clamp:2;-webkit-box-orient:vertical;overflow:hidden}
    .ctitlekh{font-size:12px;color:var(--muted);margin-bottom:8px;display:-webkit-box;-webkit-line-clamp:1;-webkit-box-orient:vertical;overflow:hidden}
    .cfoot{margin-top:auto;display:flex;align-items:flex-end;justify-content:space-between;gap:8px}
    .cprice{font-family:'Bebas Neue',sans-serif;font-size:22px;letter-spacing:1px}
    .cprice.usd{color:var(--green)}
    .cprice.khr{color:var(--gold);font-size:17px}
    .cprice.sold-price{color:var(--sold);text-decoration:line-through}
    .cloc{font-size:11px;color:var(--muted);margin-top:2px}
    .cviews{font-size:10px;color:var(--muted);margin-top:4px}

    /* BUY / SOLD button */
    .buy-btn{background:var(--green);color:#fff;border:none;cursor:pointer;padding:8px 14px;border-radius:8px;font-family:'Kantumruy Pro',sans-serif;font-size:12px;font-weight:700;transition:all .2s;white-space:nowrap;flex-shrink:0}
    .buy-btn:hover{background:#219a52;transform:scale(1.05)}
    .sold-btn{background:var(--border);color:var(--muted);border:none;padding:8px 14px;border-radius:8px;font-size:12px;font-weight:700;white-space:nowrap;cursor:default;flex-shrink:0}
    .wanted-btn{background:rgba(243,156,18,.15);color:var(--gold);border:1px solid rgba(243,156,18,.3);cursor:pointer;padding:8px 12px;border-radius:8px;font-family:'Kantumruy Pro',sans-serif;font-size:12px;font-weight:700;white-space:nowrap;flex-shrink:0;transition:all .2s}
    .wanted-btn:hover{background:rgba(243,156,18,.25)}

    /* STATUS TAG */
    .status-tag{display:inline-flex;align-items:center;gap:5px;font-size:11px;font-weight:700;padding:3px 10px;border-radius:20px;margin-top:5px}
    .status-available{background:rgba(39,174,96,.12);color:var(--green);border:1px solid rgba(39,174,96,.3)}
    .status-sold{background:rgba(100,100,100,.15);color:#666;border:1px solid #333}

    /* MODALS */
    .mbg{position:fixed;inset:0;background:rgba(0,0,0,.88);z-index:400;display:none;align-items:center;justify-content:center;padding:16px}
    .mbg.open{display:flex}
    .modal{background:var(--surface);border:1px solid var(--border);border-radius:20px;width:100%;max-width:580px;max-height:92vh;overflow-y:auto;animation:slideUp .28s ease}
    .mhead{padding:20px 24px;border-bottom:1px solid var(--border);display:flex;align-items:center;justify-content:space-between;position:sticky;top:0;background:var(--surface);z-index:2}
    .mhead h2{font-family:'Bebas Neue',sans-serif;font-size:24px;letter-spacing:2px}
    .xbtn{background:var(--card);border:none;color:var(--muted);cursor:pointer;width:34px;height:34px;border-radius:50%;font-size:15px;display:flex;align-items:center;justify-content:center;transition:all .2s}
    .xbtn:hover{background:var(--red);color:#fff}
    .mbody{padding:22px 24px}

    /* AUTH */
    .auth-tabs{display:flex;border-bottom:1px solid var(--border);margin-bottom:22px}
    .auth-tab{flex:1;padding:13px;text-align:center;font-size:14px;font-weight:600;cursor:pointer;border:none;background:transparent;color:var(--muted);font-family:'Kantumruy Pro',sans-serif;border-bottom:3px solid transparent;transition:all .2s}
    .auth-tab.active{color:var(--text);border-bottom-color:var(--red)}
    .auth-panel{display:none}
    .auth-panel.active{display:block;animation:fadeUp .2s ease}
    .auth-logo{text-align:center;margin-bottom:20px}
    .auth-logo div{font-family:'Bebas Neue',sans-serif;font-size:40px;color:var(--red2);letter-spacing:4px}
    .auth-logo p{color:var(--muted);font-size:13px;margin-top:2px}
    .auth-switch{text-align:center;margin-top:14px;font-size:13px;color:var(--muted)}
    .auth-switch a{color:var(--red2);cursor:pointer;text-decoration:underline}
    .or-line{display:flex;align-items:center;gap:12px;margin:14px 0;color:var(--muted);font-size:12px}
    .or-line::before,.or-line::after{content:'';flex:1;height:1px;background:var(--border)}
    .err-box{background:rgba(231,76,60,.1);border:1px solid rgba(231,76,60,.3);color:#e74c3c;border-radius:8px;padding:10px 14px;font-size:13px;margin-bottom:14px;display:none}
    .err-box.show{display:block}

    /* FORMS */
    .fg{margin-bottom:14px}
    .fg label{display:block;font-size:11px;font-weight:700;text-transform:uppercase;letter-spacing:1px;color:var(--muted);margin-bottom:5px}
    .fg input,.fg select,.fg textarea{width:100%;background:var(--card);border:1px solid var(--border);color:var(--text);padding:12px 14px;border-radius:9px;font-family:'Kantumruy Pro',sans-serif;font-size:14px;outline:none;transition:border-color .2s}
    .fg input:focus,.fg select:focus,.fg textarea:focus{border-color:var(--red)}
    .fg select option{background:var(--card)}
    .fg textarea{min-height:88px;resize:vertical}
    .frow{display:grid;grid-template-columns:1fr 1fr;gap:12px}
    .price-wrap{display:flex}
    .cur-sel{background:var(--border);border:1px solid var(--border);border-right:none;color:var(--text);padding:12px 10px;border-radius:9px 0 0 9px;font-size:13px;outline:none;font-family:'Kantumruy Pro',sans-serif}
    .price-inp{border-radius:0 9px 9px 0!important}
    .pw-wrap{position:relative}
    .pw-wrap input{padding-right:44px}
    .pw-eye{position:absolute;right:12px;top:50%;transform:translateY(-50%);background:none;border:none;cursor:pointer;font-size:16px;color:var(--muted);padding:4px}
    .strength-bar{height:4px;border-radius:2px;margin-top:6px;background:var(--border);overflow:hidden}
    .strength-fill{height:100%;border-radius:2px;transition:width .3s,background .3s;width:0}

    /* BIG BUTTONS */
    .auth-btn{width:100%;background:var(--red);color:#fff;border:none;cursor:pointer;padding:14px;border-radius:11px;font-family:'Kantumruy Pro',sans-serif;font-size:15px;font-weight:700;transition:all .2s;margin-top:4px}
    .auth-btn:hover{background:var(--red2)}
    .auth-btn:disabled{background:var(--border);cursor:not-allowed;color:var(--muted)}
    .gold-btn{width:100%;background:var(--gold);color:#111;border:none;cursor:pointer;padding:14px;border-radius:11px;font-family:'Kantumruy Pro',sans-serif;font-size:15px;font-weight:700;transition:all .2s;margin-top:4px}
    .gold-btn:hover{background:#e67e22}
    .gold-btn:disabled{background:var(--border);cursor:not-allowed;color:var(--muted)}
    .green-btn{width:100%;background:var(--green);color:#fff;border:none;cursor:pointer;padding:15px;border-radius:11px;font-family:'Kantumruy Pro',sans-serif;font-size:16px;font-weight:700;transition:all .2s}
    .green-btn:hover{background:#219a52}

    /* DETAIL */
    .dimg{height:252px;background:var(--card);border-radius:12px;overflow:hidden;margin-bottom:18px;display:flex;align-items:center;justify-content:center;font-size:88px;position:relative}
    .dimg img{width:100%;height:100%;object-fit:cover}
    .dimg .sold-overlay{border-radius:12px}
    .dprice{font-family:'Bebas Neue',sans-serif;font-size:42px;letter-spacing:2px;margin:6px 0}
    .dmeta{display:flex;flex-wrap:wrap;gap:8px;margin:12px 0}
    .dtag{background:var(--card);border:1px solid var(--border);font-size:12px;padding:4px 12px;border-radius:20px;color:var(--muted)}
    .sbox{background:var(--card);border:1px solid var(--border);border-radius:12px;padding:16px;margin:18px 0}
    .sbox h4{font-size:11px;text-transform:uppercase;letter-spacing:1px;color:var(--muted);margin-bottom:10px}

    /* CALL BOX */
    .call-box{background:rgba(39,174,96,.08);border:2px solid rgba(39,174,96,.3);border-radius:14px;padding:20px;text-align:center;margin:16px 0}
    .call-box h3{font-size:15px;color:var(--green);margin-bottom:6px;font-weight:700}
    .call-number{font-family:'Bebas Neue',sans-serif;font-size:32px;color:var(--text);letter-spacing:2px;margin:8px 0}
    .call-now-btn{display:inline-flex;align-items:center;gap:8px;background:var(--green);color:#fff;border:none;cursor:pointer;padding:12px 28px;border-radius:40px;font-family:'Kantumruy Pro',sans-serif;font-size:15px;font-weight:700;text-decoration:none;transition:all .2s;margin-top:8px}
    .call-now-btn:hover{background:#219a52;transform:scale(1.04)}
    .telegram-btn{display:inline-flex;align-items:center;gap:8px;background:#229ED9;color:#fff;border:none;cursor:pointer;padding:12px 28px;border-radius:40px;font-family:'Kantumruy Pro',sans-serif;font-size:15px;font-weight:700;text-decoration:none;transition:all .2s;margin-top:8px;margin-left:8px}
    .telegram-btn:hover{background:#1a8cbf;transform:scale(1.04)}

    /* SELLER SECTION */
    .seller-section{background:var(--card);border:1px solid var(--border);border-left:3px solid var(--red);border-radius:10px;padding:14px;margin-bottom:14px}
    .seller-lbl{font-size:11px;text-transform:uppercase;letter-spacing:1px;color:var(--muted);font-weight:700;margin-bottom:12px}

    /* MY LISTINGS item */
    .my-item{display:flex;align-items:center;gap:14px;padding:14px 0;border-bottom:1px solid var(--border)}
    .my-item-icon{font-size:34px;width:44px;text-align:center;flex-shrink:0}
    .mark-sold-btn{background:rgba(100,100,100,.15);border:1px solid #444;color:#aaa;cursor:pointer;padding:5px 10px;border-radius:7px;font-size:11px;transition:all .2s;white-space:nowrap}
    .mark-sold-btn:hover{background:rgba(192,57,43,.2);border-color:var(--red);color:var(--red)}
    .del-btn{background:rgba(231,76,60,.1);border:1px solid rgba(231,76,60,.3);color:#e74c3c;cursor:pointer;padding:5px 10px;border-radius:7px;font-size:11px;transition:all .2s;white-space:nowrap;margin-left:6px}
    .del-btn:hover{background:#e74c3c;color:#fff}

    /* TOAST */
    .toast{position:fixed;bottom:24px;left:50%;transform:translateX(-50%) translateY(80px);background:var(--card);border:1px solid var(--border);color:var(--text);padding:11px 22px;border-radius:40px;font-size:13px;font-weight:500;z-index:9999;transition:transform .3s cubic-bezier(.4,0,.2,1);box-shadow:0 8px 32px rgba(0,0,0,.5);white-space:nowrap;pointer-events:none}
    .toast.show{transform:translateX(-50%) translateY(0)}

    /* FOOTER */
    footer{background:var(--surface);border-top:1px solid var(--border);padding:40px clamp(16px,4vw,48px);display:grid;grid-template-columns:repeat(auto-fit,minmax(190px,1fr));gap:28px}
    .ftlogo{font-family:'Bebas Neue',sans-serif;font-size:34px;color:var(--red2);letter-spacing:3px;margin-bottom:6px}
    .ftsub{font-size:12px;color:var(--muted);line-height:1.7}
    footer h4{font-size:11px;text-transform:uppercase;letter-spacing:1px;color:var(--muted);margin-bottom:10px}
    footer p{font-size:13px;line-height:1.8;color:var(--text)}
    .ftbottom{background:var(--surface);border-top:1px solid var(--border);text-align:center;padding:14px;color:var(--muted);font-size:12px}

    @keyframes fadeUp{from{opacity:0;transform:translateY(14px)}to{opacity:1;transform:translateY(0)}}
    @keyframes slideUp{from{opacity:0;transform:translateY(22px)}to{opacity:1;transform:translateY(0)}}
    @keyframes spin{to{transform:rotate(360deg)}}
    @keyframes pulse{0%,100%{box-shadow:0 0 0 0 rgba(39,174,96,.4)}50%{box-shadow:0 0 0 10px rgba(39,174,96,0)}}

    @media(max-width:620px){
      .hero{grid-template-columns:1fr}.hero-aside{flex-direction:row}
      .stat-box{flex:1}.frow{grid-template-columns:1fr}
      .btn-ghost{display:none}.pb-stats{display:none}
    }
  </style>
</head>
<body>

<!-- MOCK google.script.run FOR BROWSER (auto-replaced in Apps Script) -->
<script>
if (typeof google === 'undefined') {
  var _db  = function(){ return JSON.parse(localStorage.getItem('cfry_listings')  || '[]'); };
  var _usr = function(){ return JSON.parse(localStorage.getItem('cfry_users')     || '[]'); };
  var _inq = function(){ return JSON.parse(localStorage.getItem('cfry_inquiries') || '[]'); };

  var google = { script: { run: {
    withSuccessHandler: function(fn){ this._sh=fn; return this; },
    withFailureHandler: function(fn){ this._fh=fn; return this; },

    getCategories: function(){
      var fn=this._sh;
      setTimeout(function(){ fn([
        {id:"all",     label:"ទំនិញទាំងអស់",   icon:"🏪"},
        {id:"phones",  label:"ទូរសព្ទ & Tech",  icon:"📱"},
        {id:"clothes", label:"សម្លៀកបំពាក់",   icon:"👗"},
        {id:"vehicles",label:"យានយន្ត",         icon:"🏍️"},
        {id:"food",    label:"អាហារ & ភេសជ្ជៈ", icon:"🍜"},
        {id:"home",    label:"គ្រឿងផ្ទះ",        icon:"🛋️"},
        {id:"beauty",  label:"សម្ផស្ស",          icon:"💄"},
        {id:"kids",    label:"ទំនិញកុមារ",        icon:"🧸"},
        {id:"books",   label:"សៀវភៅ & សិក្សា",  icon:"📚"},
        {id:"sports",  label:"កីឡា & ការហាត់",   icon:"⚽"},
        {id:"other",   label:"ផ្សេងៗ",            icon:"📦"}
      ]); },50);
    },

    getListings: function(f){
      var fn=this._sh;
      setTimeout(function(){
        var rows=_db().filter(function(r){ return r.Status==='Active'||r.Status==='Sold'; });
        if(f&&f.category&&f.category!=='all') rows=rows.filter(function(r){return r.Category===f.category;});
        if(f&&f.search&&f.search.trim()){var q=f.search.toLowerCase();rows=rows.filter(function(r){return(r.Title||'').toLowerCase().includes(q)||(r.Description||'').toLowerCase().includes(q)||(r.TitleKh||'').includes(f.search)||(r.Location||'').toLowerCase().includes(q);});}
        if(f&&f.type&&f.type!=='all') rows=rows.filter(function(r){return r.Type===f.type;});
        fn(rows.slice().reverse());
      },80);
    },

    signUp: function(d){
      var fn=this._sh;
      setTimeout(function(){
        var users=_usr();
        if(users.find(function(u){return u.email.toLowerCase()===d.email.toLowerCase();}))
          return fn({success:false,error:'This email is already registered. Please log in.'});
        var user={id:'U-'+Date.now(),name:d.name,email:d.email.toLowerCase(),phone:d.phone||'',password:d.password,joined:new Date().toLocaleString(),listings:0};
        users.push(user);
        localStorage.setItem('cfry_users',JSON.stringify(users));
        fn({success:true,user:{id:user.id,name:user.name,email:user.email,phone:user.phone,joined:user.joined,listings:0}});
      },100);
    },

    logIn: function(d){
      var fn=this._sh;
      setTimeout(function(){
        var users=_usr();
        var u=users.find(function(u){return u.email.toLowerCase()===d.email.toLowerCase()&&u.password===d.password;});
        if(!u) return fn({success:false,error:'Wrong email or password.'});
        var myCount=_db().filter(function(r){return r.SellerEmail===u.email&&(r.Status==='Active'||r.Status==='Sold');}).length;
        fn({success:true,user:{id:u.id,name:u.name,email:u.email,phone:u.phone,joined:u.joined,listings:myCount}});
      },100);
    },

    postListing: function(d){
      var fn=this._sh;
      setTimeout(function(){
        var rows=_db();
        var id='CFM-'+Date.now();
        rows.push({
          ID:id, Date:new Date().toLocaleString('en-GB'),
          Title:d.title, TitleKh:d.titleKh||'',
          Description:d.description, Price:d.price, Currency:d.currency||'USD',
          Category:d.category, Location:d.location,
          SellerName:d.sellerName, SellerPhone:d.sellerPhone, SellerEmail:d.sellerEmail||'',
          ImageUrl:d.imageUrl||'', Type:d.type||'sell',
          Status:'Active', Views:0, Condition:d.condition||'Used'
        });
        localStorage.setItem('cfry_listings',JSON.stringify(rows));
        var users=_usr();
        var ui=users.findIndex(function(u){return u.email===d.sellerEmail;});
        if(ui>-1){users[ui].listings=(users[ui].listings||0)+1;localStorage.setItem('cfry_users',JSON.stringify(users));}
        fn({success:true,id:id});
      },80);
    },

    markSold: function(id){
      var fn=this._sh;
      setTimeout(function(){
        var rows=_db().map(function(r){if(r.ID===id)r.Status='Sold';return r;});
        localStorage.setItem('cfry_listings',JSON.stringify(rows));
        fn(true);
      },50);
    },

    deleteListing: function(id){
      var fn=this._sh;
      setTimeout(function(){
        var rows=_db().map(function(r){if(r.ID===id)r.Status='Deleted';return r;});
        localStorage.setItem('cfry_listings',JSON.stringify(rows));
        fn(true);
      },50);
    },

    logInquiry: function(d){
      var fn=this._sh;
      setTimeout(function(){
        var rows=_inq();
        rows.push({Date:new Date().toLocaleString(),ListingId:d.listingId,Item:d.itemTitle,BuyerName:d.buyerName,BuyerEmail:d.buyerEmail,BuyerPhone:d.buyerPhone});
        localStorage.setItem('cfry_inquiries',JSON.stringify(rows));
        fn(true);
      },50);
    },

    getMyListings: function(email){
      var fn=this._sh;
      setTimeout(function(){
        fn(_db().filter(function(r){return r.SellerEmail===email&&r.Status!=='Deleted';}).reverse());
      },70);
    }
  }}};
}
</script>

<!-- TOPBAR -->
<div class="topbar">🇰🇭 ចូលរួមទិញ ឬ លក់ — <strong>C.Fry Marketplace</strong> — Buy &amp; Sell in Cambodia — FREE</div>

<!-- NAV -->
<nav>
  <span class="logo" onclick="location.reload()">C.FRY<sup>KH</sup></span>
  <div class="search-bar">
    <input type="text" id="searchInput" placeholder="ស្វែងរក... Search anything..." oninput="onSearch()"/>
    <button onclick="doSearch()">🔍</button>
  </div>
  <div class="nav-right" id="navRight"></div>
</nav>

<!-- HERO -->
<section class="hero">
  <div>
    <div class="hero-eye">ផ្សារអនឡាញ — Khmer Online Marketplace</div>
    <h1 class="hero-h1">BUY &amp;<br>SELL<br><span>ANYTHING</span></h1>
    <p class="hero-sub">ជួញដូរអ្វីក៏បាន — phones, clothes, bikes, food &amp; more.<br><strong>Sign up free. List in seconds. Call the seller.</strong></p>
    <div class="hero-pills">
      <span class="pill">📱 Phones</span><span class="pill">👗 Clothes</span>
      <span class="pill">🏍️ Bikes</span><span class="pill">🍜 Food</span><span class="pill">🧸 Kids</span>
    </div>
  </div>
  <div class="hero-aside">
    <div class="stat-box"><div class="stat-n" id="heroCount">0</div><div class="stat-l">Listings</div></div>
    <div class="stat-box"><div class="stat-n">FREE</div><div class="stat-l">To Post</div></div>
  </div>
</section>

<!-- PROFILE BANNER -->
<div class="pbanner" id="profileBanner" style="display:none">
  <div class="pb-av" id="pbAv"></div>
  <div class="pb-info">
    <h3 id="pbName"></h3>
    <p id="pbEmail"></p>
  </div>
  <div class="pb-stats">
    <div><div class="pbs-n" id="pbListings">0</div><div class="pbs-l">My Listings</div></div>
  </div>
</div>

<!-- CATS -->
<div class="cats-wrap"><div class="cats" id="catsBox"><span style="color:var(--muted);padding:10px;font-size:13px">Loading...</span></div></div>

<!-- TYPE TABS -->
<div class="type-bar">
  <button class="ttab active" onclick="filterType('all',this)">ទំនិញទាំងអស់</button>
  <button class="ttab" onclick="filterType('sell',this)">🏷️ For Sale</button>
  <button class="ttab" onclick="filterType('wanted',this)">🔍 Wanted</button>
  <button class="ttab" onclick="filterType('service',this)">💼 Services</button>
</div>

<!-- SECTION HEAD -->
<div class="sec-head">
  <h2>LATEST <span>LISTINGS</span></h2>
  <span class="res-count" id="resCount">Loading...</span>
</div>

<!-- GRID -->
<div class="grid" id="mainGrid">
  <div class="empty"><div class="ring"></div><p style="margin-top:14px">Loading listings...</p></div>
</div>

<!-- FOOTER -->
<footer>
  <div>
    <div class="ftlogo">C.FRY</div>
    <p class="ftsub">ផ្សារអនឡាញ Khmer<br>Buy &amp; sell everyday items in Cambodia. Free listings, call sellers directly.</p>
  </div>
  <div><h4>How it works</h4><p>1. Sign up free<br>2. Post your item<br>3. Buyer calls you<br>4. Meet &amp; sell! 🎉</p></div>
  <div><h4>Categories</h4><p>📱 Phones &amp; Tech<br>👗 Clothes<br>🏍️ Vehicles<br>🍜 Food<br>🧸 Kids Items</p></div>
  <div><h4>Contact</h4><p>📧 hello@cfry.kh<br>📍 Cambodia<br>🕐 24/7 Online</p></div>
</footer>
<div class="ftbottom">© 2025 C.Fry Khmer Marketplace 🇰🇭 — All rights reserved</div>


<!-- ══════════════════ AUTH MODAL ══════════════════ -->
<div class="mbg" id="authModal">
  <div class="modal" style="max-width:440px">
    <div class="mhead" style="border:none;padding-bottom:0"><div></div><button class="xbtn" onclick="closeM('authModal')">✕</button></div>
    <div class="mbody" style="padding-top:8px">
      <div class="auth-logo"><div>C.FRY</div><p>ផ្សារអនឡាញ Khmer Marketplace</p></div>
      <div class="auth-tabs">
        <button class="auth-tab active" id="tabLogin"  onclick="switchAuth('login')">🔑 Log In</button>
        <button class="auth-tab"        id="tabSignup" onclick="switchAuth('signup')">✨ Sign Up</button>
      </div>

      <!-- LOGIN -->
      <div class="auth-panel active" id="panelLogin">
        <div class="err-box" id="loginErr"></div>
        <div class="fg"><label>Email Address</label>
          <input type="email" id="liEmail" placeholder="your@email.com" onkeydown="if(event.key==='Enter')doLogin()"/></div>
        <div class="fg"><label>Password</label>
          <div class="pw-wrap"><input type="password" id="liPass" placeholder="Your password" onkeydown="if(event.key==='Enter')doLogin()"/>
          <button class="pw-eye" onclick="togglePw('liPass',this)">👁</button></div></div>
        <button class="auth-btn" id="loginBtn" onclick="doLogin()">🔑 Log In</button>
        <div class="or-line">or</div>
        <div class="auth-switch">No account? <a onclick="switchAuth('signup')">Sign Up FREE →</a></div>
      </div>

      <!-- SIGNUP -->
      <div class="auth-panel" id="panelSignup">
        <div class="err-box" id="signupErr"></div>
        <div class="frow">
          <div class="fg"><label>Full Name *</label><input type="text" id="suName" placeholder="Your name"/></div>
          <div class="fg"><label>Phone / Telegram</label><input type="tel" id="suPhone" placeholder="+855 ..."/></div>
        </div>
        <div class="fg"><label>Email Address *</label><input type="email" id="suEmail" placeholder="your@email.com"/></div>
        <div class="fg"><label>Password *</label>
          <div class="pw-wrap"><input type="password" id="suPass" placeholder="Min 6 characters" oninput="checkStrength(this.value)"/>
          <button class="pw-eye" onclick="togglePw('suPass',this)">👁</button></div>
          <div class="strength-bar"><div class="strength-fill" id="strengthFill"></div></div></div>
        <div class="fg"><label>Confirm Password *</label>
          <div class="pw-wrap"><input type="password" id="suPass2" placeholder="Repeat password"/>
          <button class="pw-eye" onclick="togglePw('suPass2',this)">👁</button></div></div>
        <button class="auth-btn" id="signupBtn" onclick="doSignup()">✨ Create Free Account</button>
        <div class="or-line">or</div>
        <div class="auth-switch">Have an account? <a onclick="switchAuth('login')">Log In →</a></div>
      </div>
    </div>
  </div>
</div>


<!-- ══════════════════ BUY / CALL SELLER MODAL ══════════════════ -->
<div class="mbg" id="buyModal">
  <div class="modal" style="max-width:460px">
    <div class="mhead"><h2 id="buyModalTitle">BUY THIS ITEM</h2><button class="xbtn" onclick="closeM('buyModal')">✕</button></div>
    <div class="mbody">

      <!-- item summary -->
      <div style="display:flex;gap:14px;align-items:center;background:var(--card);border-radius:12px;padding:14px;margin-bottom:18px">
        <div style="font-size:42px" id="buyItemIcon">📦</div>
        <div>
          <div style="font-weight:700;font-size:15px" id="buyItemTitle"></div>
          <div style="font-family:'Bebas Neue',sans-serif;font-size:24px;margin-top:2px" id="buyItemPrice"></div>
          <div style="font-size:12px;color:var(--muted);margin-top:2px" id="buyItemLoc"></div>
        </div>
      </div>

      <!-- call / telegram box -->
      <div class="call-box">
        <h3>📞 Call or Message the Seller</h3>
        <p style="color:var(--muted);font-size:13px;margin-bottom:10px">Contact them directly to arrange the purchase</p>
        <div class="call-number" id="buySellerPhone"></div>
        <div style="font-size:13px;color:var(--muted);margin-bottom:6px" id="buySellerName"></div>
        <div style="display:flex;flex-wrap:wrap;justify-content:center;gap:8px;margin-top:10px">
          <a class="call-now-btn" id="callLink" href="#">📞 Call Now</a>
          <a class="telegram-btn" id="telegramLink" href="#" target="_blank">✈️ Telegram</a>
        </div>
      </div>

      <p style="font-size:12px;color:var(--muted);text-align:center;line-height:1.6;margin-top:8px">
        💡 <strong style="color:var(--text)">Tip:</strong> Always meet in a public place. Inspect the item before paying. C.Fry does not handle payments.
      </p>

      <button class="green-btn" style="margin-top:16px" onclick="closeM('buyModal')">✅ Got it!</button>
    </div>
  </div>
</div>


<!-- ══════════════════ DETAIL MODAL ══════════════════ -->
<div class="mbg" id="detailModal">
  <div class="modal"><div class="mhead"><h2 id="dTitle">LISTING</h2><button class="xbtn" onclick="closeM('detailModal')">✕</button></div>
  <div class="mbody" id="dBody"></div></div>
</div>


<!-- ══════════════════ SELL MODAL ══════════════════ -->
<div class="mbg" id="sellModal">
  <div class="modal">
    <div class="mhead"><h2>📢 POST LISTING</h2><button class="xbtn" onclick="closeM('sellModal')">✕</button></div>
    <div class="mbody">
      <p style="color:var(--muted);font-size:13px;margin-bottom:18px">Post anything for FREE — buyers will call you directly!</p>
      <div class="fg"><label>Listing Type</label>
        <select id="lType"><option value="sell">🏷️ I'm Selling</option><option value="wanted">🔍 I Want to Buy</option><option value="service">💼 Service / Job</option></select></div>
      <div class="fg"><label>Item Title (English) *</label><input type="text" id="titleEn" placeholder="e.g. Samsung Galaxy S24 128GB"/></div>
      <div class="fg"><label>ចំណងជើង ខ្មែរ (optional)</label><input type="text" id="titleKh" placeholder="ឧ. Samsung Galaxy S24"/></div>
      <div class="frow">
        <div class="fg"><label>Category *</label>
          <select id="catSel">
            <option value="phones">📱 Phones &amp; Tech</option>
            <option value="clothes">👗 Clothes &amp; Fashion</option>
            <option value="vehicles">🏍️ Vehicles</option>
            <option value="food">🍜 Food &amp; Drinks</option>
            <option value="home">🛋️ Home Items</option>
            <option value="beauty">💄 Beauty &amp; Health</option>
            <option value="kids">🧸 Kids &amp; Babies</option>
            <option value="books">📚 Books &amp; Study</option>
            <option value="sports">⚽ Sports &amp; Fitness</option>
            <option value="other">📦 Other</option>
          </select></div>
        <div class="fg"><label>Condition</label>
          <select id="condSel">
            <option value="Brand New">✨ Brand New</option>
            <option value="Like New" selected>💎 Like New</option>
            <option value="Good Used">✅ Used - Good</option>
            <option value="Fair Used">⚡ Used - Fair</option>
          </select></div>
      </div>
      <div class="fg"><label>Description *</label><textarea id="descIn" placeholder="Describe your item — model, size, colour, reason for selling, any faults..."></textarea></div>
      <div class="fg"><label>Price *</label>
        <div class="price-wrap">
          <select class="cur-sel" id="curSel"><option value="USD">$ USD</option><option value="KHR">៛ KHR</option></select>
          <input type="number" id="priceIn" placeholder="0" min="0" class="price-inp" style="border-radius:0 9px 9px 0!important"/>
        </div></div>
      <div class="frow">
        <div class="fg"><label>Province *</label>
          <select id="locSel"><option>Phnom Penh</option><option>Siem Reap</option><option>Battambang</option><option>Sihanoukville</option><option>Kampot</option><option>Kampong Cham</option><option>Takeo</option><option>Kandal</option><option>Other Province</option></select></div>
        <div class="fg"><label>Image URL (optional)</label><input type="url" id="imgIn" placeholder="https://..."/></div>
      </div>
      <div class="seller-section">
        <div class="seller-lbl">Your Contact Info (shown to buyers)</div>
        <div class="frow" style="margin:0">
          <div class="fg" style="margin-bottom:10px"><label>Name *</label><input type="text" id="sName" placeholder="Your name"/></div>
          <div class="fg" style="margin-bottom:10px"><label>Phone / Telegram *</label><input type="tel" id="sPhone" placeholder="+855 ..."/></div>
        </div>
        <div class="fg" style="margin-bottom:0"><label>Email</label><input type="email" id="sEmail" placeholder="you@email.com"/></div>
      </div>
      <button class="gold-btn" id="postBtn" onclick="submitListing()">📢 Post FREE Now!</button>
    </div>
  </div>
</div>


<!-- ══════════════════ MY LISTINGS MODAL ══════════════════ -->
<div class="mbg" id="myListingsModal">
  <div class="modal">
    <div class="mhead"><h2>MY <span style="color:var(--red2)">LISTINGS</span></h2><button class="xbtn" onclick="closeM('myListingsModal')">✕</button></div>
    <div class="mbody" id="myListingsBody"><div style="text-align:center;padding:40px;color:var(--muted)"><div class="ring"></div></div></div>
  </div>
</div>


<!-- ══════════════════ SUCCESS MODAL ══════════════════ -->
<div class="mbg" id="okModal">
  <div class="modal" style="max-width:400px">
    <div class="mbody" style="text-align:center;padding:46px 26px">
      <div style="font-size:64px;margin-bottom:14px" id="okIcon">✅</div>
      <h2 style="font-family:'Bebas Neue',sans-serif;font-size:30px;letter-spacing:2px;margin-bottom:8px" id="okTitle">SUCCESS!</h2>
      <p style="color:var(--muted);font-size:14px;line-height:1.7;margin-bottom:8px" id="okMsg"></p>
      <div style="display:inline-block;background:rgba(192,57,43,.1);border:1px solid rgba(192,57,43,.3);color:var(--red2);padding:6px 16px;border-radius:8px;font-weight:700;font-size:13px;margin:10px 0 22px" id="okId"></div>
      <br><button class="gold-btn" style="max-width:200px;display:inline-block" onclick="closeM('okModal')">Continue →</button>
    </div>
  </div>
</div>

<!-- TOAST -->
<div class="toast" id="toast"></div>

<script>
// ═══ STATE ═══
var allListings  = [];
var cats         = [];
var activeFilter = { category:'all', type:'all', search:'' };
var currentUser  = null;
var searchTmr;
var CAT_ICONS    = {phones:"📱",clothes:"👗",vehicles:"🏍️",food:"🍜",home:"🛋️",beauty:"💄",kids:"🧸",books:"📚",sports:"⚽",other:"📦"};
var _pendingBuy  = null; // listing to buy after login

// ═══ INIT ═══
window.onload = function() {
  // Seed demo listings
  if (!localStorage.getItem('cfry_listings')) {
    localStorage.setItem('cfry_listings', JSON.stringify([
      {ID:'D1',Date:'01/01/2025',Title:'Samsung Galaxy A54 128GB',TitleKh:'Samsung Galaxy A54',Description:'Great condition, barely used. Comes with original charger and box. No scratches.',Price:180,Currency:'USD',Category:'phones',Location:'Phnom Penh',SellerName:'Dara Sok',SellerPhone:'+855 12 345 678',SellerEmail:'dara@demo.kh',ImageUrl:'',Type:'sell',Status:'Active',Views:31,Condition:'Like New'},
      {ID:'D2',Date:'01/01/2025',Title:'Honda Click 2023 125cc',TitleKh:'ហ្មមដា Click 2023',Description:'Only 5,000km. Well maintained, no accidents. All papers included.',Price:2200,Currency:'USD',Category:'vehicles',Location:'Siem Reap',SellerName:'Ratha Keo',SellerPhone:'+855 17 888 999',SellerEmail:'ratha@demo.kh',ImageUrl:'',Type:'sell',Status:'Active',Views:55,Condition:'Like New'},
      {ID:'D3',Date:'01/01/2025',Title:'Korean Style Dress - Size S/M',TitleKh:'សំពត់កូរ៉េ',Description:'Worn once. Blue floral pattern, very pretty. Size fits S/M.',Price:12,Currency:'USD',Category:'clothes',Location:'Phnom Penh',SellerName:'Sreyleak',SellerPhone:'+855 96 111 222',SellerEmail:'srey@demo.kh',ImageUrl:'',Type:'sell',Status:'Sold',Views:22,Condition:'Like New'},
      {ID:'D4',Date:'01/01/2025',Title:'Fresh Bai Sach Chrouk',TitleKh:'បាយសាច់ជ្រូក',Description:'Homemade Khmer pork rice, freshly cooked every morning. Order from 7am.',Price:1.5,Currency:'USD',Category:'food',Location:'Phnom Penh',SellerName:'Chenda Lim',SellerPhone:'+855 78 555 333',SellerEmail:'chenda@demo.kh',ImageUrl:'',Type:'sell',Status:'Active',Views:88,Condition:'Brand New'},
      {ID:'D5',Date:'01/01/2025',Title:'Gaming Chair - Like New',TitleKh:'កៅអីហ្គេម',Description:'Used for 3 months only. Black and red. Comfortable lumbar support. Pickup only.',Price:85,Currency:'USD',Category:'home',Location:'Phnom Penh',SellerName:'Visal Chan',SellerPhone:'+855 11 777 888',SellerEmail:'visal@demo.kh',ImageUrl:'',Type:'sell',Status:'Active',Views:19,Condition:'Like New'},
      {ID:'D6',Date:'01/01/2025',Title:'Nike Air Max 270 Size 42',TitleKh:'ស្បែកជើង Nike',Description:'Authentic, bought from Thailand. Size 42. Worn 3 times only. Still very clean.',Price:55,Currency:'USD',Category:'sports',Location:'Battambang',SellerName:'Sopheak',SellerPhone:'+855 12 600 700',SellerEmail:'sopheak@demo.kh',ImageUrl:'',Type:'sell',Status:'Active',Views:14,Condition:'Like New'},
      {ID:'D7',Date:'01/01/2025',Title:'Looking for Second-hand Laptop',TitleKh:'ស្វែងរក Laptop',Description:'Need a laptop for school. Budget max $250. Core i5 or better. Please call me.',Price:250,Currency:'USD',Category:'phones',Location:'Kampot',SellerName:'Borey',SellerPhone:'+855 11 900 123',SellerEmail:'borey@demo.kh',ImageUrl:'',Type:'wanted',Status:'Active',Views:7,Condition:''},
      {ID:'D8',Date:'01/01/2025',Title:'Khmer Tutor - Math & Science',TitleKh:'គ្រូបង្រៀន គណិត',Description:'Experienced tutor, 5 years. Grade 7-12. Home visits available. $5/hour.',Price:5,Currency:'USD',Category:'books',Location:'Phnom Penh',SellerName:'Teacher Vanna',SellerPhone:'+855 89 234 567',SellerEmail:'vanna@demo.kh',ImageUrl:'',Type:'service',Status:'Active',Views:43,Condition:''}
    ]));
  }

  var saved = localStorage.getItem('cfry_session');
  if (saved) { try { currentUser = JSON.parse(saved); } catch(e){} }

  renderNav();
  google.script.run.withSuccessHandler(function(c){ cats=c; renderCats(); }).getCategories();
  loadListings();
};

// ═══ NAV ═══
function renderNav() {
  var el = document.getElementById('navRight');
  var pb = document.getElementById('profileBanner');
  if (!currentUser) {
    el.innerHTML =
      '<button class="btn-ghost" onclick="openAuth(\'login\')">Log In</button>' +
      '<button class="btn-ghost" onclick="openAuth(\'signup\')">Sign Up</button>' +
      '<button class="btn-sell" onclick="openAuth(\'signup\')">+ Sell Now</button>';
    pb.style.display = 'none';
  } else {
    var ini = currentUser.name.charAt(0).toUpperCase();
    el.innerHTML =
      '<div class="udrop-wrap">' +
        '<div class="user-chip" onclick="toggleDrop()">' +
          '<div class="avatar">'+ini+'</div>' +
          '<span class="uname">'+escHtml(currentUser.name)+'</span>' +
          '<span style="color:var(--muted);font-size:10px;margin-left:2px">▾</span>' +
        '</div>' +
        '<div class="udrop" id="userDrop">' +
          '<div class="udrop-item" onclick="openMyListings()">📋 My Listings</div>' +
          '<div class="udrop-item" onclick="openM(\'sellModal\');closeDropdown()">📢 Post Listing</div>' +
          '<div class="udrop-div"></div>' +
          '<div class="udrop-item" onclick="doLogout()" style="color:#e74c3c">🚪 Log Out</div>' +
        '</div>' +
      '</div>' +
      '<button class="btn-sell" onclick="openM(\'sellModal\')">+ Sell Now</button>';

    if (currentUser.name)  document.getElementById('sName').value  = currentUser.name;
    if (currentUser.phone) document.getElementById('sPhone').value = currentUser.phone;
    if (currentUser.email) document.getElementById('sEmail').value = currentUser.email;

    document.getElementById('pbAv').textContent      = ini;
    document.getElementById('pbName').textContent    = currentUser.name;
    document.getElementById('pbEmail').textContent   = currentUser.email;
    document.getElementById('pbListings').textContent= currentUser.listings || 0;
    pb.style.display = 'flex';
  }
}

function toggleDrop(){ var d=document.getElementById('userDrop'); if(d)d.classList.toggle('open'); }
function closeDropdown(){ var d=document.getElementById('userDrop'); if(d)d.classList.remove('open'); }
document.addEventListener('click',function(e){ var w=document.querySelector('.udrop-wrap'); if(w&&!w.contains(e.target))closeDropdown(); });

// ═══ AUTH ═══
function openAuth(tab, afterBuy) {
  if (afterBuy) _pendingBuy = afterBuy;
  switchAuth(tab||'login');
  openM('authModal');
}
function switchAuth(tab) {
  document.getElementById('panelLogin').classList.toggle('active',tab==='login');
  document.getElementById('panelSignup').classList.toggle('active',tab==='signup');
  document.getElementById('tabLogin').classList.toggle('active',tab==='login');
  document.getElementById('tabSignup').classList.toggle('active',tab==='signup');
  document.getElementById('loginErr').classList.remove('show');
  document.getElementById('signupErr').classList.remove('show');
}
function togglePw(id,btn){ var i=document.getElementById(id); i.type=i.type==='password'?'text':'password'; btn.textContent=i.type==='password'?'👁':'🙈'; }
function checkStrength(pw){
  var f=document.getElementById('strengthFill'),s=0;
  if(pw.length>=6)s++; if(pw.length>=10)s++; if(/[A-Z]/.test(pw))s++; if(/[0-9]/.test(pw))s++; if(/[^a-zA-Z0-9]/.test(pw))s++;
  f.style.width=['0','20%','40%','60%','80%','100%'][s];
  f.style.background=['#e74c3c','#e74c3c','#e67e22','#f39c12','#27ae60','#27ae60'][s];
}
function doSignup(){
  var name=document.getElementById('suName').value.trim(), phone=document.getElementById('suPhone').value.trim(),
      email=document.getElementById('suEmail').value.trim(), pass=document.getElementById('suPass').value,
      pass2=document.getElementById('suPass2').value, err=document.getElementById('signupErr');
  err.classList.remove('show');
  if(!name||!email||!pass){err.textContent='Please fill in all required fields.';err.classList.add('show');return;}
  if(!email.includes('@')||!email.includes('.')){err.textContent='Please enter a valid email address.';err.classList.add('show');return;}
  if(pass.length<6){err.textContent='Password must be at least 6 characters.';err.classList.add('show');return;}
  if(pass!==pass2){err.textContent='Passwords do not match.';err.classList.add('show');return;}
  var btn=document.getElementById('signupBtn'); btn.disabled=true; btn.textContent='Creating account...';
  google.script.run
    .withSuccessHandler(function(r){
      btn.disabled=false; btn.textContent='✨ Create Free Account';
      if(r.success){
        currentUser=r.user; localStorage.setItem('cfry_session',JSON.stringify(currentUser));
        closeM('authModal'); renderNav(); loadListings();
        if(_pendingBuy){ var pb=_pendingBuy; _pendingBuy=null; setTimeout(function(){openBuyModal(pb);},300); }
        else showOk('🎉','WELCOME!','Account created! You can now buy and sell anything.',currentUser.email);
        ['suName','suPhone','suEmail','suPass','suPass2'].forEach(function(x){document.getElementById(x).value='';});
      } else { err.textContent=r.error||'Sign up failed.'; err.classList.add('show'); }
    })
    .withFailureHandler(function(){ btn.disabled=false; btn.textContent='✨ Create Free Account'; err.textContent='Something went wrong.'; err.classList.add('show'); })
    .signUp({name:name,phone:phone,email:email,password:pass});
}
function doLogin(){
  var email=document.getElementById('liEmail').value.trim(), pass=document.getElementById('liPass').value,
      err=document.getElementById('loginErr');
  err.classList.remove('show');
  if(!email||!pass){err.textContent='Please enter your email and password.';err.classList.add('show');return;}
  var btn=document.getElementById('loginBtn'); btn.disabled=true; btn.textContent='Logging in...';
  google.script.run
    .withSuccessHandler(function(r){
      btn.disabled=false; btn.textContent='🔑 Log In';
      if(r.success){
        currentUser=r.user; localStorage.setItem('cfry_session',JSON.stringify(currentUser));
        closeM('authModal'); renderNav(); loadListings();
        if(_pendingBuy){ var pb=_pendingBuy; _pendingBuy=null; setTimeout(function(){openBuyModal(pb);},300); }
        else showToast('👋 Welcome back, '+currentUser.name+'!');
        document.getElementById('liEmail').value=''; document.getElementById('liPass').value='';
      } else { err.textContent=r.error||'Login failed.'; err.classList.add('show'); }
    })
    .withFailureHandler(function(){ btn.disabled=false; btn.textContent='🔑 Log In'; err.textContent='Something went wrong.'; err.classList.add('show'); })
    .logIn({email:email,password:pass});
}
function doLogout(){ currentUser=null; localStorage.removeItem('cfry_session'); closeDropdown(); renderNav(); loadListings(); showToast('👋 Logged out.'); }

// ═══ CATEGORIES ═══
function renderCats(){
  document.getElementById('catsBox').innerHTML=cats.map(function(c){
    return '<button class="cat'+(c.id==='all'?' active':'')+'" onclick="filterCat(\''+c.id+'\',this)">'+c.icon+' '+c.label+'</button>';
  }).join('');
}
function filterCat(id,btn){ document.querySelectorAll('.cat').forEach(function(c){c.classList.remove('active');}); btn.classList.add('active'); activeFilter.category=id; loadListings(); }
function filterType(type,btn){ document.querySelectorAll('.ttab').forEach(function(t){t.classList.remove('active');}); btn.classList.add('active'); activeFilter.type=type; loadListings(); }
function onSearch(){ clearTimeout(searchTmr); searchTmr=setTimeout(function(){activeFilter.search=document.getElementById('searchInput').value;loadListings();},300); }
function doSearch(){ activeFilter.search=document.getElementById('searchInput').value; loadListings(); }

// ═══ LOAD LISTINGS ═══
function loadListings(){
  document.getElementById('mainGrid').innerHTML='<div class="empty"><div class="ring"></div><p style="margin-top:14px">Loading...</p></div>';
  google.script.run
    .withSuccessHandler(function(list){ allListings=list; renderGrid(list); document.getElementById('heroCount').textContent=list.length; })
    .withFailureHandler(function(){ document.getElementById('mainGrid').innerHTML='<div class="empty"><span style="font-size:48px;display:block;margin-bottom:12px">⚠️</span><p>Could not load listings.</p></div>'; })
    .getListings(activeFilter);
}

// ═══ RENDER GRID ═══
function renderGrid(list){
  document.getElementById('resCount').textContent=list.length+' listing'+(list.length!==1?'s':'');
  if(!list.length){
    document.getElementById('mainGrid').innerHTML='<div class="empty"><span style="font-size:52px;display:block;margin-bottom:14px">🔍</span><p>No listings found.<br><button onclick="openM(\'sellModal\')" style="background:var(--red);color:#fff;border:none;padding:10px 22px;border-radius:8px;cursor:pointer;margin-top:14px;font-size:14px">Be the first to post!</button></p></div>';
    return;
  }
  document.getElementById('mainGrid').innerHTML=list.map(function(l,i){
    var icon   = CAT_ICONS[l.Category]||'📦';
    var cur    = l.Currency||'USD';
    var price  = Number(l.Price||0);
    var ps     = cur==='KHR'?'៛'+price.toLocaleString():'$'+price.toFixed(2);
    var type   = l.Type||'sell';
    var tlbl   = type==='sell'?'For Sale':type==='wanted'?'Wanted':'Service';
    var sold   = l.Status==='Sold';
    var imgH   = l.ImageUrl?'<img src="'+l.ImageUrl+'" onerror="this.parentElement.innerHTML=\''+icon+'\'">':icon;

    // Action button
    var actionBtn;
    if(sold){
      actionBtn='<span class="sold-btn">✗ Sold</span>';
    } else if(type==='sell'){
      actionBtn='<button class="buy-btn" onclick="event.stopPropagation();clickBuy(\''+l.ID+'\')">🛒 Buy</button>';
    } else if(type==='wanted'){
      actionBtn='<button class="wanted-btn" onclick="event.stopPropagation();clickBuy(\''+l.ID+'\')">💬 Offer</button>';
    } else {
      actionBtn='<button class="buy-btn" style="background:#229ED9" onclick="event.stopPropagation();clickBuy(\''+l.ID+'\')">📞 Call</button>';
    }

    return [
      '<div class="lcard'+(sold?' is-sold':'')+'" style="animation-delay:'+Math.min(i*.04,.4)+'s"'+(sold?'':' onclick="openDetail(\''+l.ID+'\')"')+'>',
      sold?'<div class="sold-overlay"><div class="sold-stamp">SOLD</div></div>':'',
      '  <div class="cimg">'+imgH,
      '    <span class="type-badge tb-'+type+'">'+tlbl+'</span>',
      l.Condition?'    <span class="cond-tag">'+l.Condition+'</span>':'',
      '  </div>',
      '  <div class="cbody">',
      '    <div class="ccat">'+icon+' '+l.Category+'</div>',
      '    <div class="ctitle">'+(l.Title||'Item')+'</div>',
      l.TitleKh?'    <div class="ctitlekh">'+l.TitleKh+'</div>':'',
      '    <div class="cfoot">',
      '      <div>',
      '        <div class="cprice '+(cur==='KHR'?'khr':'usd')+(sold?' sold-price':'')+'">'+ps+'</div>',
      '        <div class="cloc">📍 '+(l.Location||'')+'</div>',
      '      </div>',
      '      '+actionBtn,
      '    </div>',
      '    <div style="display:flex;align-items:center;justify-content:space-between;margin-top:6px">',
      '      <div class="cviews">👁 '+(l.Views||0)+' views</div>',
      '      <span class="status-tag '+(sold?'status-sold':'status-available')+'">'+(sold?'✗ Sold':'✓ Available')+'</span>',
      '    </div>',
      '  </div>',
      '</div>'
    ].join('');
  }).join('');
}

// ═══ BUY FLOW ═══
function clickBuy(id){
  if(!currentUser){
    // Not logged in → gate them
    showToast('⚠️ Please sign up or log in to contact the seller');
    openAuth('signup', id);
    return;
  }
  openBuyModal(id);
}

function openBuyModal(id){
  var l=allListings.find(function(x){return x.ID===id;});
  if(!l) return;

  if(l.Status==='Sold'){ showToast('❌ Sorry, this item has already been sold!'); return; }

  var icon  = CAT_ICONS[l.Category]||'📦';
  var cur   = l.Currency||'USD';
  var price = Number(l.Price||0);
  var ps    = cur==='KHR'?'៛'+price.toLocaleString():'$'+price.toFixed(2);
  var phone = l.SellerPhone||'+855 ...';
  var type  = l.Type||'sell';

  document.getElementById('buyModalTitle').textContent = type==='wanted'?'MAKE AN OFFER':type==='service'?'CONTACT FOR SERVICE':'BUY THIS ITEM';
  document.getElementById('buyItemIcon').textContent   = icon;
  document.getElementById('buyItemTitle').textContent  = l.Title||'Item';
  document.getElementById('buyItemPrice').textContent  = ps;
  document.getElementById('buyItemLoc').textContent    = '📍 '+(l.Location||'') + (l.Condition?' · '+l.Condition:'');
  document.getElementById('buyItemPrice').style.color  = cur==='KHR'?'var(--gold)':'var(--green)';
  document.getElementById('buySellerPhone').textContent = phone;
  document.getElementById('buySellerName').textContent  = '👤 '+( l.SellerName||'Seller' );

  // Set call & telegram links
  var cleanPhone = phone.replace(/\s+/g,'');
  document.getElementById('callLink').href = 'tel:'+cleanPhone;
  document.getElementById('telegramLink').href = 'https://t.me/'+cleanPhone.replace('+','');

  // Log the inquiry
  google.script.run.logInquiry({
    listingId: l.ID, itemTitle: l.Title,
    buyerName: currentUser.name, buyerEmail: currentUser.email, buyerPhone: currentUser.phone||''
  });

  openM('buyModal');
}

// ═══ DETAIL VIEW ═══
function openDetail(id){
  var l=allListings.find(function(x){return x.ID===id;});
  if(!l) return;
  var icon  = CAT_ICONS[l.Category]||'📦';
  var cur   = l.Currency||'USD';
  var price = Number(l.Price||0);
  var ps    = cur==='KHR'?'៛'+price.toLocaleString():'$'+price.toFixed(2);
  var type  = l.Type||'sell';
  var tlbl  = type==='sell'?'🏷️ For Sale':type==='wanted'?'🔍 Wanted':'💼 Service';
  var sold  = l.Status==='Sold';
  var imgH  = l.ImageUrl?'<img src="'+l.ImageUrl+'" onerror="this.innerHTML=\''+icon+'\'">':icon;

  document.getElementById('dTitle').textContent=l.Title||'Listing';
  document.getElementById('dBody').innerHTML=[
    '<div class="dimg">'+imgH+(sold?'<div class="sold-overlay"><div class="sold-stamp">SOLD</div></div>':'')+'</div>',
    '<div class="ccat">'+icon+' '+l.Category+'</div>',
    '<h2 style="font-size:22px;font-weight:700;margin:4px 0">'+(l.Title||'')+'</h2>',
    l.TitleKh?'<p style="color:var(--muted);font-size:14px;margin:4px 0">'+l.TitleKh+'</p>':'',
    '<div class="dprice" style="color:'+(sold?'var(--sold)':cur==='KHR'?'var(--gold)':'var(--green)')+(sold?';text-decoration:line-through':'')+'">'+ps+'</div>',
    sold?'<span class="status-tag status-sold" style="font-size:14px;padding:5px 16px">✗ This item has been SOLD</span>':'<span class="status-tag status-available" style="font-size:13px;padding:5px 14px">✓ Available</span>',
    '<div class="dmeta">',
    '  <span class="dtag">'+tlbl+'</span>',
    '  <span class="dtag">📍 '+(l.Location||'')+'</span>',
    l.Condition&&!sold?'  <span class="dtag">✅ '+l.Condition+'</span>':'',
    '  <span class="dtag">👁 '+(l.Views||0)+' views</span>',
    '</div>',
    '<p style="color:var(--muted);font-size:14px;line-height:1.8;margin:16px 0">'+((l.Description||'').replace(/\n/g,'<br>'))+'</p>',
    '<div class="sbox">',
    '  <h4>Seller</h4>',
    '  <div style="font-size:16px;font-weight:700;margin-bottom:4px">👤 '+(l.SellerName||'Seller')+'</div>',
    '  <div style="font-size:14px;color:var(--muted)">📞 '+(l.SellerPhone||'—')+'</div>',
    '</div>',
    sold
      ? '<button class="auth-btn" style="background:var(--border);cursor:not-allowed;color:var(--muted)">✗ Already Sold</button>'
      : '<button class="green-btn" onclick="closeM(\'detailModal\');clickBuy(\''+l.ID+'\')">'+(type==='sell'?'🛒 Buy Now':type==='wanted'?'💬 Make Offer':'📞 Contact')+'</button>',
    '<p style="font-size:11px;color:var(--muted);text-align:center;margin-top:10px">Posted: '+(l.Date||'')+'</p>'
  ].join('');
  openM('detailModal');
}

// ═══ POST LISTING ═══
function submitListing(){
  if(!currentUser){ closeM('sellModal'); openAuth('signup'); showToast('⚠️ Please sign up first to post a listing'); return; }
  var title=document.getElementById('titleEn').value.trim(), desc=document.getElementById('descIn').value.trim(),
      price=document.getElementById('priceIn').value.trim(), sName=document.getElementById('sName').value.trim(),
      sPhone=document.getElementById('sPhone').value.trim();
  if(!title||!desc||!price||!sName||!sPhone){ showToast('⚠️ Please fill in all required fields (*)'); return; }
  var btn=document.getElementById('postBtn'); btn.disabled=true; btn.textContent='Posting...';
  google.script.run
    .withSuccessHandler(function(r){
      btn.disabled=false; btn.textContent='📢 Post FREE Now!';
      if(r.success){
        closeM('sellModal');
        currentUser.listings=(currentUser.listings||0)+1;
        localStorage.setItem('cfry_session',JSON.stringify(currentUser));
        renderNav(); loadListings();
        showOk('📢','LISTING LIVE!','Your item is now visible to buyers. They will call you directly!',r.id);
        ['titleEn','titleKh','descIn','priceIn','imgIn'].forEach(function(x){document.getElementById(x).value='';});
      } else { showToast('❌ '+(r.error||'Error posting')); }
    })
    .withFailureHandler(function(){ btn.disabled=false; btn.textContent='📢 Post FREE Now!'; showToast('❌ Failed. Try again.'); })
    .postListing({
      title:title, titleKh:document.getElementById('titleKh').value.trim(),
      description:desc, price:price, currency:document.getElementById('curSel').value,
      category:document.getElementById('catSel').value, condition:document.getElementById('condSel').value,
      location:document.getElementById('locSel').value, imageUrl:document.getElementById('imgIn').value.trim(),
      sellerName:sName, sellerPhone:sPhone,
      sellerEmail:document.getElementById('sEmail').value.trim()||currentUser.email,
      type:document.getElementById('lType').value
    });
}

// ═══ MY LISTINGS ═══
function openMyListings(){
  closeDropdown();
  if(!currentUser){ openAuth('login'); return; }
  document.getElementById('myListingsBody').innerHTML='<div style="text-align:center;padding:40px;color:var(--muted)"><div class="ring"></div><p style="margin-top:12px">Loading...</p></div>';
  openM('myListingsModal');
  google.script.run
    .withSuccessHandler(function(list){
      if(!list.length){
        document.getElementById('myListingsBody').innerHTML='<div style="text-align:center;padding:40px;color:var(--muted)"><span style="font-size:42px;display:block;margin-bottom:12px">📋</span><p>No listings yet.</p><button onclick="closeM(\'myListingsModal\');openM(\'sellModal\')" style="background:var(--red);color:#fff;border:none;padding:10px 20px;border-radius:8px;cursor:pointer;margin-top:14px">Post Your First Item</button></div>';
        return;
      }
      document.getElementById('myListingsBody').innerHTML=list.map(function(l){
        var icon=CAT_ICONS[l.Category]||'📦', cur=l.Currency||'USD', price=Number(l.Price||0);
        var ps=cur==='KHR'?'៛'+price.toLocaleString():'$'+price.toFixed(2);
        var sold=l.Status==='Sold';
        return '<div class="my-item">'+
          '<div class="my-item-icon">'+icon+'</div>'+
          '<div style="flex:1;min-width:0">'+
            '<div style="font-weight:600;font-size:14px;white-space:nowrap;overflow:hidden;text-overflow:ellipsis">'+(l.Title||'Item')+'</div>'+
            '<div style="font-size:12px;color:var(--muted);margin-top:2px">'+l.Category+' · 📍'+l.Location+' · 👁 '+(l.Views||0)+'</div>'+
          '</div>'+
          '<div style="text-align:right;flex-shrink:0">'+
            '<div style="font-family:\'Bebas Neue\',sans-serif;font-size:20px;color:'+(sold?'var(--muted)':'var(--green)')+(sold?';text-decoration:line-through':'')+'">'+(sold?'<span style="font-size:13px;letter-spacing:2px">SOLD</span> ':'')+ps+'</div>'+
            '<div style="display:flex;gap:4px;margin-top:6px;justify-content:flex-end">'+
            (!sold?'<button class="mark-sold-btn" onclick="doMarkSold(\''+l.ID+'\')">✓ Mark Sold</button>':'')+
            '<button class="del-btn" onclick="doDeleteListing(\''+l.ID+'\')">🗑</button>'+
            '</div>'+
          '</div>'+
        '</div>';
      }).join('');
    })
    .withFailureHandler(function(){ document.getElementById('myListingsBody').innerHTML='<p style="color:#e74c3c;padding:20px">Failed to load.</p>'; })
    .getMyListings(currentUser.email);
}

function doMarkSold(id){
  google.script.run
    .withSuccessHandler(function(){ openMyListings(); loadListings(); showToast('✅ Marked as sold!'); })
    .markSold(id);
}
function doDeleteListing(id){
  if(!confirm('Delete this listing?')) return;
  google.script.run
    .withSuccessHandler(function(){ openMyListings(); loadListings(); showToast('🗑 Listing deleted.'); })
    .deleteListing(id);
}

// ═══ MODALS ═══
function openM(id){ document.getElementById(id).classList.add('open'); document.body.style.overflow='hidden'; }
function closeM(id){ document.getElementById(id).classList.remove('open'); document.body.style.overflow=''; }
function showOk(icon,title,msg,id){
  document.getElementById('okIcon').textContent=icon; document.getElementById('okTitle').textContent=title;
  document.getElementById('okMsg').textContent=msg; document.getElementById('okId').textContent=id||'';
  openM('okModal');
}
document.querySelectorAll('.mbg').forEach(function(bg){ bg.addEventListener('click',function(e){ if(e.target===bg)closeM(bg.id); }); });

function escHtml(s){ return (s||'').replace(/&/g,'&amp;').replace(/</g,'&lt;').replace(/>/g,'&gt;').replace(/"/g,'&quot;'); }
var tt;
function showToast(m){ var t=document.getElementById('toast'); t.textContent=m; t.classList.add('show'); clearTimeout(tt); tt=setTimeout(function(){t.classList.remove('show');},2800); }
</script>
</body>
</html>
