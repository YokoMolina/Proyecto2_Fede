# Proyecto2 – IA en Unreal Engine 5

Este proyecto ha sido desarrollado en Unreal Engine 5 y contiene dos sistemas de inteligencia artificial distintos:

- Enemigos: se crearon enemigos para el jugador, con lógica de IA que les permite patrullar, detectar al jugador y reaccionar ante su presencia.  
- Compañante: se añadió un acompañante para el jugador, con un segundo tipo de IA que sigue al jugador, responde a comandos básicos y colabora de forma proactiva.  
- Flujo general de IA: ambos sistemas están implementados con todo el flujo de IA — desde el comportamiento base hasta la integración en el entorno del jugador.

## Cómo usarlo

1. Abre el archivo `Proyecto2.uproject` en Unreal Engine 5.  
2. Compila los blueprints / C++ según corresponda.  
3. Ejecuta la escena principal y observa cómo los enemigos y el acompañante interactúan con el jugador.  
4. Puedes modificar los parámetros de la IA (distancias de detección, velocidad de patrulla, comandos del acompañante, etc.) para ajustarlo a tus necesidades.

## Estructura del código

- Carpeta **Content/**: contiene los assets, blueprints y niveles.  
- Carpeta **Source/** (si aplica): contiene el código C++ de los comportamientos de IA.  
- Other assets/configuración: puedes adaptarlos o ampliarlos según tu objetivo.

## Licencia

Este proyecto se ofrece "tal cual", sin garantía explícita. Si lo reutilizas o modificas, por favor menciona la autoría original.

