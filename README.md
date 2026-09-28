# utkualbayrak.dev

🇬🇧 [English](#english) · 🇹🇷 [Türkçe](#türkçe)

---

## English

My CV, as a website from 1999.

### Why?

I spend my days building enterprise Angular apps: micro-frontends, NX monorepos, Module Federation, NgRx, WebSockets, build pipelines. That's the job, and I like it. But a CV is a single page of text. It doesn't need a framework, a bundler or 400 MB of `node_modules`.

So this site is one HTML file. No framework, no build step, no dependencies. It opens instantly, works everywhere, and will still work in twenty years.

And since the page was going to be old-school anyway, I went all the way: an "under construction" banner, a rainbow name, `<marquee>`, a blinking "NEW!" badge, a scrolling title bar, a cursor sparkle trail and a fake visitor counter. The things we all put on our first homepages.

It's a small joke, but there's a real point underneath: knowing a lot of tools also means knowing when not to use them.

### Features

- A single `index.html` with inline CSS and a little vanilla JavaScript
- Every classic 90s effect you remember, and some you tried to forget
- A **"Turn off the chaos"** button for people who actually want to read the CV
- A **"another dark mode btn"** button, because it's 2026 after all
- Respects `prefers-reduced-motion`: if your system asks for less motion, the page starts calm
- Responsive, readable on phones, and works in light and dark mode

### Run it locally

Open `index.html` in a browser. That's it.

### The honest part

The page itself has no build step. Deploying it to Cloudflare, however, needed a pile of `.json` and `.js` files. I tried to escape JavaScript. JavaScript found me anyway. The footnote on the site admits this too.

---

## Türkçe

CV'm, 1999'dan kalma bir web sitesi olarak.

### Neden?

Günlerim kurumsal Angular uygulamaları geliştirmekle geçiyor: micro-frontend'ler, NX monorepo'lar, Module Federation, NgRx, WebSocket'ler, build pipeline'ları. İşim bu ve seviyorum. Ama bir CV tek sayfalık bir metin. Framework'e, bundler'a ya da 400 MB'lık `node_modules` klasörüne ihtiyacı yok.

O yüzden bu site tek bir HTML dosyası. Framework yok, build adımı yok, bağımlılık yok. Anında açılıyor, her yerde çalışıyor ve yirmi yıl sonra da çalışmaya devam edecek.

Madem sayfa eski usul olacaktı, sonuna kadar gittim: "yapım aşamasında" şeridi, gökkuşağı renkli isim, `<marquee>`, yanıp sönen "NEW!" etiketi, kayan sekme başlığı, imleci takip eden yıldızlar ve sahte ziyaretçi sayacı. Hepimizin ilk ana sayfasına koyduğu şeyler.

Küçük bir şaka ama altında gerçek bir fikir var: çok araç bilmek, ne zaman kullanmayacağını da bilmek demek.

### Özellikler

- Satır içi CSS ve biraz vanilla JavaScript içeren tek bir `index.html`
- Hatırladığın bütün klasik 90'lar efektleri, bir de unutmaya çalıştıkların
- CV'yi gerçekten okumak isteyenler için **"Turn off the chaos"** butonu
- 2026'dayız sonuçta, o yüzden bir de **"another dark mode btn"** butonu
- `prefers-reduced-motion` ayarına uyuyor: sistemin daha az hareket istiyorsa sayfa sakin açılıyor
- Mobil uyumlu, telefonda okunaklı, açık ve koyu temada çalışıyor

### Yerelde çalıştırmak

`index.html` dosyasını tarayıcıda aç. Bu kadar.

### İtiraf kısmı

Sayfanın kendisinin build adımı yok. Ama Cloudflare'e deploy etmek için bir sürü `.json` ve `.js` dosyası gerekti. JavaScript'ten kaçmaya çalıştım. JavaScript beni yine buldu. Sitedeki dipnot da bunu itiraf ediyor.