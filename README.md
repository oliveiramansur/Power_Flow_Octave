# Power_Flow_Octave
Octave (Matlab) implementation for the Power Flow solution using Newton-Raphson Method

Theses functions will use the newton-raphson method to obtain the states of the shoosen power system and also the power injection and flows using the Jacobian matrix (partial derivates of V and Theta).
Any question and suggestion, contact me > email: oliveiramansur@gmail.com

  1. Estrutura dos CSV
Todos os valores elétricos em PU decimal. Todos os angulos em radianos

BUS: % nd   V    Ang.    Pg      Qg      PL      QL      Gs       jBs    Type    Shunt ELement
     % (1) (2)   (3)     (4)     (5)     (6)     (7)     (8)      (9)    (10)        (11)
     
     
     
     
LINE: % Bus.From   Bus.To    R pu    X pu      Bs pu      Type      Fase shifting angle     
      % (1)         (2)      (3)     (4)        (5)        (6)             (7)     
      
 obs: type 0=LT; type1= Trafo
