# Agradecimientos

Parte de la inspiración y enfoque inicial de este proyecto provienen del trabajo de Nilaween.

Sus macros me adentraron en easyUO y gracias a ellas pude crear este proyecto.

# Modular UO Automation Framework

Framework modular de automatización para Ultima Online basado en macros desacopladas, configurables y reutilizables.

El proyecto está diseñado como una arquitectura por componentes donde cada módulo tiene una responsabilidad concreta dentro del flujo de automatización.

La idea principal es que cualquier automatización pueda construirse combinando:

- configuración
- inicialización
- preparación
- ejecución
- herramientas auxiliares
- loops reutilizables

Todo ello sin necesidad de reescribir lógica específica para cada macro.

---

# Filosofía del proyecto

Este proyecto no pretende ser únicamente una colección de macros independientes.

El objetivo es construir un framework modular capaz de:

- reutilizar componentes entre automatizaciones
- desacoplar responsabilidades
- simplificar mantenimiento
- permitir configuraciones complejas
- facilitar ampliaciones futuras
- reducir duplicación de lógica

La mayoría de automatizaciones se construyen únicamente cambiando la configuración y reutilizando módulos existentes.

---

# Arquitectura general

```text
0_config/
1_launcher/
2_orquestador/
3_inicializador/
4_preparador/
5_ejecutor/
Aux_Ejecutables/
aux_tools/
loop_tools/
test/