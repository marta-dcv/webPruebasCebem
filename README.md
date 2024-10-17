
# GIT
## Convertir tu proyecto en un proyecto controlado por **git**
```
git init
```

## Configurar Git *correctamente*
```
git config --global user.email "marta.decastr9@gmail.com"
git config --global user.name "marta-dcv"
```

## Prepara los cambios para ser añadidos al repositorio
```
git add .
```

## Guarda los cambios en el repositorio local
```
git commit -m "creo la página web inicial"
```

## Conecta el repositiorio local con el repositorio remoto
```
git remote add origin https://github.com/marta-dcv/webpruebacebem.git
```

## Sube los cambios que tienes en local a el repositorio remoto
```
git push -u origin main
```