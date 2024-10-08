# Macam-macam-Topologi-Jaringan

Pengertian Topologi       
Topologi adalah metode atau cara yang digunakan agar bisa menghubungkan satu komputer dengan komputer lainnya. Struktur atau jaringan yang digunakan untuk menghubungkan satu komputer dengan komputer lainnya bisa dengan menggunakan kabel atau pun nirkabel (tanpa kabel).

Fungsi Topologi          
Topologi berfungsi untuk mengetahui bagaimana masing-masing komputer atau host dalam jaringan komputer dapat saling berkomunikasi satu sama lain.

Macam-macam topologi

1. Topologi Bus
![image](https://github.com/user-attachments/assets/aaf2b92c-66bf-44bf-8b4f-265711f5bc7f)

Semua perangkat terhubung ke satu kabel utama (bus) yang mengirimkan data. Data ditransmisikan ke seluruh kabel dan diterima oleh perangkat yang dituju.

Kelebihan: Sederhana dan murah untuk diimplementasikan, Mudah ditambah dengan perangkat baru tanpa mengubah struktur yang ada.

Kekurangan: Kerusakan pada kabel utama akan memutuskan seluruh jaringan, kinerja menurun seiring dengan penambahan perangkat karena lebih banyak tabrakan data.


2. Topologi Star
   ![image](https://github.com/user-attachments/assets/12ba1cc4-8db3-42b5-a0a7-c98e819b5ed7)

Semua perangkat terhubung ke hub atau switch pusat yang mengelola komunikasi antar perangkat.

 Kelebihan: Jika satu kabel perangkat rusak perangkat lain tidak terpengaruh, mudah dikelola dan dipantau, dan menambah atau menghapus perangkat lebih sederhana.

Kekurangan: Ketergantungan pada hub atau switch, jika pusat gagal seluruh jaringan akan terputus.
Biaya lebih tinggi karena memerlukan lebih banyak kabel dan perangkat pusat.


3. Topologi Ring
   ![image](https://github.com/user-attachments/assets/f47a30cf-a59b-4189-8c02-0f3a1fd09829)

Perangkat terhubung membentuk lingkaran tertutup, dengan data bergerak dalam satu arah atau dua arah di sekitar cincin.

Kelebihan:
Latensi rendah karena data hanya perlu melewati satu arah,
dapat menambah perangkat dengan mudah tanpa mempengaruhi jaringan yang ada.

Kekurangan:
Kerusakan pada satu titik dapat memutuskan seluruh jaringan, meskipun ada varian dengan pemulihan otomatis,
pengelolaan dan pemeliharaan bisa rumit jika jaringan tumbuh besar.


4. Topologi Mesh
   ![image](https://github.com/user-attachments/assets/87c65f52-8fa3-4673-8c8d-cc99d657b5aa)

Setiap perangkat terhubung langsung ke perangkat lain, menciptakan banyak jalur komunikasi. 

Kelebihan:
Sangat tahan terhadap kerusakan karena ada beberapa jalur komunikasi,
reliabilitas tinggi dan kinerja baik karena jalur komunikasi yang banyak.

Kekurangan:
Biaya tinggi dan kompleksitas pemasangan karena banyak kabel yang dibutuhkan,
Pemeliharaan rumit dan sulit dikelola jika perangkat bertambah banyak.

5. Topologi Tree
   ![image](https://github.com/user-attachments/assets/1f78a517-256e-439f-a38b-fc754845f712)

Menggabungkan topologi star dan bus, membentuk struktur hierarkis dengan node pusat (hub) yang terhubung ke beberapa cabang bus.

Kelebihan:
Skalabilitas baik karena mudah menambah cabang baru,
Terstruktur dan mudah dikelola dalam hal troubleshooting.

Kekurangan:
Kerusakan pada kabel utama atau node pusat dapat mempengaruhi bagian besar dari jaringan,
Lebih kompleks dibandingkan topologi star atau bus.


6. Topologi Hybrid
   ![image](https://github.com/user-attachments/assets/ccda80f9-2051-4a22-b172-f63c088abd60)

Menggabungkan beberapa topologi, seperti star-bus atau star-ring, untuk memanfaatkan kelebihan masing-masing.

Kelebihan:
Fleksibilitas tinggi untuk memenuhi berbagai kebutuhan jaringan,
Keandalan dan efisiensi dari berbagai topologi dapat digabungkan.

Kekurangan:
Kompleksitas perancangan dan manajemen lebih tinggi,
Biaya implementasi dan pemeliharaan bisa meningkat.


7. Topologi peer to peer
    ![image](https://github.com/user-attachments/assets/f698772e-9cea-4582-b012-bd7d0aadb96b)

  Topologi peer to peer adalah topologi jaringan yang sangat sederhana karena hanya menghubungkan 2 komputer. Umumnya topologi peer to peer menggunakan satu kabel saja untuk menghubungkan kedua komputer agar bisa saling berbagai data. 

Kelebihan:
Biaya instalasi sangat murah,
proses instalasi mudah,
setiap komputer bisa berperan sebagai server atau client

Kekurangan:
Sangat sulit dikembangkan,
security dalam topologi ini sering bermasalah,
proses troubleshooting termasuk rumit.


8. Topologi Linier
   ![image](https://github.com/user-attachments/assets/51bb6da5-6d38-42ec-a9a5-d474d996081e)

Topologi linier atau sering disebut dengan topologi bus berurut. Umumnya topologi ini hanya menggunakan satu kabel utama sebagai konektor masing-masing titik sambungan pada setiap komputer.

Kelebihan: Mudah dikembangkan, 
penggunaan kabel sedikit,
tata letak topologi linier sederhana dan mudah, topologi ini tidak membutuhkan kendali sentral.


Topologi yang paling baik digunakan adalah topologi star, karena kemudahan pengelolaan dan skalabilitasnya, terutama dengan penggunaan switch yang canggih.
