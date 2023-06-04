# Proyecto Tamagotchi: Carlito

## Descripcion general
El sistema gestionara una mascota virtual con solo 3 atributos: "Hambre", "Salud" y "Diversion"

## Analisis de requisitos
- Una vez transcurren 30 dias reales desde el nacimiento de la mascota, esta muere
- El atributo "Hambre" mide la necesidad de comer, con 0 unidades equivalentes a no tener hambre y 100 unidades equivalentes a tener mucha hambre
- El atributo "Salud" mide el bienestar de la mascota, con 0 unidades equivalentes a estar muy enfermo y 100 unidades a estar completamente sano
- El atributo "Diversion" mide el humor de la mascota, con 0 unidades equivalentes a estar muy triste y 100 unidades a estar muy feliz
- Si se realiza una accion que disminuye el hambre, pero el valor de disminucion es mayor que el valor de hambre actual, el hambre queda en 0 y el resto de unidades se pierden
- Si se realiza una accion que aumenta la salud, pero el valor de aumento mas el valor actual es mayor a 100, la salud queda en 100 y el resto de unidades se pierden
- La mascota puede comer un "Carlito", percibido como comida chatarra. Este disminuye el hambre en 5 unidades, pero aumenta la felicidad en 20
- La mascota puede comer "Brocoli", percibido como comida saludable. Este disminuye el hambre en 10 unidades, pero aumenta la felicidad en 10
- Se le puede dar "Ibuprofeno", que aumenta su salud en 25/50 unidades
- Se le puede dar "Viagra", que disminuye la salud en 50 unidades pero aumenta la diversion en 50 unidades
- Se le puede dar "Laxante", que aumenta la salud en 20 unidades pero aumenta el hambre en 50 unidades
- Puede usar "Feetfinder", que aumenta la diversion en 20 unidades pero disminuye la salud 5 unidades

## Requisitos
- Como maximo va a haber 5 botones
- Un boton destinado a funciones referidos a sacar el hambre
- Un boton destinado a funciones referidas a la higiene
- Un boton destinado a ver las estadisticas
