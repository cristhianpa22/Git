# Git
Comandos principales para el funcionamiento de git
comandos de configuracion 

git --version :nos sirve para seber si esta bien instalada y conocer la version de git
<img width="415" height="85" alt="image" src="https://github.com/user-attachments/assets/85980942-507e-4579-8479-f74b8638fe7d" />

git config --global user.name: nos sirve para cofigurar el nombre de usuario en git 
<img width="576" height="67" alt="image" src="https://github.com/user-attachments/assets/cd6f8615-5bfe-4983-b2e5-42d0d3b2f1df" />

git config --global user.email: nos sirve para cofigurar nuestro correo como prdeterminado en git
<img width="791" height="61" alt="image" src="https://github.com/user-attachments/assets/bd0d5135-a06d-472c-b4fe-7dec7b26862d" />

git config --global core.editor "code --wait": configurar nuestro esitor de texto en git
<img width="590" height="59" alt="image" src="https://github.com/user-attachments/assets/17cee4f4-e25b-4a22-bb75-582f9f8838f6" />
git config --global -e: nos sirve para ver la hoja de configuracion de git en el editor de texto

<img width="714" height="136" alt="image" src="https://github.com/user-attachments/assets/e46ae9ed-f175-490a-b0a5-b5bb2104f419" />

<img width="865" height="335" alt="image" src="https://github.com/user-attachments/assets/af0d1016-e785-4227-a82c-e30b0cb8538d" />

git config --global core.autocrlf true:
nos sirve para configuarar los saltos en linea segun el sistema operativo en el que nos encontremos 
-para windows es true
-para mac y linux es input 
<img width="418" height="65" alt="image" src="https://github.com/user-attachments/assets/e9ed3ce8-265e-4d34-905f-1e88182ffe61" />

git config -h:
nos da un listado de la configuraciones que se les pueden aplicar al git
<img width="912" height="233" alt="image" src="https://github.com/user-attachments/assets/4f1be4f3-00b4-4b75-971b-fcac89842af8" />

comandos de git
ls:nos permite ver un liitado de archivos o carpetas que se encuentran en la carpeta que estamos
<img width="598" height="101" alt="image" src="https://github.com/user-attachments/assets/d2a414da-ac5d-435a-be88-e766fa2c28df" />

pwd: conocer el directorio en el que nos encontramos
<img width="593" height="77" alt="image" src="https://github.com/user-attachments/assets/b204b631-ae8a-40ec-8971-874f78af2339" />

cd: entrar a una carpeta o dirigirte a una carpeta 
<img width="666" height="67" alt="image" src="https://github.com/user-attachments/assets/eca9c5de-8d30-47f9-aa07-06caba00de08" />

cd ..: salir de la carpeta actual y entrar a la anterior
<img width="760" height="118" alt="image" src="https://github.com/user-attachments/assets/1187571f-efea-412f-8efc-72cfa59003b4" />

mkdir miweb:crear una nueva carpeta dentro de la carpeta en la que nos encontramos 
<img width="705" height="125" alt="image" src="https://github.com/user-attachments/assets/3f3a69e3-0ed8-4450-be63-c5034d2debfe" />

git init: iniciar un nuevo reposotorio vacio en git
<img width="884" height="74" alt="image" src="https://github.com/user-attachments/assets/99905316-43fa-4afc-bbb6-2dadbeb14374" />

ls -a:muestra es listado de todos los arhivos incluyendo los que se encuentren ocultos 
<img width="820" height="71" alt="image" src="https://github.com/user-attachments/assets/42295563-1ffe-43a1-aeab-ec77827fce30" />

code .: abre el repositorio en el editor de texto
<img width="840" height="47" alt="image" src="https://github.com/user-attachments/assets/75f5a216-be63-4ee9-8c1c-f95afd1186d2" />

git add: agrega los archivos al usntage
<img width="887" height="52" alt="image" src="https://github.com/user-attachments/assets/f2fa379a-f29a-4062-9f65-e86f951e9c4c" />

opcion 1
Git status: nos sirve para ver el estado actual del repositorio 
<img width="813" height="201" alt="image" src="https://github.com/user-attachments/assets/de0252d4-dc35-4a72-bc90-5815f58742df" />
opcion 2
git status -s
<img width="802" height="932" alt="image" src="https://github.com/user-attachments/assets/ef8a1ffe-c493-46e2-995e-17e41643e0db" />


<img width="769" height="543" alt="image" src="https://github.com/user-attachments/assets/ecf10831-21c9-4016-a08d-2cceca977cd4" />

