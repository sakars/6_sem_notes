# A

## Abstraktā sintakse
Programmu attēlo abstraktā veidā.
Mērķis ir redzami, intuitīvi aprakstīt kā valoda izmantojama

Skatīt [[#Sintakse]]

No [[2025-02-04#Abstraktā sintakse]]

## Aksiomātiskā semantika
Semantika ar noteiktām sākuma un beigu stāvokļu īpašībām

Skatīt [[#Semantika]]

## Augšupejoša analīze

LR(0), LR(1), LR(k), GLR

Lasa ieejas tekstu un katru simbolu vai nu ieliek tekstā vēlākai apstrādei, vai arī šim simbolam kopā ar stekā jau ievietotiem simboliem pielieto kādu no likumiem "pretējā virzienā"

No [[2025-02-25#VSS]]
Skat. [[#Lejupejoša analīze]]
[LR parser - Wikipedia](https://en.wikipedia.org/wiki/LR_parser)
# Ā

# B

## Bezkonteksta gramatika

Veids, kā ar termināliem simboliem, netermināliem simboliem, produkcijas likumiem un sākuma neterminālo simbolu definē "valodu", kurai pieder konkrēti vārdi

Piemēram

$S\rightarrow AB$
$A\rightarrow aAb$
$A\rightarrow \epsilon$
$B \rightarrow bBc$
$B\rightarrow \epsilon$



## BNF (Bakusa-Naura Forma)

Gramatikas pieraksts balstīts uz termināļiem un netermināļiem

Skatīt arī [[#EBNF (Extended Backus-Naur Form)]]

# C

# Č

# D

## Dabiskā semantika
Saista programmas sākuma un beigu stāvokļus.

Skatīt [[#Semantika]]
# E

## EBNF (Extended Backus-Naur Form)

Paplašināta versija [[#BNF (Bakusa-Naura Forma)]].

Ļauj izmantot: 
- | - Vai simbolu var izmantot jebkurā vietā, ne tikai augšējā līmenī
- \[] - Neobligāta izteiksmes daļa
- {} - izteiksmes daļa kas var atkārtoties N reizes ($0\le N$)

# Ē

# F

# G

## Gramatika
![[#Bezkonteksta gramatika]]


# Ģ

# H

# I

# Ī

# J

# K

## Konkrētā sintakse

Programmatūras struktūra + pieraksta likumi
Tipiska konkrētas sintakses uzdošanas metode izmanto gramatikas t.s. [[#BNF (Bakusa-Naura Forma)]], [[#EBNF (Extended Backus-Naur Form)]]

No [[2025-02-18#Reminder]]
# Ķ

# L

## Lejupejoša analīze

LL(0), LL(1), LL(k), LL(\*)

- Automātā (stekā) ieliek gramatikas sākuma simbolu
- Katrā solī aplūko steka sākuma simbolu un teksta sākuma fragmentu
- Meklē ar kādu likumu jāizvērš steka pirmais simbols, ja teksta sākums ir tāds kāds dotais
- Nomaina steka pirmo simbolu ar atrastā likuma labās puses simbolu virkni



No [[2025-02-25#VSS]]
Skat. [[#Augšupejoša analīze]]
[LL parser - Wikipedia](https://en.wikipedia.org/wiki/LL_parser)

## Leksēma

Leksiskās analīzes vienums (token)
To parasti veido regulārā izteiksme.

No [[2025-02-25#VSS]]
# Ļ

# M

## Momentuzņēmums
![[#Programmas momentuzņēmums]]

# N

# Ņ

# O

# P

## ## Programmas momentuzņēmums
- Cik tālu programma ir tikusi (vieta programmā) $C$ - Stāvokļu kopa $c \in C$ - konkrēts stāvoklis
- Mainīgo vērtības ir saglabātas $\sigma \colon Var \rightarrow Val$   
Programmas stāvoklis $s = \left< c, \sigma \right>$ 

No [[2025-02-04#Programmas momentuzņēmums]]

# Q

# R

# S

## Semantika
Ko [[#Sintakse]] konstrukcijas nozīmē izpildes laikā.

Skatīt arī [[VSS_Jēdzieni#Strukturālā operacionālā semantika|Strukturālā operacionālā semantika]], [[VSS_Jēdzieni#Dabiskā semantika|Dabiskā semantika]], [[VSS_Jēdzieni#Aksiomātiskā semantika|Aksiomātiskā semantika]]

Veidots no [[2025-02-04#Semantika]]

## Sintakse
Konstrukcijas, jēdzieni valodā, kā tās attēlot.
Sintakses aprakstam jābūt
- Precīzam
- Neatkarīgam no realizācijas (formulējams kā standarts)
- Cilvēkam uztverams

Veidots no [[2025-02-04#Sintakse]]

## Strukturālā operacionālā semantika
Apraksta stāvokļu maiņas likumus (kkas līdzīgs automātam?)


# Š

# T

# U

# Ū

# V

# W

# X

# Y

# Z

# Ž
