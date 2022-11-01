## 1. FUNCIONES EN DART

### 1.1. Funcion flecha

````Dart
void main() {
  int resultSum = sum(2,3);
  print(resultSum);
  
  int resultRest = rest(2,3);
  print(resultRest);
  
  int resultMult = mult(2,3);
  print(resultMult);
  
  double resultDiv = div(2,3);
  print(resultDiv);
}
// Funcion fecha (Arrow Function) suma
int sum(int a, int b) => a+b;

// Funcion fecha (Arrow Function) resta
int rest(int a, int b) => a-b;

// Funcion fecha (Arrow Function) multiplicacion
int mult(int a, int b) => a*b;

// Funcion fecha (Arrow Function) division
double div(double a, double b) => a/b;
````