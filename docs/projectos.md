### APORTACIONES ADMINISTRATIVAS

- Con esta Visión metodológicamente congruente con un enfoque de estrategias viables y ante la revisión obligada del actual modelo de administración publica, impulse el “Modelo Administrativo, Transversal, Estratégico e Integral” (MATEI), que simplifica el marco teórico, precisa objetivos, actualiza estructuras y fortalece procesos transversales paralelos. El modelo se origina en los principios de administración general y se reforma acorde a los cambios en los componentes y normativa de la administración pública. Rescata el valor de la coherencia entre estructura y manuales de organización, ratificando la claridad del Programa Anual de Trabajo (PAT), del Programa de Trabajo de Control Interno (PTCI) y de la Matriz de Indicadores de Resultados (MIR).

	La trascendencia del MATEI, radica en ejecutar cambios sustantivos en la forma de operar en las tres (3)  Sub-funciones administrativas tradicionales: (Recursos Humanos, Financieros y Materiales); suprimiendo oficinas en las Direcciones Generales con procesos idénticos, creando a nivel Subsecretaria la unidad coordinadora con 6 áreas de procesos especializados integrados: 1) Sistema de Gestión documental, Seguimiento y Archivo; 2) Seguimiento Programático-Presupuestal; 3) Desarrollo de Recursos Humanos y Capacitación; 4) Recursos Financieros y Tesorería; 5) Recursos Materiales, Servicios Generales e Informáticos; y 6) Transparencia, Rendición de Cuentas individual y Acceso a la Información Pública.



### La estrategia organizativa

 - La estrategia organizativa al cambiar de trabajos seriados, autónomos, personalizados y con fines específicos, a trabajos administrados con un objetivo común, colaboración en equipo, transformaciones profundas e integradas, procesos simultáneos, transversales y paralelos, se da seguimiento a las orientaciones de la teoría de la administración y de la alta dirección corporativa; responde así a una planeación actualizada que no sólo define políticas y programas, suprime múltiples actividades idénticas y repetitivas, también acorta líneas de mando, optimiza presupuestos  y respeta austeridad y transparencia; por lo mismo, garantiza la rendición de cuentas y a un tiempo, el cumplimiento del objetivo.

 - El (MATEI) toma en cuenta las necesidades y capacidades del personal, endurece las funciones de regulación tales como; integración, supervisión, vigilancia y control e incorpora nuevos procesos dirigidos a la evaluación del desempeño y rendición de cuentas. El MATEI con el propósito de contribuir en la capacidad resolutiva de la administración pública, se encamina a buscar la certificación de actividades individuales como elemento indispensable para la renovación optima del personal. Es por tanto deseable aprovechar la experiencia desarrollada en ámbitos del sector privado con los KPI´s “indicadores de desempeño y rendimiento individual” cuyas métricas son exitosas si están asociadas con los objetivos propuestos. Implica también la realización anual de un análisis de Debilidades, Amenazas, Fortalezas y Oportunidades (DAFO).

### DEVOPS

  - Specially this project requires the close collaboration with DEVOPS teams to understand their code and integrate the monitoring with their pipelines to correct performance and other error during deployment (Jenkins, and Azure Pipelines).

  - Result of this collaboration help us to participate in additional projects such as "OS Software replacement" which required to design/build support GKE cluster with RabbitMQ to perform activities link to their Jenkins Pipelines.

  - Knowledge in K8S Google Cloud Platform and AWS
      Terraform to automate the GKE cluster creation.

  - During the definition of this service it was necessary to complete and get the technical approval for the Security concept which validated that all traffic is encrypted and under SAP standards.

### Security

All listed projects requires to design and implement the Security standards such as:
    - Monitoring alert with Prisma (Palo Alto networks)
    - Passwords closely guard in the Vault and carefully usage of API's to extract secrets.
    - Definition of Access Profiles for my projects
    - Definition of Firewall rules.
    - Analysis of Logs and Alert in Splunk, Logstash


- In Addition,I'm working to:
    - define a new internal services "Prometheus as service on K8S environments " this requires
    - Collaboration / definition with the FUNCTIONS AS Service using GKE and Open FAAS which have the goal to create/run shareable functions (code) as micro-services across multiple teams , this project will create metrics that will be consolidated/aggregated in a data lake so it's one source of information
