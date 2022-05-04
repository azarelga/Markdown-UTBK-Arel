# Definisi
## Tegangan dan Arus AC
Listrik AC dihasilkan oleh [[Induksi Elektromagnetik]]. Selain itu, voltase di AC antara lain :
>$$V_{t}=V_{max}sin(ωt+\theta_{0})$$
>$V_{t}$ = Volt yang ditanya
>$wt$ = $2\pi f t$ = Sudut Fase (frekuensi)
>$\theta_{0}$ = Sudut Awal (biasanya 0 kalo ga diketahui)
>$V_{max}$ = Tegangan Maximum (220 Volt di Indonesia)

Kemudian, arus di AC adalah :
>$$I = I_{max}.sin(ωt + \theta_{0})$$
>$I_{t}$ = Arus yang ditanya
>$I_{max}$ = Arus Maximum

> - Arus pada setiap rangkaian seri itu pasti sama semua 


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
Frekuensi bisa dicari kalo misalnya $x_{L}= x_{C}$