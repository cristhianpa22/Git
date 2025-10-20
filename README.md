# Git
Comandos principales para el funcionamiento de git

comandos de configuracion 

Estos comandos se utilizan para establecer las preferencias de Git a nivel global

git --version:Muestra la versión de Git instalada, útil para verificar la instalación.

<img width="415" height="85" alt="image" src="https://github.com/user-attachments/assets/85980942-507e-4579-8479-f74b8638fe7d" />

git config --global user.name: Configura el nombre de usuario que se asociará a tus commits a nivel global.

<img width="576" height="67" alt="image" src="https://github.com/user-attachments/assets/cd6f8615-5bfe-4983-b2e5-42d0d3b2f1df" />

git config --global user.email: Configura la dirección de correo electrónico para tus commits a nivel global.

<img width="791" height="61" alt="image" src="https://github.com/user-attachments/assets/bd0d5135-a06d-472c-b4fe-7dec7b26862d" />

git config --global core.editor "code --wait": Configura el editor de texto predeterminado de Git (VS Code). El "--wait" es crucial para que Git espere a que cierres el editor.

<img width="590" height="59" alt="image" src="https://github.com/user-attachments/assets/17cee4f4-e25b-4a22-bb75-582f9f8838f6" />

git config --global -e: Abre el archivo de configuración global de Git en el editor de texto configurado para ver o modificar todas las opciones.

<img width="714" height="136" alt="image" src="https://github.com/user-attachments/assets/e46ae9ed-f175-490a-b0a5-b5bb2104f419" />

<img width="865" height="335" alt="image" src="https://github.com/user-attachments/assets/af0d1016-e785-4227-a82c-e30b0cb8538d" />

git config --global core.autocrlf true:
Configura el manejo de saltos de línea (CRLF vs. LF) para evitar problemas de compatibilidad entre sistemas operativos. Usa true para Windows y input para macOS/Linux.

<img width="418" height="65" alt="image" src="https://github.com/user-attachments/assets/e9ed3ce8-265e-4d34-905f-1e88182ffe61" />

git config -h:
Muestra una ayuda detallada y un listado de las configuraciones que se pueden aplicar a Git.

<img width="912" height="233" alt="image" src="https://github.com/user-attachments/assets/4f1be4f3-00b4-4b75-971b-fcac89842af8" />

Comandos Básicos del Terminal
son fundamentales para navegar y gestionar archivos en la terminal.


ls: Lista los archivos y carpetas del directorio actual.

<img width="598" height="101" alt="image" src="https://github.com/user-attachments/assets/d2a414da-ac5d-435a-be88-e766fa2c28df" />

ls -a:Lista todos los archivos de la carpeta, incluyendo los ocultos (como la carpeta .git).

<img width="820" height="71" alt="image" src="https://github.com/user-attachments/assets/42295563-1ffe-43a1-aeab-ec77827fce30" />

pwd: Muestra la carpeta de trabajo actual.

<img width="593" height="77" alt="image" src="https://github.com/user-attachments/assets/b204b631-ae8a-40ec-8971-874f78af2339" />

cd nombre_carpeta: Cambia de carpeta para entrar en una carpeta específica.

<img width="666" height="67" alt="image" src="https://github.com/user-attachments/assets/eca9c5de-8d30-47f9-aa07-06caba00de08" />

cd ..: sale de la carpeta actual y vuelve a la anterior.
<img width="760" height="118" alt="image" src="https://github.com/user-attachments/assets/1187571f-efea-412f-8efc-72cfa59003b4" />

mkdir nombre_carpeta: Crea una nueva carpeta dentro del directorio actual.

<img width="705" height="125" alt="image" src="https://github.com/user-attachments/assets/3f3a69e3-0ed8-4450-be63-c5034d2debfe" />

code .: Abre el directorio actual en el editor de texto configurado.

<img width="840" height="47" alt="image" src="https://github.com/user-attachments/assets/75f5a216-be63-4ee9-8c1c-f95afd1186d2" />

cat nombre_archivo: Muestra el contenido de un archivo de texto directamente en la terminal.

<img width="898" height="84" alt="image" src="https://github.com/user-attachments/assets/1073a9ef-2c89-434f-b4bc-7c6dff934372" />

<img width="908" height="138" alt="image" src="https://github.com/user-attachments/assets/f39674aa-c0c3-45d3-b16c-e0dc529974a7" />

Eliminar

opción 1
rm nombre_archivo: Elimina un archivo del sistema de archivos

<img width="772" height="666" alt="image" src="https://github.com/user-attachments/assets/22f663de-4fb8-4616-ada4-418e74ef0bb5" />

opción 2 
git rm nombre_archivo: Elimina un archivo del directorio de trabajo y lo agrega al Staging Area para que la eliminación quede registrada en el próximo commit.

<img width="830" height="201" alt="image" src="https://github.com/user-attachments/assets/931f9464-8ee7-42c6-8fc9-93481ed5cd76" />

Mover o renombrar

opción 1
mv archivo_viejo a archivo_nuevo: Mueve o renombra un archivo.

<img width="834" height="384" alt="image" src="https://github.com/user-attachments/assets/ee3da345-30da-4161-9767-84622d772f22" />

<img width="893" height="189" alt="image" src="https://github.com/user-attachments/assets/5c69b246-c809-4504-bab2-c80ea0938c83" />

<img width="892" height="120" alt="image" src="https://github.com/user-attachments/assets/64d4eea3-b0dd-40ef-8729-3dd5ac2ddc93" />

opción 2

git mv nombre_viejo nombre_nuevo: Renombra un archivo y registra el cambio automáticamente en el Staging Area para el próximo commit.

