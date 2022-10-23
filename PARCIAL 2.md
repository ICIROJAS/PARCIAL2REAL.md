# FUNDAMENTOS DE PROGRAMACION
## PORTAFOLIO
## PROBLEMAS RESUELTOS EN CLASE
#### DIAGRAMA 1
![](https://github.com/ICIROJAS/PARCIAL2REAL.md/blob/main/1ER%20PRBLEMA%20WHILE.jpg)
![](https://github.com/ICIROJAS/PARCIAL2REAL.md/blob/main/1ER%20PROBLEMA%20DOWHILE.jpg)
![](https://github.com/ICIROJAS/PARCIAL2REAL.md/blob/main/1ER%20PROBLEMA%20FOR.jpg)

**PRUEBA DE ESCRITORIO**
| S=C+S | C=C+1 | C<=10 | S=C+S | C=C+1 | C<=10 |S=C+S | C=C+1 | C<=10|S=C+S | C=C+1 | C<=10|S=C+S | C=C+1 | C<=10|S=C+S | C=C+1 | C<=10|S=C+S | C=C+1 | C<=10|S=C+S | C=C+1 | C<=10|S=C+S | C=C+1 | C<=10|S=C+S | C=C+1 | C<=10|   S  |
| ----------- | ----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |
|  1 |  2  | SI |  3 |  3  | SI | 6 |  4  | SI | 10 |  5  | SI |15 |  6  | SI |21 |  7  | SI |28 |  8  | SI | 36 |  9  | SI |45 |  10  | SI |55 |  11  | NO | 55 |

#### CODIGOS
DO WHILE

// Contar del 1 hasta el 10 y sumar los valores.
void main(List<String> args) {
  int s = 0, c = 1;

  do {
    s += c;
    c++;
  } while (c <= 10);
  print("El resultado de la suma de los valores es:$s");
}//Do whilesss
                
WHILE
                   
  // Contar del 1 hasta el 10 y sumar los valores.
void main(List<String> args) {
  int s = 0, c = 1;

  while (c <= 10) {
    s += c;
    c++;
  }
  print("El resultado de la suma de los valores es:$s");
} //while

FOR
                
 // Contar del 1 hasta el 10 y sumar los valores.

void main(List<String> args) {
  int s = 0;
  for (var i = 1; i <= 10; i++) {
    s += i;
  }
  print("La suma de los valores es: $s");
}//for
#### DIAGRAMA 2
                         
![](https://github.com/ICIROJAS/PARCIAL2REAL.md/blob/main/2DO%20PROBLEMA%20DO%20WHILE.jpg)                         
![](https://github.com/ICIROJAS/PARCIAL2REAL.md/blob/main/2DO%20PROBLEMA%20FOR.jpg)                         
![](https://github.com/ICIROJAS/PARCIAL2REAL.md/blob/main/2DO%20PROBLEMA%20WHILE.jpg )                         
                       
  **PRUEBA DE ESCRITORIO**
| S=S+C*2 | C=C+1 | C<=5 | S=S+C*2 | C=C+1 | C<=5 |S=S+C*2 | C=C+1 | C<=5 | S=S+C*2 | C=C+1 | C<=5 |S=S+C*2 | C=C+1 | C<=5 | S | 
| ----------- | ----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |
|  2 | 2 | SI | 6 | 3 | SI |12 | 4 | SI | 20 | 5 | SI | 30 | 6 | NO |  30 |                        

#### CODIGOS
  WHILE

 void main(List<String> args) {
  int s = 0, c = 1;
  while (c <= 5) {
    s = s + c * 2;
    c = c + 1;
  }
  print("resultado de la suma de numeros pares:$s");
} //While

 DO WHILE                        

               void main(List<String> args) {
  int s = 0, c = 1;

  do {
    s = s + c * 2;
    c = c + 1;
  } while (c <= 5);
  print("la suma de numeros pares es:$s");
} //Do While
         
FOR
                        
                  void main(List<String> args) {
  int s = 0;
  for (var i = 2; i <= 10; i = i + 2) {
    s = s + i;
  }
  print("resultado de la suma de numeros pares es:$s");
} //For
#### DIAGRAMA 3
![](https://github.com/ICIROJAS/PARCIAL2REAL.md/blob/main/3ER%20PROBLEMA%20WHILE.jpg)
![](https://github.com/ICIROJAS/PARCIAL2REAL.md/blob/main/3ER%20PROBLEMA%20DOWHILE.jpg)
![](https://github.com/ICIROJAS/PARCIAL2REAL.md/blob/main/3ER%20PROBLEMA%20FOR.jpg)

**PRUEBA DE ESCRITORIO**
                         
| A[C]=N |C=C+1| C<=9|A[C]=N |C=C+1| C<=9| A[C]=N |C=C+1| C<=9| A[C]=N |C=C+1| C<=9| A[C]=N |C=C+1| C<=9|A[C]=N |C=C+1| C<=9|A[C]=N |C=C+1| C<=9|A[C]=N |C=C+1| C<=9|A[C]=N |C=C+1| C<=9| A[C]=N |C=C+1| C<=9| A|
| ----------- | ----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |
|  5, | 1 | SI | 5,4 | 2 | SI | 5,4,3 | 3 | SI | 5,4,3,6 | 4 | SI | 5,4,3,6,7 | 5 | SI |5,4,3,6,7,8 | 6 | SI | 5,4,3,6,7,8,9 | 7 | SI |5,4,3,6,7,8,9,1 | 8 | SI |5,4,3,6,7,8,9,1,2 | 9 | SI |5,4,3,6,7,8,9,1,2,10 | 10 | NO | 5,4,3,6,7,8,9,1,2,10|                        

#### CODIGOS                         
WHILE

 //Leer 10 numeros del teclado y ponerlos en una lista.
void main() {
  var arra = new List.filled(10, 0);
  stdout.write("Dame diez numeros\n ");
  stdout.write("----------\n");
  int i = 0;
  while (i <= 9) {
    String? s = stdin.readLineSync();
    if (s != null) {
      int ner = int.parse(s);
      arra[i] = ner;
    }
    i++;
  }
  stdout.write("Tu lista es, $arra ");
}
  
FOR

  //Leer 10 numeros del teclado y ponerlos en una lista.
void main() {
  var arra = new List.filled(10, 0);
  stdout.write("Dame diez numeros\n ");
  stdout.write("----------\n");
  for (var i = 0; i <= 9; i++) {
    String? s = stdin.readLineSync();
    if (s != null) {
      int n = int.parse(s);
      arra[i] = n;
    }
  }
  stdout.write("aqui esta la lista, $arra");
}
                         
DO WHILE

                        import 'dart:io';
void main() {
  var arra = new List.filled(10, 0);
  stdout.write("Dame diez numeros\n ");
  stdout.write("----------\n");
  int i = 0;
  do {
    String? s = stdin.readLineSync();
    if (s != null) {
      int n = int.parse(s);
      arra[i] = n;
      i++;
    }
  } while (i <= 9);
  stdout.write("Tu lista es $arra ");
}
#### DIAGRAMA 4
![](https://github.com/ICIROJAS/PARCIAL2REAL.md/blob/main/4TP%20PROBLEMA%20DOWHILE.jpg)
![](https://github.com/ICIROJAS/PARCIAL2REAL.md/blob/main/4TP%20PROBLEMA%20FOR.jpg)
![](https://github.com/ICIROJAS/PARCIAL2REAL.md/blob/main/4TP%20PROBLEMA%20WHILE.jpg)

**PRUEBA DE ESCRITORIO**
  | A[C]=N |C=C+1| C<=9|A[C]=N |C=C+1| C<=9| A[C]=N |C=C+1| C<=9| A[C]=N |C=C+1| C<=9| A[C]=N |C=C+1| C<=9|A[C]=N |C=C+1| C<=9|A[C]=N |C=C+1| C<=9|A[C]=N |C=C+1| C<=9|A[C]=N |C=C+1| C<=9| A[C]=N |C=C+1| C<=9| A|
| ----------- | ----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |
|  1, | 1 | SI | 1,2 | 2 | SI | 1,2,3 | 3 | SI | 1,2,3,4 | 4 | SI |  1,2,3,4,5 | 5 | SI | 1,2,3,4,5,6 | 6 | SI | 1,2,3,4,5,6,7 | 7 | SI |1,2,3,4,5,6,7,8 | 8 | SI |1,2,3,4,5,6,7,8,9 | 9 | SI |1,2,3,4,5,6,7,8,9,10 | 10 | NO | 1,2,3,4,5,6,7,8,9,10|

#### CODIGOS                         
WHILE
FOR
DO WHILE  
  
 #### DIAGRAMA 5
![](https://github.com/ICIROJAS/PARCIAL2REAL.md/blob/main/5TO%20PROBLEMA%20DOWHILE.jpg)
![](https://github.com/ICIROJAS/PARCIAL2REAL.md/blob/main/5TO%20PROBLEMA%20FOR.jpg)
![](https://github.com/ICIROJAS/PARCIAL2REAL.md/blob/main/5TO%20PROBLEMA%20WHILE.jpg)

**PRUEBA DE ESCRITORIO**
  
  | A[10-C]=A |C=C-1| C<=0|A[10-C]=N |C=C-1| C<=0| A[10-C]=N |C=C-1| C<=0|A[10-C]=N |C=C-1| C<=0|A[10-C]=N |C=C-1| C<=0|A[10-C]=N |C=C-1| C<=0|A[10-C]=N |C=C-1| C<=0|A[10-C]=N |C=C-1| C<=0|A[10-C]=N |C=C-1| C<=0|A[10-C]=N |C=C-1| C<=0|A[10-C]=N |C=C-1| C<=0| A|
| ----------- | ----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |----------- |
|  10, | 10 | SI | 1,2 | 9 | SI | 10,9,8 | 8 | SI | 10,9,8,7 | 7 | SI |  10,9,8,7,6 | 6 | SI |10,9,8,7,6,5 | 5 | SI | 10,9,8,7,6,5,4 | 4 | SI |10,9,8,7,6,5,4,3 | 3 | SI |10,9,8,7,6,5,4,3,2 | 2 | SI |10,9,8,7,6,5,4,3,2,1 | 1| SI |10,9,8,7,6,5,4,3,2,1,0 | 0| NO | 10,9,8,7,6,5,4,3,2,1,0|

#### CODIGOS                         
WHILE
 
  //Almacene un contador negativo en un vector, el conteo es de 10 a 0.
void main() {
  var arr = <int>[0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
  int c = 10;
  while (c >= 0) {
    arr[10 - c] = c;
    c = c - 1;
  }
  print(arr);
}
  
FOR
  
  //Almacene un contador negativo en un vector, el conteo es de 10 a 0.

void main() {
  var arr = <int>[0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
  int c = 10;
  for (var i = 10; i >= 0; i--) {
    arr[10 - i] = i;
  }
  print(arr);
}
  
DO WHILE
  
  void main() {
  var arr = <int>[0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
  int c = 10;
  do {
    arr[10 - c] = c;
    c = c - 1;
  } while (c >= 0);
  print(arr);
}//dowhile

#### DIAGRAMA 6
![](https://github.com/ICIROJAS/PARCIAL2REAL.md/blob/main/6TO%20PROBLEMA%20DOWHILE.jpg)
![](https://github.com/ICIROJAS/PARCIAL2REAL.md/blob/main/6TO%20PROBLEMA%20FOR.jpg)
![](https://github.com/ICIROJAS/PARCIAL2REAL.md/blob/main/6TO%20PROBLEMA%20WHILE.jpg)

**PRUEBA DE ESCRITORIO**

#### CODIGOS                         
WHILE
  
listanumeros = []
numerousuario = int(input("introdusca un numero: "))
listanumeros.append(numerousuario)
decision = input("¿desea añadadir mas numeros?: ")

while decision == "s" or decision == "s":
    numerousuario = int(input("introdusca otro numero: "))
    listanumeros.append(numerousuario)
    decision = input("¿desea añadir otro numero?: ")


print(f"los numeros son {listanumeros}")
for n in listanumeros:
    if n % 2 == 0:
        print("Este numero de la lista es par" + str(n))
        


input("por favor, precione una tecla para salir.") 
  
FOR
  
  listanumeros = []

for x in range(10):
    numerousuario=int(input("introdusca un numero: "))
    if numerousuario % 2 == 0:
      listanumeros.append(numerousuario)
    else: numerousuario=int(input("El numero no es par, introdusca otro numero: "))
    if numerousuario % 2 == 0:
      listanumeros.append(numerousuario)
    
print(listanumeros)
  
DO WHILE                       
                         
print("PARES")
numero_1 = int(input("Escriba un número entero: "))
numero_2 = int(input(f"Escriba un número entero mayor o igual que {numero_1}: "))

if numero_2 < numero_1:
        print(f"¡Le he pedido un número entero mayor o igual que {numero_1}!")
else:
        for i in range(numero_1, numero_2 + 1):
            if i % 2 == 0:
                print(f"El número {i} es par.")                         
                         
#### DIAGRAMA 7
![](https://github.com/ICIROJAS/PARCIAL2REAL.md/blob/main/7MO%20PROBLEMA%20DOWHILE.jpg)
![](https://github.com/ICIROJAS/PARCIAL2REAL.md/blob/main/7MO%20PROBLEMA%20FOR.jpg)
![](https://github.com/ICIROJAS/PARCIAL2REAL.md/blob/main/7MO%20PROBLEMA%20WHILE.jpg)

**PRUEBA DE ESCRITORIO**

#### CODIGOS                         
WHILE
                       
         
                       
FOR
                       
                       
                       
DO WHILE                        
                         
                         
                         
                         
                         
                 
                       
#### DIAGRAMA 8
![]()
![]()
![]()

**PRUEBA DE ESCRITORIO**

#### CODIGOS                         
WHILE
FOR
DO WHILE
                       
                       
                       
                       
                       
                       
                       
                       
                       
                       
                       
                       
                       
                       
  
  
                         #### DIAGRAMA 9
![]()
![]()
![]()

**PRUEBA DE ESCRITORIO**

#### CODIGOS                         
WHILE
FOR
DO WHILE
