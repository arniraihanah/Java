## MyConfig

'MyConfig.java' adalah kelas yang mengatur koneksi ke database MYSQL(method connection) dengan mendeklarasikan String DB_URL,DB_USER,DB_PASS untuk menyimpan informasi ke dalam database.

## Controller
'DatabaseCOntroller.java' adalah kelas yang mewarisi semua isi dan method dari dclass MyConfig.

Pada class ini juga ditambahkan beberapa method seperti getDatabase,readDB,insertDB,updateNamaDB,updateHargaDB,updateStokDB,deleteDB,getProdukbyNama untuk kebutuhan aplikasi yang lebih spesifik.

## Layouts
- 'DeleteData.java' : kelas yang mengatur untuk menghapus data dari isi tabel 'tb_produk' yang tersimpan di Database

- 'InsertData.java' : kelas yang mengatur untuk menambahkan data baru ke isi tabel 'tb_produk' yang tersimpan di Database

- 'Menu.java' : berfungsi sebagai kelas utama untuk mengakses setiap fitur pada tabel 'tb_produk'

- 'ReadData.java' : kelas yang mengatur untuk membaca atau mengambil data dari isi tabel 'tb_produk' yang tersimpan di Database

- 'UpdateData.java' : kelas yang mengatur untuk mengubah data dari isi tabel 'tb_produk' yang tersimpan di Database

## models
- 'Product.java' : kelas yang merepresentasikan product dalam sebuah program atau aplikasi.

Pada class ini ditambahkan beberapa atribut seperti id,nama,harga,jumlah dan juga ditambahkan method setter and getter untuk setiap atributnya.

## App

'App.java' : kelas yang berisi method main agar aplikasi dapat dijalankan.

<!-- ## Getting Started

Welcome to the VS Code Java world. Here is a guideline to help you get started to write Java code in Visual Studio Code.

## Folder Structure

The workspace contains two folders by default, where:

- `src`: the folder to maintain sources
- `lib`: the folder to maintain dependencies
- 'a' 

Meanwhile, the compiled output files will be generated in the `bin` folder by default.

> If you want to customize the folder structure, open `.vscode/settings.json` and update the related settings there.

## Dependency Management

The `JAVA PROJECTS` view allows you to manage your dependencies. More details can be found [here](https://github.com/microsoft/vscode-java-dependency#manage-dependencies). -->
