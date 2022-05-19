# CSS-Grid-WPU

# Rangkuman CSS GRID WPU

"Modul CSS *baru* untuk mendefinisikan sistem layout berbentuk grid dalam 2 dimensi (baris & kolom). "

# Terminologi/Istilah CSS Grid

* **Grid Container**
    "Element pembungkus grid, didefinisikan dengan menuliskan : 
    ```css
    display: grid;
    ```
* **Grid Item**
    "Element-element yang berada (1level) di dalam grid container"
* **Grid Line**
    "Garis horizontal(kolom) atau vertikal(baris) yang memisahkan grid menjadi beberapa bagian dan ditandai dengan angka."
* **Grid Cell**
    "Perpotongan/pertemuan antara baris dan kolom di dalam grid"
* **Grid Area**
    "Kumpulan lebih dari satu grid cell yang membentuk kotak"
* **Grid Track**
    "Ukuran/jarak angata 2 grid line, bisa horizontal(kolom) atau vertikal(garis)."
* **Grid Gap**
    "Jarak antar grid track/cell"

* **grid-template-columns & grid-template-rows**
    Mendefiniskan kolom/baris dengan cara menuliskan nilai dipisahkan oleh spasi. Nilai merepresentasikan ukuran **grid track** dan spasi merepresentasikan **grid line**

# Grid Properti
![Grid Properti](https://github.com/dulabdul/CSS-Grid-WPU/blob/main/Grid_properti.png)

## Special Function & Keywords

* **repeat**
    Menentukan ukuran **grid track** secara berulang

* **min-content & max-content**
    Menentukan seberapa besar ukuran **grid track** berdasarkan content pada sebuah item

* **minmax()**
    Menentukan ukuran minimal dan maksimal dari **grid track**

* **auto-fill & auto-fit**
    Menentukan jumlah item untuk berada pada **grid track**

# Grid Area & Grid Gap

* **grid-template-area**
    Mendefiniskan grid template menggunakan nama dari area yang ditulis pada property **grid-area** pada item.
    
# Grid Alignment

* **justify-items**
    Mensejajarkan grid-items pada sumbu horizontal

* **align-items**
    Mensejajarkan grid items pada sumbu vertikal

* **justify-content**
    Mengatur posisi seluruh grid-container pada sumbu horizontal.
    Ini bisa dilakukan ketika ukuran total grid lebih kecil dari ukuran containernya, biasanya ketika grid items nya menggunakan ukuran yang fixed(px)

* **align-content**
    Mengatur posisi seluruh grid-container pada sumbu vertikal.
    Ini bisa dilakukan ketika ukuran total grid lebih kecil dari ukuran containernya, biasanya ketika grid items nya menggunakan ukuran yang fixed(px)

* **grid-area**
    Menentukan nama area pada item sesuai dengan tempalte yang sudah dibuat sebelumnya melalui properti grid-template-areas.
    Bisa digunakan sebagai shorthand untuk grid-column-start, grid-column-end, grid-row-start, dan grid-row-end.

* **justify-self**
    Mengatur posisi item pada sebuah cell terhadap sumbu horizontal.

* **justify-self**
    Mengatur posisi item pada sebuah cell terhadap sumbu vertikal .