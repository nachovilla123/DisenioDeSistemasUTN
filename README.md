## 📁 Estructura del Repositorio

### 📚 `apuntes_lecturas_powers/`
Material teórico de estudio y material de la cátedra.

- **`apuntes_diagramas/`** - Apuntes sobre diagramas:
  - Casos de uso (CU)
  - Diagrama entidad relación (DER)
  - Teoría de Requerimientos
- **`patrones_de_diseño/`** - PDFs de patrones de diseño:
  - Adapter, Builder, Command, Composite, Decorator, Facade
  - Factory Method, Observer, Singleton, State, Strategy, Template Method
- **`powers_cursada/`** - Material de clases:
  - Atributos de Calidad y Patrones de Diseño
  - Refactoring, Code Smells, SOLID
  - Arquitectura de Software (Partes I, II, III)
  - Persistencia de Datos (Parte I y II)
- **`moldes_imprimibles_DER/`** - Moldes para diagramas DER
- **`moldes_imprimibles_diagrama_clases/`** - Plantillas para diagramas de clases
- **`lecturas_recomendadas/`** - Lecturas sugeridas
- **`Links De lecturas.md`** - Enlaces útiles organizados por tema
- **`diagramaDeClases.txt`** - Información sobre diagramas de clases

### 📝 `primer_parcial/`
Resoluciones de parciales organizadas por año. Cada carpeta contiene resoluciones de alumnos con **RECOMENDACIONES** de profesores.

**Estructura:** Cada parcial puede tener múltiples versiones (V1, V2, etc.) con sus respectivos feedbacks.

#### Por año:
- **`2019/`**
  - `CUIDANDONOS/` - Resolución del parcial
- **`2021/`**
  - `BOLSA_DE_TRABAJO/` - Múltiples versiones con feedbacks en audio/video
  - `GESTION_CONSORCIOS/` - Versiones V1 y V2
- **`2022/`**
  - `NOTESBOX/` - Versiones V1 y V2
  - `UNIVERSIDAD_TE_LLEVA_A_CATAR/` - Versión V1
- **`2023/`**
  - `ESTIM/` - 3 versiones distintas (V1, V2, V3)
  - `SERVICIO_ATENCION_AUTOMOTOR/` - Versión V1
  - `TINDERZ/` - Versión V1
- **`2024/`**
  - `preguntas/` - Preguntas del año
- **`ejercicios_patrones_diseño/`** - Ejercicios resueltos:
  - `moduloExportador/` - Strategy + Adapter
  - `tendencias_musicales/` - State + Template Method

> 💡 **Tip:** Los archivos dentro de cada carpeta están organizados como una conversación (Slack/WhatsApp). Sigue el flujo de consultas y respuestas para entender el proceso de diseño.

### 📊 `segundo_parcial/`
Resoluciones del segundo parcial organizadas por año. Incluye modelos de datos (DER) y ejercicios de persistencia.

#### Por año:
- **`2019/`** - Final y DER
- **`2021/`** - Modelo 2021 con múltiples versiones y feedbacks
- **`2022/`**
  - `Cartagram/` - Resolución
  - `Lentti/` - Resolución con consultas
  - `modelo_2022/` - Modelo con versiones y feedbacks
  - `UNIVERSIDAD_TE_LLEVA_A_CATAR/` - Versión V1
- **`2023/`**
  - `estim/` - DER y resolución
  - `tinderz/` - Resolución con feedback
- **`dudas-teoricas/`** - Consultas teóricas:
  - `cliente-pesado-SPAs/` - Sobre clientes pesados y SPAs
  - `estrategia-abordaje-arquitectura/` - Estrategias de arquitectura
- **`ejercicios_resultos_y_corregidos/`** - Ejercicios corregidos:
  - `moduloStock/` - Ejercicio resuelto
  - `rico_sano_y_natural/` - Modelos de datos (múltiples versiones)

### 📋 `finales/`
Enunciados de exámenes finales organizados por año.

- **`enunciados_de_finales/`** - Enunciados desde 2016 hasta 2023:
  - `2016/` - 5 finales
  - `2017/` - 10 finales
  - `2018/` - 10 finales
  - `2019/` - 10 finales
  - `2020/` - 7 finales
  - `2021/` - 12 finales
  - `2022/` - 9 finales
  - `2023/` - 5 finales
- **`readme.txt`** - Nota sobre el desarrollo de resoluciones

> 📌 **Nota:** Las resoluciones de la primera parte de los finales se encuentran en `primer_parcial/`. A medida que avance el año, se irán completando todas las carpetas.

### ❓ `consultas_frecuentes/`
Consultas comunes de alumnos con respuestas y ejemplos.

- **`errores_comunes/`** - Documento con errores frecuentes al comunicar un diseño:
  - Clases vacías
  - Herencia sin implementación
  - Métodos fuera de lugar
  - Roles del sistema en el dominio
- **`flechas_diagrama_en_doble_sentido/`** - Consulta sobre acoplamiento bidireccional:
  - Conversación alumno-profesor
  - Audios con respuestas
  - Imágenes de ejemplo
- **`modelo_pregunta_respuesta/`** - Ejemplo de modelo de cuestionario:
  - Diagramas de clases (múltiples versiones)
  - Modelo DER
  - Documentación con ejemplos y preguntas reflexivas

# Colaboraciones

¡Agredezco mucho tu contribucion a este repositorio! Si queres agregar nuevos enunciados de ejercicios o soluciones mejoradas, te invito a seguir estos pasos para hacerlo mediante pull requests:

1)Asegúrate de tener una cuenta de GitHub. Si no tienes una, puedes crear una de forma gratuita en https://github.com

2)Haz un fork de este repositorio haciendo clic en el botón "Fork" en la parte superior derecha de la página. Esto creará una copia del repositorio en tu cuenta de GitHub.

3)Clona el repositorio desde tu cuenta de GitHub a tu máquina local. Puedes utilizar el siguiente comando en tu terminal o utilizar una interfaz gráfica de Git:
```
git clone https://github.com/nachovilla123/DisenioDeSistemasUTN.git
```

4)Crea una nueva rama en tu repositorio local para trabajar en tus cambios:
Asegúrate de darle un nombre descriptivo a la rama que refleje el tipo de cambio que realizarás.
```
git checkout -b agregar-resolucion-parcial
```

5)Agrega los enunciados de ejercicios y/o soluciones a la estructura del repositorio. Asegúrate de seguir la estructura de carpetas existentes para mantener la consistencia.

6) Realiza los cambios y guarda los archivos modificados.

7)Realiza un commit de tus cambios con un mensaje descriptivo:

```
git commit -m "Agregado posible resolucion _nombreParcial_"
```
8)Sube los cambios a tu repositorio en GitHub:
```
git push origin agregar-resolucion-parcial
```

9) Abre tu repositorio clonado en GitHub y verás un mensaje para crear un nuevo pull request desde la rama que acabas de pushear. Haz clic en el botón "Compare & pull request" para abrir una nueva solicitud de extracción (PR).

10) Proporciona una descripción clara y concisa de tus cambios en la solicitud de extracción. Incluye cualquier información relevante que pueda ayudar a los revisores a entender tus contribuciones.

11) Haz clic en "Create pull request" para enviar tu solicitud. 
  Siempre que tenga tiempo voy a estar aceptando nuevos cambios lo antes que pueda! Puede haber comentarios y sugerencias para mejorar tus contribuciones.


Si tienes alguna pregunta|duda|sugerencia o necesitas ayuda en cualquier paso del proceso, no dudes en abrir un issue en el repositorio o ponerte en contacto conmigo!
  
