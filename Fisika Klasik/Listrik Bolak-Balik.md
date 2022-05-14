# Definisi
## Tegangan dan Arus AC

### Tegangan
Listrik AC dihasilkan oleh [[Induksi Elektromagnetik]]. Selain itu, voltase di AC antara lain :
>$$V_{t}=V_{max}sin(ωt+\theta_{0})$$
>$V_{t}$ = Volt yang ditanya
>$wt$ = $2\pi f t$ = Sudut Fase (frekuensi)
>$\theta_{0}$ = Sudut Awal (biasanya 0 kalo ga diketahui)
>$V_{max}$ = Tegangan Maximum (220 Volt di Indonesia)

Namun, tegangan pada rangkaian AC memiliki sifat
>$$V_{R} =IR$$
>$$V_C=I.X_C$$
>$$V_L=I.X_{L}$$

Sehingga tegangan pada setiap RLC tu beda beda

### Arus
Kemudian, arus di AC adalah :
>$$I = I_{max}.sin(ωt + \theta_{0})$$
>$I_{t}$ = Arus yang ditanya
>$I_{max}$ = Arus Maximum

> - Arus pada setiap rangkaian seri itu pasti sama semua 

Arus di AC memiliki sifat sebagai berikut
> $$I_R=I_L=I_C=I$$

![[Pasted image 20220428163005.png]]

### Note!
> - Nilai sesaat adalah besar AC pada suatu waktu tertentu.
> - Nilai maks adalah **besar AC maksimum yang dapat terjadi**. Nilai maks terbaca pada osiloskop. ($V_{maks},I_{maks}$) Biasanya terjadi pada saat $V_{t}$ pada saat frekuensi maximum
> - Nilai efektif adalah **besar AC yang setara dengan besar DC** **yang menghasilkan jumlah kalor** yang sama pada waktu yang sama. Nilai efektif terbaca pada alat ukur listrik. ($V_{eff},I_{eff}$) atau ($V_{RMS},I_{RMS}$)

Untuk mencari nilai maks, dapat di cari dengan
>$$ V_{eff} = \frac{V_{max}}{\sqrt{2}}$$
>$$ I_{eff} = \frac{I_{max}}{\sqrt{2}}$$

## Hukum Ohm AC
![[Pasted image 20220428215924.png]]
Hambatan pada listrik bolak - balik biasanya didefinisikan sebagai **Impedansi** ($z$), nah nanti impedansi nih dia tuh gabisa asal langsung jumlahin ([[Listrik Bolak-Balik#Impedansi]]) 

### Resistor (R)
> $$V_{max}= I_{max} R$$ 
>$$V_{eff}= I_{eff}R$$

Selain rumus hukum ohm biasa, resistor dapat berguna untuk mencari Daya suatu sistem
>$$P = V_{eff}I_{eff}= (I_{eff})^{2}R$$

### Induktor (L)
>$$x_{L}= w L$$
> $x_{L}$ = Hambatan Induktif (Ohm)
> $w$ = $2\pi f$
> L = [[Induktor]]

Untuk mencari Impedansi apabila pada suatu rangkaian hanya ada

### Impedansi
>$$ z = \sqrt{R^{2}+(x_{L}-x_{C})^{2}}$$

> $x_{L}$ sama $x_C$ tukeran tempat sesuai sama besar kecilnya. Yang penting yang dikurang tu harus lebih gede


## Frekuensi
Frekuensi bisa dicari kalo misalnya sesuatu yang disebut dengan **Resonansi** terjadi

Kenapa **Resonansi** terjadi?
- Arus Maksimum juga terjadi
-  $X_{L}= X_{c}$

Dari rumus $X_L=X_C$ kita dapat sederhanakan sehingga
$X_{L}= X_{C}$
$w.L = \frac{1}{w.C}$
$w^{2}=\frac{1}{LC}$
$w = \sqrt{\frac{1}{LC}}$

Karena kita ketahui dari rumus [[Gerak Harmonik Sederhana#Frekuensi]] bahwa $w = 2\pi f$
 $2 \pi f = \frac{1}{\sqrt{LC}}$
> $$f = \frac{1}{2\pi \sqrt{LC}}$$