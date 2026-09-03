# Onur Akçay Portfolio v2

CV odaklı, minimal kişisel portföy sitesi.

## Yapı
- `public/index.html`
- `public/style.css`
- `public/assets/Onur_AKCAY_CV.pdf`
- `public/assets/profile.jpg` (profil fotoğrafı eklendiğinde otomatik gösterilir)
- `wrangler.jsonc`

## Profil fotoğrafı
LinkedIn profil görseli dışarıdan güvenilir şekilde indirilemediği için kendi profil fotoğrafınızı
`public/assets/profile.jpg` olarak ekleyin. Site otomatik olarak gösterecektir.

## Deploy
```bash
git add .
git commit -m "Update portfolio from CV"
git push
```
Cloudflare GitHub entegrasyonu açıksa push sonrası otomatik deploy edilir.
