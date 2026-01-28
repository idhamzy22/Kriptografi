<div align="center">

# 🔐 **Sistem Keamanan E-Ticketing AES-256** 🔐

*Perancangan Sistem Keamanan Data E-Ticketing Menggunakan Algoritma Kriptografi AES-256*  
**Oleh: Muhammad Najib Ardiansah et al. | Teknik Informatika, Universitas Esa Unggul** 

---

## 📋 **Ringkasan Penelitian**
Penelitian ini merancang prototipe aman untuk e-ticketing dengan **AES-256-CBC**, melindungi data sensitif seperti identitas, pembayaran, dan rute perjalanan dari serangan siber.  
**Metodologi:** 5 tahap (literatur → arsitektur → Java+Bouncy Castle → OWASP ZAP → evaluasi).

**Arsitektur Utama:**
- Encryption Service (AES-256)
- QR Code Generator (ZXing)
- Verification Service
- Database Terenkripsi

---

## ⚡ **Hasil Performa & Keamanan**

| Ukuran Data | 🛡️ Enkripsi (ms) | 🔓 Dekripsi (ms) | 🚀 Throughput (MB/s) |
|-------------|------------------|------------------|----------------------|
| 100 bytes  | **0.5**         | **0.4**         | **0.11**            |
| 1 KB       | **1.2**         | **1.1**         | **0.43**            |
| **10 KB**  | **5.6**         | **5.2**         | **0.93**            |
| 100 KB     | **52.3**        | **48.7**        | **0.99**            |
| 1 MB       | **523.4**       | **487.6**       | **0.99**            | 

**Keamanan Terbukti:**
✅ **100%** anti-duplikasi tiket  
✅ Tahan **brute-force** (\(2^{256}\) kombinasi)  
✅ OWASP ZAP: No SQLi, XSS, MITM 

---

## 🎥 **Video Demonstrasi**
[![AES-256 E-Ticketing Demo](https://img.youtube.com/vi/OicloiH3BCs/0.jpg)](https://youtu.be/OicloiH3BCs)  
**Implementasi AES dalam E-Ticketing** – Visualisasi proses enkripsi QR code 

---

## 🏆 **Kesimpulan & Rekomendasi**
> **AES-256** = Keseimbangan sempurna **keamanan enterprise** + **performa cepat** (0.9ms/tiket).

**Best Practices:**
- HSM/Key Management Service
- Rotasi kunci **90 hari**
- Hybrid blockchain untuk audit
- Future: Quantum-resistant crypto 

---
*Jurnal lengkap: Jurnal-Kelompok.docx | Dibuat Januari 2026* ✨

</div>
