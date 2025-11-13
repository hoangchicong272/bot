<!doctype html>
<html lang="vi">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Portfolio chuyên nghiệp — Chuyên gia</title>
  <meta name="description" content="Trang giới thiệu chuyên nghiệp — dịch vụ, dự án và liên hệ." />

  <!-- Fonts (system fallback + subtle Google) -->
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">

  <style>
    :root{
      --bg:#0f1724; /* deep navy */
      --card:#0b1220;
      --muted:#9aa4b2;
      --accent:#6ee7b7; /* mint */
      --accent-2:#60a5fa; /* blue */
      --glass: rgba(255,255,255,0.04);
      --glass-2: rgba(255,255,255,0.02);
      --radius:14px;
      --max-width:1100px;
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;font-family:Inter,system-ui,-apple-system,"Segoe UI",Roboto,"Helvetica Neue",Arial; background: linear-gradient(180deg,var(--bg), #071022 120%); color:#e6eef6;-webkit-font-smoothing:antialiased}

    /* Layout */
    .wrap{max-width:var(--max-width);margin:48px auto;padding:24px}
    header{display:flex;align-items:center;justify-content:space-between;gap:16px;margin-bottom:28px}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{width:48px;height:48px;display:grid;place-items:center;background:linear-gradient(135deg,var(--accent),var(--accent-2));border-radius:12px;box-shadow:0 6px 18px rgba(12,18,30,0.6)}
    .logo svg{width:26px;height:26px}
    .brand h1{font-size:18px;margin:0;font-weight:700;letter-spacing:0.2px}
    .brand p{margin:0;font-size:12px;color:var(--muted)}

    nav{display:flex;gap:12px;align-items:center}
    nav a{color:var(--muted);text-decoration:none;padding:8px 12px;border-radius:10px;font-size:14px}
    nav a:hover{color:#fff;background:var(--glass)}

    /* Hero */
    .hero{display:grid;grid-template-columns:1fr 380px;gap:28px;align-items:center;margin-top:12px}
    .card{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.015)); border-radius:var(--radius); padding:28px;box-shadow:0 8px 30px rgba(2,6,23,0.6);backdrop-filter: blur(6px)}

    .intro h2{margin:0;font-size:30px;line-height:1.02}
    .intro p.lead{color:var(--muted);margin:16px 0 20px;font-size:15px}
    .cta-row{display:flex;gap:12px}
    .btn{padding:10px 16px;border-radius:10px;font-weight:600;border:0;cursor:pointer}
    .btn-primary{background:linear-gradient(90deg,var(--accent),var(--accent-2));color:#022;box-shadow:0 8px 22px rgba(98,172,210,0.08);}
    .btn-ghost{background:transparent;border:1px solid rgba(255,255,255,0.06);color:var(--muted)}

    .skills{display:flex;gap:8px;flex-wrap:wrap;margin-top:14px}
    .skill{font-size:13px;padding:8px 12px;border-radius:999px;background:var(--glass-2);color:var(--muted)}

    /* Right hero: profile */
    .profile{display:flex;flex-direction:column;gap:16px}
    .profile .avatar{height:140px;border-radius:12px;background:linear-gradient(180deg,#102233,#0b1a2a);display:grid;place-items:center;color:var(--accent);font-weight:700;box-shadow:inset 0 0 40px rgba(96,165,250,0.06)}
    .meta{display:flex;gap:12px;justify-content:space-between}
    .meta .m{font-size:13px;color:var(--muted)}

    /* social floating */
    .social-fixed{position:fixed;left:18px;top:50%;transform:translateY(-50%);display:flex;flex-direction:column;gap:12px}
    .social-fixed a{width:44px;height:44px;border-radius:10px;display:grid;place-items:center;background:var(--card);box-shadow:0 6px 18px rgba(2,6,23,0.6);text-decoration:none}
    .social-fixed a svg{width:20px;height:20px;opacity:0.95}

    /* Sections */
    section{margin-top:28px}
    .grid-3{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
    .service h3{margin:0;font-size:16px}
    .service p{color:var(--muted);font-size:14px}

    /* Projects */
    .projects{display:grid;grid-template-columns:repeat(2,1fr);gap:16px}
    .proj{border-radius:12px;padding:14px;background:linear-gradient(180deg, rgba(255,255,255,0.015), rgba(255,255,255,0.01));border:1px solid rgba(255,255,255,0.02)}
    .proj img{width:100%;height:160px;object-fit:cover;border-radius:8px}

    /* Footer */
    footer{margin-top:32px;padding:20px;border-radius:12px;background:transparent;display:flex;justify-content:space-between;align-items:center}
    footer p{color:var(--muted);margin:0}

    /* subtle animated gradient underline */
    .logo-underline{height:4px;border-radius:999px;background:linear-gradient(90deg,var(--accent),var(--accent-2));width:80px;margin-top:8px;animation:float 6s ease-in-out infinite}
    @keyframes float{0%{transform:translateX(0)}50%{transform:translateX(18px)}100%{transform:translateX(0)} }

    /* small devices */
    @media (max-width:900px){
      .hero{grid-template-columns:1fr;}
      .profile{order:2}
      .social-fixed{display:none}
      .projects{grid-template-columns:1fr}
      .grid-3{grid-template-columns:1fr}
    }

    /* micro-interactions */
    .btn:active{transform:translateY(1px)}
    a{transition:all .18s ease}
    .card:hover{transform:translateY(-6px);transition:transform .28s cubic-bezier(.2,.9,.2,1)}

    /* subtle background particles using pseudo-elements */
    body::before{content:"";position:fixed;left:-10%;top:-20%;width:60vmax;height:60vmax;background:radial-gradient(circle at 30% 30%, rgba(108,211,178,0.06), transparent 10%), radial-gradient(circle at 70% 70%, rgba(96,165,250,0.035), transparent 12%);pointer-events:none;filter:blur(36px);}
  </style>
</head>
<body>

  <div class="social-fixed" aria-hidden="false">
    <a href="#" title="Email" onclick="openMail()" aria-label="Email">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"><path d="M3 8.5v7.5a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2V8.5"/><path d="M22 6H2l10 7L22 6z"/></svg>
    </a>
    <a href="https://www.linkedin.com" target="_blank" rel="noopener" title="LinkedIn">
      <svg viewBox="0 0 24 24" fill="currentColor"><path d="M4.98 3.5C4.98 4.88 3.86 6 2.5 6S0 4.88 0 3.5 1.12 1 2.5 1 4.98 2.12 4.98 3.5zM0 24h5V7H0v17zM7.5 24h4.8V15.1c0-2.2 1.6-3.4 3.6-3.4 2 0 3.5 1 3.5 3.9V24h4.8V14.3c0-5.8-3.1-8.5-7.3-8.5-3.3 0-4.7 2-5.5 3.4h-.1V7H7.5v17z"/></svg>
    </a>
    <a href="https://github.com" target="_blank" rel="noopener" title="GitHub">
      <svg viewBox="0 0 24 24" fill="currentColor"><path d="M12 .5C5.73.5.98 5.26.98 11.5c0 4.7 3.07 8.7 7.33 10.12.54.1.74-.24.74-.53 0-.26-.01-1.14-.02-2.06-2.98.65-3.61-1.44-3.61-1.44-.49-1.25-1.2-1.58-1.2-1.58-.98-.67.08-.66.08-.66 1.08.08 1.65 1.11 1.65 1.11.96 1.64 2.52 1.17 3.13.9.1-.7.38-1.17.69-1.44-2.38-.27-4.88-1.19-4.88-5.3 0-1.17.42-2.13 1.11-2.88-.12-.27-.48-1.36.11-2.83 0 0 .9-.29 2.95 1.11a10.18 10.18 0 0 1 2.69-.36c.91 0 1.83.12 2.69.36 2.05-1.4 2.95-1.11 2.95-1.11.59 1.47.23 2.56.12 2.83.69.75 1.1 1.7 1.1 2.88 0 4.12-2.51 5.02-4.9 5.29.39.34.73 1.02.73 2.06 0 1.48-.01 2.66-.01 3.02 0 .3.2.64.75.53C20 20.2 23 16.2 23 11.5 23 5.26 18.27.5 12 .5z"/></svg>
    </a>
  </div>

  <div class="wrap">
    <header>
      <div class="brand">
        <div class="logo" aria-hidden="true">
          <svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path d="M4 12c2-4 7-6 12-4" stroke="#022" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" opacity="0.95"/></svg>
        </div>
        <div>
          <h1>Chuyên gia Thiết kế &amp; Phát triển</h1>
          <p>Thiết kế giao diện • Website • Thương hiệu</p>
          <div class="logo-underline" aria-hidden></div>
        </div>
      </div>

      <nav aria-label="Navigation">
        <a href="#about">Giới thiệu</a>
        <a href="#services">Dịch vụ</a>
        <a href="#projects">Dự án</a>
        <a href="#contact">Liên hệ</a>
      </nav>
    </header>

    <main>
      <section class="hero">
        <div class="card intro">
          <h2>Xin chào — Tôi là <span style="color:var(--accent);">Chuyên gia</span> thiết kế & phát triển web.</h2>
          <p class="lead">Tôi giúp các thương hiệu và dự án cá nhân xây dựng trang web chuyên nghiệp, tối ưu trải nghiệm người dùng và tăng chuyển đổi. Thiết kế tỉ mỉ, mã sạch và hiệu suất ưu tiên.</p>

          <div class="cta-row">
            <button class="btn btn-primary" onclick="scrollToId('contact')">Yêu cầu báo giá</button>
            <a class="btn btn-ghost" href="#projects">Xem dự án</a>
          </div>

          <div class="skills" aria-hidden>
            <div class="skill">HTML &amp; CSS</div>
            <div class="skill">JavaScript / SPA</div>
            <div class="skill">Thiết kế UI/UX</div>
            <div class="skill">Tối ưu hiệu suất</div>
            <div class="skill">Responsive</div>
          </div>

          <p class="lead" style="margin-top:18px">Tôi ưu tiên giao tiếp rõ ràng, tiến độ đúng hạn, và sản phẩm dễ bảo trì. Dưới đây là một số dịch vụ tiêu biểu.</p>
        </div>

        <aside class="card profile" aria-labelledby="profile-heading">
          <div class="avatar">
            <div style="text-align:center">
              <div style="font-size:22px">CG</div>
              <div style="font-size:12px;color:var(--muted);margin-top:6px">Chuyên gia — Frontend</div>
            </div>
          </div>

          <div class="meta">
            <div>
              <div class="m">Kinh nghiệm</div>
              <div style="font-weight:700">8+ năm</div>
            </div>
            <div>
              <div class="m">Dự án</div>
              <div style="font-weight:700">120+</div>
            </div>
          </div>

          <div style="display:flex;gap:10px;align-items:center;justify-content:space-between">
            <div style="font-size:13px;color:var(--muted)">Sẵn sàng nhận việc</div>
            <div>
              <a href="#contact" class="btn btn-primary" style="padding:8px 12px">Thuê tôi</a>
            </div>
          </div>
        </aside>
      </section>

      <section id="about">
        <div class="card">
          <h2>Giới thiệu ngắn</h2>
          <p style="color:var(--muted)">Tôi là chuyên gia thiết kế trải nghiệm người dùng (UX) và phát triển giao diện tương tác. Tôi xây dựng sản phẩm có tính thẩm mỹ cao, tải nhanh và dễ mở rộng. Lần hợp tác tốt nhất bắt đầu bằng một cuộc nói chuyện — hãy kể cho tôi về mục tiêu của bạn.</p>
        </div>
      </section>

      <section id="services">
        <div class="card">
          <h2>Dịch vụ</h2>
          <div class="grid-3" style="margin-top:14px">
            <div class="service">
              <h3>Thiết kế UI/UX</h3>
              <p>Wireframe, thiết kế tương tác, hệ thống thiết kế (design systems) để giữ tính nhất quán cho thương hiệu.</p>
            </div>
            <div class="service">
              <h3>Phát triển Frontend</h3>
              <p>HTML, CSS hiện đại, JavaScript tối ưu, SPA và tích hợp với API. Tối ưu SEO cơ bản và tốc độ tải.</p>
            </div>
            <div class="service">
              <h3>Thương mại &amp; Landing</h3>
              <p>Landing pages chuyển đổi cao, tích hợp theo dõi, tối ưu CRO cho chiến dịch marketing.</p>
            </div>
          </div>
        </div>
      </section>

      <section id="projects">
        <div class="card">
          <h2>Dự án tiêu biểu</h2>
          <div class="projects" style="margin-top:14px">
            <article class="proj">
              <img src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='800' height='450'><rect width='100%' height='100%' fill='%230b1220'/><text x='50%' y='50%' dominant-baseline='middle' text-anchor='middle' font-size='22' fill='%2360a5fa'>Dự án A — Website thương hiệu</text></svg>" alt="Dự án A">
              <h3 style="margin-top:12px">Website thương hiệu</h3>
              <p style="color:var(--muted)">Thiết kế hệ thống sản phẩm, tối ưu hiển thị trên thiết bị di động.</p>
            </article>

            <article class="proj">
              <img src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='800' height='450'><rect width='100%' height='100%' fill='%23102233'/><text x='50%' y='50%' dominant-baseline='middle' text-anchor='middle' font-size='22' fill='%236ee7b7'>Dự án B — Landing</text></svg>" alt="Dự án B">
              <h3 style="margin-top:12px">Landing chuyển đổi</h3>
              <p style="color:var(--muted)">Tối ưu hành trình người dùng, tăng tỉ lệ chuyển đổi đơn hàng.</p>
            </article>
          </div>
        </div>
      </section>

      <section id="contact">
        <div class="card">
          <h2>Liên hệ</h2>
          <p style="color:var(--muted)">Gửi thông tin cơ bản, tôi sẽ phản hồi trong vòng 24 - 48 giờ.</p>

          <form id="contactForm" onsubmit="submitForm(event)" style="margin-top:12px;display:grid;gap:10px">
            <div style="display:grid;grid-template-columns:1fr 1fr;gap:10px">
              <input id="name" name="name" required placeholder="Họ và tên" style="padding:10px;border-radius:8px;background:transparent;border:1px solid rgba(255,255,255,0.04);color:#eaf5ff">
              <input id="email" name="email" type="email" required placeholder="Email" style="padding:10px;border-radius:8px;background:transparent;border:1px solid rgba(255,255,255,0.04);color:#eaf5ff">
            </div>
            <input id="subject" name="subject" placeholder="Tiêu đề" style="padding:10px;border-radius:8px;background:transparent;border:1px solid rgba(255,255,255,0.04);color:#eaf5ff">
            <textarea id="message" name="message" rows="6" required placeholder="Nội dung" style="padding:10px;border-radius:8px;background:transparent;border:1px solid rgba(255,255,255,0.04);color:#eaf5ff"></textarea>
            <div style="display:flex;gap:10px;align-items:center">
              <button class="btn btn-primary" type="submit">Gửi</button>
              <div id="formMsg" style="color:var(--muted)"></div>
            </div>
          </form>
        </div>
      </section>

      <footer>
        <p>&copy; <span id="year"></span> Chuyên gia. Bản quyền.</p>
        <div>
          <a href="#" style="margin-right:12px;color:var(--muted);text-decoration:none">Privacy</a>
          <a href="#" style="color:var(--muted);text-decoration:none">Terms</a>
        </div>
      </footer>
    </main>
  </div>

  <script>
    // small utilities
    function scrollToId(id){
      const el = document.getElementById(id);
      if(!el) return;
      el.scrollIntoView({behavior:'smooth',block:'start'});
    }

    // set current year
    document.getElementById('year').textContent = new Date().getFullYear();

    // fake contact submit (no backend) — provide downloadable mailto fallback
    function submitForm(e){
      e.preventDefault();
      const n = document.getElementById('name').value.trim();
      const mail = document.getElementById('email').value.trim();
      const subj = document.getElementById('subject').value.trim() || 'Yêu cầu từ website';
      const msg = document.getElementById('message').value.trim();
      const msgEl = document.getElementById('formMsg');
      if(!n || !mail || !msg){
        msgEl.textContent = 'Vui lòng điền đầy đủ tên, email và nội dung.'; return; }

      // create mailto as a fallback and show a friendly message
      const body = encodeURIComponent('Tên: '+n + '\nEmail: '+mail + '\n\n' + msg);
      const mailto = `mailto:hello@yourdomain.com?subject=${encodeURIComponent(subj)}&body=${body}`;

      // show success then open mail client
      msgEl.textContent = 'Cảm ơn! Mở ứng dụng email để hoàn tất gửi...';
      setTimeout(()=>{
        window.location.href = mailto;
      },600);
    }

    function openMail(){
      window.location.href = 'mailto:hello@yourdomain.com';
    }

    // small theme of micro-animation on scroll
    const observer = new IntersectionObserver((entries)=>{
      entries.forEach(e=>{
        if(e.isIntersecting){
          e.target.classList.add('in-view');
        }
      });
    },{threshold:0.12});

    document.querySelectorAll('.card').forEach(c=>observer.observe(c));

    // keyboard accessibility: pressing / focuses search (example)
    window.addEventListener('keydown', (ev)=>{
      if(ev.key === 'k' && (ev.ctrlKey || ev.metaKey)){
        ev.preventDefault();
        document.getElementById('name')?.focus();
      }
    });

  </script>
</body>
</html>
