Tugas Akhir 'Klasifikasi Depresi dengan menggunakan EEG berdasarkan Domain Frekuensi'

Dataset asli

53
depression: 24
healthy: 29

Metode Eksperimen:
1. Dataset full menghasilkan 3 model eksperimen

2. 5 depresi dan 5 healthy dari dataset mat diambil terus nanti di test di modelnya, sama menghasilkan 3 model eksperimen. Dataset balancing dilakukan secara teratur, maksudnya per orang bukan per epoch jadi sekali apus langsung 50 image

5 orang yang di hapus dari dataset healthy untuk balancing:
8, 12, 17, 4, 20

13 orang untuk dataset train depression (650 file):
1, 3, 7, 8, 10, 12, 14, 15, 16, 4, 5, 11, 17

2 orang untuk dataset val depression (100 file):
19, 2 

4 orang untuk dataset testing depression (200 file):
6, 9, 13, 18

13 orang untuk dataset train healthy (650 file):
1, 2, 3, 5, 6, 7, 9, 10, 11, 13, 14, 15, 16

2 orang untuk dataset val healthy (100 file):
18, 19

4 orang untuk dataset testing healthy (210 file):
21, 22, 23, 24

3. Dataset primer dengan perekaman langsung
3 orang healthy yang dihilangin buat dataset balancing
2(5), 4(7), 7(10)

5 orang untuk dataset train depression (1165 - 25 file)
1(4), 2(5), 4(7), 5(8), 6(9)

1 orang untuk dataset testing depression (233 + 93 file)
3(6)

1 orang untuk dataset val depression (233 - 70 file)

3 orang untuk dataset train healthy ()
1, 3, 5

1 orang untuk dataset val healthy ()
6

4. Eksperimen 1 yang dikaji ulang dan revisi

