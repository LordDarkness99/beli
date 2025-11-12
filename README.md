
<!-- PROJECT LOGO -->
<p align="center">
  <h3 align="center">FLUTTER-BELI.EL</h3>
</p>


Selamat datang di repositori FLUTTER-BELI.EL! Proyek ini adalah etalase praktik pengembangan aplikasi seluler modern, yang memanfaatkan kekuatan Flutter, Clean Architecture, dan paket BLoC (Business Logic Component). Dibangun menggunakan Flutter 3 versi terbaru, aplikasi E-Commerce ini mencontohkan praktik terbaik untuk membangun aplikasi Flutter yang scalable (mudah dikembangkan), maintainable (mudah dirawat), dan efisien.

## Fitu Utama::
* **Arsitektur Bersih (Clean Architecture)**:Aplikasi ini mengikuti arsitektur modular yang memisahkan fokus (SoC) ke dalam lapisan-lapisan berbeda: Presentation, Domain, dan Data. Arsitektur ini mendukung penggunaan ulang kode dan memudahkan adaptasi terhadap perubahan di masa depan.
* **Managemen Status BLoC**: Aplikasi ini menggunakan pola BLoC untuk manajemen status. BLoC membantu mengelola aliran data dan logika bisnis secara bersih dan reaktif, meningkatkan kinerja aplikasi secara keseluruhan.
* **FUngsionalitas E-Commerce**: Aplikasi ini menampilkan berbagai fitur E-Commerce, seperti penjelajahan produk, pencarian, keranjang, dan pembelian. Pengguna dapat menjelajahi produk, menambahkannya ke keranjang, dan menyelesaikan transaksi dengan lancar.
<!-- Features -->
---
| Feature       | UseCases                                                                                                                                                                                                   |
|---------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Produk       | Get Product UseCase                                                                                                                                                                                        |
| Kategori     | Get Cached Category UseCase<br/>Get Remote Category UseCase<br/>Filter Category UseCase                                                                                                                    |
| Keranjang    | Get Cached Cart UseCase<br/>Get Remote Cart UseCase<br/>Add Cart Item UseCase<br/>Sync Cart UseCase                                                                                                        |
| User         | Get Cached User UseCase<br/>SignIn UseCase<br/>SignUp UseCase<br/>SignOut UseCase                                                                                                                          |
| Delivery Info | Get Cached Delivery Info UseCase<br/>Get Remote Delivery Info UseCase<br/>Add Delivery Info UseCase<br/>Edit Delivery Info UseCase<br/>Select Delivery Info UseCase<br/>Get Selected Delivery Info Use Case |
| Pesanan         | Get Orders UseCase<br/>Add Order UseCase                                                                                                                                                                   |

---

## Demo Sample

<div style="text-align: center">
    <table>
        <tr>
            <td style="text-align: center">
                <img src="https://res.cloudinary.com/dhyttttax/image/upload/v1695741758/RepoAssets/home-loading_r39lc6.gif" width="200"/>
            </td>            
            <td style="text-align: center">
                <img src="https://res.cloudinary.com/dhyttttax/image/upload/v1695743869/RepoAssets/home-navigation-min_q1cou5.gif" width="200"/>
            </td>
            <td style="text-align: center">
                <img src="https://res.cloudinary.com/dhyttttax/image/upload/v1695744798/RepoAssets/product-details-order_j0lvw5.gif" width="200" />
            </td>
        </tr>
        <tr>
            <td style="text-align: center">
                <img src="https://res.cloudinary.com/dhyttttax/image/upload/v1695745493/RepoAssets/user-delivery-infomarion_zr1eyv.gif" width="200"/>
            </td>
            <td style="text-align: center">
                <img src="https://res.cloudinary.com/dhyttttax/image/upload/v1695746530/RepoAssets/user-auth-screens_k3h6fw.gif" width="200"/>
            </td>
            <td style="text-align: center">
                <img src="https://res.cloudinary.com/dhyttttax/image/upload/v1695747060/RepoAssets/user-sign-in-loading_qjqmt0.gif" width="200"/>
            </td>
        </tr>
    </table>
</div>

<!-- GETTING STARTED -->
## MULAIIII
Ikuti langkah-langkah berikut untuk menyiapkan proyek di perangkat Anda:

### Sebelum Memasang Aplikasi
Flutter SDK (minimal versi 3.0.0)
1. Download di sini
    ![Download Disini](https://docs.flutter.dev/get-started)
2. Android Studio (disarankan versi terbaru)
3. Android SDK Platform Tools
4. Device/Emulator:
     Emulator Android melalui Android Studio
     atau perangkat fisik dengan USB Debugging

### Memasang Aplikasi
1. Clone the repo
   ```sh
   https://github.com/fdwp03/Flutter-TDD-Clean-Architecture-E-Commerce-App-main.git
   ```
2. Install packages
   ```sh
   flutter pub get
   ```
3. Deteksi Perangkat
   ```sh
   flutter devices
   ```
4. Pilih Perangkat Untuk Dijalankan
   ```sh
   flutter run -d <device_id>
   ```
   
