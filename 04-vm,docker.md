### Seorang DevOps sering menggunakan **Virtual Machine dan Docker** untuk memudahkan pekerjaannya, menurut pendapatmu mengapa dia harus menggunakan *tools* tersebut ?

![vm vs docker](https://raw.githubusercontent.com/fembi/dumbway-fembi-isnanto/main/gambar/vm%20docker.jpg)

Pengunaan teknologi vm bertujuan untuk Ketika tahap pengujian sebuah teknologi atau infra baru tidak menganggu sistem operasi utama/host os. Karena vm berjalan mandiri/memiliki sistem operasi sendiri yang berjalan diatas teknologi hypervisor atau sering kita serbut virtualisasi diatas host os. Tetapi teknologi ini membutuhkan resorce yang cukup besar.\

Berbeda dengan docker/container sejenis, dimana Teknik isolir/isolasi sebuah program/aplikasi dapat dibangun tanpa perlu sebuah os tambahan. Dan berdiri diatas sistem operasi utama. Dengan mengunakan docker proses build dan destroy app lebih mudah karena sudah disediakan beberapa template contoh docker hub. Dengan mengunakan teknologi container memperkecil pengunaan resource.