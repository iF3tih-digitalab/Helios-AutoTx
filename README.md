# 🚀 Jalancuan Bot — Helios Auto Stake & Bridge

**jalancuan-bot-premium.js**  
Bot terminal interaktif untuk auto-transaksi di jaringan **Helios**.  
Mendukung banyak wallet, proxy per wallet, randomisasi, dan fitur keamanan premium.

---

## ✨ Fitur Utama

- ✅ UI interaktif langsung di terminal (berbasis `blessed`)
- ✅ Input banyak wallet via private key
- ✅ Dukungan multi proxy → 1 proxy : 1 wallet (anti-sybil)
- ✅ Auto Bridge + Stake setiap hari
- ✅ Random volume & delay (simulasi manusia)
- ✅ Fee checker → skip TX kalau saldo native kurang
- ✅ Gas monitor → TX di-skip kalau gas terlalu mahal
- ✅ Retry otomatis saat TX gagal
- ✅ Export TX log ke file CSV
- ✅ Manual config editor untuk pengaturan volume + frekuensi

---

## 🧪 Cara Menjalankan

### 1. Clone repository:

```bash
git clone https://github.com/NAMA-KAMU/jalancuan---helios-auto-tx.git
cd jalancuan---helios-auto-tx
```

### 2. Install dependencies:

```bash
npm install
```

### 3. Jalankan bot:

```bash
npm start
```

---

## 📋 Format Input Wallet & Proxy

- Private Key dipisah dengan koma `,`
  ```
  0xabc...,0xdef...,0x123...
  ```

- Proxy format:
  ```
  http://user:pass@1.2.3.4:8000,socks5://5.6.7.8:1080
  ```

---

## 🛡️ Catatan Keamanan

- Private key **tidak disimpan ke file**
- Semua proses dijalankan langsung di memori (RAM)
- Jangan gunakan wallet utama untuk bot (gunakan wallet farming)

---

## 👨‍💻 Developer

Built with ❤️ by [Rizal Hilaluzaman](https://github.com/iF3tih-digitalab)  
Twitter: [@jalancuan_id](https://twitter.com/jalancuan_id)

---

> Follow @jalancuan.id untuk tips farming & update fitur terbaru!
