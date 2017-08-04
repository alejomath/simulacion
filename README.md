# simulacion
taller 1
linea de codigos:
a=1;             genera la variable para el primer numero
b=1;             genera la variable para el segundo numero parte imaginaria la cual simpre sera 1 quedara estandar la aprte imaginaria
for j=1:100      for para generar cierta cantidad de primos gaussianos
    a=a+1;       sumarle una unidad a la primera variable apra volver a evaluar
    v=[a,b];     vector a mostrar los dos numeros parte real e imaginaria de los numeros primos gaussianos 
    if isprime(a^2+b^2)     evaluar si la suma de los numeros a y b al cuadrado cada uno es primo 
        disp(v)             en caso de ser primos imprime en pantalla los dos numeros como vector 
    end                     fin del if
end                         fin del for



ejemplos variando a 
     2    + 1i

     4    + 1i

     6    + 1i

    10    + 1i

    14    + 1i

    16    + 1i
    
    20    + 1i
   
    24    + 1i

    26    + 1i

    36    + 1i

    40    + 1i

    54    + 1i

    56    + 1i

    66    + 1i

    74    + 1i

    84    + 1i

    90    + 1i

    94    + 1i
