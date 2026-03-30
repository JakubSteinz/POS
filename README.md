Ordinální hodnoty pro X (STEINZ) (mod 256)


| Písmeno | Ordinální hodnota |
| ------- | ----------------- |
| S       | 83                |
| T       | 84                |
| E       | 69                |
| I       | 73                |
| N       | 78                |
| Z       | 90                |
Součet tedy činí - 477

X = 477 (mod 256) = 221


Ordinální hodnoty pro Y (JAKUB) (mod 10)



| Písmeno | Ordinální hodnota |
| ------- | ----------------- |
| J       | 74                |
| A       | 65                |
| K       | 75                |
| U       | 85                |
| B       | 66                |
Součet tedy činí = 365

Y = 365 (mod 10) = 5



10.221.0.0/21





### Nastavování switche přes notebook

Nejdříve propojíme notebook se switchem přes RS232 port na notebooku a pak do zdířky jménem console dáme přípojku RJ45 na konci. Pak jdeme do aplikace terminal na notebooku a hned co budeme mít configurační terminál přes conf t, můžeme napsat hostname S1.

<img width="403" height="183" alt="Screenshot 2026-03-30 190435" src="https://github.com/user-attachments/assets/cfd7b25e-41b4-4b06-af0e-6b70729eff76" />



### Nastavení PC1

Po tom co si nastavíme switch, můžeme jít na PC1, kde si nastavíme IP adresu staticky a pak můžeme jít do command promptu a dát command *ipconfig*, kde pak dostaneme informace o IP adrese, masce, gateway, atd.

![[Pasted image 20260330190255.png]]


### Ping z PC1 na PC4

Zde se pingovalo z PC1, kde se nastavila IP adresa na 10.221.0.5 na PC4 s adresou 10.221.0.15, kde je viditelný výsledek úspěchu níže.

![[Pasted image 20260330190604.png]]
