# Calculadora de Notas EPN

Aplicación web interactiva que permite a un estudiante de la **Escuela Politécnica Nacional (EPN)** saber si aprueba una asignatura a partir de sus notas de los dos bimestres y, en caso de quedar a supletorio, cuánto necesita obtener en el examen para aprobar.

Utilizando **OpenCode** con un modelo gratuito.

<img width="1917" height="965" alt="image" src="https://github.com/user-attachments/assets/ac940232-7634-411c-b304-d74f79027e4b" />


## Características

- Ingreso de la **nota del primer bimestre** y la **nota del segundo bimestre**, ambas sobre 20.
- Cálculo automático de la suma sobre 40.
- Resultado claro según la situación del estudiante:
  - **Aprobación directa**.
  - **Supletorio**, mostrando la nota que debe alcanzar en el examen (sobre 40) y su equivalencia sobre 20.
  - **Pérdida directa** de la materia.

## Criterios de calificación

La suma de los dos bimestres se evalúa sobre 40 puntos:

| Suma de bimestres | Resultado |
|---|---|
| 28 a 40 | Aprobación directa |
| 18 a menos de 28 | Supletorio |
| Menos de 18 | Pérdida directa |

Para el supletorio, la calculadora indica la nota mínima requerida en el examen (sobre 40) y su equivalente sobre 20. Por ejemplo, 24/40 equivale a 12/20.

```
.
├── index.html     # Aplicación completa (HTML, CSS y JavaScript)
└── README.md
```

## Cómo ejecutarla

**Opción 1: abrir el archivo directamente**
1. Descarga o clona el repositorio.
2. Abre `index.html` con el navegador (doble clic).


## Cómo se desarrolló

La aplicación se generó con **OpenCode** enviando un prompt, y luego se revisó y probó. Modelo utilizado: Exo Free

```text
Actúa como un desarrollador web experto. Necesito que crees una aplicación
web interactiva (en un archivo HTML que incluya CSS y JavaScript) que
funcione como una calculadora de notas oficial para los estudiantes de la
Escuela Politécnica Nacional (EPN).

La aplicación debe seguir estrictamente esta lógica de calificaciones de la EPN:
1. Se ingresan dos notas: "Nota primer bimestre" y "Nota segundo bimestre",
   ambas calificadas sobre 20 puntos.
2. La suma de ambos bimestres da un puntaje sobre 40. La nota mínima para
   aprobar la materia de forma directa es 28/40 (equivalente a un promedio
   de 14 por bimestre).
3. Si la suma es menor a 28, el estudiante se queda a supletorio (examen
   final sobre 40 puntos).
4. Para el supletorio, la calculadora debe determinar exactamente cuánto
   debe alcanzar el estudiante en el examen final (sobre 40) para aprobar
   la materia, mostrando también su equivalencia sobre 20 (por ejemplo, si
   necesita 24/40, mostrar su equivalente a 12/20).
5. Si la suma es mayor o igual a 28, debe mostrar un mensaje claro de que
   el estudiante ha aprobado la materia directamente sin supletorio o si es
   menor de 18 mostrar que el estudiante perdió la materia directamente.
6. Diseña una interfaz moderna, limpia y atractiva, con un estilo visual
   profesional (puedes usar tonos oscuros y acentos institucionales de la
   EPN como azul y rojo).

Entrégame el código completo listo para usar.
```

**Leonor Elizabeth Yumi López**Escuela Politécnica Nacional, ESFOT
Asignatura: Sistemas Operativos · Docente: Ing. Juan Carlos Gonzalez, MSc.
