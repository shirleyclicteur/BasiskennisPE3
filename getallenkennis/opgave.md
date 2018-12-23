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
  
##van decimaal naar binair

845/2 = 422  rest 1
422/2 = 211  rest 0
211/2 = 105  rest 1
105/2 = 52   rest 1
52/2  = 26   rest 0
26/2  = 13   rest 0
13/2  = 6    rest 1
6/2   = 3    rest 0
3/2   = 1    rest 1
1/2   = 0    rest 1

845 binair is 1101001101
