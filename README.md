# Recipe Finder — SKL 2

**Nama:** (isi nama kamu)
**Kelas:** (isi kelas kamu)

## Fitur yang berhasil dibuat
- 🍜 Menampilkan daftar recipe dari DummyJSON (`https://dummyjson.com/recipes`) dengan Fetch API
- 🔍 Mencari recipe berdasarkan nama
- 🏷️ Filter recipe berdasarkan Cuisine dan Difficulty
- 📖 Melihat detail recipe (bahan, cara membuat, waktu, kalori, porsi)
- ❤️ Menambahkan dan menghapus recipe favorit
- 💾 Favorite disimpan di LocalStorage (tetap ada setelah refresh)
- 📱 Tampilan responsif untuk desktop dan mobile

## Alur aplikasi
Fetch Recipe → Tampilkan → Search / Filter → Lihat Detail → Simpan Favorite

## Kendala yang ditemukan
(isi dengan kendala yang kamu alami, contoh: tombol di dalam card dibuat dinamis sehingga event-nya tidak jalan — solusinya memakai event delegation pada `recipeList`.)

## Bagian yang masih belum dipahami
(isi dengan bagian yang masih belum kamu pahami)

## Cara membuka
Ekstrak ZIP, lalu buka index.html. Jangan pisahkan folder images: seluruh 50 foto resep asli disertakan agar gambar bawah tidak kosong. Data utama diambil melalui Fetch API; salinan data di script.js dipakai jika jaringan gagal. HTML, CSS, dan seluruh JavaScript berada di tiga file sesuai tugas, tanpa framework.

## Video yang WAJIB kamu rekam sendiri
1. Tampilkan daftar resep, cari nama, dan coba kedua filter.
2. Buka detail bahan dan instruksi.
3. Tambah favorite, refresh, buka Favorites, lalu hapus favorite.
4. Buka script.js, jelaskan getRecipes() (fetch dan response.json) serta renderRecipes() (filter dan DOM).
5. Pilih bagian yang kamu pahami dan jelaskan dengan bahasamu sendiri.
6. Ceritakan kendala yang benar-benar kamu alami dan solusinya.

Video belum disertakan karena tugas menilai penjelasan dan pemahamanmu sendiri. Isi Nama, Kelas, Kendala, dan Bagian yang belum dipahami dengan jawabanmu sendiri sebelum dikumpulkan.