opcion 1
git commit -m: enviar los archivos al repositorio y se escribe que se hace
<img width="867" height="121" alt="image" src="https://github.com/user-attachments/assets/6a36442c-3bc5-4658-9b6b-64c65c7143b2" />
opcion 2 
git commit
<img width="698" height="451" alt="image" src="https://github.com/user-attachments/assets/190d07c7-ff7a-4a93-bc32-456f4d3edcff" />

<img width="838" height="306" alt="image" src="https://github.com/user-attachments/assets/bb8b7a22-a618-413f-8322-4ba7b372d04e" />

elimina un arhivo del repositorio se debe agregar a la etapa de unstage para su eliminacion 
opcion 1
rm: 
<img width="772" height="666" alt="image" src="https://github.com/user-attachments/assets/22f663de-4fb8-4616-ada4-418e74ef0bb5" />
opcion 2 
git rm 
<img width="830" height="201" alt="image" src="https://github.com/user-attachments/assets/931f9464-8ee7-42c6-8fc9-93481ed5cd76" />

 git restore --staged  archivo1.txt: desahacer un cambio que se pase a la etapa de staged 
<img width="876" height="228" alt="image" src="https://github.com/user-attachments/assets/68b611d2-d30a-4890-aa70-48beaaa8fd69" />

 git restore:recuperar un archivo eliminado
 <img width="815" height="267" alt="image" src="https://github.com/user-attachments/assets/9acc5841-42b0-4f2f-8e69-86a4adab916a" />
ocion 1
mv: mover un archivo o cambiar el nombre
<img width="834" height="384" alt="image" src="https://github.com/user-attachments/assets/ee3da345-30da-4161-9767-84622d772f22" />

<img width="893" height="189" alt="image" src="https://github.com/user-attachments/assets/5c69b246-c809-4504-bab2-c80ea0938c83" />

<img width="892" height="120" alt="image" src="https://github.com/user-attachments/assets/64d4eea3-b0dd-40ef-8729-3dd5ac2ddc93" />
opcion 2
git mv 
<img width="892" height="120" alt="image" src="https://github.com/user-attachments/assets/12388e66-df5e-4cbc-81e1-edf9c4ec5f2b" />

nos sirve para ignorar archivos y nunca se suban al repositorio
<img width="824" height="143" alt="image" src="https://github.com/user-attachments/assets/242a2c70-358d-49d9-b9db-ce08700c1a73" />
<img width="770" height="451" alt="image" src="https://github.com/user-attachments/assets/53c64725-ee04-466d-9327-4e466ab8686a" />

gitt diff: ver los cambios mas visualmente 
<img width="836" height="419" alt="image" src="https://github.com/user-attachments/assets/6f602988-93f4-4d5e-bacf-750ae3d092ae" />

git diff -staged: muestra todos los cambios que se encunetran en la estapa de staged
<img width="774" height="239" alt="image" src="https://github.com/user-attachments/assets/2899025a-b86f-4fe4-9eb1-6546abd12250" />

opcion 1
git log: revisar el historial de todo el repositorio
<img width="821" height="726" alt="image" src="https://github.com/user-attachments/assets/9f1f7e36-581a-4092-adc4-03e8061b1119" />

opcion 2
 git log --oneline
<img width="842" height="202" alt="image" src="https://github.com/user-attachments/assets/c9d8057f-90a4-4352-ba56-bdbd4087edf3" />

git branch: nos permite observar en que rama de trabajo nos encontramos
<img width="903" height="82" alt="image" src="https://github.com/user-attachments/assets/a6e8ad49-4984-4202-ad1b-8ba091d7e36f" />

git checkout -b:nos permite crear una rama nueva 
<img width="895" height="88" alt="image" src="https://github.com/user-attachments/assets/e9cdd81d-d0f3-43bb-bde2-a21aa1d783fa" />
<img width="756" height="198" alt="image" src="https://github.com/user-attachments/assets/aab338f0-1d84-4d10-966a-91fe4b433957" />

cat: mostrara el contenido del archivo 
<img width="898" height="84" alt="image" src="https://github.com/user-attachments/assets/1073a9ef-2c89-434f-b4bc-7c6dff934372" />
<img width="908" height="138" alt="image" src="https://github.com/user-attachments/assets/f39674aa-c0c3-45d3-b16c-e0dc529974a7" />

 git marge :traer cambio de una rama a otra 
<img width="825" height="178" alt="image" src="https://github.com/user-attachments/assets/b87c7bd4-eecb-4111-a23a-aaa0f92ff670" />
























