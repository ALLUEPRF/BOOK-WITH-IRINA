<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>August 15 Travel Deals</title>
  <meta name="description" content="Hand-picked travel deals for August 15, 2025 – Panama, Canada, Thailand and more." />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;600;700;800&display=swap" rel="stylesheet">
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: { sans: ['Plus Jakarta Sans', 'ui-sans-serif', 'system-ui'] },
          colors: {
            brand: {
              50: '#ECFEFF', 100: '#CFFAFE', 200: '#A5F3FC', 300: '#67E8F9', 400: '#22D3EE',
              500: '#06B6D4', 600: '#0891B2', 700: '#0E7490', 800: '#155E75', 900: '#164E63'
            },
            accent: '#FFD447'
          }
        }
      }
    }
  </script>
  <style>
    .bg-hero {
      background: radial-gradient(1200px 600px at 10% 10%, rgba(255,212,71,.25), transparent 60%),
                  radial-gradient(1200px 600px at 90% 0%, rgba(6,182,212,.25), transparent 60%),
                  linear-gradient(180deg, #f8fafc, #ffffff);
    }
    .price-pop { animation: pop .5s ease both; }
    @keyframes pop { 0%{transform:scale(.95);opacity:0} 100%{transform:scale(1);opacity:1} }
    .badge-pulse { animation: pulse 2s cubic-bezier(0.4, 0, 0.6, 1) infinite; }
    .grid-auto-fill { grid-template-columns: repeat(auto-fill, minmax(280px, 1fr)); }
  </style>
</head>
<body class="bg-hero text-slate-800">
  <header class="sticky top-0 z-40 backdrop-blur bg-white/70 border-b border-slate-200">
    <div class="max-w-6xl mx-auto px-4 py-3 flex items-center justify-between">
      <div class="flex items-center gap-2">
        <span class="text-2xl">🌴</span>
        <h1 class="text-xl sm:text-2xl font-extrabold tracking-tight">August 15 Travel Deals</h1>
      </div>
      <a href="#contact" class="hidden sm:inline-flex items-center gap-2 px-3 py-2 text-sm font-semibold rounded-xl bg-brand-500 text-white shadow hover:bg-brand-600 transition">Book Now</a>
    </div>
  </header>

  <main class="max-w-6xl mx-auto px-4 py-6">
    <section class="mb-6">
      <div class="rounded-3xl p-6 md:p-8 bg-gradient-to-br from-brand-50 to-white border border-slate-200 shadow-sm">
        <div class="flex flex-col md:flex-row items-start md:items-center gap-4 md:gap-6">
          <div class="flex-1">
            <h2 class="text-2xl md:text-3xl font-extrabold mb-1">Today’s picks — <span id="today" class="text-brand-700">August 15, 2025</span></h2>
            <p class="text-slate-600">Hotel + Flight + Transfer unless noted. Prices in <strong>USD per person</strong>. Prices may change until booked.</p>
          </div>
          <div class="flex items-center gap-2">
            <label class="text-sm font-semibold">Filter:</label>
            <select id="destinationFilter" class="px-3 py-2 rounded-xl border bg-white">
              <option value="all">All destinations</option>
              <option value="Panama">Panama</option>
              <option value="Canada">Canada</option>
              <option value="Thailand">Thailand</option>
            </select>
            <select id="sortSelect" class="px-3 py-2 rounded-xl border bg-white">
              <option value="priceAsc">Sort: Price (Low → High)</option>
              <option value="priceDesc">Sort: Price (High → Low)</option>
              <option value="alpha">Sort: A → Z</option>
            </select>
          </div>
        </div>
      </div>
    </section>

    <section>
      <div id="dealsGrid" class="grid grid-auto-fill gap-4"></div>
    </section>

    <section id="contact" class="mt-10 mb-20">
      <div class="rounded-3xl p-6 md:p-8 bg-white border border-slate-200 shadow-sm flex flex-col md:flex-row items-center gap-6">
        <img src="https://api.iconify.design/solar/plane-bold.svg" alt="" class="w-16 h-16"/>
        <div class="flex-1">
          <h3 class="text-xl font-extrabold">Ready to lock in a deal?</h3>
          <p class="text-slate-600">Message to book now and secure today’s prices.</p>
        </div>
        <div class="text-center md:text-right">
          <p class="font-semibold">📞 1 (876) 583-9627</p>
          <p class="font-semibold">📧 besttravelagentrena@gmail.com</p>
        </div>
      </div>
    </section>
  </main>

  <footer class="border-t border-slate-200 py-8 text-center text-sm text-slate-500">
    <p>© <span id="year"></span> Travel Deals • Built for GitHub Pages</p>
  </footer>

  <script>
    const deals = [
      { destination:'Panama', title:'Dream Playa Bonita Panama', subtitle:'All-Inclusive · 2 adults', dates:'Oct 27–31, 2025', price:1005.88, includes:['flight','hotel','transfer'] },
      { destination:'Panama', title:'Hotel Terranova', dates:'Oct 27–31, 2025', price:583.70, includes:['flight','hotel','transfer'] },
      { destination:'Panama', title:'Sheraton Grand Panama', dates:'Oct 27–31, 2025', price:813.02, includes:['flight','hotel','transfer'] },
      { destination:'Panama', title:'Aloft Panama', dates:'Oct 27–31, 2025', price:740.02, includes:['flight','hotel','transfer'] },
      { destination:'Panama', title:'Ramada Plaza by Wyndham Panama Punta Pacifica', dates:'Oct 27–31, 2025', price:703.62, includes:['flight','hotel','transfer'] },
      { destination:'Panama', title:'AC Hotel by Marriott Panama City', subtitle:'With breakfast', dates:'Nov 24–28, 2025', price:764.53, includes:['flight','hotel','transfer'] },
      { destination:'Panama', title:'Aloft Panama', dates:'Nov 24–28, 2025', price:745.22, includes:['flight','hotel','transfer'] },
      { destination:'Panama', title:'Riu Plaza Panama', dates:'Nov 24–28, 2025', price:750.37, includes:['flight','hotel','transfer'] },
      { destination:'Panama', title:'Exe Oriental Panama', dates:'Nov 24–28, 2025', price:680.03, includes:['flight','hotel','transfer'] },
      { destination:'Panama', title:'Yoo Panama by Boutique Apartments', dates:'Nov 24–28, 2025', price:716.50, includes:['flight','hotel','transfer'] },
      { destination:'Canada', title:'Smithe House, Vancouver', dates:'Aug 2025', price:472.00, includes:['flight','hotel','transfer'] },
      { destination:'Canada', title:'The Laundry Rooms, Cambridge', dates:'Aug 2025', price:641.00, includes:['flight','hotel','transfer'] },
      { destination:'Canada', title:'1 Hotel Toronto', dates:'Aug 2025', price:1218.00, includes:['flight','hotel','transfer'] },
      { destination:'Canada', title:'Summit Lodge Boutique Hotel (Whistler)', dates:'Aug 2025', price:945.00, includes:['flight','hotel','transfer'] },
      { destination:'Thailand', title:'Hope Land Hotel Sukhumvit 46/1, Bangkok', dates:'Aug 2025', price:260.00, includes:['flight','hotel','transfer'] },
      { destination:'Thailand', title:'Klub Hotel, Bangkok', dates:'Aug 2025', price:295.00, includes:['flight','hotel','transfer'] },
      { destination:'Thailand', title:'Hotel Icon Bangkok Sukhumvit 2', dates:'Aug 2025', price:336.00, includes:['flight','hotel','transfer'] },
      { destination:'Thailand', title:'Centre Point Plus Hotel Pratunam, Bangkok', dates:'Aug 2025', price:483.00, includes:['flight','hotel','transfer'] }
    ];

    const icons = { flight: '✈️', hotel: '🏨', transfer: '🚐' };

    function renderDeals(list){
      const grid = document.getElementById('dealsGrid');
      grid.innerHTML = '';
      list.forEach(d => {
        const includes = (d.includes||[]).map(k=>`<span class="inline-flex items-center gap-1 text-xs px-2 py-1 rounded-full bg-slate-100 border"><span>${icons[k]||''}</span><span class="uppercase tracking-wide">${k}</span></span>`).join(' ');
        const price = `<span class="text-2xl font-extrabold">$${Number(d.price).toLocaleString(undefined,{minimumFractionDigits:2, maximumFractionDigits:2})}</span>`;
        const badge = '<span class="badge-pulse inline-flex items-center px-2 py-1 text-[10px] font-bold rounded-full bg-accent text-slate-900">BOOK NOW</span>';
        grid.insertAdjacentHTML('beforeend', `
          <article class="price-pop group rounded-3xl overflow-hidden border border-slate-200 bg-white shadow-sm hover:shadow-md transition">
            <div class="p-5 flex flex-col gap-3">
              <div class="flex items-center justify-between gap-2">
                <span class="text-xs font-bold tracking-wide text-brand-700 bg-brand-100 px-2 py-1 rounded-full">${d.destination}</span>
                ${badge}
              </div>
              <h3 class="text-lg font-extrabold leading-tight">${d.title}</h3>
              ${d.subtitle ? `<p class="text-sm text-slate-600">${d.subtitle}</p>` : ''}
              <p class="text-sm text-slate-700">${d.dates}</p>
              <div class="flex items-center justify-between mt-1">
                <div class="flex flex-wrap gap-2">${includes}</div>
                <div class="text-right">${price}</div>
              </div>
            </div>
          </article>
        `);
      })
    }

    function applyFilters(){
      const dest = document.getElementById('destinationFilter').value;
      const sort = document.getElementById('sortSelect').value;
      let list = deals.filter(d => dest==='all' ? true : d.destination===dest);
      if (sort==='priceAsc') list = list.slice().sort((a,b)=> a.price - b.price);
      if (sort==='priceDesc') list = list.slice().sort((a,b)=> b.price - a.price);
      if (sort==='alpha') list = list.slice().sort((a,b)=> a.title.localeCompare(b.title));
      renderDeals(list);
    }

    document.getElementById('destinationFilter').addEventListener('change', applyFilters);
    document.getElementById('sortSelect').addEventListener('change', applyFilters);

    document.getElementById('year').textContent = new Date().getFullYear();
    document.getElementById('today').textContent = new Date().toLocaleDateString(undefined, { year:'numeric', month:'long', day:'numeric'});
    applyFilters();
  </script>
</body>
</html>
