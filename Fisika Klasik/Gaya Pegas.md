# Rumus
![[Pasted image 20220508121711.png]]

Gaya Pegas datang dari sebuah hukum yang bernama **Hukum Hooke** yang menyatakan bahwa sebuah pegas memiliki sebuah **Gaya Pemulih**. Kita panggil gaya pemulih soalnya pegasnya selalu ke arah kesetimbangan (misalnya titik 0)

## Gaya Pemulih
Misal suatu pegas dipress atau ditarik dengan suatu gaya sebesar $F_{s} = ma_{x}$. Kemudian, pegas akan memiliki suatu gaya pegas sebesar $F_{T}=kx$. Karena pegas tidak dipercepat, maka $\sum\limits F= F_{s}+F_{t}=0$ atau
$$ma_{x}+kx=0$$
Persamaan tersebut memiliki persamaan gerak yaitu
$$\frac{d^{2}x}{dt^{2}}+ \frac{k}{m}x=0$$
Atau, persamaan tersebut dapat dicari $F_s$ sebagai berikut
$$ma_x=-kx$$
> $$F_{s}= -kx$$


Sehingga rumus tersebut dapat disesuaikan vektornya menjadi :

> $$F = k \triangle x$$
> $F$ = Gaya Pegas
> $k$ = Konstanta Pegas
> $\triangle x$ = Perubahan Panjang 

Konstanta Pegas didapatkan dari perpaduan antara Modulus Elastisitas dan Gaya, Bisa dicek di [[Elastisitas]]


## Frekuensi Angular Pegas
Apabila disamakan dengan Hukum Newton II,  percepatan dari pegas dapat diketahui sebagai berikut
$$F=ma =-kx$$
$$a = \frac{-k}{m}x$$
Setelah itu, kita ketahui rumus percepatan pada [[Osilasi#Percepatan Osilasi]], dan dapat kita masukkan sehingga
$$-w^2x=\frac{-k}{m}x$$
> $$w = \sqrt{\frac{k}{m}}$$
> $w$ = Frekuensi Angular (rad/s)
> $k$ = Konstanta pegas
> $m$ = Massa (kg)

## Periode Pegas
>$$T = \frac{2\pi}{w}=2\pi \sqrt{\frac{m}{k}}$$
>$T$ = Periode (sekon)

## Frekuensi Pegas
>$$f = \frac{1}{T}= \frac{1}{2\pi}\sqrt{\frac{k}{m}}$$
>$f$ = Frekuensi (Hz)

## Sudut Fase
Estimasi dari sudut fase sebagai berikut
> $$x(t) = A\cos(wt+\phi)$$
> $\phi$ = Sudut fase

Dengan sudut fase merupakan sudut awal dari objek sebelum berosilasi
***Contoh :***
![[Pasted image 20221107093043.png|300]]
Saat t = 0, objek sudah berada pada A. Sehingga 
$x(0) = A \cos (w.0+\phi) = A cos(\phi)=A$  

Oleh karena itu, diperoleh
$cos(\phi) = 1$
$\phi = \cos^{-1}(1) = 0$

***Contoh 2 :***
![[Pasted image 20221107093343.png|300]]
Saat t = 0, objek berada pada 0 sehingga
$x(0) = A \cos(w.0 + \phi) = A\cos(\phi)= 0$

Diperoleh
$\cos(\phi) = 0$

Ada dua kemungkinan, yaitu $\cos(90)$ atau $\cos (270)$. Maka, kita cari pake persamaan kecepatan
$v(0) = -Awsin(w.0+\phi) = -Aw sin(\phi) = Aw$

Jadi $Aw$ karena dia kecepatannya ke arah luar pegas sehingga
$sin(\phi) = -1$
$\phi = sin^{-1} (-1) = 270$


## Kekekalan Energi Pegas
![[Pasted image 20220513183823.png]]

### Energi Kinetik Pegas
>$$EK=\frac{1}{2}mv^{2} $$$$EK_{pegas}=\frac{1}{2}mw^{2}A^{2}\sin^{2}(wt)$$

### Energi Potensial Pegas
>$$EP=\frac{1}{2}kx^2$$ $$EP_{pegas}=\frac{1}{2}mw^2A^{2}\cos^{2}(wt)$$
>$$EP_{pegas}= \frac{1}{2}k(A\cos(wt))^2$$

### Energi Mekanik Pegas
>$$EM=EK+EP=\frac{1}{2}m(Aw)^{2}=\frac{1}{2}kA^{2}$$

