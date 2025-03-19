# A

# Ā

# B

## Band-pass filtrs

Filtrs, kas atļauj tikai vidējās frekvences. Tos var veidot izmantojot [[#Low-pass filtrs|low-pass]] un [[#High-pass filtrs|high-pass]] filtrus.

# C

# Č

# D


## Decibels

Mērvienība ir `dB`.
To izsaka logaritmiskajā skalā. Tas izsaka signāla relatīvo izmaiņu.
deci-bels = viena desmitdaļa bela.

```
-20 dB -> *0.01
-10 dB -> *0.1
0   dB -> *1
10  dB -> *10
20  dB -> *100
```

$$
dB = 10 \log_{10}{\frac{P_1}{P_2}}
$$
Šeit $P$ ir jauda. $\text{Amplitūda} \sim \sqrt{\text{Jauda}}$ 
Tātad
$$
dB = 20 \log_{10}{\frac{A_1}{A_2}}
$$

Tā kā decibeli ir relatīva mērvienība to izmanto salīdzinot signālus vai arī salīdzinot pret kādu atskaites signālu. Viens piemērs ir izmantot cilvēka dzirdamības slieksni kā atskaites punktu
## Dekompozīcija

[[#Signāls|Signāla]] sadalīšana vairākos signālos.

No [[2025-02-26#Sintēze un dekompozīcija]]

## Delta funkcija

Arī Dirac delta function nepārtrauktiem signāliem vai Kronecker delta function diskrētiem signāliem.

funkcija, kurai vērtība ir 
$$
y[i]\left\{
\begin{matrix}
0, i\ne 0\\
1, i=0
\end{matrix}
\right.
$$
![[Pasted image 20250305095414.png]]

No [[2025-03-05#Konvolūcija]]

## Digitāla sistēma

Programmatūra, kas veic digitālu signālu apstrādi.

Digitālas sistēmas var:
- pārprogrammēt
- pārvietot dažādām aparatūrām
- Pavairot
- Nav atkarīgas no komponenšu precizitātes
- Rezultāts ir neatkarīgs no ārējiem faktoriem (piem. temperatūras)
- Vienkāršākas: Digitālas sistēmas bieži ir vienkāršākas nekā to analogie ekvivalenti.

No [[2025-02-05#DSP priekšrocības]]

## Digitālais filtrs

Digitālie filtri ir noderīgi, jo tiem ir ļoti daudz pielietojumu DSP

Populārākie ir:
- atdalīt signālu
- restaurēt signālu

Parasti filtri ir implementēti 2 veidos:
- [[#Konvolūcija]] ar [[#Impulsa signāls|impulsa signālu]]
- Rekursija

## Digitālo signālu apstrāde

Digitālā signālu apstrāde ir kā pārvērst kaut kāda mēra analogus datus digitālos datos (nepilnīga definīcija)

No [[2025-02-05#DSP]]
# E

# Ē

# F

## Frekvences reakcija

Signāls, kuru var iegūt pielietojot [[#Furjē transformācija|furjē transformāciju]] [[#Impulsa reakcija|impulsa reakcijai]]. Pretējā virzienā [[#Impulsa reakcija|impulsa reakciju]] var iegūt pielietojot [[#Inversā Furjē transformācija|inverso Furjē transformāciju]] frekvences reakcijai. Frekvences reakcija izsakāma [[#Decibels|decibelos]] pielietojot logaritmu frekvences reakcijai.

## Furjē dekompozīcija

[[#Dekompozīcija]], kas sadala [[#Signāls|signālu]] individuālās frekvencēs.

No [[2025-02-26#Sintēze un dekompozīcija]]
## Furjē transformācija

Matemātiska transformācija līknei.

Analogs signāls -> frekvences
laika domēns -> Frekvences domēns

Skatīt [[#Inversā Furjē transformācija]]

No [[2025-02-05#Furjē transformācija]]
# G

# Ģ

# H

## High-pass filtrs

Filtrs, kas dzēš zemās frekvences
Pretējs [[#Low-pass filtrs|low-pass filtram]]

## Histogramma

Grafiks, kurā atspoguļots gadījumu biežums konkrētam parametram

[Histogram - Wikipedia](https://en.wikipedia.org/wiki/Histogram)

No [[2025-02-12]]


## Homogenitāte

Princips, kuram jāseko sistēmai, lai tā būtu [[#Lineāras sistēmas|lineāra sistēma]]

$$
\begin{matrix}
x_1[t] \xrightarrow{s} y_1[t]\\
k \cdot x_1[t] \xrightarrow{s} k \cdot y_1[t]
\end{matrix}
$$

Vienkāršā valodā pastiprinot sistēmas ieejas signālu, pastiprināsies.

# I

## Impulsa dekompozīcija

[[#Dekompozīcija]], kura diskrētam [[DSP_Jēdzieni#Signāls|signālam]] paņem katru individuālo vērtību kā atsevišķu signālu.

## Impulsa reakcija

Signāls, kuru izmanto, lai apstrādātu signālu, viens no veidiem ir [[#Konvolūcija]]. Apstrādes rezultātā iegūst jaunu izvades signālu.

## Inversā Furjē transformācija

Veic pretējo darbību [[#Furjē transformācija|Furjē transformācijai]], pārvēršot frekvenču amplitūdas viļņu summas līknē.

Skatīt [[#Furjē transformācija]]

# Ī

# J

# K

## Kodols

Alternatīvs nosaukums [[#Impulsa reakcija|Impulsa reakcijai]]

## Komutatīva sistēma

2 [[#Lineāras sistēmas]] $A$ un $B$ ir komutatīvas, ja 

$$
x[t] \xrightarrow{A} i[t] \xrightarrow{B} y[t] 
\Leftrightarrow 
x[t] \xrightarrow{B} j[t] \xrightarrow{A} y[t]
$$

jeb sistēmas var pielietot mainītā secībā un izejas [[#Signāls]] nemainīsies.


## Konvolūcija

Veids kā apstrādāt signālu, kur var iegūt dažādas signālu īpašības.

No [[2025-03-05#Konvolūcija]]

## Korelācija

No [[2025-03-05#Korelācija]]


## Kvadrātiskā kļūda
Angl. [[#Variance]]

$$\sigma^2 = \frac{\sum^{N}_{i=0}{\left(x_i-\mu\right)^2}}{N}$$

No [[2025-02-12#Kvadrātiskā kļūda (variance)]]
# Ķ

# L

## Laika invariantas sistēmas

Sistēma, kurai nav svarīgs šī brīža laiks - tā strādā neatkarīgi no laika vērtības.

Laika invariantai sistēmai jāizpildās

$$
x[n+n_0] \rightarrow y[n+n_0]
$$

Ne visas [[#Lineāras sistēmas]] ir laika invariantas sistēmas.

No [[2025-02-26#Lineāras sistēmas]]

## Lineāras sistēmas

Sistēma, kura viena veida [[#Signāls|signālu]] pārveido citā.
Lineāras sistēmas seko [[#Superpozīcija|superpozīcijas principam]] un [[#Homogenitāte|homogenitātes principam]].

Ja signālu apstrādā lineāra sistēma, to iespējams sadalīt mazākos signālos un apstrādāt tos, vai savienot vairākus signālus kopā pirms laist caur sistēmai.


No [[2025-02-26#Lineāras sistēmas]]

## Low-pass filtrs

Filtrs, kas bloķē augstās frekvences.
Pretējs [[#High-pass filtrs|high-pass filtram]]

# Ļ

# M

## Mean
![[#Vidējais]]

## Mean absolute deviation
![[#Vidējā novirze]]
# N

# Ņ

# O

# P

## Probability Mass Function (PMF)

Arī *frequency function*

Kāda ir iespēja, ka vērtībai būs atbilstošā x vērtība.
Derīga diskrētiem mērījumiem.

[Probability mass function - Wikipedia](https://en.wikipedia.org/wiki/Probability_mass_function)


## Probability Density Function (PDF)

Nepārtraukta līkne, kas apzīmē relatīvo varbūtību, cik bieži dati notiks

[Probability density function - Wikipedia](https://en.wikipedia.org/wiki/Probability_density_function)


# Q

# R

# S

## Signāls

Viena parametra izmaiņas pret citiem.

No [[2025-02-26#Lineāras sistēmas]]

## Sintēze

Vairāku [[#Signāls|signālu]] apvienošana vienā.

No [[2025-02-26#Sintēze un dekompozīcija]]

## Skandas

Skaļrunis

## Soļa reakcija

Signāls, ko var iegūt, ņemot integrāli no [[#Impulsa reakcija|impulsa reakcijas]]. Pretējā virzienā, atvasinājums no soļa reakcijas ir impulsa reakcija.



## Superpozīcija

Vienotas [[#Lineāras sistēmas]] raksturīpašība, kas nozīmē, ka dažādu faktoru individuālā izmaiņas summa ir vienāda ar kopējo izmaiņu.

$$
\begin{matrix}
x_1[t]\xrightarrow{s} y_1[t]\\
x_2[t]\xrightarrow{s} y_2[t]\\
x_1[t]+x_2[t] \xrightarrow{s} y_1[t]+y_2[t]
\end{matrix}
$$

No [[2025-02-26#Lineāras sistēmas]]
# Š

# T

# U

# Ū

# V

## Variance
![[#Kvadrātiskā kļūda]]

## Vidējais
Angl. [[#Mean]]
$$\mu =  \frac{\sum^{N}_{i=0}{x_i}}{N}$$
Visu elementu summa dalīta ar to skaitu

No [[2025-02-12#Vidējais (mean)]]

## Vidējā novirze
Angl. [[#Mean absolute deviation]]

$$\mathit{MAD}=\frac{\sum^{N}_{i=0}{\left|x_i-\mu\right|}}{N}$$

No [[2025-02-12#Vidējā novirze (Mean absolute deviation)]]

## Vienības signāls

Signāls, kura amplitūda ir 0 visā diapazonā, izņemot $(1,1)$

$$
y=\left\{
\begin{matrix}
0, x \ne 1 \\
1, x =1
\end{matrix}
\right.
$$


# W

# X

# Y

# Z

# Ž
