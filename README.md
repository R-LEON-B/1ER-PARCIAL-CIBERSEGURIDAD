
# 1ER-PARCIAL-CIBERSEGURIDAD🦁
Parte Conceptual 🧐

1xResponda las siguientes preguntas a continuación:

1_¿Qué es la ciberseguridad?, ¿Cuales son sus características? Y ¿usted cómo lo ve
reflejado en su vida personal?

RTA/ La ciberseguridad es el conjunto de técnicas, herramientas y prácticas para proteger sistemas, redes, programas, dispositivos y datos de ataques digitales.
CARACTERSITICAS: Confidencialidad,  Integridad,  Disponibilidad, Autenticación y Autorización,  No repudio, Resiliencia y Prevención.

2_¿Cuál es el objetivo de la triada de seguridad? Y ¿Cuál sería la función en un estándar
como el EMV usado en tarjetas de crédito?

RTA/ Su objetivo es garantizar que la información sea: Confidencial, Íntegra, Disponible.
PASO 1: Iniciación de la transacción, PASO 2: Autenticación de la Tarjeta - ¿Es una tarjeta real?, PASO 3: Verificación del Titular - ¿Eres tú?, PASO 4: Autorización de la Transacción - El criptograma, PASO 5: Validación Online del Banco.

3_El pc de una compañía A esta funcionando de manera errónea desde que se descargó un
archivo X. ¿Qué debe hacer la empresa A para revisar si es un virus, un gusano o un
troyano?

RTA/ 1. AISLAR: Desconectar el PC de internet/red, pero no apagarlo.
2. ANALIZAR sin ejecutarlo:Subir el archivo X a VirusTotal.Escanear con antivirus.
3. IDENTIFICAR por el comportamiento.
4. ELIMINAR.

4_¿Cuál es la diferencia entre un hacker de sombrero negro, un hacker de sombrero blanco, un hacker de sombrero gris y un cracker?

RTA/ 
<table>
  <thead>
    <tr>
      <th>TIPO DE HACKER</th>
      <th>DEFINICIÓN</th>
      <th>OBJETIVO</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>SOMBRERO BLANCO</td>
      <td>Es el hacker ético. Es un profesional de ciberseguridad con altos conocimientos técnicos que usa sus habilidades con autorización por escrito de la empresa.</td>
      <td>Su objetivo es defender. Encontrar las fallas antes que los criminales para cerrarlas y evitar que la empresa sea atacada.</td>
    </tr>
    <tr>
      <td>SOMBRERO NEGRO</td>
      <td>Es el ciberdelincuente. Tiene el mismo conocimiento que el blanco, pero lo usa sin permiso y con fines maliciosos.</td>
      <td>Su objetivo es ganar dinero o poder ilegalmente. Robar datos, pedir rescate, espiar o destruir.</td>
    </tr>
    <tr>
      <td>SOMBRERO GRIS</td>
      <td>Está entre los dos. No es un delincuente, pero tampoco es 100% ético. A veces actúa sin permiso, pero sin intención de hacer daño grave.</td>
      <td>Su objetivo es probar que puede hacerlo. Busca fama, curiosidad o que le paguen una recompensa por avisar de un fallo que encontró sin permiso.</td>
    <tr>
      <td>CRACKER</td>
      <td>Es el que se especializa en romper (to crack). No necesariamente entra a redes, su especialidad es romper la seguridad del software.</td>
      <td>Su objetivo es romper la protección de un programa para hacerlo gratis, modificarlo o distribuirlo ilegalmente.</td>
  </tbody>
</table>

5_¿Qué leyes nacionales e internacionales están orientadas a la ciberseguridad y el
habeas data?

RTA/ 
<table border="1" cellpadding="10" cellspacing="5" style="border-collapse: collapse; width: 100%; font-family: Arial; font-size: 14px;">
  <thead style="background-color: #0d1b2a; color: white;">
    <tr>
      <th>Ley / Norma</th>
      <th>Ámbito</th>
      <th>Año</th>
      <th>Objetivo Principal</th>
      <th>Qué Protege</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>Ley 1273</b></td>
      <td>Colombia - Nacional</td>
      <td>2009</td>
      <td>Delitos Informáticos</td>
      <td>Penas por acceso abusivo, virus, phishing y suplantación</td>
    </tr>
    <tr>
      <td><b>Ley 1581</b></td>
      <td>Colombia - Nacional</td>
      <td>2012</td>
      <td>Régimen General de Habeas Data</td>
      <td>Derecho a conocer, actualizar y rectificar datos personales</td>
    </tr>
    <tr>
      <td><b>Ley 1266</b></td>
      <td>Colombia - Nacional</td>
      <td>2008</td>
      <td>Habeas Data Financiero</td>
      <td>Datos crediticios en centrales de riesgo</td>
    </tr>
    <tr>
      <td><b>Decreto 1377</b></td>
      <td>Colombia - Nacional</td>
      <td>2013</td>
      <td>Reglamenta Ley 1581</td>
      <td>Cómo pedir autorización para uso de datos</td>
    </tr>
    <tr>
      <td><b>Ley 1928 / Convenio de Budapest</b></td>
      <td>Internacional</td>
      <td>2001 / 2018</td>
      <td>Cooperación contra ciberdelitos</td>
      <td>Unifica delitos informáticos en 68 países</td>
    </tr>
    <tr>
      <td><b>GDPR UE 2016/679</b></td>
      <td>Internacional - UE</td>
      <td>2016</td>
      <td>Protección de datos europea</td>
      <td>Datos de ciudadanos UE, aplica extraterritorialmente</td>
    </tr>
  </tbody>
</table>


