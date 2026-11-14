<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<meta name="theme-color" content="#7A1C1C">
<title>Royal Rajasthani Thali Restaurant – Koramangala, Bengaluru</title>
<meta name="description" content="A royal Rajasthani feast in the heart of Koramangala. Pure vegetarian & Jain thali. Reserve your table on WhatsApp.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600;700;800&family=Plus+Jakarta+Sans:wght@400;500;600;700&display=swap" rel="stylesheet">
<script src="https://cdn.tailwindcss.com"></script>
<script>
tailwind.config={theme:{extend:{colors:{maroon:'#7A1C1C',saffron:'#D97706',sand:'#FDF8F2',char:'#1F2937'},
fontFamily:{serif:['"Playfair Display"','Georgia','serif'],sans:['"Plus Jakarta Sans"','system-ui','sans-serif']}}}}
</script>
<style>
html{scroll-behavior:smooth}
body{font-family:"Plus Jakarta Sans",system-ui,sans-serif;background:#FDF8F2;color:#1F2937;overflow-x:hidden}
@media (prefers-reduced-motion:reduce){html{scroll-behavior:auto}*{animation:none!important;transition:none!important}}
.glass{background:rgba(253,248,242,.78);backdrop-filter:blur(14px);-webkit-backdrop-filter:blur(14px);border-bottom:1px solid rgba(122,28,28,.12)}
.pattern{background-color:#7A1C1C;background-image:radial-gradient(circle at 1px 1px,rgba(217,119,6,.28) 1px,transparent 0),linear-gradient(160deg,#8f2424,#5e1212);background-size:22px 22px,100% 100%}
.chip{border:1.5px solid #e7d6c2;background:#fff;border-radius:.75rem;padding:.55rem .6rem;min-height:44px;font-size:.875rem;font-weight:600;transition:all .15s}
.chip:hover:not(:disabled){border-color:#D97706}
.chip[aria-pressed="true"]{background:#7A1C1C;border-color:#7A1C1C;color:#fff}
.chip:disabled{opacity:.35;text-decoration:line-through;cursor:not-allowed}
.field{width:100%;background:#fff;border:1.5px solid #e7d6c2;border-radius:.75rem;padding:.75rem 1rem;font-size:16px;min-height:48px;outline:none}
.field:focus{border-color:#D97706;box-shadow:0 0 0 3px rgba(217,119,6,.2)}
.lbl{display:block;font-size:.72rem;font-weight:700;letter-spacing:.09em;text-transform:uppercase;color:#7A1C1C;margin-bottom:.45rem}
.card{background:#fff;border:1px solid #efe1cf;border-radius:1.25rem;box-shadow:0 6px 24px rgba(122,28,28,.06)}
.ticket{background:#fff;border:2px dashed #D97706;border-radius:1rem}
.fade{animation:fade .5s ease}@keyframes fade{from{opacity:0;transform:translateY(6px)}to{opacity:1;transform:none}}
</style>
</head>
<body>

<header class="sticky top-0 z-40 glass" style="padding-top:env(safe-area-inset-top)">
  <div class="max-w-6xl mx-auto flex items-center justify-between px-4 py-3">
    <a href="#top" class="font-serif font-bold text-maroon text-base sm:text-lg leading-tight">Royal Rajasthani <span class="text-saffron">Thali</span></a>
    <nav class="hidden md:flex items-center gap-6 text-sm font-semibold">
      <a href="#menu" class="hover:text-saffron">Menu &amp; Pricing</a><a href="#heritage" class="hover:text-saffron">Heritage Experience</a>
      <a href="#location" class="hover:text-saffron">Location</a><a href="#book" class="hover:text-saffron">Book Table</a>
    </nav>
    <div class="flex items-center gap-2">
      <a href="#book" class="rounded-lg bg-maroon text-white text-sm font-bold px-4 py-2.5">Book via WhatsApp</a>
      <button id="menuBtn" class="md:hidden w-11 h-11 rounded-lg border border-maroon/20 text-maroon" aria-label="Open menu" aria-expanded="false">☰</button>
    </div>
  </div>
  <div id="mobileNav" class="hidden md:hidden px-4 pb-3 grid gap-1 text-sm font-semibold">
    <a class="py-2" href="#menu">Menu &amp; Pricing</a><a class="py-2" href="#heritage">Heritage Experience</a>
    <a class="py-2" href="#location">Location</a><a class="py-2" href="#book">Book Table</a>
  </div>
</header>

<main id="top">
<section class="pattern text-white">
  <div class="max-w-6xl mx-auto px-4 py-14 md:py-24 grid md:grid-cols-5 gap-10 items-center">
    <div class="md:col-span-3">
      <div class="flex flex-wrap gap-2 text-xs font-bold mb-5">
        <span class="bg-saffron text-white rounded-full px-3 py-1.5">★ 4.7 · 1,355+ Google Reviews</span>
        <span class="bg-white/15 rounded-full px-3 py-1.5">📍 Koramangala 7th Block</span>
        <span id="status" class="bg-white/15 rounded-full px-3 py-1.5">…</span>
      </div>
      <h1 class="font-serif font-extrabold text-4xl sm:text-5xl leading-tight">Royal Rajasthani Thali Restaurant</h1>
      <p class="mt-4 text-lg sm:text-xl text-amber-100 font-serif italic">“A Royal Rajasthani Feast in the Heart of Koramangala”</p>
      <p class="mt-3 text-white/80 max-w-xl">100% pure vegetarian Rajasthani &amp; Jain cuisine, with masalas and atta ground in-house.</p>
      <a href="#book" class="inline-block mt-7 rounded-xl bg-saffron px-7 py-4 font-bold shadow-lg active:scale-[.98] transition">Reserve Your Royal Thali</a>
    </div>
    <div class="md:col-span-2 flex justify-center">
      <div class="w-56 sm:w-64 border-4 border-saffron rounded-t-full px-6 pt-14 pb-8 text-center bg-black/10">
        <div class="font-serif text-5xl font-extrabold text-amber-200">4.7★</div>
        <div class="text-sm mt-1 text-white/80">from 1,355+ guests</div>
        <div class="mt-4 text-2xl">🪔</div>
        <div class="font-serif italic mt-1 text-amber-100">Padharo Mhare Desh</div>
      </div>
    </div>
  </div>
</section>

<section class="bg-white border-b border-amber-100">
  <ul class="max-w-6xl mx-auto px-4 py-4 flex flex-wrap justify-center gap-x-6 gap-y-2 text-sm font-semibold text-maroon">
    <li>🌿 Pure Vegetarian</li><li>🙏 Jain Food Available</li><li>🪑 Baithak &amp; Regular Seating</li>
    <li>🧒 Kid-friendly</li><li>♿ Step-free Entry</li><li>📶 Free Wi-Fi</li>
  </ul>
</section>

<section id="menu" class="max-w-6xl mx-auto px-4 py-14 scroll-mt-20">
  <div class="text-center mb-8">
    <p class="lbl">Menu &amp; Pricing</p>
    <h2 class="font-serif text-3xl sm:text-4xl font-bold text-maroon">Unlimited Thali, Served with Love</h2>
    <p id="todayNote" class="mt-2 text-char/70"></p>
  </div>
  <div id="thalis" class="grid sm:grid-cols-2 lg:grid-cols-3 gap-4"></div>
  <div class="card mt-6 p-6 text-center">
    <p class="lbl">Signature highlights</p>
    <p class="font-serif text-lg">Ghee-drenched Dal Baati Churma · Gatte ki Sabzi · Ker Sangri · Panchmukhi Dal · Kadhi Pakora · Moong Dal Halwa · Boondi Chaach</p>
    <span class="inline-block mt-3 bg-green-100 text-green-800 text-xs font-bold rounded-full px-3 py-1.5">🙏 Jain Food Available</span>
    <p class="mt-3 text-xs text-char/60">All prices are exclusive of GST.</p>
  </div>
</section>

<section id="heritage" class="pattern text-white scroll-mt-20">
  <div class="max-w-6xl mx-auto px-4 py-14 grid md:grid-cols-3 gap-4">
    <div class="md:col-span-3 text-center mb-2"><p class="text-amber-200 text-xs font-bold tracking-widest uppercase">Heritage Experience</p>
      <h2 class="font-serif text-3xl sm:text-4xl font-bold mt-1">Dine Like Rajasthani Royalty</h2></div>
    <div class="bg-white/10 rounded-2xl p-6"><div class="text-3xl">🪑</div><h3 class="font-serif text-xl font-bold mt-2">Baithak Floor Seating</h3><p class="text-white/80 text-sm mt-1">Sit cross-legged the traditional way, or choose a regular table. Both are available.</p></div>
    <div class="bg-white/10 rounded-2xl p-6"><div class="text-3xl">🫓</div><h3 class="font-serif text-xl font-bold mt-2">Ground In-house</h3><p class="text-white/80 text-sm mt-1">Masalas and atta are ground in-house for the flavours of a Rajasthani home kitchen.</p></div>
    <div class="bg-white/10 rounded-2xl p-6"><div class="text-3xl">🙏</div><h3 class="font-serif text-xl font-bold mt-2">Warm Hospitality</h3><p class="text-white/80 text-sm mt-1">Hot rotis, ghee and refills keep coming until you say enough.</p></div>
  </div>
</section>

<section id="book" class="max-w-6xl mx-auto px-4 py-14 scroll-mt-20">
  <div class="text-center mb-8">
    <p class="lbl">Table Reservation</p>
    <h2 class="font-serif text-3xl sm:text-4xl font-bold text-maroon">Book Your Table on WhatsApp</h2>
    <p class="mt-2 text-char/70">Fill in the details and your booking opens on WhatsApp, ready to send.</p>
  </div>
  <div class="grid lg:grid-cols-5 gap-6 items-start">
    <form id="form" class="card p-5 sm:p-7 space-y-5 lg:col-span-3" novalidate>
      <div class="grid sm:grid-cols-2 gap-4">
        <div><label class="lbl" for="name">Guest name *</label><input id="name" class="field" autocomplete="name" maxlength="60" placeholder="e.g. Ananya Rao"></div>
        <div><label class="lbl" for="phone">Phone number *</label><input id="phone" class="field" type="tel" inputmode="numeric" autocomplete="tel" maxlength="15" placeholder="10-digit mobile number"></div>
      </div>
      <div><label class="lbl" for="date">Reservation date *</label><input id="date" class="field" type="date"></div>
      <div><span class="lbl">Meal session *</span><div id="session" class="grid grid-cols-2 gap-2"></div></div>
      <div><span class="lbl">Time slot *</span><div id="slots" class="grid grid-cols-4 gap-2"></div></div>
      <div><span class="lbl">Number of guests</span><div id="guests" class="grid grid-cols-3 sm:grid-cols-6 gap-2"></div></div>
      <div><span class="lbl">Seating preference</span><div id="seat" class="grid grid-cols-1 sm:grid-cols-2 gap-2"></div></div>
      <div><span class="lbl">Dietary / occasion (optional)</span><div id="tags" class="flex flex-wrap gap-2"></div></div>
      <div><label class="lbl" for="notes">Anything else? (optional)</label><textarea id="notes" class="field" rows="2" maxlength="250" placeholder="Allergies, high chair, cake arrangement…"></textarea></div>
      <p id="err" class="hidden text-sm font-semibold text-red-700 bg-red-50 border border-red-200 rounded-xl px-4 py-3" role="alert"></p>
      <button type="submit" class="w-full rounded-xl bg-[#25D366] text-[#052e16] font-bold py-4 shadow-lg active:scale-[.99] transition">Confirm &amp; Send on WhatsApp</button>
      <button type="button" id="copyBtn" class="w-full rounded-xl border-2 border-maroon text-maroon font-bold py-3.5">Copy Booking Details</button>
      <p id="note" class="text-center text-sm min-h-[1.25rem]" aria-live="polite"></p>
    </form>
    <aside class="lg:col-span-2 lg:sticky lg:top-24">
      <div class="ticket p-5" aria-live="polite">
        <p class="lbl">Live booking summary</p>
        <pre id="summary" class="whitespace-pre-wrap break-words font-sans text-sm leading-relaxed"></pre>
      </div>
      <p class="text-xs text-char/60 mt-3 text-center">Your table is confirmed once the restaurant replies on WhatsApp.</p>
    </aside>
  </div>
</section>

<section class="bg-white py-14">
  <div class="max-w-3xl mx-auto px-4 text-center">
    <p class="lbl">Guest Reviews</p>
    <h2 class="font-serif text-3xl sm:text-4xl font-bold text-maroon">Loved by Koramangala</h2>
    <div class="card mt-8 p-7 min-h-[200px] flex flex-col justify-center" aria-live="off">
      <div id="rev" class="fade"></div>
    </div>
    <div class="mt-4 flex items-center justify-center gap-3">
      <button id="prev" class="w-11 h-11 rounded-full border border-maroon/30 text-maroon" aria-label="Previous review">‹</button>
      <div id="dots" class="flex gap-2"></div>
      <button id="next" class="w-11 h-11 rounded-full border border-maroon/30 text-maroon" aria-label="Next review">›</button>
    </div>
  </div>
</section>

<section id="location" class="max-w-6xl mx-auto px-4 py-14 scroll-mt-20 grid md:grid-cols-2 gap-4">
  <div class="card p-7">
    <p class="lbl">Find us</p><h2 class="font-serif text-2xl font-bold text-maroon">Location &amp; Contact</h2>
    <address class="not-italic mt-3 text-char/80">Royal Rajasthani Thali Restaurant<br>4, 80 Feet Rd, KHB Colony, 7th Block,<br>Koramangala, Bengaluru, Karnataka 560095</address>
    <p class="mt-3">📞 <a class="font-semibold underline" href="tel:+917337877282">+91 73378 77282</a></p>
    <div class="mt-5 grid grid-cols-2 gap-3">
      <a class="text-center rounded-xl bg-maroon text-white font-bold py-3" target="_blank" rel="noopener" href="https://www.google.com/maps/search/?api=1&query=Royal%20Rajasthani%20Thali%20Restaurant%2080%20Feet%20Rd%20KHB%20Colony%20Koramangala%20Bengaluru">Get Directions</a>
      <a class="text-center rounded-xl border-2 border-maroon text-maroon font-bold py-3" href="tel:+917337877282">Call Now</a>
    </div>
  </div>
  <div class="card p-7">
    <p class="lbl">Opening hours</p><h2 class="font-serif text-2xl font-bold text-maroon">Open Every Day</h2>
    <ul class="mt-4 text-sm divide-y divide-amber-100">
      <li class="flex justify-between py-3"><span>🍛 Lunch</span><b>12:00 PM – 4:00 PM</b></li>
      <li class="flex justify-between py-3"><span>🌙 Dinner</span><b>7:00 PM – 11:00 PM</b></li>
      <li class="flex justify-between py-3"><span>Days</span><b>Monday – Sunday</b></li>
    </ul>
  </div>
</section>
</main>

<footer class="bg-maroon text-white/80 text-center text-sm px-4 pt-8 pb-24">
  <p class="font-serif text-lg text-amber-200">Padharo Mhare Desh 🙏</p>
  <p class="mt-1">© <span id="yr"></span> Royal Rajasthani Thali Restaurant · Koramangala, Bengaluru</p>
</footer>

<a id="fab" href="https://wa.me/917337877282" target="_blank" rel="noopener" aria-label="Chat on WhatsApp"
   class="fixed right-4 z-50 w-14 h-14 rounded-full bg-[#25D366] text-[#052e16] shadow-xl flex items-center justify-center text-2xl"
   style="bottom:calc(1rem + env(safe-area-inset-bottom))">💬</a>

<script>
(() => {
  const WA = '917337877282', $ = s => document.querySelector(s), pad = n => String(n).padStart(2, '0');
  const iso = d => `${d.getFullYear()}-${pad(d.getMonth() + 1)}-${pad(d.getDate())}`;
  const fmt = m => { const h = Math.floor(m / 60); return `${h % 12 || 12}:${pad(m % 60)} ${h >= 12 ? 'PM' : 'AM'}`; };
  const rng = (a, z) => { const r = []; for (let m = a; m <= z; m += 30) r.push(m); return r; };
  const SLOTS = { Lunch: rng(720, 930), Dinner: rng(1140, 1350) };
  const st = { session: 'Lunch', time: '', guests: '2', seat: 'Regular Table', tags: [] };

  // Menu nav + footer
  $('#menuBtn').onclick = e => { const o = $('#mobileNav').classList.toggle('hidden'); e.currentTarget.setAttribute('aria-expanded', !o); };
  $('#mobileNav').addEventListener('click', e => { if (e.target.tagName === 'A') $('#mobileNav').classList.add('hidden'); });
  $('#yr').textContent = new Date().getFullYear();

  // Open/closed status
  (() => {
    const n = new Date(), m = n.getHours() * 60 + n.getMinutes(); let t;
    if (m >= 720 && m < 960) t = '🟢 Lunch open · till 4:00 PM';
    else if (m >= 1140 && m < 1380) t = '🟢 Dinner open · till 11:00 PM';
    else if (m < 720) t = '🟠 Lunch opens at 12:00 PM';
    else if (m < 1140) t = '🟠 Dinner opens at 7:00 PM';
    else t = '🔴 Closed · lunch opens 12:00 PM';
    $('#status').textContent = t;
  })();

  // Thali cards (0 = Sunday)
  const dow = new Date().getDay(), dn = ['Sunday', 'Monday', 'Tuesday', 'Wednesday', 'Thursday', 'Friday', 'Saturday'][dow];
  const THALIS = [
    ['Weekday Unlimited Thali', 'Mon · Wed · Thu', '₹499', [1, 3, 4], '🍛'],
    ['Weekend Royal Feast Thali', 'Fri · Sat · Sun', '₹699', [5, 6, 0], '👑'],
    ['Tuesday Special Thali', 'Every Tuesday', '₹399', [2], '✨'],
    ['Women’s Wednesday Offer', 'Wednesday · Lunch & Dinner', '₹399', [3], '🌸'],
    ['Kids’ Thali', 'Ages 6–10', '₹399', [], '🧒']
  ];
  $('#thalis').innerHTML = THALIS.map(([n, d, p, days, ic]) => `
    <article class="card p-6 ${days.includes(dow) ? 'ring-2 ring-saffron' : ''}">
      <div class="flex justify-between items-start"><span class="text-3xl">${ic}</span>
        ${days.includes(dow) ? '<span class="text-[11px] font-bold bg-saffron text-white rounded-full px-2.5 py-1">TODAY</span>' : ''}</div>
      <h3 class="font-serif text-xl font-bold text-maroon mt-3">${n}</h3>
      <p class="text-sm text-char/60">${d}</p>
      <p class="mt-3"><span class="font-serif text-3xl font-bold text-saffron">${p}</span> <span class="text-sm text-char/60">+ GST</span></p>
    </article>`).join('');
  $('#todayNote').textContent = `Today is ${dn}. Highlighted cards apply today.`;

  // Chips
  function chips(box, items, key, multi) {
    const el = $(box); el.innerHTML = '';
    items.forEach(v => {
      const b = document.createElement('button'); b.type = 'button'; b.className = 'chip'; b.textContent = v; b.dataset.v = v;
      const on = () => multi ? st[key].includes(v) : st[key] === v; b.setAttribute('aria-pressed', on());
      b.onclick = () => {
        if (multi) {
          if (v === 'None') st[key] = []; else st[key] = st[key].includes(v) ? st[key].filter(x => x !== v) : [...st[key], v];
          el.querySelectorAll('.chip').forEach(c => c.setAttribute('aria-pressed', c.dataset.v === 'None' ? st[key].length === 0 : st[key].includes(c.dataset.v)));
        } else { st[key] = v; el.querySelectorAll('.chip').forEach(c => c.setAttribute('aria-pressed', c.dataset.v === v)); }
        if (key === 'session') { st.time = ''; slots(); }
        summary();
      };
      el.appendChild(b);
    });
  }
  const dateEl = $('#date'), t0 = new Date(), mx = new Date(t0); mx.setDate(mx.getDate() + 60);
  dateEl.min = iso(t0); dateEl.max = iso(mx); dateEl.value = iso(t0);
  if (t0.getHours() * 60 + t0.getMinutes() > 870) st.session = 'Dinner';

  function slots() {
    const n = new Date(), today = dateEl.value === iso(n), nm = n.getHours() * 60 + n.getMinutes(), box = $('#slots'); box.innerHTML = '';
    SLOTS[st.session].forEach(m => {
      const l = fmt(m), b = document.createElement('button'); b.type = 'button'; b.className = 'chip'; b.textContent = l;
      b.disabled = today && m <= nm + 30; if (b.disabled && st.time === l) st.time = '';
      b.setAttribute('aria-pressed', st.time === l);
      b.onclick = () => { st.time = l; box.querySelectorAll('.chip').forEach(c => c.setAttribute('aria-pressed', c.textContent === l)); summary(); };
      box.appendChild(b);
    });
  }
  chips('#session', ['Lunch', 'Dinner'], 'session');
  chips('#guests', ['1', '2', '4', '6', '8', '10+ Group'], 'guests');
  chips('#seat', ['Regular Table', 'Rajasthani Floor Seating (Baithak)'], 'seat');
  chips('#tags', ['Jain Thali Needed', 'Birthday / Anniversary', 'Women’s Wednesday Offer', 'None'], 'tags', true);
  $('#tags [data-v="None"]').setAttribute('aria-pressed', 'true');
  slots();
  dateEl.onchange = () => { slots(); summary(); };

  // Message + summary
  const clean = () => { let p = $('#phone').value.replace(/\D/g, ''); if (p.length === 12 && p.startsWith('91')) p = p.slice(2); if (p.length === 11 && p[0] === '0') p = p.slice(1); return p; };
  const dstr = () => { if (!dateEl.value) return '—'; const [y, m, d] = dateEl.value.split('-').map(Number); return new Date(y, m - 1, d).toLocaleDateString('en-IN', { weekday: 'short', day: 'numeric', month: 'short', year: 'numeric' }); };
  function message() {
    const notes = $('#notes').value.trim(), tg = st.tags.join(', ');
    return [
      '🙏 *Table Reservation Request*',
      '🏰 *Royal Rajasthani Thali Restaurant*, Koramangala', '',
      `👤 *Name:* ${$('#name').value.trim() || '—'}`,
      `📞 *Phone:* ${clean() ? '+91 ' + clean() : '—'}`,
      `📅 *Date:* ${dstr()}`,
      `🍽️ *Session:* ${st.session}`,
      `⏰ *Time:* ${st.time || '—'}`,
      `👥 *Guests:* ${st.guests}`,
      `🪑 *Seating:* ${st.seat}`,
      `🏷️ *Preferences:* ${tg || 'None'}`,
      `📝 *Notes:* ${notes || 'None'}`, '',
      'Kindly confirm my table. Dhanyavaad! 🙏'
    ].join('\n');
  }
  function summary() { $('#summary').textContent = message().replace(/\*/g, ''); }
  ['#name', '#phone', '#notes'].forEach(s => $(s).addEventListener('input', summary));
  summary();

  // Validate
  const err = $('#err');
  function valid() {
    err.classList.add('hidden');
    const bad = m => { err.textContent = m; err.classList.remove('hidden'); err.scrollIntoView({ behavior: 'smooth', block: 'center' }); return false; };
    if ($('#name').value.trim().length < 2) return bad('Please enter the guest name.');
    if (!/^[6-9]\d{9}$/.test(clean())) return bad('Please enter a valid 10-digit Indian mobile number.');
    if (!dateEl.value || dateEl.value < dateEl.min) return bad('Please choose today’s date or a future date.');
    if (!st.time) return bad('Please pick a time slot.');
    return true;
  }
  $('#form').addEventListener('submit', e => {
    e.preventDefault(); if (!valid()) return;
    const url = `https://wa.me/${WA}?text=${encodeURIComponent(message())}`;
    const w = window.open(url, '_blank', 'noopener');
    $('#note').innerHTML = w ? 'Opening WhatsApp… tap Send there to finish.' : `Popup blocked. <a class="underline font-bold text-maroon" target="_blank" rel="noopener" href="${url}">Tap here to open WhatsApp</a>`;
  });
  $('#copyBtn').onclick = async () => {
    const txt = message().replace(/\*/g, ''); let ok = false;
    try { await navigator.clipboard.writeText(txt); ok = true; } catch (_) {
      const t = document.createElement('textarea'); t.value = txt; t.style.cssText = 'position:fixed;opacity:0'; document.body.appendChild(t); t.select();
      try { ok = document.execCommand('copy'); } catch (_) {} t.remove();
    }
    $('#note').textContent = ok ? 'Booking details copied.' : 'Could not copy. Please select the summary and copy it.';
  };

  // Reviews carousel. REPLACE these with real Google reviews before going live.
  const REV = [
    ['The ghee-soaked Dal Baati Churma was unreal, and the staff kept serving with a smile. Padharo Mhare Desh is felt here.', 'Priya S.'],
    ['Sat on the floor Baithak style with family. Spotless, calm ambience and food that tastes like home.', 'Rahul M.'],
    ['Ker Sangri and Gatte ki Sabzi were spot on. They arranged a Jain thali for my parents without any fuss.', 'Neha J.'],
    ['Weekend feast thali is worth every rupee. The Moong Dal Halwa at the end made my day.', 'Karthik V.'],
    ['Kid-friendly and easy to enter with a stroller. Our little one loved the kids’ thali.', 'Divya R.']
  ];
  let ri = 0, timer;
  const show = i => {
    ri = (i + REV.length) % REV.length; const [q, n] = REV[ri], el = $('#rev');
    el.classList.remove('fade'); void el.offsetWidth; el.classList.add('fade');
    el.innerHTML = `<div class="text-saffron text-xl">★★★★★</div><p class="font-serif text-lg sm:text-xl mt-3">“${q}”</p><p class="mt-3 text-sm font-semibold text-maroon">${n} · Dine-in guest</p>`;
    $('#dots').innerHTML = REV.map((_, k) => `<button class="w-2.5 h-2.5 rounded-full ${k === ri ? 'bg-maroon' : 'bg-maroon/25'}" aria-label="Review ${k + 1}" data-k="${k}"></button>`).join('');
  };
  const auto = () => { clearInterval(timer); timer = setInterval(() => show(ri + 1), 6000); };
  $('#prev').onclick = () => { show(ri - 1); auto(); }; $('#next').onclick = () => { show(ri + 1); auto(); };
  $('#dots').onclick = e => { if (e.target.dataset.k) { show(+e.target.dataset.k); auto(); } };
  show(0); auto();
})();
</script>
</body>
</html>