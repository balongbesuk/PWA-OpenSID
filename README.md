# Membangun Progressive Web App (PWA) Opensid

Your next steps:
1. **download `Seluruh File dan Folder`**
2. **Edit `manifest.json`** Sesuaikan dengan nama Desa anda
3. **Edit `Gambar Logo`** Sesuaikan dengan Logo Desa anda
4. **Upload `semua file dan folder`** ke server
5. **Tambahkan manifest link tag** ke tema HTML anda 
6. **Tambahkan service worker registration snippet** ke tema HTML anda

Langkah Langkahnya sebagai berikut.

## 1. Upload `Semua fila dan folder` ke server

zip file yang berisi `seluruh perubahan no 2 dan no 3` upload ke public_html

## 2. Tambahkan manifest link tag ke tema HTML

pada `<head>` tema HTML, tambahkan code:

```html
<link rel="manifest" href="manifest.json" />
```

## 2. Tambahkan service worker registration snippet ke tema HTML anda

pada `<head>` tema HTML, tambahkan code:

```html
<script type="module">
   import 'https://cdn.jsdelivr.net/npm/@pwabuilder/pwaupdate';
   const el = document.createElement('pwa-update');
   document.body.appendChild(el);
</script>
```

## Selamat, Web anda sudah support PWA!

Untuk memverifikasi web sudah PWA, Buka [PWABuilder](https://pwabuilder.com).
