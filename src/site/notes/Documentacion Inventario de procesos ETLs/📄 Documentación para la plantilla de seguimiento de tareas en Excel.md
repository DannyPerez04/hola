---
{"dg-publish":true,"permalink":"/documentacion-inventario-de-procesos-et-ls/documentacion-para-la-plantilla-de-seguimiento-de-tareas-en-excel/"}
---

# 🧠Inventario de Procesos ETL Enjoy Group

---
### 🎯 Objetivo del Proceso

> Este archivo tiene como propósito **documentar y centralizar los procesos ETL** que extraen datos desde diversas plataformas (como Monday, SharePoint, Skill4IT, Monolith y otros) hacia el Data Warehouse (DWH) del Enjoy Group. Permite tener visibilidad sobre la propiedad, ejecución, origen y complejidad técnica de cada proceso.
> 

---

### 📋 Pasos del Proceso

1. **Identificar el proceso a documentar**
    - Define el nombre del proceso y su propósito general.
2. **Asignar un ID único**
    - Usa una nomenclatura consistente para facilitar búsquedas y referencias.
3. **Determinar el servidor y propiedad**
    - Especifica dónde se ejecuta el proceso y quién es responsable.
4. **Registrar la ruta técnica**
    - Copia la ruta exacta del script o archivo ejecutable.
5. **Establecer horarios de ejecución**
    - Anota la hora de inicio y fin programada del proceso.
6. **Medir el tiempo de ejecución**
    - Calcula la duración total del proceso (si aplica).
7. **Describir funcionalmente el proceso**
    - Explica brevemente qué hace el proceso y qué datos transforma.
8. **Indicar el origen de los datos**
    - Define la fuente (ej. Monolith, SharePoint, etc.).
9. **Clasificar el tipo de proceso**
    - Usa etiquetas como ETL, BI, SFTP, etc.
10. **Contabilizar los scripts involucrados**
    - Anota cuántos scripts de Python se usan en el proceso.

---

### 📊 Descripción de Columnas

| **Columna** | **Descripción** |
| --- | --- |
| **Servidor** | Nombre del servidor donde corre el proceso. |
| **Id** | Identificador único del proceso. |
| **Proceso** | Nombre del proceso ETL. |
| **Propiedad** | Área o entidad responsable. |
| **Ruta** | Ruta local del script o archivo ejecutable. |
| **Hora de Inicio** | Hora programada de inicio. |
| **Hora Fin** | Hora de finalización. |
| **Tiempo de ejecución** | Duración total del proceso. |
| **Descripción Proceso** | Explicación funcional del proceso. |
| **Origen** | Fuente de los datos (ej. Monolith, Monday). |
| **Tipo** | Tipo de proceso (ETL). |
| **Cantidad python script** | Número de scripts Python involucrados. |

---

### 📊 Gráfico de procesos por origen

![520e95b6-0311-4e3d-9290-1b8f3dfb38a8.png](/img/user/Diagramas Y MAS/520e95b6-0311-4e3d-9290-1b8f3dfb38a8.png)

---

### **👥 Responsables Técnicos**

- 👨‍💻 **Danny Pérez** – Documentador, Ingeniero de Datos Junior
- 🧑‍🔧 **Allan** – Proveedor de datos, Ingeniero de Datos Senior

---

### 🧭 Alcance

Es la documentacion de los procesos de analitica para las propiadades actuales y futuras 

---

### 🟢 Estado del Proceso

> 🛠️ En proceso
> 
> 
> Bloqueado
> 
> ✅ Diseño
> 
> 🔄 En revisión
> 
> 🚀 Activo
> 
> 🛠️ En mejora continua
> 

---

### 🧩Enlaces o Documentos Relacionados

