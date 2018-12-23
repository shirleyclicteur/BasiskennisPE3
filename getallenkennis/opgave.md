**hamming-opgave**

**1110110**

P0 is een pariteitscontrole van de bits die H0 bewaakt. 
=> P0 = H0 +D0 +D1 +D3 = 1 + 1 + 1 + 0 = 1

P1 is een pariteitscontrole van de bits die H1 bewaakt. 
=> P1 = H1 +D0 +D2 +D3 = 1 + 1 + 1 + 0 = 1

P2 is een pariteitscontrole van de bits die H1 bewaakt. 
=> P2 = H2 +D1 +D2 +D3 = 0 + 1 + 1 + 0 = 0

(P2P1P0)2=011=3 
Er is een fout op positie 3!
=> Na controle : Datacorrectie op positie 3 : 1100110 => Data : 0110 


##van decimaal naar hexadecimaal

(845)10 = ()16
 
 845/16 = 52    rest 13=D
 52/16  = 3     rest 4
 3/16   = 0     rest 3

 845 hexadecimaal is 34D

