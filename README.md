En este TXT  existe una funcion PL/SQL que toma un numero en formato VARCHAR y lo conviente en alfanumerico
partiendo por el numero 1 y llegando hasta la Z

EJ:
1 , 2 , 3 , 4 , ... , 8 , 9 , A , B , C , D , ... , Z

Al llegar a la Z se le agrega un caracter mas partiendo por el 1 

Ej:

X , Y , Z , 10 , 11 , 12 , 13 , ... , 19 , 1A , 1B , ... , 1Z , 21 , .... , 2Z

En terminos de combinaciones creadas es 
36^x - 1
donde X es el numero de caracteres que tenga
es decir con un solo caracter existen 35 opciones llaque no se cuenta el 0
pero con 2 caracteres si tomamos el 0 en los numeros 10,20,A0,B0,C0,etc.. y hay 1295 opciones

