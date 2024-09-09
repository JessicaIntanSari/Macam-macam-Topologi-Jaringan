# Macam-macam-Topologi-Jaringan

Pengertian Topologi Jaringan        
Topologi jaringan komputer adalah metode atau cara yang digunakan agar bisa menghubungkan satu komputer dengan komputer lainnya. Struktur atau jaringan yang digunakan untuk menghubungkan satu komputer dengan komputer lainnya bisa dengan menggunakan kabel atau pun nirkabel (tanpa kabel)

Fungsi Topologi Jaringan Komputer
Topologi jaringan komputer berfungsi untuk mengetahui bagaimana masing-masing komputer atau host dalam jaringan komputer dapat saling berkomunikasi satu sama lain.

Macam macam topologi beserta kekurangan dan kelebihan 

1. Topologi Bus
   ![image](https://github.com/user-attachments/assets/4164910a-d70a-47d7-9b84-8a384880b823)

Semua perangkat terhubung ke satu kabel utama (bus) yang mengirimkan data. Data ditransmisikan ke seluruh kabel dan diterima oleh perangkat yang dituju.

Kelebihan: Sederhana dan murah untuk diimplementasikan. Mudah ditambah dengan perangkat baru tanpa mengubah struktur yang ada.

Kekurangan: Kerusakan pada kabel utama akan memutuskan seluruh jaringan. Kinerja menurun seiring dengan penambahan perangkat karena lebih banyak tabrakan data.

2. Topologi Star:
Semua perangkat terhubung ke hub atau switch pusat yang mengelola komunikasi antar perangkat.

 Kelebihan: Jika satu kabel perangkat rusak, perangkat lain tidak terpengaruh. Mudah dikelola dan dipantau, dan menambah atau menghapus perangkat lebih sederhana.

Kekurangan: Ketergantungan pada hub atau switch, jika pusat gagal, seluruh jaringan akan terputus.
Biaya lebih tinggi karena memerlukan lebih banyak kabel dan perangkat pusat.

3. Topologi Ring
Perangkat terhubung membentuk lingkaran tertutup, dengan data bergerak dalam satu arah atau dua arah di sekitar cincin.

Kelebihan: Latensi rendah karena data hanya perlu melewati satu arah. Dapat menambah perangkat dengan mudah tanpa mempengaruhi jaringan yang ada.

Kekurangan: Kerusakan pada satu titik dapat memutuskan seluruh jaringan, meskipun ada varian dengan pemulihan otomatis.
Pengelolaan dan pemeliharaan bisa rumit jika jaringan tumbuh besar.

4. Topologi Mesh
Setiap perangkat terhubung langsung ke perangkat lain, menciptakan banyak jalur komunikasi. 

Kelebihan: Sangat tahan terhadap kerusakan karena ada beberapa jalur komunikasi. Reliabilitas tinggi dan kinerja baik karena jalur komunikasi yang banyak.

Kekurangan: Biaya tinggi dan kompleksitas pemasangan karena banyak kabel yang dibutuhkan.
Pemeliharaan rumit dan sulit dikelola jika perangkat bertambah banyak.

5. Topologi Tree
Menggabungkan topologi star dan bus, membentuk struktur hierarkis dengan node pusat (hub) yang terhubung ke beberapa cabang bus.

Kelebihan: Skalabilitas baik karena mudah menambah cabang baru.
Terstruktur dan mudah dikelola dalam hal troubleshooting.

Kekurangan: Kerusakan pada kabel utama atau node pusat dapat mempengaruhi bagian besar dari jaringan. Lebih kompleks dibandingkan topologi star atau bus.

6. Topologi Hybrid
Menggabungkan beberapa topologi, seperti star-bus atau star-ring, untuk memanfaatkan kelebihan masing-masing.

Kelebihan: Fleksibilitas tinggi untuk memenuhi berbagai kebutuhan jaringan. Keandalan dan efisiensi dari berbagai topologi dapat digabungkan.

Kekurangan: Kompleksitas perancangan dan manajemen lebih tinggi. Biaya implementasi dan pemeliharaan bisa meningkat.

7. Topologi peer to peer 
  Topologi peer to peer adalah topologi jaringan yang sangat sederhana karena hanya menghubungkan 2 komputer. Umumnya topologi peer to peer menggunakan satu kabel saja untuk menghubungkan kedua komputer agar bisa saling berbagai data. 

Kelebihan: Biaya instalasi sangat murah, proses instalasi mudah
Setiap komputer bisa berperan sebagai server atau client.

Kekurangan: Sangat sulit dikembangkan, security dalam topologi ini sering bermasalah, proses troubleshooting termasuk rumit.

8. Topologi Linier
Topologi linier atau sering disebut dengan topologi bus berurut. Umumnya topologi ini hanya menggunakan satu kabel utama sebagai konektor masing-masing titik sambungan pada setiap komputer.

Kelebihan: Mudah dikembangkan, 
penggunaan kabel sedikit,
tata letak topologi linier sederhana dan mudah, topologi ini tidak membutuhkan kendali sentral.
