#include <iostream>
#include <iomanip>
using namespace std;

// Funciones auxiliares (para organizar el c�digo)
void menuLongitud();
void menuMasa();
void menuTemperatura();

int main() {
    int opcionPrincipal;

    do {
        cout << "\n=== SISTEMA DE CONVERSI�N DE UNIDADES ===" << endl;
        cout << "1. Longitud (km, m, cm, pulgadas, pies)" << endl;
        cout << "2. Masa (kg, gramos, libras, onzas)" << endl;
        cout << "3. Temperatura (°C, °F, °K)" << endl;
        cout << "4. Salir" << endl;
        cout << "Elige una categoría (1-4): ";
        cin >> opcionPrincipal;

        switch (opcionPrincipal) {
            case 1:
                menuLongitud();
                break;
            case 2:
                menuMasa();
                break;
            case 3:
                menuTemperatura();
                break;
            case 4:
                cout << "Saliendo del programa..." << endl;
                break;
            default:
                cout << "Opción inválida: elige un número entre 1 y 4" << endl;
        }
    } while (opcionPrincipal != 4);

    return 0;
}

void menuLongitud() {
    int opcion;
    double valor, resultado;
    do {
        cout << "\n--- CONVERSIÓN DE LONGITUD ---" << endl;
        cout << "1. Kilómetros a Metros" << endl;
        cout << "2. Metros a Centímetros" << endl;
        cout << "3. Centímetros a Pulgadas" << endl;
        cout << "4. Pulgadas a Pies" << endl;
        cout << "5. Volver al menú principal" << endl;
        cout << "Elige una opción (1-5): ";
        cin >> opcion;

        switch (opcion) {
            case 1:
                cout << "Ingresa valor en km: "; cin >> valor;
                resultado = valor * 1000;
                cout << valor << " km = " << resultado << " m" << endl;
                break;
            case 2:
                cout << "Ingresa valor en m: "; cin >> valor;
                resultado = valor * 100;
                cout << valor << " m = " << resultado << " cm" << endl;
                break;
            case 3:
                cout << "Ingresa valor en cm: "; cin >> valor;
                resultado = valor / 2.54;
                cout << valor << " cm = " << fixed << setprecision(2) << resultado << " pulgadas" << endl;
                break;
            case 4:
                cout << "Ingresa valor en pulgadas: "; cin >> valor;
                resultado = valor / 12;
                cout << valor << " pulgadas = " << fixed << setprecision(2) << resultado << " pies" << endl;
                break;
            case 5:
                break;
            default:
                cout << "Opción inválida" << endl;
        }
    } while (opcion != 5);
}

void menuMasa() {
    int opcion;
    double valor, resultado;
    do {
        cout << "\n--- CONVERSIÓN DE MASA ---" << endl;
        cout << "1. Kilogramos a Gramos" << endl;
        cout << "2. Gramos a Onzas" << endl;
        cout << "3. Onzas a Libras" << endl;
        cout << "4. Volver al menú principal" << endl;
        cout << "Elige una opción (1-4): ";
        cin >> opcion;

        switch (opcion) {
            case 1:
                cout << "Ingresa valor en kg: "; cin >> valor;
                resultado = valor * 1000;
                cout << valor << " kg = " << resultado << " gramos" << endl;
                break;
            case 2:
                cout << "Ingresa valor en gramos: "; cin >> valor;
                resultado = valor / 28.35; // 1 onza = 28.35 gramos
                cout << valor << " gramos = " << fixed << setprecision(2) << resultado << " onzas" << endl;
                break;
            case 3:
                cout << "Ingresa valor en onzas: "; cin >> valor;
                resultado = valor / 16; // 1 libra = 16 onzas
                cout << valor << " onzas = " << fixed << setprecision(2) << resultado << " libras" << endl;
                break;
            case 4:
                break;
            default:
                cout << "Opción inválida" << endl;
        }
    } while (opcion != 4);
}

void menuTemperatura() {
    int opcion;
    double valor, resultado;
    do {
        cout << "\n--- CONVERSIÓN DE TEMPERATURA ---" << endl;
        cout << "1. Celsius (°C) a Fahrenheit (°F)" << endl;
        cout << "2. Fahrenheit (°F) a Celsius (°C)" << endl;
        cout << "3. Celsius (°C) a Kelvin (°K)" << endl;
        cout << "4. Volver al menú principal" << endl;
        cout << "Elige una opción (1-4): ";
        cin >> opcion;

        switch (opcion) {
            case 1:
                cout << "Ingresa valor en °C: "; cin >> valor;
                resultado = (valor * 9/5) + 32;
                cout << valor << " °C = " << fixed << setprecision(1) << resultado << " °F" << endl;
                break;
            case 2:
                cout << "Ingresa valor en °F: "; cin >> valor;
                resultado = (valor - 32) * 5/9;
                cout << valor << " °F = " << fixed << setprecision(1) << resultado << " °C" << endl;
                break;
            case 3:
                cout << "Ingresa valor en °C: "; cin >> valor;
                resultado = valor + 273.15;
                cout << valor << " °C = " << fixed << setprecision(2) << resultado << " °K" << endl;
                break;
            case 4:
                break;
            default:
                cout << "Opción inválida" << endl;
        }
    } while (opcion != 4);
}
