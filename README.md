# Image Enhancement using Dynamic Histogram Equalization
## I. Apa yang kalian kerjakan dan masalah apa yang kalian pecahkan/kerjakan.

  Penggunaan kamera Closed Circuit Television (CCTV) banyak digunakan saat ini terutama perusahaan atau industry, pertokoan dan tempat-tempat strategis lainnya. Dengan menggunakan kamera CCTV keamanan tempat tersebut akan terjamin. Akan tetapi kekurangan dari kamera CCTV adalah apabila ruangan tidak memiliki cahaya kurang (gelap) maka hasil objek yang terekam tidak maksimal. Untuk mengatasi permasalahan diatas maka perlu adanya Histogram Equalization yang dapat memberikan perbaikan kualitas citra (Image Enhancement) dan kami juga menggunakan konvolusi untuk memperbagus dari hasil pemrosesan Image Enhancement tersebut. Untuk citra yang diambil sebagai Image Enhancement sebagai contoh uji coba penelitian adalah citra Screen Capture CCTV dari dataset google. Dari citra Screen Capture CCTV tersebut dilakukan tahap-tahap pemrosesan citra untuk menghasilkan perbaikan kualitas citra yang baik. Rencana pengambilan data citra screen Capture CCTV sejumlah 3 citra. Cara kerja sistem informasi Image Enhancement adalah citra screen Capture CCTV di praproses dengan merescale dengan merubah ukuran pada gambar pada citra Screen Capture CCTV, kami menggunakan rescale 50% atau setengah lebih kecil dari gambar ukuran aslinya, kemudian citra di Grayscale untuk dijadikan nilai piksel yang seragam, selanjutnya citra di Histogram Equalization  untuk intensitas menjadi seragam dan proses Histogram Equalization untuk mendapatkan hasil image enhancement.

## II.	Step by step detail algoritmanya (disisipin source code juga).
Langkah-langkah yang dilakukan dalam penelitian ini ada dua proses, yaitu proses image enhancement dan proses uji coba tingkat keberhasilan. Untuk proses image enhancement terdapat proses input citra, grayscale, dan proses Histogram Equalization untuk mendapatkan hasil image enhancement. 

-	Input Citra
Input citra berupa screen capture dari kamera CCTV yang diambil di Internet dengan di praproses ukuran setengah dari ukuran aslinya. Pengubahan ukuran citra dari ukuran asli dan akan menghasilkan ukuran setengah dari aslinya dengan format file JPG dilakukan untuk keseragaman ukuran dan format file data uji coba pada penelitian.
- Proses Grayscale
Proses pertama adalah mengubah citra screen capture CCTV dijadikan grayscale. Nilai grayscale sama dengan rata-rata dari nilai ketiga elemen warnanya dengan menggunakan Persamaan 1

- Proses Histogram Equalization
Metode Histogram Equalization merupakan suatu cara yang bertujuan untuk memperoleh histogram yang intensitasnya terdistribusi secara seragam pada citra. Pendekatan yang dilakukan adalah untuk mendapatkan grayscale yang lebih luas pada daerah yang memiliki banyak piksel dan mempersempit aras keabuan pada daerah yang berpiksel sedikit. Efeknya dapat digunakan untuk meningkatkan kontras secara menyeluruh

