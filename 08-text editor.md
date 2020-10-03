### Bagaimana cara Anda memasukkan teks ke dalam sebuah file tanpa harus membuka file tersebut menggunakan editor seperti vim atau nano, menggunakan perintah linux? praktikkan serta berikan screenshotnya

masuk ke linux mentgunakan ssh. disini saya mengunakan mobaxterm sebagai aplikasi  untuk akses ssh
masukan ip server linux, username,dan password/jika mengunakan private key. dan port ssh.
setelah masuk jalankan perintah:\
jika mengunakan vi: vi namafile.txt , edit dengan menekan tombol i, isi filenya, jika sudah tekan esc, ketikan :wq yang berarti write and quit dari editor.\
jika mengunakan vim: vim namafile.txt edit dengan menekan tombol i, isi filenya, jika sudah tekan esc, ketikan :wq yang berarti write and quit dari editor.\
jika mengunakan nano: nano namafile.txt ediit isi file, jiika sudah ketikan ctrl+O dan ctrl+X untuk keluar.\
jika mengunakan pico: pico namafile.txt ediit isi file, jiika sudah ketikan ctrl+O dan ctrl+X untuk keluar.