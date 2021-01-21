# Soil Moisture Control

*Read this in other languages: [English](README.en.md), [Romanian](README.md).*

Proiectul presupune implementarea unui sistem prin care utilizatorul poate ajusta umidatea solului prin intermediul unei pompe de apă controlată printr-un telefon. Se folosește un senzor de umiditate a solului pentru a verifica în permanență dacă trebuie ajustată umiditatea sau nu. Utilizatorul poate vedea mereu procentul de umiditate și în momentul în
care acesta a scăzut poate alege să controleze pompa de apă în mod manual sau în mod automat. În modul manual, se poate porni și opri pompa în permanență. În modul automat, pompa va porni pentru o periodă de timp în care umiditatea solului va crește.

## Componente
  - [Microcontroller XMC 2Go](#Microcontroller-XMC-2Go)
  - [Modul Bluetooh HC-05](#Modul-Bluetooh-HC-05)
  - [Senzor umiditate sol](#Senzor-umiditate-sol)
  - [Releu 5V](#Releu-5V)
  - [Pompa de apa](#Pompa-de-apa)
  
### Microcontroller XMC 2Go
Acest microcontroller are rolul de a controla pompa de apă prin intermediul unui releu și de a prelua informații de la senzorul de umiditate.
<p align="center">
  <img src="https://lh5.googleusercontent.com/08mrpW-P9tvrNUtpExyJ_qcaxljHNjZQZBeHNrqWRyvXTZ1cDtX7ZxZzdLkq-Ul7oYX7pG5jGxJgs0timrxEDGN2IaeYG7jXJ3d23V2GTod34QS6loj0qe1Mxpi_NtAZ7ZKge4p0">
</p>

### Modul Bluetooh HC-05
Acest modul permite o conexiune Bluetooth între microcontroller-ul XMC 2Go și un dispozitiv mobil.
<p align="center">
  <img width="350" height="300" src="https://nandgeek.com/wp-content/uploads/2016/05/hc05.png">
</p>

### Senzor umiditate sol
Are rolul de a colecta informațiile legate de umiditatea solului.
<p align="center">
  <img width="300" height="300" src="https://s13emagst.akamaized.net/products/15573/15572752/images/res_ca0b5e3e498910e1bf6765b0232578aa.jpg">
</p>

### Releu 5V
Permite controlarea pompei de apă.
<p align="center">
  <img width="300" height="300" src="https://ardushop.ro/4570-large_default/modul-releu-1-canal.jpg">
</p>

### Pompa de apa
<p align="center">
  <img width="300" height="300" src="https://electronicgadgets.ro/726-large_default/pompa-apa-sumersibila-25-6v-80-120l-ora.jpg">
</p>
  
## Schema circuitului
<p align="center">
  <img src="https://i.ibb.co/xm0j4Qv/Screenshot-1.png">
</p>