Parte de Diseño🧬

2xPlantee una solución paso a paso de la situación descrita con lo aprendido en clase:

a_Necesita desarrollar una copia de seguridad en la nube y local, para ello va a usar herramientas como
git, github, donde desarrollará un ambiente compartido de trabajo para un proyecto.
Describir el paso a paso desde la creación del repositorio en github, luego la sincronización con git,
posteriormente la creación de la carpeta desde el terminal, con la creación y movimiento de archivos
para su posterior anexo y subida de información a github, para finalmente que el usuario 2 lo descargue
y lo use.

RTA/
1. Crear el repositorio en GitHub:

1_Ingresar a GitHub e iniciar sesión.

2_En la esquina superior derecha, seleccionar “+” → “New repository”.

3_Asignar un nombre al repositorio.

4_Seleccionar si el repositorio será:
Public: cualquier persona puede verlo.
Private: solamente usuarios autorizados podrán acceder.

5_Presionar “Create repository”.

2. Configurar Git en el computador:

Abrir el Terminal y comprobar que Git esté instalado: git --version

Si aparece algo similar a: git version 2.x.x
Git está instalado.

Luego configurar el nombre del usuario:
git config --global user.name "Nombre Usuario"

Y configurar el correo asociado a GitHub:
git config --global user.email "correo@ejemplo.com"

Se puede comprobar la configuración con:
git config --list

3. Crear una carpeta de trabajo desde el terminal:

Por ejemplo, ubicarse en la carpeta donde se desea almacenar el proyecto:
cd Documentos

Crear la carpeta:
mkdir proyecto-git

Entrar en ella:
cd proyecto-git

Ahora el terminal estará ubicado en:
Documentos/proyecto-git

4. Inicializar Git en la carpeta:

Dentro de la carpeta ejecutar:
git init

Git creará internamente una carpeta oculta llamada .git.
Esto convierte proyecto-git en un repositorio Git local.

Se puede comprobar el estado con:
git status.

5. Crear archivos desde el terminal:

Por ejemplo, crear un archivo de texto:
touch datos.txt

También se puede crear un archivo README:
touch README.md

La estructura podría quedar así:

proyecto-git/

├── datos.txt

└── README.md

Para agregar información a datos.txt, se puede abrir con un editor de texto o utilizar el terminal.

6. Crear carpetas y mover archivos

Crear una carpeta:
mkdir informacion

Mover datos.txt a esa carpeta:
mv datos.txt informacion/

La estructura ahora será:

proyecto-git/

├── informacion/

│   └── datos.txt

└── README.md

7. Conectar el repositorio local con GitHub

En la página del repositorio creado en GitHub aparecerá la opción para copiar su dirección.

Comprobar que quedó correctamente configurado:
git remote -v

Debería aparecer algo parecido a:

origin  https://github.com/USUARIO/proyecto-git.git (fetch)
origin  https://github.com/USUARIO/proyecto-git.git (push)

8. Agregar los archivos a Git

Primero comprobar qué archivos existen:
git status
Para agregar todos los archivos:
git add .
(El punto . significa agregar todos los archivos modificados o nuevos del directorio actual.)

Volver a comprobar:
git status

Los archivos deberían aparecer como preparados para realizar un commit.

9. Crear el primer commit:
Un commit es una versión o punto de control de los cambios realizados.

Ejecutar:
git commit -m "Agrega archivos iniciales del proyecto"

10. Subir la información a GitHub

Primero podemos verificar el nombre de la rama:
git branch

Si la rama se llama master y queremos utilizar main:
git branch -M main

Después subir el contenido:
git push -u origin main
(Git solicitará autenticación si es necesario.)

Después de completar el proceso, al actualizar la página del repositorio en GitHub aparecerán los archivos:

proyecto-git

├── informacion

│   ├── datos.txt

│   └── resultados.txt

└── README.md

11. Realizar nuevos cambios

Después de guardar los cambios:
git status
(Git mostrará que datos.txt fue modificado.)

Agregar el cambio:
git add datos.txt

Crear un nuevo commit:
git commit -m "Actualiza datos del proyecto"

Y finalmente subirlo:
git push

El flujo habitual para trabajar con Git será:
Modificar archivos
       ↓
   git status
       ↓
     git add
       ↓
   git commit
       ↓
    git push
       ↓
     GitHub

12. Dar acceso al Usuario 2

Repositorio público
Si el repositorio es público, el Usuario 2 puede descargarlo directamente.

Repositorio privado
Si el repositorio es privado, el Usuario 1 debe darle acceso al Usuario 2 desde la configuración del repositorio:

Settings → Collaborators → Add people

Se agrega la cuenta de GitHub del Usuario 2.

El Usuario 2 deberá aceptar la invitación.

13. Usuario 2 descarga el repositorio

El Usuario 2 abre el terminal y se ubica en el lugar donde quiere guardar el proyecto.
Por ejemplo:
cd Documentos

Después ejecuta:

git clone https://github.com/USUARIO/proyecto-git.git
(Git descargará todo el repositorio.)

Entrar en la carpeta:
cd proyecto-git

Comprobar los archivos:
ls

En Windows también puede utilizarse:
dir

El Usuario 2 tendrá ahora una copia local:

Computador Usuario 2

       │

       └── proyecto-git/
       
             ├── informacion/
             
             │     ├── datos.txt
             
             │     └── resultados.txt
             
             └── README.md

14. Usuario 2 utiliza la información
El Usuario 2 puede abrir, leer o procesar los archivos.

Por ejemplo:
cat informacion/datos.txt

También puede abrir el proyecto con un editor de código como Visual Studio Code:
code .

