<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Okinawa Trip 2026</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+TC:wght@300;400;500;700&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: { sans: ['"Noto Sans TC"', 'sans-serif'] },
                    colors: {
                        muji: { bg: '#F9F8F6', card: '#FFFFFF', text: '#4A4A4A', light: '#8C8C8C', accent: '#9D8E7D', border: '#E8E6E1', alert: '#D47264' }
                    }
                }
            }
        }
    </script>
    <style>
        body { background-color: #F9F8F6; color: #4A4A4A; font-family: 'Noto Sans TC', sans-serif; -webkit-tap-highlight-color: transparent; }
        ::-webkit-scrollbar { display: none; }
        .hide-scroll { -ms-overflow-style: none; scrollbar-width: none; }
        .view-section { display: none; animation: fadeIn 0.3s ease-in-out; }
        .view-section.active { display: block; }
        @keyframes fadeIn { from { opacity: 0; transform: translateY(5px); } to { opacity: 1; transform: translateY(0); } }
        .muji-card { background: #FFFFFF; border-radius: 12px; box-shadow: 0 2px 8px rgba(0,0,0,0.04); border: 1px solid #E8E6E1; }
        .muji-input { width: 100%; border: 1px solid #E8E6E1; border-radius: 8px; padding: 10px; background: #F9F8F6; outline: none; transition: border 0.2s; }
        .muji-input:focus { border-color: #9D8E7D; background: #FFFFFF; }
        .muji-btn { background: #9D8E7D; color: #FFF; padding: 10px 16px; border-radius: 8px; text-align: center; font-weight: 500; transition: opacity 0.2s; }
        .pb-safe { padding-bottom: env(safe-area-inset-bottom); }
    </style>
</head>
<body class="pb-24 hide-scroll">

    <header class="sticky top-0 bg-muji-bg/90 backdrop-blur-sm z-40 border-b border-muji-border px-5 py-4">
        <h1 class="text-xl font-medium tracking-wider text-center text-muji-text">OKINAWA <span class="text-muji-light text-sm ml-1">6.16 - 6.20</span></h1>
    </header>

    <main id="view-plan" class="view-section active p-5">
        <div class="mb-6 muji-card p-4 text-sm space-y-2">
            <h2 class="text-sm font-bold text-muji-light mb-3"><i class="fa-solid fa-plane text-muji-accent mr-2"></i>航班 & 住宿</h2>
            <p><span class="bg-muji-border px-2 py-0.5 rounded text-xs mr-1">6/16去程</span> 06:50 桃園 ✈️ 09:20 那霸 (虎航 T230)</p>
            <p><span class="bg-muji-border px-2 py-0.5 rounded text-xs mr-1">6/20回程</span> 21:40 那霸 ✈️ 22:10 桃園 (虎航 T230)</p>
            <hr class="border-muji-border my-2">
            <p><span class="text-muji-accent font-medium">6/16-6/17</span> Hotel Peace Island Nago</p>
            <p><span class="text-muji-accent font-medium">6/18-6/20</span> Living Inn Asahibashi Station Annex</p>
        </div>

        <h2 class="text-lg font-medium mb-4 pl-1">每日行程</h2>
        <div class="space-y-6">
            <div class="relative border-l-2 border-muji-accent/30 ml-3 pl-5">
                <div class="absolute -left-[9px] top-0 w-4 h-4 rounded-full bg-muji-accent border-2 border-white"></div>
                <h3 class="font-bold text-lg mb-2">Day 1 <span class="text-muji-light text-sm font-normal ml-2">6/16 (日)・自駕</span></h3>
                <div class="muji-card p-3 text-sm">
                    <p class="text-muji-alert font-bold">09:20 抵達沖繩</p>
                    <p>OTS 租車 → 泊港魚市場(午) → 許田休息站(買門票) → 萬座毛 → 古宇利島心形岩</p>
                    <p class="text-muji-alert font-medium mt-1">15:00後 前往名護飯店 Check-in</p>
                    <div class="text-xs text-muji-light mt-2"><i class="fa-solid fa-utensils mr-1"></i>晚：阿古豬火鍋 (名護中山90)</div>
                </div>
            </div>
            
            <div class="relative border-l-2 border-muji-accent/30 ml-3 pl-5">
                <div class="absolute -left-[9px] top-0 w-4 h-4 rounded-full bg-muji-accent border-2 border-white"></div>
                <h3 class="font-bold text-lg mb-2">Day 2 <span class="text-muji-light text-sm font-normal ml-2">6/17 (一)・自駕</span></h3>
                <div class="muji-card p-3 text-sm">
                    <p class="text-muji-accent font-bold">08:30 美麗海水族館</p>
                    <p>14:00-19:00 Junglia Okinawa → 晚餐後自由活動</p>
                    <div class="text-xs text-muji-light mt-2"><i class="fa-solid fa-utensils mr-1"></i>午：Kaihomaru 2nd / 晚：燒肉五苑名護店</div>
                </div>
            </div>

            <div class="relative border-l-2 border-muji-accent/30 ml-3 pl-5">
                <div class="absolute -left-[9px] top-0 w-4 h-4 rounded-full bg-muji-accent border-2 border-white"></div>
                <h3 class="font-bold text-lg mb-2">Day 3 <span class="text-muji-light text-sm font-normal ml-2">6/18 (二)・轉市區</span></h3>
                <div class="muji-card p-3 text-sm">
                    <p class="text-muji-alert font-bold">11:00 前退房</p>
                    <p>美國村 → PARCO CITY → 那霸市區飯店 Check-in → 晚上自由活動</p>
                    <div class="text-xs text-muji-light mt-2"><i class="fa-solid fa-utensils mr-1"></i>午：PARCO CITY美食街 / 晚：Yuunangi</div>
                </div>
            </div>

            <div class="relative border-l-2 border-muji-accent/30 ml-3 pl-5">
                <div class="absolute -left-[9px] top-0 w-4 h-4 rounded-full bg-muji-accent border-2 border-white"></div>
                <h3 class="font-bold text-lg mb-2">Day 4 <span class="text-muji-light text-sm font-normal ml-2">6/19 (三)・還車</span></h3>
                <div class="muji-card p-3 text-sm">
                    <p class="text-muji-accent font-bold">09:00 玉泉洞</p>
                    <p>瀨長島 → ASHIBINAA Outlet</p>
                    <p class="text-muji-alert font-bold mt-1">19:00 前去 OTS 還車</p>
                    <div class="text-xs text-muji-light mt-2"><i class="fa-solid fa-utensils mr-1"></i>午：蕎蕎蕎 (南城市) / 晚：國際通居酒屋</div>
                </div>
            </div>

            <div class="relative border-l-2 border-transparent ml-3 pl-5">
                <div class="absolute -left-[9px] top-0 w-4 h-4 rounded-full bg-muji-accent border-2 border-white"></div>
                <h3 class="font-bold text-lg mb-2">Day 5 <span class="text-muji-light text-sm font-normal ml-2">6/20 (四)・電車</span></h3>
                <div class="muji-card p-3 text-sm">
                    <p class="text-muji-alert font-bold">10:00 前退房</p>
                    <p>第一牧志公設市場 → 國際通購物</p>
                    <p class="text-muji-accent font-bold mt-1">18:00 搭電車去那霸機場</p>
                    <p class="text-muji-alert font-bold mt-1">21:40 搭虎航 T230 離開</p>
                </div>
            </div>
        </div>
    </main>

    <main id="view-wallet" class="view-section p-5">
        <div class="muji-card p-4 mb-6 bg-muji-accent/5">
            <div class="flex justify-between items-center mb-3 text-sm font-bold">
                <span><i class="fa-solid fa-calculator mr-2 text-muji-accent"></i>匯率換算</span>
                <span>Rate: <input type="number" id="ex-rate" value="0.21" step="0.001" class="w-16 border rounded text-center"></span>
            </div>
            <div class="flex gap-2 mb-2">
                <input type="text" id="calc-input" placeholder="輸入算式 (如 500+200*2)" class="muji-input text-sm">
                <button onclick="executeCalc()" class="bg-muji-text text-white px-3 rounded-lg text-sm">=</button>
            </div>
            <div class="flex justify-between bg-white p-3 rounded border border-muji-border">
                <div id="calc-jpy" class="font-bold">¥ 0</div>
                <div id="calc-twd" class="font-bold text-muji-alert">NT$ 0</div>
            </div>
        </div>
        <div class="muji-card p-4">
            <input type="text" id="expense-item" placeholder="品項" class="muji-input mb-2">
            <input type="number" id="expense-price" placeholder="日幣金額" class="muji-input mb-2">
            <button onclick="addExpense()" class="muji-btn w-full">儲存</button>
        </div>
        <div id="expense-list" class="mt-6 space-y-3"></div>
    </main>

    <main id="view-lists" class="view-section p-5">
        <h2 class="font-medium mb-3">CheckList</h2>
        <div id="checklist-container" class="muji-card p-4 space-y-3 text-sm"></div>
        <h2 class="font-medium mt-6 mb-3">個人備忘錄</h2>
        <textarea id="memo-input" rows="4" class="muji-input text-sm mb-2" placeholder="在此輸入筆記..."></textarea>
        <button onclick="saveMemo()" class="muji-btn w-full mb-4">儲存</button>
        <div id="memo-display" class="bg-stone-50 p-3 rounded border border-muji-border text-sm whitespace-pre-wrap"></div>
    </main>

    <nav class="fixed bottom-0 w-full bg-white/95 backdrop-blur border-t border-muji-border flex justify-around pb-safe z-50">
        <button onclick="switchTab('plan')" class="nav-btn py-3 flex flex-col items-center w-1/3 text-muji-accent" data-target="view-plan">
            <i class="fa-solid fa-calendar-days text-xl"></i><span class="text-[10px]">行程</span>
        </button>
        <button onclick="switchTab('wallet')" class="nav-btn py-3 flex flex-col items-center w-1/3 text-muji-light" data-target="view-wallet">
            <i class="fa-solid fa-wallet text-xl"></i><span class="text-[10px]">記帳</span>
        </button>
        <button onclick="switchTab('lists')" class="nav-btn py-3 flex flex-col items-center w-1/3 text-muji-light" data-target="view-lists">
            <i class="fa-solid fa-clipboard-list text-xl"></i><span class="text-[10px]">清單</span>
        </button>
    </nav>

    <script>
        // --- Try-Catch 防護版儲存機制 ---
        function getStorage(key, defaultVal) {
            try { return JSON.parse(localStorage.getItem(key)) || defaultVal; }
            catch(e) { return defaultVal; }
        }
        function setStorage(key, val) {
            try { localStorage.setItem(key, JSON.stringify(val)); }
            catch(e) { 
                if(!window.warned) {
                    alert('【系統提示】您目前使用 iPhone 直接開啟檔案，蘋果安全機制會阻擋儲存功能。重整後記帳將會消失。請依照下方說明產生專屬網址。');
                    window.warned = true;
                }
            }
        }

        // --- 視圖切換邏輯 ---
        function switchTab(tabId) {
            document.querySelectorAll('.view-section').forEach(el => el.classList.remove('active'));
            document.getElementById('view-' + tabId).classList.add('active');
            document.querySelectorAll('.nav-btn').forEach(btn => btn.classList.replace('text-muji-accent', 'text-muji-light'));
            event.currentTarget.classList.replace('text-muji-light', 'text-muji-accent');
        }

        // --- 記帳功能 ---
        let expenses = getStorage('ok_expenses', []);

        function executeCalc() {
            const input = document.getElementById('calc-input').value;
            try {
                const res = Function('return ' + input.replace(/[^-()\d/*+.]/g, ''))();
                document.getElementById('calc-jpy').innerText = '¥ ' + Math.round(res);
                const rate = parseFloat(document.getElementById('ex-rate').value);
                document.getElementById('calc-twd').innerText = 'NT$ ' + Math.round(res * rate);
                document.getElementById('expense-price').value = Math.round(res);
            } catch(e) { alert('計算錯誤'); }
        }

        function addExpense() {
            const item = document.getElementById('expense-item').value;
            const jpy = parseInt(document.getElementById('expense-price').value);
            if(!item || isNaN(jpy)) return;
            const rate = parseFloat(document.getElementById('ex-rate').value);
            expenses.unshift({ id: Date.now(), item, jpy, twd: Math.round(jpy * rate) });
            setStorage('ok_expenses', expenses);
            renderExpenses();
            document.getElementById('expense-item').value = '';
            document.getElementById('expense-price').value = '';
        }

        function renderExpenses() {
            document.getElementById('expense-list').innerHTML = expenses.map(e => `
                <div class="muji-card p-3 flex justify-between items-center text-sm">
                    <div><div class="font-medium">${e.item}</div><div class="text-xs text-muji-light">¥${e.jpy}</div></div>
                    <div class="text-right"><div class="font-bold text-muji-alert">NT$${e.twd}</div>
                    <button onclick="deleteExp(${e.id})" class="text-xs text-stone-300">刪除</button></div>
                </div>
            `).join('');
        }
        function deleteExp(id) {
            expenses = expenses.filter(e => e.id !== id);
            setStorage('ok_expenses', expenses);
            renderExpenses();
        }

        // --- 清單與備忘錄 ---
        const defaultCheck = ["護照", "日幣現金", "網卡/eSIM", "日文譯本駕照", "行動電源", "常備藥品"];
        let savedCheck = getStorage('ok_checklist', {});
        
        function renderCheck() {
            document.getElementById('checklist-container').innerHTML = defaultCheck.map((t, i) => `
                <label class="flex items-center gap-2">
                    <input type="checkbox" onchange="toggleCheck(${i}, this.checked)" ${savedCheck[i]?'checked':''}>
                    <span class="${savedCheck[i]?'line-through text-muji-light':''}">${t}</span>
                </label>
            `).join('');
        }
        function toggleCheck(i, c) { savedCheck[i]=c; setStorage('ok_checklist', savedCheck); renderCheck(); }

        function saveMemo() { setStorage('ok_memo', document.getElementById('memo-input').value); renderMemo(); }
        function renderMemo() {
            const text = getStorage('ok_memo', '');
            document.getElementById('memo-input').value = text;
            document.getElementById('memo-display').innerHTML = text.replace(/(https?:\/\/[^\s]+)/g, '<a href="$1" target="_blank" class="text-muji-accent underline">開啟連結</a>');
        }

        // 初始執行
        renderExpenses(); renderCheck(); renderMemo();
    </script>
</body>
</html>
