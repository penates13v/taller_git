# Respuestas del Taller de Git

### 1. ¿Qué carpeta nueva creó Git en el proyecto?
[cite_start]Al ejecutar el comando de inicialización, Git crea una carpeta oculta llamada **`.git`**[cite: 37]. Aquí es donde se almacena todo el historial y la configuración del repositorio.

### 2. ¿El menú aparece en esta rama (main)?
[cite_start]No. Al volver a la rama `main` después de trabajar en `nueva-seccion`, el menú no aparece porque ese cambio solo existía en la rama secundaria hasta que se realizó la fusión (`merge`)[cite: 81, 84].

### 3. ¿Para qué sirve git init?
[cite_start]Sirve para inicializar un nuevo repositorio de Git en una carpeta existente[cite: 31, 33, 91]. Transforma un directorio común en un proyecto versionado.

### 4. ¿Qué hace git add?
[cite_start]Este comando añade los cambios realizados en los archivos al "área de preparación" (*staging area*), indicándole a Git qué archivos queremos incluir en el próximo commit[cite: 39, 42, 92].

### 5. ¿Qué guarda un commit?
[cite_start]Un commit guarda una "captura" o fotografía del estado de los archivos en un momento específico[cite: 45, 93]. Incluye un mensaje descriptivo, el autor y la fecha.

### 6. ¿Para qué sirven las ramas en Git?
[cite_start]Sirven para trabajar en diferentes funcionalidades, experimentos o correcciones de forma aislada sin afectar la línea de código principal (`main`)[cite: 67, 94].