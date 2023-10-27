# Examen COD pt.1

## 1 Git Clone
Ejecuto los siguientes comandos:

En una carpeta nueva a la que llamo **examen** meto el clonado del repositorio.
`1. git clone -o rep_examen_cod https://github.com/damiancastelao/examenDAM.git`
Este comando lo que hace es que clona el contenido del repositorio a la ruta actual.
El parámetro *-o* le cambia el nombre al repositorio copiado al nombre que indiques.

## 2 Creación de un repositorio y modificación del README.md
Dentro de GitHub creo un repositorio al que llamo **"examen_cod_parte1"**.
Una vez creado, desde la consola ejecuto los siguientes comandos:
```
1. git init
Para inicializar el repositorio, modificar el README.md con 'nano README.md'.
```
Una vez iniciado el repositorio, lanzo el comando `nano README.md` para modificar el archivo
y que quede como está quedando ahora aplicando los diferentes metodos de escrituda típicos de los archivos.MD.

Ahora, ejecuto lo siguiente:
```
3. git add .
4. git commit -m "modificacion del readme"
5. git branch -M main
6. git remote add origin https://github.com/cod3stealer/wtgarg.git
7. git push -u origin main
```

## 3 Copia de programa al repositorio y otro commit
Ejecuto el comando `cp RotaPrograma RutaDelRepositorio`

Para terminar hago lo mismo que antes:
```
1. git add .
2. git commit -m "añadir programa al repo"
3. git push -u origin main  
```

