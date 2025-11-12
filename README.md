[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
<!-- PROJECT LOGO -->
<p align="center">
  <h3 align="center">FLUTTER-BELI.EL</h3>
</p>

![Deskripsi Gambar Anda](https://drive.google.com/file/d/1CerkuXoylQWryg-XSiraTqvwHKqWSOE3/view?usp=sharing)


Selamat datang di repositori Flutter-TDD-Clean-Architecture-E-Commerce-App! Proyek ini adalah etalase praktik pengembangan aplikasi seluler modern, yang memanfaatkan kekuatan Flutter, Test-Driven Development (TDD), Clean Architecture, dan paket BLoC (Business Logic Component). Dibangun menggunakan Flutter 3 versi terbaru, aplikasi E-Commerce ini mencontohkan praktik terbaik untuk membangun aplikasi Flutter yang scalable (mudah dikembangkan), maintainable (mudah dirawat), dan efisien.

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

## Backend Options
### Node json-server(Mock API)
* Source Code - https://github.com/Sameera-Perera/E-Commerce-Mock-API
* Live - https://e-commerce-mock-api-webservice.onrender.com

### Java Spring Boot
* Source Code - coming soon
* Live - coming soon

## Contributing:

We welcome contributions from the Flutter community to make this project even better. Whether you are interested in adding new features, fixing bugs, or improving documentation, your contributions are highly appreciated. Please refer to the contribution guidelines in the repository for more details on how to get involved.

<!-- GETTING STARTED -->
## Getting Started

To get started with this project, follow the instructions in the README to set up your development environment and run the app locally. You can also explore the project's architecture, tests, and documentation to gain insights into building robust Flutter apps.

We hope this Flutter-TDD-Clean-Architecture-E-Commerce-App serves as a valuable resource for both Flutter enthusiasts and developers looking to learn about TDD, clean architecture, and BLoC in the context of mobile app development. Happy coding!

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
   
For help getting started with Flutter, view our online
[documentation](https://flutter.io/).

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contributors ✨

Thanks to these wonderful people:
<!-- ALL-CONTRIBUTORS-LIST:START -->
<table>
  <tr><td align="center"><a href="https://github.com/AaronDsilva97"><img src="https://avatars.githubusercontent.com/u/74453685?v=4" width="100px;" alt="AaronDsilva97"/><br /><sub><b>AaronDsilva97</b></sub></a></td></tr>
</table>
<!-- ALL-CONTRIBUTORS-LIST:END -->


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/Sameera-Perera/Flutter-TDD-Clean-Architecture-E-Commerce-App.svg?style=for-the-badge
[contributors-url]: https://github.com/Sameera-Perera/Flutter-TDD-Clean-Architecture-E-Commerce-App/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Sameera-Perera/Flutter-TDD-Clean-Architecture-E-Commerce-App.svg?style=for-the-badge
[forks-url]: https://github.com/Sameera-Perera/Flutter-TDD-Clean-Architecture-E-Commerce-App/network/members
[stars-shield]: https://img.shields.io/github/stars/Sameera-Perera/Flutter-TDD-Clean-Architecture-E-Commerce-App.svg?style=for-the-badge
[stars-url]: https://github.com/Sameera-Perera/Flutter-TDD-Clean-Architecture-E-Commerce-App/stargazers
[issues-shield]: https://img.shields.io/github/issues/Sameera-Perera/Flutter-TDD-Clean-Architecture-E-Commerce-App.svg?style=for-the-badge
[issues-url]: https://github.com/Sameera-Perera/Flutter-TDD-Clean-Architecture-E-Commerce-App/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: http://www.linkedin.com/in/sameera-perera-1148081b8
[product-screenshot]: readme_assets/splash.jpg
