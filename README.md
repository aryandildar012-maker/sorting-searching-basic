Bubble Sort - Anti Capek (Early Exit):
Biasanya Bubble Sort itu "polos", data sudah urut pun tetap dicek terus sampai habis. Di sini saya tambahkan variabel swapped. Kalau dalam satu putaran nggak ada angka yang tukaran, program bakal langsung tahu kalau data sudah rapi dan langsung berhenti. Jadi lebih hemat waktu eksekusi!

Binary Search - Anti Crash (Overflow Protection):
Saya nggak pakai rumus pasaran (low + high) / 2 buat cari nilai tengah. Kenapa? Karena kalau datanya banyak banget, hasil penjumlahan low + high bisa kegedean dan bikin error (integer overflow). Saya pakai rumus low + (high - low) / 2 supaya kodenya jauh lebih aman dan stabil buat data skala besar.
