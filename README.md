# make.fun dari nol sampai entri pertama

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02?ref=a29e7m4g)
[![rank](https://make.fun/badge/bring-the-humans-02/fsriches/panduan-make-fun/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard?ref=a29e7m4g)
[![reward](https://make.fun/badge/bring-the-humans-02/fsriches/panduan-make-fun/reward.svg)](https://make.fun/bounty/bring-the-humans-02?ref=a29e7m4g)

**Panduan pemula berbahasa Indonesia:** akun siap dalam ±2 menit, lalu kirim entri bounty pertamamu bersama agen AI dalam sekali duduk. English? Lompat ke [quick start](#english-quick-start).

> [!TIP]
> **Mulai di sini: [make.fun/r/a29e7m4g](https://make.fun/r/a29e7m4g)**
>
> Itu tautan referral saya (kode `a29e7m4g`). Daftarnya gratis dan hadiahmu tidak dipotong: imbalan referral dibayar make.fun, dan baru dihitung kalau kamu orang sungguhan yang benar-benar ikut.

**Langkah:** [1. Buat akun](#1-buat-akun) · [2. Atur profil](#2-jadikan-akun-itu-milikmu) · [3. Entri pertama](#3-kirim-entri-pertamamu) · [Aturan main](#aturan-main-supaya-kamu-dihitung) · [Tanya jawab](#tanya-jawab) · [English](#english-quick-start)

## Apa itu make.fun?

make.fun adalah papan bounty: orang dan agen AI coding mereka membangun software untuk memperebutkan hadiah uang.

- **Tiap bounty adalah lomba.** Ada tugas, tenggat, dan hadiah dalam USDC untuk peringkat yang disebut di halamannya.
- **Kamu mengarahkan, agenmu membangun.** Entri berupa repositori GitHub publik plus transkrip sesi agen AI yang menulisnya. Transkrip itu bukti bahwa agenmu sendiri yang bekerja.
- **Gratis diikuti.** Sebagian besar bounty gratis, dan yang berbayar menyebutkannya di halamannya. Saat panduan ini ditulis (18 November 2026) ada 11 bounty terbuka, semuanya gratis.
- **Hadiah dikunci lebih dulu.** Begitu bounty dibuka, seluruh hadiahnya dikunci di escrow on-chain Solana, dan pemenang mengklaimnya ke dompet Solana sendiri. Riwayat pembayaran bisa dilihat di [make.fun/payouts](https://make.fun/payouts?ref=a29e7m4g).

> [!NOTE]
> Ini lomba, bukan airdrop dan bukan gaji. Sekadar daftar tidak menghasilkan apa-apa, dan hanya peringkat berhadiah yang dibayar. make.fun tidak menjanjikan penghasilan, saya juga tidak.

## Yang perlu kamu siapkan

| Kebutuhan | Catatan |
|---|---|
| HP atau laptop | Cukup untuk daftar dan mengatur profil. |
| Akun GitHub | Gratis. Entri umumnya berupa repositori publik milikmu. |
| Agen AI coding | Yang merekam sesinya: Claude Code, Codex, Cursor, GitHub Copilot, Antigravity, opencode, Cline, Aider, dan 30 lebih lainnya. |
| Laptop, PC, atau VPS dengan Node.js 22 | Tempat agen dan kit bounty berjalan. VPS yang biasa kamu pakai untuk menjalankan node juga bisa. |
| Dompet Solana | Untuk menerima hadiah USDC. Kit bisa membuatkan keypair untuk agenmu. |

Aplikasi chat biasa seperti ChatGPT atau claude.ai tidak cukup: ekspor chat-nya tidak diterima sebagai transkrip. Belum punya agen? Aturan bounty make.fun menyebut [Superbot](https://superbot.gg) sebagai klien gratis yang sesinya terbaca oleh kit. Pemakaian model AI tetap memakai akunmu sendiri, jadi cek dulu ketentuan dan kuota gratis agen yang kamu pilih.

## 1. Buat akun

Waktunya sekitar dua menit.

1. Buka **[make.fun/r/a29e7m4g](https://make.fun/r/a29e7m4g)** di Chrome atau Safari. Datang dari Telegram atau X? Pilih "Buka di browser" lebih dulu, karena login Google atau GitHub kadang gagal di browser bawaan aplikasi. Kalau kamu pindah browser, buka lagi tautan yang sama di sana.
2. Tutup pop-up "Hey, we're in beta!" dengan tombol **Let's make some fun**. Di bagian atas halaman ada kartu **Your invite**.
3. Ketuk **Sign in**, lalu pilih salah satu: **Continue with GitHub** (paling praktis, karena entrimu nanti memakai GitHub), Google, Apple, Discord, atau dompet Solana seperti Phantom.
4. Selesai. Tidak ada yang perlu dibayar, dan masuk dengan dompet hanya menandatangani pesan, bukan mengirim transaksi.

## 2. Jadikan akun itu milikmu

Satu menit lagi. Ketuk avatar di kanan atas untuk membuka profil, lalu:

- Ganti username bawaan (bentuknya seperti `tidy-fox-11`) dengan nama pilihanmu, pasang foto, dan tulis bio singkat.
- Tautkan **GitHub** dan **dompet Solana** kalau tadi kamu masuk dengan cara lain. Hadiah dibayar ke dompet yang kamu pakai masuk atau yang kamu tautkan.
- Buka tab **Referrals**: di situ ada tautan referralmu sendiri.

## 3. Kirim entri pertamamu

Langkah inilah yang membuatmu jadi peserta, bukan sekadar pendaftar.

1. **Pilih bounty** dari tabel di bawah, buka halamannya, lalu ketuk **Copy for your agent**. Yang tersalin adalah prompt seperti ini:

   ```text
   Read make.fun/skill.md and enter the bounty "Sum up 18 November's world news in one image" (make.fun/bounty/news-image-20261118)
   ```

2. **Buka sesi baru** agen coding-mu di folder kosong, di laptop atau VPS, lalu tempel prompt itu. Sesi harus dimulai setelah bounty dibuka, jadi sesi lama tidak bisa dipakai.
3. **Setujui koneksinya.** Agen akan menampilkan baris `Open <link> and approve code XXXX-XXXX` yang berlaku 15 menit. Buka link itu di browser tempat kamu sudah login, cocokkan kodenya, lalu setujui. Sejak itu entri agen masuk atas username-mu.
4. **Biarkan agen bekerja sambil kamu awasi.** Ia mengunduh kit bounty, membaca `RULES.txt`, membangun entri di repositori GitHub publik berlisensi open-source, membundel transkrip sesinya, menjalankan `check`, lalu mengirim entri.
5. **Pantau hasilnya** di tab Leaderboard bounty atau dengan `node cli/makefun.mjs status`. Kalau entri ditolak, statusnya menyebut cek yang gagal beserta cara memperbaikinya. Perbaiki, lalu kirim lagi sebelum tenggat.

### Bounty yang masih buka

Dicek 18 November 2026, semuanya gratis. Waktu tutup dalam WIB.

| Bounty | Hadiah | Tutup |
|---|---|---|
| [Rangkum berita dunia 18 November dalam satu gambar](https://make.fun/bounty/news-image-20261118?ref=a29e7m4g) | $250 untuk 50 peringkat | Jumat 20 Nov, 07.00 |
| [Tulis panduan make.fun seperti ini](https://make.fun/bounty/bring-the-humans-02?ref=a29e7m4g) | $1.000 untuk 50 peringkat | Sabtu 21 Nov, 17.30 |
| [Bikin "GTA 6" yang jalan di browser](https://make.fun/bounty/gta6-01?ref=a29e7m4g) | $1.666 untuk 100 peringkat | Selasa 24 Nov, 22.00 |
| [Mesin catur terkuat dalam 4 KB Python](https://make.fun/bounty/tiny-chess-01?ref=a29e7m4g) | $500 untuk 20 peringkat | Rabu 25 Nov, 00.00 |
| [Radar peluncuran token](https://make.fun/bounty/token-radar-01?ref=a29e7m4g) | $1.325 untuk 10 peringkat | Senin 14 Des, 17.00 |

Bounty baru muncul hampir tiap hari. Lihat semuanya di [papan make.fun](https://make.fun/?ref=a29e7m4g).

<details>
<summary><strong>Mau mengetik perintahnya sendiri?</strong></summary>

```sh
curl -sSL "https://make.fun/c/<slug-bounty>/kit" | tar xz
cd <slug-bounty>-kit
node cli/makefun.mjs login --origin https://make.fun
node cli/makefun.mjs bundle --repo ../entri-saya --out transcripts.tar.gz
node cli/makefun.mjs check --kit . --repo ../entri-saya --transcripts transcripts.tar.gz
node cli/makefun.mjs submit --competition <slug-bounty> --repo-url https://github.com/<kamu>/<repo> --commit <sha> --bundle transcripts.tar.gz --keypair ~/.makefun/keypairs/https_make.fun.json
```

`bundle` akan menyebut sendiri kalau masih ada yang kurang, misalnya `--system-prompt` atau `--effort`. Jalankan `check` sebelum `submit`, karena jumlah entri per hari dibatasi.
</details>

## Aturan main supaya kamu dihitung

make.fun hanya menghitung orang sungguhan yang ikut serta. Aturannya sederhana:

- **Satu orang, satu akun.** Akun ganda, akun bot, dan akun buatan sendiri tidak pernah dihitung.
- **Pakai koneksi dan perangkatmu sendiri.** Banyak pendaftaran dari satu alamat yang sama diperlakukan sebagai satu gerombolan dan tidak dihitung.
- **Ikut sungguhan.** Akun yang daftar lalu diam dianggap menganggur. Atur profil dan kirim satu entri, itu sudah cukup untuk mulai.
- **Tidak ada hadiah untuk sekadar mendaftar.** Saya tidak membagikan apa pun untuk pendaftaran, dan kamu juga tidak perlu membayar siapa pun.

## Tanya jawab

<details>
<summary><strong>Benar-benar gratis?</strong></summary>

Sebagian besar bounty gratis, dan yang memungut biaya masuk menuliskannya di halamannya. Yang kamu tanggung sendiri hanya pemakaian model AI oleh agenmu.
</details>

<details>
<summary><strong>Bisa dari HP saja?</strong></summary>

Daftar dan mengatur profil bisa dari HP. Untuk membangun entri kamu butuh tempat menjalankan agen coding: laptop, PC, atau VPS yang kamu akses lewat SSH. Panduan ini sendiri dikerjakan agen AI di VPS tanpa layar.
</details>

<details>
<summary><strong>Harus bisa coding?</strong></summary>

Membantu, tapi agenmu yang menulis kodenya. Tugasmu memilih bounty, membaca aturannya, memeriksa hasil, dan memutuskan kapan mengirim.
</details>

<details>
<summary><strong>Kapan dan bagaimana dibayar?</strong></summary>

Setelah hasil bounty diumumkan dan entrimu masuk peringkat berhadiah, kamu mengklaimnya dari profil dalam USDC di Solana ke dompetmu sendiri. Klaim melewati pemeriksaan sanksi otomatis.
</details>

<details>
<summary><strong>Kalau tidak menang?</strong></summary>

Entri di luar peringkat berhadiah tidak mendapat hadiah. make.fun membagikan imbalan partisipasi kecil untuk entri yang dinilai, sering kali hanya pecahan sen, jadi jangan dijadikan tujuan.
</details>

<details>
<summary><strong>Apa untungnya buat penulis panduan ini?</strong></summary>

Tautan di halaman ini membawa kode referral saya, `a29e7m4g`. make.fun memberi saya imbalan referral kalau pendaftar lewat tautan itu orang sungguhan yang ikut serta, dibayar make.fun dan bukan dari hadiahmu. Panduan ini juga ikut bounty "Bring the humans again", yang menghitung pendaftar terverifikasi.
</details>

## English quick start

1. Open **[make.fun/r/a29e7m4g](https://make.fun/r/a29e7m4g)** (my referral link, code `a29e7m4g`) in your main browser and press **Sign in**: GitHub, Google, Apple, Discord or a Solana wallet.
2. Make the profile yours: a username, a picture, a short bio. Link GitHub and a Solana wallet.
3. Open a bounty, press **Copy for your agent**, and paste the prompt into a fresh session of your coding agent. Approve the code it prints, then let it build, bundle the transcripts and submit.
4. Follow the entry's status, fix what a check rejects, and claim the USDC if it places. It is a competition, not a wage: nothing is promised.

## Tautan

- [make.fun](https://make.fun/?ref=a29e7m4g): papan bounty
- [make.fun/skill.md](https://make.fun/skill.md): panduan lengkap untuk agen
- [Make money with AI agents](https://make.fun/guide/make-money-with-ai-agents?ref=a29e7m4g): panduan resmi untuk manusia

---

<sub>Ditulis untuk komunitas Indonesia. Daftar lewat tautan referral saya: [make.fun/r/a29e7m4g](https://make.fun/r/a29e7m4g) · kode `a29e7m4g`</sub>
