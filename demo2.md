===
    Estructura del programa
===
1. Inicio: #include libreria
2. using namespace std; 
3. Declaración de las funciones 
4. Declaración de la función principal

Ejemplo de cada una de las estructuras del programa: 

#include < iostream >
using namespace std; 

vacio declarar () {
    //opciones de declaración: 
    entero a; 
    entero a = 7; 
    booleano a = falso; 
    entero a=7; 
    booleano a=falso; 
}

vacio leer (){
    entrada>> a; 
}

vacio ciclosEimprimir (){
    //Formas de imprimir
    cout << "El valor de a es " << a << endl; 
    cout << "Texto"; 
    cout << a << endl;
    cout << a;

    //Formas de los ciclos
    //Forma 1 del si
    si (a > 7){
        salida <<a;
    }


    //Forma 2 del si
    si (a > 7){
        entero a = a+1;
        salida <<a;
    }

    //Forma 3 del si
    si (a > 7){
        entero b; 
        entero c; 
        c = a+b;
        salida <<c;
    }

    //Formas del para 
    //Forma 1 del para
    para (int i = 0; i < 5; i++){
        salida << i; 
    }

    //Forma 2 del para
    para (int i = 0; i < 5; i++){
        entero k; 
        salida << k; 
    }

    //Forma 3 del para 
    para (int i = 0; i < 5; i++){
        entero k; 
        k = k+i;
        salida << k; 
    }

    //Formas del mientras
    //Forma 1 del mientras
    mientras (a<10){
        salida <<a;
    }

    //Forma 2 del mientras
    mientras (a=10){
        entero k = 5; 
        salida << k;
    }

    //Forma 3 del mientras 
    mientras (a>10){
        entero k; 
        k = k+i;
        salida << k; 
    }
}


entero principal (){
    declarar ();
    leer (); 
    ciclosEimprimir();

    return 0;
}
