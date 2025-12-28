<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Link Dashboard | Nguyễn Danh Thành Trung</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary-bg: #0f172a;
            --glass-bg: rgba(255, 255, 255, 0.03);
            --glass-border: rgba(255, 255, 255, 0.1);
            --accent-self: #00f2fe;
            --accent-other: #a855f7;
            --text-color: #f8fafc;
        }

        * { box-sizing: border-box; margin: 0; padding: 0; font-family: 'Inter', sans-serif; }
        body { background-color: var(--primary-bg); color: var(--text-color); min-height: 100vh; display: flex; justify-content: center; padding: 40px 10px; overflow-x: hidden; }
        #particles { position: fixed; top: 0; left: 0; width: 100%; height: 100%; z-index: -1; }

        .wrapper { width: 100%; max-width: 900px; z-index: 1; }
        .header-title { text-align: center; margin-bottom: 40px; font-weight: 800; font-size: 2.2rem; background: linear-gradient(to right, #fff, #94a3b8); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }

        .container { display: grid; grid-template-columns: 1fr 1fr; gap: 30px; }
        @media (max-width: 768px) { .container { grid-template-columns: 1fr; } }

        .input-card {
            background: rgba(255, 255, 255, 0.05); padding: 20px; border-radius: 24px; border: 1px solid var(--glass-border); margin-bottom: 25px; backdrop-filter: blur(10px);
        }
        .section-label { font-weight: 800; margin-bottom: 15px; display: block; text-transform: uppercase; letter-spacing: 1px; font-size: 0.9rem; }
        .label-self { color: var(--accent-self); }

        input {
            width: 100%; padding: 14px; margin-bottom: 10px; border-radius: 12px; border: 1px solid var(--glass-border); background: rgba(0,0,0,0.3); color: white; outline: none; transition: 0.3s;
        }
        input:focus { border-color: white; background: rgba(0,0,0,0.5); }
        .btn-add { width: 100%; padding: 14px; border-radius: 12px; border: none; font-weight: 800; cursor: pointer; transition: 0.3s; text-transform: uppercase; margin-top: 5px; }
        .add-self { background: var(--accent-self); color: #0f172a; }
        .add-other { background: var(--accent-other); color: white; }

        .link-grid { display: flex; flex-direction: column; gap: 15px; }
        .link-btn-item {
            background: var(--glass-bg); border: 1px solid var(--glass-border); border-radius: 20px; transition: all 0.3s ease; position: relative; overflow: hidden;
        }
        .link-btn-item:hover { background: rgba(255, 255, 255, 0.08); transform: translateY(-2px); border-color: rgba(255,255,255,0.4); }

        .btn-content { display: flex; align-items: center; width: 100%; }
        .main-link { flex-grow: 1; padding: 18px 20px; text-decoration: none; color: white; display: flex; flex-direction: column; overflow: hidden; }
        .main-link strong { font-size: 0.95rem; margin-bottom: 4px; line-height: 1.4; }
        .main-link span { font-size: 0.7rem; opacity: 0.4; white-space: nowrap; overflow: hidden; text-overflow: ellipsis; }

        .side-actions { display: flex; padding-right: 15px; gap: 8px; }
        .icon-btn {
            width: 36px; height: 36px; border-radius: 10px; display: flex; align-items: center; justify-content: center; background: rgba(255,255,255,0.05); color: white; border: 1px solid var(--glass-border); cursor: pointer; transition: 0.2s;
        }
        .copy-btn:hover { background: #4ade80; color: #0f172a; border-color: #4ade80; }
        .del-btn:hover { background: #f43f5e; color: white; border-color: #f43f5e; }

        /* All In One Special Box */
        .sub-links {
            background: rgba(0, 0, 0, 0.2); border-top: 1px solid var(--glass-border); padding: 12px 20px; display: flex; flex-direction: column; gap: 10px;
        }
        .sub-item { display: flex; justify-content: space-between; align-items: center; padding: 8px 12px; background: rgba(255,255,255,0.03); border-radius: 10px; font-size: 0.85rem; }
        .sub-item span { color: #94a3b8; }
        .sub-item .actions a { color: var(--accent-self); text-decoration: none; font-weight: 600; margin-right: 10px; }
        .sub-item .actions button { background: none; border: none; color: #fff; cursor: pointer; opacity: 0.7; }
        .sub-item .actions button:hover { opacity: 1; color: #4ade80; }
    </style>
</head>
<body>

    <canvas id="particles"></canvas>

    <div class="wrapper">
        <h1 class="header-title">Link Dashboard</h1>

        <div class="container">
            <div class="column">
                <div class="input-card">
                    <span class="section-label label-self"><i class="fa-solid fa-wand-magic-sparkles"></i> Tự làm</span>
                    <input type="text" id="titleSelf" placeholder="Tên nút...">
                    <input type="text" id="urlSelf" placeholder="https://...">
                    <button class="btn-add add-self" onclick="saveLink('self')">Thêm Nút Tự Làm</button>
                </div>
                <div class="link-grid" id="listSelf"></div>
            </div>

            <div class="column">
                <div class="input-card">
                    <span class="section-label label-other"><i class="fa-solid fa-link"></i> Nguồn tham khảo</span>
                    <input type="text" id="titleOther" placeholder="Tên nguồn...">
                    <input type="text" id="urlOther" placeholder="https://...">
                    <button class="btn-add add-other" onclick="saveLink('other')">Thêm Nút Nguồn Khác</button>
                </div>
                <div class="link-grid" id="listOther"></div>
            </div>
        </div>
    </div>

    <script>
        // Particles Effect
        const canvas = document.getElementById('particles');
        const ctx = canvas.getContext('2d');
        let particles = [];
        function initCanvas() { canvas.width = window.innerWidth; canvas.height = window.innerHeight; }
        class Particle {
            constructor() {
                this.x = Math.random() * canvas.width; this.y = Math.random() * canvas.height;
                this.size = Math.random() * 1.5; this.speedX = Math.random() * 0.4 - 0.2; this.speedY = Math.random() * 0.4 - 0.2; this.opacity = Math.random() * 0.4;
            }
            update() { this.x += this.speedX; this.y += this.speedY; if (this.x > canvas.width) this.x = 0; if (this.y > canvas.height) this.y = 0; }
            draw() { ctx.fillStyle = `rgba(255, 255, 255, ${this.opacity})`; ctx.beginPath(); ctx.arc(this.x, this.y, this.size, 0, Math.PI * 2); ctx.fill(); }
        }
        function animate() { ctx.clearRect(0, 0, canvas.width, canvas.height); particles.forEach(p => { p.update(); p.draw(); }); requestAnimationFrame(animate); }
        initCanvas(); for(let i=0; i<70; i++) particles.push(new Particle()); animate();

        // Database setup with your specific links
        const confLink = "https://raw.githubusercontent.com/NgDanhThanhTrung/AllInOne_ProMax/refs/heads/main/AllInOne_ProMax.conf";
        const sgLink = "https://raw.githubusercontent.com/NgDanhThanhTrung/AllInOne_ProMax/refs/heads/main/AllInOne_ProMax.sgmodule";

        let db = JSON.parse(localStorage.getItem('btnLinksV4')) || {
            self: [
                { title: "All in one (ProMax Config)", special: true },
                { title: "YouTube Ads Block & Premium Unlocked (PicsArt, Lightroom, Spotify, Alight Motion, etc.)", url: "https://raw.githubusercontent.com/NgDanhThanhTrung/allinone/refs/heads/main/All%20IN%20ONE(v1.0).sgmodule" },
                { title: "YouTube Premium, Spotify Premium & Locket Gold", url: "https://raw.githubusercontent.com/NgDanhThanhTrung/allinone/refs/heads/main/ALL_IN_ONE.sgmobile" }
            ],
            other: []
        };

        function render() {
            ['self', 'other'].forEach(type => {
                const container = document.getElementById(`list${type.charAt(0).toUpperCase() + type.slice(1)}`);
                container.innerHTML = db[type].map((item, index) => {
                    if (item.special) {
                        return `
                        <div class="link-btn-item">
                            <div class="btn-content">
                                <div class="main-link">
                                    <strong style="color:var(--accent-self)">${item.title}</strong>
                                    <span>GitHub ProMax Config Files</span>
                                </div>
                                <div class="side-actions"><button class="icon-btn del-btn" onclick="del('${type}', ${index})"><i class="fa-solid fa-xmark"></i></button></div>
                            </div>
                            <div class="sub-links">
                                <div class="sub-item"><span>File .conf</span><div class="actions"><a href="${confLink}" target="_blank">Mở</a><button onclick="copy('${confLink}', this)">Copy</button></div></div>
                                <div class="sub-item"><span>File .sgmodule</span><div class="actions"><a href="${sgLink}" target="_blank">Mở</a><button onclick="copy('${sgLink}', this)">Copy</button></div></div>
                            </div>
                        </div>`;
                    }
                    return `
                    <div class="link-btn-item">
                        <div class="btn-content">
                            <a href="${item.url}" target="_blank" class="main-link">
                                <strong>${item.title}</strong>
                                <span>${item.url}</span>
                            </a>
                            <div class="side-actions">
                                <button class="icon-btn copy-btn" onclick="copy('${item.url}', this)"><i class="fa-regular fa-copy"></i></button>
                                <button class="icon-btn del-btn" onclick="del('${type}', ${index})"><i class="fa-solid fa-xmark"></i></button>
                            </div>
                        </div>
                    </div>`;
                }).join('');
            });
            localStorage.setItem('btnLinksV4', JSON.stringify(db));
        }

        function saveLink(type) {
            const tInput = document.getElementById(`title${type.charAt(0).toUpperCase() + type.slice(1)}`);
            const uInput = document.getElementById(`url${type.charAt(0).toUpperCase() + type.slice(1)}`);
            if(!tInput.value) return alert("Nhập tên nút!");
            db[type].unshift({ title: tInput.value, url: uInput.value || "#" });
            tInput.value = ''; uInput.value = '';
            render();
        }

        function del(type, index) {
            if(confirm("Xóa nhé Trung?")) { db[type].splice(index, 1); render(); }
        }

        function copy(text, btn) {
            navigator.clipboard.writeText(text);
            const original = btn.innerHTML;
            btn.innerHTML = 'COPIED!';
            btn.style.color = '#4ade80';
            setTimeout(() => { btn.innerHTML = original; btn.style.color = ''; }, 1500);
        }

        render();
        window.onresize = initCanvas;
    </script>
</body>
</html>
