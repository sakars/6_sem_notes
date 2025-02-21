# A

# Ā

# B

## Bāze

Mērījumu sistēma kā interpretēt kvantu stāvokli, veido no [[#Bāzes stāvoklis|bāzes stāvokļiem]]
Pamata sistēma ir $\ket{0}$, $\ket{1}$

Arbitrārai bāzei $\ket{\psi_1}$, $\ket{\psi_2}$


$$\ket{\psi_1}=a\ket{0}+b\ket{1}$$
$$\ket{\psi_2}=c\ket{0}+d\ket{1}$$
Ar ierobežojumiem
$$|a|^2+|b|^2=1$$
$$|c|^2+|d|^2 = 1$$
Stāvokļiem jābūt perpendikulāriem.

Populārs stāvokļu pāris: $\ket{-},\ket{+}$
$$\ket{-} = -\frac{1}{\sqrt{2}}\ket{0} + \frac{1}{\sqrt{2}}\ket{1}$$
$$\ket{+}=\frac{1}{\sqrt{2}}\ket{0}+\frac{1}{\sqrt{2}}\ket{1}$$



No [[2025-02-13#Manipulācijas]]


## Bāzes stāvoklis

Lineāra superpozīcija, piemēram, $\ket{0}$, $\ket{1}$ no kuras konstruē [[#Bāze|Bāzi]]



# C

# Č

# D

# E

# Ē

# F

# G

# Ģ

## Grover's search

Meklēšanas algoritms kvadrātiski ātrāk nekā tradicionāliem datoriem. $N$ tradicionāli, $\sqrt{N}$ ar Grover's search.

# H

## Hadamarda transformācija

[[#Transformācija]], kas plaši lietota kvantu algoritmos.

Transformācija $H$ - Hadamarda transformācija
$H\ket{0} = \frac{1}{\sqrt{2}}\ket{0}+\frac{1}{\sqrt{2}}\ket{1}$
$H\ket{1} = \frac{1}{\sqrt{2}}\ket{0}-\frac{1}{\sqrt{2}}\ket{1}$

Izsakāma kā spoguļattēls pa $22.5\degree$ asi

2x pielietota $H$ ir ekvivalenta $I$ - [[#Identitātes transformācija|Identitātes transformācijai]]



# I

## Identitātes transformācija

[[#Transformācija]], kuras rezultātā [[#Kvantu stāvoklis]] nemainās
$I\ket{0}=\ket{0}$, $I\ket{1}=\ket{1}$


# Ī

# J

# K

## Kompleksi saistītais

$$
(a+bi)^*= a-bi
$$

## Kubits

kvantu bits, eksistē superpozīcijā starp $\ket{0}$ un $\ket{1}$
Precīzāk, kubita vērtība ir $\alpha\ket{0} + \beta\ket{1}$, kur $\alpha, \beta \in \mathbb{C}, |\alpha|^2 + |\beta|^2 = 1$
kubita vērtība ir [[#Kvantu stāvoklis]]
## Kvantu dators

[[#Kubits|Kubitu]] reģistrs, kas ļauj mērīt, mainīt, manipulēt tos.

## Kvantu sapinums

Divas daļiņas, kuras ir "sapītas" spēj ietekmēt cita citu

## Kvantu stāvoklis

$$\alpha\ket{0}+\beta\ket{1}$$$$|\alpha|^2+|\beta|^2=1$$$$\alpha, \beta \in \mathbb{C}$$

Sastāv no 2 perpendikulāriem [[#Bāzes stāvoklis|bāzes stāvokļiem]]


# Ķ

# L

## Lineāra transformācija

Transformācija kas manipulē ar individuāliem elementiem...?

$$
U\left(\alpha\ket{0}+\beta\ket{1}\right)=\alpha U\ket{0}+\beta U\ket{1}
$$
>[!warning] Not entirely sure abt the definition

Lineāra transformācija, kuras rezultātā nemainās garums ir [[#Unitāra transformācija]]




# Ļ

# M

# N

# Ņ

# O

# P

# Q

## Qubit
![[#Kubits]]

# R

## Rekursija
![[#Rekursija]]

## Rotācijas transformācija

[[#Transformācija]], kas pagriež [[#Kvantu stāvoklis|kvantu stāvokli]] pa arbitrāru leņķi $\alpha$ 

Rotācijas transformācijai $R_\alpha$
$$
\left\{
\begin{alignedat}{1}
&\ket{0} \rightarrow &\cos\alpha\ket{0}+\sin\alpha\ket{1}\\
&\ket{1} \rightarrow -&\sin\alpha\ket{0}+\cos\alpha\ket{0}
\end{alignedat}
\right.
$$


# S

## Saistītā transformācija

Transponēta ar visiem elementiem kā [[#Kompleksi saistītais|kompleksi saistītiem]]

$$
\left(
\begin{matrix}
\alpha & \gamma \\
\beta & \delta
\end{matrix}
\right)^+
=
\left(
\begin{matrix}
\alpha^* & \beta^* \\
\gamma^* & \delta^*
\end{matrix}
\right)
$$
No [[2025-02-20#KS]]
# Š

# T

## Tensoru reizināšana

$$(a\ket{0} + b\ket{1}) \otimes (c\ket{0}+ d\ket{1}) = ac\ket{00} + ad\ket{01}+ bc\ket{10}+ bd\ket{11}$$

## Transformācija

Pārveido [[#Kvantu stāvoklis|kvantu stāvokli]] citā kvantu stāvoklī.

Iedalāma dažādos raksturojumos:
- [[#Lineāra transformācija]]
- [[#Unitāra transformācija]]

Daži transformāciju piemēri:
- [[#Identitātes transformācija]]
- [[#X transformācija]]
- [[#Z transformācija]]
- [[#Hadamarda transformācija]]
- [[#Rotācijas transformācija]]

Transformāciju var uzskatīt par matricu

$$
\begin{matrix}
\left\{
\begin{matrix}
U\ket{0} = \alpha\ket{0} + \beta\ket{1}\\
U\ket{1} = \gamma\ket{0} + \delta\ket{1}
\end{matrix}
\right.\\

U=
\left(
\begin{matrix}
\alpha & \gamma\\
\beta & \delta
\end{matrix}
\right)
\end{matrix}
$$



No [[2025-02-13#Transformācija]]


# U

## Unitāra transformācija

[[#Lineāra transformācija]], kura saglabā vektora garumu.
Unitārai transformācijai informāciju dzēst nevar.

Arbitrāra transformācija $U$ ir unitāra ja 

$$
\begin{matrix}
U\ket{0} = a\ket{0}+b\ket{1}\\
U\ket{0} = c\ket{0}+d\ket{1}\\
\left(
\begin{matrix}
a\\b
\end{matrix}
\right)
\text{ perpendikulārs }
\left(
\begin{matrix}
c\\d
\end{matrix}
\right)\Leftrightarrow

\left(
\begin{matrix}
a\\b
\end{matrix}
\right)
\bot
\left(
\begin{matrix}
c\\d
\end{matrix}
\right) = 0
\Leftrightarrow
a^*c+b^*d=0

\\

\left|\left(
\begin{matrix}
a\\b
\end{matrix}
\right)\right| = 
\left|\left(
\begin{matrix}
c\\d
\end{matrix}
\right)\right| = 
1 \Leftrightarrow |a|^2+|b|^2 = |c|^2+|d|^2 = 1
\end{matrix}\\
$$

>[!note] Perpendikularitātes aprēķinā tiek izmantots [[#Kompleksi saistītais|kompleksi saistītā]] skaitļa operācija $*$ 

$U$ ir unitāra ja 
$$
\begin{matrix}
\left\{
\begin{matrix}
U\ket{0} = \alpha\ket{0} + \beta\ket{1}\\
U\ket{1} = \gamma\ket{0} + \delta\ket{1}
\end{matrix}
\right.\\

U=
\left(
\begin{matrix}
\alpha & \gamma\\
\beta & \delta
\end{matrix}
\right)\\
U^+=
\left(
\begin{matrix}
\alpha^* & \beta^*\\
\gamma^* & \delta^*
\end{matrix}
\right)\\
U^+U=I\\
\end{matrix}
$$

Jebkurai unitārai transformācijai $U$, apgrieztā transformācija ir vienāda ar [[#Saistītā transformācija|saistīto transformāciju]].

$$
U^+ = U^{-1}
$$



No [[2025-02-13#Transformācija]]

Skatīt [[#Transformācija]]

# Ū

# V

# W

# X

## X transformācija

[[#Transformācija]], kas apmaina vietām [[#Bāzes stāvoklis|bāzes stāvokļus]]

$X\ket{0}=\ket{1}$, $X\ket{1}=\ket{0}$

# Y

# Z

## Z transformācija

[[#Transformācija]], kas apvērš stāvokli ap $\ket{0}$ asi
$Z\ket{0}=\ket{0}$, $Z\ket{1}=-\ket{1}$

$ZZ= I$
[[#Identitātes transformācija]]



# Ž
