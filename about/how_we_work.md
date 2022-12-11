# Pola Kerja

Kontributor RDS merupakan masyarakat Indonesia, namun beberapa dari kami tinggal di UK dan beberapa di Indonesia. Tahun depan, siapa tahu? Inginnya sih saya menjadikan RDS sebagai fenomena perpetaan global masyarakat Indonesia yang tersebar di seluruh dunia. _however_, sepertinya jalan masih panjang. _nevertheless_, kami terpisah jarak dan zona waktu. Ini merupakan tantangan tersendiri terutama oleh zona waktu. Pagi di UK merupakan sore di Indonesia; kami berjarak 7-jam.

Ada beberapa _merits_ dari tantangan ini:
- saat kontributor Indonesia tidur, kontributor UK bekerja, dan sebaliknya.
- jarak bukan merupakan syarat utama bekerja, di mana pun kami berada, kami akan tetap berkarya.

Berikut merupakan arsitektur pola kerja kami.

```{image} ./img/pola_kerja.png
```

## {octicon}`git-pull-request;1em;sd-bg-light sd-text-muted` Git 

Kami dapat bekerja dengan mengadopsi Git workflow. Dengan Git Workflow, kami mengembangkan kode-kode dengan sinergi dan independen. Dengan repository sentral dengan github, kami dapat bekerja tanpa batas geografi dalam menjawab pertanyaan __di mana__. 

:::{figure} https://wac-cdn.atlassian.com/dam/jcr:8f00f1a4-ef2d-498a-a2c6-8020bb97902f/03%20Release%20branches.svg?cdnVersion=670

sumber: [Atlassian](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow)
:::

Setiap proyek yang kami kerjakan memiliki repository ```.git``` yang berada di Github; termasuk buku ini! Buku ini merupakan salah satu proyek open source yang akan diurus selama satu tahun, dan selayaknya open source, pembaca dapat ikut berkolaborasi dengan RDS.

```{admonition} Repository Buku Ini
:class: note
Buku yang anda baca saat ini merupakan proyek _open source_. Tentang kontribusi, selengkapnya dalam [kontribusi](./kontribusi.md).

[<button class="btn btn-primary">Repository Buku Ini {fas}`arrow-right`</button>](https://github.com/sutanmufti/tentang-rekayasadata)
```

## {material-outlined}`cloud;1.25em;sd-text-muted sd-bg-light` _Cloud Computing_ 

```{figure} https://azurecomcdn.azureedge.net/cvt-031d78d2380ba572861f1fc8c37e624c906c3a38f054ceb6fb4444af53de1c2d/images/page/resources/cloud-computing-dictionary/what-is-cloud-computing/cloud-ill-2.svg
:align: center

Azure Cloud (sumber: [Azure](https://azure.microsoft.com/en-us/resources/cloud-computing-dictionary/what-is-cloud-computing/#cloud-computing-models))
```

Perkembangan teknologi virtualisasi melahirkan infrastruktur IT sebagai layanan. Ini bahasa formalnya "_cloud computing_". _Cloud computing_ rupanya hanya lah komputer orang lain yang kami sewa untuk melakukan tugas-tugas komputasi. Dampaknya, institusi-institusi tidak perlu investasi besar-besaran dalam infrastruktur IT; dan kami salah satunya. Kami hanya membayar sumber daya IT yang kami perlu semasa hidup proyek dan menghancurkan semua infrastruktur ketika proyek selesai. Dengan begitu, kami tidak memiliki _liability_ dan depresiasi asset.

## {octicon}`terminal;1em;sd-bg-light sd-text-muted` Python & Typescript

[Kontributor senior](./kontributor/kontributor.md) kami mengandalkan bahasa pemrograman Python dan Typescript dalam melakukan proyek riset _in house_. Kedua bahasa ini merupakan bahasa tingkat tinggi dengan _syntax_ sederhana untuk dimengerti manusia. Rekayasa Data Spasial bergantung pada data sains, dan Python merupakan alat yang paling optimal dalam memproses data bagi kami. Typescript, dengan Nodejs, merupakan bahasa yang kami gunakan untuk presentasi konten dan _server development_ di dalam _cloud_.

```{figure} ./img/pyjs.jpg
:align: center

sumber: Rini & Sutan, 2022
```


## {octicon}`database;1em;sd-bg-light sd-text-muted` Data Spasial, Peta, dan Cerita

Poin-poin di atas merupakan infrastruktur dan alat bekerja. Ujungnya kami mengakuisisi data spasial yang kami butuhkan dan mengolahnya untuk menjawab pertanyaan-pertanyaan spasial. Kami bergantung pada software _open source_ seperti Python, QGIS dan _Postgresql_ sebagai alat analisis dan database. _In the end_,kami menyampaikan cerita-cerita berdasarkan peta-peta yang kami produksi. 

Kunjungi https://rekayasadata.co.uk untuk cerita-cerita.

```{figure} ./img/database.jpg
:align: center

sumber: Rini & Sutan, 2022
```

