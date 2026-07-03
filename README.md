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
│   └──  CATASTRO_RELAVES_CHILE_OCT2025_1 .xlsm                               # Data de los Relaves en Chile hasta octubre 2025
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
CATASTRO_RELAVES_CHILE_OCT2025_1.xlsm  
        │
        ▼
   Power Query
   ├── EDA.
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
   Power BI
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
|Power Query|Limpieza,EDA, transformación de datos-Eliminacion de columnas Innesesarias-Corrección de Errores-ETC.Realización del modelo de datos Tipo estrella|
|Power BI| Creación del Dashboard Iteractivo para realizar el catastro de Relave,creación de nuevas columnas y KPI |

---
## 📊 Hallazgos principales

**1. ¿      ?.**

> 

**2. ¿  ?**

> 

**3. ¿  ?**
> 

**4. ¿   ?**

> 

**5. ¿  ?**

> 

---

## 📢 Recomendaciones

> 
---
## 📐 KPIs calculados

| KPI | Definición | Fórmula |
|---|---|---|
| **   ** |   | (Accidentes registrables × 200,000) / Horas trabajadas |
| **FIR** | fatality Injury Rate (Tasa de Fatalidades) | (  Fatalidades registradas  × 200,000) / Horas trabajadas |
| **Días perdidos promedio** | Severidad promedio por evento | Total días perdidos / Total accidentes con días perdidos |

>  
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