<img width="892" height="120" alt="image" src="https://github.com/user-attachments/assets/12388e66-df5e-4cbc-81e1-edf9c4ec5f2b" />


Comaandos de Inicialización

git init: Inicializa un nuevo repositorio de Git vacío en la carpeta actual.

<img width="884" height="74" alt="image" src="https://github.com/user-attachments/assets/99905316-43fa-4afc-bbb6-2dadbeb14374" />

Mostrar el estado actual de el respositorio.

opción 1

Git status: nos sirve para ver el estado actual del repositorio. 
<img width="813" height="201" alt="image" src="https://github.com/user-attachments/assets/de0252d4-dc35-4a72-bc90-5815f58742df" />

opción 2

git status -s : Muestra el estado de forma concisa

<img width="802" height="932" alt="image" src="https://github.com/user-attachments/assets/ef8a1ffe-c493-46e2-995e-17e41643e0db" />


Área de Staging

git add nombre_archivo: Agrega un archivo modificado o nuevo al Staging Area.

<img width="887" height="52" alt="image" src="https://github.com/user-attachments/assets/f2fa379a-f29a-4062-9f65-e86f951e9c4c" />

git add .: Agrega todos los archivos modificados o nuevos al Staging Area.

<img width="769" height="543" alt="image" src="https://github.com/user-attachments/assets/ecf10831-21c9-4016-a08d-2cceca977cd4" />

gitt diff: Muestra las diferencias entre el directorio de trabajo y el área de staging (cambios sin agregar).

<img width="836" height="419" alt="image" src="https://github.com/user-attachments/assets/6f602988-93f4-4d5e-bacf-750ae3d092ae" />

git diff -staged: Muestra las diferencias entre el área de staging y el último commit (cambios listos para commit).

<img width="774" height="239" alt="image" src="https://github.com/user-attachments/assets/2899025a-b86f-4fe4-9eb1-6546abd12250" />

git restore --staged  nombre_archivo: Deshace la adición de un archivo del Staging Area, devolviéndolo al directorio de trabajo (sin eliminar los cambios).

<img width="876" height="228" alt="image" src="https://github.com/user-attachments/assets/68b611d2-d30a-4890-aa70-48beaaa8fd69" />

 git restore nombre_archivo: recuperar un archivo eliminado.
 
 <img width="815" height="267" alt="image" src="https://github.com/user-attachments/assets/9acc5841-42b0-4f2f-8e69-86a4adab916a" />


Commits

git commit -m "Mensaje descriptivo": Guarda los cambios que están en el Staging Area de forma permanente en el historial del repositorio con un mensaje.

<img width="867" height="121" alt="image" src="https://github.com/user-attachments/assets/6a36442c-3bc5-4658-9b6b-64c65c7143b2" />

git commit: Abre el editor de texto para escribir un mensaje de commit más detallado.

<img width="698" height="451" alt="image" src="https://github.com/user-attachments/assets/190d07c7-ff7a-4a93-bc32-456f4d3edcff" />

<img width="838" height="306" alt="image" src="https://github.com/user-attachments/assets/bb8b7a22-a618-413f-8322-4ba7b372d04e" />

git log: Muestra el historial de commits del repositorio (autor, fecha, mensaje, hash).

<img width="821" height="726" alt="image" src="https://github.com/user-attachments/assets/9f1f7e36-581a-4092-adc4-03e8061b1119" />

 git log --oneline: Muestra el historial de commits de forma compacta.
 
<img width="842" height="202" alt="image" src="https://github.com/user-attachments/assets/c9d8057f-90a4-4352-ba56-bdbd4087edf3" />


Ramas

git branch: Lista las ramas existentes y muestra en cuál te encuentras actualmente.

<img width="903" height="82" alt="image" src="https://github.com/user-attachments/assets/a6e8ad49-4984-4202-ad1b-8ba091d7e36f" />

git checkout -b nombre_rama: Crea una rama nueva y cambia inmediatamente a ella.

<img width="895" height="88" alt="image" src="https://github.com/user-attachments/assets/e9cdd81d-d0f3-43bb-bde2-a21aa1d783fa" />

<img width="756" height="198" alt="image" src="https://github.com/user-attachments/assets/aab338f0-1d84-4d10-966a-91fe4b433957" />

git marge nombre_rama: Integra los cambios una rama a la rama actual.
 
<img width="825" height="178" alt="image" src="https://github.com/user-attachments/assets/b87c7bd4-eecb-4111-a23a-aaa0f92ff670" />


Comandos de Repositorios Remotos

git remote add origin URL_remota: Añade una URL remota a tu repositorio local.

<img width="814" height="63" alt="image" src="https://github.com/user-attachments/assets/3a84cdab-b18a-4a63-a7fe-33a441a87370" />

git push -u origin main: Sube los commits locales a la rama main del repositorio remoto.

<img width="833" height="296" alt="image" src="https://github.com/user-attachments/assets/af6eeb61-e225-431f-ba7a-92c1ade9d1c5" />

.gitignore: Archivo donde se listan los patrones de archivos/carpetas a ignorar para que Git nunca les dé seguimiento ni te pregunte por ellos.

<img width="824" height="143" alt="image" src="https://github.com/user-attachments/assets/242a2c70-358d-49d9-b9db-ce08700c1a73" />

<img width="770" height="451" alt="image" src="https://github.com/user-attachments/assets/53c64725-ee04-466d-9327-4e466ab8686a" />

git clone URL_del_repositorio: escarga un repositorio existente desde una URL remota a tu máquina local. Git crea automáticamente un directorio con el nombre del proyecto.

<img width="669" height="179" alt="image" src="https://github.com/user-attachments/assets/83afcab6-f09d-449b-82b1-f1516790093a" />








































