# 📄 Planeación del Sistema

## Desglose de trabajo: Épicas, Historias de Usuario y Tareas

La implementación de los requerimientos identificados de TechCup se desglosa de la siguiente manera:

### 1. Épica: Implementar el Sistema de Autenticación y Gestión de Acceso de Usuarios

| Campo | Descripción |
|------|-------------|
| **ID** | EP-01 |
| **Título** | Sistema de Autenticación y Gestión de Acceso de Usuarios |
| **Descripción** | *Esta epica es requerida con gran prioridad por TechCup, dado que justamente es lo primero que hace, ve y busca un usuario, ya que para que un usuario empiece a utilizar la aplicacion este debe de estar registrado dentro de la misma, y ademas iniciar sesion para poder acceder a todas las funcionalidades disponibles segun su rol, por lo que es una funcionalidad indispensable que debe de ser la primera epica y el primer paso para crear la aplicacion, dado que es una aplicacion enfocada y motivada por usuarios dentro de la universidad interesados en los torneos de futbol.* |
| **Stakeholder** | *El principal StakeHolder de esta epica son los mismos usuarios, que esten interesados en los torneos de futbol dentro de la universidad, ya sea por seguir el evento o por participar en el mismo, y otro StakeHolder seria el cliente que solicita la creacion de la aplicacion, dado que este requiere no solo obtener el producto final, sino hacer un seguimiento continuo del mismo para estar satisfecho con el resultado y decisiones actuales del equipo Scrum.* |

### 2. Historias de usuario:

| Campo | Descripción |
|-------|-------------|
| **ID** | HU-01 |
| **Título** | Registrar Al Estudiante |
| **Descripción** | *COMO Estudiante QUIERO registrarme PARA PODER tener un usuario con el que logearme y acceder a las funcionalidades de Estudiante.* |
| **Prioridad** | *Alta* |
| **Estimación** | *5* |
| **Justificación** | *La prioridad es alta debido a que consideramos que es util para el proyecto, dado que es uno de los usuarios principales, y requerimos verificar, que este se registre correctamente como un estudiante y que pueda acceder a su interfaz y funcionalidades como estudiante una vez inicia sesion, y colocamos una estimacion de 5 dado que creemos que el equipo debe de realizar una corta investigacion de como se hace un registro y se conecta con la interfaz y base de datos, y no requiere una logica compleja.* |

| Campo | Descripción |
|-------|-------------|
| **ID** | HU-02 |
| **Título** | Registrar Al Capitan |
| **Descripción** | *COMO Capitan QUIERO registrarme PARA PODER tener un usuario con el que logearme y acceder a las funcionalidades de Capitan.* |
| **Prioridad** | *Alta* |
| **Estimación** | *3* |
| **Justificación** | *La prioridad es alta debido a que consideramos que es util para el proyecto, dado que es uno de los usuarios principales, y requerimos verificar, que este se registre correctamente como un capitan y que pueda acceder a su interfaz y funcionalidades como capitan una vez inicia sesion, y colocamos una estimacion de 3 dado que suponemos que creamos primeramente el registro del estudiante, esta primera funcionalidad, nos da la experiencia y conocimiento para realizar un proceso igual o similar con el registro del capitan.* |

| Campo | Descripción |
|-------|-------------|
| **ID** | HU-03 |
| **Título** | Registrar Al Organizador |
| **Descripción** | *COMO Organizador QUIERO registrarme PARA PODER tener un usuario con el que logearme y acceder a las funcionalidades de Organizador.* |
| **Prioridad** | *Alta* |
| **Estimación** | *3* |
| **Justificación** | *La prioridad es alta debido a que consideramos que es util para el proyecto, dado que es uno de los usuarios principales, y requerimos verificar, que este se registre correctamente como un organizador y que pueda acceder a su interfaz y funcionalidades como organizador una vez inicia sesion, y colocamos una estimacion de 3 dado que suponemos que creamos primeramente el registro del estudiante, esta primera funcionalidad, nos da la experiencia y conocimiento para realizar un proceso igual o similar con el registro del organizador.* |

| Campo | Descripción |
|-------|-------------|
| **ID** | HU-04 |
| **Título** | Autenticar Las Credenciales Del Estudiante |
| **Descripción** | *COMO Estudiante QUIERO iniciar sesion en la aplicacion PARA PODER acceder a las funcionalidades de Estudiante.* |
| **Prioridad** | *Alta* |
| **Estimación** | *5* |
| **Justificación** | *La prioridad es alta debido a que consideramos que es util para el proyecto, dado que es uno de los usuarios principales, y requerimos verificar, que este inicie sesion correctamente como un estudiante y que pueda acceder a su interfaz y funcionalidades como estudiante, y colocamos una estimacion de 5 dado que creemos que el equipo debe de realizar una corta investigacion de como se hace un inicio de sesion y se conecta con la interfaz y base de datos, y no requiere una logica compleja.* |

