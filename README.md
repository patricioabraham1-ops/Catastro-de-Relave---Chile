# Catastro de Relave

### Catastro de Relaves en chile (Hasta 2025 de Octubre)
---
## 👤 Autor

**Patricio Valenzuela**
 >Tecnico en Operaciones | Mineras Ingeniero Civil en Minas

 >[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/patricio-valenzuela-villablanca-82b951165/)
---

## 📌 Descripción del proyecto

Este proyecto analiza alrededor de **836 registros reales** de depósitos de relaves en Chile, administrado por SERNAGEOMIN , utilizando datos oficiales.
Se debe aplicar un analisis de datos en para responder preguntas criticas en los Catastro Nacional de Relaves Mineros.

----
## 📝 Observación
> 

> 
---

## 🎯 Preguntas de negocio

1. 
2. 
3. 
4. 
5. 
 

---
## 🗂️ Estructura del repositorio

```
mining-safety-analytics/
│
├── README.md
│
├── data/
│   └──  CATASTRO_RELAVES_CHILE_OCT2025_1                                # Data de los Relaves en Chile hasta octubre 2025
│
├── Iconos/
│   └── LogoSernageomin.png
│
└── images/
│    ├── 1.-Resumen.png
│    ├── 2.-Catastro.png
│    ├── 3.-Mapas.png
│    ├── 4.-Regulación.png
│    ├── 5.-Capacidad y Usos.png
│    ├── 6.-Riesgos.png
│    └── 7.-Modelo de Estrella.png
│
└── Catastro de Relaves _Estrella.pbix
```
---
## 📦 Fuente de datos
| Dataset | Fuente | Registros | Actualización |
|---|---|---|---|
| Catastro de Relave en Chile | [Sernageomin](https://www.sernageomin.cl/visores-mineros/) | 836 | Octubre del 2025 |

>Los datos son de **acceso público y gratuito**.
---
## 🔄 Flujo de trabajo
```
MSHA Open Data (.txt)
        │
        ▼
   Excel
   └── Importación de Tabla Txt y Xlsm.
   ├── Consultas analíticas
   └── Exportación de vistas limpias
        │
        ▼
   Power Query
   ├── EDA: distribuciones, nulos.
   ├── Cálculo de Años de Experinecia en Rangos.
   └── limpieza de Datos y transformaciones.
        │
        ▼
   Power Pivot
   ├── Transformación final, si es necesarios.
   ├── Modelo estrella (Tablas de Hecho + Tabla de Dimensiones).
   ├── Creacion de Tabla Calendario y Año Fiscal.
   └─  Medidas DAX
        │
        ▼
   Excel
   └── Creación de DashBoard.
   └── Calculos para la interactividad del DashBoard.
        │
        ▼
   GitHub.
```

---
## 🛠️ Herramientas utilizadas

| Herramienta | Uso en el proyecto |
|---|---|
|Power Query|Limpieza,EDA, transformación de datos-Eliminacion de columnas Innesesarias-Corrección de Errores-ETC|
|Power Pivot|Creación de tabla calendario, Año Fiscal y Realizacion del modelo de datos Tipo estrella|
|Power BI| Creación del Dashboard Iteractivo para realizar el catastro de Relave|

---
## 📊 Hallazgos principales

**1. ¿Cuál ha sido la efectividad a largo plazo de las políticas de seguridad minera de la MSHA en los últimos 25 años en términos de volumen e índices de frecuencia ($AIR$ y $FIR$)?.**

> La efectividad de las políticas de la MSHA ha sido altamente exitosa y sostenible en el tiempo. Los datos demuestran un cambio estructural en la industria:
  El volumen de accidentes y fatalidades disminullo:

> **Volumen de siniestros:** Se logró una reducción histórica drástica del -60.64% en el total de accidentes anuales entre el año 2000 y 2025.

> **Fatalidades**: Las fatalidades totales disminuyeron un -59.09%, cerrando el año 2025 con solo 27 muertes a nivel nacional.

> **Frecuencia e Impacto ($AIR$ y $FIR$):** La tasa de lesiones totales ($AIR$) cayó un -55.6% hasta llegar en 1.77 y la tasa de accidentes mortales ($FIR$) cayo un -53.9% hasta llegar un 0.0097. Esto demuestra que la reducción de accidentes no se debió a que las operaciones se volvieron intrínsecamente más seguras.

**2. ¿Cuáles son los estados críticos (puntos calientes) donde se concentran la mayor cantidad de accidentes y fatalidades en EE. UU.?**

> El análisis geográfico revela una que hay una conexion entre las fatalidades y los accidentes en los estados.

> **Mortalidad y Accidentabilidad:**El estado de West Virginia es el punto más crítico de todo el país que tiene una 202 muertes y luego sigue el estado de Kentucky (143 muertes), Ademas, ambos estados son los que tiene las mayor densidad de accidentes totales, con 28,819 y 22,180 respectivamente.

**3. ¿Qué tipo de minería y qué métodos de extracción representan el mayor riesgo operacional?**
> Al cruzar las variables de Actividad Minera y Tipo de Mina, los datos demuestra lo siguiente:

> La minería de Carbón Subterráneo (Coal - Underground) es la operación más peligrosa de la industria, registrando 56,443 accidentes y 333 muertes en estos 26 años. El mapas de calor histórica confirma que el carbón domina esta metrica.

> El riesgo en operaciones de Superficie concetra la mayor accidentabilidad con 109,397 con los sectores que dominos son primer lugar canteras (Stone)y carbon (Coal). Mientras la mortalidad tambien concentra son la cantera (Stone) con 190 y la actividad de Arena y Grava (Sand And Gravel).

> El riesgo en operaciones subterranea concetra la mayor tasa de accidentabilidad con  con los sectores que dominos son primer lugar canteras (Stone)y carbon (Coal).

> El sector más seguro son instalaciones de procesamiento (Facility) y la actividad de mineria no metalica(Nommetal) presentan los índices de accidentabilidad más bajos los cuales son 42,372 y 18,079,respectivamente.La mortalidad el sector mas seguro son las instalaciones de procesamiento (Facility) con 152 muerets y la otra es mineria no metalica(Nommetal) con 66 muertes.

**4. ¿Cuáles son los tipos de accidentes más comunes, partes del cuerpo afectadas y puestos de trabajo con mayor riesgo?**

> Los patrones son los siguientes:

> La accidentabilidad segun por los tipos de accidentes son la Manipulación de Materiales (Handling Of Materials) es la causa reina con 76,840 casos, seguida por los resbalones y caídas (Slip Or Fall Of Person) con 45,349. Respecto con la mortalidad es Transporte Motorizado (Powered Haulage) con 356 casos, seguida de Maquinaria (Machinery) con 245 casos.

> Las partes del cuerpo más afectadas son los dedos/pulgar (Finger/Thumb) con 39,122 casos y la espalda/zona lumbar con 30,825 casos.Respecto con la mortalidad son los multiples partes (Multiple Parts) con 603 muertes y Sistemas Corporales (Body Systems) con 177 muertes.

> El Puesto de trabajo más vulnerable es el personal de mantenimiento y mecánica (Maintenance Man, Mechanic) con 41,404 accidentes y la mortalidad tambien concentra este indice con 129 Muertes.

**5. ¿Cómo influye la experiencia del trabajador en la probabilidad de sufrir un accidente y fatalidad ?**

> Los accidentes menores son de los novatos,es decri el volumen de accidentabilidad lo concentran ellos.Los trabajadores con Baja Experiencia (1 a 5 años) e Inexpertos (<1 año) acumulan el 45.7% de los casos (25.3% y 20.4% respectivamente).

> Las muertes son de los expertos, se descubrimos que el 29% de las muertes ocurre en trabajadores de Alta Experiencia (>20 años), y un 22% en trabajadores de Media-Alta Experiencia (10 a 20 años).

---

## 📢 Recomendaciones

> Reentrenamiento a Veteranos,diseñar campañas específicas de ventilación, control de techos y mitigación de polvo/gases.

> Plan de choque de Mitigación en la minería de Carbón Subterráneo,
---
## 📐 KPIs calculados

| KPI | Definición | Fórmula |
|---|---|---|
| **AIR** | All injures Rate(Tasa de lesiones totales) | (Accidentes registrables × 200,000) / Horas trabajadas |
| **FIR** | fatality Injury Rate (Tasa de Fatalidades) | (  Fatalidades registradas  × 200,000) / Horas trabajadas |
| **Días perdidos promedio** | Severidad promedio por evento | Total días perdidos / Total accidentes con días perdidos |

> El factor 200,000 corresponde a las horas trabajadas por 100 trabajadores en un año de 50 semanas.

> Días perdidos promedio solo se utilizan los eventos que ocurren lesion, es decir, se excluyen las fatalidades y sin eventos de lesion y dias perdidos, ya que afecta al calculo del promedio.

>El año Fiscal lo consideran desde desde octubre del año anterior hasta el septiembre del mismo año.  
---
## 🖼️ Vista previa del dashboard

### Página 1 — Resumen.
![Dashboard Accidentes](./Imagenes/DashBoard_Accidentes.png)

### Página 2 — Catastro.
![Dashboard Fatalidades](./Imagenes/DashBoard_Fatalidades.png)
### Página 3 — Mapa.
![Dashboard Causas](./Imagenes/DashBoard_Causas.png)
### Página 4 — Capacidad y Regulación.
![Dashboard Tipo de minas](./Imagenes/DashBoard_Tipo_Minas.png)
### Página 5 — Capacidad y Regulación.
![Dashboard Tipo de minas](./Imagenes/DashBoard_Tipo_Minas.png)
### Página 6 — Capacidad y Regulación.
![Dashboard Tipo de minas](./Imagenes/DashBoard_Tipo_Minas.png)
### Página 7 — Modelo de Datos.
![Dashboard Tipo de minas](./Imagenes/DashBoard_Tipo_Minas.png)
---
## 📄 Licencia
Los datos utilizados son de dominio público, publicados por SERNAGEOMIN.
