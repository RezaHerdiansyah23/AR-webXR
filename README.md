

# AR-webXR

Proyek ini adalah aplikasi berbasis web yang menggunakan **A-Frame** dan **AR.js** untuk menampilkan objek 3D dan video pada marker AR yang dipindai menggunakan webcam.

---

## 📂 Struktur Proyek

```plaintext
AR-webXR/
├── patternScan/
│   ├── pattern-keyboard.patt       # Marker untuk menampilkan model keyboard
│   ├── pattern-youwin.patt         # Marker untuk menampilkan video
├── keyboard.glb                    # File model 3D untuk keyboard
├── Rick Astley - Never Gonna Give You Up (Official Music Video).mp4  # Video lokal
├── index.html                      # File utama aplikasi web
```

---

## ✨ Fitur Utama

1. **Marker Pattern**  
   - **`pattern-keyboard.patt`**: Marker untuk model keyboard 3D.  
   - **`pattern-youwin.patt`**: Marker untuk video.

2. **Model 3D**  
   - **`keyboard.glb`**: Model keyboard yang dimuat menggunakan A-Frame.

3. **Video Augmented Reality**  
   - Video lokal yang ditampilkan pada marker khusus untuk video.

---

## 🚀 Cara Menjalankan Proyek

### 1️⃣ Clone Repository  
```bash
git clone https://github.com/username/AR-webXR.git
cd AR-webXR
```

### 2️⃣ Jalankan Server Lokal  
Gunakan server lokal untuk menjalankan proyek:  
- Contoh dengan Python:
  ```bash
  python -m http.server
  ```
- Akses melalui browser di `http://localhost:8000`.

### 3️⃣ Scan Marker  
- Gunakan webcam untuk memindai marker di folder `patternScan`.

---

## 📍 Marker

### Keyboard Marker
Marker untuk model keyboard:  
![Keyboard Marker](patternScan/pattern-keyboard.patt)

### Video Marker
Marker untuk menampilkan video:  
![Video Marker](patternScan/pattern-youwin.patt)

---

## 🛠 Teknologi yang Digunakan

- **[A-Frame](https://aframe.io/):** Framework untuk menciptakan pengalaman Virtual Reality di web.  
- **[AR.js](https://ar-js-org.github.io/AR.js/):** Library untuk Augmented Reality berbasis web.  
- **HTML/CSS/JavaScript:** Teknologi dasar untuk membangun halaman web.

---

## ❗ Catatan

- Pastikan browser mendukung **WebXR** dan **WebRTC** (seperti Chrome atau Firefox).
- Jika video tidak muncul:
  - Periksa path file video di `index.html`.
  - Pastikan video dapat diputar langsung di browser.
