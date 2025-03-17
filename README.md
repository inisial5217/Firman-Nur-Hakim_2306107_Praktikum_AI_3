# Implementasi Algoritma Pencarian Berbasis Heuristik dalam Python  

Repositori ini menyediakan implementasi tiga algoritma pencarian berbasis heuristik yang sering digunakan dalam pemecahan masalah jalur terpendek dan optimasi rute. Algoritma yang tersedia meliputi:  

## 🔍 Algoritma yang Diimplementasikan  
🔹 **Greedy Best-First Search (GBFS)** – Algoritma yang selalu memilih simpul dengan **nilai heuristik (h(n)) terendah**, tanpa mempertimbangkan biaya perjalanan sebelumnya. Cocok untuk eksplorasi cepat tetapi tidak selalu optimal.  

🔹 **A* Tree Search** – Menggunakan pendekatan **f(n) = g(n) + h(n)**, di mana g(n) adalah biaya perjalanan dari awal, dan h(n) adalah estimasi ke tujuan. Algoritma ini tidak menyimpan simpul yang sudah dikunjungi, sehingga bisa melakukan eksplorasi berulang.  

🔹 **A* Graph Search** – Versi yang lebih efisien dari A* Tree Search karena menyimpan daftar simpul yang telah dikunjungi untuk menghindari eksplorasi ulang, sehingga lebih optimal dalam menemukan jalur terpendek.  

Repositori ini ditujukan bagi mahasiswa, peneliti, atau siapa saja yang ingin memahami bagaimana algoritma pencarian bekerja dan bagaimana mengimplementasikannya dalam Python. Selamat belajar! 🚀