> Espacio para mejoras, sugerencias o incidentes detectados.
>  Monday Boards
> 	Batchs
> 		[[📥Documentación Técnica del Script   `00_Mndy_Boards_Master.bat`]]
> 		[[Documentacion Inventario de procesos ETLs/Monday Boards/Bats/📥Documentación Técnica – Proceso 01_Mndy_Boards_extr.bat\|📥Documentación Técnica – Proceso 01_Mndy_Boards_extr.bat]]
> 		[[Documentacion Inventario de procesos ETLs/Monday Boards/Bats/📥 Documentación Técnica – Proceso 02_Mndy_Boards_up.bat\|📥 Documentación Técnica – Proceso 02_Mndy_Boards_up.bat]]
> 	Scripts
> 		[[Documentacion Inventario de procesos ETLs/Monday Boards/Scrips Python/📨 Documentación Técnica – Proceso Mndy_Boards_Extract_Master.py\|📨 Documentación Técnica – Proceso Mndy_Boards_Extract_Master.py]]
> 		[[Documentacion Inventario de procesos ETLs/Monday Boards/Scrips Python/📨Documentación Técnica – Proceso Mndy_Boards_01_Download.py\|📨Documentación Técnica – Proceso Mndy_Boards_01_Download.py]]
> 		[[Documentacion Inventario de procesos ETLs/Monday Boards/Scrips Python/📨Documentación Técnica – Proceso Mndy_Boards_02_mov_files.py\|📨Documentación Técnica – Proceso Mndy_Boards_02_mov_files.py]]
> 		[[Documentacion Inventario de procesos ETLs/Monday Boards/Scrips Python/📨 Documentación Técnica – Proceso Mndy_Boards_Upload_Master.py\|📨 Documentación Técnica – Proceso Mndy_Boards_Upload_Master.py]]
> 		[[Documentacion Inventario de procesos ETLs/Monday Boards/Scrips Python/📨 Documentación Técnica – Proceso Mndy_01_fnnls_mrk_up.py\|📨 Documentación Técnica – Proceso Mndy_01_fnnls_mrk_up.py]]
> 		[[Documentacion Inventario de procesos ETLs/Monday Boards/Scrips Python/📨 Documentación Técnica – Proceso Mndy_02_fnnls_sls_up.py\|📨 Documentación Técnica – Proceso Mndy_02_fnnls_sls_up.py]]
> 		[[Documentacion Inventario de procesos ETLs/Monday Boards/Scrips Python/📨 Documentación Técnica – Proceso Mndy_03_brds_cntrl_up.py\|📨 Documentación Técnica – Proceso Mndy_03_brds_cntrl_up.py]]
> 		[[Documentacion Inventario de procesos ETLs/Monday Boards/Scrips Python/📨 Documentación Técnica Proceso Mndy_03_GSS_Up\|📨 Documentación Técnica Proceso Mndy_03_GSS_Up]]
> ShartPoint Boards
> 	Batchs
> 		[[Documentacion Inventario de procesos ETLs/Shartpoint Boards/Batchs/📥Documentación Técnica del Proceso Corp_excutv.bat\|📥Documentación Técnica del Proceso Corp_excutv.bat]]
> 	Scripts
> 		[[Documentacion Inventario de procesos ETLs/Shartpoint Boards/Scrips Python/📨 Documentación Técnica Master_corp_finz.py\|📨 Documentación Técnica Master_corp_finz.py]]
> 		[[Documentacion Inventario de procesos ETLs/Shartpoint Boards/Scrips Python/📨 Documentación Técnica 01Filling_template_BU.py\|📨 Documentación Técnica 01Filling_template_BU.py]]
> 		[[Documentacion Inventario de procesos ETLs/Shartpoint Boards/Scrips Python/📨Documentación Técnica 02Filling_template.py\|📨Documentación Técnica 02Filling_template.py]]
> 		[[Documentacion Inventario de procesos ETLs/Shartpoint Boards/Scrips Python/📨 Documentación Técnica 03FNB.py\|📨 Documentación Técnica 03FNB.py]]
> 		[[Documentacion Inventario de procesos ETLs/Shartpoint Boards/Scrips Python/📨 Documentación Técnica 04PNL_BU.py\|📨 Documentación Técnica 04PNL_BU.py]]
> 		[[Documentacion Inventario de procesos ETLs/Shartpoint Boards/Scrips Python/📨 Documentación Técnica 05PNL.py\|📨 Documentación Técnica 05PNL.py]]
> 		[[Documentacion Inventario de procesos ETLs/Shartpoint Boards/Scrips Python/📨 Documentación Técnica 06fnz_upload.py\|📨 Documentación Técnica 06fnz_upload.py]]
> Skill4it
> 	Batchs
> 		[[Documentacion Inventario de procesos ETLs/Skill4it/Batchs/📥Documentación del Proceso Skill4it_Master.bat\|📥Documentación del Proceso Skill4it_Master.bat]]
> 		[[Documentacion Inventario de procesos ETLs/Skill4it/Batchs/📥Documentación Técnica `Skill4it_Master_c.bat\|📥Documentación Técnica `Skill4it_Master_c.bat]]
> 		[[Documentacion Inventario de procesos ETLs/Skill4it/Batchs/📥 Documentación Técnica Skill4it_Master_e.bat\|📥 Documentación Técnica Skill4it_Master_e.bat]]
> 		[[Documentacion Inventario de procesos ETLs/Skill4it/Batchs/📥Documentación Técnica Skill4it_Master_rvn.bat\|📥Documentación Técnica Skill4it_Master_rvn.bat]]
> 	Scripts 
> 		[[Documentacion Inventario de procesos ETLs/Skill4it/Scripts/📨 Documentación Técnica skllt_master_ext.py\|📨 Documentación Técnica skllt_master_ext.py]]
> 		[[Documentacion Inventario de procesos ETLs/Skill4it/Scripts/📨 Documentación Técnica Ryl_Corn_rsv_extract.py\|📨 Documentación Técnica Ryl_Corn_rsv_extract.py]]
> 		[[Documentacion Inventario de procesos ETLs/Skill4it/Scripts/📨 Documentación Técnica Ryl_Corn_rvn_extract.py\|📨 Documentación Técnica Ryl_Corn_rvn_extract.py]]
> 		[[Documentacion Inventario de procesos ETLs/Skill4it/Scripts/📨 Documentación Técnica Ryl_Corn_rsv_disconn.py\|📨 Documentación Técnica Ryl_Corn_rsv_disconn.py]]
> 		[[Documentacion Inventario de procesos ETLs/Skill4it/Scripts/📨 Documentación Técnica skllt_master_upload.py\|📨 Documentación Técnica skllt_master_upload.py]]
> 		[[Documentacion Inventario de procesos ETLs/Skill4it/Scripts/📨 Documentación Técnica Ryl_Corn_rsv_upload.py\|📨 Documentación Técnica Ryl_Corn_rsv_upload.py]]
> 		[[Documentacion Inventario de procesos ETLs/Skill4it/Scripts/📨 Documentación Técnica Ryl_Corn_rvn_upload.py\|📨 Documentación Técnica Ryl_Corn_rvn_upload.py]]
> 		[[Documentacion Inventario de procesos ETLs/Skill4it/Scripts/📨 Documentación Técnica Ryl_Corn_rsv_conn.py\|📨 Documentación Técnica Ryl_Corn_rsv_conn.py]]
> 		[[Documentacion Inventario de procesos ETLs/Skill4it/Scripts/📨 Documentación Técnica Ryl_Corn_rsv_connt2.py\|📨 Documentación Técnica Ryl_Corn_rsv_connt2.py]]
> Monolith Reservaciones
> 	Batchs
> 		[[Documentacion Inventario de procesos ETLs/Monolith Reservaciones/Batchs/📥 Documentación Técnica - MonolithRsv.bat\|📥 Documentación Técnica - MonolithRsv.bat]]
> 	Scripts
> 		[[Documentacion Inventario de procesos ETLs/Monolith Reservaciones/Scripts/📨 Documentación Técnica - etl_monolith_rsv_fiesta.py\|📨 Documentación Técnica - etl_monolith_rsv_fiesta.py]]
> 		[[Documentacion Inventario de procesos ETLs/Monolith Reservaciones/Scripts/📨 Documentación Técnica - etl_monolith_rsv_lapas.py\|📨 Documentación Técnica - etl_monolith_rsv_lapas.py]]
> 		[[Documentacion Inventario de procesos ETLs/Monolith Reservaciones/Scripts/📨 Documentación Técnica - etl_monolith_rsv_marina.py\|📨 Documentación Técnica - etl_monolith_rsv_marina.py]]
> 		[[Documentacion Inventario de procesos ETLs/Monolith Reservaciones/Scripts/📨 Documentación Técnica - etl_monolith_grupos_v1.py\|📨 Documentación Técnica - etl_monolith_grupos_v1.py]]
> 		[[Documentacion Inventario de procesos ETLs/Monolith Reservaciones/Scripts/📨 Documentación Técnica - etl_monolith_stats_v1.py\|📨 Documentación Técnica - etl_monolith_stats_v1.py]]
> Monolith Restaurantes
> 	Batchs
> 		[[Documentacion Inventario de procesos ETLs/Monolith Restaurantes/Batchs/📥Documentación - Monolith Sales Proceso de carga\|📥Documentación - Monolith Sales Proceso de carga]]
> 	Scripts
> 		[[Documentacion Inventario de procesos ETLs/Monolith Restaurantes/Scripts/📨 Documentación - monolith_restaurantes_Master.py\|📨 Documentación - monolith_restaurantes_Master.py]]
> 		[[Documentacion Inventario de procesos ETLs/Monolith Restaurantes/Scripts/📨 Documentación - etl_monolith_det_transf_fiesta.py\|📨 Documentación - etl_monolith_det_transf_fiesta.py]]
> 		[[Documentacion Inventario de procesos ETLs/Monolith Restaurantes/Scripts/📨 Documentación - etl_monolith_det_transf_marina.py\|📨 Documentación - etl_monolith_det_transf_marina.py]]
> 		[[Documentacion Inventario de procesos ETLs/Monolith Restaurantes/Scripts/📨Documentación - etl_monolith_det_transf_lapas.py\|📨Documentación - etl_monolith_det_transf_lapas.py]]
> 		[[Documentacion Inventario de procesos ETLs/Monolith Restaurantes/Scripts/📨 Documentación - etl_monolith_rest_transf_lapas.py\|📨 Documentación - etl_monolith_rest_transf_lapas.py]]
> 		[[Documentacion Inventario de procesos ETLs/Monolith Restaurantes/Scripts/📨 Documentación - etl_monolith_rest_transf_marina.py\|📨 Documentación - etl_monolith_rest_transf_marina.py]]
> 		[[Documentacion Inventario de procesos ETLs/Monolith Restaurantes/Scripts/📨Documentación - etl_monolith_rest_transf_fiesta.py\|📨Documentación - etl_monolith_rest_transf_fiesta.py]]
> 		[[Documentacion Inventario de procesos ETLs/Monolith Restaurantes/Scripts/📨 Documentación - etl_monolith_rest_transf_bacchus.py\|📨 Documentación - etl_monolith_rest_transf_bacchus.py]]
> 		[[Documentacion Inventario de procesos ETLs/Monolith Restaurantes/Scripts/📨Documentación - etl_monolith_rest_transf_lile.py\|📨Documentación - etl_monolith_rest_transf_lile.py]]
> Monolith Pops
> 	Batchs
> 		[[Documentacion Inventario de procesos ETLs/Monolith POPS/Batchs/📥 Documentación - FctPPSMoved.bat\|📥 Documentación - FctPPSMoved.bat]]
> 		[[Documentacion Inventario de procesos ETLs/Monolith POPS/Batchs/📥Documentación - FctPPSProcess-transf.bat\|📥Documentación - FctPPSProcess-transf.bat]]
> 		[[Documentacion Inventario de procesos ETLs/Monolith POPS/Batchs/📥Documentación - FctPPSProcess.bat\|📥Documentación - FctPPSProcess.bat]]
> 	Scripts
> 		[[Documentacion Inventario de procesos ETLs/Monolith POPS/Script/📨Documentación - Pps_Master.py\|📨Documentación - Pps_Master.py]]
> 		[[Documentacion Inventario de procesos ETLs/Monolith POPS/Script/📨Documentación - PpsJsonXml.py\|📨Documentación - PpsJsonXml.py]]
> 		[[Documentacion Inventario de procesos ETLs/Monolith POPS/Script/📨 Documentación - PpsXmlCsv.py\|📨 Documentación - PpsXmlCsv.py]]
---