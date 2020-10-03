### CI/CD (_Continuous Integration/Continuous Development_) merupakan hal yang sering ditemui oleh seorang DevOps. Menurut pendapatmu mengapa CI/CD diperlukan, dan berikan gambaran diagram kerjanya (Workflow) ?!

![ci/cd workflow](https://raw.githubusercontent.com/fembi/dumbway-fembi-isnanto/main/gambar/ci%20cd%20workflow.JPG)

dalam pengembangan product bermodelkan git flow, akan tiba saatnya melakukan aktivitas merge Dalam melakukan merge tersebut, terkadang akan menimbulkan konflik — konflik yang tidak diinginkan. karena terjadinya perbedaan branch yang sedang dikerjakan dengan branch master.

Hal ini tentu akan menghabiskan waktu untuk menyelesaikan merge conflict. Karena banyaknya merge conflict ini sangat berbanding lurus dengan seberapa besar perbedaan branch satu dan yang lainnya. Dan besar perbedaan branch juga sangat terpengaruh oleh seberapa lama umur dari branch tersebut.

Solusi dalam pemecahan masalah tersebut diciptakanlah CI, CI merupakan proses pengecekan merge secara otomatis, sehingga ketika merge request akan dilakukan pengecekan apakah branch iitu sudah memenuh syarat atau blm, baik dari segi test,linter, dan build. Setelah itu akan dicek apakah diperlukan mengatasi merge konflik, semua hal akan dilakukan secara otomatis. Sehinga tidak membebankan developer. Secara garis besar CI melakukan proses testing dari suatu produk.

Sedangkan CD memastikan secara otomatis setiap release yang siap dipakai sudah lulus test dan siap di deploy. Sehingga hasil proses otomatis dan cepat yang dihasilkan. Perbedaan utama antara CI dan CD,CI merupakan produk yang dapat dijalankan tanpa adanya error. Sedangkan CD ini menghasilkan produk yang sudah dapat dilakukan release secara otomatis.