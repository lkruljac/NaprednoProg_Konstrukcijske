# kruljac-kv
KV project, napredno programiranje

Napraviti modul koji predstavlja stog (engl. stack). Modul treba sadržavati funkcije za inicijalizaciju stoga, dodavanje elemenata u stog, brisanje n-tog elementa stoga,brisanje svih elemenata stoga te ispis svih elemenata stoga. Modul izvesti kao dinamičku biblioteku koja se povezuje prilikom pokretanja programa.Zatim napisati funkciju koja kreće od zadanog piksela i pronalazi sve piksele različite vrijednosti koji su mu susjedni, kao i sve piksele različite vrijednosti koji su susjedi njegovim različitim susjedima, itd. Uzeti u obzir da je na pretpostavljenom namjenskom procesoru maksimalna dubina poziva funkcija 4. Na primjer, ako je na donjoj slici zadan piksel s indeksom (4,4) (broj 1 je podebljan i podvučen), onda program treba pronaći i ispisati koordinate zatamnjenih piksela.

0 0 0 0 0 0 0 0 0 0
0 0 0 0 0 0 0 0 0 0
0 0 1 1 0 1 1 0 0 0
1 0 0 1 1 1 1 0 0 0
0 1 0 1 1 1 0 0 1 1
0 1 0 0 1 1 0 0 1 1
0 0 0 0 1 0 1 0 0 0
0 0 0 1 1 0 0 0 0 0
