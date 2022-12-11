# Buku Ini (Meta)

Buku ini diproduksi menggunakan MyST markdown yang diconvert menjadi HTML. Di belakang layar, kami menggunakan ```Jupyter-book``` dengan Python yang di belakangnya menggunakan ```sphinx```. Ini merupakan mesin pengubah markdown {octicon}`arrow-right;1em` HTML yang umum digunakan di dunia dokumentasi. Misal, dokumentasi modul ```Pandas```, modul populer Python untuk analisis data tabular, menggunakan ```sphinx``` dengan tema pydata. Namun, ```sphinx``` memiliki kontrol yang sangat granular, dan secara syntax, ```Jupyter-book``` dirasa lebih sederhana.

## Cloud Computing

Buku ini hidup di https://tentang.rekayasadata.co.uk yang membawa anda pada sebuah _virtual machine_ (VM) di Google Cloud. Buku ini sendiri merupakan demonstrasi sederhana aplikasi _cloud computing_ dalam memberikan solusi terhadap masalah-masalah perpetaan. Saat ini, VM ini hanya berperan sebagai web-server ```NGINX``` dengan protokol HTTP dan {octicon}`lock;1em` HTTPS.

```{image} ./img/compute_engine.png
```

Selebihnya tentang peran Cloud Computing di RDS ada di bagian [Pola Kerja](how_we_work).

## Edit Buku Ini

Pembaca (iya, anda!) dapat mengedit buku ini! Buku ini merupakan proyek _open source_ yang artinya semua orang dapat berkontribusi. Anda memerlukan pengetahuan dasar tentang git, github, dan fork. 

Secara singkat

1. _fork repository_ buku ini
2. buat perubahan dalam _fork_ di akun personal github anda
3. membuat _pull request_ dengan _repository_ yang telah di-_fork_

Ini adalah cara kerja _fork_ dengan git. Informasi lebih lengkat ada dalam [tutorial berikut](https://www.atlassian.com/git/tutorials/comparing-workflows/forking-workflow).

Selengkapnya tentang bagaimana kontributor RDS bekerja ada dalam [Pola Kerja](how_we_work) kontributor.