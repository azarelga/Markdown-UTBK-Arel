	# Table Of Contents
- [Definisi](Fisika%20Klasik/Dinamika%20Rotasi.md#Definisi)
- [Rumus - Rumus](Fisika%20Klasik/Dinamika%20Rotasi.md#Rumus%20-%20Rumus)
	- [Inersia](Fisika%20Klasik/Dinamika%20Rotasi.md#Inersia)
	- [Kecepatan dan Percepatan Sudut](Fisika%20Klasik/Dinamika%20Rotasi.md#Kecepatan%20dan%20Percepatan%20Sudut)
	- [Torsi](Fisika%20Klasik/Dinamika%20Rotasi.md#Torsi)
	- [Momentum Angular](Fisika%20Klasik/Dinamika%20Rotasi.md#Momentum%20Angular)
	- [Kerja dan Energi](Fisika%20Klasik/Dinamika%20Rotasi.md#Kerja%20dan%20Energi%20pada%20Rotasi)

# Definisi
Gerak Rotasi adalah suatu gerak mekanika gerak linear yang diubah menjadi gerak rotasi (perputaran)
![[Pasted image 20220428140306.png]]

# Inersia
**Momen Inersia** adalah kemampuan benda untuk menahan suatu gerakan rotasi. Suatu momen inersia dipengaruhi sama bentuk dan massa. Contohnya cincin berongga dan cincin pejal akan berotasi berbeda.
![[Pasted image 20221026092145.png]]

### Teorema Steiner
Diketahui *Teorema Steiner* (buat mindahin sumbu putar satu ke sumbu putar lain) yang menyatakan bahwa momen inersia ($I$) pada suatu sumbu yang sejajar dan berjarak $d$ dari sumbu yang melalui pusat massa dinyatakan dengan :
![[Pasted image 20221026091917.png]]
>$$I = I_{CM} + Md^2$$
> $I$ = momen inersia pada sumbu putar baru
> $I_{CM}$ = momen inersia awal
> $M$ = massa benda tegar
> $d$ = jarak antara sumbu putar baru ke sumbu putar awal (pergeseran sumbu putar)

# Kecepatan dan Percepatan Sudut

#### Kecepatan Sudut
> $$\omega = \frac{d\theta}{dt}$$
> $\omega$ = Kecepatan Angular atau Sudut

Apabila disangkut-pautin sama Kecepatan, dia jadi

>$$v = \frac{ds}{dt}=r\frac{d\theta}{dt} = \omega r$$

Sehingga,

>$$\omega = \frac{v}{r}$$

#### Percepatan Sudut
>$$\alpha = \frac{dw}{dt}$$
> $\alpha$ = Percepatan angular atau sudut

Kalo kita turunin, 

$$a = \frac{dv}{dt}= \frac{d(wr)}{dt}=\alpha r$$

Sehingga

>$$\alpha=\frac{a}{r}$$

#### GLBB Rotasi
Selain itu, rotasi bisa mengalami GLBB dimana rumusnya sebagai berikut :
>1. $\omega_{t} = \omega_{o} + \alpha t$ 
>2. $\theta = \omega_{o} t + \frac{1}{2}\alpha t^{2}$ 
>3. $\omega_{t}^{2} = \omega_{o}^{2}+2\alpha \theta$   

# Torsi

>$$\tau =Fr$$

Gini
$\sum\limits F =ma$

Kita kalikan dengan jari - jari
$\sum\limits F .r= ma.r$

Sehingga
$\sum\limits \tau = m\alpha r^{2}$  

Maka 
> $$\sum\limits \tau = I\alpha$$

# Kerja dan Energi pada Rotasi

#### Energi Kinetik Rotasi
>$$K_{rotasi}= \frac{1}{2}Iw^2$$

Total energi kinetik pada **benda yang menggelinding tanpa tergelincir** adalah
>$$K = K_{translasi}+ K_{rotasi}$$

#### Kekekalan Energi Rotasi
>$$E_{m}=E_{k}+ E_{Ppegas}=  \frac{1}{2}Iw^{2}+ \frac{1}{2}k\theta^2$$

Pada rotasi, energi potensial tu gaada. Ketinggian bukan jadi faktor pengganggu pada dinamika rotasi. Mau setinggi apapun, kerja rotasi gabakal berubah dan gabakal terpengaruhi. Jadi, energi potensial pada rotasi diabaikan.

#### Kerja
>$$W = \tau \theta$$

#### Daya
>$$P = \tau \omega$$

Daya didapatkan dari $P = \omega/t = \frac{2\theta}{t}=2\omega$. Rumus ini analog dengan $P = Fv$


# Momentum Angular
Momentum Angular adalah Momentum ([[Momentum dan Impuls]]) yang bersifat melingkar dan konstan. **Momentum Angular** adalah daya hancur atau sulitnya dihentikan dari suatu objek yang berputar. 

>$$L=P. r = mvr=mwr^2$$
> $w$ = Kecepatan Sudut (rad)
> $r$ = Jarak objek ke pusat

> Perlu diketahui bahwa L bersifat konstan, jadi mau dibandingin sama berapa aja (asal sistemnya sama), mereka bakal sama. Sehingga, dapat kita temukan bahwa
> $L_{1}= L_{2}$
> $m_{1} \ v_{1} \ r_{1}= m_{2} \ v_{2} \ r_{2}$
> 
> Karena sistemnya sama, maka $m1$ dan $m2$ dapat dicoret (objeknya sama cok)
> $v_{1} \ r_{1}= v_{2} \ r_{2}$
> 
> Maka, kita mendapatkan sebuah perbandingan dimana :
> $$\frac{v_1}{v_2}=\frac{r_{1}}{r_{2}}$$


# Kesetimbangan Benda Tegar
Penjumlahan vektor gaya pada kesetimbangan benda tegar harus sama dengan 0
>$$\sum\limits F = 0 $$
>$$\sum\limits F_x =0,\sum\limits F_y =0,\sum\limits F_z =0 $$