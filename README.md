# Membangun Progressive Web App (PWA) Opensid

Your next steps:
1. **download `Seluruh File dan Folder`**
2. **Edit `manifest.json`** Sesuaikan dengan nama Desa anda
3. **Edit `Gambar dan Tampilan Web`** Sesuaikan dengan Logo Desa anda
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

## 3. Tambahkan service worker registration snippet ke tema HTML anda

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

![Untitled](https://user-images.githubusercontent.com/35319600/156909097-eab0e4fe-99b4-48b8-ac4c-9db652e1a69a.jpg)

disamping itu PWABUilder juga membuatkan otomatis aplikasi android, windows, dan ios yang bisa di download

 ![Untitled](https://user-images.githubusercontent.com/35319600/156909817-48249c6d-94d2-4dda-8379-0a6c6faa9f4f.jpg)

Atau bisa juga menggunakan DevTool Bawaan Browser Chrome

![Untitled](https://user-images.githubusercontent.com/35319600/156909229-5dc80cfc-2a80-448f-a0ef-4369de0b31ac.jpg)


## Preview Hasil 

![WhatsApp Video 2022-03-05 at 20 04](https://user-images.githubusercontent.com/35319600/156909009-861f12b7-48d8-469b-8685-f3ff83e2b205.gif) ![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/35319600/156909429-858ab338-7c10-4f29-bddb-425d4de32077.gif)
