# PROGRAMAS EN C++ DE TIGUA ANGIE

# # # Informacion de autor # # # 

Autor: Tigua Rodriguez Angie Viviana          TICS 1 "B"

Correo electronico: angie.tigua.rodriguez@utelvt.edu.ec

Celular: 0986180938

Link de video: https://www.youtube.com/watch?v=7_Vq-NVqGcI 

# Nombres de cada Programa realizado en la ACTIVIDAD-C2 

TiguaVivi-Compara.cpp

TiguaVivi-LaEdad.cpp

TiguaVivi-PuntoVenta.cpp

TiguaVivi-CuentaMoneda.cpp

TiguaVivi-SumaN.cpp

# Descripción de cada Programa

>> TiguaVivi-Compara.cpp : 

Este es un programa que nos permite comparar dos números y verificar cual de estos es el mayor, menor o igual.

>> TiguaVivi-LaEdad.cpp : 

En este programa permitirá al usuario calcular su edad en Años, Meses y Dias.

>> TiguaVivi-PuntoVenta.cpp :  

Este es un programa que se encargará de calcular la compra de varios productos, calculando su valor bruto, sumandole el Iva a la compra y realizando un descuento adicional a la compra del usuario.

>> TiguaVivi-CuentaMoneda.cpp : 

Este programa permite al usuario contar monedas de tres denominaciones, saber cuanto es la cantidad de dinero que tiene y cuantas monedas tiene de cada denominación.

>> TiguaVivi-SumaN.cpp : 

Este es un programa que se encarga que, cualquier usuario en general pueda sumar los valores de varios números.

# FUNCIONALIDAD

>> TiguaVivi-Compara.cpp :
   float AR_t,AR_r;
   cout<<"Ingrese el valor de T: ";
   cin>>AR_t;
   cout<<"Ingrese el valor de R: ";
   cin>>AR_r;
  
 >> TiguaVivi-LaEdad.cpp : 
    int AR_dd,AR_mm,AR_yy,AR_dd1,AR_mm1,AR_yy1,AR_da,AR_ma,AR_ya;
    cout<<"Ingresa la Fecha Actual: Dia Mes y Año "<<endl;
    cin>>AR_dd>>AR_mm>>AR_yy;
    cout<<"Ingresa la Fecha de Nacimiento: Dia Mes y Año "<<endl;
    cin>>AR_dd1>>AR_mm1>>AR_yy1;   
  
  >> TiguaVivi-PuntoVenta.cpp : 
    int AR_b=0,AR_q;
    float AR_e=0,AR_m,AR_vt,AR_tiva,AR_tdes,AR_iva=0.12,AR_dsc=0.10,AR_pt;
    cout<<"Ingresar la cantidad de productos a comprar: ";
    cin>>AR_q;
    do{
    cout<<"Ingresar el valor del producto: ";
    cin>>AR_m;
  
 >> TiguaVivi-CuentaMoneda.cpp : 
     int AR_n, AR_c=0, AR_c1=0, AR_c2=0;
     float AR_x, AR_a=0, AR_a1=0, AR_a2=0, AR_m=0.10;
     cout<<"Cantidad de monedas a ingresar : ";
     cin>>AR_n;
     do{
     cout<<"Ingrese el valor de la moneda (0.10, 0.25) : ";
     cin>>AR_x;
            
>> TiguaVivi-SumaN.cpp : 
     int AR_a=0,AR_v;
     float AR_t=0,AR_r;
     cout<<"Ingresar la cantidad de numeros a sumar: ";
     cin>>AR_v;
     do{
     cout<<"Ingresar un numero: ";
     cin>>AR_r;
        
 # SALIDAS DE LOS PROGRAMAS
   
  >> TiguaVivi-Compara.cpp :
   cout<<"El valor de T: "<<AR_t<<" es mayor a R: "<<AR_r<<endl;
   
   cout<<"El valor de R: "<<AR_r<<" es mayor a T: "<<AR_t<<endl;
   
  >> TiguaVivi-LaEdad.cpp : 
   cout<<"Usted Tiene "<<AR_ya<<" años "<<AR_ma<<" meses "<<" y "<<AR_da<<" dias "<<endl; 
  
  >> TiguaVivi-PuntoVenta.cpp : 
   cout<<"El valor del iva de su compra es: $ " <<AR_tiva<<endl;
   cout<<"Su compra obtiene descuento de: "<<AR_vt<<endl;
   cout<<"El valor total a pagar de su compra es: $ "<<AR_pt<<endl;
  
  >> TiguaVivi-CuentaMoneda.cpp : 

    cout<<"El resultado fue:"<<endl;
    cout<<"Cantidad de monedas ingresadas : "<<AR_c<<endl;
    cout<<"Cantidad total en dinero contado : "<<AR_a<<endl;
    cout<<"Cantidad de monedas de 0.10c ingresadas : "<<AR_c1<<endl;
    cout<<"Cantidad total en dinero de monedas de 0.10cc : "<<AR_a1<<endl;
    cout<<"Cantidad de monedas de 0.25cc ingresadas : "<<AR_c2<<endl;
    cout<<"Cantidad total en dinero de monedas de 0.25cc : "<<AR_a2<<endl;

  >> TiguaVivi-SumaN.cpp : 
    cout<<"La suma total es: "<<AR_t<<endl;

   # INSTALACIÓN
   
1.- Descargar F-Droid
  
  https://f-droid.org/

2.- Descargar la Terminal (Termux)

    Dentro de la aplicación F-Droid

3.- Instalar paquetes en la Terminal (Termux)

    pkg install git

    pkg install vim

    pkg install g++

    pkg install clang

    apt update

    apt upgrade

4.- Clonar el Repositorio en la Terminal

    git clone https://github.com/ViviTigua03/ACTIVIDAD-E2 

5.- Acceder al Repositorio

    cd ACTIVIDAD-E2

6.- Acceder al Directorio

    cd ACTIVIDAD-B2-C2

7.- Escribir el Comando > ls

    * TiguaVivi-Compara
    * TiguaVivi-Compara.cpp
    * TiguaVivi-Compara.jpg
    * TiguaVivi-LaEdad
    * TiguaVivi-LaEdad.cpp
    * TiguaVivi-LaEdad.jpg
    * TiguaVivi-PuntoVenta
    * TiguaVivi-PuntoVenta.cpp
    * TiguaVivi-PuntoVenta.jpg
    * TiguaVivi-CuentaMoneda
    * TiguaVivi-CuentaMoneda.cpp
    * TiguaVivi-CuentaMoneda.jpg
    * TiguaVivi-SumaN
    * TiguaVivi-SumaN.cpp
    * TiguaVivi-SumaN.jpg  
    
# COPILACIÓN DE LOS PROGRAMAS

1.- Ingresar al Repositorio

    cd ACTIVIDAD-E2

2.- Ingresar al Directorio

    cd ACTIVIDAD-B2-C2

3.- Compilar Programa

    g++ TiguaVivi-CuentaMoneda.cpp -o TiguaVivi-CuentaMoneda
  
# EJECUTAR LOS PROGRAMAS 
  
  ./TiguaVivi-CuentaMoneda
