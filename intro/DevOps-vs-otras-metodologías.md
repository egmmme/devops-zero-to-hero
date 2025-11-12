[[_TOC_]]

# DevOps vs otras metodologías

## Introducción

DevOps no es una metodología que compita con otras como [Agile](https://www.atlassian.com/agile) o [ITIL](https://www.peoplecert.org/best-practices/itil), sino que **las complementa**. Entender sus diferencias y puntos de encuentro es clave para aplicar DevOps de forma efectiva en entornos reales.

## Comparativa general

| Característica     | DevOps                            | Agile                                                                                                                                             | ITIL                                                                                                                                                            |
|--------------------|-----------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Enfoque principal  | Automatización y entrega continua | Gestión ágil de proyectos                                                                                                                         | Gestión de servicios de TI                                                                                                                                      |
| Colaboración       | Dev + Ops + Sec                   | Dev + Negocio                                                                                                                                     | Ops + Negocio                                                                                                                                                   |
| Ciclo de entrega   | Continuo                          | Iterativo                                                                                                                                         | Por solicitud                                                                                                                                                   |
| Automatización     | Alta                              | Variable                                                                                                                                          | Baja                                                                                                                                                            |
| Documentación      | Ligera y automatizada             | Ligera                                                                                                                                            | Extensa                                                                                                                                                         |
| Herramientas clave | CI/CD, IaC, Monitorización        | [Scrum](https://www.atlassian.com/agile/scrum), [Kanban](https://www.atlassian.com/agile/kanban), [Jira](https://www.atlassian.com/software/jira) | [CMDB](https://www.atlassian.com/itsm/cmdb/what-is-a-cmdb), [ITSM](https://www.atlassian.com/itsm), [Service Desk](https://www.atlassian.com/itsm/service-desk) |
| Objetivo final     | Entrega rápida y estable          | Adaptación al cambio                                                                                                                              | Estabilidad y control                                                                                                                                           |

## DevOps + Agile: una combinación poderosa

- **Agile** se enfoca en cómo se planifica y desarrolla el software.
- **DevOps** se enfoca en cómo se prueba, entrega, despliega y opera ese software.

Ambos enfoques se complementan perfectamente:

- Agile mejora la **velocidad de desarrollo**.
- DevOps mejora la **velocidad de entrega y operación**.

> Nota: Muchas organizaciones exitosas combinan Agile para la gestión de proyectos y DevOps para la entrega técnica.

## DevOps vs ITIL

- ITIL es un marco tradicional centrado en la **gestión de servicios de TI**, con procesos bien definidos y orientados a la estabilidad.
- DevOps promueve la **agilidad y la automatización**, priorizando la entrega continua y la mejora constante.

Aunque pueden parecer opuestos, **no son incompatibles**. DevOps puede integrarse con ITIL modernizando procesos como:

- Gestión de cambios → Automatización de despliegues.
- Gestión de incidencias → Monitorización proactiva.
- Gestión de configuración → [Infraestructura como código](/DevOps/IaC/Qué-es.md).

## ¿Cuál elegir?

No se trata de elegir uno u otro, sino de **entender qué aporta cada uno** y cómo pueden convivir. DevOps es especialmente útil cuando:

- Se necesita entregar software de forma frecuente.
- Hay múltiples equipos colaborando.
- Se busca automatizar y escalar procesos.
