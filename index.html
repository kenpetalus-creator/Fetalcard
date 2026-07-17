<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>FetalCard — Fetal Heart Screening Platform</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,500;9..144,600;9..144,700&family=Source+Sans+3:wght@400;500;600;700&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
  :root{
    --purple-950:#1c0a2e;
    --purple-900:#2c0f47;
    --purple-800:#3d1461;
    --purple-700:#551d84;
    --purple-500:#7c3fae;
    --purple-200:#e3d3f5;
    --purple-100:#f1e8fa;
    --white:#ffffff;
    --off-white:#faf8fc;
    --red-600:#c81e3a;
    --red-500:#e02f4c;
    --red-100:#fbe4e8;
    --green-600:#1e7a4c;
    --green-100:#e2f3e9;
    --ink:#1c0a2e;
    --ink-soft:#5a4d6b;
    --line:#e6dcf2;
    --font-display:'Fraunces', serif;
    --font-body:'Source Sans 3', sans-serif;
    --font-mono:'JetBrains Mono', monospace;
  }
  *{box-sizing:border-box;}
  html{scroll-behavior:smooth;}
  body{margin:0; font-family:var(--font-body); color:var(--ink); background:var(--white); -webkit-font-smoothing:antialiased;}
  img,svg{display:block;max-width:100%;}
  a{color:inherit;}
  button{font-family:inherit;}

  .wrap{max-width:1180px;margin:0 auto;padding:0 32px;}
  .eyebrow{font-family:var(--font-mono); font-size:12.5px; letter-spacing:0.14em; text-transform:uppercase; color:var(--red-600); display:flex; align-items:center; gap:10px;}
  .eyebrow::before{content:""; width:22px;height:1px;background:var(--red-600); display:inline-block;}
  .btn{display:inline-flex; align-items:center; justify-content:center; gap:8px; padding:13px 26px; border-radius:3px; font-weight:600; font-size:15px; border:1px solid transparent; cursor:pointer; text-decoration:none; transition:transform .15s ease, box-shadow .15s ease, background .15s ease, color .15s ease;}
  .btn-primary{background:var(--red-600);color:var(--white);}
  .btn-primary:hover{background:var(--red-500); box-shadow:0 6px 20px rgba(200,30,58,.28);}
  .btn-primary:disabled{background:#d9c9e8; color:#fff; cursor:not-allowed; box-shadow:none;}
  .btn-ghost{background:transparent;color:var(--white);border-color:rgba(255,255,255,.4);}
  .btn-ghost:hover{border-color:var(--white); background:rgba(255,255,255,.08);}
  .btn-dark{background:var(--purple-900);color:var(--white);}
  .btn-dark:hover{background:var(--purple-800);}
  .btn-outline{background:transparent;color:var(--purple-900);border-color:var(--purple-700);}
  .btn-outline:hover{background:var(--purple-100);}
  .btn-sm{padding:9px 16px;font-size:13.5px;}
  .btn-xs{padding:6px 12px;font-size:12.5px;}

  /* nav */
  .nav{position:sticky; top:0; z-index:50; background:rgba(28,10,46,.92); backdrop-filter:blur(10px); border-bottom:1px solid rgba(255,255,255,.08);}
  .nav-inner{max-width:1180px;margin:0 auto;padding:0 32px; height:72px; display:flex; align-items:center; justify-content:space-between;}
  .logo{display:flex; align-items:center; gap:10px; font-family:var(--font-display); font-weight:600; font-size:21px; color:var(--white); letter-spacing:-0.01em; text-decoration:none;}
  .logo .pulse{color:var(--red-500);}
  .nav-links{display:flex; align-items:center; gap:34px;}
  .nav-links a{color:rgba(255,255,255,.75); text-decoration:none; font-size:14.5px; font-weight:500; transition:color .15s ease;}
  .nav-links a:hover{color:var(--white);}
  .nav-cta{display:flex; gap:12px; align-items:center;}

  /* hero */
  .hero{background:radial-gradient(ellipse 900px 500px at 85% -10%, rgba(224,47,76,.18), transparent 60%), linear-gradient(180deg, var(--purple-950) 0%, var(--purple-900) 55%, var(--purple-800) 100%); color:var(--white); padding:96px 0 110px; position:relative; overflow:hidden;}
  .hero-grid{display:grid; grid-template-columns:1.1fr .9fr; gap:60px; align-items:center;}
  .hero h1{font-family:var(--font-display); font-size:56px; line-height:1.06; font-weight:600; letter-spacing:-0.01em; margin:22px 0 24px;}
  .hero h1 em{font-style:italic; color:var(--purple-200); font-weight:500;}
  .hero p.lede{font-size:18px; line-height:1.65; color:rgba(255,255,255,.72); max-width:520px; margin:0 0 36px;}
  .hero-actions{display:flex; gap:14px; margin-bottom:44px;}
  .hero-stats{display:flex; gap:36px; flex-wrap:wrap;}
  .hero-stat b{display:block; font-family:var(--font-display); font-size:28px; font-weight:600; color:var(--white);}
  .hero-stat span{font-family:var(--font-mono); font-size:11.5px; letter-spacing:.05em; color:rgba(255,255,255,.55); text-transform:uppercase;}

  .monitor{background:var(--purple-950); border:1px solid rgba(255,255,255,.12); border-radius:6px; padding:24px 24px 20px; box-shadow:0 30px 80px rgba(0,0,0,.45), 0 0 0 1px rgba(255,255,255,.02);}
  .monitor-head{display:flex; justify-content:space-between; align-items:center; margin-bottom:14px;}
  .monitor-head .label{font-family:var(--font-mono); font-size:11px; letter-spacing:.08em; color:rgba(255,255,255,.5); text-transform:uppercase;}
  .monitor-head .bpm{font-family:var(--font-mono); font-size:13px; color:var(--red-500); display:flex; align-items:center; gap:6px;}
  .dot-live{width:7px;height:7px;border-radius:50%;background:var(--red-500); animation:blink 1.1s infinite;}
  @keyframes blink{0%,100%{opacity:1;}50%{opacity:.25;}}
  .monitor svg{width:100%; height:150px;}
  .monitor-readout{display:flex; justify-content:space-between; margin-top:16px; font-family:var(--font-mono); font-size:12px; color:rgba(255,255,255,.55); border-top:1px solid rgba(255,255,255,.08); padding-top:14px;}
  .monitor-readout b{color:var(--white); font-weight:500;}
  .heartline{fill:none; stroke:var(--red-500); stroke-width:2; stroke-linecap:round; stroke-linejoin:round; filter:drop-shadow(0 0 6px rgba(224,47,76,.5));}
  .heartline-bg{fill:none; stroke:rgba(255,255,255,.08); stroke-width:1;}
  @media (prefers-reduced-motion: no-preference){
    .heartline{stroke-dasharray:1400; stroke-dashoffset:1400; animation:draw 3.2s ease-in-out infinite;}
    @keyframes draw{0%{stroke-dashoffset:1400;}55%{stroke-dashoffset:0;}100%{stroke-dashoffset:-1400;}}
  }

  section{padding:100px 0;}
  .section-head{max-width:640px; margin:0 0 56px;}
  .section-head h2{font-family:var(--font-display); font-size:38px; font-weight:600; letter-spacing:-0.01em; color:var(--ink); margin:16px 0 0; line-height:1.15;}
  .section-head p{font-size:16.5px; color:var(--ink-soft); line-height:1.6; margin-top:14px;}
  .bg-soft{background:var(--off-white);}
  .bg-dark{background:var(--purple-950); color:var(--white);}
  .bg-dark .section-head p{color:rgba(255,255,255,.65);}

  .about-grid{display:grid; grid-template-columns:.9fr 1.1fr; gap:70px; align-items:start;}
  .about-copy p{font-size:16px; line-height:1.75; color:var(--ink-soft); margin:0 0 18px;}
  .about-copy strong{color:var(--ink);}
  .about-figures{display:grid; grid-template-columns:1fr 1fr; gap:1px; background:var(--line); border:1px solid var(--line); border-radius:4px; overflow:hidden;}
  .about-figure{background:var(--white); padding:28px 26px;}
  .about-figure b{font-family:var(--font-display); font-size:32px; font-weight:600; color:var(--purple-800); display:block;}
  .about-figure span{font-size:13.5px; color:var(--ink-soft); line-height:1.5; display:block; margin-top:8px;}

  .flow{display:flex; flex-direction:column; gap:0;}
  .flow-step{display:grid; grid-template-columns:88px 1fr; gap:32px; padding:36px 0; border-top:1px solid var(--line); position:relative;}
  .flow-step:last-child{border-bottom:1px solid var(--line);}
  .flow-num{font-family:var(--font-mono); font-size:13px; color:var(--red-600); padding-top:4px;}
  .flow-num .stage{display:block; font-size:10.5px; letter-spacing:.08em; text-transform:uppercase; color:var(--ink-soft); margin-top:6px;}
  .flow-body h3{font-family:var(--font-display); font-size:21px; font-weight:600; margin:0 0 8px; color:var(--ink);}
  .flow-body p{font-size:15px; line-height:1.65; color:var(--ink-soft); margin:0; max-width:640px;}

  .feat-grid{display:grid; grid-template-columns:repeat(3, 1fr); gap:1px; background:rgba(255,255,255,.1); border:1px solid rgba(255,255,255,.1); border-radius:6px; overflow:hidden;}
  .feat-card{background:var(--purple-900); padding:34px 30px;}
  .feat-icon{width:36px; height:36px; margin-bottom:20px; color:var(--red-500);}
  .feat-card h3{font-family:var(--font-display); font-size:19px; font-weight:600; margin:0 0 10px; color:var(--white);}
  .feat-card p{font-size:14px; line-height:1.6; color:rgba(255,255,255,.62); margin:0;}
  .feat-role{display:inline-block; margin-top:16px; font-family:var(--font-mono); font-size:10.5px; letter-spacing:.06em; text-transform:uppercase; color:var(--purple-200); background:rgba(255,255,255,.06); padding:4px 9px; border-radius:2px;}

  .team-grid{display:grid; grid-template-columns:repeat(4, 1fr); gap:30px;}
  .team-photo{width:100%; aspect-ratio:1/1; border-radius:4px; background:linear-gradient(155deg, var(--purple-800), var(--purple-950)); display:flex; align-items:center; justify-content:center; margin-bottom:16px; font-family:var(--font-display); font-size:34px; color:rgba(255,255,255,.85); position:relative; overflow:hidden;}
  .team-photo::after{content:""; position:absolute; inset:0; background:radial-gradient(circle at 30% 20%, rgba(224,47,76,.35), transparent 55%);}
  .team-card h4{font-size:16px; font-weight:600; margin:0 0 3px; color:var(--ink);}
  .team-card span{font-size:13px; color:var(--ink-soft);}

  .contact-grid{display:grid; grid-template-columns:1fr 1fr; gap:70px; align-items:flex-start;}
  .form-field{margin-bottom:20px;}
  .form-field label{display:block; font-size:13px; font-weight:600; color:var(--ink); margin-bottom:7px;}
  .form-field input, .form-field select, .form-field textarea{width:100%; padding:12px 14px; border:1px solid var(--line); border-radius:3px; font-family:var(--font-body); font-size:14.5px; color:var(--ink); background:var(--white);}
  .form-field input:focus, .form-field select:focus, .form-field textarea:focus{outline:2px solid var(--purple-500); outline-offset:1px; border-color:var(--purple-500);}
  .form-field textarea{resize:vertical; min-height:80px;}
  .form-field .hint{font-size:12px; color:var(--ink-soft); margin-top:5px;}
  .form-row{display:grid; grid-template-columns:1fr 1fr; gap:16px;}
  .contact-info{background:var(--purple-950); color:var(--white); border-radius:6px; padding:40px;}
  .contact-info h3{font-family:var(--font-display); font-size:22px; margin:0 0 14px;}
  .contact-info p{font-size:14.5px; line-height:1.7; color:rgba(255,255,255,.65); margin:0 0 24px;}
  .contact-line{display:flex; gap:12px; align-items:flex-start; margin-bottom:16px; font-size:14px;}
  .contact-line b{color:var(--white); display:block; font-size:12px; letter-spacing:.05em; text-transform:uppercase; font-family:var(--font-mono); margin-bottom:2px; color:var(--purple-200);}

  footer{background:var(--purple-950); border-top:1px solid rgba(255,255,255,.08); padding:44px 0;}
  .footer-inner{display:flex; justify-content:space-between; align-items:center; color:rgba(255,255,255,.5); font-size:13.5px;}
  .footer-inner a{color:rgba(255,255,255,.5); text-decoration:none; margin-left:24px;}
  .footer-inner a:hover{color:var(--white);}

  /* app shell */
  #app-view{display:none; min-height:100vh; background:var(--off-white);}
  #app-view.active{display:block;}
  #marketing-view.hidden{display:none;}

  .app-topbar{background:var(--purple-950); color:var(--white); height:64px; display:flex; align-items:center; justify-content:space-between; padding:0 28px; position:sticky; top:0; z-index:40;}
  .app-topbar .logo{font-size:18px;}
  .app-user{display:flex; align-items:center; gap:16px; font-size:13.5px;}
  .app-user .role-tag{font-family:var(--font-mono); font-size:10.5px; letter-spacing:.06em; text-transform:uppercase; background:rgba(224,47,76,.18); color:var(--red-500); padding:4px 10px; border-radius:2px;}
  .app-user button{background:transparent; border:1px solid rgba(255,255,255,.25); color:rgba(255,255,255,.8); padding:7px 14px; border-radius:3px; font-size:13px; cursor:pointer;}
  .app-user button:hover{border-color:var(--white); color:var(--white);}

  .notif-wrap{position:relative;}
  .notif-bell{background:transparent;border:1px solid rgba(255,255,255,.25);color:rgba(255,255,255,.85);width:36px;height:36px;border-radius:3px;cursor:pointer;display:flex;align-items:center;justify-content:center;position:relative;}
  .notif-bell:hover{border-color:#fff;color:#fff;}
  .notif-bell svg{width:17px;height:17px;}
  .notif-badge{position:absolute;top:-5px;right:-5px;background:var(--red-600);color:#fff;font-size:10px;font-family:var(--font-mono);width:16px;height:16px;border-radius:50%;display:flex;align-items:center;justify-content:center;}
  .notif-dropdown{position:absolute;top:46px;right:0;width:320px;background:#fff;border-radius:6px;box-shadow:0 20px 50px rgba(0,0,0,.35);display:none;z-index:60;overflow:hidden;}
  .notif-dropdown.show{display:block;}
  .notif-head{padding:13px 16px;font-weight:600;font-size:13px;border-bottom:1px solid var(--line);color:var(--ink);background:var(--off-white);}
  .notif-list{max-height:320px;overflow-y:auto;}
  .notif-item{padding:13px 16px;border-bottom:1px solid var(--line);font-size:13px;color:var(--ink);}
  .notif-item:last-child{border-bottom:none;}
  .notif-item .notif-time{display:block;font-size:11px;color:var(--ink-soft);margin-top:4px;font-family:var(--font-mono);}

  .login-shell{min-height:100vh; display:flex; align-items:center; justify-content:center; background:radial-gradient(ellipse 700px 400px at 80% 0%, rgba(224,47,76,.15), transparent 60%), linear-gradient(180deg, var(--purple-950), var(--purple-900)); padding:40px;}
  .login-card{background:var(--white); border-radius:8px; width:100%; max-width:430px; padding:44px 40px; box-shadow:0 40px 90px rgba(0,0,0,.35);}
  .login-card .logo{color:var(--ink); justify-content:center; margin-bottom:8px;}
  .login-card .logo .pulse{color:var(--red-600);}
  .login-sub{text-align:center; font-size:14px; color:var(--ink-soft); margin-bottom:30px;}
  .role-select{display:grid; grid-template-columns:repeat(3,1fr); gap:10px; margin-bottom:24px;}
  .role-opt{border:1.5px solid var(--line); border-radius:4px; padding:14px 8px; text-align:center; cursor:pointer; font-size:12.5px; font-weight:600; color:var(--ink-soft); transition:all .15s ease;}
  .role-opt.selected{border-color:var(--purple-700); background:var(--purple-100); color:var(--purple-800);}
  .login-card .btn-primary{width:100%; margin-top:6px;}
  .login-links{display:flex; justify-content:space-between; margin-top:4px; margin-bottom:6px;}
  .login-links a{font-size:12.5px; color:var(--purple-700); text-decoration:none; cursor:pointer;}
  .login-links a:hover{text-decoration:underline;}
  .login-2fa{display:flex; align-items:center; gap:8px; opacity:.55; margin-top:8px;}
  .login-2fa input{width:auto;}
  .login-2fa label{margin:0; font-size:12.5px; font-weight:500;}
  .login-back{display:block; text-align:center; margin-top:20px; font-size:13px; color:var(--ink-soft); text-decoration:none;}
  .login-back:hover{color:var(--purple-700);}
  .login-hint{margin-top:18px; padding:12px 14px; background:var(--purple-100); border-radius:4px; font-size:12.5px; color:var(--purple-800); line-height:1.5;}

  .app-body{padding:32px 28px 60px; max-width:1320px; margin:0 auto;}
  .app-header{display:flex; justify-content:space-between; align-items:flex-end; margin-bottom:24px; flex-wrap:wrap; gap:16px;}
  .app-header h1{font-family:var(--font-display); font-size:28px; font-weight:600; margin:0; color:var(--ink);}
  .app-header p{font-size:13.5px; color:var(--ink-soft); margin:4px 0 0;}
  .header-actions{display:flex; gap:10px;}

  .app-tabs{display:flex; gap:2px; border-bottom:1px solid var(--line); margin-bottom:28px; overflow-x:auto;}
  .app-tab{padding:12px 18px; font-size:14px; font-weight:600; color:var(--ink-soft); cursor:pointer; border-bottom:2px solid transparent; margin-bottom:-1px; white-space:nowrap;}
  .app-tab.active{color:var(--purple-800); border-bottom-color:var(--red-600);}
  .app-tab:hover{color:var(--purple-700);}
  .tab-panel{display:none;}
  .tab-panel.active{display:block;}

  .stat-row{display:grid; grid-template-columns:repeat(4,1fr); gap:16px; margin-bottom:32px;}
  .stat-card{background:var(--white); border:1px solid var(--line); border-radius:6px; padding:20px 22px;}
  .stat-card .stat-label{font-family:var(--font-mono); font-size:10.5px; letter-spacing:.05em; text-transform:uppercase; color:var(--ink-soft);}
  .stat-card .stat-value{font-family:var(--font-display); font-size:30px; font-weight:600; color:var(--purple-800); margin-top:8px;}
  .stat-card .stat-value.red{color:var(--red-600);}
  .stat-card .stat-delta{font-size:12px; color:var(--ink-soft); margin-top:4px;}

  .panel{background:var(--white); border:1px solid var(--line); border-radius:6px; margin-bottom:24px; overflow:hidden;}
  .panel-head{display:flex; justify-content:space-between; align-items:center; padding:18px 22px; border-bottom:1px solid var(--line); gap:12px; flex-wrap:wrap;}
  .panel-head h2{font-size:16px; font-weight:600; margin:0; color:var(--ink);}
  .panel-body{padding:6px 0;}
  .panel-body.padded{padding:22px;}
  .search-box{position:relative; min-width:220px;}
  .search-box input{width:100%; padding:9px 12px 9px 32px; border:1px solid var(--line); border-radius:3px; font-size:13.5px;}
  .search-box svg{position:absolute; left:10px; top:50%; transform:translateY(-50%); width:14px; height:14px; color:var(--ink-soft);}

  table{width:100%; border-collapse:collapse;}
  thead th{text-align:left; font-family:var(--font-mono); font-size:10.5px; letter-spacing:.05em; text-transform:uppercase; color:var(--ink-soft); padding:10px 22px; border-bottom:1px solid var(--line); font-weight:500;}
  tbody td{padding:14px 22px; font-size:14px; border-bottom:1px solid var(--line); color:var(--ink);}
  tbody tr:last-child td{border-bottom:none;}
  tbody tr:hover{background:var(--off-white);}
  tbody tr.archived{opacity:.5;}
  .pill{display:inline-block; padding:3px 10px; border-radius:20px; font-size:11.5px; font-weight:600;}
  .pill-red{background:var(--red-100); color:var(--red-600);}
  .pill-purple{background:var(--purple-100); color:var(--purple-800);}
  .pill-gray{background:#f0eef2; color:var(--ink-soft);}
  .pill-green{background:var(--green-100); color:var(--green-600);}
  .row-actions{display:flex; gap:8px;}
  .row-actions button{background:none; border:1px solid var(--line); color:var(--ink-soft); font-size:12px; padding:5px 10px; border-radius:3px; cursor:pointer;}
  .row-actions button:hover{border-color:var(--purple-500); color:var(--purple-700);}

  .two-col{display:grid; grid-template-columns:1.4fr 1fr; gap:24px; align-items:start;}
  .upload-box{border:1.5px dashed var(--line); border-radius:6px; padding:30px 20px; text-align:center; color:var(--ink-soft); font-size:13.5px; background:var(--off-white); cursor:pointer;}
  .upload-box svg{width:28px; height:28px; margin:0 auto 10px; color:var(--purple-500);}
  .upload-box .accepted{display:block; margin-top:6px; font-size:11.5px; color:var(--ink-soft);}
  .file-chip-row{display:flex; gap:8px; flex-wrap:wrap; margin-top:12px;}
  .file-chip{background:var(--purple-100); color:var(--purple-800); font-size:12px; padding:5px 10px; border-radius:3px; display:flex; align-items:center; gap:6px;}
  .file-chip button{background:none; border:none; color:var(--purple-700); cursor:pointer; font-size:13px; padding:0; line-height:1;}

  .activity-list{padding:6px 0;}
  .activity-item{display:flex; gap:12px; padding:13px 22px; border-bottom:1px solid var(--line); font-size:13.5px;}
  .activity-item:last-child{border-bottom:none;}
  .activity-dot{width:8px;height:8px;border-radius:50%; margin-top:6px; flex-shrink:0;}
  .activity-item .activity-time{display:block; font-size:11.5px; color:var(--ink-soft); margin-top:2px; font-family:var(--font-mono);}

  .cal-toolbar{display:flex; justify-content:space-between; align-items:center; margin-bottom:16px;}
  .cal-toolbar h3{font-family:var(--font-display); font-size:19px; font-weight:600; margin:0; color:var(--ink);}
  .cal-grid{display:grid; grid-template-columns:repeat(7,1fr); gap:1px; background:var(--line); border:1px solid var(--line); border-radius:4px; overflow:hidden;}
  .cal-day-head{background:var(--off-white); padding:9px; font-family:var(--font-mono); font-size:10px; text-transform:uppercase; color:var(--ink-soft); text-align:center; letter-spacing:.05em;}
  .cal-cell{background:#fff; min-height:82px; padding:8px; font-size:12px; color:var(--ink-soft);}
  .cal-cell.empty{background:var(--off-white);}
  .cal-cell .daynum{font-weight:600; color:var(--ink); font-size:13px;}
  .cal-cell.has-appt{background:var(--purple-100);}
  .cal-appt-tag{margin-top:5px; font-size:10.5px; background:var(--red-600); color:#fff; padding:2px 6px; border-radius:2px; display:block; overflow:hidden; text-overflow:ellipsis; white-space:nowrap;}

  .echo-section{border:1px solid var(--line); border-radius:6px; margin-bottom:16px; overflow:hidden;}
  .echo-section-head{background:var(--off-white); padding:12px 18px; font-weight:600; font-size:14px; color:var(--purple-800); border-bottom:1px solid var(--line);}
  .echo-section-body{padding:18px;}
  .measure-table td, .measure-table th{padding:8px 10px;}
  .measure-table input{width:100%; padding:6px 8px; border:1px solid var(--line); border-radius:3px; font-size:13px;}

  .empty-state{padding:50px 20px; text-align:center; color:var(--ink-soft); font-size:14px;}
  .empty-state svg{width:34px; height:34px; margin:0 auto 12px; color:var(--line);}

  .toast{position:fixed; bottom:28px; right:28px; background:var(--purple-950); color:var(--white); padding:14px 20px; border-radius:6px; font-size:13.5px; box-shadow:0 20px 50px rgba(0,0,0,.3); display:flex; align-items:center; gap:10px; z-index:100; transform:translateY(20px); opacity:0; pointer-events:none; transition:all .25s ease;}
  .toast.show{transform:translateY(0); opacity:1;}
  .toast .dot{width:7px;height:7px;border-radius:50%;background:var(--red-500);}

  .modal-overlay{position:fixed; inset:0; background:rgba(28,10,46,.55); display:none; align-items:center; justify-content:center; z-index:90; padding:20px;}
  .modal-overlay.show{display:flex;}
  .modal{background:var(--white); border-radius:8px; max-width:560px; width:100%; padding:32px; max-height:88vh; overflow-y:auto;}
  .modal.modal-lg{max-width:820px;}
  .modal h3{font-family:var(--font-display); font-size:20px; margin:0 0 6px; color:var(--ink);}
  .modal .modal-sub{font-size:13px; color:var(--ink-soft); margin:0 0 20px;}
  .modal-close-row{display:flex; justify-content:flex-end; gap:10px; margin-top:26px; flex-wrap:wrap;}

  ::-webkit-scrollbar{width:10px; height:10px;}
  ::-webkit-scrollbar-track{background:transparent;}
  ::-webkit-scrollbar-thumb{background:var(--line); border-radius:6px;}

  a:focus-visible, button:focus-visible, input:focus-visible, select:focus-visible, textarea:focus-visible, .role-opt:focus-visible, .app-tab:focus-visible{outline:2px solid var(--red-600); outline-offset:2px;}

  @media (max-width: 900px){
    .hero-grid{grid-template-columns:1fr;}
    .hero h1{font-size:38px;}
    .about-grid, .contact-grid, .two-col, .form-row{grid-template-columns:1fr;}
    .feat-grid{grid-template-columns:1fr;}
    .team-grid{grid-template-columns:repeat(2,1fr);}
    .nav-links{display:none;}
    .stat-row{grid-template-columns:1fr 1fr;}
    .role-select{grid-template-columns:1fr;}
    .cal-cell{min-height:56px; font-size:10.5px;}
  }
</style>
</head>
<body>

<!-- ============ MARKETING SITE ============ -->
<div id="marketing-view">

  <nav class="nav">
    <div class="nav-inner">
      <a href="#top" class="logo">Fetal<span class="pulse">Card</span></a>
      <div class="nav-links">
        <a href="#about">About</a>
        <a href="#how">How it works</a>
        <a href="#features">Features</a>
        <a href="#team">Team</a>
        <a href="#contact">Contact</a>
      </div>
      <div class="nav-cta">
        <button class="btn btn-ghost btn-sm" onclick="showLogin()">Log in</button>
        <a href="#contact" class="btn btn-primary btn-sm">Request demo</a>
      </div>
    </div>
  </nav>

  <header class="hero" id="top">
    <div class="wrap hero-grid">
      <div>
        <div class="eyebrow">Fetal Cardiac Care Platform</div>
        <h1>Every fetal heartbeat, <em>read with certainty.</em></h1>
        <p class="lede">FetalCard brings screening, diagnosis, and reporting for fetal echocardiography into one platform — built with cardiologists, for the hospitals and families who depend on an early, accurate read.</p>
        <div class="hero-actions">
          <a href="#contact" class="btn btn-primary">Request a demo</a>
          <button class="btn btn-ghost" onclick="showLogin()">Log in to platform</button>
        </div>
        <div class="hero-stats">
          <div class="hero-stat"><b>60+</b><span>Hospitals onboarded</span></div>
          <div class="hero-stat"><b>18 min</b><span>Avg. report turnaround</span></div>
          <div class="hero-stat"><b>99.2%</b><span>Diagnostic concordance</span></div>
        </div>
      </div>

      <div class="monitor" aria-hidden="true">
        <div class="monitor-head">
          <span class="label">Fetal HR Trace — Live</span>
          <span class="bpm"><span class="dot-live"></span>142 bpm</span>
        </div>
        <svg viewBox="0 0 500 150" preserveAspectRatio="none">
          <line x1="0" y1="30" x2="500" y2="30" class="heartline-bg"/>
          <line x1="0" y1="75" x2="500" y2="75" class="heartline-bg"/>
          <line x1="0" y1="120" x2="500" y2="120" class="heartline-bg"/>
          <path class="heartline" d="M0,75 L40,75 L55,75 L65,30 L75,120 L85,50 L95,75 L140,75 L160,75 L175,30 L185,120 L195,50 L205,75 L250,75 L270,75 L285,30 L295,120 L305,50 L315,75 L360,75 L380,75 L395,30 L405,120 L415,50 L425,75 L470,75 L500,75"/>
        </svg>
        <div class="monitor-readout">
          <span>GA <b>26w 3d</b></span>
          <span>4CH View <b>Normal axis</b></span>
          <span>Study <b>#FC-40281</b></span>
        </div>
      </div>
    </div>
  </header>

  <section id="about">
    <div class="wrap about-grid">
      <div>
        <div class="eyebrow">About FetalCard</div>
        <h2 style="font-family:var(--font-display); font-size:34px; font-weight:600; margin:16px 0 0; line-height:1.2;">One record, from first scan to final report.</h2>
      </div>
      <div class="about-copy">
        <p>Congenital heart defects are the most common birth anomaly, yet fetal echo findings are often scattered across ultrasound machines, referral letters, and disconnected PACS systems. <strong>FetalCard unifies that workflow</strong> — image capture, structured measurement, diagnosis, and the final report — inside a single secure record per pregnancy.</p>
        <p>Built directly with pediatric and fetal cardiologists, the platform standardizes reporting templates across a hospital network, flags studies that need a second read, and gets a clear, structured report in front of the referring physician and family faster.</p>
        <div class="about-figures">
          <div class="about-figure"><b>40+</b><span>Structured fetal echo measurement fields per study</span></div>
          <div class="about-figure"><b>3</b><span>Role-based workspaces: admin, doctor, hospital manager</span></div>
          <div class="about-figure"><b>256-bit</b><span>Encryption for every stored image and report</span></div>
          <div class="about-figure"><b>24/7</b><span>Access to reports for referring clinicians</span></div>
        </div>
      </div>
    </div>
  </section>

  <section id="how" class="bg-soft">
    <div class="wrap">
      <div class="section-head">
        <div class="eyebrow">How it works</div>
        <h2>From probe to PDF, in four steps.</h2>
        <p>A fetal echo study moves through a fixed clinical sequence — FetalCard mirrors that sequence exactly, so nothing is re-typed or re-explained between stages.</p>
      </div>
      <div class="flow">
        <div class="flow-step">
          <div class="flow-num">01<span class="stage">Intake</span></div>
          <div class="flow-body"><h3>Patient & referral record created</h3><p>A doctor opens a new patient record with gestational age, referral reason, and maternal history — pulled once, used throughout the study.</p></div>
        </div>
        <div class="flow-step">
          <div class="flow-num">02<span class="stage">Screening</span></div>
          <div class="flow-body"><h3>Images and clips uploaded</h3><p>Cardiac views from the ultrasound session are uploaded directly to the record, organized by view — four-chamber, outflow tracts, three-vessel — for structured review.</p></div>
        </div>
        <div class="flow-step">
          <div class="flow-num">03<span class="stage">Diagnosis</span></div>
          <div class="flow-body"><h3>Structured findings & measurements</h3><p>The doctor documents findings against a standard template, flags any suspected anomaly, and refers the case for a second opinion if needed.</p></div>
        </div>
        <div class="flow-step">
          <div class="flow-num">04<span class="stage">Reporting</span></div>
          <div class="flow-body"><h3>Report generated & shared</h3><p>A structured PDF report is generated automatically and made available to the hospital, the referring physician, and the patient record — ready to download or print.</p></div>
        </div>
      </div>
    </div>
  </section>

  <section id="features" class="bg-dark">
    <div class="wrap">
      <div class="section-head">
        <div class="eyebrow">Features</div>
        <h2 style="color:var(--white);">A workspace for every role in the loop.</h2>
        <p>Admins, doctors, and hospital managers each get exactly what their job requires — nothing bolted on, nothing missing.</p>
      </div>
      <div class="feat-grid">
        <div class="feat-card"><svg class="feat-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6"><path d="M3 21h18M5 21V7l7-4 7 4v14M9 21v-6h6v6M9 11h.01M15 11h.01M9 15h.01M15 15h.01"/></svg><h3>Hospital & user management</h3><p>Onboard hospitals, manage clinician access, and configure permissions across a growing network from one console.</p><span class="feat-role">Admin</span></div>
        <div class="feat-card"><svg class="feat-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6"><path d="M9 3h6v4H9zM9 7H7a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2V9a2 2 0 00-2-2h-2M9 12h6M9 16h4"/></svg><h3>Configurable report templates</h3><p>Standardize the structured fields, terminology, and layout every doctor in the network reports against.</p><span class="feat-role">Admin</span></div>
        <div class="feat-card"><svg class="feat-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6"><path d="M3 3v18h18M7 15l4-6 3 4 4-7"/></svg><h3>Network-wide analytics</h3><p>Track case volumes, turnaround time, and flagged-case rates across every hospital on the platform.</p><span class="feat-role">Admin</span></div>
        <div class="feat-card"><svg class="feat-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6"><path d="M12 4a4 4 0 100 8 4 4 0 000-8zM6 20c0-3.3 2.7-6 6-6s6 2.7 6 6"/></svg><h3>Patient records & echo reports</h3><p>Create, edit, search, and archive a pregnancy's full fetal cardiac record from first scan through delivery.</p><span class="feat-role">Doctor</span></div>
        <div class="feat-card"><svg class="feat-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6"><path d="M4 16l4-4 4 4 4-8 4 4M4 4h16v16H4z"/></svg><h3>Appointments & echo reporting</h3><p>Schedule follow-ups on a calendar, then complete a full structured fetal echo report with image upload and PDF export.</p><span class="feat-role">Doctor</span></div>
        <div class="feat-card"><svg class="feat-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6"><path d="M17 8l4 4-4 4M3 12h18M7 8l-4 4 4 4"/></svg><h3>Referral module</h3><p>Send a flagged case to a specialist with a referral note and attached report, and track its status through to completion.</p><span class="feat-role">Doctor</span></div>
        <div class="feat-card"><svg class="feat-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6"><path d="M17 20h5v-2a4 4 0 00-3-3.87M9 20H4v-2a4 4 0 013-3.87M9 7a4 4 0 118 0 4 4 0 01-8 0z"/></svg><h3>Doctor roster management</h3><p>Add and manage the doctors practicing at your hospital, and see who's active on which cases.</p><span class="feat-role">Hospital Manager</span></div>
        <div class="feat-card"><svg class="feat-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6"><path d="M9 12l2 2 4-4M12 3l8 4v5c0 5-3.4 8.4-8 10-4.6-1.6-8-5-8-10V7l8-4z"/></svg><h3>Hospital case oversight</h3><p>View every case moving through your hospital, its current status, and which doctor owns it.</p><span class="feat-role">Hospital Manager</span></div>
        <div class="feat-card"><svg class="feat-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6"><path d="M3 10h18M7 15h1m4 0h5M5 6h14a2 2 0 012 2v9a2 2 0 01-2 2H5a2 2 0 01-2-2V8a2 2 0 012-2z"/></svg><h3>Billing overview</h3><p>Keep a clear view of subscription status and per-case billing for your hospital's account.</p><span class="feat-role">Hospital Manager</span></div>
      </div>
    </div>
  </section>

  <section id="team">
    <div class="wrap">
      <div class="section-head">
        <div class="eyebrow">Team</div>
        <h2>Built by clinicians and engineers.</h2>
        <p>FetalCard is led by a small team spanning fetal cardiology, obstetric imaging, and health software.</p>
      </div>
      <div class="team-grid">
        <div class="team-card"><div class="team-photo">AK</div><h4>Dr. Anjali Kapoor</h4><span>Co-founder & Chief Medical Officer, Pediatric Cardiology</span></div>
        <div class="team-card"><div class="team-photo">RS</div><h4>Rohan Sethi</h4><span>Co-founder & CEO</span></div>
        <div class="team-card"><div class="team-photo">MV</div><h4>Dr. Meera Varma</h4><span>Clinical Lead, Fetal Medicine</span></div>
        <div class="team-card"><div class="team-photo">TN</div><h4>Tarun Nair</h4><span>Head of Engineering</span></div>
      </div>
    </div>
  </section>

  <section id="contact" class="bg-soft">
    <div class="wrap contact-grid">
      <div>
        <div class="eyebrow">Get in touch</div>
        <h2 style="font-family:var(--font-display); font-size:32px; font-weight:600; margin:16px 0 26px;">Request a demo</h2>
        <form id="demo-form" onsubmit="handleDemoSubmit(event)">
          <div class="form-field"><label for="f-name">Full name</label><input id="f-name" type="text" required placeholder="Dr. Jane Smith"></div>
          <div class="form-field"><label for="f-email">Work email</label><input id="f-email" type="email" required placeholder="jane@hospital.org"></div>
          <div class="form-field"><label for="f-org">Hospital / organization</label><input id="f-org" type="text" required placeholder="St. Mary's Hospital"></div>
          <div class="form-field"><label for="f-role">I am a</label><select id="f-role"><option>Doctor / Cardiologist</option><option>Hospital Administrator</option><option>Hospital Manager</option><option>Other</option></select></div>
          <div class="form-field"><label for="f-msg">What would you like to see in the demo?</label><textarea id="f-msg" placeholder="Tell us about your hospital's fetal cardiology workflow..."></textarea></div>
          <button type="submit" class="btn btn-primary">Send request</button>
        </form>
      </div>
      <div class="contact-info">
        <h3>Talk to the team</h3>
        <p>We typically respond within one business day. For existing hospital partners, reach your account manager directly.</p>
        <div class="contact-line"><div><b>Email</b>hello@fetalcard.com</div></div>
        <div class="contact-line"><div><b>Support</b>support@fetalcard.com</div></div>
        <div class="contact-line"><div><b>Partnerships</b>partners@fetalcard.com</div></div>
      </div>
    </div>
  </section>

  <footer>
    <div class="wrap footer-inner">
      <span>© 2026 FetalCard. All rights reserved.</span>
      <div><a href="#" onclick="return false;">Privacy</a><a href="#" onclick="return false;">Terms</a><a href="#" onclick="return false;">Security</a></div>
    </div>
  </footer>
</div>

<!-- ============ LOGIN VIEW ============ -->
<div id="login-view" style="display:none;">
  <div class="login-shell">
    <div class="login-card">
      <a href="#top" class="logo" onclick="showMarketing(); return true;">Fetal<span class="pulse">Card</span></a>
      <p class="login-sub">Log in to your workspace</p>

      <div class="role-select" id="role-select">
        <div class="role-opt" data-role="admin" tabindex="0" onclick="selectRole('admin')" onkeydown="if(event.key==='Enter')selectRole('admin')">Admin</div>
        <div class="role-opt" data-role="doctor" tabindex="0" onclick="selectRole('doctor')" onkeydown="if(event.key==='Enter')selectRole('doctor')">Doctor</div>
        <div class="role-opt" data-role="manager" tabindex="0" onclick="selectRole('manager')" onkeydown="if(event.key==='Enter')selectRole('manager')">Hospital Manager</div>
      </div>

      <div class="form-field"><label for="login-email">Email</label><input id="login-email" type="email" placeholder="you@hospital.org"></div>
      <div class="form-field">
        <label for="login-pass">Password</label>
        <input id="login-pass" type="password" placeholder="••••••••">
      </div>
      <div class="login-links">
        <span></span>
        <a onclick="openModal('modal-reset')">Forgot password?</a>
      </div>
      <div class="login-2fa"><input type="checkbox" disabled id="tfa-cb"><label for="tfa-cb">Enable two-factor authentication (coming soon)</label></div>
      <button class="btn btn-primary" style="margin-top:18px;" onclick="doLogin()">Log in</button>

      <div class="login-hint">This is a demo environment. Pick any role above and click Log in — no real credentials are needed.</div>
      <a href="#top" class="login-back" onclick="showMarketing(); return true;">← Back to fetalcard.com</a>
    </div>
  </div>
</div>

<!-- ============ APP VIEW (DASHBOARDS) ============ -->
<div id="app-view">
  <div class="app-topbar">
    <a href="#" class="logo" onclick="return false;" style="cursor:default;">Fetal<span class="pulse">Card</span></a>
    <div class="app-user">
      <div class="notif-wrap">
        <button class="notif-bell" onclick="toggleNotifs()" aria-label="Notifications">
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8"><path d="M18 8a6 6 0 10-12 0c0 7-3 9-3 9h18s-3-2-3-9M13.7 21a2 2 0 01-3.4 0"/></svg>
          <span class="notif-badge" id="notif-badge">3</span>
        </button>
        <div class="notif-dropdown" id="notif-dropdown">
          <div class="notif-head">Notifications</div>
          <div class="notif-list" id="notif-list"></div>
        </div>
      </div>
      <span class="role-tag" id="topbar-role">DOCTOR</span>
      <span id="topbar-name">Dr. Jane Smith</span>
      <button onclick="logout()">Log out</button>
    </div>
  </div>

  <!-- ADMIN DASHBOARD -->
  <div class="app-body" id="dash-admin" style="display:none;">
    <div class="app-header">
      <div><h1>Admin overview</h1><p>Network-wide view across all onboarded hospitals.</p></div>
      <button class="btn btn-dark btn-sm" onclick="openModal('modal-hospital')">+ Add hospital</button>
    </div>

    <div class="stat-row">
      <div class="stat-card"><div class="stat-label">Hospitals</div><div class="stat-value">62</div><div class="stat-delta">+3 this month</div></div>
      <div class="stat-card"><div class="stat-label">Active doctors</div><div class="stat-value">214</div><div class="stat-delta">+11 this month</div></div>
      <div class="stat-card"><div class="stat-label">Reports this month</div><div class="stat-value">1,486</div><div class="stat-delta">+8.4% vs last month</div></div>
      <div class="stat-card"><div class="stat-label">Flagged cases</div><div class="stat-value red">37</div><div class="stat-delta">2.5% of total</div></div>
    </div>

    <div class="panel">
      <div class="panel-head"><h2>Hospitals</h2><button class="btn btn-outline btn-sm" onclick="openModal('modal-hospital')">+ Add hospital</button></div>
      <div class="panel-body">
        <table><thead><tr><th>Hospital</th><th>Location</th><th>Doctors</th><th>Plan</th><th>Status</th><th></th></tr></thead><tbody id="admin-hospitals-table"></tbody></table>
      </div>
    </div>

    <div class="two-col">
      <div class="panel">
        <div class="panel-head"><h2>Report templates</h2><button class="btn btn-outline btn-sm" onclick="toast('Template editor is a demo placeholder')">Configure</button></div>
        <div class="panel-body">
          <table><thead><tr><th>Template</th><th>Fields</th><th>Used by</th><th>Updated</th></tr></thead>
            <tbody>
              <tr><td>Standard 4-Chamber Echo</td><td>42</td><td>58 hospitals</td><td>Jun 12, 2026</td></tr>
              <tr><td>Extended Anomaly Report</td><td>67</td><td>21 hospitals</td><td>May 30, 2026</td></tr>
              <tr><td>Follow-up Scan Summary</td><td>18</td><td>62 hospitals</td><td>Apr 22, 2026</td></tr>
            </tbody></table>
        </div>
      </div>
      <div class="panel">
        <div class="panel-head"><h2>Subscriptions</h2></div>
        <div class="panel-body padded">
          <table><thead><tr><th>Plan</th><th>Hospitals</th></tr></thead>
            <tbody><tr><td>Enterprise</td><td>14</td></tr><tr><td>Growth</td><td>29</td></tr><tr><td>Starter</td><td>19</td></tr></tbody></table>
        </div>
      </div>
    </div>
  </div>

  <!-- DOCTOR DASHBOARD -->
  <div class="app-body" id="dash-doctor" style="display:none;">
    <div class="app-header">
      <div><h1>Doctor workspace</h1><p>St. Mary's Hospital — Fetal Cardiology</p></div>
    </div>

    <div class="app-tabs">
      <div class="app-tab active" data-tab="overview" onclick="switchDoctorTab('overview')">Overview</div>
      <div class="app-tab" data-tab="patients" onclick="switchDoctorTab('patients')">Patients</div>
      <div class="app-tab" data-tab="appointments" onclick="switchDoctorTab('appointments')">Appointments</div>
      <div class="app-tab" data-tab="reports" onclick="switchDoctorTab('reports')">Echo Reports</div>
      <div class="app-tab" data-tab="referrals" onclick="switchDoctorTab('referrals')">Referrals</div>
    </div>

    <!-- OVERVIEW -->
    <div class="tab-panel active" id="tab-overview">
      <div class="stat-row">
        <div class="stat-card"><div class="stat-label">Total patients</div><div class="stat-value">34</div><div class="stat-delta">Under your care</div></div>
        <div class="stat-card"><div class="stat-label">Reports created</div><div class="stat-value">28</div><div class="stat-delta">This month</div></div>
        <div class="stat-card"><div class="stat-label">Pending reports</div><div class="stat-value red">5</div><div class="stat-delta">Awaiting sign-off</div></div>
        <div class="stat-card"><div class="stat-label">Upcoming follow-ups</div><div class="stat-value">7</div><div class="stat-delta">Next 14 days</div></div>
      </div>
      <div class="panel">
        <div class="panel-head"><h2>Recent activity</h2></div>
        <div class="activity-list" id="activity-list"></div>
      </div>
    </div>

    <!-- PATIENTS -->
    <div class="tab-panel" id="tab-patients">
      <div class="panel">
        <div class="panel-head">
          <h2>Patient records</h2>
          <div style="display:flex; gap:10px; align-items:center;">
            <div class="search-box">
              <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="11" cy="11" r="7"/><path d="M21 21l-4.3-4.3"/></svg>
              <input type="text" id="patient-search" placeholder="Search by name or ID..." oninput="renderPatients()">
            </div>
            <button class="btn btn-dark btn-sm" onclick="openPatientModal()">+ New patient</button>
          </div>
        </div>
        <div class="panel-body">
          <table>
            <thead><tr><th>Patient ID</th><th>Name</th><th>Age</th><th>GA</th><th>Referring Doctor</th><th>Status</th><th></th></tr></thead>
            <tbody id="patients-table"></tbody>
          </table>
        </div>
      </div>
    </div>

    <!-- APPOINTMENTS -->
    <div class="tab-panel" id="tab-appointments">
      <div class="panel">
        <div class="panel-head"><h2>Calendar — July 2026</h2><button class="btn btn-dark btn-sm" onclick="openModal('modal-appt')">+ Schedule appointment</button></div>
        <div class="panel-body padded">
          <div id="calendar-grid" class="cal-grid"></div>
        </div>
      </div>
      <div class="panel">
        <div class="panel-head"><h2>Upcoming appointments</h2></div>
        <div class="panel-body">
          <table><thead><tr><th>Date</th><th>Time</th><th>Patient</th><th>Type</th><th></th></tr></thead><tbody id="appointments-table"></tbody></table>
        </div>
      </div>
    </div>

    <!-- ECHO REPORTS -->
    <div class="tab-panel" id="tab-reports">
      <div class="panel">
        <div class="panel-head"><h2>Fetal echo reports</h2><button class="btn btn-dark btn-sm" onclick="openEchoModal()">+ New echo report</button></div>
        <div class="panel-body">
          <table><thead><tr><th>Patient ID</th><th>Study Date</th><th>Rhythm</th><th>Heart Rate</th><th>Status</th><th></th></tr></thead><tbody id="reports-table"></tbody></table>
        </div>
      </div>
    </div>

    <!-- REFERRALS -->
    <div class="tab-panel" id="tab-referrals">
      <div class="panel">
        <div class="panel-head"><h2>Referrals</h2><button class="btn btn-dark btn-sm" onclick="openModal('modal-referral')">+ New referral</button></div>
        <div class="panel-body">
          <table><thead><tr><th>Referral ID</th><th>Patient</th><th>Receiving Specialist</th><th>Date</th><th>Status</th><th></th></tr></thead><tbody id="referrals-table"></tbody></table>
        </div>
      </div>
    </div>
  </div>

  <!-- HOSPITAL MANAGER DASHBOARD -->
  <div class="app-body" id="dash-manager" style="display:none;">
    <div class="app-header">
      <div><h1>Hospital overview</h1><p>St. Mary's Hospital</p></div>
      <button class="btn btn-dark btn-sm" onclick="openModal('modal-doctor')">+ Add doctor</button>
    </div>

    <div class="stat-row">
      <div class="stat-card"><div class="stat-label">Doctors on staff</div><div class="stat-value">9</div><div class="stat-delta">2 pending invite</div></div>
      <div class="stat-card"><div class="stat-label">Open cases</div><div class="stat-value">47</div><div class="stat-delta">Across all doctors</div></div>
      <div class="stat-card"><div class="stat-label">Reports this month</div><div class="stat-value">183</div><div class="stat-delta">+6.1% vs last month</div></div>
      <div class="stat-card"><div class="stat-label">Billing status</div><div class="stat-value" style="font-size:20px;">Current</div><div class="stat-delta">Next invoice Aug 1</div></div>
    </div>

    <div class="panel">
      <div class="panel-head"><h2>Doctors</h2><button class="btn btn-outline btn-sm" onclick="openModal('modal-doctor')">+ Add doctor</button></div>
      <div class="panel-body">
        <table><thead><tr><th>Doctor</th><th>Specialty</th><th>Active cases</th><th>Status</th><th></th></tr></thead><tbody id="manager-doctors-table"></tbody></table>
      </div>
    </div>

    <div class="two-col">
      <div class="panel">
        <div class="panel-head"><h2>Hospital cases</h2></div>
        <div class="panel-body"><table><thead><tr><th>Case ID</th><th>Doctor</th><th>Status</th></tr></thead><tbody id="manager-cases-table"></tbody></table></div>
      </div>
      <div class="panel">
        <div class="panel-head"><h2>Billing overview</h2></div>
        <div class="panel-body padded">
          <table><tbody>
            <tr><td>Plan</td><td style="text-align:right; font-weight:600;">Enterprise</td></tr>
            <tr><td>Cases this cycle</td><td style="text-align:right; font-weight:600;">183 / 250</td></tr>
            <tr><td>Next invoice date</td><td style="text-align:right; font-weight:600;">Aug 1, 2026</td></tr>
            <tr><td>Status</td><td style="text-align:right;"><span class="pill pill-purple">Current</span></td></tr>
          </tbody></table>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- ============ MODALS ============ -->

<div class="modal-overlay" id="modal-reset">
  <div class="modal">
    <h3>Reset your password</h3>
    <p class="modal-sub">Enter your account email and we'll send a reset link.</p>
    <div class="form-field"><label>Email</label><input type="email" placeholder="you@hospital.org"></div>
    <div class="modal-close-row">
      <button class="btn btn-outline btn-sm" onclick="closeModal('modal-reset')">Cancel</button>
      <button class="btn btn-primary btn-sm" onclick="submitMockForm('modal-reset','Password reset link sent')">Send reset link</button>
    </div>
  </div>
</div>

<div class="modal-overlay" id="modal-hospital">
  <div class="modal">
    <h3>Add hospital</h3>
    <div class="form-field"><label>Hospital name</label><input type="text" placeholder="e.g. Lakeview Medical Center"></div>
    <div class="form-field"><label>City</label><input type="text" placeholder="e.g. Lucknow"></div>
    <div class="form-field"><label>Plan</label><select><option>Starter</option><option>Growth</option><option>Enterprise</option></select></div>
    <div class="modal-close-row">
      <button class="btn btn-outline btn-sm" onclick="closeModal('modal-hospital')">Cancel</button>
      <button class="btn btn-primary btn-sm" onclick="submitMockForm('modal-hospital','Hospital added')">Add hospital</button>
    </div>
  </div>
</div>

<div class="modal-overlay" id="modal-doctor">
  <div class="modal">
    <h3>Add doctor</h3>
    <div class="form-field"><label>Full name</label><input type="text" placeholder="e.g. Dr. Aisha Rahman"></div>
    <div class="form-field"><label>Email</label><input type="email" placeholder="doctor@hospital.org"></div>
    <div class="form-field"><label>Specialty</label><input type="text" placeholder="e.g. Fetal Cardiology"></div>
    <div class="modal-close-row">
      <button class="btn btn-outline btn-sm" onclick="closeModal('modal-doctor')">Cancel</button>
      <button class="btn btn-primary btn-sm" onclick="submitMockForm('modal-doctor','Doctor invited')">Send invite</button>
    </div>
  </div>
</div>

<!-- PATIENT MODAL (create/edit) -->
<div class="modal-overlay" id="modal-patient">
  <div class="modal modal-lg">
    <h3 id="patient-modal-title">New patient record</h3>
    <p class="modal-sub" id="patient-modal-sub">Patient ID is generated automatically on save.</p>
    <div class="form-row">
      <div class="form-field"><label>Full name</label><input type="text" id="pf-name" placeholder="e.g. Ritu Kapoor"></div>
      <div class="form-field"><label>Date of birth</label><input type="date" id="pf-dob"></div>
    </div>
    <div class="form-row">
      <div class="form-field"><label>Age</label><input type="number" id="pf-age" placeholder="e.g. 29"></div>
      <div class="form-field"><label>Contact number</label><input type="text" id="pf-contact" placeholder="e.g. +91 98765 43210"></div>
    </div>
    <div class="form-field"><label>Address</label><input type="text" id="pf-address" placeholder="e.g. 14 Park Road, Delhi NCR"></div>
    <div class="form-row">
      <div class="form-field"><label>Hospital MRN</label><input type="text" id="pf-mrn" placeholder="e.g. MRN-88213"></div>
      <div class="form-field"><label>Referring doctor</label><input type="text" id="pf-refdoc" placeholder="e.g. Dr. S. Iyer"></div>
    </div>
    <div class="form-row">
      <div class="form-field"><label>Gestational age</label><input type="text" id="pf-ga" placeholder="e.g. 24w 2d"></div>
      <div class="form-field"><label>LMP</label><input type="date" id="pf-lmp"></div>
    </div>
    <div class="form-row">
      <div class="form-field"><label>EDD</label><input type="date" id="pf-edd"></div>
      <div class="form-field"><label>Status</label>
        <select id="pf-status"><option>Draft</option><option>In review</option><option>Report ready</option><option>Referred</option></select>
      </div>
    </div>
    <div class="form-field"><label>Clinical history</label><textarea id="pf-history" placeholder="Relevant maternal & pregnancy history..."></textarea></div>
    <div class="form-field"><label>Risk factors</label><textarea id="pf-risk" placeholder="e.g. Family history of CHD, maternal diabetes..."></textarea></div>
    <div class="form-field"><label>Notes</label><textarea id="pf-notes" placeholder="Any additional notes..."></textarea></div>
    <div class="modal-close-row">
      <button class="btn btn-outline btn-sm" onclick="closeModal('modal-patient')">Cancel</button>
      <button class="btn btn-primary btn-sm" id="patient-save-btn" onclick="savePatient()">Save patient record</button>
    </div>
  </div>
</div>

<!-- APPOINTMENT MODAL -->
<div class="modal-overlay" id="modal-appt">
  <div class="modal">
    <h3>Schedule appointment</h3>
    <div class="form-field"><label>Patient</label>
      <select id="apt-patient"></select>
    </div>
    <div class="form-row">
      <div class="form-field"><label>Date</label><input type="date" id="apt-date" value="2026-07-20"></div>
      <div class="form-field"><label>Time</label><input type="time" id="apt-time" value="10:00"></div>
    </div>
    <div class="form-field"><label>Appointment type</label>
      <select id="apt-type"><option>Fetal echo screening</option><option>Follow-up scan</option><option>Consultation</option></select>
    </div>
    <div class="form-field"><label>Notes</label><textarea id="apt-notes" placeholder="Optional notes..."></textarea></div>
    <p class="modal-sub" style="margin-top:-6px;">SMS/email reminders are a planned future feature.</p>
    <div class="modal-close-row">
      <button class="btn btn-outline btn-sm" onclick="closeModal('modal-appt')">Cancel</button>
      <button class="btn btn-primary btn-sm" onclick="scheduleAppointment()">Schedule</button>
    </div>
  </div>
</div>

<!-- ECHO REPORT MODAL -->
<div class="modal-overlay" id="modal-echo">
  <div class="modal modal-lg">
    <h3>New fetal echo report</h3>
    <p class="modal-sub">Complete each section of the structured examination.</p>

    <div class="echo-section">
      <div class="echo-section-head">Examination details</div>
      <div class="echo-section-body">
        <div class="form-row">
          <div class="form-field"><label>Patient</label><select id="echo-patient"></select></div>
          <div class="form-field"><label>Examination date</label><input type="date" id="echo-date" value="2026-07-15"></div>
        </div>
        <div class="form-field"><label>Indication</label><input type="text" id="echo-indication" placeholder="e.g. Routine anomaly screen"></div>
      </div>
    </div>

    <div class="echo-section">
      <div class="echo-section-head">Cardiac views</div>
      <div class="echo-section-body">
        <div class="form-field"><label>Four-chamber view</label><textarea id="echo-4ch" placeholder="Findings..."></textarea></div>
        <div class="form-row">
          <div class="form-field"><label>LVOT</label><textarea id="echo-lvot" placeholder="Findings..."></textarea></div>
          <div class="form-field"><label>RVOT</label><textarea id="echo-rvot" placeholder="Findings..."></textarea></div>
        </div>
        <div class="form-row">
          <div class="form-field"><label>Three-vessel view</label><textarea id="echo-3vv" placeholder="Findings..."></textarea></div>
          <div class="form-field"><label>Three-vessel trachea view</label><textarea id="echo-3vt" placeholder="Findings..."></textarea></div>
        </div>
        <div class="form-row">
          <div class="form-field"><label>Aortic arch</label><textarea id="echo-aortic" placeholder="Findings..."></textarea></div>
          <div class="form-field"><label>Ductal arch</label><textarea id="echo-ductal" placeholder="Findings..."></textarea></div>
        </div>
      </div>
    </div>

    <div class="echo-section">
      <div class="echo-section-head">Rhythm & measurements</div>
      <div class="echo-section-body">
        <div class="form-row">
          <div class="form-field"><label>Rhythm</label><select id="echo-rhythm"><option>Regular</option><option>Irregular</option></select></div>
          <div class="form-field"><label>Heart rate (bpm)</label><input type="number" id="echo-hr" placeholder="e.g. 142"></div>
        </div>
        <div class="form-field"><label>Doppler findings</label><textarea id="echo-doppler" placeholder="Findings..."></textarea></div>
        <table class="measure-table">
          <thead><tr><th>Measurement</th><th>Value</th></tr></thead>
          <tbody>
            <tr><td>Cardiothoracic ratio</td><td><input type="text" placeholder="e.g. 0.32"></td></tr>
            <tr><td>Cardiac axis</td><td><input type="text" placeholder="e.g. 45°"></td></tr>
            <tr><td>Ventricular wall thickness</td><td><input type="text" placeholder="e.g. within normal limits"></td></tr>
          </tbody>
        </table>
      </div>
    </div>

    <div class="echo-section">
      <div class="echo-section-head">Image upload</div>
      <div class="echo-section-body">
        <div class="upload-box" onclick="document.getElementById('echo-file-input').click()">
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6"><path d="M12 16V4m0 0L7 9m5-5l5 5M5 20h14"/></svg>
          Click to attach cardiac view images
          <span class="accepted">Supports JPG, PNG, PDF · DICOM & video clips planned</span>
        </div>
        <input type="file" id="echo-file-input" accept=".jpg,.jpeg,.png,.pdf" multiple style="display:none;" onchange="handleEchoFiles(event)">
        <div class="file-chip-row" id="echo-file-chips"></div>
      </div>
    </div>

    <div class="echo-section">
      <div class="echo-section-head">Impression & recommendations</div>
      <div class="echo-section-body">
        <div class="form-field"><label>Impression</label><textarea id="echo-impression" placeholder="Overall impression..."></textarea></div>
        <div class="form-field"><label>Recommendations</label><textarea id="echo-recs" placeholder="Recommended follow-up / next steps..."></textarea></div>
      </div>
    </div>

    <p class="modal-sub">Email delivery of reports is a planned future feature — PDF and print are available now.</p>
    <div class="modal-close-row">
      <button class="btn btn-outline btn-sm" onclick="closeModal('modal-echo')">Cancel</button>
      <button class="btn btn-outline btn-sm" onclick="toast('Sending to printer (demo)')">Print</button>
      <button class="btn btn-primary btn-sm" onclick="saveEchoReport()">Save & generate PDF</button>
    </div>
  </div>
</div>

<!-- REFERRAL MODAL -->
<div class="modal-overlay" id="modal-referral">
  <div class="modal">
    <h3>New referral</h3>
    <div class="form-field"><label>Patient</label><select id="ref-patient"></select></div>
    <div class="form-field"><label>Receiving specialist</label><input type="text" id="ref-specialist" placeholder="e.g. Dr. Kunal Mehta, Pediatric Cardiology, Fortis"></div>
    <div class="form-field"><label>Referral note</label><textarea id="ref-note" placeholder="Reason for referral and relevant findings..."></textarea></div>
    <div class="form-field" style="display:flex; align-items:center; gap:8px;">
      <input type="checkbox" id="ref-attach" style="width:auto;" checked>
      <label for="ref-attach" style="margin:0;">Attach latest echo report</label>
    </div>
    <div class="modal-close-row">
      <button class="btn btn-outline btn-sm" onclick="closeModal('modal-referral')">Cancel</button>
      <button class="btn btn-primary btn-sm" onclick="submitReferral()">Send referral</button>
    </div>
  </div>
</div>

<div class="modal-overlay" id="modal-report">
  <div class="modal">
    <h3 id="report-modal-title">Fetal echo report</h3>
    <div id="report-modal-body" style="font-size:14px; color:var(--ink-soft); line-height:1.7;"></div>
    <div class="modal-close-row">
      <button class="btn btn-outline btn-sm" onclick="closeModal('modal-report')">Close</button>
      <button class="btn btn-outline btn-sm" onclick="toast('Sending to printer (demo)')">Print</button>
      <button class="btn btn-primary btn-sm" onclick="toast('PDF downloaded (demo)'); closeModal('modal-report')">Download PDF</button>
    </div>
  </div>
</div>

<div class="toast" id="toast"><span class="dot"></span><span id="toast-text">Saved</span></div>

<script>
  // ============ MOCK DATA ============
  const hospitals = [
    {name:"St. Mary's Hospital", city:"Delhi NCR", doctors:9, plan:"Enterprise", status:"Active"},
    {name:"Lakeview Medical Center", city:"Lucknow", doctors:5, plan:"Growth", status:"Active"},
    {name:"Sunrise Women's Hospital", city:"Bengaluru", doctors:7, plan:"Enterprise", status:"Active"},
    {name:"Green Valley Maternity", city:"Pune", doctors:3, plan:"Starter", status:"Trial"},
    {name:"Riverside Children's Hospital", city:"Ahmedabad", doctors:6, plan:"Growth", status:"Active"},
  ];

  const managerDoctors = [
    {name:"Dr. Aisha Rahman", specialty:"Fetal Cardiology", cases:12, status:"Active"},
    {name:"Dr. Vikram Chandra", specialty:"Fetal Cardiology", cases:9, status:"Active"},
    {name:"Dr. Priya Menon", specialty:"Obstetric Imaging", cases:15, status:"Active"},
    {name:"Dr. Samuel George", specialty:"Pediatric Cardiology", cases:6, status:"Active"},
    {name:"Dr. Neha Bhatt", specialty:"Fetal Cardiology", cases:5, status:"Invited"},
  ];
  const managerCases = [
    {id:"FC-40281", doctor:"Dr. Aisha Rahman", status:"Report ready"},
    {id:"FC-40276", doctor:"Dr. Vikram Chandra", status:"In review"},
    {id:"FC-40268", doctor:"Dr. Aisha Rahman", status:"Referred"},
    {id:"FC-40251", doctor:"Dr. Priya Menon", status:"Draft"},
  ];

  let patientSeq = 40290;
  let patients = [
    {id:"FC-40281", name:"Ritu Kapoor", dob:"1997-03-14", age:29, contact:"+91 98765 43210", address:"14 Park Road, Delhi NCR", mrn:"MRN-88213", refdoc:"Dr. S. Iyer", ga:"26w 3d", lmp:"2026-01-12", edd:"2026-10-19", history:"First pregnancy, uneventful so far.", risk:"None reported", notes:"", status:"Report ready", archived:false, updated:"Jul 14, 2026"},
    {id:"FC-40276", name:"Sneha Reddy", dob:"1994-07-02", age:31, contact:"+91 98220 11234", address:"22 MG Road, Bengaluru", mrn:"MRN-77190", refdoc:"Dr. K. Nanda", ga:"22w 0d", lmp:"2026-02-16", edd:"2026-11-23", history:"Routine anomaly screen referral.", risk:"None reported", notes:"", status:"In review", archived:false, updated:"Jul 13, 2026"},
    {id:"FC-40268", name:"Meena Joshi", dob:"1990-11-21", age:35, contact:"+91 99887 65432", address:"9 Civil Lines, Lucknow", mrn:"MRN-65021", refdoc:"Dr. R. Verma", ga:"31w 5d", lmp:"2025-12-05", edd:"2026-09-11", history:"Prior scan flagged possible outflow tract anomaly.", risk:"Advanced maternal age", notes:"Referred for second opinion.", status:"Referred", archived:false, updated:"Jul 11, 2026"},
    {id:"FC-40251", name:"Kavya Nair", dob:"1999-05-30", age:26, contact:"+91 90080 12345", address:"5 Marine Drive, Ahmedabad", mrn:"MRN-51882", refdoc:"Dr. A. Pillai", ga:"20w 1d", lmp:"2026-03-01", edd:"2026-12-06", history:"Family history of congenital heart disease.", risk:"Family history of CHD", notes:"", status:"Draft", archived:false, updated:"Jul 9, 2026"},
    {id:"FC-40239", name:"Deepa Iyer", dob:"1992-09-18", age:33, contact:"+91 98765 22110", address:"31 Anna Salai, Pune", mrn:"MRN-44902", refdoc:"Dr. M. Rao", ga:"28w 6d", lmp:"2026-01-02", edd:"2026-10-09", history:"Routine anomaly screen.", risk:"None reported", notes:"", status:"Report ready", archived:false, updated:"Jul 7, 2026"},
  ];

  let apptSeq = 1;
  let appointments = [
    {id:1, patientId:"FC-40276", date:"2026-07-16", time:"09:30", type:"Follow-up scan"},
    {id:2, patientId:"FC-40251", date:"2026-07-18", time:"11:00", type:"Fetal echo screening"},
    {id:3, patientId:"FC-40268", date:"2026-07-22", time:"14:00", type:"Consultation"},
    {id:4, patientId:"FC-40239", date:"2026-07-27", time:"10:30", type:"Follow-up scan"},
  ];

  let reportSeq = 1;
  let echoReports = [
    {id:1, patientId:"FC-40281", date:"2026-07-14", rhythm:"Regular", hr:142, status:"Complete"},
    {id:2, patientId:"FC-40239", date:"2026-07-07", rhythm:"Regular", hr:138, status:"Complete"},
    {id:3, patientId:"FC-40276", date:"2026-07-13", rhythm:"Regular", hr:150, status:"Draft"},
  ];

  let referralSeq = 1;
  let referrals = [
    {id:"REF-1042", patientId:"FC-40268", specialist:"Dr. Kunal Mehta, Pediatric Cardiology, Fortis", date:"Jul 11, 2026", status:"Pending"},
    {id:"REF-1038", patientId:"FC-40251", specialist:"Dr. Farah Sheikh, Fetal Medicine, Apollo", date:"Jul 4, 2026", status:"Accepted"},
    {id:"REF-1029", patientId:"FC-40239", specialist:"Dr. Arvind Rao, Pediatric Cardiology, Manipal", date:"Jun 28, 2026", status:"Completed"},
  ];

  const activity = [
    {text:"Echo report completed for <b>FC-40281</b> — Ritu Kapoor", time:"Today, 2:14 PM", color:"var(--purple-700)"},
    {text:"New patient record created for <b>FC-40251</b> — Kavya Nair", time:"Yesterday, 4:02 PM", color:"var(--purple-700)"},
    {text:"Referral accepted by Dr. Farah Sheikh for <b>FC-40251</b>", time:"Jul 12, 2026", color:"var(--green-600)"},
    {text:"Case <b>FC-40268</b> flagged and referred for second read", time:"Jul 11, 2026", color:"var(--red-600)"},
    {text:"Follow-up appointment scheduled for <b>FC-40276</b>", time:"Jul 10, 2026", color:"var(--purple-700)"},
  ];

  const notifications = [
    {text:"Follow-up due tomorrow for <b>FC-40276</b> — Sneha Reddy", time:"2 hours ago"},
    {text:"Referral <b>REF-1038</b> was accepted by Dr. Farah Sheikh", time:"Yesterday"},
    {text:"Echo report for <b>FC-40281</b> is ready to view", time:"Yesterday"},
  ];

  // ============ HELPERS ============
  function pillFor(status){
    const map = {
      "Report ready":"pill-purple", "Active":"pill-purple", "Accepted":"pill-purple", "Complete":"pill-purple",
      "Referred":"pill-red", "Pending":"pill-red",
      "Trial":"pill-gray", "Invited":"pill-gray", "Draft":"pill-gray", "In review":"pill-gray",
      "Completed":"pill-green"
    };
    return `<span class="pill ${map[status]||'pill-gray'}">${status}</span>`;
  }

  function findPatient(id){ return patients.find(p=>p.id===id); }

  // ============ RENDER: STATIC TABLES ============
  function renderTables(){
    document.getElementById('admin-hospitals-table').innerHTML = hospitals.map(h=>`
      <tr><td style="font-weight:600;">${h.name}</td><td>${h.city}</td><td>${h.doctors}</td><td>${h.plan}</td><td>${pillFor(h.status)}</td>
      <td><div class="row-actions"><button onclick="toast('Viewing ${h.name} (demo)')">View</button></div></td></tr>`).join('');

    document.getElementById('manager-doctors-table').innerHTML = managerDoctors.map(d=>`
      <tr><td style="font-weight:600;">${d.name}</td><td>${d.specialty}</td><td>${d.cases}</td><td>${pillFor(d.status)}</td>
      <td><div class="row-actions"><button onclick="toast('Viewing ${d.name} (demo)')">View</button></div></td></tr>`).join('');

    document.getElementById('manager-cases-table').innerHTML = managerCases.map(c=>`
      <tr><td style="font-weight:600;">${c.id}</td><td>${c.doctor}</td><td>${pillFor(c.status)}</td></tr>`).join('');
  }

  // ============ RENDER: PATIENTS ============
  function renderPatients(){
    const q = (document.getElementById('patient-search')?.value || '').toLowerCase();
    const rows = patients.filter(p => !q || p.name.toLowerCase().includes(q) || p.id.toLowerCase().includes(q));
    document.getElementById('patients-table').innerHTML = rows.map(p=>`
      <tr class="${p.archived?'archived':''}">
        <td style="font-weight:600;">${p.id}</td>
        <td>${p.name}</td>
        <td>${p.age}</td>
        <td>${p.ga}</td>
        <td>${p.refdoc}</td>
        <td>${p.archived ? '<span class="pill pill-gray">Archived</span>' : pillFor(p.status)}</td>
        <td><div class="row-actions">
          <button onclick="openPatientModal('${p.id}')">Edit</button>
          <button onclick="toggleArchive('${p.id}')">${p.archived ? 'Unarchive' : 'Archive'}</button>
        </div></td>
      </tr>`).join('') || `<tr><td colspan="7"><div class="empty-state">No patients match your search.</div></td></tr>`;
  }

  function toggleArchive(id){
    const p = findPatient(id);
    p.archived = !p.archived;
    renderPatients();
    toast(p.archived ? `${id} archived` : `${id} restored`);
  }

  let editingPatientId = null;
  function openPatientModal(id){
    editingPatientId = id || null;
    const isEdit = !!id;
    document.getElementById('patient-modal-title').textContent = isEdit ? `Edit patient — ${id}` : 'New patient record';
    document.getElementById('patient-modal-sub').textContent = isEdit ? 'Update this patient\\'s record.' : 'Patient ID is generated automatically on save.';
    document.getElementById('patient-save-btn').textContent = isEdit ? 'Save changes' : 'Save patient record';

    const p = isEdit ? findPatient(id) : {};
    document.getElementById('pf-name').value = p.name || '';
    document.getElementById('pf-dob').value = p.dob || '';
    document.getElementById('pf-age').value = p.age || '';
    document.getElementById('pf-contact').value = p.contact || '';
    document.getElementById('pf-address').value = p.address || '';
    document.getElementById('pf-mrn').value = p.mrn || '';
    document.getElementById('pf-refdoc').value = p.refdoc || '';
    document.getElementById('pf-ga').value = p.ga || '';
    document.getElementById('pf-lmp').value = p.lmp || '';
    document.getElementById('pf-edd').value = p.edd || '';
    document.getElementById('pf-status').value = p.status || 'Draft';
    document.getElementById('pf-history').value = p.history || '';
    document.getElementById('pf-risk').value = p.risk || '';
    document.getElementById('pf-notes').value = p.notes || '';
    openModal('modal-patient');
  }

  function savePatient(){
    const data = {
      name: document.getElementById('pf-name').value || 'Unnamed patient',
      dob: document.getElementById('pf-dob').value,
      age: document.getElementById('pf-age').value || '—',
      contact: document.getElementById('pf-contact').value,
      address: document.getElementById('pf-address').value,
      mrn: document.getElementById('pf-mrn').value,
      refdoc: document.getElementById('pf-refdoc').value,
      ga: document.getElementById('pf-ga').value,
      lmp: document.getElementById('pf-lmp').value,
      edd: document.getElementById('pf-edd').value,
      status: document.getElementById('pf-status').value,
      history: document.getElementById('pf-history').value,
      risk: document.getElementById('pf-risk').value,
      notes: document.getElementById('pf-notes').value,
      updated: "Jul 15, 2026"
    };
    if(editingPatientId){
      Object.assign(findPatient(editingPatientId), data);
      toast(`${editingPatientId} updated`);
    } else {
      const id = `FC-${patientSeq++}`;
      patients.unshift({id, archived:false, ...data});
      toast(`Patient record ${id} created`);
    }
    closeModal('modal-patient');
    renderPatients();
    refreshSelects();
  }

  // ============ RENDER: APPOINTMENTS + CALENDAR ============
  function refreshSelects(){
    const opts = patients.filter(p=>!p.archived).map(p=>`<option value="${p.id}">${p.id} — ${p.name}</option>`).join('');
    ['apt-patient','echo-patient','ref-patient'].forEach(sel=>{
      const el = document.getElementById(sel);
      if(el) el.innerHTML = opts;
    });
  }

  function renderAppointments(){
    const sorted = [...appointments].sort((a,b)=> (a.date+a.time).localeCompare(b.date+b.time));
    document.getElementById('appointments-table').innerHTML = sorted.map(a=>{
      const p = findPatient(a.patientId);
      return `<tr><td>${a.date}</td><td>${a.time}</td><td>${p ? p.name+' ('+p.id+')' : a.patientId}</td><td>${a.type}</td>
        <td><div class="row-actions"><button onclick="toast('Reminder sending is a planned future feature')">Remind</button></div></td></tr>`;
    }).join('') || `<tr><td colspan="5"><div class="empty-state">No upcoming appointments.</div></td></tr>`;
    renderCalendar();
  }

  function renderCalendar(){
    // July 2026: 1st is a Wednesday, 31 days
    const firstDayOfWeek = 3; // 0=Sun..6=Sat
    const daysInMonth = 31;
    const dayHeads = ['Sun','Mon','Tue','Wed','Thu','Fri','Sat'].map(d=>`<div class="cal-day-head">${d}</div>`).join('');
    let cells = '';
    for(let i=0;i<firstDayOfWeek;i++) cells += `<div class="cal-cell empty"></div>`;
    for(let d=1; d<=daysInMonth; d++){
      const dateStr = `2026-07-${String(d).padStart(2,'0')}`;
      const dayAppts = appointments.filter(a=>a.date===dateStr);
      const hasAppt = dayAppts.length>0;
      cells += `<div class="cal-cell ${hasAppt?'has-appt':''}">
        <div class="daynum">${d}</div>
        ${dayAppts.slice(0,2).map(a=>{
          const p = findPatient(a.patientId);
          return `<span class="cal-appt-tag">${a.time} ${p?p.name.split(' ')[0]:a.patientId}</span>`;
        }).join('')}
      </div>`;
    }
    document.getElementById('calendar-grid').innerHTML = dayHeads + cells;
  }

  function scheduleAppointment(){
    const patientId = document.getElementById('apt-patient').value;
    const date = document.getElementById('apt-date').value;
    const time = document.getElementById('apt-time').value;
    const type = document.getElementById('apt-type').value;
    if(!patientId || !date || !time){ toast('Please complete all required fields'); return; }
    appointments.push({id: apptSeq++, patientId, date, time, type});
    closeModal('modal-appt');
    renderAppointments();
    toast('Appointment scheduled');
  }

  // ============ RENDER: ECHO REPORTS ============
  function renderReports(){
    document.getElementById('reports-table').innerHTML = echoReports.map(r=>{
      const p = findPatient(r.patientId);
      return `<tr>
        <td style="font-weight:600;">${r.patientId}</td>
        <td>${r.date}</td>
        <td>${r.rhythm}</td>
        <td>${r.hr} bpm</td>
        <td>${pillFor(r.status==='Complete'?'Report ready':'Draft')}</td>
        <td><div class="row-actions">
          <button onclick="openReport('${r.patientId}')">View</button>
          <button onclick="toast('PDF downloaded (demo)')">PDF</button>
        </div></td>
      </tr>`;
    }).join('') || `<tr><td colspan="6"><div class="empty-state">No echo reports yet.</div></td></tr>`;
  }

  let echoFiles = [];
  function handleEchoFiles(e){
    const files = Array.from(e.target.files || []);
    files.forEach(f=> echoFiles.push(f.name));
    renderEchoChips();
  }
  function renderEchoChips(){
    document.getElementById('echo-file-chips').innerHTML = echoFiles.map((name,i)=>`
      <span class="file-chip">${name}<button onclick="removeEchoFile(${i})" aria-label="Remove">×</button></span>`).join('');
  }
  function removeEchoFile(i){ echoFiles.splice(i,1); renderEchoChips(); }

  function openEchoModal(){
    echoFiles = [];
    renderEchoChips();
    ['echo-indication','echo-4ch','echo-lvot','echo-rvot','echo-3vv','echo-3vt','echo-aortic','echo-ductal','echo-hr','echo-doppler','echo-impression','echo-recs'].forEach(id=>{
      const el = document.getElementById(id); if(el) el.value='';
    });
    openModal('modal-echo');
  }

  function saveEchoReport(){
    const patientId = document.getElementById('echo-patient').value;
    if(!patientId){ toast('Please select a patient'); return; }
    const rhythm = document.getElementById('echo-rhythm').value;
    const hr = document.getElementById('echo-hr').value || '—';
    echoReports.unshift({id: reportSeq++, patientId, date: document.getElementById('echo-date').value || '2026-07-15', rhythm, hr, status:'Complete'});
    const p = findPatient(patientId);
    if(p){ p.status = 'Report ready'; p.updated = 'Jul 15, 2026'; }
    closeModal('modal-echo');
    renderReports();
    renderPatients();
    toast('Echo report saved — PDF generated');
  }

  function openReport(patientId){
    const p = findPatient(patientId);
    const r = echoReports.find(x=>x.patientId===patientId) || {rhythm:'Regular', hr:142};
    document.getElementById('report-modal-title').textContent = `Report — ${patientId}`;
    document.getElementById('report-modal-body').innerHTML = `
      <p><strong>Patient:</strong> ${p ? p.name : patientId}</p>
      <p><strong>Gestational age:</strong> ${p ? p.ga : '—'}</p>
      <p><strong>Rhythm:</strong> ${r.rhythm} · <strong>Heart rate:</strong> ${r.hr} bpm</p>
      <p><strong>Four-chamber view:</strong> Normal cardiac axis and situs.</p>
      <p><strong>Outflow tracts:</strong> No crossing abnormality identified.</p>
      <p><strong>Impression:</strong> Structurally normal fetal heart on this study. Recommend routine follow-up per protocol.</p>
    `;
    openModal('modal-report');
  }

  // ============ RENDER: REFERRALS ============
  function renderReferrals(){
    document.getElementById('referrals-table').innerHTML = referrals.map(r=>{
      const p = findPatient(r.patientId);
      return `<tr>
        <td style="font-weight:600;">${r.id}</td>
        <td>${p ? p.name+' ('+r.patientId+')' : r.patientId}</td>
        <td>${r.specialist}</td>
        <td>${r.date}</td>
        <td>${pillFor(r.status)}</td>
        <td><div class="row-actions"><button onclick="advanceReferral('${r.id}')">Advance status</button></div></td>
      </tr>`;
    }).join('') || `<tr><td colspan="6"><div class="empty-state">No referrals yet.</div></td></tr>`;
  }

  function advanceReferral(id){
    const r = referrals.find(x=>x.id===id);
    const flow = {"Pending":"Accepted","Accepted":"Completed","Completed":"Completed"};
    r.status = flow[r.status];
    renderReferrals();
    toast(`${id} marked ${r.status}`);
  }

  function submitReferral(){
    const patientId = document.getElementById('ref-patient').value;
    const specialist = document.getElementById('ref-specialist').value;
    if(!patientId || !specialist){ toast('Please complete all required fields'); return; }
    const id = `REF-${1050+referralSeq++}`;
    referrals.unshift({id, patientId, specialist, date:"Jul 15, 2026", status:"Pending"});
    const p = findPatient(patientId);
    if(p){ p.status = 'Referred'; p.updated = 'Jul 15, 2026'; }
    closeModal('modal-referral');
    renderReferrals();
    renderPatients();
    toast('Referral sent');
  }

  // ============ ACTIVITY ============
  function renderActivity(){
    document.getElementById('activity-list').innerHTML = activity.map(a=>`
      <div class="activity-item">
        <span class="activity-dot" style="background:${a.color};"></span>
        <span>${a.text}<span class="activity-time">${a.time}</span></span>
      </div>`).join('');
  }

  // ============ NOTIFICATIONS ============
  function renderNotifs(){
    document.getElementById('notif-list').innerHTML = notifications.map(n=>`
      <div class="notif-item">${n.text}<span class="notif-time">${n.time}</span></div>`).join('');
    document.getElementById('notif-badge').textContent = notifications.length;
    document.getElementById('notif-badge').style.display = notifications.length ? 'flex' : 'none';
  }
  function toggleNotifs(){ document.getElementById('notif-dropdown').classList.toggle('show'); }
  document.addEventListener('click', (e)=>{
    const wrap = document.querySelector('.notif-wrap');
    if(wrap && !wrap.contains(e.target)) document.getElementById('notif-dropdown').classList.remove('show');
  });

  // ============ DOCTOR TABS ============
  function switchDoctorTab(tab){
    document.querySelectorAll('#dash-doctor .app-tab').forEach(t=>t.classList.toggle('active', t.dataset.tab===tab));
    document.querySelectorAll('#dash-doctor .tab-panel').forEach(p=>p.classList.toggle('active', p.id==='tab-'+tab));
  }

  // ============ VIEW SWITCHING ============
  function showMarketing(){
    document.getElementById('marketing-view').classList.remove('hidden');
    document.getElementById('login-view').style.display='none';
    document.getElementById('app-view').classList.remove('active');
  }
  function showLogin(){
    document.getElementById('marketing-view').classList.add('hidden');
    document.getElementById('login-view').style.display='block';
    document.getElementById('app-view').classList.remove('active');
    window.scrollTo(0,0);
  }
  let chosenRole = 'doctor';
  function selectRole(role){
    chosenRole = role;
    document.querySelectorAll('.role-opt').forEach(el=>{ el.classList.toggle('selected', el.dataset.role===role); });
  }
  selectRole('doctor');

  const roleNames = {
    admin: {label:'ADMIN', name:'Amit Verma'},
    doctor: {label:'DOCTOR', name:'Dr. Jane Smith'},
    manager: {label:'HOSPITAL MANAGER', name:'Kavita Rao'}
  };

  function doLogin(){
    document.getElementById('marketing-view').classList.add('hidden');
    document.getElementById('login-view').style.display='none';
    document.getElementById('app-view').classList.add('active');
    document.getElementById('dash-admin').style.display = chosenRole==='admin' ? 'block' : 'none';
    document.getElementById('dash-doctor').style.display = chosenRole==='doctor' ? 'block' : 'none';
    document.getElementById('dash-manager').style.display = chosenRole==='manager' ? 'block' : 'none';
    document.getElementById('topbar-role').textContent = roleNames[chosenRole].label;
    document.getElementById('topbar-name').textContent = roleNames[chosenRole].name;

    renderTables();
    refreshSelects();
    renderPatients();
    renderAppointments();
    renderReports();
    renderReferrals();
    renderActivity();
    renderNotifs();
    window.scrollTo(0,0);
  }
  function logout(){ showLogin(); }

  // ============ MODALS / TOAST ============
  function openModal(id){ document.getElementById(id).classList.add('show'); }
  function closeModal(id){ document.getElementById(id).classList.remove('show'); }
  function submitMockForm(id, message){ closeModal(id); toast(message); }
  let toastTimer;
  function toast(msg){
    const t = document.getElementById('toast');
    document.getElementById('toast-text').textContent = msg;
    t.classList.add('show');
    clearTimeout(toastTimer);
    toastTimer = setTimeout(()=>t.classList.remove('show'), 2800);
  }

  function handleDemoSubmit(e){
    e.preventDefault();
    toast("Demo request sent — we'll be in touch soon");
    e.target.reset();
  }

  document.querySelectorAll('.modal-overlay').forEach(ov=>{
    ov.addEventListener('click', (e)=>{ if(e.target===ov) ov.classList.remove('show'); });
  });
  document.addEventListener('keydown', (e)=>{
    if(e.key==='Escape'){ document.querySelectorAll('.modal-overlay.show').forEach(ov=>ov.classList.remove('show')); }
  });
</script>

</body>
</html>
