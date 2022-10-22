# FUNDAMENTOS DE PROGRAMACION
## PORTAFOLIO
## PROBLEMAS RESUELTOS EN CLASE
#### DIAGRAMA 1
![](https://github.com/ICIROJAS/PARCIAL2REAL.md/blob/main/1ER%20PRBLEMA%20WHILE.jpg)
![](https://github.com/ICIROJAS/PARCIAL2REAL.md/blob/main/1ER%20PROBLEMA%20DOWHILE.jpg)
![](https://github.com/ICIROJAS/PARCIAL2REAL.md/blob/main/1ER%20PROBLEMA%20FOR.jpg)

**PRUEBA DE ESCRITORIO**

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

#### CODIGOS                         
WHILE
FOR
DO WHILE  
  
 #### DIAGRAMA 5
![](https://github.com/ICIROJAS/PARCIAL2REAL.md/blob/main/5TO%20PROBLEMA%20DOWHILE.jpg)
![](https://github.com/ICIROJAS/PARCIAL2REAL.md/blob/main/5TO%20PROBLEMA%20FOR.jpg)
![](https://github.com/ICIROJAS/PARCIAL2REAL.md/blob/main/5TO%20PROBLEMA%20WHILE.jpg)

**PRUEBA DE ESCRITORIO**

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
FOR
DO WHILE                       
                         
                         
                         
                         
                         
                         
                         
                         
                         
                   
  
  
                         #### DIAGRAMA 1
![]()
![]()
![]()

**PRUEBA DE ESCRITORIO**

#### CODIGOS                         
WHILE
FOR
DO WHILE
