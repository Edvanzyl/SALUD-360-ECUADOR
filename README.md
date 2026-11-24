# SALUD 360 ECUADOR

### Open-Source Healthcare Coordination & Capacity Management Platform

**Una visión integral, inteligente y conectada de la salud en Ecuador.**

Español | English

---

## ESPAÑOL

### 1. ¿Qué es SALUD 360 ECUADOR?

SALUD 360 ECUADOR es una iniciativa tecnológica de código abierto orientada al desarrollo de una plataforma digital para mejorar la coordinación administrativa y operativa de los servicios de salud en Ecuador.

El proyecto propone una infraestructura modular que permita organizar información sobre establecimientos sanitarios, servicios disponibles, capacidad operativa, gestión de citas y procesos administrativos de referencia y contrarreferencia.

Su propósito es facilitar la conexión entre la demanda de atención de la población y la capacidad declarada de los establecimientos de salud, contribuyendo a una mejor planificación, visibilidad y coordinación de los recursos sanitarios.

SALUD 360 ECUADOR busca desarrollar tecnología abierta, escalable, interoperable y adaptable a las necesidades del sistema sanitario ecuatoriano.

### 2. El problema que buscamos abordar

- Fragmentación de información entre establecimientos.
- - Dificultades para conocer la disponibilidad de servicios.
  - - Demoras en los procesos de asignación de citas.
    - - Sobrecarga de determinados establecimientos sanitarios.
      - - Distribución desigual de la demanda asistencial.
        - - Limitaciones en la coordinación entre niveles de atención.
          - - Dificultades para dar seguimiento administrativo a referencias.
            - - Falta de información consolidada para planificación operativa.
             
              - ### 3. Nuestra propuesta
             
              - Desarrollar una plataforma digital que permita centralizar y organizar información operativa de establecimientos de salud, facilitando la consulta de servicios, la visualización de capacidad declarada y la coordinación administrativa de los procesos de atención.
             
              - La plataforma se plantea como una infraestructura complementaria a los sistemas institucionales existentes, no como un reemplazo de estos.
             
              - ### 4. Objetivo general
             
              - Diseñar y desarrollar una plataforma de código abierto que contribuya a mejorar la gestión, coordinación y visibilidad de la capacidad operativa de los establecimientos de salud en Ecuador, mediante herramientas digitales modulares, interoperables y orientadas a las necesidades del sistema sanitario.
             
              - ### 5. Objetivos específicos
             
              - 1. Desarrollar un directorio digital de establecimientos de salud y servicios disponibles.
                2. 2. Diseñar herramientas para gestionar y consultar disponibilidad de citas.
                   3. 3. Implementar mecanismos de visualización de capacidad operativa declarada.
                      4. 4. Facilitar la trazabilidad administrativa de procesos de referencia y contrarreferencia.
                         5. 5. Desarrollar paneles de indicadores para planificación y gestión sanitaria.
                            6. 6. Establecer una arquitectura tecnológica modular y escalable.
                               7. 7. Evaluar mecanismos de interoperabilidad con estándares sanitarios.
                                  8. 8. Promover el desarrollo colaborativo de tecnología sanitaria de código abierto.
                                    
                                     9. ### 6. Módulos del proyecto
                                    
                                     10. **6.1. Gestión de citas**
                                     11. - Consulta de disponibilidad.
                                         - - Búsqueda por establecimiento y especialidad.
                                           - - Solicitudes de citas.
                                             - - Reprogramación y cancelación.
                                               - - Listas de espera.
                                                 - - Notificaciones y recordatorios.
                                                  
                                                   - **6.2. Gestión de capacidad sanitaria**
                                                   - - Registro de establecimientos.
                                                     - - Catálogo de servicios.
                                                       - - Capacidad declarada.
                                                         - - Disponibilidad de cupos.
                                                           - - Información operativa actualizada.
                                                             - - Indicadores de utilización.
                                                              
                                                               - **6.3. Referencia y contrarreferencia**
                                                               - - Registro de solicitudes administrativas.
                                                                 - - Seguimiento de referencias.
                                                                   - - Identificación de establecimientos de destino.
                                                                     - - Estado de recepción.
                                                                       - - Trazabilidad del proceso.
                                                                         - - Registro de respuesta administrativa.
                                                                          
                                                                           - **6.4. Analítica e inteligencia sanitaria**
                                                                           - - Demanda de servicios.
                                                                             - - Tiempos de espera.
                                                                               - - Utilización de capacidad.
                                                                                 - - Distribución territorial de la demanda.
                                                                                   - - Indicadores de actividad.
                                                                                     - - Informes administrativos.
                                                                                      
                                                                                       - **6.5. Geolocalización**
                                                                                       - - Directorio geográfico.
                                                                                         - - Ubicación de establecimientos.
                                                                                           - - Servicios disponibles.
                                                                                             - - Visualización de la oferta sanitaria.
                                                                                               - - Herramientas de búsqueda territorial.
                                                                                                
                                                                                                 - **6.6. Administración y seguridad**
                                                                                                 - - Gestión de usuarios.
                                                                                                   - - Roles y permisos.
                                                                                                     - - Auditoría de operaciones.
                                                                                                       - - Control de acceso.
                                                                                                         - - Gestión de establecimientos.
                                                                                                           - - Supervisión de calidad de datos.
                                                                                                            
                                                                                                             - ### 7. Arquitectura tecnológica
                                                                                                            
                                                                                                             - - Frontend: React y TypeScript.
                                                                                                               - - Backend: Python y FastAPI.
                                                                                                                 - - Base de datos: PostgreSQL.
                                                                                                                   - - API: REST.
                                                                                                                     - - Interoperabilidad sanitaria futura: evaluación de HL7 FHIR.
                                                                                                                       - - Contenedores: Docker.
                                                                                                                         - - Control de versiones: Git y GitHub.
                                                                                                                           - - Pruebas: Pytest y herramientas de pruebas frontend.
                                                                                                                            
                                                                                                                             - La arquitectura será modular para facilitar el mantenimiento, la escalabilidad y la incorporación progresiva de funcionalidades.
                                                                                                                            
                                                                                                                             - ### 8. Interoperabilidad
                                                                                                                            
                                                                                                                             - El proyecto contempla evaluar mecanismos de interoperabilidad con los sistemas de información existentes en Ecuador.
                                                                                                                            
                                                                                                                             - A largo plazo, se busca estudiar posibles mecanismos de integración con instituciones como el Ministerio de Salud Pública (MSP) y el Instituto Ecuatoriano de Seguridad Social (IESS), siempre mediante autorización institucional, acuerdos formales y cumplimiento de los requisitos técnicos y legales.
                                                                                                                            
                                                                                                                             - **Actualmente no existe ninguna integración institucional implementada o autorizada.**
                                                                                                                            
                                                                                                                             - ### 9. Privacidad, seguridad y protección de datos
                                                                                                                            
                                                                                                                             - - Privacidad desde el diseño.
                                                                                                                               - - Minimización de datos.
                                                                                                                                 - - Control de acceso por roles.
                                                                                                                                   - - Cifrado de información.
                                                                                                                                     - - Registro de auditoría.
                                                                                                                                       - - Gestión segura de credenciales.
                                                                                                                                         - - Políticas de conservación y eliminación de datos.
                                                                                                                                           - - Evaluaciones de seguridad.
                                                                                                                                             - - Cumplimiento de la legislación ecuatoriana aplicable, incluida la Ley Orgánica de Protección de Datos Personales.
                                                                                                                                              
                                                                                                                                               - Durante el desarrollo se utilizarán exclusivamente datos sintéticos o adecuadamente anonimizados. No se deben incorporar datos personales ni información clínica real al repositorio.
                                                                                                                                              
                                                                                                                                               - ### 10. Alcance y visión futura
                                                                                                                                              
                                                                                                                                               - La primera etapa se concentra en desarrollar un prototipo funcional que permita demostrar la arquitectura, los módulos principales y los flujos administrativos propuestos.
                                                                                                                                              
                                                                                                                                               - La visión a largo plazo es construir una infraestructura abierta que pueda adaptarse a diferentes instituciones, niveles de atención y contextos sanitarios, comenzando con Ecuador como contexto de referencia.
                                                                                                                                              
                                                                                                                                               - ### 11. Estado del proyecto
                                                                                                                                              
                                                                                                                                               - **Fase actual: diseño y prototipo inicial.**
                                                                                                                                              
                                                                                                                                               - El proyecto se encuentra en una etapa temprana de desarrollo. No se afirma que existan usuarios institucionales, despliegues hospitalarios, convenios, integraciones o adopción oficial.
                                                                                                                                              
                                                                                                                                               - ### 12. Cómo contribuir
                                                                                                                                              
                                                                                                                                               - Puedes contribuir mediante desarrollo de software, diseño de interfaces, documentación técnica, investigación de procesos sanitarios, pruebas y control de calidad, revisión de arquitectura, propuestas de interoperabilidad, accesibilidad y experiencia de usuario.
                                                                                                                                              
                                                                                                                                               - Consulta CONTRIBUTING.md antes de enviar cambios.
                                                                                                                                              
                                                                                                                                               - ### 13. Licencia
                                                                                                                                              
                                                                                                                                               - Este proyecto se distribuye bajo la licencia MIT. Consulta el archivo LICENSE.
                                                                                                                                              
                                                                                                                                               - ### 14. Advertencia de uso
                                                                                                                                              
                                                                                                                                               - SALUD 360 ECUADOR es un proyecto tecnológico en desarrollo. No es un dispositivo médico, no proporciona diagnósticos, no realiza triaje clínico y no debe utilizarse para tomar decisiones sobre tratamientos o atención de emergencia.
                                                                                                                                              
                                                                                                                                               - El prototipo no debe gestionar pacientes reales ni procesar datos personales o de salud. Cualquier piloto requiere validación, autorización institucional, evaluación de seguridad, revisión legal y gobernanza apropiada.
                                                                                                                                              
                                                                                                                                               - ---
                                                                                                                                               
                                                                                                                                               ## ENGLISH
                                                                                                                                               
                                                                                                                                               ### About the project
                                                                                                                                               
                                                                                                                                               SALUD 360 ECUADOR is an open-source initiative focused on developing a digital platform for healthcare coordination and operational capacity management in Ecuador.
                                                                                                                                               
                                                                                                                                               The project explores modular tools for healthcare facility directories, appointment coordination, declared service availability, administrative referrals and operational analytics.
                                                                                                                                               
                                                                                                                                               Its long-term vision is to improve visibility and coordination between healthcare demand and available institutional capacity through open, scalable and interoperable technology.
                                                                                                                                               
                                                                                                                                               ### Mission
                                                                                                                                               
                                                                                                                                               To develop accessible and sustainable open-source technology that supports healthcare coordination, operational planning and the organization of health services.
                                                                                                                                               
                                                                                                                                               ### Current status
                                                                                                                                               
                                                                                                                                               Early design and prototype stage. No institutional deployment, official adoption or integration with MSP or IESS is currently implemented.
                                                                                                                                               
                                                                                                                                               ### Technology
                                                                                                                                               
                                                                                                                                               React · TypeScript · Python · FastAPI · PostgreSQL · Docker · REST APIs.
                                                                                                                                               
                                                                                                                                               ### Contributing
                                                                                                                                               
                                                                                                                                               Developers, healthcare professionals, researchers and students are welcome to contribute through software development, documentation, testing, research and technical review.
                                                                                                                                               
                                                                                                                                               ### License
                                                                                                                                               
                                                                                                                                               MIT License.
                                                                                                                                               
                                                                                                                                               ### Disclaimer
                                                                                                                                               
                                                                                                                                               This project is an experimental software initiative. It is not a medical device or clinical decision-support system. It must not be used to diagnose, triage, treat or manage real patients. Real-world deployment requires institutional authorization, security assessment, privacy and legal review, and appropriate governance.
                                                                                                                                               
                                                                                                                                               ---
                                                                                                                                               
                                                                                                                                               **SALUD 360 ECUADOR — Open technology for a better-connected healthcare system.**
                                                                                                                                               
