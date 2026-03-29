# 🛡️ Portafolio de Nicolás Pérez Cerda
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Cisco](https://img.shields.io/badge/Cisco-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
---

## 👤 Sobre mí

Soy **Nicolás Andrés Pérez Cerda**, Ingeniero en Conectividad y Redes, y actualmente me dedico a **Soporte Tecnológico**, buscando la reconversión profesional hacia la **Ciberseguridad**.

**Mi Trayectoria:**
* Ingeniero en Conectividad y Redes (IP San Sebastián).
* Experiencia en **NOC de Monitoreo**.
* Formación continua en Ciberseguridad y Python.

**¿Por qué contactarme?**
Soy una persona **responsable, proactiva** y con una fuerte motivación por el aprendizaje constante.
---
## 🛠️ Habilidades destacadas

### 🌐 Redes y Conectividad
* **Protocolos de Enrutamiento:** RIP/ ESTATIC/ OSPF / EIGRP / BGP.
* **Redes de Acceso:** VLANs, Inter-VLAN Routing.
* **Alta Disponibilidad:** Implementación de redundancia (HSRP, Etherchannel, STP). 

### 🔒 Seguridad de Red y Hardening
* **Seguridad de Capa 2 (L2):** Hardening de Infraestructura y Control de Acceso (STP, Seguridad L2).
* **Control de Tráfico:** Listas de Control de Acceso (ACLs).
* **Autenticación Centralizada:** Configuración de TACACS+ y Syslog centralizado.
* **VPNs:** Implementación de VPNs (IPsec, Site-to-Site).

### 🔍 Ciberseguridad y Herramientas
* **Distribuciones:** Kali Linux.
* **Análisis de Tráfico:** Wireshark.
* **Mapeo de Red:** Nmap.

---
## 📁 Proyectos en el portafolio

### 🛡️ Seguridad Avanzada (Firewall, VPN, Hardening)
* **Soluciones de Seguridad Corporativa: Firewall Cisco ASA, VPN de Acceso Remoto...**
  * *Foco: Implementación de seguridad perimetral, DMZ y VPN.* [Archivo Packet Tracert](https://drive.google.com/file/d/19kWHh3tJvBpkttV4DVBgv-Ci5MAmPjTS/view?usp=drive_link)
* **Implementación de Políticas de Seguridad: ACL, NAT Estático y Monitoreo (SNMP/SYSLOG)**
  * *Foco: Control de tráfico, restricción de acceso (ACL) y visibilidad de red.* [Archivo Packet Tracert](https://drive.google.com/file/d/10arOpSYmTNtU1tFBdrxiF41rpPDDnyyI/view?usp=drive_link)

### 🔍 Ciberseguridad y Análisis
* **Análisis de Seguridad en Redes de Datos: Testeo con Hping3 y Wireshark** * *Foco: Análisis forense y testeo de conectividad con herramientas de Kali Linux.* [Link](https://docs.google.com/document/d/1F_2BTmyfGmp6yGGPQyK2txbxGLnvGvsa/edit?usp=drive_link&ouid=108335102691958278528&rtpof=true&sd=true)
* **Documentación de Hallazgos de Seguridad y Mitigación de Vulnerabilidades** * *Foco: Análisis de un Incidente de Seguridad (IR), Reporting y mitigación.* [Link](https://docs.google.com/document/d/1-taIb7uiCI1fEmRRwx-gy71bD6BMYhLW/edit?usp=drive_link&ouid=108335102691958278528&rtpof=true&sd=true)


### ⚙️ Fundamentos de Red y Arquitectura
* **Implementación de Alta Disponibilidad (HA L2/L3): Etherchannel, STP y HSRP**
  * *Foco: Asegurar la continuidad operacional de la red con redundancia L2 y L3.* [Archivo Packet Tracert](https://drive.google.com/file/d/1iHEpsGeqPmi9f6oS6rK3UVzp7UwSXa9y/view?usp=drive_link)
* **Hardening de Infraestructura y Control de Acceso: STP, AAA/TACACS+, Seguridad L2** * *Foco: Seguridad de Capa 2, autenticación centralizada y protección de infraestructura.* [Archivo Packet Tracert](https://drive.google.com/file/d/1_lOJIwCNiEJEWDgi3_F3XRmY0Wy-Zu7a/view?usp=drive_link)

## 📊 Análisis de Datos
 
### 🔬 Caso de Estudio: EDA para ComercioYA
 
> **Proyecto representativo de mi crecimiento técnico en Análisis de Datos**
 
---
 
#### 📌 Descripción de la actividad
 
Desarrollo de un análisis exploratorio de datos (EDA) completo para **ComercioYA**, una empresa de comercio electrónico. A partir de un dataset de 250 registros de clientes (generado con NumPy con semilla fija para reproducibilidad), se analizó el comportamiento de compra, la distribución de montos, la correlación entre variables y se construyeron modelos de regresión para identificar los factores que más influyen en los ingresos del negocio.
 
El dataset incluía variables como: `visitas_mes`, `monto_compra`, `devoluciones`, `puntuación_cliente` y `categoria_frecuente` (Electrónica, Hogar, Moda, Deportes).
 
---
 
#### 🧩 Desafío principal
 
El desafío central fue transformar un conjunto de datos sin estructura analítica previa en **insights accionables para el negocio**. Esto implicó:
 
- Identificar qué variables realmente predicen el gasto del cliente (y cuáles no).
- Detectar y decidir qué hacer con los valores atípicos (outliers), ya que eliminarlos habría significado ignorar a los **clientes de mayor valor**.
- Construir visualizaciones que contaran una historia clara para una audiencia no técnica.
 
---
 
#### 💡 Solución propuesta
 
Se desarrolló un pipeline de análisis en 6 etapas:
 
1. **EDA inicial (IDA):** revisión de tipos de datos, valores nulos y estadísticas descriptivas.
2. **Estadística descriptiva:** cálculo de media, mediana, moda, varianza, desviación estándar, cuartiles y percentil 90 sobre `monto_compra`.
3. **Detección de outliers:** método IQR (rango intercuartílico) para identificar clientes de alto valor sin eliminarlos del análisis.
4. **Análisis de correlación:** matriz de Pearson y heatmap para medir relaciones entre variables numéricas.
5. **Regresión lineal simple y múltiple:** modelos OLS (statsmodels) con `visitas_mes` y `puntuación_cliente` como predictores del `monto_compra`.
6. **Visualización avanzada:** pairplot, violinplot, jointplot, FacetGrid y subplots personalizados con Matplotlib.
 
**Hallazgo clave:** Las visitas al mes no tienen correlación significativa con el monto de compra. Los clientes de alto valor (outliers superiores) representan solo el ~5% de la base pero generan un porcentaje desproporcionado de los ingresos totales, lo que sugiere implementar un programa de fidelización VIP.
 
---
 
#### 🛠️ Herramientas técnicas utilizadas
 
| Herramienta | Uso |
|---|---|
| Python 3 | Lenguaje base del análisis |
| Pandas | Carga, manipulación y filtrado del dataset |
| NumPy | Generación del dataset y cálculos estadísticos |
| Matplotlib | Visualizaciones personalizadas, subplots y anotaciones |
| Seaborn | Heatmap, violinplot, pairplot, jointplot, FacetGrid |
| Statsmodels | Regresión OLS simple y múltiple |
| Scikit-learn | Métricas de evaluación (MSE, MAE) |
| Jupyter Notebook | Entorno de desarrollo y documentación |
 
---
 
#### 📈 Métricas de impacto logradas
 
- **250 registros** analizados con pipeline reproducible (semilla fija `np.random.seed(42)`).
- **6 tipos de gráficos** generados y exportados como PNG para informes.
- **2 modelos de regresión** evaluados (simple y múltiple) con métricas R², MSE y MAE.
- Identificación de que los outliers generan un **impacto desproporcionado** en los ingresos totales, derivando en una recomendación concreta de segmentación VIP.
- Detección de **correlación espuria** entre visitas y monto de compra, corrigiendo un supuesto de negocio incorrecto.
 
---
 
#### 🧠 Principales aprendizajes
 
- La **mediana es más robusta que la media** cuando existen outliers, algo crítico para no tomar decisiones de negocio basadas en promedios distorsionados.
- Los valores atípicos no son siempre errores: en comercio electrónico, pueden ser los **clientes más valiosos**.
- La regresión lineal tiene límites: un R² bajo no significa que el análisis falló, sino que el fenómeno es más complejo y requiere otras variables o modelos.
- La visualización es tan importante como el cálculo: un heatmap o violinplot comunica en segundos lo que una tabla de números no logra transmitir.
 
---
 
#### ✅ Habilidades técnicas aplicadas
 
`Python` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn` · `Statsmodels` · `Scikit-learn` · `EDA` · `Estadística Descriptiva` · `Regresión Lineal` · `Detección de Outliers` · `Visualización de Datos` · `Jupyter Notebook`
 
---
 
#### 🎯 ¿Por qué elegí este proyecto para mi portafolio?
 
Este proyecto es el más representativo de mi crecimiento porque integra **todo el ciclo del análisis de datos**: desde la exploración inicial hasta la comunicación de hallazgos con recomendaciones estratégicas concretas. No se trató solo de aplicar funciones de Pandas, sino de tomar decisiones analíticas con criterio (como mantener los outliers y justificarlo con argumentos de negocio). Además, refleja mi capacidad para conectar los números con el mundo real, algo que viene de mi experiencia previa trabajando con infraestructura crítica donde los datos de monitoreo siempre tienen consecuencias operacionales.
 
🔗 **[Ver notebook completo en GitHub](https://github.com/Recnico/EDA-ComercioYA/tree/main)**

## 📬 Contacto

| Plataforma | Enlace |
| :--- | :--- |
| 📧 Correo | [nicolas.perez.cerda@gmail.com](mailto:nicolas.perez.cerda@gmail.com) |
| 💼 LinkedIn | [nicolasperezcerda](https://www.linkedin.com/in/nicolasperezcerda/) |
| 🐙 GitHub | [Recnico](https://github.com/Recnico) |

---

✍️ *Creado con Readme.so*
