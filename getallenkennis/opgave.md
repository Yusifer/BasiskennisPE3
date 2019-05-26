# Hamming-bits 1110110

H1 | H2 | D3 | H4 | D5 | D6 | D7 |
--- | --- | --- | --- | --- | --- | --- |
  1 |   1  |   1 |  0   |  1  |   1 |    0 |
--- | --- | --- | --- | --- | --- | --- |
 X |       |       |      |      |       |      |  (1-bit)
--- | --- | --- | --- | --- | --- | --- |
 X |   V  |       |      |      |       |      | (2-bit)
--- | --- | --- | --- | --- | --- | --- |
 X |   V  |       |  V  |      |       |      | (4-bit)

 Resultaat: 0110110
 De data klopt niet, de fout bevindt zich bij H1.



 
> (845)10 = ()zd

> Van decimaal naar binair:

845 / 2 = 422, rest: 1
422 / 2 = 211, rest: 0
211 / 2 = 105, rest: 1
105 / 2 =   52, rest: 1
  52 / 2 =   26, rest: 0
  26 / 2 =   13, rest: 0
  13 / 2 =     6, rest: 1
    6 / 2 =     3, rest: 0
    3 / 2 =     1, rest: 1
    1 / 2 =     0, rest: 1

(845)10 = (1101001101)2

Binair naar Zoned Decimal:

1101 = negatief.

1101 0011 01 = **-845**

Voor zover de veel te beknopte uitleg over Zoned Decimals in de cursus verschijnt.