# Proyecto-Lógica 🧠

## Descripción  
Este repositorio contiene el trabajo final de la materia de Lógica para las Ciencias Informáticas 2025. El proyecto está implementado en Prolog y tiene como objetivo resolver ejercicios de lógica/formulación lógica — por ejemplo, problemas de existencia de vida inteligente en planetas, modelado de datos desde archivos CSV, consultas lógicas, etc.  

## Funcionalidades  
- Leer datos de un archivo CSV (por ejemplo `planetas.csv`) con información relevante.  
- Representar conocimientos y reglas lógicas en un archivo Prolog (por ejemplo `vida_inteligente.pl`).  
- Permitir consultas lógicas sobre los datos: determinar, según las reglas definidas, si ciertos planetas podrían albergar vida inteligente, o cualquier otra consulta lógica implementada.  
- Modularidad: los datos y la lógica están separados (csv + Prolog), lo que permite adaptar las reglas o los datos sin modificar ambos.  

## Instrucciones de uso  
1. Clonar el repositorio:  
   ```bash
   git clone https://github.com/momet0/proyecto-logica.git  
   cd proyecto-logica  

2. Asegurarse de tener instalado un intérprete Prolog compatible (por ejemplo SWI-Prolog).
3. Cargar el archivo Prolog desde el intérprete, por ejemplo:
   ?- [vida_inteligente].
4.Realizar las consultas lógicas definidas en el código. Por ejemplo, consultar qué planetas cumplen ciertas condiciones, buscar relaciones lógicas, etc.
5.Si se usan datos en planetas.csv, ajustar la lógica Prolog para leerlos (o convertirlos a hechos Prolog) según lo que se haya definido en el proyecto.

##Casos de uso
-Validar hipótesis sobre vida inteligente en planetas a partir de criterios lógicos.
-Ejemplificar el uso de lógica declarativa para modelar conocimiento y hacer inferencias.
-Proporcionar una base para proyectos educativos o prácticos donde se necesite razonamiento lógico con datos estructurados.
-Sirve como punto de partida para extensiones: agregar más reglas, nuevos predicados, filtros más complejos, importar otros datos, etc.

##Requisitos
-Intérprete Prolog (SWI-Prolog u otro compatible).

##Integrantes
Alvez Rojas Valentín
Benítez Kevin Andrés
Fernández Risso Martina
Juárez Eduardo Martín
