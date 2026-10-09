# kotabijapanese.github.io

Halaman perkenalan Kotabi Japanese: https://kotabijapanese.github.io

Isinya hanya halaman statis (`index.html`, `og.png`). Tidak ada kode bot, token, atau data member di repo ini.
Setiap push ke `main` langsung tayang lewat GitHub Pages.

## Yang perlu diperbarui bersama bot

| Bagian di `index.html` | Sumbernya | Kapan diubah |
|---|---|---|
| Blok `KETENTUAN:MULAI` … `KETENTUAN:SELESAI` | `Msg.KETENTUAN_ISI` di kotabi-bot (`shared/messages.py`, `docs/MEMBERSHIP_SYSTEM.md` §3.4) | Setiap kali Ketentuan Membership berubah. Tanggal versinya harus sama |
| Tanya jawab | `/info faq` (`features/social/info_commands.yml`) | Kalau jawabannya berubah |
| Angka (600 ribu+ kalimat, 1.547 episode, 64 judul, 10.650 kata, 632 pola) | paket korpus dan kamus kotabi-bot | Sesekali, tulis bulan datanya di baris "Angka per …" |
| "Gratis untuk semua" / "Member" | ringkasan tier `/info member-reguler` | Kalau batas gratis berubah |

Harga sengaja tidak ditulis di halaman ini. Harga terbaru ada di `/info member-reguler`, supaya tidak ada dua tempat
yang bisa berbeda.

## Aturan isi

- Jangan menyebut atau membandingkan aplikasi/layanan lain.
- Pembayaran tidak dilakukan di halaman ini. Semua transaksi lewat `/subscribe` di Discord.
- Link Discord memakai undangan khusus web, `https://discord.gg/cxHhQbK275` (tidak kedaluwarsa, tanpa batas), supaya
  jumlah orang yang masuk lewat web bisa dilihat di *Server Settings → Invites*. Ada di 3 tombol "Gabung".
