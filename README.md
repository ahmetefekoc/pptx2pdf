# PPTX → PDF (kaymadan)

Tamamen tarayıcıda çalışan, sunucusuz PPTX → PDF dönüştürücü.

## GitHub Pages'e yayınlama
1. Bu klasörün içeriğini yeni bir GitHub deposuna `main` dalına yükle.
2. Depoda **Settings → Pages → Build and deployment → Source** kısmını **GitHub Actions** yap.
3. `main`'e her push'ta `.github/workflows/pages.yml` siteyi otomatik yayınlar (Actions sekmesinden izleyebilirsin).

## Yerelde deneme
`python3 -m http.server` ile aç, `http://localhost:8000` adresine git.

## Kullanılan kütüphaneler (vendor/)
pptx-preview 1.0.7, html2canvas 1.4.1, jsPDF 4.2.1
