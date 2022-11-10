# counter_7

1. Jelaskan apa yang dimaksud dengan stateless widget dan stateful widget dan jelaskan perbedaan dari keduanya.

Apapun widget yang dapat berubah atau dinamis adalah stateful widget. Apapun widget yang tidak dapat berubah atau statis adalah stateless widget.

2. Sebutkan widget apa saja yang kamu pakai di proyek kali ini dan jelaskan fungsinya.

Scaffold : Sebagai layar utama aplikasi
AppBar : Untuk meletakkan judul aplikasi
Center : Untuk meletakkan elemen di tengah
Column : Untuk layouting
Text : Untuk menampilkan string/kata kata
Stack : Untuk meletakkan FloatingActionButton
Positioned : Untuk memosisikan FloatingActionButton
FloatingActionButton : Untuk meng-handle tindakan

3. Apa fungsi dari setState()? Jelaskan variabel apa saja yang dapat terdampak dengan fungsi tersebut.

Saat ada oerubahan status dari widget stateful, kita menggunakan setState() untuk melakukan pembuatan ulang widget dan semua turunannya. Variabel _counter dan widget widget yang menggunakannya

4. Jelaskan perbedaan antara const dengan final.

Const saat sebelum run akan sudah dikunci valuenya, sedangkan Final akan mengunci value saat sudah di run

5. Jelaskan bagaimana cara kamu mengimplementasikan checklist di atas.

- Melakukan flutter create
- Membuat FAB tambahan untuk decrement
- Membuat method _decrement dan set method tersebut sebagai aksi dari FAB decrement
- Membuat kondisi dimana saat counter dimodulo 2 = 1 maka teks ganjil, dan selain itu genap
- Membuat kondisi dimana button FAB decrement hanya tampil saat _counter > 0
