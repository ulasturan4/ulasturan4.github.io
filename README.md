
# Academic Site Starter (Static HTML/CSS)

Bu proje, GitHub Pages üzerinde **hiçbir ek araç kurmadan** çalışır.

## Yayınlama — GitHub Pages (en kolay)

1) GitHub'da bir repo açın. Öneri ad: `KULLANICIADINIZ.github.io` (kendi kullanıcı adınızla).
2) Bu klasörün içeriğini **Upload files** ile repoya yükleyin.
3) Repo **Settings → Pages** → Build and deployment: *Deploy from a branch*.
4) Branch: `main` ve Folder: `/ (root)` seçin.
5) Sayfa birkaç dakika içinde `https://KULLANICIADINIZ.github.io` adresinden yayında olur.

## Özel Alan Adı (isteğe bağlı)
- Domain sağlayıcınızdan bir alan adı alın (örn. `adiniz.dev`).
- GitHub Pages ayarlarında **Custom domain** bölümünden ekleyin.
- DNS’te `CNAME` kaydı eklemeyi unutmayın (hedef: `KULLANICIADINIZ.github.io`).

## İçerik Düzenleme
- `index.html`: Ana sayfa ve kısa biyografi
- `projects.html`: Proje kartları
- `publications.html`: Yayın listesi
- `blog/`: Blog ana sayfası ve yazılar
- `assets/css/style.css`: Tema/renkler/typography

## Yeni Blog Yazısı
- `blog/posts/first-post.html` dosyasını kopyalayın, isim ve içeriği değiştirin.
- `blog/index.html` içine yeni yazıya bir `<li>` ekleyin.

## Görseller
- `assets/img/avatar.jpg` dosyasını kendi fotoğrafınızla değiştirin.
- `assets/Ulas_Turan_CV.pdf` dosyasını gerçek CV’nizle değiştirin veya linki kaldırın.

## Netlify (alternatif)
- Netlify hesabı açın → **New site from Git** → repoyu seçin → direkt yayınlanır.