| Campo | Descripción |
|-------|-------------|
| **ID** | HU-05 |
| **Título** | Autenticar Las Credenciales Del Capitan |
| **Descripción** | *COMO Capitan QUIERO iniciar sesion en la aplicacion PARA PODER acceder a las funcionalidades de Capitan.* |
| **Prioridad** | *Alta* |
| **Estimación** | *3* |
| **Justificación** | *La prioridad es alta debido a que consideramos que es util para el proyecto, dado que es uno de los usuarios principales, y requerimos verificar, que este inicie sesion correctamente como un capitan y que pueda acceder a su interfaz y funcionalidades como capitan, y colocamos una estimacion de 3 dado que suponemos que creamos primeramente el inicio de sesion del estudiante, esta primera funcionalidad, nos da la experiencia y conocimiento para realizar un proceso igual o similar con el inicio de sesion del capitan.* |

| Campo | Descripción |
|-------|-------------|
| **ID** | HU-06 |
| **Título** | Autenticar Las Credenciales Del Organizador |
| **Descripción** | *COMO Organizador QUIERO iniciar sesion en la aplicacion PARA PODER acceder a las funcionalidades de Organizador.* |
| **Prioridad** | *Alta* |
| **Estimación** | *3* |
| **Justificación** | *La prioridad es alta debido a que consideramos que es util para el proyecto, dado que es uno de los usuarios principales, y requerimos verificar, que este inicie sesion correctamente como un organizador y que pueda acceder a su interfaz y funcionalidades como organizador, y colocamos una estimacion de 3 dado que suponemos que creamos primeramente el inicio de sesion del estudiante, esta primera funcionalidad, nos da la experiencia y conocimiento para realizar un proceso igual o similar con el inicio de sesion del organizador.* |

### 3. Tareas:

| Campo | Descripción |
|------|-------------|
| **ID** | TR-01 |
| **Título** | Crear el registro para el Estudiante |
| **ID de la Historia de Uso asociada** | HU-01 |
| **Descripción** | *Diseñar y programar el sistema de registro para el estudiante.* |
| **Tareas requisito** | *Ninguna* |

| Campo | Descripción |
|------|-------------|
| **ID** | TR-02 |
| **Título** | Establecer y añadir reglas para el registro del Estudiante |
| **ID de la Historia de Uso asociada** | HU-01 |
| **Descripción** | *Establecer y añadir las reglas para el registro del estudiante.* |
| **Tareas requisito** | *TR-01* |

| Campo | Descripción |
|------|-------------|
| **ID** | TR-03 |
| **Título** | Crear el registro para el Capitan |
| **ID de la Historia de Uso asociada** | HU-02 |
| **Descripción** | *Diseñar y programar el sistema de registro para el capitan.* |
| **Tareas requisito** | *Ninguna* |

| Campo | Descripción |
|------|-------------|
| **ID** | TR-04 |
| **Título** | Establecer y añadir reglas para el registro del Capitan |
| **ID de la Historia de Uso asociada** | HU-02 |
| **Descripción** | *Establecer y añadir las reglas para el registro del capitan.* |
| **Tareas requisito** | *TR-03* |

| Campo | Descripción                                                       |
|------|-------------------------------------------------------------------|
| **ID** | TR-05                                                             |
| **Título** | Crear el registro para el Organizador                             |
| **ID de la Historia de Uso asociada** | HU-03                                                             |
| **Descripción** | *Diseñar y programar el sistema de registro para el organizador.* |
| **Tareas requisito** | *Ninguna*                                                         |

| Campo | Descripción |
|------|-------------|
| **ID** | TR-06 |
| **Título** | Establecer y añadir reglas para el registro del Organizador |
| **ID de la Historia de Uso asociada** | HU-03 |
| **Descripción** | *Establecer y añadir las reglas para el registro del organizador.* |
| **Tareas requisito** | *TR-05* |

| Campo | Descripción |
|------|-------------|
| **ID** | TR-07 |
| **Título** | Crear el inicio de sesion para el Estudiante|
| **ID de la Historia de Uso asociada** | HU-04 |
| **Descripción** | *Diseñar y programar el sistema de inicio de sesion para el estudiante.* |
| **Tareas requisito** | *TR-01 y TR-02* |

| Campo | Descripción |
|------|-------------|
| **ID** | TR-08 |
| **Título** | Crear el inicio de sesion para el Capitan|
| **ID de la Historia de Uso asociada** | HU-05 |
| **Descripción** | *Diseñar y programar el sistema de inicio de sesion para el capitan.* |
| **Tareas requisito** | *TR-03 y TR-04* |

| Campo | Descripción |
|------|-------------|
| **ID** | TR-09 |
| **Título** | Crear el inicio de sesion para el Organizador|
| **ID de la Historia de Uso asociada** | HU-06 |
| **Descripción** | *Diseñar y programar el sistema de inicio de sesion para el organizador.* |
| **Tareas requisito** | *TR-05 y TR-06* |

| Campo | Descripción |
|------|-------------|
| **ID** | TR-10 |
| **Título** | Crear la interfaz de Registro de Usuario|
| **ID de la Historia de Uso asociada** | HU-01, HU-02, HU-03 |
| **Descripción** | *Diseñar y programar la interfaz de registro para los usuarios.* |
| **Tareas requisito** | *Ninguna* |

| Campo | Descripción |
|------|-------------|
| **ID** | TR-11 |
| **Título** | Crear la interfaz de Inicio de Sesion|
| **ID de la Historia de Uso asociada** | HU-04, HU-05, HU-06 |
| **Descripción** | *Diseñar y programar la interfaz de inicio de sesion para los usuarios.* |
| **Tareas requisito** | *Ninguna* |