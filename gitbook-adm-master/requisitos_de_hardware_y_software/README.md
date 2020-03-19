# Requisitos de hardware y software 

Se recomienda la siguiente configuración para administrar entre 1 y 2500 dispositivos.

---

## Servidor de Aplicaciones de Aranda

|  |  |
| :-- | :-- |
| **Sistema Operativo** | Windows Server 2012 R2, Standard Edition, x64, con las últimas versiones de Service Pack instaladas. |
| **Memoria RAM** | 6 GB o Superior. |
| **Procesador** | Intel Xeon 2,0 GHz, 12 MB Cache, Turbo, HT de 4 Core o superior, Intel Core i7 de cuarta generación o superior. |
| **Discos Duros** | Opción 1:  <ul><li>DD 0 (RAID 10) Partición C: 60 GB (SO) </li><li> DD 1 (RAID 10) Partición D: 80 GB (App y Servidor de archivos)</li></ul> *Notas:* <ul><li>Se recomienda que los discos duros sean SAS de 15.000 RPM o superior</li><li>El espacio en GB es el requerido y puede ser aumentado</li></ul> |
| **Notas** | Estos son los requisitos necesarios únicamente para Aranda y el servidor debe ser dedicado. |

---

## Servidor de Comunicaciones de Aranda (Conserver)

|  |  |
| :-- | :-- |
| **Sistema Operativo** | Windows Server 2012 R2, Standard Edition, x64, con las últimas versiones de Service Pack instaladas. |
| **Memoria RAM** | 4 GB o Superior. |
| **Procesador** | Intel Xeon 2,0 GHz, 12 MB Cache, Turbo, HT de 4 Core o superior, Intel Core i7 de cuarta generación o superior. |
| **Discos Duros** | Opción 1: <ul><li>DD 0 (RAID 10) Partición C: 60 GB (SO) </li><li> DD 1 (RAID 10) Partición D: 80 GB (App y Servidor de archivos)</li></ul> *Notas:* <ul><li>Se recomienda que los discos duros sean SAS de 15.000 RPM o superior</li><li>El espacio en GB es el requerido y puede ser aumentado</li></ul>|
| **Notas** | Estos requisitos son los necesarios únicamente para Aranda y este servidor debe ser dedicado. |

---

## Servidor de base de datos

|  |  |
| :-- | :-- |
| **Sistema Operativo** | Windows Server 2012 R2, Standard Edition, x64, con las últimas versiones de Service Pack instaladas. |
| **Memoria RAM** | 8 GB o Superior. |
| **Procesador** | Intel Xeon, 2.0 GHz, 12 MB Cache, Turbo, HT de 6 Core o superior. |
| **Discos Duros** | Opción 1: <ul><li>DD 0 (RAID 1) Partición C: 60 GB (SO)</li><li>DD 1 (RAID 10) Partición D: 120 GB (Data Files MDF)</li><li>DD 2 (RAID 1) Partición E: 80 GB (Transaction Log LDF)</li></ul>Opción 2:<ul><li>DD 0 (RAID 1) Partición C: 140 GB (SO, Transaction Log LDF)</li><li>DD 1 (RAID 10) Partición E: 120 GB (Data Files MDF)</li></ul> Opción 3:<ul><li>DD 0 (RAID 1) Partición C: 140 GB (SO, Transaction Log LDF)</li><li>DD 1 (RAID 5) Partición E: 120 GB (Data Files MDF)</li></ul>*Notas:* <ul><li>La opción 1 es la más recomendada, ya que su funcionamiento es mucho más rápido para las operaciones de lectura y escritura aleatorias en los MDF y para las operaciones de lectura y escritura secuenciales en los LDF.</li><li>Se recomienda que los discos duros sean SAS de 15.000 RPM o superior</li><li>El espacio en GB es el requerido y este puede ser aumentado en cualquiera de las 3 opciones.</li></ul> |
| **SQL Server** | Microsoft SQL Server 2012 Service Pack 2 Actualizado, instalado con: Full Text Search, Autenticación Mixta y Servicios de SQL Server Reporting Services. |
| **Notas** | Estos son los requerimientos necesarios únicamente para Aranda y el servidor debe ser dedicado. |
