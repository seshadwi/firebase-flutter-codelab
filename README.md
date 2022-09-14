# Firebase Flutter Codelab

## Langkah Praktikum 

### 1. Menjalankan sampel kode

Berikut ini menjalankan sampel kode dari **codelab**.

![screenshot](images/01.png)

### 2. Melakukan setup project Firebase

- Memberi nama project firebase

![screenshot](images/02.png)

- Menonaktifkan **Google Analytics**

![screenshot](images/03.png)

- Mengaktifkan login email untuk **Firebase Authentication**

![screenshot](images/04.png)

- Mengaktifkan **Cloud Firestore**

![screenshot](images/05.png)

- Pilih opsi **test mode**

![screenshot](images/06.png)

- Pilih **Firestore location**

![screenshot](images/07.png)

- Lalu klik **enable** untuk mengaktifkan

### 3. Mengkonfigurasi Firebase

- Mengkonfigurasi dependensi

  Menjalankan perintah berikut pada terminal

  `flutter pub add firebase_core` digunakan untuk plugin **Firebase Flutter**.

  `flutter pub add firebase_auth` mengintegrasikan **Otentikasi Firebase**.

  `flutter pub add cloud_firestore` mengakses penyimpanan data **Cloud Firestore**.

  `flutter pub add provider` digunakan untuk utilisasi Firebase. 

- Menginstall Flutterfire

  **Flutter CLI** merupakan sebuah interface baris perintah pada flutter yang digunakan untuk mengkonfigurasi project untuk mengintegrasikan pada Firebase. Menjalankan perintah berikut pada terminal. 

  `dart pub global activate flutterfire_cli`. 

- Mengkonfigurasi Apps

  Untuk melakukan konfigurasi app, dapat menggunakan perintah `flutterfire configure` pada terimal.

- Konfigurasi macOS

  Menambahkan baris program berikut pada direktori **macos/Runner/DebugProfile.entitlements**.

  ```
  <key>com.apple.security.network.client</key>
  <true/>
  ```

  Menambahkan baris program berikut pada direktori **macos/Runner/Release.entitlements**.

  ```
  <key>com.apple.security.network.client</key>
  <true/>
  ```

### 4. Menambahkan **user sign-in** (RSVP)

Berikut ini hasil penambahan **user sign-in** pada kode program 

![screenshot](images/08.png)

![screenshot](images/09.png)

![screenshot](images/10.png)

![screenshot](images/11.png)

![screenshot](images/12.png)

![screenshot](images/13.png)

![screenshot](images/14.png)

![screenshot](images/15.png)

![screenshot](images/16.png)

![screenshot](images/17.png)

![screenshot](images/18.png)

![screenshot](images/19.png)
